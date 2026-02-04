<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>КИБЕРЩИТ | Проект для школьников</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {--primary-color: #004d98;--secondary-color: #a50044;--accent-color: #edbb00;}
        body {font-family: 'Inter', sans-serif;background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 100%);color: #f8f9fa;overflow-x: hidden;}
        .glassmorphism {background: rgba(255, 255, 255, 0.05);backdrop-filter: blur(10px);border: 1px solid rgba(255, 255, 255, 0.1);box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);}
        .gradient-text {background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));-webkit-background-clip: text;-webkit-text-fill-color: transparent;}
        .barcelona-gradient {background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));}
        .video-container {position: relative;padding-bottom: 56.25%;height: 0;overflow: hidden;border-radius: 12px;}
        .video-container iframe {position: absolute;top: 0;left: 0;width: 100%;height: 100%;border: none;}
    </style>
</head>
<body class="min-h-screen">
    <header class="sticky top-0 glassmorphism">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <div class="w-10 h-10 rounded-full barcelona-gradient flex items-center justify-center">
                        <i class="fas fa-shield-alt text-white"></i>
                    </div>
                    <div><h1 class="text-2xl font-bold">КИБЕРЩИТ</h1><p class="text-xs text-gray-400">Проект для школьников</p></div>
                </div>
            </div>
        </div>
    </header>

    <section class="container mx-auto px-4 py-12 md:py-20">
        <div class="max-w-4xl mx-auto text-center">
            <div class="glassmorphism rounded-2xl p-8 md:p-12 mb-10">
                <h2 class="text-4xl md:text-6xl font-bold mb-6 gradient-text">КАРТА — НЕ ИГРУШКА</h2>
                <p class="text-xl md:text-2xl text-gray-300 mb-8">Дропперство ломает жизни. Узнай, как не стать соучастником преступления.</p>
            </div>
        </div>
    </section>

    <section class="container mx-auto px-4 py-12 md:py-20">
        <div class="max-w-5xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-2">О ПРОЕКТЕ</h2>
            <div class="glassmorphism rounded-2xl p-6 md:p-8">
                <h3 class="text-2xl font-bold mb-6 text-center">Обучающее видео</h3>
                <div class="video-container">
                    <iframe src="https://vk.com/video_ext.php?oid=-49388814&id=456314171&hd=2" 
                            allowfullscreen title="КИБЕРЩИТ - Обучающее видео">
                    </iframe>
                </div>
            </div>
        </div>
    </section>

    <footer class="border-t border-gray-800 py-8">
        <div class="container mx-auto px-4">
            <div class="text-center">
                <p class="text-gray-400">© 2026 КИБЕРЩИТ | ПРОЕКТ ДЛЯ ШКОЛЬНИКОВ</p>
            </div>
        </div>
    </footer>
</body>
</html>
