<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>RECON: OMEGA CORE | CLASSIFIED EVIDENCE</title>
    <style>
        :root { --neon: #00ff00; --bg: #050505; --red: #ff0000; }
        body { background: var(--bg); color: var(--neon); font-family: 'Consolas', monospace; margin: 0; text-align: center; overflow-x: hidden; }
        
        body::before {
            content: "1010110100101011010101010011010";
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            font-size: 20px; color: rgba(0, 255, 0, 0.03);
            white-space: nowrap; word-break: break-all; z-index: -1;
            animation: matrix 10s linear infinite;
        }
        @keyframes matrix { from { transform: translateY(-100%); } to { transform: translateY(100%); } }

        header { padding: 80px 20px; border-bottom: 2px solid var(--neon); background: rgba(0, 0, 0, 0.8); }
        h1 { font-size: 5em; letter-spacing: 20px; text-shadow: 0 0 25px var(--neon); margin: 0; }
        .alert-bar { background: var(--red); color: white; padding: 5px; font-weight: bold; letter-spacing: 5px; }

        .container { max-width: 950px; margin: 40px auto; padding: 20px; }
        
        .feature { 
            border: 1px solid var(--neon); 
            padding: 35px; 
            margin-bottom: 30px; 
            background: rgba(0, 0, 0, 0.9); 
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); 
            position: relative;
            box-shadow: inset 0 0 10px rgba(0,255,0,0.1);
        }
        .feature:hover { 
            transform: scale(1.06); 
            box-shadow: 0 0 50px rgba(0, 255, 0, 0.3);
            border-color: #fff;
        }

        h2 { color: #fff; text-transform: uppercase; border-left: 5px solid var(--red); padding-left: 15px; text-align: left; }
        p { text-align: left; font-size: 1.1em; line-height: 1.6; color: #ccc; }
        
        .intel-box { border: 2px dashed var(--red); padding: 20px; margin-top: 20px; background: rgba(255,0,0,0.05); }
        .status-blink { color: var(--red); animation: blink 0.8s infinite; font-weight: bold; }
        @keyframes blink { 50% { opacity: 0; } }

        /* БЛОК СО СВОДКОЙ ВЗЛОМА */
        .log-entry { background: #111; border: 1px solid #333; padding: 15px; margin-top: 15px; font-size: 0.9em; text-align: left; color: #00cc00; }
        .timer { color: var(--red); font-weight: bold; }

        footer { padding: 40px; color: #333; font-size: 0.8em; border-top: 1px solid #111; }
    </style>
</head>
<body>
    <div class="alert-bar">INTERNAL USE ONLY // SOURCE: CLASSIFIED // LEVEL 9 ACCESS</div>

    <header>
        <h1>OMEGA PROJECT</h1>
        <p style="color: #666;">[ПОДТВЕРЖДЕННЫЕ ДАННЫЕ СЕТЕВОЙ АКТИВНОСТИ]</p>
    </header>

    <div class="container">
        <div class="feature">
            <h2>ОТЧЕТ ПО ОБЪЕКТУ</h2>
            <p>Существование <strong>OMEGA</strong> официально подтверждено после серии необъяснимых инцидентов в закрытых сетях. Система обладает колоссальной вычислительной мощностью, позволяющей взламывать архитектуры любой сложности. Главный архитектор — <strong>Владимир</strong>.</p>
        </div>

        <div class="feature">
            <h2>ОПЕРАТИВНАЯ СВОДКА: ИНЦИДЕНТ #X-99</h2>
            <p>Зафиксирован пример боевого применения системы OMEGA против укрепленного правительственного узла данных:</p>
            <div class="log-entry">
                [00:01:12] — Обход первичного брандмауэра... <br>
                [00:02:45] — Инъекция V-SHIELD в ядро системы... <br>
                [00:04:10] — Дешифровка протоколов уровня "Super-Admin"... <br>
                [00:05:30] — Захват управления распределенной сетью... <br>
                <span class="timer">[00:06:00] — ПОЛНЫЙ КОНТРОЛЬ ПОЛУЧЕН. СЕРВЕР ВЗЛОМАН.</span>
            </div>
            <p style="margin-top: 10px; color: #ff9900;">* Примечание: Сверхзащищенный узел пал менее чем за 6 минут.</p>
        </div>

        <div class="feature">
            <h2>РАЗВЕДДАННЫЕ: ВЛАДЕЛЬЦЫ</h2>
            <div class="intel-box">
                <ul style="text-align: left; list-style: none; padding: 0;">
                    <li><span class="status-blink">[ВЫЯВЛЕН]</span> <strong>ВЛАДИМИР</strong> — Создатель и владелец исходного кода.</li>
                    <li><span class="status-blink">[ПОДТВЕРЖДЕН]</span> <strong>ГАВРИИЛ</strong> — Единственный установленный носитель действующей копии OMEGA.</li>
                </ul>
            </div>
            <p style="margin-top: 15px; font-style: italic; color: #888;">* Официальных сайтов OMEGA не существует. Данные получены путем мониторинга трафика Гавриила.</p>
        </div>
    </div>

    <footer>
        OMEGA_SEC_LOG_V4.0 // ENCRYPTED // NO PUBLIC ACCESS
    </footer>
</body>
</html>
