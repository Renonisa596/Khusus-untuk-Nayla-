<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Pagi, Nayla!</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f9ff; /* Warna latar belakang biru muda */
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4">
    <div class="bg-white rounded-xl shadow-lg p-8 md:p-12 max-w-lg w-full text-center transform transition-all duration-300 hover:scale-105">
        <!-- Header dengan warna gradien -->
        <h1 class="text-4xl md:text-5xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-blue-500 to-purple-600 mb-6">
            Selamat Pagi, Nayla!
        </h1>

        <!-- Gambar yang relevan dengan selamat pagi -->
        <img
            src="https://placehold.co/400x250/a78bfa/ffffff?text=Pagi+Ceria"
            alt="Gambar Pagi Ceria"
            class="w-full h-auto rounded-lg shadow-md mb-8 mx-auto"
            onerror="this.onerror=null;this.src='https://placehold.co/400x250/a78bfa/ffffff?text=Selamat+Pagi';"
        >

        <!-- Pesan selamat pagi -->
        <p class="text-gray-700 text-lg md:text-xl leading-relaxed mb-8">
            Semoga harimu dipenuhi dengan kebahagiaan, senyum, dan semua hal baik.
            Awali pagimu dengan semangat baru dan energi positif!
        </p>

        <!-- Pesan tambahan atau penutup -->
        <p class="text-gray-600 text-base md:text-lg italic">
            Dari seseorang yang selalu mendoakan yang terbaik untukmu.
        </p>
    </div>
</body>
</html>
