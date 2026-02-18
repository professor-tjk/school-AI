
<!DOCTYPE html>
<html lang="tg" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>School-AI</title>
  <!-- Tailwind CSS CDN барои дизайн зуд -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Chart.js барои графикҳо -->
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    .sidebar { transition: transform 0.3s ease; }
  </style>
</head>
<body class="bg-gray-100">

  <!-- Sidebar (аз чап) -->
  <aside id="sidebar" class="fixed top-0 left-0 h-full w-64 bg-indigo-900 text-white transform -translate-x-full md:translate-x-0 z-50">
    <div class="p-6">
      <h1 class="text-2xl font-bold mb-8 text-center">School-AI</h1>
      <ul class="space-y-2">
        <li><a href="#" class="block p-3 hover:bg-indigo-700 rounded">Саҳифаи аввал</a></li>
        <li><a href="children.html" class="block p-3 hover:bg-indigo-700 rounded">Хонандагон</a></li>
        <li><a href="teacher.html" class="block p-3 hover:bg-indigo-700 rounded">Омӯзгорон</a></li>
        <li><a href="jadval.html" class="block p-3 hover:bg-indigo-700 rounded">Ҷадвали дарсҳо</a></li>
        <li><a href="Baho.html" class="block p-3 hover:bg-indigo-700 rounded">Баҳоҳо</a></li>
        <li><a href="ogohiho.html" class="block p-3 hover:bg-indigo-700 rounded">Огоҳиҳо</a></li>
        <li><a href="Navbatdor.html" class="block p-3 hover:bg-indigo-700 rounded">Навбатдор</a></li>
        <li><a href="Jashnho.html" class="block p-3 hover:bg-indigo-700 rounded">Ҷашнвораҳо</a></li>
        <li><a href="jurnali_sinf.html" class="block p-3 hover:bg-indigo-700 rounded">Журнали синфҳо</a></li>
        <li><a href="khonandagoni_nabuda.html" class="block p-3 hover:bg-indigo-700 rounded">Хонандагони набуда</a></li>
      </ul>
    </div>
  </aside>

  <!-- Тугмаи меню барои телефон (аз чап) -->
  <button id="menuBtn" class="md:hidden fixed top-4 left-4 z-50 bg-indigo-900 text-white p-3 rounded-lg shadow-lg">
    ☰
  </button>

  <!-- Қисми асосӣ -->
  <div class="md:ml-64 min-h-screen">
    <!-- Topbar -->
    <header class="bg-white shadow p-4 flex justify-between items-center">
      <h1 class="text-xl font-bold text-indigo-900">Хуш омадед ба системаи идоракунии муассиса</h1>
    </header>

    <!-- Баннер -->
    <div class="bg-gradient-to-r from-teal-500 to-cyan-600 text-white p-8 m-6 rounded-xl shadow-lg">
      <div class="flex flex-col md:flex-row items-center justify-between">
        <div>
          <h2 class="text-3xl font-bold mb-2">Муассисаи Таҳсилоти миёнаи умумии №18</h2>
        </div>

      </div>
    </div>

    <!-- Карточкаҳои асосӣ -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 px-6">
      <div class="bg-white p-6 rounded-xl shadow">
        <div class="flex items-center gap-4">
          <div class="bg-pink-100 p-4 rounded-full">
            <span class="text-3xl">🎓</span>
          </div>
          <div>
            <p class="text-gray-600">Шумораи хонандагон</p>
            <p class="text-3xl font-bold">300</p>
          </div>
        </div>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <div class="flex items-center gap-4">
          <div class="bg-yellow-100 p-4 rounded-full">
            <span class="text-3xl">👩‍🏫</span>
          </div>
          <div>
            <p class="text-gray-600">Шумораи омӯзгорон</p>
            <p class="text-3xl font-bold">30</p>
          </div>
        </div>
      </div>
      <div class="bg-white p-6 rounded-xl shadow">
        <div class="flex items-center gap-4">
          <div class="bg-green-100 p-4 rounded-full">
            <span class="text-3xl">📊</span>
          </div>
          <div>
            <p class="text-gray-600">Ҷоизаи Ҷумҳуриявӣ</p>
            <p class="text-3xl font-bold">2</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Курсҳои маъмул -->
    <div class="p-6">
      <h2 class="text-2xl font-bold mb-4">Гирандаи ҷоизаҳои сатҳи вилоятӣ ва ҷумҳуриявӣ</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <div class="bg-white p-5 rounded-xl shadow hover:shadow-lg transition">
          <div class="bg-yellow-100 text-yellow-800 p-3 rounded-lg inline-block mb-3">_________________</div>
          <p class="font-bold">________________</p>
          <button class="mt-2 text-indigo-600 hover:underline">Дидани ҷоизаҳо →</button>
        </div>
        <div class="bg-white p-5 rounded-xl shadow hover:shadow-lg transition">
          <div class="bg-purple-100 text-purple-800 p-3 rounded-lg inline-block mb-3">_________________</div>
          <p class="font-bold">________________</p>
          <button class="mt-2 text-indigo-600 hover:underline">Дидани ҷоизаҳо →</button>
        </div>
        <div class="bg-white p-5 rounded-xl shadow hover:shadow-lg transition">
          <div class="bg-blue-100 text-blue-800 p-3 rounded-lg inline-block mb-3">________________</div>
          <p class="font-bold">_________________</p>
          <button class="mt-2 text-indigo-600 hover:underline">Дидани ҷоизаҳо →</button>
        </div>
        <div class="bg-white p-5 rounded-xl shadow hover:shadow-lg transition">
          <div class="bg-green-100 text-green-800 p-3 rounded-lg inline-block mb-3">Фозилов Билол</div>
          <p class="font-bold">Синфи 9 "А"</p>
          <button class="mt-2 text-indigo-600 hover:underline">Дидани Ҷоизаҳо→</button>
        </div>
      </div>
    </div>

    <!-- Графикҳои пешрафт -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 p-6">
      <div class="bg-white p-6 rounded-xl shadow">
        <h3 class="text-lg font-bold mb-4">Пешрафти солонаи муассиса дар 2025-2026</h3>
        <canvas id="progressChart" height="200"></canvas>
      </div>
      <div class="bg-white p-6 rounded-xl shadow grid grid-cols-1 gap-4">
        <div class="bg-yellow-50 p-4 rounded-lg">
          <p class="font-bold text-xl"> +50% дар соли 2025 </p>
        </div>
        <div class="bg-pink-50 p-4 rounded-lg">
          <p class="font-bold text-xl">+70% дар соли 2026 </p>
        </div>
      </div>
    </div>

  </div>

  <script src="01/js/index.js">
  </script>
</body>
</html>
