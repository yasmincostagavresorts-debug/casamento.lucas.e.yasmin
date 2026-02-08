<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucas & Yasmin - 25 de Fevereiro de 2026</title>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;600&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, #e8ede7 0%, #d4ddd2 100%);
            color: #4a5447;
            overflow-x: hidden;
        }

        .container {
            max-width: 100%;
            margin: 0 auto;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(232, 237, 231, 0.95), rgba(232, 237, 231, 0.95)), 
                        url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 800"><rect fill="%23a8b5a1" width="1200" height="800"/></svg>');
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
            position: relative;
        }

        .save-the-date {
            font-family: 'Montserrat', sans-serif;
            font-size: 14px;
            letter-spacing: 4px;
            color: #7a8c6f;
            margin-bottom: 40px;
            font-weight: 300;
        }

        .names-container {
            margin-bottom: 50px;
        }

        .names {
            font-family: 'Cormorant Garamond', serif;
            font-size: 72px;
            font-weight: 300;
            color: #4a5e3f;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        .ampersand {
            font-size: 48px;
            color: #7a8c6f;
            margin: 0 10px;
        }

        .date-box {
            display: inline-block;
            border: 2px solid #a8b5a1;
            padding: 40px 60px;
            margin: 30px 0;
            background: rgba(255, 255, 255, 0.6);
        }

        .date-day {
            font-family: 'Cormorant Garamond', serif;
            font-size: 80px;
            font-weight: 400;
            color: #4a5e3f;
            line-height: 1;
        }

        .date-month {
            font-family: 'Montserrat', sans-serif;
            font-size: 20px;
            letter-spacing: 3px;
            color: #7a8c6f;
            text-transform: uppercase;
            margin-top: 10px;
        }

        .date-year {
            font-family: 'Cormorant Garamond', serif;
            font-size: 36px;
            color: #4a5e3f;
            margin-top: 5px;
        }

        .time {
            font-family: 'Montserrat', sans-serif;
            font-size: 24px;
            color: #7a8c6f;
            margin-top: 30px;
            letter-spacing: 2px;
        }

        /* Buttons Section */
        .buttons-section {
            background: #ffffff;
            padding: 80px 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }

        .button-card {
            width: 280px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .button-card:hover {
            transform: translateY(-10px);
        }

        .icon-circle {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background: linear-gradient(135deg, #a8b5a1 0%, #8fa182 100%);
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            box-shadow: 0 4px 15px rgba(168, 181, 161, 0.4);
        }

        .icon-circle svg {
            width: 40px;
            height: 40px;
            fill: #ffffff;
        }

        .button-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 12px;
            letter-spacing: 2px;
            color: #7a8c6f;
            text-transform: uppercase;
            margin-bottom: 15px;
            font-weight: 400;
        }

        .btn {
            display: inline-block;
            padding: 15px 40px;
            background: #5d7052;
            color: #ffffff;
            text-decoration: none;
            font-family: 'Montserrat', sans-serif;
            font-size: 13px;
            letter-spacing: 2px;
            text-transform: uppercase;
            border-radius: 30px;
            transition: all 0.3s ease;
            font-weight: 400;
        }

        .btn:hover {
            background: #7a8c6f;
            box-shadow: 0 5px 20px rgba(93, 112, 82, 0.4);
        }

        /* Footer */
        .footer {
            background: #5d7052;
            color: #e8ede7;
            text-align: center;
            padding: 40px 20px;
            font-family: 'Cormorant Garamond', serif;
            font-size: 18px;
        }

        .footer-names {
            font-size: 28px;
            margin-bottom: 10px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .names {
                font-size: 48px;
            }

            .date-day {
                font-size: 60px;
            }

            .date-box {
                padding: 30px 40px;
            }

            .buttons-section {
                padding: 60px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Hero Section -->
        <section class="hero">
            <div class="save-the-date">SAVE THE DATE</div>
            
            <div class="names-container">
                <div class="names">
                    Lucas <span class="ampersand">&</span> Yasmin
                </div>
            </div>

            <div class="date-box">
                <div class="date-day">25</div>
                <div class="date-month">FEVEREIRO</div>
                <div class="date-year">2026</div>
            </div>

            <div class="time">10H</div>
        </section>

        <!-- Buttons Section -->
        <section class="buttons-section">
            <!-- Confirmar Presença -->
            <div class="button-card">
                <div class="icon-circle">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.11 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 16H5V9h14v11z"/>
                    </svg>
                </div>
                <div class="button-title">Presença</div>
                <a href="https://docs.google.com/forms/d/e/1FAIpQLSdkx8SjXsM87hBuHjz3BSDz1sukB9lDU0VmQ1gxOuCXiKGXhQ/viewform" target="_blank" class="btn">Confirmar</a>
            </div>

            <!-- Localização Cartório -->
            <div class="button-card">
                <div class="icon-circle">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
                    </svg>
                </div>
                <div class="button-title">Localização Cartório</div>
                <a href="https://share.google/771jqSFPAB6Rg5oOi" target="_blank" class="btn">Ver Mapa</a>
            </div>

            <!-- Localização Restaurante -->
            <div class="button-card">
                <div class="icon-circle">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M11 9H9V2H7v7H5V2H3v7c0 2.12 1.66 3.84 3.75 3.97V22h2.5v-9.03C11.34 12.84 13 11.12 13 9V2h-2v7zm5-3v8h2.5v8H21V2c-2.76 0-5 2.24-5 4z"/>
                    </svg>
                </div>
                <div class="button-title">Localização Festa</div>
                <a href="https://share.google/ByffdyM8qq9NUS9kt" target="_blank" class="btn">Ver Mapa</a>
            </div>

            <!-- Lista de Presentes -->
            <div class="button-card">
                <div class="icon-circle">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M20 6h-2.18c.11-.31.18-.65.18-1 0-1.66-1.34-3-3-3-1.05 0-1.96.54-2.5 1.35l-.5.67-.5-.68C10.96 2.54 10.05 2 9 2 7.34 2 6 3.34 6 5c0 .35.07.69.18 1H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2zm-5-2c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zM9 4c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zm11 15H4v-2h16v2zm0-5H4V8h5.08L7 10.83 8.62 12 11 8.76l1-1.36 1 1.36L15.38 12 17 10.83 14.92 8H20v6z"/>
                    </svg>
                </div>
                <div class="button-title">Lista de Presentes</div>
                <a href="https://www.querodecasamento.com.br/lista-de-casamento/yasmin-eLucas" target="_blank" class="btn">Ver Lista</a>
            </div>
        </section>

        <!-- Footer -->
        <footer class="footer">
            <div class="footer-names">Lucas & Yasmin</div>
            <div>25 . 02 . 2026</div>
        </footer>
    </div>
</body>
</html>
