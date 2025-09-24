<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>السيرة الذاتية - عبد الإله عثمان أحمد غويث</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
      if (document.documentElement.classList.contains('dark')) {
        localStorage.setItem('theme', 'dark');
      } else {
        localStorage.setItem('theme', 'light');
      }
    }
    if (localStorage.getItem('theme') === 'dark') {
      document.documentElement.classList.add('dark');
    }
  </script>
</head>
<body class="bg-gray-100 dark:bg-gray-900 font-sans transition duration-500">
  <div class="max-w-3xl mx-auto my-10 bg-white dark:bg-gray-800 p-8 rounded-2xl shadow-lg text-gray-900 dark:text-gray-100">
    <div class="flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-12 h-12 rounded-full bg-gradient-to-r from-blue-500 to-purple-600 flex items-center justify-center text-white font-bold text-lg shadow">AG</div>
        <h1 class="text-2xl font-bold">عبد الإله عثمان أحمد غويث</h1>
      </div>
      <div class="flex items-center gap-3">
        <a href="index_en.html" class="px-4 py-2 rounded-full bg-blue-500 text-white shadow hover:bg-blue-600 transition">🌐 English</a>
        <button onclick="toggleDarkMode()" class="px-4 py-2 rounded-full bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-200 shadow hover:scale-105 transition">🌙/☀️</button>
      </div>
    </div>
    <div class="text-center mt-6">
      <img src="profile.jpg" alt="صورة شخصية" class="w-40 h-40 rounded-full mx-auto shadow-md">
      <p class="text-gray-600 dark:text-gray-300 mt-2">فني حوشبي</p>
    </div>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">📝 المعلومات الشخصية</h2>
      <ul class="space-y-2">
        <li>📅 <b>تاريخ الميلاد:</b> 01/01/1999</li>
        <li>📍 <b>مكان الميلاد:</b> تعز / المخاء</li>
        <li>🌍 <b>الجنسية:</b> يمني</li>
      </ul>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">💼 الخبرات العملية</h2>
      <ul class="list-disc pr-6">
        <li>موظف في شركة السراج للتجهيزات الصناعية 🏭</li>
      </ul>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">🛠️ المهارات</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
        <div class="bg-gray-50 dark:bg-gray-700 p-3 rounded-lg shadow">🔧 تشغيل وصيانة المعدات الصناعية</div>
        <div class="bg-gray-50 dark:bg-gray-700 p-3 rounded-lg shadow">🤝 العمل بروح الفريق</div>
        <div class="bg-gray-50 dark:bg-gray-700 p-3 rounded-lg shadow">⏱️ الالتزام والانضباط</div>
      </div>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">🌐 اللغات</h2>
      <ul class="flex flex-wrap gap-4">
        <li>🇾🇪 العربية (اللغة الأم)</li>
        <li>🇬🇧 الإنجليزية</li>
      </ul>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">🎯 الاهتمامات والهوايات</h2>
      <div class="flex flex-wrap gap-3">
        <span class="bg-blue-100 dark:bg-blue-900 text-blue-800 dark:text-blue-200 px-3 py-1 rounded-full">📚 تطوير المهارات التقنية</span>
        <span class="bg-green-100 dark:bg-green-900 text-green-800 dark:text-green-200 px-3 py-1 rounded-full">📖 القراءة والاطلاع</span>
        <span class="bg-purple-100 dark:bg-purple-900 text-purple-800 dark:text-purple-200 px-3 py-1 rounded-full">👥 الأنشطة الاجتماعية</span>
      </div>
    </section>
    <section class="mt-10 text-center">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-6">📬 للتواصل</h2>
      <div class="flex justify-center gap-6 text-blue-600 dark:text-blue-400 text-lg">
        <a href="mailto:example@email.com" class="hover:text-blue-800 dark:hover:text-blue-200">📧 البريد الإلكتروني</a>
        <a href="https://github.com/USERNAME" target="_blank" class="hover:text-gray-800 dark:hover:text-gray-200">💻 GitHub</a>
        <a href="https://www.linkedin.com/in/USERNAME" target="_blank" class="hover:text-blue-700 dark:hover:text-blue-200">🔗 LinkedIn</a>
      </div>
      <div class="mt-8">
        <a href="cv_abdullah_ghawith_bilingual.pdf" download class="bg-blue-600 dark:bg-blue-500 text-white px-6 py-2 rounded-full shadow hover:bg-blue-700 dark:hover:bg-blue-600 transition">⬇️ تحميل السيرة الذاتية (عربي + English) PDF</a>
      </div>
    </section>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CV - Abdelilah Othman Ahmed Ghawith</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
      if (document.documentElement.classList.contains('dark')) {
        localStorage.setItem('theme', 'dark');
      } else {
        localStorage.setItem('theme', 'light');
      }
    }
    if (localStorage.getItem('theme') === 'dark') {
      document.documentElement.classList.add('dark');
    }
  </script>
