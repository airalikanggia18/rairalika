```html
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Teknik Komputer & Jaringan (TKJ) - Pusat Keunggulan Teknologi</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter & JetBrains Mono -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;600&display=swap" rel="stylesheet">
    <!-- Font Awesome untuk Ikon Teknologi -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    },
                    colors: {
                        navy: {
                            800: '#112240',
                            900: '#0a192f',
                            950: '#060f1e',
                        },
                        cyan: {
                            400: '#38bdf8',
                            500: '#06b6d4',
                            600: '#0891b2',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-cyan-500 selection:text-white">

    <!-- ================= 1. NAVBAR RESPONSIF ================= -->
    <header id="navbar" class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 bg-navy-900/95 backdrop-blur-md border-b border-slate-800 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo & Nama Jurusan -->
                <a href="#beranda" class="flex items-center space-x-3 group">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-cyan-500 to-blue-600 flex items-center justify-center shadow-lg shadow-cyan-500/30 group-hover:scale-105 transition-transform">
                        <i class="fa-solid fa-network-wired text-white text-lg"></i>
                    </div>
                    <div>
                        <span class="font-extrabold text-xl tracking-tight text-white">TKJ<span class="text-cyan-400">.TECH</span></span>
                        <span class="block text-[10px] font-mono text-slate-400 uppercase tracking-widest">Network & Cloud Academy</span>
                    </div>
                </a>

                <!-- Menu Navigasi Desktop -->
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#beranda" class="text-sm font-medium text-slate-300 hover:text-cyan-400 transition-colors">Beranda</a>
                    <a href="#tentang" class="text-sm font-medium text-slate-300 hover:text-cyan-400 transition-colors">Tentang Kami</a>
                    <a href="#kompetensi" class="text-sm font-medium text-slate-300 hover:text-cyan-400 transition-colors">Kompetensi</a>
                    <a href="#fasilitas" class="text-sm font-medium text-slate-300 hover:text-cyan-400 transition-colors">Fasilitas Lab</a>
                    <a href="#galeri" class="text-sm font-medium text-slate-300 hover:text-cyan-400 transition-colors">Galeri Proyek</a>
                    <a href="#kontak" class="px-5 py-2.5 rounded-xl bg-cyan-500 hover:bg-cyan-400 text-navy-950 font-semibold text-sm transition-all shadow-lg shadow-cyan-500/20">
                        Hubungi Kami
                    </a>
                </nav>

                <!-- Tombol Hamburger Mobile -->
                <div class="md:hidden">
                    <button id="mobile-menu-btn" type="button" class="p-2.5 rounded-xl text-slate-300 hover:text-white hover:bg-navy-800 focus:outline-none" aria-label="Buka Menu">
                        <i class="fa-solid fa-bars text-xl" id="menu-icon"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Dropdown Menu Mobile -->
        <div id="mobile-menu" class="hidden md:hidden bg-navy-900 border-b border-slate-800 px-4 pt-2 pb-6 space-y-2">
            <a href="#beranda" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-300 hover:text-white hover:bg-navy-800">Beranda</a>
            <a href="#tentang" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-300 hover:text-white hover:bg-navy-800">Tentang Kami</a>
            <a href="#kompetensi" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-300 hover:text-white hover:bg-navy-800">Kompetensi & Layanan</a>
            <a href="#fasilitas" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-300 hover:text-white hover:bg-navy-800">Fasilitas Lab</a>
            <a href="#galeri" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-300 hover:text-white hover:bg-navy-800">Galeri Proyek</a>
            <a href="#kontak" class="mobile-link block px-4 py-3 rounded-xl text-base font-semibold bg-cyan-500 text-navy-950 text-center mt-4">Pendaftaran & Kemitraan</a>
        </div>
    </header>

    <!-- ================= 2. HERO SECTION ================= -->
    <section id="beranda" class="relative pt-32 pb-20 lg:pt-44 lg:pb-32 bg-navy-950 text-white overflow-hidden">
        <!-- Dekorasi Background Grid & Glow -->
        <div class="absolute inset-0 bg-[linear-gradient(to_right,#1e293b_1px,transparent_1px),linear-gradient(to_bottom,#1e293b_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_0%,#000_70%,transparent_100%)] opacity-30"></div>
        <div class="absolute top-20 left-1/2 -translate-x-1/2 w-[30rem] h-[30rem] bg-cyan-500/20 rounded-full blur-[120px] pointer-events-none"></div>

        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <!-- Konten Teks Hero -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center space-x-2 px-4 py-2 rounded-full bg-navy-800/80 border border-cyan-500/30 text-cyan-400 text-xs sm:text-sm font-mono">
                        <span class="w-2 h-2 rounded-full bg-cyan-400 animate-ping"></span>
                        <span>Kompetensi Keahlian Berstandar Industri</span>
                    </div>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight">
                        Membangun Infrastruktur <span class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500">Digital Masa Depan</span>
                    </h1>

                    <p class="text-base sm:text-lg text-slate-300 max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                        Jurusan <strong>Teknik Komputer dan Jaringan (TKJ)</strong> mencetak tenaga ahli profesional di bidang arsitektur jaringan fiber optik, administrasi server Linux/Windows, keamanan siber, hingga teknologi <em>Cloud Computing</em>.
                    </p>

                    <!-- Tombol CTA -->
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#kontak" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-gradient-to-r from-cyan-500 to-blue-600 hover:from-cyan-400 hover:to-blue-500 text-white font-bold text-sm sm:text-base shadow-xl shadow-cyan-500/25 transition-all flex items-center justify-center gap-2">
                            <span>Gabung Sekarang</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <a href="#kompetensi" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-navy-800 hover:bg-navy-800/80 border border-slate-700 text-slate-200 font-semibold text-sm sm:text-base transition-all flex items-center justify-center gap-2">
                            <i class="fa-solid fa-layer-group text-cyan-400"></i>
                            <span>Pelajari Kompetensi</span>
                        </a>
                    </div>

                    <!-- Statistik Singkat -->
                    <div class="grid grid-cols-3 gap-4 pt-8 border-t border-slate-800/80">
                        <div>
                            <p class="text-2xl sm:text-3xl font-extrabold text-white">95%</p>
                            <p class="text-xs sm:text-sm text-slate-400">Lulusan Terserap Kerja</p>
                        </div>
                        <div>
                            <p class="text-2xl sm:text-3xl font-extrabold text-cyan-400">25+</p>
                            <p class="text-xs sm:text-sm text-slate-400">Mitra Industri IT</p>
                        </div>
                        <div>
                            <p class="text-2xl sm:text-3xl font-extrabold text-white">MTCNA</p>
                            <p class="text-xs sm:text-sm text-slate-400">Sertifikasi Internasional</p>
                        </div>
                    </div>
                </div>

                <!-- Visual Ilustrasi Terminal & Jaringan -->
                <div class="lg:col-span-5">
                    <div class="rounded-2xl bg-navy-900 border border-slate-700/80 shadow-2xl overflow-hidden">
                        <!-- Header Window -->
                        <div class="px-4 py-3 bg-navy-800 border-b border-slate-700 flex items-center justify-between">
                            <div class="flex space-x-2">
                                <span class="w-3 h-3 rounded-full bg-rose-500"></span>
                                <span class="w-3 h-3 rounded-full bg-amber-400"></span>
                                <span class="w-3 h-3 rounded-full bg-emerald-500"></span>
                            </div>
                            <span class="text-xs font-mono text-slate-400">root@tkj-core-server:~#</span>
                            <i class="fa-solid fa-shield-halved text-cyan-400 text-xs"></i>
                        </div>
                        <!-- Isi Terminal -->
                        <div class="p-6 font-mono text-xs sm:text-sm space-y-3 text-slate-300">
                            <p class="text-emerald-400">$ systemctl status network-infrastructure</p>
                            <p class="text-slate-400">● tkj-backbone.service - High-Speed Fiber & Cloud Core</p>
                            <p class="pl-4">Loaded: <span class="text-cyan-400">loaded (/etc/systemd/system/tkj.service)</span></p>
                            <p class="pl-4">Active: <span class="text-emerald-400 font-bold">active (running)</span> since 2026</p>
                            <div class="p-3 rounded-xl bg-navy-950/90 border border-slate-800 space-y-1.5 mt-3">
                                <div class="flex justify-between">
                                    <span class="text-slate-400">[OK] MikroTik BGP Routing</span>
                                    <span class="text-cyan-400">10 Gbps</span>
                                </div>
                                <div class="flex justify-between">
                                    <span class="text-slate-400">[OK] Proxmox Cloud Cluster</span>
                                    <span class="text-emerald-400">Online</span>
                                </div>
                                <div class="flex justify-between">
                                    <span class="text-slate-400">[OK] Firewall & IDS/IPS</span>
                                    <span class="text-amber-400">Protected</span>
                                </div>
                            </div>
                            <p class="text-cyan-400 pt-2 animate-pulse">_ Siap mencetak Network Engineer handal...</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= 3. TENTANG KAMI (VISI, MISI & PROSPEK) ================= -->
    <section id="tentang" class="py-20 lg:py-28 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-cyan-600 font-mono text-sm font-semibold uppercase tracking-wider">Tentang Jurusan TKJ</span>
                <h2 class="mt-2 text-3xl sm:text-4xl font-extrabold text-navy-900">Mencetak Inovator Infrastruktur IT & Keamanan Jaringan</h2>
                <p class="mt-4 text-slate-600 leading-relaxed">
                    Kami memadukan kurikulum berbasis praktik industri langsung dengan fasilitas laboratorium modern untuk memastikan setiap siswa menguasai teknologi terkini.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-10 items-start">
                <!-- Visi & Misi -->
                <div class="space-y-6">
                    <div class="p-8 rounded-2xl bg-slate-50 border border-slate-200/80 shadow-sm">
                        <div class="flex items-center gap-4 mb-4">
                            <div class="w-12 h-12 rounded-xl bg-navy-900 text-cyan-400 flex items-center justify-center text-xl">
                                <i class="fa-solid fa-eye"></i>
                            </div>
                            <h3 class="text-xl font-bold text-navy-900">Visi Kami</h3>
                        </div>
                        <p class="text-slate-600 leading-relaxed">
                            "Menjadi pusat pendidikan kejuruan unggulan di bidang Teknik Komputer dan Jaringan yang menghasilkan lulusan kompeten, bersertifikat internasional, berkarakter profesional, dan adaptif terhadap transformasi digital global."
                        </p>
                    </div>

                    <div class="p-8 rounded-2xl bg-slate-50 border border-slate-200/80 shadow-sm">
                        <div class="flex items-center gap-4 mb-4">
                            <div class="w-12 h-12 rounded-xl bg-cyan-500 text-white flex items-center justify-center text-xl">
                                <i class="fa-solid fa-bullseye"></i>
                            </div>
                            <h3 class="text-xl font-bold text-navy-900">Misi Strategis</h3>
                        </div>
                        <ul class="space-y-3 text-slate-600">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-circle-check text-cyan-600 mt-1"></i>
                                <span>Menyelenggarakan pembelajaran berbasis proyek nyata (<em>Project-Based Learning</em>) bersama praktisi ISP dan Data Center.</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-circle-check text-cyan-600 mt-1"></i>
                                <span>Memfasilitasi uji kompetensi dan sertifikasi vendor global (MikroTik, Cisco, AWS, dan BNSP).</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-circle-check text-cyan-600 mt-1"></i>
                                <span>Menumbuhkan jiwa technopreneurship di bidang layanan IT, instalasi jaringan, dan konsultasi sistem.</span>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- Prospek Karier Lulusan -->
                <div class="p-8 sm:p-10 rounded-2xl bg-navy-900 text-white shadow-xl">
                    <span class="inline-block px-3 py-1 rounded-lg bg-cyan-500/20 text-cyan-400 font-mono text-xs mb-4">Peluang Karier Masa Depan</span>
                    <h3 class="text-2xl font-bold mb-6">Prospek Lulusan TKJ</h3>
                    <p class="text-slate-300 text-sm mb-8 leading-relaxed">
                        Lulusan TKJ memiliki fleksibilitas tinggi untuk langsung bekerja di perusahaan teknologi, melanjutkan studi ke perguruan tinggi, maupun membangun usaha jasa IT mandiri.
                    </p>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="p-4 rounded-xl bg-navy-800 border border-slate-700/70 flex items-center gap-3">
                            <i class="fa-solid fa-sitemap text-cyan-400 text-lg"></i>
                            <div>
                                <h4 class="font-semibold text-sm">Network Engineer</h4>
                                <p class="text-xs text-slate-400">ISP & Perusahaan Korporat</p>
                            </div>
                        </div>
                        <div class="p-4 rounded-xl bg-navy-800 border border-slate-700/70 flex items-center gap-3">
                            <i class="fa-solid fa-server text-cyan-400 text-lg"></i>
                            <div>
                                <h4 class="font-semibold text-sm">System Administrator</h4>
                                <p class="text-xs text-slate-400">Linux, Windows & Virtualisasi</p>
                            </div>
                        </div>
                        <div class="p-4 rounded-xl bg-navy-800 border border-slate-700/70 flex items-center gap-3">
                            <i class="fa-solid fa-cloud text-cyan-400 text-lg"></i>
                            <div>
                                <h4 class="font-semibold text-sm">Cloud & DevOps Junior</h4>
                                <p class="text-xs text-slate-400">Manajemen Server Cloud</p>
                            </div>
                        </div>
                        <div class="p-4 rounded-xl bg-navy-800 border border-slate-700/70 flex items-center gap-3">
                            <i class="fa-solid fa-user-shield text-cyan-400 text-lg"></i>
                            <div>
                                <h4 class="font-semibold text-sm">Cyber Security Analyst</h4>
                                <p class="text-xs text-slate-400">SOC & Keamanan Jaringan</p>
                            </div>
                        </div>
                        <div class="p-4 rounded-xl bg-navy-800 border border-slate-700/70 flex items-center gap-3">
                            <i class="fa-solid fa-wave-square text-cyan-400 text-lg"></i>
                            <div>
                                <h4 class="font-semibold text-sm">Fiber Optic Technician</h4>
                                <p class="text-xs text-slate-400">Instalasi FTTH & Backbone</p>
                            </div>
                        </div>
                        <div class="p-4 rounded-xl bg-navy-800 border border-slate-700/70 flex items-center gap-3">
                            <i class="fa-solid fa-headset text-cyan-400 text-lg"></i>
                            <div>
                                <h4 class="font-semibold text-sm">IT Support Specialist</h4>
                                <p class="text-xs text-slate-400">Hardware & Troubleshooting</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= 4. KOMPETENSI UTAMA & LAYANAN (CARD GRID) ================= -->
    <section id="kompetensi" class="py-20 lg:py-28 bg-slate-100 border-y border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-cyan-600 font-mono text-sm font-semibold uppercase tracking-wider">Kurikulum & Keahlian</span>
                <h2 class="mt-2 text-3xl sm:text-4xl font-extrabold text-navy-900">5 Pilar Kompetensi Utama TKJ</h2>
                <p class="mt-4 text-slate-600">
                    Penguasaan teknis komprehensif dari lapisan fisik jaringan hingga komputasi awan modern.
                </p>
            </div>

            <!-- Grid 5 Kartu Kompetensi -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="group p-8 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-xl hover:border-cyan-500/50 transition-all duration-300">
                    <div class="w-14 h-14 rounded-2xl bg-cyan-50 text-cyan-600 group-hover:bg-cyan-500 group-hover:text-white flex items-center justify-center text-2xl transition-colors mb-6">
                        <i class="fa-solid fa-route"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy-900 mb-3">Administrasi Infrastruktur Jaringan</h3>
                    <p class="text-slate-600 text-sm leading-relaxed mb-4">
                        Perancangan topologi LAN/WAN, konfigurasi VLAN, Dynamic Routing (OSPF, BGP), Manajemen Bandwidth, serta instalasi jaringan Fiber Optik (FTTH).
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">MikroTik</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Cisco IOS</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">FTTH</span>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="group p-8 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-xl hover:border-cyan-500/50 transition-all duration-300">
                    <div class="w-14 h-14 rounded-2xl bg-cyan-50 text-cyan-600 group-hover:bg-cyan-500 group-hover:text-white flex items-center justify-center text-2xl transition-colors mb-6">
                        <i class="fa-solid fa-server"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy-900 mb-3">Administrasi Sistem Jaringan</h3>
                    <p class="text-slate-600 text-sm leading-relaxed mb-4">
                        Instalasi dan manajemen sistem operasi server (Debian, Ubuntu Server, Windows Server), konfigurasi DNS, Web Server, Mail Server, dan Database.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Linux CLI</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Nginx/Apache</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Active Directory</span>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="group p-8 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-xl hover:border-cyan-500/50 transition-all duration-300">
                    <div class="w-14 h-14 rounded-2xl bg-cyan-50 text-cyan-600 group-hover:bg-cyan-500 group-hover:text-white flex items-center justify-center text-2xl transition-colors mb-6">
                        <i class="fa-solid fa-tower-broadcast"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy-900 mb-3">Teknologi Layanan Jaringan</h3>
                    <p class="text-slate-600 text-sm leading-relaxed mb-4">
                        Implementasi komunikasi data modern meliputi Voice over IP (VoIP / Asterisk IP-PBX), Video Streaming Server, dan manajemen trafik jaringan berskala besar.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">VoIP / SIP</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Asterisk</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">QoS</span>
                    </div>
                </div>

                <!-- Card 4 -->
                <div class="group p-8 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-xl hover:border-cyan-500/50 transition-all duration-300">
                    <div class="w-14 h-14 rounded-2xl bg-cyan-50 text-cyan-600 group-hover:bg-cyan-500 group-hover:text-white flex items-center justify-center text-2xl transition-colors mb-6">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-xl font-bold text-navy-900 mb-3">Keamanan Siber (Cyber Security)</h3>
                    <p class="text-slate-600 text-sm leading-relaxed mb-4">
                        Perlindungan infrastruktur jaringan dari serangan siber menggunakan Firewall, VPN Tunneling (WireGuard/IPSec), IDS/IPS, serta dasar-dasar Penetration Testing.
                    </p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Firewall</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">VPN Tunnel</span>
                        <span class="px-2.5 py-1 rounded-md bg-slate-100 text-slate-700 font-mono text-xs">Hardening</span>
                    </div>
                </div>

                <!-- Card 5 -->
                <div class="group p-8 rounded-2xl bg-white border border-slate-200/80 shadow-sm hover:shadow-xl hover:border-cyan-500/50 transition-all duration-300 md:col-span-2 lg:col-span-2">
                    <div class="flex flex-col sm:flex-row sm:items-center gap-6">
                        <div class="w-16 h-16 shrink-0 rounded-2xl bg-navy-900 text-cyan-400 group-hover:bg-cyan-500 group-hover:text-white flex items-center justify-center text-2xl transition-colors">
                            <i class="fa-solid fa-cloud-arrow-up"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-navy-900 mb-2">Cloud Computing & Internet of Things (IoT)</h3>
                            <p class="text-slate-600 text-sm leading-relaxed mb-4">
                                Virtualisasi server dengan Proxmox VE, kontainerisasi aplikasi menggunakan Docker, pengelolaan layanan Cloud (AWS/GCP), serta integrasi perangkat cerdas berbasis mikrokontroler ESP32 dan protokol MQTT.
                            </p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2.5 py-1 rounded-md bg-cyan-50 text-cyan-700 font-mono text-xs font-medium">Proxmox VE</span>
                                <span class="px-2.5 py-1 rounded-md bg-cyan-50 text-cyan-700 font-mono text-xs font-medium">Docker Container</span>
                                <span class="px-2.5 py-1 rounded-md bg-cyan-50 text-cyan-700 font-mono text-xs font-medium">Cloud Infrastructure</span>
                                <span class="px-2.5 py-1 rounded-md bg-cyan-50 text-cyan-700 font-mono text-xs font-medium">ESP32 & MQTT</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= 5. FASILITAS LABORATORIUM ================= -->
    <section id="fasilitas" class="py-20 lg:py-28 bg-navy-950 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-6">
                <div>
                    <span class="text-cyan-400 font-mono text-sm font-semibold uppercase tracking-wider">Infrastruktur Praktik</span>
                    <h2 class="mt-2 text-3xl sm:text-4xl font-extrabold">Fasilitas Laboratorium Modern</h2>
                </div>
                <p class="text-slate-400 max-w-md text-sm leading-relaxed">
                    Dilengkapi perangkat standar industri agar siswa terbiasa dengan lingkungan kerja profesional sejak dini.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Lab 1: Fiber Optic -->
                <div class="rounded-2xl bg-navy-900 border border-slate-800 overflow-hidden group">
                    <div class="h-52 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1544197150-b99a580bb7a8?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/0a192f/38bdf8?text=Lab+Fiber+Optic'"
                             alt="Laboratorium Fiber Optic"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute top-4 left-4 px-3 py-1 rounded-lg bg-navy-950/80 backdrop-blur-sm border border-cyan-500/30 text-cyan-400 text-xs font-mono">
                            LAB-01 // FTTH
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Lab Fiber Optic & Transmisi</h3>
                        <p class="text-slate-400 text-sm leading-relaxed mb-4">
                            Fasilitas penyambungan dan pengukuran jaringan optik dilengkapi Fusion Splicer, OTDR, Optical Power Meter (OPM), OLT, dan simulator jaringan FTTH.
                        </p>
                        <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-cyan-400 font-mono">
                            <span><i class="fa-solid fa-check mr-1"></i> Kapasitas 36 Siswa</span>
                            <span><i class="fa-solid fa-wifi mr-1"></i> Full Gigabit</span>
                        </div>
                    </div>
                </div>

                <!-- Lab 2: Server & Data Center -->
                <div class="rounded-2xl bg-navy-900 border border-slate-800 overflow-hidden group">
                    <div class="h-52 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/0a192f/38bdf8?text=Lab+Server+%26+Data+Center'"
                             alt="Laboratorium Server dan Data Center"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute top-4 left-4 px-3 py-1 rounded-lg bg-navy-950/80 backdrop-blur-sm border border-cyan-500/30 text-cyan-400 text-xs font-mono">
                            LAB-02 // NOC & CLOUD
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Lab Server & Mini Data Center</h3>
                        <p class="text-slate-400 text-sm leading-relaxed mb-4">
                            Dilengkapi Rack Server 42U, Rackmount Blade Server, Router MikroTik CCR, Cisco Catalyst Switch, serta sistem pendingin dan UPS terpusat.
                        </p>
                        <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-cyan-400 font-mono">
                            <span><i class="fa-solid fa-server mr-1"></i> 12 Node Server</span>
                            <span><i class="fa-solid fa-bolt mr-1"></i> Redundant Power</span>
                        </div>
                    </div>
                </div>

                <!-- Lab 3: Hardware & Perakitan -->
                <div class="rounded-2xl bg-navy-900 border border-slate-800 overflow-hidden group">
                    <div class="h-52 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1591799264318-7e6ef8ddb7ea?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/0a192f/38bdf8?text=Lab+Hardware+%26+Perakitan'"
                             alt="Laboratorium Hardware dan Perakitan"
                             class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute top-4 left-4 px-3 py-1 rounded-lg bg-navy-950/80 backdrop-blur-sm border border-cyan-500/30 text-cyan-400 text-xs font-mono">
                            LAB-03 // HARDWARE & IOT
                        </div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Lab Hardware, Perakitan & IoT</h3>
                        <p class="text-slate-400 text-sm leading-relaxed mb-4">
                            Meja kerja anti-statis, kit perakitan PC & Workstation, alat diagnostik motherboard, solder station, serta perangkat pengembangan mikrokontroler IoT.
                        </p>
                        <div class="pt-4 border-t border-slate-800 flex items-center justify-between text-xs text-cyan-400 font-mono">
                            <span><i class="fa-solid fa-microchip mr-1"></i> ESD Safe Workstation</span>
                            <span><i class="fa-solid fa-screwdriver-wrench mr-1"></i> Lengkap</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= 6. GALERI & PROYEK SISWA (DENGAN FILTER JS) ================= -->
    <section id="galeri" class="py-20 lg:py-28 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-12">
                <span class="text-cyan-600 font-mono text-sm font-semibold uppercase tracking-wider">Karya & Inovasi</span>
                <h2 class="mt-2 text-3xl sm:text-4xl font-extrabold text-navy-900">Galeri Proyek & Praktikum Siswa</h2>
                <p class="mt-4 text-slate-600">
                    Hasil karya nyata peserta didik dalam mengimplementasikan solusi jaringan, server, dan sistem cerdas.
                </p>
            </div>

            <!-- Tombol Filter Kategori -->
            <div class="flex flex-wrap items-center justify-center gap-3 mb-12" id="filter-buttons">
                <button type="button" data-filter="all" class="filter-btn active px-5 py-2.5 rounded-xl text-sm font-semibold bg-navy-900 text-white shadow-md transition-all">
                    Semua Proyek
                </button>
                <button type="button" data-filter="jaringan" class="filter-btn px-5 py-2.5 rounded-xl text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition-all">
                    Jaringan & Fiber Optic
                </button>
                <button type="button" data-filter="server" class="filter-btn px-5 py-2.5 rounded-xl text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition-all">
                    Server & Cloud
                </button>
                <button type="button" data-filter="iot" class="filter-btn px-5 py-2.5 rounded-xl text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200 transition-all">
                    IoT & Keamanan
                </button>
            </div>

            <!-- Grid Galeri Proyek -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8" id="project-grid">
                <!-- Item 1 -->
                <div class="project-card rounded-2xl bg-slate-50 border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all" data-category="jaringan">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1551703599-6b3e8379aa8c?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/e2e8f0/0f172a?text=Instalasi+RT%2FRW+Net+FTTH'"
                             alt="Instalasi FTTH" class="w-full h-full object-cover">
                        <span class="absolute top-3 right-3 px-3 py-1 rounded-lg bg-cyan-600 text-white text-xs font-semibold">Jaringan</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg text-navy-900 mb-2">Perancangan Infrastruktur RT/RW Net Berbasis FTTH</h3>
                        <p class="text-sm text-slate-600 mb-4">Implementasi distribusi internet serat optik menggunakan OLT GPON dan manajemen voucher hotspot MikroTik.</p>
                        <span class="text-xs font-mono text-slate-500">Tim Proyek Kelas XII TKJ 1</span>
                    </div>
                </div>

                <!-- Item 2 -->
                <div class="project-card rounded-2xl bg-slate-50 border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all" data-category="server">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1563986768609-322da13575f3?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/e2e8f0/0f172a?text=Private+Cloud+Sekolah'"
                             alt="Private Cloud" class="w-full h-full object-cover">
                        <span class="absolute top-3 right-3 px-3 py-1 rounded-lg bg-blue-600 text-white text-xs font-semibold">Server & Cloud</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg text-navy-900 mb-2">Private Cloud Storage & E-Learning Lokal</h3>
                        <p class="text-sm text-slate-600 mb-4">Membangun layanan penyimpanan awan mandiri menggunakan Nextcloud di atas cluster virtualisasi Proxmox VE.</p>
                        <span class="text-xs font-mono text-slate-500">Tim Proyek Kelas XII TKJ 2</span>
                    </div>
                </div>

                <!-- Item 3 -->
                <div class="project-card rounded-2xl bg-slate-50 border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all" data-category="iot">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/e2e8f0/0f172a?text=Smart+Server+Room+IoT'"
                             alt="IoT Monitoring" class="w-full h-full object-cover">
                        <span class="absolute top-3 right-3 px-3 py-1 rounded-lg bg-emerald-600 text-white text-xs font-semibold">IoT & Keamanan</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg text-navy-900 mb-2">Smart Server Room Monitoring Berbasis IoT</h3>
                        <p class="text-sm text-slate-600 mb-4">Sistem pemantauan suhu, kelembapan, dan deteksi akses pintu ruang server secara real-time dengan notifikasi Telegram.</p>
                        <span class="text-xs font-mono text-slate-500">Klub Inovasi TKJ</span>
                    </div>
                </div>

                <!-- Item 4 -->
                <div class="project-card rounded-2xl bg-slate-50 border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all" data-category="jaringan">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1520869562399-e772f042f422?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/e2e8f0/0f172a?text=Load+Balancing+Dual+ISP'"
                             alt="Load Balancing" class="w-full h-full object-cover">
                        <span class="absolute top-3 right-3 px-3 py-1 rounded-lg bg-cyan-600 text-white text-xs font-semibold">Jaringan</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg text-navy-900 mb-2">Load Balancing & Failover Dual ISP</h3>
                        <p class="text-sm text-slate-600 mb-4">Konfigurasi metode PCC (Per Connection Classifier) untuk menggabungkan dua jalur internet demi stabilitas konektivitas kampus.</p>
                        <span class="text-xs font-mono text-slate-500">Tim LKS Networking</span>
                    </div>
                </div>

                <!-- Item 5 -->
                <div class="project-card rounded-2xl bg-slate-50 border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all" data-category="server">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1607799279861-4dd421887fb3?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/e2e8f0/0f172a?text=Network+Monitoring+Zabbix'"
                             alt="Zabbix Monitoring" class="w-full h-full object-cover">
                        <span class="absolute top-3 right-3 px-3 py-1 rounded-lg bg-blue-600 text-white text-xs font-semibold">Server & Cloud</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg text-navy-900 mb-2">Dashboard Monitoring Jaringan dengan Zabbix & Grafana</h3>
                        <p class="text-sm text-slate-600 mb-4">Visualisasi trafik bandwidth, kesehatan CPU server, dan latensi perangkat jaringan sekolah secara terpusat.</p>
                        <span class="text-xs font-mono text-slate-500">Tim NOC Siswa</span>
                    </div>
                </div>

                <!-- Item 6 -->
                <div class="project-card rounded-2xl bg-slate-50 border border-slate-200 overflow-hidden shadow-sm hover:shadow-lg transition-all" data-category="iot">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1555949963-ff9fe0c870eb?auto=format&fit=crop&w=800&q=80"
                             onerror="this.src='https://placehold.co/800x500/e2e8f0/0f172a?text=Intrusion+Detection+System'"
                             alt="Keamanan Siber" class="w-full h-full object-cover">
                        <span class="absolute top-3 right-3 px-3 py-1 rounded-lg bg-emerald-600 text-white text-xs font-semibold">IoT & Keamanan</span>
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg text-navy-900 mb-2">Implementasi Snort IDS & Honeypot Server</h3>
                        <p class="text-sm text-slate-600 mb-4">Simulasi deteksi dini serangan DDoS dan pencatatan aktivitas mencurigakan pada jaringan lokal menggunakan Linux Server.</p>
                        <span class="text-xs font-mono text-slate-500">Komunitas Cyber Security TKJ</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= 7. KONTAK, PENDAFTARAN & KEMITRAAN INDUSTRI ================= -->
    <section id="kontak" class="py-20 lg:py-28 bg-slate-100 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                <!-- Info Kontak & Kemitraan -->
                <div class="lg:col-span-5 space-y-8">
                    <div>
                        <span class="text-cyan-600 font-mono text-sm font-semibold uppercase tracking-wider">Hubungi Kami</span>
                        <h2 class="mt-2 text-3xl sm:text-4xl font-extrabold text-navy-900">Pendaftaran Siswa & Kemitraan Industri</h2>
                        <p class="mt-4 text-slate-600 leading-relaxed">
                            Tertarik bergabung menjadi bagian dari generasi ahli jaringan masa depan, atau ingin menjalin kerja sama Prakerin (PKL) dan rekrutmen lulusan? Silakan hubungi tim kami.
                        </p>
                    </div>

                    <div class="space-y-4">
                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-white border border-slate-200/80">
                            <div class="w-11 h-11 rounded-xl bg-navy-900 text-cyan-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-navy-900 text-sm">Lokasi Gedung TKJ</h4>
                                <p class="text-sm text-slate-600 mt-0.5">Gedung Teknologi Informasi Lt. 2, Jl. Pendidikan Teknologi No. 45, Bandung, Jawa Barat</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-white border border-slate-200/80">
                            <div class="w-11 h-11 rounded-xl bg-navy-900 text-cyan-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-envelope"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-navy-900 text-sm">Email Resmi Jurusan</h4>
                                <p class="text-sm text-slate-600 mt-0.5">info.tkj@smkteknologi.sch.id</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-white border border-slate-200/80">
                            <div class="w-11 h-11 rounded-xl bg-navy-900 text-cyan-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-navy-900 text-sm">Telepon & WhatsApp Layanan</h4>
                                <p class="text-sm text-slate-600 mt-0.5">+62 812-3456-7890 (Senin - Jumat, 07.30 - 16.00 WIB)</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Formulir Interaktif -->
                <div class="lg:col-span-7">
                    <div class="p-8 sm:p-10 rounded-2xl bg-white border border-slate-200 shadow-xl">
                        <h3 class="text-2xl font-bold text-navy-900 mb-2">Formulir Informasi & Kemitraan</h3>
                        <p class="text-sm text-slate-500 mb-6">Lengkapi data di bawah ini, tim admin jurusan akan segera merespons pesan Anda.</p>

                        <!-- Kotak Notifikasi Sukses (Tersembunyi secara default) -->
                        <div id="success-alert" class="hidden mb-6 p-4 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-800 flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-emerald-600 text-xl mt-0.5"></i>
                            <div class="flex-1">
                                <h4 class="font-bold text-sm">Pesan Berhasil Terkirim!</h4>
                                <p class="text-xs sm:text-sm mt-1" id="success-message-detail">
                                    Terima kasih telah menghubungi Jurusan Teknik Komputer dan Jaringan. Tim kami akan segera menghubungi Anda kembali.
                                </p>
                            </div>
                            <button type="button" id="close-alert-btn" class="text-emerald-600 hover:text-emerald-800 p-1">
                                <i class="fa-solid fa-xmark"></i>
                            </button>
                        </div>

                        <form id="contact-form" class="space-y-5">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                                <div>
                                    <label for="nama" class="block text-sm font-semibold text-slate-700 mb-1.5">Nama Lengkap *</label>
                                    <input type="text" id="nama" name="nama" required placeholder="Contoh: Budi Santoso"
                                           class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500/20 outline-none text-sm transition-all">
                                </div>
                                <div>
                                    <label for="email" class="block text-sm font-semibold text-slate-700 mb-1.5">Alamat Email *</label>
                                    <input type="email" id="email" name="email" required placeholder="nama@email.com"
                                           class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500/20 outline-none text-sm transition-all">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                                <div>
                                    <label for="telepon" class="block text-sm font-semibold text-slate-700 mb-1.5">Nomor WhatsApp *</label>
                                    <input type="tel" id="telepon" name="telepon" required placeholder="0812xxxxxxxx"
                                           class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500/20 outline-none text-sm transition-all">
                                </div>
                                <div>
                                    <label for="kategori" class="block text-sm font-semibold text-slate-700 mb-1.5">Keperluan *</label>
                                    <select id="kategori" name="kategori" required
                                            class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500/20 outline-none text-sm bg-white transition-all">
                                        <option value="Pendaftaran Siswa Baru (PPDB)">Pendaftaran Siswa Baru (PPDB)</option>
                                        <option value="Kemitraan Industri / Prakerin (PKL)">Kemitraan Industri / Prakerin (PKL)</option>
                                        <option value="Rekrutmen Lulusan TKJ">Rekrutmen Lulusan TKJ</option>
                                        <option value="Layanan Jasa IT / Instalasi Jaringan">Layanan Jasa IT / Instalasi Jaringan</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label for="pesan" class="block text-sm font-semibold text-slate-700 mb-1.5">Pesan / Detail Kebutuhan *</label>
                                <textarea id="pesan" name="pesan" rows="4" required placeholder="Tuliskan pertanyaan atau detail kerja sama yang ingin diajukan..."
                                          class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:border-cyan-500 focus:ring-2 focus:ring-cyan-500/20 outline-none text-sm transition-all"></textarea>
                            </div>

                            <button type="submit" class="w-full py-4 px-6 rounded-xl bg-gradient-to-r from-navy-900 to-navy-800 hover:from-cyan-600 hover:to-blue-600 text-white font-bold text-sm sm:text-base shadow-lg transition-all flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Kirim Pesan Sekarang</span>
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER PROFESIONAL ================= -->
    <footer class="bg-navy-950 text-slate-400 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-14">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10">
                <!-- Brand -->
                <div class="space-y-4">
                    <div class="flex items-center space-x-3">
                        <div class="w-9 h-9 rounded-xl bg-cyan-500 flex items-center justify-center text-navy-950">
                            <i class="fa-solid fa-network-wired"></i>
                        </div>
                        <span class="font-extrabold text-xl text-white">TKJ<span class="text-cyan-400">.TECH</span></span>
                    </div>
                    <p class="text-sm leading-relaxed">
                        Kompetensi Keahlian Teknik Komputer dan Jaringan. Mencetak generasi unggul di bidang infrastruktur jaringan, administrasi server, dan cloud computing.
                    </p>
                    <div class="flex space-x-3 pt-2">
                        <a href="#" aria-label="Instagram" class="w-9 h-9 rounded-lg bg-navy-900 hover:bg-cyan-500 hover:text-navy-950 flex items-center justify-center transition-colors">
                            <i class="fa-brands fa-instagram"></i>
                        </a>
                        <a href="#" aria-label="YouTube" class="w-9 h-9 rounded-lg bg-navy-900 hover:bg-cyan-500 hover:text-navy-950 flex items-center justify-center transition-colors">
                            <i class="fa-brands fa-youtube"></i>
                        </a>
                        <a href="#" aria-label="LinkedIn" class="w-9 h-9 rounded-lg bg-navy-900 hover:bg-cyan-500 hover:text-navy-950 flex items-center justify-center transition-colors">
                            <i class="fa-brands fa-linkedin-in"></i>
                        </a>
                        <a href="#" aria-label="GitHub" class="w-9 h-9 rounded-lg bg-navy-900 hover:bg-cyan-500 hover:text-navy-950 flex items-center justify-center transition-colors">
                            <i class="fa-brands fa-github"></i>
                        </a>
                    </div>
                </div>

                <!-- Navigasi Cepat -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Navigasi</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li><a href="#beranda" class="hover:text-cyan-400 transition-colors">Beranda</a></li>
                        <li><a href="#tentang" class="hover:text-cyan-400 transition-colors">Tentang & Visi Misi</a></li>
                        <li><a href="#kompetensi" class="hover:text-cyan-400 transition-colors">Kompetensi Utama</a></li>
                        <li><a href="#fasilitas" class="hover:text-cyan-400 transition-colors">Fasilitas Laboratorium</a></li>
                        <li><a href="#galeri" class="hover:text-cyan-400 transition-colors">Galeri Proyek Siswa</a></li>
                    </ul>
                </div>

                <!-- Sertifikasi -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Sertifikasi & Mitra</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li>MikroTik Academy (MTCNA)</li>
                        <li>Cisco Networking Academy</li>
                        <li>BNSP Klaster Jaringan</li>
                        <li>AWS Cloud Foundations</li>
                        <li>Asosiasi Penyelenggara Jasa Internet</li>
                    </ul>
                </div>

                <!-- Jam Operasional -->
                <div>
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4">Jam Layanan Lab & Info</h4>
                    <ul class="space-y-2.5 text-sm">
                        <li class="flex justify-between"><span>Senin - Kamis:</span> <span class="text-white">07.00 - 16.00</span></li>
                        <li class="flex justify-between"><span>Jumat:</span> <span class="text-white">07.00 - 15.30</span></li>
                        <li class="flex justify-between"><span>Sabtu (Ekskul IT):</span> <span class="text-cyan-400">08.00 - 13.00</span></li>
                        <li class="flex justify-between"><span>Minggu:</span> <span class="text-slate-500">Tutup</span></li>
                    </ul>
                </div>
            </div>

            <div class="mt-12 pt-8 border-t border-slate-800/80 flex flex-col sm:flex-row items-center justify-between text-xs gap-4">
                <p>&copy; 2026 Jurusan Teknik Komputer dan Jaringan (TKJ). Hak Cipta Dilindungi.</p>
                <p class="font-mono text-slate-500">Didesain untuk Pendidikan Vokasi Teknologi Indonesia</p>
            </div>
        </div>
    </footer>

    <!-- ================= JAVASCRIPT INTERAKTIF ================= -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // 1. Toggle Menu Mobile
            const mobileMenuBtn = document.getElementById('mobile-menu-btn');
            const mobileMenu = document.getElementById('mobile-menu');
            const menuIcon = document.getElementById('menu-icon');
            const mobileLinks = document.querySelectorAll('.mobile-link');

            mobileMenuBtn.addEventListener('click', () => {
                const isHidden = mobileMenu.classList.contains('hidden');
                if (isHidden) {
                    mobileMenu.classList.remove('hidden');
                    menuIcon.classList.remove('fa-bars');
                    menuIcon.classList.add('fa-xmark');
                } else {
                    mobileMenu.classList.add('hidden');
                    menuIcon.classList.remove('fa-xmark');
                    menuIcon.classList.add('fa-bars');
                }
            });

            // Tutup menu mobile saat tautan diklik
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                    menuIcon.classList.remove('fa-xmark');
                    menuIcon.classList.add('fa-bars');
                });
            });

            // 2. Filter Kategori Galeri Proyek Siswa
            const filterBtns = document.querySelectorAll('.filter-btn');
            const projectCards = document.querySelectorAll('.project-card');

            filterBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    // Reset gaya tombol aktif
                    filterBtns.forEach(b => {
                        b.classList.remove('bg-navy-900', 'text-white', 'shadow-md');
                        b.classList.add('bg-slate-100', 'text-slate-700');
                    });

                    // Aktifkan tombol yang diklik
                    btn.classList.remove('bg-slate-100', 'text-slate-700');
                    btn.classList.add('bg-navy-900', 'text-white', 'shadow-md');

                    const selectedCategory = btn.getAttribute('data-filter');

                    projectCards.forEach(card => {
                        const cardCategory = card.getAttribute('data-category');
                        if (selectedCategory === 'all' || selectedCategory === cardCategory) {
                            card.classList.remove('hidden');
                        } else {
                            card.classList.add('hidden');
                        }
                    });
                });
            });

            // 3. Penanganan Formulir Kontak & Notifikasi Sukses
            const contactForm = document.getElementById('contact-form');
            const successAlert = document.getElementById('success-alert');
            const successDetail = document.getElementById('success-message-detail');
            const closeAlertBtn = document.getElementById('close-alert-btn');

            contactForm.addEventListener('submit', (e) => {
                e.preventDefault();

                try {
                    const nama = document.getElementById('nama').value.trim();
                    const kategori = document.getElementById('kategori').value;

                    // Tampilkan pesan personalisasi di banner notifikasi
                    successDetail.textContent = `Terima kasih, ${nama}! Pengajuan untuk kategori "${kategori}" telah kami terima. Tim admin TKJ akan segera menghubungi Anda melalui WhatsApp atau Email.`;

                    successAlert.classList.remove('hidden');
                    contactForm.reset();

                    // Gulir halus ke kotak notifikasi agar terlihat jelas di perangkat mobile
                    successAlert.scrollIntoView({ behavior: 'smooth', block: 'center' });
                } catch (error) {
                    console.error('Terjadi kesalahan saat memproses formulir:', error);
                }
            });

            closeAlertBtn.addEventListener('click', () => {
                successAlert.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
```
