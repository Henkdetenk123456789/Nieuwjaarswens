<!-- <!DOCTYPE html> -->
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
            overflow: hidden; /* Verberg overloop voor animaties */
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

        /* Ballonnen */
        .balloon {
            position: absolute;
            bottom: -100px;
            width: 30px;
            height: 50px;
            background-color: #ffd700;
            border-radius: 50% 50% 50% 50%;
            animation: rise 5s ease-in-out infinite;
        }

        @keyframes rise {
            0% {
                bottom: -100px;
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                bottom: 100vh;
                opacity: 0;
            }
        }

        .balloon::before {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            width: 2px;
            height: 20px;
            background-color: #ffd700;
        }

        /* Vallende sterren */
        .shooting-star {
            position: absolute;
            top: -50px;
            width: 2px;
            height: 100px;
            background: linear-gradient(white, rgba(255, 255, 255, 0));
            animation: shoot 3s ease-in-out infinite;
        }

        @keyframes shoot {
            0% {
                transform: translateX(0) translateY(0);
                opacity: 1;
            }
            100% {
                transform: translateX(500px) translateY(500px);
                opacity: 0;
            }
        }

        /* Confetti */
        .confetti {
            position: absolute;
            top: 0;
            width: 10px;
            height: 10px;
            background-color: #ffd700;
            animation: fall 3s ease-in-out infinite;
        }

        @keyframes fall {
            0% {
                transform: translateY(0);
                opacity: 1;
            }
            100% {
                transform: translateY(100vh);
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
    <div class="balloon" style="left: 20%; animation-delay: 0s;"></div>
    <div class="balloon" style="left: 40%; animation-delay: 1s;"></div>
    <div class="balloon" style="left: 60%; animation-delay: 2s;"></div>
    <div class="balloon" style="left: 80%; animation-delay: 3s;"></div>
    <div class="shooting-star" style="left: 20%; animation-delay: 0s;"></div>
    <div class="shooting-star" style="left: 40%; animation-delay: 1s;"></div>
    <div class="shooting-star" style="left: 60%; animation-delay: 2s;"></div>
    <div class="shooting-star" style="left: 80%; animation-delay: 3s;"></div>
    <div class="confetti" style="left: 10%; animation-delay: 0s;"></div>
    <div class="confetti" style="left: 30%; animation-delay: 0.5s;"></div>
    <div class="confetti" style="left: 50%; animation-delay: 1s;"></div>
    <div class="confetti" style="left: 70%; animation-delay: 1.5s;"></div>
    <div class="confetti" style="left: 90%; animation-delay: 2s;"></div>
    <div class="hidden-text"><!-- <!DOCTYPE html> --></div>
</body>
</html>
