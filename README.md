<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Студия Вайб-Кодинга — Быстрая разработка сайтов с ИИ</title>
    <script src="https://jsdelivr.net"></script>
    <style>
        .vibe-gradient {
            background: linear-gradient(135deg, #6366f1 0%, #a855f7 50%, #ec4899 100%);
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased">

    <!-- Навигация -->
    <nav class="max-w-6xl mx-auto px-6 py-6 flex justify-between items-center">
        <div class="text-2xl font-black tracking-wider text-transparent bg-clip-text vibe-gradient">VIBE CODE</div>
        <a href="#contact" class="bg-indigo-600 hover:bg-indigo-500 text-white font-medium px-5 py-2 rounded-full transition text-sm">Связаться</a>
    </nav>

    <!-- Главный экран -->
    <header class="max-w-4xl mx-auto px-6 pt-20 pb-16 text-center">
        <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight mb-6 leading-tight">
            Ваша идея превратится в готовый сайт <br class="hidden md:inline">
            <span class="text-transparent bg-clip-text vibe-gradient">уже к этим выходным</span>
        </h1>
        <p class="text-lg md:text-xl text-slate-400 mb-10 max-w-2xl mx-auto">
            Мы — студия «вайб-кодинга». Создаем современные веб-сервисы, лендинги и MVP на максимальной скорости с помощью синергии ИИ-инструментов, Low-Code и нашего опыта.
        </p>
        <div class="flex flex-col items-center gap-3">
            <a href="#contact" class="vibe-gradient text-white font-bold px-8 py-4 rounded-xl text-lg shadow-lg hover:opacity-90 transition transform hover:-translate-y-0.5">
                Обсудить проект за 15 минут
            </a>
            <span class="text-xs text-slate-500">Расскажите свою идею, и мы сразу прикинем архитектуру. Бесплатно.</span>
        </div>
    </header>

    <!-- Секция О нас -->
    <section class="max-w-4xl mx-auto px-6 py-16 border-t border-slate-800">
        <h2 class="text-3xl font-bold mb-8 text-center md:text-left">Кто мы такие и почему кодим на вайбе?</h2>
        <div class="bg-slate-800/50 border border-slate-700/50 p-8 rounded-2xl shadow-xl space-y-4 text-slate-300 leading-relaxed">
            <p class="font-medium text-white text-lg">Привет! Мы — команда VIBE CODE.</p>
            <p>
                Ровно год назад мы поняли, что классическая веб-разработка сломалась. Заказчики месяцами ждут макеты, платят сотни тысяч рублей за базовый функционал и перегорают к моменту релиза.
            </p>
            <p>
                Мы решили это исправить. Весь этот год мы глубоко копали тему ИИ-генерации, тестировали десятки No-Code/Low-Code платформ и связывали их с современными фреймворками. Мы превратили разработку сайтов в «вайб-кодинг» — чистый творческий процесс, где скорость генерации кода равна скорости мысли.
            </p>
            <p>
                За нашим плечами десятки часов оптимизации промптов, интеграций API и настройки баз данных. Мы не пишем код руками там, где ИИ делает это за секунды. Мы фокусируемся на главном — на вашем бизнесе, удобстве пользователей и сочном визуале.
            </p>
        </div>
    </section>

    <!-- Форма / Контакты -->
    <section id="contact" class="max-w-xl mx-auto px-6 py-16 text-center">
        <h2 class="text-2xl font-bold mb-4">Готовы запустить свой продукт?</h2>
        <p class="text-slate-400 mb-8">Оставьте контакты, мы свяжемся в Telegram или по почте в течение часа.</p>
        
        <!-- Простая интеграция с Formspree для бесплатного сбора заявок на почту -->
        <form action="https://formspree.io" method="POST" class="space-y-4 text-left">
            <div>
                <label class="block text-sm font-medium text-slate-400 mb-1">Имя</label>
                <input type="text" name="name" required class="w-full bg-slate-800 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-indigo-500">
            </div>
            <div>
                <label class="block text-sm font-medium text-slate-400 mb-1">Telegram или Email</label>
                <input type="text" name="contact" required class="w-full bg-slate-800 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-indigo-500" placeholder="@username или mail@example.com">
            </div>
            <div>
                <label class="block text-sm font-medium text-slate-400 mb-1">Коротко о вашей идее</label>
                <textarea name="idea" rows="3" class="w-full bg-slate-800 border border-slate-700 rounded-lg px-4 py-2.5 text-white focus:outline-none focus:border-indigo-500"></textarea>
            </div>
            <button type="submit" class="w-full bg-indigo-600 hover:bg-indigo-500 text-white font-bold py-3 rounded-lg transition">
                Отправить заявку
            </button>
        </form>
    </section>

    <!-- Подвал -->
    <footer class="border-t border-slate-800 max-w-6xl mx-auto px-6 py-8 text-center text-sm text-slate-500">
        &copy; 2026 VIBE CODE. Разработано на правильном вайбе.
    </footer>

</body>
</html>
