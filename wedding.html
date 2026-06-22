<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Свадебное Приглашение — Лепестки и Цветы</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Caveat:wght@600&family=Montserrat:wght@300;400;500;600&display=swap');

        :root {
            --bg-color: #fff0f3;
            --card-bg: rgba(255, 255, 255, 0.85);
            --text-main: #6c4f57;
            --text-muted: #a88a93;
            --accent: #ffb3c1;
        }

        body {
            margin: 0; padding: 0;
            font-family: 'Montserrat', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            display: flex; justify-content: center; align-items: center;
            min-height: 100vh; overflow: hidden; position: relative;
        }

        /* Контейнер для летающих цветков и сердечек */
        #bg-particles {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            pointer-events: none; z-index: 1;
        }

        /* Стиль и анимация для каждого летающего цветка/лепестка */
        .petal {
            position: absolute;
            user-select: none;
            opacity: 0;
            animation: flyAndRotate linear infinite;
            top: -50px;
        }

        @keyframes flyAndRotate {
            0% { transform: translateY(0) translateX(0) rotate(0deg); opacity: 0; }
            10% { opacity: 0.8; }
            90% { opacity: 0.8; }
            100% { transform: translateY(105vh) translateX(100px) rotate(360deg); opacity: 0; }
        }

        /* Экраны */
        .screen {
            width: 100%; max-width: 420px; min-height: 100vh;
            padding: 20px; box-sizing: border-box;
            display: flex; flex-direction: column; justify-content: center; align-items: center;
            position: relative; z-index: 2; transition: opacity 0.5s ease;
        }
        .hidden { display: none !important; }
        .fade-out { opacity: 0; }
        .fade-in { animation: popUp 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.2) forwards; }

        @keyframes popUp {
            from { opacity: 0; transform: scale(0.85); }
            to { opacity: 1; transform: scale(1); }
        }

        /* Красивая кнопка из оригинального дизайна */
        .main-btn {
            background: linear-gradient(135deg, #cc7870, #b5635b);
            border: none; color: white; padding: 14px 40px;
            font-size: 1rem; border-radius: 50px; cursor: pointer;
            box-shadow: 0 6px 20px rgba(204,120,112,0.4);
            transition: all 0.3s;
        }
        .main-btn:hover { transform: translateY(-3px); box-shadow: 0 8px 25px rgba(204,120,112,0.6); }

        /* Округлая карточка, как в weding.jpg */
        .card-container {
            background: var(--card-bg); padding: 40px 20px;
            border-radius: 30px; text-align: center; width: 100%; box-sizing: border-box;
            box-shadow: 0 15px 35px rgba(108,79,87,0.1);
            border: 1px solid rgba(255,255,255,0.7);
            backdrop-filter: blur(8px); /* Размытие фона за карточкой */
        }

        .names { font-family: 'Caveat', cursive; font-size: 3.6rem; color: #cc7870; margin: 10px 0; }
        .divider { font-size: 1.2rem; color: var(--accent); margin: 15px 0; }

        /* Таймер обратного отсчета */
        .countdown { display: flex; justify-content: space-around; margin: 25px 0; }
        .time-block {
            background: white; width: 68px; height: 68px;
            display: flex; flex-direction: column; justify-content: center;
            border-radius: 18px; border: 1px solid #ffe5ec;
            box-shadow: 0 4px 10px rgba(0,0,0,0.02);
        }
        .time-block span { font-size: 1.4rem; font-weight: 600; color: #cc7870; }
        .time-block label { font-size: 0.55rem; color: var(--text-muted); font-weight: 600; margin-top: 2px; }
        .time-separator { align-self: center; font-weight: bold; color: var(--accent); }

        /* Блоки с инфо */
        .info-box { background: rgba(255, 255, 255, 0.6); border-radius: 20px; padding: 18px; border: 1px solid #ffe5ec; }
        .details-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 20px; }
        h3 { font-size: 0.8rem; color: var(--text-muted); letter-spacing: 1px; margin-top: 0; margin-bottom: 5px; font-weight: 600; }
    </style>
</head>
<body>

    <!-- Сюда JavaScript будет сыпать цветы и лепестки -->
    <div id="bg-particles"></div>

    <!-- ЭКРАН 1: КОНВЕРТ -->
    <div id="envelope-screen" class="screen">
        <div style="text-align: center;">
            <div style="font-size: 4rem; margin-bottom: 10px; animation: heartbeat 2s infinite ease-in-out;">💌</div>
            <p style="letter-spacing: 2px; color: var(--text-muted); font-weight: 600; font-size: 0.9rem; margin-bottom: 5px;">Приглашение для</p>
            <h1 style="font-family: 'Caveat', cursive; font-size: 3.3rem; margin-top: 0; color: var(--text-main); margin-bottom: 40px;">Дорогого Гостя</h1>
            <button id="open-btn" class="main-btn">✨ Открыть приглашение ✨</button>
        </div>
    </div>

    <!-- ЭКРАН 2: ОСНОВНОЙ КОНТЕНТ -->
    <div id="info-screen" class="screen hidden">
        <div class="card-container">
            <p style="font-size: 0.75rem; letter-spacing: 3px; color: var(--text-muted); font-weight: 600; margin-top: 0;">СВАДЕБНОЕ ПРИГЛАШЕНИЕ</p>
            <p style="margin: 5px 0; font-size: 1.1rem;">Дорогой Гость,</p>
            <h2 class="names">Влад & Диана</h2>
            <p style="font-size: 0.95rem; line-height: 1.6; color: #5c454a; padding: 0 5px;">С огромной радостью и любовью приглашаем вас разделить с нами этот особенный день нашей жизни</p>

            <div class="divider">🌸 • 🌸 • 🌸</div>

            <!-- Таймер -->
            <section class="timer-section">
                <p style="font-size: 0.7rem; letter-spacing: 1.5px; color: var(--text-muted); font-weight: 600; margin: 0;">ДО СВАДЬБЫ ОСТАЛОСЬ</p>
                <div class="countdown">
                    <div class="time-block"><span id="days">00</span><label>ДНЕЙ</label></div>
                    <div class="time-separator">:</div>
                    <div class="time-block"><span id="hours">00</span><label>ЧАСОВ</label></div>
                    <div class="time-separator">:</div>
                    <div class="time-block"><span id="minutes">00</span><label>МИНУТ</label></div>
                    <div class="time-separator">:</div>
                    <div class="time-block"><span id="seconds">00</span><label>СЕКУНД</label></div>
                </div>
            </section>

            <!-- Блоки даты и времени -->
            <div class="details-grid">
                <div class="info-box">
                    <div style="font-size: 1.3rem; margin-bottom: 3px;">📅</div>
                    <h3>ДАТА</h3>
                    <p style="font-weight: 600; margin: 0; color: #cc7870;">20 сентября</p>
                    <p style="margin: 0; font-size: 0.85rem;">2027 года</p>
                </div>
                <div class="info-box">
                    <div style="font-size: 1.3rem; margin-bottom: 3px;">⏰</div>
                    <h3>ВРЕМЯ</h3>
                    <p style="margin: 0; font-size: 0.85rem; font-weight: 600;">Никах — 14:00</p>
                    <p style="margin: 4px 0 0 0; font-size: 0.85rem; font-weight: 600;">Банкет — 18:00</p>
                </div>
            </div>

            <!-- Место проведения -->
            <section class="info-box">
                <div style="font-size: 1.4rem; margin-bottom: 3px;">🕊️</div>
                <h3>МЕСТО ПРОВЕДЕНИЯ</h3>
                <p style="font-weight: 600; margin: 0 0 4px 0;">Свадебный зал «Жемчужина»</p>
                <p style="margin: 0; font-size: 0.85rem; color: var(--text-muted);">ул. Навои 12, Ташкент</p>
            </section>

            <p style="margin-top: 35px; font-size: 0.9rem; font-weight: 600; color: var(--text-muted); margin-bottom: 0;">Ваше присутствие — лучший подарок для нас ✨</p>
        </div>
    </div>

    <script>
        document.addEventListener("DOMContentLoaded", () => {
            // Экраны
            const openBtn = document.getElementById("open-btn");
            const env = document.getElementById("envelope-screen");
            const info = document.getElementById("info-screen");

            openBtn.addEventListener("click", () => {
                env.classList.add("fade-out");
                setTimeout(() => {
                    env.classList.add("hidden");
                    info.classList.remove("hidden");
                    info.classList.add("fade-in");
                }, 500);
            });

            // Таймер
            const targetDate = new Date("September 20, 2027 14:00:00").getTime();
            setInterval(() => {
                const now = new Date().getTime();
                const diff = targetDate - now;
                if (diff < 0) return;
                document.getElementById("days").textContent = String(Math.floor(diff / (1000 * 60 * 60 * 24))).padStart(2, '0');
                document.getElementById("hours").textContent = String(Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60))).padStart(2, '0');
                document.getElementById("minutes").textContent = String(Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60))).padStart(2, '0');
                document.getElementById("seconds").textContent = String(Math.floor((diff % (1000 * 60)) / 1000)).padStart(2, '0');
            }, 1000);

            // ГЕНЕРАТОР ЖИВОГО ФОНА (Лепестки, Цветы, Сердечки)
            const particleContainer = document.getElementById("bg-particles");
            const elements = ['🌸', '🌹', '💖', '💮', '💗', '🍃']; // Эмодзи, которые будут летать

            function createPetal() {
                const petal = document.createElement("div");
                petal.classList.add("petal");

                // Случайный выбор элемента из списка
                petal.innerText = elements[Math.floor(Math.random() * elements.length)];

                // Рандомные настройки для уникальности каждого лепестка
                petal.style.left = Math.random() * 100 + "vw"; // Позиция по ширине экрана
                petal.style.fontSize = Math.random() * (30 - 16) + 16 + "px"; // Размер от 16px до 30px
                petal.style.animationDuration = Math.random() * (8 - 4) + 4 + "s"; // Скорость полета от 4 до 8 секунд

                particleContainer.appendChild(petal);

                // Удаляем элемент после того, как он улетел за экран
                setTimeout(() => { petal.remove(); }, 8000);
            }

            // Запускаем постоянное создание лепестков (каждые 300 миллисекунд)
            setInterval(createPetal, 300);
        });
    </script>
</body>
</html>
