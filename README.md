<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valetax | Partner Trading Terbaik Anda</title>
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

    <!-- Navigation -->
    <nav class="fixed top-0 left-0 w-full z-50 bg-slate-900/90 backdrop-blur-md border-b border-slate-800 transition-all duration-300" id="navbar">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center gap-2 cursor-pointer">
                    <i class="fa-solid fa-chart-line text-brand-500 text-3xl"></i>
                    <span class="font-bold text-2xl tracking-tight">Valetax</span>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-slate-300 hover:text-white transition font-medium">Beranda</a>
                    <a href="#keuntungan" class="text-slate-300 hover:text-white transition font-medium">Keuntungan</a>
                    <a href="#daftar" class="bg-brand-600 hover:bg-brand-700 text-white px-6 py-2.5 rounded-full font-semibold transition shadow-lg shadow-brand-500/30">Buka Akun</a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-300 hover:text-white focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Panel -->
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
        <!-- Abstract background elements -->
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
                    <!-- Placeholder for Trading Illustration/Mockup -->
                    <div class="relative rounded-2xl border border-slate-700 bg-slate-800/50 p-2 shadow-2xl backdrop-blur-sm">
                        <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Trading Dashboard" class="rounded-xl opacity-90 hover:opacity-100 transition duration-500 w-full aspect-video object-cover">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-12 bg-slate-800/50 border-y border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div>
                    <h3 class="text-4xl font-bold text-white mb-2">2,500+</h3>
                    <p class="text-slate-400 font-medium">Trader Aktif</p>
                </div>
                <div>
                    <h3 class="text-4xl font-bold text-white mb-2">$500K+</h3>
                    <p class="text-slate-400 font-medium">Rebate Dibagikan</p>
                </div>
                <div>
                    <h3 class="text-4xl font-bold text-white mb-2">5+</h3>
                    <p class="text-slate-400 font-medium">Tahun Pengalaman</p>
                </div>
                <div>
                    <h3 class="text-4xl font-bold text-white mb-2">24/7</h3>
                    <p class="text-slate-400 font-medium">Dukungan Lokal</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Keuntungan Section -->
    <section id="keuntungan" class="py-24 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-4xl mx-auto mb-16">
                <h2 class="text-brand-500 font-semibold tracking-wide uppercase text-sm mb-2">MENGAPA MEMILIH KAMI?</h2>
                <h3 class="text-3xl md:text-4xl font-bold mb-4">Fasilitas Eksklusif Klien Kami</h3>
                <p class="text-slate-400 text-lg mb-10">Kami tidak hanya menyediakan link pendaftaran, tapi kami memastikan Anda memiliki 'senjata' lengkap untuk bertempur di market.</p>
                
                <!-- Kotak Grup Free -->
                <div class="grid sm:grid-cols-3 gap-6 text-left">
                    <a href="https://chat.whatsapp.com/LL1VW32Cp5HFX1n45i7LYO" target="_blank" class="relative overflow-hidden bg-slate-900 rounded-2xl p-6 border border-slate-700 hover:border-brand-500/50 transition duration-300 group block shadow-lg">
                        <!-- Background Image & Overlay -->
                        <div class="absolute inset-0 bg-[url('https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg')] bg-cover bg-center opacity-40 group-hover:opacity-50 transition duration-300 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-slate-900/60 transition duration-300 group-hover:bg-slate-900/40"></div>
                        
                        <!-- Content -->
                        <div class="relative z-10">
                            <div class="w-12 h-12 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition duration-300 border border-brand-500/30 overflow-hidden shadow-sm relative">
                                <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Logo Grup 1" class="w-full h-full object-cover">
                            </div>
                            <h4 class="text-lg font-bold mb-1 text-white drop-shadow-md">Grup Free 1</h4>
                            <p class="text-sm text-slate-200 group-hover:text-brand-300 transition drop-shadow-md">Klik untuk bergabung <i class="fa-solid fa-arrow-right text-xs ml-1"></i></p>
                        </div>
                    </a>

                    <a href="https://chat.whatsapp.com/EasRNABfvdKIGYmzJFkd2A" target="_blank" class="relative overflow-hidden bg-slate-900 rounded-2xl p-6 border border-slate-700 hover:border-brand-500/50 transition duration-300 group block shadow-lg">
                        <!-- Background Image & Overlay -->
                        <div class="absolute inset-0 bg-[url('https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg')] bg-cover bg-center opacity-40 group-hover:opacity-50 transition duration-300 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-slate-900/60 transition duration-300 group-hover:bg-slate-900/40"></div>
                        
                        <!-- Content -->
                        <div class="relative z-10">
                            <div class="w-12 h-12 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition duration-300 border border-brand-500/30 overflow-hidden shadow-sm relative">
                                <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Logo Grup 2" class="w-full h-full object-cover">
                            </div>
                            <h4 class="text-lg font-bold mb-1 text-white drop-shadow-md">Grup Free 2</h4>
                            <p class="text-sm text-slate-200 group-hover:text-brand-300 transition drop-shadow-md">Klik untuk bergabung <i class="fa-solid fa-arrow-right text-xs ml-1"></i></p>
                        </div>
                    </a>

                    <a href="https://chat.whatsapp.com/GSE4BpLdWTj0tTp4AVnr68" target="_blank" class="relative overflow-hidden bg-slate-900 rounded-2xl p-6 border border-slate-700 hover:border-brand-500/50 transition duration-300 group block shadow-lg">
                        <!-- Background Image & Overlay -->
                        <div class="absolute inset-0 bg-[url('https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg')] bg-cover bg-center opacity-40 group-hover:opacity-50 transition duration-300 group-hover:scale-105"></div>
                        <div class="absolute inset-0 bg-slate-900/60 transition duration-300 group-hover:bg-slate-900/40"></div>
                        
                        <!-- Content -->
                        <div class="relative z-10">
                            <div class="w-12 h-12 rounded-xl flex items-center justify-center mb-4 group-hover:scale-110 transition duration-300 border border-brand-500/30 overflow-hidden shadow-sm relative">
                                <img src="https://raw.githubusercontent.com/hendroah/BrokerVale/2b10cf94d1d4e61c9096995eb8d31e4e13f046dd/GRUP%20UMUM%20ZUTRADE%203%2020260315_120727.jpg" alt="Logo Grup 3" class="w-full h-full object-cover">
                            </div>
                            <h4 class="text-lg font-bold mb-1 text-white drop-shadow-md">Grup Free 3</h4>
                            <p class="text-sm text-slate-200 group-hover:text-brand-300 transition drop-shadow-md">Klik untuk bergabung <i class="fa-solid fa-arrow-right text-xs ml-1"></i></p>
                        </div>
                    </a>
                </div>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Feature 1 -->
                <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group">
                    <div class="w-14 h-14 bg-brand-900/50 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-hand-holding-dollar text-brand-400 text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3 text-white">Rebate Mingguan</h4>
                    <p class="text-slate-400 leading-relaxed">Dapatkan pengembalian dana (rebate) hingga 80% dari komisi IB setiap minggunya, loss atau profit Anda tetap dibayar.</p>
                </div>

                <!-- Feature 2 -->
                <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 hover:border-accent-500/50 transition duration-300 group">
                    <div class="w-14 h-14 bg-accent-900/30 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-gem text-accent-500 text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3 text-white">Sinyal VIP Premium</h4>
                    <p class="text-slate-400 leading-relaxed">Akses ke grup Telegram VIP kami. Dapatkan 3-5 sinyal harian dengan akurasi tinggi lengkap dengan Take Profit & Stop Loss.</p>
                </div>

                <!-- Feature 3 -->
                <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group">
                    <div class="w-14 h-14 bg-brand-900/50 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-graduation-cap text-brand-400 text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3 text-white">Edukasi & Mentoring</h4>
                    <p class="text-slate-400 leading-relaxed">Materi belajar lengkap dari basic hingga advance. Sesi Live Zoom mingguan untuk analisa market bersama.</p>
                </div>

                <!-- Feature 4 -->
                <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group">
                    <div class="w-14 h-14 bg-brand-900/50 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-robot text-brand-400 text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3 text-white">Akses EA / Robot Trading</h4>
                    <p class="text-slate-400 leading-relaxed">Dapatkan Expert Advisor (EA) teruji yang kami kembangkan sendiri untuk trading otomatis secara gratis.</p>
                </div>

                <!-- Feature 5 -->
                <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group">
                    <div class="w-14 h-14 bg-brand-900/50 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-headset text-brand-400 text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3 text-white">Support Prioritas</h4>
                    <p class="text-slate-400 leading-relaxed">Kendala deposit, withdrawal, atau pertanyaan teknis? Tim kami siap membantu menjembatani Anda dengan broker.</p>
                </div>

                <!-- Feature 6 -->
                <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 hover:border-brand-500/50 transition duration-300 group">
                    <div class="w-14 h-14 bg-brand-900/50 rounded-xl flex items-center justify-center mb-6 group-hover:scale-110 transition duration-300">
                        <i class="fa-solid fa-users text-brand-400 text-2xl"></i>
                    </div>
                    <h4 class="text-xl font-bold mb-3 text-white">Komunitas Solid</h4>
                    <p class="text-slate-400 leading-relaxed">Bergabung dengan ribuan trader lainnya. Diskusi, berbagi analisa, dan tumbuh bersama dalam lingkungan yang positif.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section id="daftar" class="py-20 relative overflow-hidden">
        <div class="absolute inset-0 bg-brand-900/20"></div>
        <div class="max-w-4xl mx-auto px-4 relative z-10 text-center bg-slate-800 border border-slate-700 p-8 md:p-12 rounded-3xl shadow-2xl">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">Siap Menghasilkan Profit Konsisten?</h2>
            <p c
