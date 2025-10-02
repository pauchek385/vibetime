<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>VIBETIME — демо (тёмно-красная тема)</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    // Tailwind custom colors
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            rw: {
              50:  '#fff5f6',
              100: '#ffe6e8',
              200: '#ffbfc3',
              300: '#ff949b',
              400: '#ff666f',
              500: '#e64549',
              600: '#b03234',
              700: '#7f2426',
              800: '#4f1718',
              900: '#2a0c0d'
            }
          }
        }
      }
    }
  </script>
  <style>
    /* Небольшая стилизация для красивых скроллов и карточек */
    html { scroll-behavior: smooth; }
    .glass {
      background: rgba(255,255,255,0.04);
      backdrop-filter: blur(6px);
      border: 1px solid rgba(255,255,255,0.04);
    }
    /* стили для range input (чуть лучше выглядит) */
    input[type="range"] {
      appearance: none;
      height: 6px;
      border-radius: 999px;
      background: linear-gradient(90deg,#7f2426 0%, #7f2426 40%, #fff 40%);
      outline: none;
    }
    input[type="range"]::-webkit-slider-thumb {
      appearance: none;
      width: 18px;
      height: 18px;
      border-radius: 999px;
      background: #ffdede;
      border: 3px solid #7f2426;
      box-shadow: 0 2px 6px rgba(0,0,0,0.35);
    }
  </style>
</head>
<body class="bg-rw-900 text-gray-100 antialiased">

  <!-- NAV -->
  <header class="fixed top-4 left-0 right-0 z-40">
    <div class="max-w-7xl mx-auto px-4">
      <div class="flex items-center justify-between">
        <a href="#" class="flex items-center gap-3">
          <div class="w-12 h-12 rounded-md bg-gradient-to-br from-rw-700 to-rw-900 flex items-center justify-center text-white shadow-lg">
            <span class="font-bold">RW</span>
          </div>
          <div class="hidden sm:block">
            <div class="text-sm font-semibold">VIBETIME</div>
            <div class="text-xs text-rw-200 opacity-80 -mt-1">Начало новой эры</div>
          </div>
        </a>

        <nav class="hidden md:flex gap-6 items-center">
          <a href="#home" class="py-2 px-3 rounded-md hover:bg-rw-800">Главная</a>
          <a href="#currency" class="py-2 px-3 rounded-md hover:bg-rw-800">Покупка</a>
          <a href="#shop" class="py-2 px-3 rounded-md hover:bg-rw-800">Магазин</a>
          <a href="#services" class="py-2 px-3 rounded-md hover:bg-rw-800">Услуги</a>
          <a href="#gallery" class="py-2 px-3 rounded-md hover:bg-rw-800">Галерея</a>
        </nav>

        <div class="flex items-center gap-3">
          <a href="#" class="px-4 py-2 bg-rw-600 hover:bg-rw-500 rounded-md shadow">VibeT1me.aternos.me</a>
        </div>
      </div>
    </div>
  </header>

  <main class="pt-28">

    <!-- HERO -->
    <section id="home" class="max-w-7xl mx-auto px-4 mb-12">
      <div class="rounded-2xl overflow-hidden relative glass p-8 md:p-14 flex flex-col md:flex-row items-center gap-8"
           style="background: linear-gradient(90deg, rgba(73,17,18,0.9), rgba(125,30,36,0.9));">
        <div class="flex-1 text-center md:text-left">
          <h1 class="text-4xl md:text-6xl font-extrabold leading-tight">VIBETIME<br><span class="text-rw-50">НАЧАЛО НОВОЙ ЭРЫ</span></h1>
          <p class="mt-4 text-rw-50/80 max-w-xl">Открой для себя огромные миры, полные веселья и миллионов друзей. Присоединяйся и стань частью сообщества!</p>
          <div class="mt-6 flex items-center justify-center md:justify-start gap-4">
            <a href="#shop" class="px-5 py-3 bg-rw-600 hover:bg-rw-500 rounded-md shadow font-semibold">Подключиться</a>
            <a href="#gallery" class="px-5 py-3 border border-rw-700 rounded-md hover:bg-rw-800">Подробнее</a>
          </div>
        </div>

        <div class="w-full md:w-1/3">
          <!-- стилизованная карточка персонажа -->
          <div class="bg-gradient-to-br from-rw-800 to-rw-700 rounded-xl p-4 shadow-2xl">
            <img src="server-banner.png" alt="Превью сервера" class="w-full h-52 object-cover rounded-lg shadow-inner">
            <div class="mt-4 text-center">
              <div class="text-sm">Наш сервер</div>
              <div class="text-lg font-bold">VibeT1me.aternos.me</div>
              <div class="mt-3">
                <a href="#currency" class="inline-block px-4 py-2 bg-rw-600 rounded-md">В магазин</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CURRENCY / Покупка игровой валюты -->
    <section id="currency" class="max-w-7xl mx-auto px-4 mb-12">
      <div class="glass rounded-2xl p-8 md:p-10">
        <div class="flex flex-col md:flex-row items-center gap-8">
          <div class="flex-1">
            <div class="flex items-center gap-4">
              <div class="w-16 h-16 rounded-xl bg-rw-700 flex items-center justify-center text-white">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 8c-1.657 0-3 .895-3 2v4c0 1.105 1.343 2 3 2s3-.895 3-2v-4c0-1.105-1.343-2-3-2z"/>
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M12 3v2m0 14v2m8-8h-2M6 12H4"/>
                </svg>
              </div>
              <div>
                <h3 class="text-xl font-semibold">Покупка игровой валюты</h3>
                <p class="text-sm text-rw-50/80">Выбери количество риллик/валюты и нажми купить.</p>
              </div>
            </div>

            <div class="mt-6">
              <label class="block text-sm mb-2">Количество монеток</label>
              <input id="range" type="range" min="100" max="6000" value="500" oninput="updateRange(this.value)">
              <div class="mt-3 grid grid-cols-2 gap-4">
                <div class="bg-rw-800 p-4 rounded-md">
                  <div class="text-xs text-rw-50/70">Отдаёте</div>
                  <div id="pay" class="text-2xl font-bold">500₽</div>
                </div>
                <div class="bg-rw-800 p-4 rounded-md">
                  <div class="text-xs text-rw-50/70">Получаете</div>
                  <div id="get" class="text-2xl font-bold">500R</div>
                </div>
              </div>
              <div class="mt-4">
                <a href="#shop" class="inline-block px-5 py-2 bg-rw-600 rounded-md">Приобрести монетки</a>
                <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
              </div>
            </div>
          </div>

          <div class="w-full md:w-1/3">
            <div class="bg-rw-800 p-6 rounded-xl">
              <div class="text-sm text-rw-50/80">Рекомендуемая версия</div>
              <div class="mt-2 text-lg font-bold">1.16.5</div>
              <div class="mt-4">
                <a href="#" class="inline-block px-4 py-2 bg-rw-600 rounded-md">VibeT1me.aternos.me</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SHOP / Магазин привилегий -->
    <section id="shop" class="max-w-7xl mx-auto px-4 mb-12">
      <div class="glass rounded-2xl p-8 md:p-10">
        <div class="flex items-center justify-between mb-6">
          <div>
            <h2 class="text-2xl font-bold">Магазин привилегий</h2>
            <p class="text-sm text-rw-50/80">Выбери роль и начни играть с бонусами.</p>
          </div>
          <div class="flex gap-2">
            <button class="px-3 py-2 bg-rw-700 rounded-md">Гриф. Выживание</button>
            <button class="px-3 py-2 bg-transparent border border-rw-700 rounded-md">Анархия</button>
            <button class="px-3 py-2 bg-transparent border border-rw-700 rounded-md">СТО</button>
          </div>
        </div>

        <!-- Grid of cards -->
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
          <!-- sample card -->
          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">4449₽</div>
              <div class="absolute top-3 right-3 bg-rw-700/60 px-2 py-1 rounded text-xs">Скидка</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Полный набор привилегий.</div>
              <div class="mt-4 flex items-center justify-between">
                <div class="text-xl font-bold">4449₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded-md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>

          <!-- копируем несколько карточек для примера -->
          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">6666₽</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Эксклюзивные скины и комнаты.</div>
              <div class="mt-4 flex items-center justify-between">
                <div class="text-xl font-bold">6666₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded-md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>

          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">1899₽</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Особые питомцы и ранги.</div>
              <div class="mt-4 flex items-center justify-between">
                <div class="text-xl font-bold">1899₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded-md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>

          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">999₽</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Королевская роль и доступы.</div>
              <div class="mt-4 flex items-center justify-between">
                <div class="text-xl font-bold">999₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded-md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>

          <!-- пары карточек для сетки -->
          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">289₽</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Мини-роль для старта.</div>
              <div class="mt-4 flex items-center justify_between">
                <div class="text-xl font-bold">289₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded-md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>

          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">129₽</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Для фанатов ПВП.</div>
              <div class="mt-4 flex items-центер justify_between">
                <div class="text-xl font-bold">129₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded_md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>

          <div class="bg-rw-800 rounded-xl overflow-hidden shadow-md">
            <div class="relative">
              <img src="shop-placeholder.png" alt="Скоро" class="w-full h-40 object-cover">
              <div class="absolute top-3 left-3 bg-rw-600 px-3 py-1 rounded text-sm font-semibold">89₽</div>
            </div>
            <div class="p-4">
              <div class="font-bold text-lg">Скоро</div>
              <div class="mt-2 text-sm text-rw-50/70">Экономный набор.</div>
              <div class="mt-4 flex items-center justify_between">
                <div class="text-xl font-bold">89₽</div>
                <button class="px-3 py-2 bg-rw-600 rounded_md">Купить</button>
              </div>
              <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
            </div>
          </div>
        </div>

      </div>
    </section>

    <!-- SERVICES / Услуги -->
    <section id="services" class="max-w-7xl mx-auto px-4 mb-12">
      <div class="glass rounded-2xl p-8 md:p-10">
        <div class="flex flex-col md:flex-row items-start gap-8">
          <div class="flex-1">
            <h3 class="text-2xl font-bold">Услуги</h3>
            <p class="text-sm text-rw-50/80 mt-2">У нас доступны услуги по разбану и размуту аккаунтов. Оформление и сроки обсуждаются в дискорде.</p>

            <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div class="relative rounded-lg overflow-hidden border border-rw-700/50">
                <img src="service-unban.png" alt="Разбан" class="absolute inset-0 w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-b from-black/20 via-black/55 to-rw-900/85"></div>
                <div class="relative p-6 flex flex-col gap-4 text-white">
                  <div class="text-3xl font-extrabold uppercase tracking-wide drop-shadow-lg">Разбан</div>
                  <div class="inline-flex w-fit items-center px-4 py-2 rounded-md bg-rw-700/70 backdrop-blur border border-white/20 text-lg font-semibold">Цена: 150₽</div>
                  <div>
                    <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="px-4 py-2 bg-rw-600 hover:bg-rw-500 rounded-md">Заказать</a>
                  </div>
                  <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
                </div>
              </div>

              <div class="relative rounded-lg overflow-hidden border border-rw-700/50">
                <img src="service-unmute.png" alt="Размут" class="absolute inset-0 w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-b from-black/20 via-black/55 to-rw-900/85"></div>
                <div class="relative p-6 flex flex-col gap-4 text-white">
                  <div class="text-3xl font-extrabold uppercase tracking-wide drop-shadow-lg">Размут</div>
                  <div class="inline-flex w-fit items-center px-4 py-2 rounded-md bg-rw-700/70 backdrop-blur border border-white/20 text-lg font-semibold">Цена: 75₽</div>
                  <div>
                    <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="px-4 py-2 bg-rw-600 hover:bg-rw-500 rounded-md">Заказать</a>
                  </div>
                  <a href="https://discord.gg/DsDWbJF99G" target="_blank" rel="noopener" class="mt-3 block text-xs text-rw-200 hover:text-rw-50 transition">Чтобы купить, свяжитесь с нами в Discord</a>
                </div>
              </div>
            </div>
          </div>

          <div class="w-full md:w-1/3">
            <div class="p-6 rounded-lg bg-gradient-to-br from-rw-800 to-rw-700">
              <div class="text-sm text-rw-50/80">Наши соцсети</div>
              <div class="mt-2 font-bold text-lg">VibeTime в Discord</div>
              <div class="mt-4">
                <button onclick="openDiscord()" class="px-4 py-2 bg-rw-600 rounded-md">Открыть Discord</button>
              </div>
              <div class="mt-3 text-xs text-rw-50/70">(ссылка откроется в новом окне)</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- GALLERY -->
    <!-- FOOTER -->
    <footer class="bg-rw-900 border-t border-rw-800">
      <div class="max-w-7xl mx-auto px-4 py-8 flex flex-col md:flex-row items-center justify-between gap-4">
        <div class="text-sm">© VIBETIME — все права защищены</div>
        <div class="flex gap-4 items-center">
          <a href="#" class="text-sm">Правила</a>
          <a href="#" class="text-sm">Поддержка</a>
          <a href="#" class="text-sm">Форум</a>
        </div>
      </div>
    </footer>
  </main>

  <script>
    // поддержка range
    function updateRange(v) {
      document.getElementById('range').value = v;
      document.getElementById('pay').innerText = Math.round(v) + '₽';
      document.getElementById('get').innerText = Math.round(v) + 'R';
    }

    // пример открытия дискорда (подставь свою ссылку)
    function openDiscord(){
      const url = 'https://discord.gg/DsDWbJF99G';
      window.open(url, '_blank');
    }

    // клик по картинке Discord
    document.getElementById('discordCard').addEventListener('click', function(e){
      e.preventDefault();
      openDiscord();
    });
  </script>
</body>
</html>
