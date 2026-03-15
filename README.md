<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZUTTRADE | Partner Trading Terbaik Anda</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#22c55e',
                            600: '#16a34a',
                            700: '#15803d',
                            900: '#14532d',
                        },
                        accent: {
                            500: '#eab308', // Gold
                            600: '#ca8a04',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a; /* slate-900 */
            color: #f8fafc; /* slate-50 */
        }
        .gradient-text {
            background: linear-gradient(to right, #22c55e, #4ade80);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gradient-bg {
            background: linear-gradient(135deg, rgba(20, 83, 45, 0.2) 0%, rgba(15, 23, 42, 1) 100%);
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-500 selection:text-white">

    <!-- Navigasi -->
    <nav class="fixed top-0 left-0 w-full z-50 bg-slate-900/90 backdrop-blur-md border-b border-slate-800 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center gap-2 cursor-pointer">
                    <i class="fa-solid fa-chart-line text-accent-500 text-3xl"></i>
                    <span class="font-bold text-2xl tracking-tight">ZUTTRADE</span>
                </div>
                
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-slate-300 hover:text-white transition font-medium">Beranda</a>
                    <a href="#keuntungan" class="text-slate-300 hover:text-white transition font-medium">Keuntungan</a>
                    <a href="#daftar" class="bg-brand-600 hover:bg-brand-700 text-white px-6 py-2.5 rounded-full font-semibold transition shadow-lg shadow-brand-500/30">Buka Akun</a>
                </div>

                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-300 hover:text-white focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <div id="mobile-menu" class="hidden md:hidden bg-slate-800 border-b border-slate-700 absolute w-full">
            <div class="px-4 pt-2 pb-6 space-y-2 text-center flex flex-col">
                <a href="#home" class="block px-3 py-3 text-slate-300 hover:text-white hover:bg-slate-700 rounded-md font-medium">Beranda</a>
                <a href="#keuntungan" class="block px-3 py-3 text-slate-300 hover:text-white hover:bg-slate-700 rounded-md font-medium">Keuntungan</a>
                <a href="#daftar" class="block mt-4 bg-brand-600 hover:bg-brand-700 text-white px-3 py-3 rounded-md font-semibold text-center">Buka Akun Sekarang</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-32 pb-20 lg:pt-48 lg:pb-32 gradient-bg relative overflow-hidden">
        <div class="absolute top-0 right-0 -mr-20 -mt-20 w-96 h-96 rounded-full bg-brand-900/30 blur-3xl filter"></div>
        <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 rounded-full bg-accent-500/10 blur-3xl filter"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-slate-800 border border-slate-700 text-sm font-medium text-brand-400 mb-6">
                        <span class="flex h-2 w-2 rounded-full bg-brand-500"></span>
                        Partner Resmi Broker Terpercaya 2026
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight mb-3 leading-tight">
                        Maksimalkan Profit Anda dengan <span class="gradient-text">Fasilitas VIP</span>
                    </h1>
                    <h2 class="text-2xl sm:text-3xl font-bold text-brand-400 mb-4 tracking-wide drop-shadow-md">
                        TRADER'S HOOD FAMILY 📊
                    </h2>
                    <p class="text-lg text-slate-400 mb-8 max-w-2xl mx-auto lg:mx-0">
                        Bergabunglah dengan komunitas trader pemenang. Dapatkan rebate tertinggi, sinyal trading akurat setiap hari, dan edukasi eksklusif tanpa biaya tambahan.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
                        <a href="#daftar" class="bg-brand-600 hover:bg-brand-700 text-white px-8 py-4 rounded-full font-bold text-lg transition shadow-lg shadow-brand-500/30 flex items-center justify-center gap-2">
                            Buka Akun Broker <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <a href="https://wa.me/6288293951568" target="_blank" class="bg-slate-800 hover:bg-slate-700 border border-slate-700 text-white px-8 py-4 rounded-full font-bold text-lg transition flex items-center justify-center gap-2">
                            <i class="fa-brands fa-whatsapp text-green-500 text-xl"></i> Tanya Admin
                        </a>
                    </div>
                    
                    <div class="mt-10 flex items-center justify-center lg:justify-start gap-6 text-slate-400 text-sm font-medium">
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-check-circle text-brand-500"></i> Spread Rendah
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-check-circle text-brand-500"></i> WD Instan
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-check-circle text-brand-500"></i> Regulated
                        </div>
                    </div>
                </div>
                
                <div class="relative hidden lg:block">
                    <div class="relative rounded-2xl border border-slate-700 bg-slate-800/50 p-2 shadow-2xl backdrop-blur-sm flex justify-center">
                        <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Trading Dashboard" class="rounded-xl opacity-90 hover:opacity-100 transition duration-500 w-full h-auto object-contain">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Fasilitas Section -->
    <section id="keuntungan" class="py-24 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-4xl mx-auto mb-16">
                <h2 class="text-brand-500 font-semibold tracking-wide uppercase text-sm mb-2">MENGAPA MEMILIH KAMI?</h2>
                <h3 class="text-3xl md:text-4xl font-bold mb-4">Fasilitas Eksklusif Klien Kami</h3>
                <p class="text-slate-400 text-lg mb-10">Kami memastikan Anda memiliki 'senjata' lengkap untuk bertempur di market.</p>
                
                <!-- Kotak Grup Free -->
                <div class="grid sm:grid-cols-3 gap-6 text-left mb-12">
                    <a href="https://chat.whatsapp.com/LL1VW32Cp5HFX1n45i7LYO" target="_blank" class="relative overflow-hidden bg-slate-900 rounded-2xl p-6 border border-slate-700 hover:border-brand-500/50 transition duration-300 group block shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg')] bg-cover bg-center opacity-40 group-hover:opacity-50 transition duration-300 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-slate-900/60 transition duration-300 group-hover:bg-slate-900/40"></div>
                        <div class="relative z-10">
                            <div class="w-12 h-12 rounded-xl flex items-center justify-center mb-4 border border-brand-500/30 overflow-hidden shadow-sm relative">
                                <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Logo Grup 1" class="w-full h-full object-cover">
                            </div>
                            <h4 class="text-lg font-bold mb-1 text-white drop-shadow-md">Grup Free 1</h4>
                            <p class="text-sm text-slate-200 group-hover:text-brand-300 transition drop-shadow-md">Klik untuk bergabung <i class="fa-solid fa-arrow-right text-xs ml-1"></i></p>
                        </div>
                    </a>

                    <a href="https://chat.whatsapp.com/EasRNABfvdKIGYmzJFkd2A" target="_blank" class="relative overflow-hidden bg-slate-900 rounded-2xl p-6 border border-slate-700 hover:border-brand-500/50 transition duration-300 group block shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg')] bg-cover bg-center opacity-40 group-hover:opacity-50 transition duration-300 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-slate-900/60 transition duration-300 group-hover:bg-slate-900/40"></div>
                        <div class="relative z-10">
                            <div class="w-12 h-12 rounded-xl flex items-center justify-center mb-4 border border-brand-500/30 overflow-hidden shadow-sm relative">
                                <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Logo Grup 2" class="w-full h-full object-cover">
                            </div>
                            <h4 class="text-lg font-bold mb-1 text-white drop-shadow-md">Grup Free 2</h4>
                            <p class="text-sm text-slate-200 group-hover:text-brand-300 transition drop-shadow-md">Klik untuk bergabung <i class="fa-solid fa-arrow-right text-xs ml-1"></i></p>
                        </div>
                    </a>

                    <a href="https://chat.whatsapp.com/GSE4BpLdWTj0tTp4AVnr68" target="_blank" class="relative overflow-hidden bg-slate-900 rounded-2xl p-6 border border-slate-700 hover:border-brand-500/50 transition duration-300 group block shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg')] bg-cover bg-center opacity-40 group-hover:opacity-50 transition duration-300 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-slate-900/60 transition duration-300 group-hover:bg-slate-900/40"></div>
                        <div class="relative z-10">
                            <div class="w-12 h-12 rounded-xl flex items-center justify-center mb-4 border border-brand-500/30 overflow-hidden shadow-sm relative">
                                <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Logo Grup 3" class="w-full h-full object-cover">
                            </div>
                            <h4 class="text-lg font-bold mb-1 text-white drop-shadow-md">Grup Free 3</h4>
                            <p class="text-sm text-slate-200 group-hover:text-brand-300 transition drop-shadow-md">Klik untuk bergabung <i class="fa-solid fa-arrow-right text-xs ml-1"></i></p>
                        </div>
                    </a>
                </div>

                <!-- Baris Fasilitas Bawah -->
                <div class="grid md:grid-cols-2 gap-8 text-left">
                    <!-- Sinyal VIP -->
                    <div class="relative overflow-hidden bg-slate-900 rounded-2xl p-8 border border-slate-700 hover:border-accent-500/50 transition duration-300 group shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1642543492481-44e81e391452?auto=format&fit=crop&w=800&q=80')] bg-cover bg-center opacity-60 group-hover:opacity-80 transition duration-500 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/50 to-slate-900/20 transition duration-300 group-hover:opacity-80"></div>
                        <div class="relative z-10">
                            <div class="w-14 h-14 bg-accent-900/80 rounded-xl flex items-center justify-center mb-6 border border-accent-500/30 backdrop-blur-md">
                                <i class="fa-solid fa-gem text-accent-500 text-2xl"></i>
                            </div>
                            <h4 class="text-xl font-bold mb-3 text-white drop-shadow-xl">Sinyal VIP Premium</h4>
                            <p class="text-slate-100 font-medium leading-relaxed drop-shadow-lg">Akses ke grup Telegram VIP kami. Dapatkan 3-5 sinyal harian dengan akurasi tinggi.</p>
                        </div>
                    </div>

                    <!-- Edukasi -->
                    <div class="relative overflow-hidden bg-slate-900 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=800&q=80')] bg-cover bg-center opacity-60 group-hover:opacity-80 transition duration-500 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/50 to-slate-900/20 transition duration-300 group-hover:opacity-80"></div>
                        <div class="relative z-10">
                            <div class="w-14 h-14 bg-brand-900/80 rounded-xl flex items-center justify-center mb-6 border border-brand-500/30 backdrop-blur-md">
                                <i class="fa-solid fa-graduation-cap text-brand-400 text-2xl"></i>
                            </div>
                            <h4 class="text-xl font-bold mb-3 text-white drop-shadow-xl">Edukasi & Mentoring</h4>
                            <p class="text-slate-100 font-medium leading-relaxed drop-shadow-lg">Materi belajar lengkap. Sesi Live Zoom mingguan untuk analisa market bersama.</p>
                        </div>
                    </div>

                    <!-- Support -->
                    <div class="relative overflow-hidden bg-slate-900 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1521791136064-7986c2920216?auto=format&fit=crop&w=800&q=80')] bg-cover bg-center opacity-60 group-hover:opacity-80 transition duration-500 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/50 to-slate-900/20 transition duration-300 group-hover:opacity-80"></div>
                        <div class="relative z-10">
                            <div class="w-14 h-14 bg-brand-900/80 rounded-xl flex items-center justify-center mb-6 border border-brand-500/30 backdrop-blur-md">
                                <i class="fa-solid fa-headset text-brand-400 text-2xl"></i>
                            </div>
                            <h4 class="text-xl font-bold mb-3 text-white drop-shadow-xl">Support Prioritas</h4>
                            <p class="text-slate-100 font-medium leading-relaxed drop-shadow-lg">Tim kami siap membantu menjembatani Anda dengan broker untuk kendala teknis.</p>
                        </div>
                    </div>

                    <!-- Komunitas -->
                    <div class="relative overflow-hidden bg-slate-900 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group shadow-lg">
                        <div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1522071820081-009f0129c71c?auto=format&fit=crop&w=800&q=80')] bg-cover bg-center opacity-60 group-hover:opacity-80 transition duration-500 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 via-slate-900/50 to-slate-900/20 transition duration-300 group-hover:opacity-80"></div>
                        <div class="relative z-10">
                            <div class="w-14 h-14 bg-brand-900/80 rounded-xl flex items-center justify-center mb-6 border border-brand-500/30 backdrop-blur-md">
                                <i class="fa-solid fa-users text-brand-400 text-2xl"></i>
                            </div>
                            <h4 class="text-xl font-bold mb-3 text-white drop-shadow-xl">Komunitas Solid</h4>
                            <p class="text-slate-100 font-medium leading-relaxed drop-shadow-lg">Bergabung dengan ribuan trader lainnya untuk berbagi analisa dan strategi.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Form Section -->
    <section id="daftar" class="py-20 relative overflow-hidden">
        <div class="absolute inset-0 bg-brand-900/20"></div>
        <div class="max-w-4xl mx-auto px-4 relative z-10 text-center bg-slate-800 border border-slate-700 p-8 md:p-12 rounded-3xl shadow-2xl">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">Siap Menghasilkan Profit Konsisten?</h2>
            <p class="text-lg text-slate-300 mb-8">Proses pendaftaran cepat, kurang dari 5 menit.</p>
            
            <div class="w-full bg-slate-900 rounded-2xl overflow-hidden border border-slate-700 mb-4 shadow-inner">
                <iframe src="https://ma.valetaxmobile.com/embed/register/block/QgyIhHpXEWxCEGFZKL8iFt%2F%2B1zTcKbdeuPARQ6ynEhd%2ByeYF29DUa1NtrArMU%2FRuZANi92d8EnXg6KXUrnCwrTw1AUHEDjdzm04mf9KbY7q7Zg9UXW%2BLq%2BUQoOBYBYzA?lang=id&background=green" width="100%" height="490px" class="border-0 w-full" sandbox="allow-scripts allow-same-origin allow-forms allow-popups"></iframe>
            </div>

            <div class="mb-8">
                <p class="text-sm text-red-400 mb-3"><i class="fa-solid fa-circle-info"></i> Formulir error?</p>
                <a href="https://ma.valetax-indonesia.com/p/2999665" t