</head>
<body class="bg-gray-100 dark:bg-gray-900 font-sans transition duration-500">
  <div class="max-w-3xl mx-auto my-10 bg-white dark:bg-gray-800 p-8 rounded-2xl shadow-lg text-gray-900 dark:text-gray-100">
    <div class="flex items-center justify-between">
      <div class="flex items-center gap-3">
        <div class="w-12 h-12 rounded-full bg-gradient-to-r from-blue-500 to-purple-600 flex items-center justify-center text-white font-bold text-lg shadow">AG</div>
        <h1 class="text-2xl font-bold">Abdelilah Othman Ahmed Ghawith</h1>
      </div>
      <div class="flex items-center gap-3">
        <a href="index.html" class="px-4 py-2 rounded-full bg-blue-500 text-white shadow hover:bg-blue-600 transition">🌐 العربية</a>
        <button onclick="toggleDarkMode()" class="px-4 py-2 rounded-full bg-gray-200 dark:bg-gray-700 text-gray-800 dark:text-gray-200 shadow hover:scale-105 transition">🌙/☀️</button>
      </div>
    </div>
    <div class="text-center mt-6">
      <img src="profile.jpg" alt="Profile Photo" class="w-40 h-40 rounded-full mx-auto shadow-md">
      <p class="text-gray-600 dark:text-gray-300 mt-2">Technical Specialist (Houshbi)</p>
    </div>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">📝 Personal Information</h2>
      <ul class="space-y-2">
        <li>📅 <b>Date of Birth:</b> 01/01/1999</li>
        <li>📍 <b>Place of Birth:</b> Taiz / Mokha</li>
        <li>🌍 <b>Nationality:</b> Yemeni</li>
      </ul>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">💼 Work Experience</h2>
      <ul class="list-disc pl-6">
        <li>Employee at Al-Siraj Industrial Equipment Company 🏭</li>
      </ul>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">🛠️ Skills</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
        <div class="bg-gray-50 dark:bg-gray-700 p-3 rounded-lg shadow">🔧 Operation & Maintenance of Industrial Equipment</div>
        <div class="bg-gray-50 dark:bg-gray-700 p-3 rounded-lg shadow">🤝 Teamwork & Collaboration</div>
        <div class="bg-gray-50 dark:bg-gray-700 p-3 rounded-lg shadow">⏱️ Discipline & Punctuality</div>
      </div>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">🌐 Languages</h2>
      <ul class="flex flex-wrap gap-4">
        <li>🇾🇪 Arabic (Native)</li>
        <li>🇬🇧 English</li>
      </ul>
    </section>
    <section class="mt-8">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-4">🎯 Interests & Hobbies</h2>
      <div class="flex flex-wrap gap-3">
        <span class="bg-blue-100 dark:bg-blue-900 text-blue-800 dark:text-blue-200 px-3 py-1 rounded-full">📚 Developing Technical Skills</span>
        <span class="bg-green-100 dark:bg-green-900 text-green-800 dark:text-green-200 px-3 py-1 rounded-full">📖 Reading & Self-Learning</span>
        <span class="bg-purple-100 dark:bg-purple-900 text-purple-800 dark:text-purple-200 px-3 py-1 rounded-full">👥 Social Activities</span>
      </div>
    </section>
    <section class="mt-10 text-center">
      <h2 class="text-xl font-semibold border-b-2 border-gray-300 dark:border-gray-600 pb-2 mb-6">📬 Contact</h2>
      <div class="flex justify-center gap-6 text-blue-600 dark:text-blue-400 text-lg">
        <a href="mailto:example@email.com" class="hover:text-blue-800 dark:hover:text-blue-200">📧 Email</a>
        <a href="https://github.com/USERNAME" target="_blank" class="hover:text-gray-800 dark:hover:text-gray-200">💻 GitHub</a>
        <a href="https://www.linkedin.com/in/USERNAME" target="_blank" class="hover:text-blue-700 dark:hover:text-blue-200">🔗 LinkedIn</a>
      </div>
      <div class="mt-8">
        <a href="cv_abdullah_ghawith_bilingual.pdf" download class="bg-blue-600 dark:bg-blue-500 text-white px-6 py-2 rounded-full shadow hover:bg-blue-700 dark:hover:bg-blue-600 transition">⬇️ Download CV (Arabic + English) PDF</a>
      </div>
    </section>
  </div>
</body>
</html>
