<!DOCTYPE html>
<html lang="az">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Teymur Hesenov | KiberLife & Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Plus+Jakarta+Sans:wght@300;400;600;800&display=swap" rel="stylesheet">
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            brand: '#741FFF',
            brandDark: '#5612C7',
            brandLight: '#A13FFF',
            bgDark: '#0B0C10',
            cardDark: '#12141C',
            accentGlow: '#741FFF33'
          },
          fontFamily: {
            sans: ['Plus Jakarta Sans', 'sans-serif'],
            mono: ['Fira Code', 'monospace']
          }
        }
      }
    }
  </script>
  <style>
    body {
      background-color: #0B0C10;
      color: #E2E8F0;
      font-family: 'Plus Jakarta Sans', sans-serif;
    }
    .glass-card {
      background: rgba(18, 20, 28, 0.75);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(116, 31, 255, 0.18);
      box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
    }
    .glass-card:hover {
      border-color: rgba(161, 63, 255, 0.45);
      box-shadow: 0 12px 40px 0 rgba(116, 31, 255, 0.25);
    }
    .brand-gradient-text {
      background: linear-gradient(135deg, #A13FFF 0%, #741FFF 50%, #60A5FA 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .brand-gradient-bg {
      background: linear-gradient(135deg, #741FFF 0%, #A13FFF 100%);
    }
    .custom-scrollbar::-webkit-scrollbar {
      width: 6px;
    }
    .custom-scrollbar::-webkit-scrollbar-track {
      background: #0B0C10;
    }
    .custom-scrollbar::-webkit-scrollbar-thumb {
      background: #741FFF;
      border-radius: 10px;
    }
  </style>
</head>
<body class="custom-scrollbar min-h-screen flex flex-col justify-between selection:bg-brand selection:text-white">

  <!-- Header / Navigation -->
  <header class="sticky top-0 z-50 backdrop-blur-md bg-bgDark/80 border-b border-brand/20">
    <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 rounded-xl brand-gradient-bg flex items-center justify-center font-bold text-white shadow-lg shadow-brand/40">
          KL
        </div>
        <div>
          <span class="text-xl font-extrabold tracking-wider text-white">Kiber<span class="text-brandLight">Life</span></span>
          <span class="hidden sm:inline-block text-xs text-gray-400 border-l border-gray-700 ml-2 pl-2">Fikirdən Texnologiyaya</span>
        </div>
      </div>

      <nav class="hidden md:flex items-center space-x-8 text-sm font-semibold text-gray-300">
        <a href="#about" class="hover:text-brandLight transition-colors">Haqqımda</a>
        <a href="#experience" class="hover:text-brandLight transition-colors">Təcrübə & Təhsil</a>
        <a href="#startup" class="hover:text-brandLight transition-colors">KiberLife & Startup</a>
        <a href="#projects" class="hover:text-brandLight transition-colors">Projelər</a>
        <a href="#tech" class="hover:text-brandLight transition-colors">Texnologiyalar</a>
        <a href="#terminal" class="hover:text-brandLight transition-colors">Terminal</a>
      </nav>

      <a href="#contact" class="px-5 py-2.5 rounded-xl brand-gradient-bg text-white text-sm font-semibold hover:opacity-90 transition-all shadow-md shadow-brand/30">
        Əlaqə
      </a>
    </div>
  </header>

  <main class="max-w-7xl mx-auto px-6 py-12 space-y-24 flex-grow">

    <!-- Hero Section -->
    <section id="about" class="grid md:grid-cols-12 gap-12 items-center">
      <div class="md:col-span-7 space-y-6">
        <div class="inline-flex items-center space-x-2 px-3.5 py-1.5 rounded-full bg-brand/10 border border-brand/30 text-brandLight text-xs font-semibold">
          <span class="w-2 h-2 rounded-full bg-brandLight animate-pulse"></span>
          <span>Founder & Lead Developer @ KiberLife</span>
        </div>
        <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white leading-tight">
          Teymur Hesenov
        </h1>
        <p class="text-xl font-medium brand-gradient-text">
          Computer Engineer | Cyber Security | Full-Stack & Hardware Innovator
        </p>
        <p class="text-gray-400 leading-relaxed text-base">
          Proqram təminatı, siber təhlükəsizlik, süni intellekt və aparat sistemləri (IoT/Robotics) üzrə innovativ həllər hazırlayıram. Naxçıvan Dövlət Universitetində (NDU) Python dərsləri üzrə müəllim köməkçisi olmuşam. Şəxsi startupım olan <strong class="text-white">KiberLife</strong> çətiri altında tətbiqlər, təhlükəsizlik sistemləri və əlilliyi olan şəxslər üçün xüsusi köməkçi texnologiyalar qururam.
        </p>

        <div class="flex flex-wrap gap-4 pt-2">
          <a href="#projects" class="px-6 py-3 rounded-xl brand-gradient-bg text-white font-semibold text-sm shadow-lg shadow-brand/30 hover:scale-105 transition-transform">
            🚀 Projelərimi İncələ
          </a>
          <a href="#experience" class="px-6 py-3 rounded-xl glass-card text-white font-semibold text-sm hover:bg-brand/20 transition-all border border-brand/30">
            🎓 Təcrübə & Təhsil
          </a>
        </div>
      </div>

      <div class="md:col-span-5 flex justify-center">
        <div class="relative w-72 h-72 sm:w-80 sm:h-80 rounded-3xl p-1 brand-gradient-bg shadow-2xl shadow-brand/40">
          <div class="w-full h-full bg-bgDark rounded-[22px] overflow-hidden flex items-center justify-center relative group">
            <img src="https://github.com/TeymurHesenov.png" alt="Teymur Hesenov" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
            <div class="absolute inset-0 bg-gradient-to-t from-bgDark/80 via-transparent to-transparent"></div>
            <div class="absolute bottom-4 left-4 right-4 text-center">
              <span class="text-xs font-mono text-brandLight bg-bgDark/90 px-3 py-1 rounded-full border border-brand/40">
                Fikirdən Texnologiyaya ⚡
              </span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Experience & Education Section -->
    <section id="experience" class="space-y-8">
      <div class="border-l-4 border-brand pl-4">
        <h2 class="text-3xl font-extrabold text-white">Təcrübə & Sertifikasiyalar</h2>
        <p class="text-gray-400 text-sm">Akademik fəaliyyət, kurslar və təlimçilik təcrübəsi</p>
      </div>

      <div class="grid md:grid-cols-3 gap-6">

        <!-- Experience 1: NDU Assistant -->
        <div class="glass-card p-6 rounded-2xl space-y-3 relative overflow-hidden border border-brand/30">
          <div class="w-10 h-10 rounded-lg bg-blue-500/10 border border-blue-500/30 flex items-center justify-center text-blue-400 font-bold text-lg">
            <i class="fa-solid fa-chalkboard-user"></i>
          </div>
          <h3 class="text-xl font-bold text-white">Python Müəllim Köməkçisi</h3>
          <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-blue-400 bg-blue-500/10 rounded border border-blue-500/30">
            Naxçıvan Dövlət Universiteti (NDU)
          </span>
          <p class="text-gray-300 text-sm leading-relaxed">
            NDU-da tələbələrə Python proqramlaşdırma dilinin əsasları, alqoritmlər və praktiki kodlaşdırma tapşırıqlarında müəllim köməkçisi (Teaching Assistant) kimi dəstək olmuşam, mentorluq etmişəm.
          </p>
        </div>

        <!-- Experience 2: FullStack Course -->
        <div class="glass-card p-6 rounded-2xl space-y-3 relative overflow-hidden border border-brand/30">
          <div class="w-10 h-10 rounded-lg bg-purple-500/10 border border-purple-500/30 flex items-center justify-center text-purple-400 font-bold text-lg">
            <i class="fa-solid fa-code"></i>
          </div>
          <h3 class="text-xl font-bold text-white">Full-Stack Development</h3>
          <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-purple-400 bg-purple-500/10 rounded border border-purple-500/30">
            Kurs Məzunu (Completed)
          </span>
          <p class="text-gray-300 text-sm leading-relaxed">
            Müasir frontend və backend texnologiyalarını, REST API, verilənlər bazası arxitekturasını və tammiqyaslı veb tətbiqlərinin sıfırdan qurulmasını əhatə edən Full-Stack kursunu uğurla bitirmişəm.
          </p>
        </div>

        <!-- Experience 3: Cyber Security Course -->
        <div class="glass-card p-6 rounded-2xl space-y-3 relative overflow-hidden border border-brand/30">
          <div class="w-10 h-10 rounded-lg bg-emerald-500/10 border border-emerald-500/30 flex items-center justify-center text-emerald-400 font-bold text-lg">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <h3 class="text-xl font-bold text-white">Siber Təhlükəsizlik Təlimi</h3>
          <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-emerald-400 bg-emerald-500/10 rounded border border-emerald-500/30">
            Davam Edir (Ongoing)
          </span>
          <p class="text-gray-300 text-sm leading-relaxed">
            Şəbəkə təhlükəsizliyi, sızma testləri (Penetration Testing), zəiflik analizi və zərərli proqramların öyrənilməsi istiqamətində peşəkar Siber Güvenlik kursunda təhsilimi davam etdirirəm.
          </p>
        </div>

      </div>
    </section>

    <!-- Company & Startup Section -->
    <section id="startup" class="space-y-8">
      <div class="border-l-4 border-brand pl-4">
        <h2 class="text-3xl font-extrabold text-white">Şirkət & Əsas Təşəbbüslər</h2>
        <p class="text-gray-400 text-sm">Proqram təminatı, mobil ekosistemlər və innovativ startaplar</p>
      </div>

      <div class="grid md:grid-cols-2 gap-8">
        <!-- KiberLife -->
        <div class="glass-card p-8 rounded-2xl relative overflow-hidden space-y-4">
          <div class="absolute top-0 right-0 w-32 h-32 bg-brand/10 rounded-full blur-2xl"></div>
          <div class="flex items-center justify-between">
            <div class="w-12 h-12 rounded-xl brand-gradient-bg flex items-center justify-center font-bold text-white text-xl shadow-lg">
              KL
            </div>
            <span class="px-3 py-1 text-xs font-mono font-semibold text-brandLight bg-brand/10 rounded-full border border-brand/30">
              Şirkət / Studio
            </span>
          </div>
          <h3 class="text-2xl font-bold text-white">KiberLife</h3>
          <p class="text-xs font-mono text-brandLight">"Fikirdən texnologiyaya."</p>
          <p class="text-gray-300 text-sm leading-relaxed">
            Veb və mobil platformalar, proqram təminatının hazırlanması, avtomatlaşdırma, siber təhlükəsizlik və MVP layihələrinin sıfırdan qurulması ilə məşğul olan texnologiya studiyası.
          </p>
          <div class="pt-2 flex flex-wrap gap-2 text-xs font-mono text-gray-400">
            <span class="px-2.5 py-1 bg-white/5 rounded-lg border border-white/10">#SoftwareDev</span>
            <span class="px-2.5 py-1 bg-white/5 rounded-lg border border-white/10">#CyberSecurity</span>
            <span class="px-2.5 py-1 bg-white/5 rounded-lg border border-white/10">#WebApps</span>
          </div>
        </div>

        <!-- ZallPass -->
        <div class="glass-card p-8 rounded-2xl relative overflow-hidden space-y-4">
          <div class="absolute top-0 right-0 w-32 h-32 bg-brandLight/10 rounded-full blur-2xl"></div>
          <div class="flex items-center justify-between">
            <div class="w-12 h-12 rounded-xl bg-gradient-to-tr from-blue-600 to-indigo-500 flex items-center justify-center font-bold text-white text-xl shadow-lg">
              <i class="fa-solid fa-mobile-screen-button"></i>
            </div>
            <span class="px-3 py-1 text-xs font-mono font-semibold text-blue-400 bg-blue-500/10 rounded-full border border-blue-500/30">
              iOS & Android Mobile App
            </span>
          </div>
          <h3 class="text-2xl font-bold text-white">ZallPass</h3>
          <p class="text-xs font-mono text-blue-400">Mobil Keçid və İdarəetmə Sistemi</p>
          <p class="text-gray-300 text-sm leading-relaxed">
            iOS və Android platformaları üçün hazırlanmış xüsusi mobil proqram. İstifadəçilərin sürətli, təhlükəsiz və rəqəmsal keçid/doğrulama sistemlərinə çıxışını təmin edir.
          </p>
          <div class="pt-2 flex flex-wrap gap-2 text-xs font-mono text-gray-400">
            <span class="px-2.5 py-1 bg-white/5 rounded-lg border border-white/10">#iOS</span>
            <span class="px-2.5 py-1 bg-white/5 rounded-lg border border-white/10">#Android</span>
            <span class="px-2.5 py-1 bg-white/5 rounded-lg border border-white/10">#MobileApp</span>
          </div>
        </div>
      </div>
    </section>

    <!-- Key Projects Section -->
    <section id="projects" class="space-y-8">
      <div class="border-l-4 border-brand pl-4">
        <h2 class="text-3xl font-extrabold text-white">Öne Çıxan Mühəndislik Layihələri</h2>
        <p class="text-gray-400 text-sm">Sosial məsuliyyət, aparat həlləri, siber güvenlik və AI innovasiyaları</p>
      </div>

      <div class="grid md:grid-cols-3 gap-6">

        <!-- Project 1: Eye Control System -->
        <div class="glass-card p-6 rounded-2xl flex flex-col justify-between space-y-4 hover:-translate-y-1 transition-transform">
          <div class="space-y-3">
            <div class="w-10 h-10 rounded-lg bg-emerald-500/10 border border-emerald-500/30 flex items-center justify-center text-emerald-400 font-bold text-lg">
              <i class="fa-solid fa-eye"></i>
            </div>
            <h3 class="text-xl font-bold text-white">Gözlə İdarə Edilən Kompüter Sistemi</h3>
            <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-emerald-400 bg-emerald-500/10 rounded border border-emerald-500/30">
              Əlillər üçün Sosial Layihə
            </span>
            <p class="text-gray-300 text-sm leading-relaxed">
              Əlləri olmayan və ya hərəkət məhdudiyyətli şəxslər üçün hazırladığım xüsusi kompüter idarəetmə sistemi. Arxa plan tətbiqi vasitəsilə sıfırdan mausu, klaviaturanı və bütün kompüter funksiyalarını yalnız göz hərəkətləri ilə idarə etməyə imkan verir.
            </p>
          </div>
          <div class="pt-2 text-xs font-mono text-gray-400 border-t border-white/10 flex justify-between">
            <span>#Accessibility</span>
            <span>#ComputerVision</span>
          </div>
        </div>

        <!-- Project 2: Gas Leak & SMS Alarm -->
        <div class="glass-card p-6 rounded-2xl flex flex-col justify-between space-y-4 hover:-translate-y-1 transition-transform">
          <div class="space-y-3">
            <div class="w-10 h-10 rounded-lg bg-amber-500/10 border border-amber-500/30 flex items-center justify-center text-amber-400 font-bold text-lg">
              <i class="fa-solid fa-triangle-exclamation"></i>
            </div>
            <h3 class="text-xl font-bold text-white">Qaz Sızması Təhlükəsizlik & SMS Sistemi</h3>
            <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-amber-400 bg-amber-500/10 rounded border border-amber-500/30">
              IoT & Smart Safety
            </span>
            <p class="text-gray-300 text-sm leading-relaxed">
              Arduino və sensorlar əsasında qurulmuş qaz sızması xəbərdarlıq sistemi. Sızma aşkar edildikdə avtomatik olaraq rele sistemini işə salır, səsli alarm verir və təyin olunmuş nömrəyə dərhal SMS bildirişi göndərir.
            </p>
          </div>
          <div class="pt-2 text-xs font-mono text-gray-400 border-t border-white/10 flex justify-between">
            <span>#Arduino</span>
            <span>#GSM_SMS</span>
          </div>
        </div>

        <!-- Project 3: Radar Detection System -->
        <div class="glass-card p-6 rounded-2xl flex flex-col justify-between space-y-4 hover:-translate-y-1 transition-transform">
          <div class="space-y-3">
            <div class="w-10 h-10 rounded-lg bg-cyan-500/10 border border-cyan-500/30 flex items-center justify-center text-cyan-400 font-bold text-lg">
              <i class="fa-solid fa-radar"></i>
            </div>
            <h3 class="text-xl font-bold text-white">Ultrasonik Radar Sistemi</h3>
            <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-cyan-400 bg-cyan-500/10 rounded border border-cyan-500/30">
              Hardware & Visualization
            </span>
            <p class="text-gray-300 text-sm leading-relaxed">
              Ultrasonik sensorlar və servo motorlar vasitəsilə 180 dərəcəlik bucaqda obyektləri məsafədən təyin edən və məlumatları interaktiv visual interfeysdə göstərən radar aparatı.
            </p>
          </div>
          <div class="pt-2 text-xs font-mono text-gray-400 border-t border-white/10 flex justify-between">
            <span>#Robotics</span>
            <span>#Processing</span>
          </div>
        </div>

        <!-- Project 4: Test Malware & Defense -->
        <div class="glass-card p-6 rounded-2xl flex flex-col justify-between space-y-4 hover:-translate-y-1 transition-transform">
          <div class="space-y-3">
            <div class="w-10 h-10 rounded-lg bg-red-500/10 border border-red-500/30 flex items-center justify-center text-red-400 font-bold text-lg">
              <i class="fa-solid fa-bug"></i>
            </div>
            <h3 class="text-xl font-bold text-white">Test Virusları & Analiz Skriptləri</h3>
            <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-red-400 bg-red-500/10 rounded border border-red-500/30">
              Cyber Security Lab
            </span>
            <p class="text-gray-300 text-sm leading-relaxed">
              Sistem zəifliklərini öyrənmək, antivirus mexanizmlərini test etmək və zərərli proqramların iş prinsiplərini analiz etmək üçün təhlükəsiz laboratoriya mühitində yazılmış test virusları və analiz vasitələri.
            </p>
          </div>
          <div class="pt-2 text-xs font-mono text-gray-400 border-t border-white/10 flex justify-between">
            <span>#MalwareAnalysis</span>
            <span>#Python</span>
          </div>
        </div>

        <!-- Project 5: Hack The Box Sherlocks -->
        <div class="glass-card p-6 rounded-2xl flex flex-col justify-between space-y-4 hover:-translate-y-1 transition-transform">
          <div class="space-y-3">
            <div class="w-10 h-10 rounded-lg bg-purple-500/10 border border-purple-500/30 flex items-center justify-center text-purple-400 font-bold text-lg">
              <i class="fa-solid fa-magnifying-glass font-bold"></i>
            </div>
            <h3 class="text-xl font-bold text-white">HTB Sherlocks & Forensics</h3>
            <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-purple-400 bg-purple-500/10 rounded border border-purple-500/30">
              Hack The Box
            </span>
            <p class="text-gray-300 text-sm leading-relaxed">
              Hack The Box platformasında Blue Teaming, incident response və rəqəmsal kriminalistika (Digital Forensics) sahəsində həll edilmiş mürəkkəb Sherlocks ssenariləri və log analizləri.
            </p>
          </div>
          <div class="pt-2 text-xs font-mono text-gray-400 border-t border-white/10 flex justify-between">
            <span>#BlueTeam</span>
            <span>#DFIR</span>
          </div>
        </div>

        <!-- Project 6: AI Prompts & Design -->
        <div class="glass-card p-6 rounded-2xl flex flex-col justify-between space-y-4 hover:-translate-y-1 transition-transform">
          <div class="space-y-3">
            <div class="w-10 h-10 rounded-lg bg-pink-500/10 border border-pink-500/30 flex items-center justify-center text-pink-400 font-bold text-lg">
              <i class="fa-solid fa-wand-magic-sparkles"></i>
            </div>
            <h3 class="text-xl font-bold text-white">AI Prompts, Brand & UI/UX</h3>
            <span class="inline-block px-2.5 py-0.5 text-[10px] font-mono font-semibold text-pink-400 bg-pink-500/10 rounded border border-pink-500/30">
              Creative & AI Engineering
            </span>
            <p class="text-gray-300 text-sm leading-relaxed">
              Süni intellekt modelləri üçün xüsusi prompt mühəndisliyi şablonları, Canva ilə hazırlanmış brend loqoları, afişa dizaynları və Figma üzərində tətbiq interfeysi prototipləri.
            </p>
          </div>
          <div class="pt-2 text-xs font-mono text-gray-400 border-t border-white/10 flex justify-between">
            <span>#Canva_Figma</span>
            <span>#PromptEngineering</span>
          </div>
        </div>

      </div>
    </section>

    <!-- Tech Ecosystem Section -->
    <section id="tech" class="space-y-8">
      <div class="border-l-4 border-brand pl-4">
        <h2 class="text-3xl font-extrabold text-white">Texnologiya Ekosistemi & Alətlər</h2>
        <p class="text-gray-400 text-sm">Gündəlik istifadə etdiyim proqramlar, süni intellektlər və əməliyyat sistemləri</p>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">

        <!-- Tools & Apps -->
        <div class="glass-card p-6 rounded-2xl space-y-4">
          <h3 class="text-lg font-bold text-white flex items-center space-x-2">
            <i class="fa-solid fa-screwdriver-wrench text-brandLight"></i>
            <span>Tətbiqlər & IDE-lər</span>
          </h3>
          <ul class="space-y-2 text-sm text-gray-300 font-mono">
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Antigravity</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>VS Code</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Xcode</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Arduino IDE & Wokwi</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>SDR++ & Postman</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Git & GitHub</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Pinokio & Figma</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Canva</span></li>
          </ul>
        </div>

        <!-- AI Ecosystem -->
        <div class="glass-card p-6 rounded-2xl space-y-4">
          <h3 class="text-lg font-bold text-white flex items-center space-x-2">
            <i class="fa-solid fa-brain text-brandLight"></i>
            <span>Süni İntellekt (AI)</span>
          </h3>
          <ul class="space-y-2 text-sm text-gray-300 font-mono">
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Gemini (Google)</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Claude (Anthropic)</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Qwen (Alibaba AI)</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>OpenAI Codex / ChatGPT</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Custom AI Prompts</span></li>
          </ul>
        </div>

        <!-- Operating Systems -->
        <div class="glass-card p-6 rounded-2xl space-y-4">
          <h3 class="text-lg font-bold text-white flex items-center space-x-2">
            <i class="fa-solid fa-desktop text-brandLight"></i>
            <span>Əməliyyat Sistemləri</span>
          </h3>
          <ul class="space-y-2 text-sm text-gray-300 font-mono">
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Linux (Kali, Ubuntu, Tails)</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>macOS (Apple Silicon M5)</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Windows</span></li>
          </ul>
        </div>

        <!-- Practice & Labs -->
        <div class="glass-card p-6 rounded-2xl space-y-4">
          <h3 class="text-lg font-bold text-white flex items-center space-x-2">
            <i class="fa-solid fa-flask text-brandLight"></i>
            <span>Laboratoriya & Təlim</span>
          </h3>
          <ul class="space-y-2 text-sm text-gray-300 font-mono">
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>NDU Python Teaching Asst.</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Full-Stack Development</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Siber Güvenlik Kursu</span></li>
            <li class="flex items-center space-x-2"><span class="text-brandLight">›</span> <span>Hack The Box (Sherlocks)</span></li>
          </ul>
        </div>

      </div>
    </section>

    <!-- Terminal Simulator Section -->
    <section id="terminal" class="space-y-6">
      <div class="border-l-4 border-brand pl-4">
        <h2 class="text-3xl font-extrabold text-white">KiberLife Interactive Terminal</h2>
        <p class="text-gray-400 text-sm">Aşağıdakı əmrləri yazaraq sistemi yoxlaya bilərsiniz: <code class="text-brandLight font-mono">help</code>, <code class="text-brandLight font-mono">exp</code>, <code class="text-brandLight font-mono">projects</code>, <code class="text-brandLight font-mono">startup</code>, <code class="text-brandLight font-mono">clear</code></p>
      </div>

      <div class="glass-card rounded-2xl overflow-hidden border border-brand/30 shadow-2xl">
        <div class="bg-bgDark px-4 py-3 flex items-center justify-between border-b border-white/10">
          <div class="flex items-center space-x-2">
            <span class="w-3 h-3 rounded-full bg-red-500"></span>
            <span class="w-3 h-3 rounded-full bg-yellow-500"></span>
            <span class="w-3 h-3 rounded-full bg-green-500"></span>
            <span class="text-xs font-mono text-gray-400 ml-2">teymur@kiberlife-terminal ~ %</span>
          </div>
          <span class="text-xs font-mono text-brandLight">zsh / bash</span>
        </div>

        <div id="terminal-body" class="p-6 font-mono text-sm space-y-3 h-72 overflow-y-auto custom-scrollbar bg-black/60 text-gray-300">
          <div>Welcome to <span class="text-brandLight font-bold">KiberLife Terminal Shell v2.5</span>. Type <span class="text-yellow-400">'help'</span> for a list of available commands.</div>
        </div>

        <div class="px-6 py-3 bg-bgDark/80 border-t border-white/10 flex items-center space-x-2">
          <span class="text-brandLight font-mono text-sm font-bold">teymur@kiberlife %</span>
          <input type="text" id="terminal-input" class="bg-transparent flex-grow font-mono text-sm text-white focus:outline-none" placeholder="Əmr daxil edin..." autofocus>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="glass-card p-10 rounded-3xl text-center space-y-6 border border-brand/30 relative overflow-hidden">
      <div class="absolute -top-24 -left-24 w-48 h-48 bg-brand/20 rounded-full blur-3xl"></div>
      <div class="absolute -bottom-24 -right-24 w-48 h-48 bg-brandLight/20 rounded-full blur-3xl"></div>

      <h2 class="text-3xl font-extrabold text-white">Bir Layihəniz Var? Birlikdə Quraq!</h2>
      <p class="text-gray-300 max-w-2xl mx-auto text-sm leading-relaxed">
        KiberLife çətiri altında yeni ideyaları reallaşdırmaq, proqram təminatı hazırlamaq, mobil tətbiqlər və siber təhlükəsizlik sahəsində əməkdaşlıq üçün mənə yazın.
      </p>

      <div class="flex flex-wrap justify-center gap-6 pt-4">
        <a href="mailto:teymurhasanovh@gmail.com" class="flex items-center space-x-2 px-6 py-3 rounded-xl brand-gradient-bg text-white font-semibold text-sm shadow-lg shadow-brand/30 hover:scale-105 transition-transform">
          <i class="fa-solid fa-envelope"></i>
          <span>teymurhasanovh@gmail.com</span>
        </a>
        <a href="https://linkedin.com/in/teymur-hesenov-579a07234" target="_blank" class="flex items-center space-x-2 px-6 py-3 rounded-xl glass-card text-white font-semibold text-sm hover:bg-brand/20 transition-all border border-brand/30">
          <i class="fa-brands fa-linkedin"></i>
          <span>LinkedIn Profilim</span>
        </a>
        <a href="https://github.com/TeymurHesenov" target="_blank" class="flex items-center space-x-2 px-6 py-3 rounded-xl glass-card text-white font-semibold text-sm hover:bg-brand/20 transition-all border border-brand/30">
          <i class="fa-brands fa-github"></i>
          <span>GitHub Repository</span>
        </a>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="border-t border-brand/20 py-8 text-center text-xs text-gray-500 font-mono">
    <div class="max-w-7xl mx-auto px-6 flex flex-col sm:flex-row justify-between items-center space-y-4 sm:space-y-0">
      <div>
        © 2026 <span class="text-white font-semibold">Teymur Hesenov</span> | <span class="text-brandLight">KiberLife</span>. Bütün hüquqlar qorunur.
      </div>
      <div>
        Always learning. Always building. Always exploring technology. ⚡
      </div>
    </div>
  </footer>

  <script>
    // Interactive Terminal Functionality
    const terminalBody = document.getElementById('terminal-body');
    const terminalInput = document.getElementById('terminal-input');

    const commands = {
      'help': 'Mövcud əmrlər:\n - <span class="text-yellow-400">exp</span>: Təcrübə, NDU müəllim köməkçiliyi və kurslar\n - <span class="text-yellow-400">startup</span>: KiberLife və ZallPass haqqında məlumat\n - <span class="text-yellow-400">projects</span>: Əsas mühəndislik layihələrim\n - <span class="text-yellow-400">tools</span>: İstifadə etdiyim alətlər və AI-lar\n - <span class="text-yellow-400">about</span>: Teymur Hesenov haqqında qısa məlumat\n - <span class="text-yellow-400">clear</span>: Terminal ekranını təmizləyir',
      'exp': '🎓 <span class="text-blue-400 font-bold">NDU Python Assistant:</span> Naxçıvan Dövlət Universitetində tələbələrə Python dərslərində köməkçilik və mentorluq.\n💻 <span class="text-purple-400 font-bold">Full-Stack Course:</span> Uğurla bitirilib.\n🛡️ <span class="text-emerald-400 font-bold">Siber Güvenlik Kursu:</span> Təhsil davam edir.',
      'startup': '<span class="text-brandLight font-bold">KiberLife:</span> "Fikirdən texnologiyaya" - Proqram, Veb, Siber Güvenlik və MVP Studio.\n<span class="text-blue-400 font-bold">ZallPass:</span> iOS və Android üçün hazırlanmış keçid idarəetmə mobil proqramı.',
      'projects': '1. Əlillər üçün Gözlə İdarə Edilən Kompüter Sistemi (Maus & Klaviatur)\n2. Qaz Sızması Alarm & Otomatik SMS Bildiriş Sistemi\n3. Ultrasonik Radar Vizualizasiya Aparatı\n4. Siber Güvenlik Test Virusları & HTB Sherlocks',
      'tools': 'IDE: Antigravity, VS Code, Xcode, Arduino IDE, Wokwi\nAI: Gemini, Claude, Qwen, Codex\nOS: Linux (Kali/Ubuntu/Tails), macOS, Windows\nTools: SDR++, Postman, Pinokio, Figma, Canva',
      'about': 'Teymur Hesenov - Kompüter Mühəndisliyi Tələbəsi, NDU Müəllim Köməkçisi, KiberLife-ın Təsisçisi və Proqramçı.'
    };

    terminalInput.addEventListener('keydown', function(e) {
      if (e.key === 'Enter') {
        const inputVal = this.value.trim().toLowerCase();
        
        // Render Prompt
        const promptDiv = document.createElement('div');
        promptDiv.innerHTML = `<span class="text-brandLight font-bold">teymur@kiberlife %</span> ${this.value}`;
        terminalBody.appendChild(promptDiv);

        if (inputVal === 'clear') {
          terminalBody.innerHTML = '';
        } else if (commands[inputVal]) {
          const resDiv = document.createElement('div');
          resDiv.className = 'text-gray-300 pl-4 border-l-2 border-brand/50 my-1 whitespace-pre-line';
          resDiv.innerHTML = commands[inputVal];
          terminalBody.appendChild(resDiv);
        } else if (inputVal !== '') {
          const errDiv = document.createElement('div');
          errDiv.className = 'text-red-400 pl-4';
          errDiv.innerHTML = `command not found: ${inputVal}. Type 'help' for available commands.`;
          terminalBody.appendChild(errDiv);
        }

        this.value = '';
        terminalBody.scrollTop = terminalBody.scrollHeight;
      }
    });
  </script>
</body>
</html>
