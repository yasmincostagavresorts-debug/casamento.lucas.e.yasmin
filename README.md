<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="robots" content="index, follow">
    <meta name="description" content="Site de casamento de Lucas e Yasmin - 25 de Fevereiro de 2026">
    <title>Lucas & Yasmin</title>

    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;600&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">

    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }

        body {
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, #e8ede7 0%, #d4ddd2 100%);
            color: #4a5447;
            overflow-x: hidden;
        }

        .container { max-width: 100%; margin: 0 auto; }

        .hero {
            background: linear-gradient(rgba(232,237,231,.95), rgba(232,237,231,.95)),
            url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 800"><rect fill="%23a8b5a1" width="1200" height="800"/></svg>');
            min-height: 100vh;
            display: flex; flex-direction: column; justify-content: center; align-items: center;
            text-align: center; padding: 40px 20px;
        }

        .save-the-date {
            font-size: 14px; letter-spacing: 4px; color: #7a8c6f; margin-bottom: 40px;
        }

        .names {
            font-family: 'Cormorant Garamond', serif;
            font-size: 72px; color: #4a5e3f; margin-bottom: 20px;
        }

        .ampersand { font-size: 48px; color: #7a8c6f; margin: 0 10px; }

        .date-box {
            border: 2px solid #a8b5a1;
            padding: 40px 60px;
            background: rgba(255,255,255,.6);
            margin: 30px 0;
        }

        .date-day { font-family: 'Cormorant Garamond', serif; font-size: 80px; color: #4a5e3f; }
        .date-month { font-size: 20px; letter-spacing: 3px; color: #7a8c6f; margin-top: 10px; }
        .date-year { font-family: 'Cormorant Garamond', serif; font-size: 36px; color: #4a5e3f; }

        .time { font-size: 24px; color: #7a8c6f; margin-top: 30px; letter-spacing: 2px; }

        .buttons-section {
            background: #fff;
            padding: 80px 20px;
            display: flex; flex-wrap: wrap; justify-content: center; gap: 30px;
        }

        .button-card { width: 280px; text-align: center; transition: .3s; }
        .button-card:hover { transform: translateY(-10px); }

        .icon-circle {
            width: 80px; height: 80px; border-radius: 50%;
            background: linear-gradient(135deg, #a8b5a1, #8fa182);
            display: flex; align-items: center; justify-content: center;
            margin: 0 auto 20px;
        }

        .icon-circle svg { width: 40px; height: 40px; fill: #fff; }

        .button-title {
            font-size: 12px; letter-spacing: 2px; color: #7a8c6f; margin-bottom: 15px;
        }

        .btn {
            padding: 15px 40px;
            background: #5d7052; color: #fff; text-decoration: none;
            border-radius: 30px; font-size: 13px; letter-spacing: 2px;
            display: inline-block;
        }

        .footer {
            background: #5d7052; color: #e8ede7;
            text-align: center; padding: 40px 20px;
            font-family: 'Cormorant Garamond', serif;
        }

        @media (max-width:768px){
            .names{font-size:48px;}
            .date-day{font-size:60px;}
        }
    </style>
</head>

<body>
<div class="container">

    <section class="hero">
        <div class="save-the-date">SAVE THE DATE</div>
        <div class="names">Lucas <span class="ampersand">&</span> Yasmin</div>

        <div class="date-box">
            <div class="date-day">25</div>
            <div class="date-month">FEVEREIRO</div>
            <div class="date-year">2026</div>
        </div>

        <div class="time">10H</div>
    </section>

    <section class="buttons-section">

        <div class="button-card">
            <div class="icon-circle">✓</div>
            <div class="button-title">Presença</div>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSdkx8SjXsM87hBuHjz3BSDz1sukB9lDU0VmQ1gxOuCXiKGXhQ/viewform" target="_blank" class="btn">Confirmar</a>
        </div>

        <div class="button-card">
            <div class="icon-circle">📍</div>
            <div class="button-title">Localização Cartório</div>
            <a href="https://share.google/771jqSFPAB6Rg5oOi" target="_blank" class="btn">Ver Mapa</a>
        </div>

        <div class="button-card">
            <div class="icon-circle">🍽</div>
            <div class="button-title">Localização Festa</div>
            <a href="https://share.google/ByffdyM8qq9NUS9kt" target="_blank" class="btn">Ver Mapa</a>
        </div>

        <div class="button-card">
            <div class="icon-circle">🎁</div>
            <div class="button-title">Lista de Presentes</div>
            <a href="https://www.querodecasamento.com.br/lista-de-casamento/yasmin-eLucas" target="_blank" class="btn">Ver Lista</a>
        </div>

    </section>

    <footer class="footer">
        <div style="font-size:28px;">Lucas & Yasmin</div>
        <div>25 . 02 . 2026</div>
    </footer>

</div>
</body>
</html>
