<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nieuwjaarswens voor Mariska</title>
    <style>
        body {
            font-family: 'Georgia', serif; /* Dille & Kamille stijl */
            background-color: #f5f5f5; /* lichte achtergrondkleur */
            color: #333; /* donkere tekstkleur */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
            animation: fadeIn 2s ease-in-out; /* subtiele animatie bij laden */
        }

        h1 {
            font-size: 2.5em;
            color: #ffd700; /* gouden kleur voor de titel */
            margin-bottom: 0.5em;
            letter-spacing: 1px;
            text-transform: uppercase;
            animation: slideIn 1s ease-out;
        }

        p {
            font-size: 1.2em;
            line-height: 1.6;
            margin: 0.5em 0;
            color: #6b8e23; /* groene kleur voor de tekst */
        }

        footer {
            font-size: 1em;
            color: #888;
            margin-top: 2em;
            font-style: italic;
            animation: fadeIn 2s ease-in-out 1s; /* subtiele animatie voor footer */
        }

        strong {
            color: #ffd700; /* gouden kleur voor nadruk */
            font-weight: bold;
        }

        .container {
            background-color: #ffffff;
            padding: 2em;
            border-radius: 5px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            width: 100%;
            text-align: center;
            animation: zoomIn 0.8s ease-out;
        }

        /* Subtiele animaties */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(0);
            }
        }

        @keyframes zoomIn {
            0% {
                transform: scale(0.8);
                opacity: 0;
            }
            100% {
                transform: scale(1);
                opacity: 1;
            }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }

            p {
                font-size: 1em;
            }
        }

        /* Onzichtbare tekst */
        .hidden-text {
            color: #f5f5f5; /* zelfde kleur als de achtergrond */
        }

        /* Nieuwjaarsvuurpijl */
        .firework {
            position: absolute;
            bottom: 0;
            left: 50%;
            width: 5px;
            height: 100px;
            background-color: #ffd700;
            animation: launch 2s ease-in-out infinite;
        }

        @keyframes launch {
            0% {
                bottom: 0;
                opacity: 1;
            }
            80% {
                bottom: 80%;
                opacity: 1;
            }
            100% {
                bottom: 100%;
                opacity: 0;
            }
        }

        .explosion {
            position: absolute;
            bottom: 80%;
            left: 50%;
            width: 10px;
            height: 10px;
            background-color: #ffd700;
            border-radius: 50%;
            animation: explode 2s ease-in-out infinite;
        }

        @keyframes explode {
            0%, 80% {
                transform: scale(0);
                opacity: 0;
            }
            85% {
                transform: scale(1);
                opacity: 1;
            }
            100% {
                transform: scale(0);
                opacity: 0;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Een speciale nieuwjaarswens voor Mariska</h1>
        <p>Ik wens je iets goeds, iets lekkers, iets geks, iets aardigs, iets liefs en hoe dan ook iets positiefs.</p>
        <p><strong>Gelukkig nieuwjaar!</strong></p>
        <footer>Met liefde gemaakt, speciaal voor jou.</footer>
    </div>
    <div class="firework"></div>
    <div class="explosion"></div>
    <div class="hidden-text"><!DOCTYPE html></div>
</body>
</html>
