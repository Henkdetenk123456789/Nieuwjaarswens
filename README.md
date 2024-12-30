<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nieuwjaarswens voor Mariska</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #000000; /* zwarte achtergrond */
            color: #d3d3d3; /* wit/grijze letters */
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
            font-size: 3em;
            color: #ffffff; /* witte letters voor de titel */
            margin-bottom: 0.5em;
            letter-spacing: 2px;
            text-transform: uppercase;
            animation: slideIn 1s ease-out;
        }

        p {
            font-size: 1.3em;
            line-height: 1.6;
            margin: 0.5em 0;
            color: #d3d3d3; /* wit/grijze tekst */
        }

        footer {
            font-size: 1.2em;
            color: #a9a9a9; /* lichtere grijze kleur voor de footer */
            margin-top: 2em;
            font-style: italic;
            animation: fadeIn 2s ease-in-out 1s; /* subtiele animatie voor footer */
        }

        strong {
            color: #e91e63; /* roze voor nadruk */
            font-weight: bold;
        }

        .container {
            background-color: rgba(255, 255, 255, 0.1); /* semi-transparante achtergrond */
            padding: 3em;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            max-width: 650px;
            width: 100%;
            text-align: center;
            animation: zoomIn 0.8s ease-out;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 1em 0;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
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
                font-size: 2.5em;
            }

            p {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Een speciale nieuwjaarswens voor Mariska</h1>
        <img src="URL_VAN_OUD_EN_NIEUW_AFBEELDING" alt="Oud en Nieuw">
        <p>Ik wens je iets goeds, iets lekkers, iets geks, iets aardigs, iets liefs en hoe dan ook iets positiefs.</p>
        <img src="URL_VAN_ZEEP_AFBEELDING" alt="Zeep">
        <p><strong>Gelukkig nieuwjaar!</strong></p>
        <img src="URL_VAN_HARDLOPEN_AFBEELDING" alt="Hardlopen">
        <footer>Met liefde gemaakt, speciaal voor jou.</footer>
    </div>
</body>
</html>
