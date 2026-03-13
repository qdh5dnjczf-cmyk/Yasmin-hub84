# Yasmin-hub84
Indix-love<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>ياسمين HUB | استشارات الكتابة والتصميم - عمّان</title>
    <meta name="description" content="هندسة النظم وشاعرية التصميم. حجز استشارات شخصية مع ياسمين شهاب، الكتابة الوجدانية وهوية بصرية. عمّان، الأردن.">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        :root {
            --pearl: #FDFCF0;
            --jasmine: #85A97A;
            --charcoal: #333333;
            --gold: #D4AF37;
        }
        body {
            font-family: 'Tajawal', sans-serif;
            background-color: var(--pearl);
            color: var(--charcoal);
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
        }
        .app-shell {
            max-width: 500px;
            margin: 0 auto;
            background: #FCFCFA;
            min-height: 100vh;
            position: relative;
            box-shadow: 0 0 40px rgba(0,0,0,0.03);
        }
        .screen { display: none; animation: slideIn 0.3s ease-out; padding-bottom: 100px; }
        .screen.active { display: block; }
        @keyframes slideIn { from { transform: translateX(20px); opacity: 0; } to { transform: translateX(0); opacity: 1; } }
        
        .jasmine-gradient {
            background: linear-gradient(135deg, #85A97A 0%, #6B8E61 100%);
        }
        .gold-accent { color: var(--gold); }
        .bottom-nav {
            position: fixed;
            bottom: 0;
            width: 100%;
            max-width: 500px;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            display: flex;
            justify-content: space-around;
            padding: 15px 0;
            border-top: 1px solid #f0f0f0;
            z-index: 100;
        }
        .nav-link { color: #A0A0A0; transition: 0.3s; cursor: pointer; text-align: center; }
        .nav-link.active { color: var(--jasmine); }
        
        .floating-card {
            background: white;
            border-radius: 24px;
            box-shadow: 0 10px 30px rgba(133, 169, 122, 0.08);
            border: 1px solid rgba(133, 169, 122, 0.05);
        }
    </style>
</head>
<body>

<div class="app-shell">
    <!-- Header -->
    <header class="p-6 flex justify-between items-center sticky top-0 bg-[#FCFCFA]/80 backdrop-blur-md z-50">
        <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded-2xl jasmine-gradient flex items-center justify-center shadow-lg shadow-[#85A97A]/20">
                <i data-lucide="sparkles" class="text-white w-6 h-6"></i>
            </div>
            <h1 class="font-bold text-xl tracking-tight">ياسمين <span class="text-[#85A97A] font-light">HUB</span></h1>
        </div>
        <button onclick="toggleAdmin()" class="w-10 h-10

