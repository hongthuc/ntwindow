<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>NT Window | Cửa Nhôm Xingfa & Kính Cường Lực Cao Cấp Đà Nẵng - ntwindow.com</title>
    <meta name="description" content="NT Window (ntwindow.com) chuyên thiết kế, gia công và lắp đặt Cửa Nhôm Xingfa chính hãng, Cửa Kính Cường Lực, Cửa Nhựa Lõi Thép, Cầu Thang Kính, Phòng Tắm Kính tại Đà Nẵng. Hotline: 0982.539.678.">

    <!-- Open Graph / Thumbnail Logo khi chia sẻ liên kết trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ntwindow.com/">
    <meta property="og:site_name" content="NT Window - ntwindow.com">
    <meta property="og:title" content="NT Window | Cửa Nhôm Xingfa & Cửa Kính Cường Lực Đà Nẵng">
    <meta property="og:description" content="Chuyên thi công Cửa Nhôm Xingfa, Cửa Kính Cường Lực, Cửa Tự Động, Phòng Tắm Kính uy tín tại 183 Mạc Đăng Dung, Hòa Xuân, Đà Nẵng. Hotline: 0982.539.678.">
    <meta property="og:image" content="https://placehold.co/1200x630/0A3D7A/FFFFFF?text=NT+WINDOW+-+ntwindow.com">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="NT Window | Cửa Nhôm Xingfa Đà Nẵng">
    <meta name="twitter:description" content="Cửa Nhôm Xingfa chính hãng, Cửa Kính Cường Lực tại Đà Nẵng - Hotline: 0982.539.678">
    <meta name="twitter:image" content="https://placehold.co/1200x630/0A3D7A/FFFFFF?text=NT+WINDOW+-+ntwindow.com">

    <!-- Favicon SVG đồng bộ logo NT Window -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230A3D7A'/%3E%3Crect x='10' y='10' width='44' height='44' rx='6' fill='none' stroke='%23FFFFFF' stroke-width='3.5'/%3E%3Cline x1='32' y1='10' x2='32' y2='54' stroke='%23F58220' stroke-width='3.5'/%3E%3Cline x1='10' y1='32' x2='54' y2='32' stroke='%23FFFFFF' stroke-width='2.5'/%3E%3Ctext x='32' y='44' font-family='Arial,sans-serif' font-weight='900' font-size='18' fill='%23F58220' text-anchor='middle'%3ENT%3C/text%3E%3C/svg%3E">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Cấu hình màu chủ đạo đồng bộ theo Logo NT Window -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0A3D7A',      // Xanh dương đậm chủ đạo của logo
                            blue: '#1256A3',      // Xanh dương trung tính
                            light: '#EEF5FC',     // Nền xanh nhạt
                            accent: '#F58220',    // Cam vàng điểm nhấn của logo
                            accentDark: '#D96B0F' // Cam đậm khi hover
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Đảm bảo tuyệt đối không tràn viền ngang và không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #F8FAFC;
            color: #1E293B;
        }

        /* Chiều ngang chuẩn 95% trên máy tính, tối ưu co giãn gọn gàng trên điện thoại */
        .nt-container {
            width: 94%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .nt-container {
                width: 95%;
                max-width: 95vw;
            }
        }

        /* Tiêu đề mục theo phong cách Flatsome chuẩn UX Builder */
        .flatsome-section-title {
            position: relative;
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding-bottom: 0.5rem;
        }
        .flatsome-section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background: linear-gradient(90deg, #0A3D7A, #F58220);
            border-radius: 9999px;
        }

        /* Menu dropdown Flatsome trên máy tính */
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown,
        .nav-item:focus-within .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Slider 2 banner đồng nhất kích thước tuyệt đối bằng CSS Grid chồng lớp */
        .hero-slider-grid {
            display: grid;
            grid-template-columns: 1fr;
        }
        .hero-slide {
            grid-area: 1 / 1 / 2 / 2;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
            pointer-events: none;
        }
        .hero-slide.active {
            opacity: 1;
            visibility: visible;
            pointer-events: auto;
            z-index: 2;
        }

        /* Hiệu ứng nhịp sóng nhẹ cho nút Hotline nổi */
        @keyframes pulseRing {
            0% {
                box-shadow: 0 0 0 0 rgba(245, 130, 32, 0.55);
            }
            70% {
                box-shadow: 0 0 0 12px rgba(245, 130, 32, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(245, 130, 32, 0);
            }
        }
        .hotline-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="antialiased">

    <!-- =========================================================
         SECTION 1: TOP BAR (FLATSOME HEADER TOP)
    ========================================================== -->
    <div class="bg-brand-navy text-white text-xs border-b border-white/10">
        <div class="nt-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 min-w-0">
                <i class="fa-solid fa-location-dot text-brand-accent shrink-0"></i>
                <span class="truncate">183 Mạc Đăng Dung, Phường Hòa Xuân, TP Đà Nẵng</span>
            </div>
            <div class="hidden sm:flex items-center gap-5 shrink-0">
                <span class="flex items-center gap-1.5">
                    <i class="fa-regular fa-clock text-brand-accent"></i> Làm việc 24/7
                </span>
                <a href="tel:0982539678" class="flex items-center gap-1.5 hover:text-brand-accent transition-colors font-semibold">
                    <i class="fa-solid fa-phone text-brand-accent"></i> 0982.539.678
                </a>
                <span class="hidden md:flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-brand-accent"></i> ntwindow.com
                </span>
            </div>
        </div>
    </div>

    <!-- =========================================================
         SECTION 2: MAIN HEADER (LOGO GỌN NHỎ + TÌM KIẾM, KHÔNG NÚT GỌI NGAY)
    ========================================================== -->
    <header id="trang-chu" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="nt-container py-2.5 flex items-center justify-between gap-3">
            <!-- Nút Mở Menu Mobile -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-brand-light transition shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>

            <!-- Logo NT Window chuyên nghiệp, thiết kế gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" aria-label="Logo NT Window">
                    <rect width="64" height="64" rx="12" fill="#0A3D7A"/>
                    <!-- Khung cửa kiến trúc -->
                    <rect x="9" y="9" width="46" height="46" rx="6" stroke="#FFFFFF" stroke-width="3"/>
                    <!-- Khung chia ô cửa hiện đại -->
                    <path d="M32 9V55" stroke="#F58220" stroke-width="3"/>
                    <path d="M9 28H55" stroke="#FFFFFF" stroke-width="2" stroke-opacity="0.7"/>
                    <!-- Chữ lồng NT sắc nét -->
                    <path d="M15 47V34H18.8L25.2 42.4V34H28.8V47H25.1L18.6 38.5V47H15Z" fill="#FFFFFF"/>
                    <path d="M36 37.2V34H49.5V37.2H44.6V47H40.9V37.2H36Z" fill="#F58220"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-base sm:text-lg font-extrabold tracking-tight text-brand-navy group-hover:text-brand-blue transition">
                        NT <span class="text-brand-accent">WINDOW</span>
                    </div>
                    <div class="text-[10px] sm:text-[11px] font-semibold text-slate-500 tracking-wider uppercase">
                        Nhôm Kính Cao Cấp
                    </div>
                </div>
            </a>

            <!-- Thanh tìm kiếm sản phẩm gọn gàng -->
            <div class="hidden md:flex flex-1 max-w-md mx-4">
                <form id="searchForm" class="w-full relative flex items-center">
                    <input id="searchInput" type="text" placeholder="Tìm cửa nhôm Xingfa, cửa kính, cầu thang..." class="w-full pl-4 pr-11 py-2 text-sm bg-slate-50 border border-slate-200 rounded-full focus:outline-none focus:border-brand-navy focus:bg-white transition">
                    <button type="submit" aria-label="Tìm kiếm" class="absolute right-1.5 w-8 h-8 rounded-full bg-brand-navy text-white flex items-center justify-center hover:bg-brand-accent transition">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </form>
            </div>

            <!-- Thông tin ngắn bên phải header (Không để nút Gọi ngay tránh tràn viền) -->
            <div class="flex items-center gap-3 shrink-0">
                <div class="hidden xl:flex items-center gap-2 text-xs text-slate-600">
                    <span class="w-8 h-8 rounded-full bg-brand-light text-brand-navy flex items-center justify-center">
                        <i class="fa-solid fa-shield-halved"></i>
                    </span>
                    <div class="leading-snug">
                        <div class="font-bold text-brand-navy">Chính hãng 100%</div>
                        <div class="text-[11px]">Bảo hành 5 năm</div>
                    </div>
                </div>
                <button id="openQuoteQuickBtn" type="button" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-brand-light text-brand-navy hover:bg-brand-navy hover:text-white text-xs font-semibold transition">
                    <i class="fa-solid fa-file-invoice text-brand-accent"></i>
                    <span>Nhận báo giá</span>
                </button>
            </div>
        </div>

        <!-- =========================================================
             SECTION 3: THANH DANH MỤC TRÊN MÁY TÍNH (1 HÀNG DUY NHẤT, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG)
        ========================================================== -->
        <nav aria-label="Danh mục chính" class="hidden lg:block bg-brand-navy text-white border-t border-white/10">
            <div class="nt-container">
                <ul class="flex items-center justify-between flex-nowrap w-full py-0">
                    <li class="shrink-0">
                        <a href="#trang-chu" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Trang chủ
                        </a>
                    </li>
                    <li class="shrink-0">
                        <a href="#gioi-thieu" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Giới thiệu
                        </a>
                    </li>

                    <!-- Dropdown: Cửa nhôm xingfa -->
                    <li class="relative nav-item shrink-0">
                        <a href="#san-pham" class="flex items-center gap-1 px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            <span>Cửa nhôm xingfa</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                        </a>
                        <ul class="nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-100 py-1.5 z-50">
                            <li><a href="#san-pham" onclick="filterProductByKeyword('1 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProductByKeyword('2 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProductByKeyword('3 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProductByKeyword('4 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a></li>
                            <li><a href="#san-pham" onclick="filterProductByKeyword('xếp trượt')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
                        </ul>
                    </li>

                    <li class="shrink-0">
                        <a href="#danh-muc" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Cửa kính cường lực
                        </a>
                    </li>

                    <!-- Dropdown: Sản phẩm -->
                    <li class="relative nav-item shrink-0">
                        <a href="#danh-muc" class="flex items-center gap-1 px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            <span>Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                        </a>
                        <ul class="nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-100 py-1.5 z-50">
                            <li><a href="#danh-muc" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhôm xingfa</a></li>
                            <li><a href="#danh-muc" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa nhựa lõi thép</a></li>
                            <li><a href="#danh-muc" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cửa kính tự động</a></li>
                            <li><a href="#danh-muc" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Cầu thang kính</a></li>
                            <li><a href="#danh-muc" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Kính ốp bếp</a></li>
                            <li><a href="#danh-muc" class="block px-4 py-2 text-xs font-medium hover:bg-brand-light hover:text-brand-navy transition whitespace-nowrap">Phòng tắm kính</a></li>
                        </ul>
                    </li>

                    <li class="shrink-0">
                        <a href="#cong-trinh" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Công trình
                        </a>
                    </li>
                    <li class="shrink-0">
                        <a href="#bao-gia" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Báo giá
                        </a>
                    </li>
                    <li class="shrink-0">
                        <a href="#tin-tuc" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Tin tức
                        </a>
                    </li>
                    <li class="shrink-0">
                        <a href="#lien-he" class="block px-2 xl:px-3 py-2.5 text-[11.5px] xl:text-[12.5px] font-semibold uppercase tracking-tight whitespace-nowrap hover:text-brand-accent transition">
                            Liên hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- =========================================================
         MOBILE DRAWER MENU (TỐI ƯU GIAO DIỆN DANH MỤC TRÊN ĐIỆN THOẠI)
    ========================================================== -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
    <aside id="mobileDrawer" class="fixed top-0 left-0 h-full w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between p-4 bg-brand-navy text-white">
            <span class="font-extrabold tracking-tight text-base">NT <span class="text-brand-accent">WINDOW</span></span>
            <button id="closeMobileMenuBtn" type="button" aria-label="Đóng danh mục" class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center hover:bg-white/20">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <!-- Tìm kiếm trong menu mobile -->
        <div class="p-3 border-b border-slate-100">
            <form id="mobileSearchForm" class="relative flex items-center">
                <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm..." class="w-full pl-3 pr-9 py-2 text-xs bg-slate-50 border border-slate-200 rounded-lg focus:outline-none focus:border-brand-navy">
                <button type="submit" aria-label="Tìm" class="absolute right-2 text-brand-navy">
                    <i class="fa-solid fa-magnifying-glass text-xs"></i>
                </button>
            </form>
        </div>

        <!-- Danh mục mobile có đóng/mở submenu -->
        <nav class="flex-1 overflow-y-auto py-2">
            <ul class="divide-y divide-slate-100 text-sm font-medium text-slate-700">
                <li><a href="#trang-chu" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Trang chủ</a></li>
                <li><a href="#gioi-thieu" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Giới thiệu</a></li>
                <li>
                    <div class="flex items-center justify-between px-4 py-3">
                        <a href="#san-pham" class="mobile-nav-link flex-1 hover:text-brand-navy">Cửa nhôm xingfa</a>
                        <button type="button" class="submenu-toggle w-7 h-7 rounded bg-slate-100 text-brand-navy flex items-center justify-center" data-target="sub-xingfa">
                            <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                        </button>
                    </div>
                    <ul id="sub-xingfa" class="hidden bg-slate-50 pl-6 pr-4 py-1.5 space-y-1 text-xs text-slate-600">
                        <li><a href="#san-pham" onclick="filterProductByKeyword('1 cánh')" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('2 cánh')" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('3 cánh')" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('4 cánh')" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('xếp trượt')" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhôm xingfa 5 cánh</a></li>
                    </ul>
                </li>
                <li><a href="#danh-muc" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Cửa kính cường lực</a></li>
                <li>
                    <div class="flex items-center justify-between px-4 py-3">
                        <a href="#danh-muc" class="mobile-nav-link flex-1 hover:text-brand-navy">Sản phẩm</a>
                        <button type="button" class="submenu-toggle w-7 h-7 rounded bg-slate-100 text-brand-navy flex items-center justify-center" data-target="sub-sanpham">
                            <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                        </button>
                    </div>
                    <ul id="sub-sanpham" class="hidden bg-slate-50 pl-6 pr-4 py-1.5 space-y-1 text-xs text-slate-600">
                        <li><a href="#danh-muc" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhôm xingfa</a></li>
                        <li><a href="#danh-muc" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa nhựa lõi thép</a></li>
                        <li><a href="#danh-muc" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cửa kính tự động</a></li>
                        <li><a href="#danh-muc" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Cầu thang kính</a></li>
                        <li><a href="#danh-muc" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Kính ốp bếp</a></li>
                        <li><a href="#danh-muc" class="mobile-nav-link block py-1.5 hover:text-brand-navy">+ Phòng tắm kính</a></li>
                    </ul>
                </li>
                <li><a href="#cong-trinh" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Công trình</a></li>
                <li><a href="#bao-gia" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Báo giá</a></li>
                <li><a href="#tin-tuc" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Tin tức</a></li>
                <li><a href="#lien-he" class="mobile-nav-link block px-4 py-3 hover:bg-brand-light hover:text-brand-navy">Liên hệ</a></li>
            </ul>
        </nav>

        <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
            <div class="font-bold text-brand-navy">Hotline: 0982.539.678</div>
            <div>183 Mạc Đăng Dung, P. Hòa Xuân, Đà Nẵng</div>
        </div>
    </aside>

    <!-- =========================================================
         SECTION 4: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU,
         CHỮ & HÌNH NẰM TRỌN TRONG BANNER, CÁCH XA VIỀN, KHÔNG CẮT CHỮ TRÊN MOBILE & PC)
    ========================================================== -->
    <section class="pt-4 pb-6 bg-white">
        <div class="nt-container">
            <div id="heroSlider" class="relative rounded-2xl overflow-hidden shadow-lg bg-brand-navy">
                <div class="hero-slider-grid">

                    <!-- BANNER 1 -->
                    <div class="hero-slide active relative bg-gradient-to-br from-[#072B59] via-[#0A3D7A] to-[#1256A3] text-white">
                        <!-- Họa tiết kiến trúc mờ nền -->
                        <div class="absolute inset-0 opacity-10 pointer-events-none" style="background-image: radial-gradient(#FFFFFF 1px, transparent 1px); background-size: 24px 24px;"></div>

                        <!-- Vùng an toàn chữ & hình cách xa viền banner trên cả mobile và desktop -->
                        <div class="relative z-10 px-10 py-8 sm:px-14 sm:py-10 lg:px-20 lg:py-12 grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
                            <!-- Nội dung chữ Banner 1 -->
                            <div class="md:col-span-7 space-y-3 sm:space-y-4 text-left">
                                <div class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-accent">
                                    NT WINDOW • NHÔM XINGFA ĐÀ NẴNG
                                </div>
                                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight text-white">
                                    CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-xl">
                                    Thanh nhôm Xingfa tem đỏ Quảng Đông kết hợp phụ kiện Kinlong đồng bộ. Cách âm, cách nhiệt vượt trội, thẩm mỹ sang trọng cho nhà phố, biệt thự và khách sạn.
                                </p>
                                <div class="pt-2 flex flex-wrap items-center gap-3">
                                    <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow transition">
                                        <span>Nhận báo giá ưu đãi</span>
                                        <i class="fa-solid fa-arrow-right text-xs"></i>
                                    </a>
                                    <a href="#san-pham" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/25 text-xs sm:text-sm font-semibold transition">
                                        <span>Xem mẫu cửa</span>
                                    </a>
                                </div>
                            </div>

                            <!-- Hình ảnh sản phẩm nằm gọn trong khung Banner 1 -->
                            <div class="md:col-span-5 flex justify-center">
                                <div class="w-full max-w-sm aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10">
                                    <img data-gdrive="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-" data-fallback="Cua+Nhom+Xingfa+4+Canh" alt="Cửa nhôm Xingfa nhập khẩu NT Window" class="gdrive-img w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="hero-slide relative bg-gradient-to-br from-[#0A3D7A] via-[#0E4A8F] to-[#082E5E] text-white">
                        <div class="absolute inset-0 opacity-10 pointer-events-none" style="background-image: linear-gradient(135deg, #F58220 1px, transparent 1px); background-size: 30px 30px;"></div>

                        <!-- Vùng an toàn chữ & hình cách xa viền banner đồng nhất kích thước với Banner 1 -->
                        <div class="relative z-10 px-10 py-8 sm:px-14 sm:py-10 lg:px-20 lg:py-12 grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center h-full">
                            <!-- Nội dung chữ Banner 2 -->
                            <div class="md:col-span-7 space-y-3 sm:space-y-4 text-left">
                                <div class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-accent">
                                    THI CÔNG TRỌN GÓI • BẢO HÀNH DÀI HẠN
                                </div>
                                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug tracking-tight text-white">
                                    CỬA KÍNH CƯỜNG LỰC & HẠNG MỤC NHÔM KÍNH HIỆN ĐẠI
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-xl">
                                    Tư vấn khảo sát tận nơi miễn phí tại Đà Nẵng. Thi công chuẩn kỹ thuật Cửa Kính Tự Động, Phòng Tắm Kính, Cầu Thang Kính, Kính Ốp Bếp với chi phí tối ưu nhất.
                                </p>
                                <div class="pt-2 flex flex-wrap items-center gap-3">
                                    <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow transition">
                                        <span>Xem dự án Đà Nẵng</span>
                                        <i class="fa-solid fa-building text-xs"></i>
                                    </a>
                                    <a href="tel:0982539678" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/25 text-xs sm:text-sm font-semibold transition">
                                        <i class="fa-solid fa-phone text-xs text-brand-accent"></i>
                                        <span>0982.539.678</span>
                                    </a>
                                </div>
                            </div>

                            <!-- Hình ảnh công trình nằm gọn trong khung Banner 2 -->
                            <div class="md:col-span-5 flex justify-center">
                                <div class="w-full max-w-sm aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10">
                                    <img data-gdrive="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ" data-fallback="Du+An+Nhom+Kinh+NT+Window" alt="Thi công công trình nhôm kính NT Window Đà Nẵng" class="gdrive-img w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút chuyển trái/phải gọn ở sát mép ngoài, không che chữ -->
                <button id="prevSlideBtn" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-brand-accent text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button id="nextSlideBtn" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-brand-accent text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm tròn điều hướng banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" class="slider-dot w-6 h-2 rounded-full bg-brand-accent transition-all" data-index="0" aria-label="Banner 1"></button>
                    <button type="button" class="slider-dot w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-index="1" aria-label="Banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 5: GIỚI THIỆU NT WINDOW & CHỈ SỐ NĂNG LỰC (FLATSOME STYLE)
    ========================================================== -->
    <section id="gioi-thieu" class="py-10 bg-slate-50 border-y border-slate-200/70">
        <div class="nt-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <div class="lg:col-span-7 space-y-4">
                    <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase leading-snug">
                        CÔNG TY CỬA NHÔM XINGFA ĐÀ NẴNG – <span class="text-brand-accent">NT WINDOW</span>
                    </h2>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        <strong>NT Window</strong> là đơn vị chuyên thiết kế, gia công và thi công lắp đặt các hạng mục nhôm kính cao cấp hàng đầu tại Đà Nẵng và khu vực Miền Trung. Với xưởng sản xuất hiện đại tại <strong>183 Mạc Đăng Dung, Phường Hòa Xuân, TP Đà Nẵng</strong>, chúng tôi cung cấp trọn gói: Cửa nhôm Xingfa nhập khẩu, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính.
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Với phương châm <strong>“Uy tín – Chất lượng – Thẩm mỹ bền vững”</strong>, NT Window cam kết sử dụng vật tư chính hãng 100%, quy trình ép góc CNC chuẩn xác và chính sách bảo hành chu đáo cho mọi công trình từ nhà phố, biệt thự đến khách sạn, resort cao cấp.
                    </p>

                    <!-- Cam kết dịch vụ ngắn gọn -->
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 pt-2">
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-xl border border-slate-200/80">
                            <i class="fa-solid fa-circle-check text-brand-accent text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Khảo sát & lắp đặt tận nơi miễn phí</span>
                        </div>
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-xl border border-slate-200/80">
                            <i class="fa-solid fa-circle-check text-brand-accent text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Nhôm Xingfa & phụ kiện chính hãng</span>
                        </div>
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-xl border border-slate-200/80">
                            <i class="fa-solid fa-circle-check text-brand-accent text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Ưu đãi chiết khấu thi công đến 20%</span>
                        </div>
                        <div class="flex items-center gap-2.5 bg-white p-3 rounded-xl border border-slate-200/80">
                            <i class="fa-solid fa-circle-check text-brand-accent text-base shrink-0"></i>
                            <span class="text-xs sm:text-sm font-medium text-slate-700">Bảo hành kết cấu & phụ kiện dài hạn</span>
                        </div>
                    </div>
                </div>

                <!-- 4 Ô thống kê năng lực theo mẫu ngochanwindow -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-4">
                    <div class="bg-white p-5 rounded-xl shadow-sm border border-slate-200/80 text-center">
                        <div class="text-2xl sm:text-3xl font-black text-brand-navy">150+</div>
                        <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án hoàn thành</div>
                    </div>
                    <div class="bg-white p-5 rounded-xl shadow-sm border border-slate-200/80 text-center">
                        <div class="text-2xl sm:text-3xl font-black text-brand-accent">50+</div>
                        <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Kỹ thuật viên lành nghề</div>
                    </div>
                    <div class="bg-white p-5 rounded-xl shadow-sm border border-slate-200/80 text-center">
                        <div class="text-2xl sm:text-3xl font-black text-brand-navy">100+</div>
                        <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu sản phẩm chuẩn</div>
                    </div>
                    <div class="bg-white p-5 rounded-xl shadow-sm border border-slate-200/80 text-center">
                        <div class="text-2xl sm:text-3xl font-black text-brand-accent">100%</div>
                        <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 6: SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT TRÊN MOBILE,
         GIÁ & GIẢM GIÁ % GÓC TRÊN TRÁI, TÊN SẢN PHẨM ĐẦY ĐỦ KHÔNG TRÀN)
    ========================================================== -->
    <section id="san-pham" class="py-12 bg-white">
        <div class="nt-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    SẢN PHẨM CỬA NHÔM XINGFA NỔI BẬT
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3 max-w-2xl mx-auto">
                    Các mẫu cửa đi, cửa sổ nhôm Xingfa hệ 55 & 93 bán chạy nhất tại Đà Nẵng – cập nhật giá ưu đãi trực tiếp từ xưởng NT Window.
                </p>
            </div>

            <!-- Thanh lọc nhanh sản phẩm gọn gàng -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
                <button type="button" onclick="renderProducts('all')" class="prod-filter-btn px-3.5 py-1.5 rounded-full text-xs font-semibold bg-brand-navy text-white transition" data-filter="all">Tất cả</button>
                <button type="button" onclick="renderProducts('cua-di')" class="prod-filter-btn px-3.5 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition" data-filter="cua-di">Cửa đi mở quay</button>
                <button type="button" onclick="renderProducts('xep-truot')" class="prod-filter-btn px-3.5 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition" data-filter="xep-truot">Cửa xếp trượt</button>
                <button type="button" onclick="renderProducts('cua-so')" class="prod-filter-btn px-3.5 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition" data-filter="cua-so">Cửa sổ mở hất</button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (md:grid-cols-3) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-6">
                <!-- Dữ liệu sản phẩm được render tự động bằng JavaScript bên dưới -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 7: DANH MỤC SẢN PHẨM NỔI BẬT (THEO MẪU NGOCHANWINDOW)
    ========================================================== -->
    <section id="danh-muc" class="py-12 bg-slate-50 border-y border-slate-200/70">
        <div class="nt-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    DANH MỤC SẢN PHẨM CHÍNH
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3">
                    Đa dạng hạng mục nhôm kính nội thất và ngoại thất thi công trực tiếp tại Đà Nẵng
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-6">
                <!-- Danh mục 1: Cửa nhôm xingfa -->
                <a href="#san-pham" class="group bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md border border-slate-200/80 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img data-gdrive="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX" data-fallback="Cua+Nhom+Xingfa" alt="Cửa nhôm xingfa" class="gdrive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase group-hover:text-brand-accent transition break-words">
                            Cửa Nhôm Xingfa
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 2: Cửa nhựa lõi thép -->
                <a href="#form-bao-gia" onclick="selectQuoteCategory('Cửa nhựa lõi thép')" class="group bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md border border-slate-200/80 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img data-gdrive="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA" data-fallback="Cua+Nhua+Loi+Thep" alt="Cửa nhựa lõi thép" class="gdrive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase group-hover:text-brand-accent transition break-words">
                            Cửa Nhựa Lõi Thép
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 3: Cửa tự động -->
                <a href="#form-bao-gia" onclick="selectQuoteCategory('Cửa kính tự động')" class="group bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md border border-slate-200/80 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img data-gdrive="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ" data-fallback="Cua+Kinh+Tu+Dong" alt="Cửa tự động" class="gdrive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase group-hover:text-brand-accent transition break-words">
                            Cửa Kính Tự Động
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 4: Cầu thang kính -->
                <a href="#form-bao-gia" onclick="selectQuoteCategory('Cầu thang kính')" class="group bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md border border-slate-200/80 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img data-gdrive="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul" data-fallback="Cau+Thang+Kinh" alt="Cầu thang kính" class="gdrive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase group-hover:text-brand-accent transition break-words">
                            Cầu Thang Kính
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 5: Kính ốp bếp -->
                <a href="#form-bao-gia" onclick="selectQuoteCategory('Kính ốp bếp')" class="group bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md border border-slate-200/80 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img data-gdrive="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb" data-fallback="Kinh+Op+Bep" alt="Kính ốp bếp" class="gdrive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase group-hover:text-brand-accent transition break-words">
                            Kính Ốp Bếp
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 6: Phòng tắm kính -->
                <a href="#form-bao-gia" onclick="selectQuoteCategory('Phòng tắm kính')" class="group bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-md border border-slate-200/80 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img data-gdrive="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH" data-fallback="Phong+Tam+Kinh" alt="Phòng tắm kính" class="gdrive-img w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy uppercase group-hover:text-brand-accent transition break-words">
                            Phòng Tắm Kính
                        </h3>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 8: BẢNG BÁO GIÁ THAM KHẢO CỬA NHÔM XINGFA ĐÀ NẴNG
    ========================================================== -->
    <section id="bao-gia" class="py-12 bg-white">
        <div class="nt-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    BÁO GIÁ CỬA NHÔM XINGFA ĐÀ NẴNG
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3">
                    Bảng giá tham khảo lắp đặt hoàn thiện (Nhôm Xingfa nhập khẩu tem đỏ, kính cường lực 8mm/an toàn 6.38mm, gioăng EPDM)
                </p>
            </div>

            <div class="overflow-x-auto rounded-xl border border-slate-200 shadow-sm">
                <table class="w-full text-left border-collapse text-xs sm:text-sm">
                    <thead>
                        <tr class="bg-brand-navy text-white">
                            <th class="py-3 px-4 font-semibold w-12 text-center">STT</th>
                            <th class="py-3 px-4 font-semibold">Hệ cửa nhôm Xingfa</th>
                            <th class="py-3 px-4 font-semibold hidden md:table-cell">Thông số kỹ thuật</th>
                            <th class="py-3 px-4 font-semibold text-right">Đơn giá (VNĐ/m²)</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-200 bg-white">
                        <tr class="hover:bg-brand-light/50 transition">
                            <td class="py-3 px-4 text-center font-semibold text-slate-500">01</td>
                            <td class="py-3 px-4 font-bold text-brand-navy">Cửa đi mở quay 1 cánh nhôm Xingfa</td>
                            <td class="py-3 px-4 text-slate-600 hidden md:table-cell">Hệ 55 dày 2.0mm, phụ kiện Kinlong chính hãng</td>
                            <td class="py-3 px-4 text-right font-bold text-brand-accent">1.950.000 ₫</td>
                        </tr>
                        <tr class="hover:bg-brand-light/50 transition">
                            <td class="py-3 px-4 text-center font-semibold text-slate-500">02</td>
                            <td class="py-3 px-4 font-bold text-brand-navy">Cửa đi mở quay 2 cánh nhôm Xingfa</td>
                            <td class="py-3 px-4 text-slate-600 hidden md:table-cell">Hệ 55 dày 2.0mm, kính an toàn 6.38mm / 8mm</td>
                            <td class="py-3 px-4 text-right font-bold text-brand-accent">2.050.000 ₫</td>
                        </tr>
                        <tr class="hover:bg-brand-light/50 transition">
                            <td class="py-3 px-4 text-center font-semibold text-slate-500">03</td>
                            <td class="py-3 px-4 font-bold text-brand-navy">Cửa đi mở quay 3 cánh & 4 cánh nhôm Xingfa</td>
                            <td class="py-3 px-4 text-slate-600 hidden md:table-cell">Hệ 55 dày 2.0mm, bản lề 3D, khóa đa điểm</td>
                            <td class="py-3 px-4 text-right font-bold text-brand-accent">2.100.000 ₫</td>
                        </tr>
                        <tr class="hover:bg-brand-light/50 transition">
                            <td class="py-3 px-4 text-center font-semibold text-slate-500">04</td>
                            <td class="py-3 px-4 font-bold text-brand-navy">Cửa đi mở xếp trượt nhôm Xingfa (4-6 cánh)</td>
                            <td class="py-3 px-4 text-slate-600 hidden md:table-cell">Hệ 63 nhập khẩu, ray trượt êm ái chịu tải cao</td>
                            <td class="py-3 px-4 text-right font-bold text-brand-accent">2.250.000 ₫</td>
                        </tr>
                        <tr class="hover:bg-brand-light/50 transition">
                            <td class="py-3 px-4 text-center font-semibold text-slate-500">05</td>
                            <td class="py-3 px-4 font-bold text-brand-navy">Cửa sổ mở hất 2 cánh nhôm Xingfa</td>
                            <td class="py-3 px-4 text-slate-600 hidden md:table-cell">Hệ 55 dày 1.4mm, chống nước hắt tuyệt đối</td>
                            <td class="py-3 px-4 text-right font-bold text-brand-accent">1.850.000 ₫</td>
                        </tr>
                        <tr class="hover:bg-brand-light/50 transition">
                            <td class="py-3 px-4 text-center font-semibold text-slate-500">06</td>
                            <td class="py-3 px-4 font-bold text-brand-navy">Cửa kính cường lực 10mm – 12mm bản lề sàn</td>
                            <td class="py-3 px-4 text-slate-600 hidden md:table-cell">Kính tôi nhiệt an toàn, phụ kiện VVP / Hafele</td>
                            <td class="py-3 px-4 text-right font-bold text-brand-accent">750.000 ₫</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 9: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 CÔNG TRÌNH)
    ========================================================== -->
    <section id="cong-trinh" class="py-12 bg-slate-50 border-y border-slate-200/70">
        <div class="nt-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3">
                    Các công trình khách sạn, resort tiêu chuẩn 4 sao và căn hộ cao cấp tiêu biểu đã triển khai
                </p>
            </div>

            <div id="projectGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5">
                <!-- Dữ liệu 6 dự án Đà Nẵng render bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 10: DANH MỤC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ
    ========================================================== -->
    <section id="tin-tuc" class="py-12 bg-white">
        <div class="nt-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    TIN TỨC & KINH NGHIỆM CHỌN CỬA
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3">
                    Kiến thức chuyên sâu về nhôm Xingfa, kính cường lực và giải pháp thi công tối ưu
                </p>
            </div>

            <div id="newsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <!-- Bài viết render bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 11: ĐỐI TÁC CỦA CHÚNG TÔI (6 LOGO ĐỐI TÁC GOOGLE DRIVE)
    ========================================================== -->
    <section class="py-10 bg-slate-50 border-t border-slate-200/70">
        <div class="nt-container">
            <div class="text-center mb-7">
                <h2 class="flatsome-section-title text-base sm:text-xl font-extrabold text-brand-navy uppercase">
                    ĐỐI TÁC CỦA CHÚNG TÔI
                </h2>
            </div>
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-4 items-center">
                <div class="bg-white rounded-xl border border-slate-200/80 p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
                    <img data-gdrive="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" data-fallback="Doi+Tac+1" alt="Đối tác NT Window 1" class="gdrive-img max-h-14 max-w-full object-contain">
                </div>
                <div class="bg-white rounded-xl border border-slate-200/80 p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
                    <img data-gdrive="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" data-fallback="Doi+Tac+2" alt="Đối tác NT Window 2" class="gdrive-img max-h-14 max-w-full object-contain">
                </div>
                <div class="bg-white rounded-xl border border-slate-200/80 p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
                    <img data-gdrive="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" data-fallback="Doi+Tac+3" alt="Đối tác NT Window 3" class="gdrive-img max-h-14 max-w-full object-contain">
                </div>
                <div class="bg-white rounded-xl border border-slate-200/80 p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
                    <img data-gdrive="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" data-fallback="Doi+Tac+4" alt="Đối tác NT Window 4" class="gdrive-img max-h-14 max-w-full object-contain">
                </div>
                <div class="bg-white rounded-xl border border-slate-200/80 p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
                    <img data-gdrive="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" data-fallback="Doi+Tac+5" alt="Đối tác NT Window 5" class="gdrive-img max-h-14 max-w-full object-contain">
                </div>
                <div class="bg-white rounded-xl border border-slate-200/80 p-3 h-20 flex items-center justify-center hover:shadow-sm transition">
                    <img data-gdrive="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" data-fallback="Doi+Tac+6" alt="Đối tác NT Window 6" class="gdrive-img max-h-14 max-w-full object-contain">
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 12: FORM YÊU CẦU BÁO GIÁ + GOOGLE MAP + FANPAGE TRANG CHỦ
    ========================================================== -->
    <section id="lien-he" class="py-12 bg-white border-t border-slate-200">
        <div class="nt-container">
            <div class="text-center mb-8">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    YÊU CẦU BÁO GIÁ – BẢN ĐỒ & FANPAGE
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-3">
                    Để lại thông tin để kỹ thuật viên NT Window khảo sát, đo đạc và gửi báo giá chi tiết hoàn toàn miễn phí
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột 1: Form Yêu Cầu & Báo Giá (5/12) -->
                <div id="form-bao-gia" class="lg:col-span-5 bg-slate-50 rounded-2xl border border-slate-200 p-5 sm:p-6 flex flex-col justify-between">
                    <div>
                        <h3 class="text-base sm:text-lg font-extrabold text-brand-navy uppercase mb-1 flex items-center gap-2">
                            <i class="fa-solid fa-pen-to-square text-brand-accent"></i>
                            <span>Đăng ký nhận báo giá nhanh</span>
                        </h3>
                        <p class="text-xs text-slate-500 mb-4">Phản hồi tư vấn trong vòng 15 phút • Hotline: 0982.539.678</p>

                        <form id="quoteRequestForm" class="space-y-3.5">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy">
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                                    <input id="qPhone" type="tel" required placeholder="0982 xxx xxx" class="w-full px-3.5 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy">
                                </div>
                                <div>
                                    <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                                    <select id="qCategory" class="w-full px-3 py-2.5 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy">
                                        <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                        <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                        <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                        <option value="Cửa kính tự động">Cửa kính tự động</option>
                                        <option value="Cầu thang kính">Cầu thang kính</option>
                                        <option value="Kính ốp bếp">Kính ốp bếp</option>
                                        <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    </select>
                                </div>
                            </div>
                            <div>
                                <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Kích thước dự kiến / Ghi chú công trình</label>
                                <textarea id="qNote" rows="3" placeholder="Ví dụ: Cần làm 1 cửa đi 4 cánh, 2 cửa sổ mở hất tại quận Cẩm Lệ, Đà Nẵng..." class="w-full px-3.5 py-2 text-sm bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brand-navy"></textarea>
                            </div>
                            <button type="submit" class="w-full py-3 rounded-lg bg-brand-navy hover:bg-brand-accent text-white font-bold text-sm uppercase tracking-wide shadow transition flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Gửi yêu cầu báo giá ngay</span>
                            </button>
                        </form>
                    </div>

                    <!-- Thông báo gửi form thành công (Không dùng alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs leading-relaxed">
                        <div class="font-bold flex items-center gap-1.5 mb-0.5">
                            <i class="fa-solid fa-circle-check text-emerald-600"></i>
                            <span>Gửi yêu cầu thành công!</span>
                        </div>
                        <span id="quoteSuccessText"></span>
                    </div>
                </div>

                <!-- Cột 2: Bản đồ Google Map ra ngoài trang chủ (4/12) -->
                <div class="lg:col-span-4 bg-slate-50 rounded-2xl border border-slate-200 p-4 flex flex-col">
                    <div class="flex items-center justify-between mb-3">
                        <h3 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
                            <span>Bản đồ Google Map</span>
                        </h3>
                        <a href="https://maps.google.com/?q=183+Mac+Dang+Dung,+Hoa+Xuan,+Da+Nang" target="_blank" rel="noopener" class="text-xs font-semibold text-brand-blue hover:text-brand-accent transition">
                            Chỉ đường <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
                        </a>
                    </div>
                    <p class="text-xs text-slate-600 mb-3">
                        <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>
                        183 Mạc Đăng Dung, Phường Hòa Xuân, TP Đà Nẵng
                    </p>
                    <div class="flex-1 min-h-[260px] rounded-xl overflow-hidden border border-slate-200 bg-white">
                        <iframe
                            title="Bản đồ NT Window - 183 Mạc Đăng Dung, Hòa Xuân, Đà Nẵng"
                            src="https://maps.google.com/maps?q=183%20M%E1%BA%A1c%20%C4%90%C4%83ng%20Dung,%20H%C3%B2a%20Xu%C3%A2n,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[260px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột 3: Fanpage Facebook ra ngoài trang chủ (3/12) -->
                <div class="lg:col-span-3 bg-slate-50 rounded-2xl border border-slate-200 p-4 flex flex-col">
                    <h3 class="text-sm sm:text-base font-extrabold text-brand-navy uppercase mb-3 flex items-center gap-2">
                        <i class="fa-brands fa-facebook text-[#1877F2]"></i>
                        <span>Fanpage Facebook</span>
                    </h3>

                    <!-- Khung Fanpage chuẩn giao diện Facebook Page Plugin -->
                    <div class="flex-1 bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col shadow-sm">
                        <!-- Ảnh bìa Fanpage -->
                        <div class="relative h-28 bg-gradient-to-r from-brand-navy to-brand-blue p-3 flex flex-col justify-between text-white">
                            <div class="flex items-start gap-2.5">
                                <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                    <svg class="w-full h-full" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect width="64" height="64" rx="10" fill="#0A3D7A"/>
                                        <rect x="9" y="9" width="46" height="46" rx="5" stroke="#FFFFFF" stroke-width="3"/>
                                        <path d="M32 9V55" stroke="#F58220" stroke-width="3"/>
                                        <path d="M15 47V34H18.8L25.2 42.4V34H28.8V47H25.1L18.6 38.5V47H15Z" fill="#FFFFFF"/>
                                        <path d="M36 37.2V34H49.5V37.2H44.6V47H40.9V37.2H36Z" fill="#F58220"/>
                                    </svg>
                                </div>
                                <div class="min-w-0">
                                    <div class="font-bold text-sm leading-tight truncate">NT Window Đà Nẵng</div>
                                    <div class="text-[11px] text-blue-100 mt-0.5">4.860 lượt thích • 5.120 người theo dõi</div>
                                </div>
                            </div>
                            <div class="flex items-center justify-between gap-2">
                                <a href="https://www.facebook.com/" target="_blank" rel="noopener" class="inline-flex items-center gap-1.5 px-2.5 py-1 rounded bg-white text-slate-800 text-[11px] font-bold hover:bg-slate-100 transition">
                                    <i class="fa-brands fa-facebook-square text-[#1877F2]"></i> Thích Trang
                                </a>
                                <a href="https://m.me/" target="_blank" rel="noopener" class="inline-flex items-center gap-1 px-2.5 py-1 rounded bg-[#1877F2] text-white text-[11px] font-semibold hover:bg-blue-700 transition">
                                    <i class="fa-brands fa-facebook-messenger"></i> Nhắn tin
                                </a>
                            </div>
                        </div>

                        <!-- Bài đăng mới nhất hiển thị trong khung Fanpage -->
                        <div class="p-3.5 flex-1 flex flex-col justify-between text-xs text-slate-600 space-y-3">
                            <div>
                                <div class="font-bold text-slate-800 mb-1">Cập nhật công trình mới nhất</div>
                                <p class="leading-relaxed">
                                    Hoàn thiện lắp đặt trọn bộ cửa nhôm Xingfa hệ 55 & vách kính cường lực tại Hòa Xuân, Đà Nẵng. Nhận khảo sát báo giá miễn phí 24/7!
                                </p>
                            </div>
                            <div class="pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
                                <span><i class="fa-solid fa-phone text-brand-accent mr-1"></i>0982.539.678</span>
                                <a href="https://www.facebook.com/" target="_blank" rel="noopener" class="text-[#1877F2] font-semibold hover:underline">Xem Fanpage →</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         SECTION 13: FOOTER (FLATSOME 4 CỘT ĐỒNG BỘ MÀU LOGO)
    ========================================================== -->
    <footer class="bg-brand-navy text-blue-100 pt-12 pb-6">
        <div class="nt-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/15">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="12" fill="#FFFFFF"/>
                            <rect x="9" y="9" width="46" height="46" rx="6" stroke="#0A3D7A" stroke-width="3.2"/>
                            <path d="M32 9V55" stroke="#F58220" stroke-width="3.2"/>
                            <path d="M15 47V34H18.8L25.2 42.4V34H28.8V47H25.1L18.6 38.5V47H15Z" fill="#0A3D7A"/>
                            <path d="M36 37.2V34H49.5V37.2H44.6V47H40.9V37.2H36Z" fill="#F58220"/>
                        </svg>
                        <div>
                            <div class="text-base font-extrabold text-white">NT <span class="text-brand-accent">WINDOW</span></div>
                            <div class="text-[10px] uppercase tracking-wider text-blue-200">ntwindow.com</div>
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-blue-100/90">
                        Đơn vị thiết kế, sản xuất và thi công Cửa Nhôm Xingfa, Cửa Kính Cường Lực, Nhôm Kính Cao Cấp uy tín hàng đầu tại TP Đà Nẵng.
                    </p>
                    <ul class="space-y-2 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-brand-accent mt-0.5 shrink-0"></i>
                            <span>183 Mạc Đăng Dung, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-brand-accent shrink-0"></i>
                            <a href="tel:0982539678" class="hover:text-white font-semibold">0982.539.678</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-brand-accent shrink-0"></i>
                            <span>www.ntwindow.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-brand-accent/60 inline-block">
                        Danh mục sản phẩm
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#danh-muc" class="hover:text-brand-accent transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
                        <li><a href="#danh-muc" class="hover:text-brand-accent transition">Cửa nhựa lõi thép</a></li>
                        <li><a href="#danh-muc" class="hover:text-brand-accent transition">Cửa kính cường lực</a></li>
                        <li><a href="#danh-muc" class="hover:text-brand-accent transition">Cửa kính tự động</a></li>
                        <li><a href="#danh-muc" class="hover:text-brand-accent transition">Cầu thang kính</a></li>
                        <li><a href="#danh-muc" class="hover:text-brand-accent transition">Kính ốp bếp & Phòng tắm kính</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dòng cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-brand-accent/60 inline-block">
                        Cửa Nhôm Xingfa
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="filterProductByKeyword('1 cánh')" class="hover:text-brand-accent transition">Cửa nhôm Xingfa 1 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('2 cánh')" class="hover:text-brand-accent transition">Cửa nhôm Xingfa 2 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('3 cánh')" class="hover:text-brand-accent transition">Cửa nhôm Xingfa 3 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('4 cánh')" class="hover:text-brand-accent transition">Cửa nhôm Xingfa 4 cánh</a></li>
                        <li><a href="#san-pham" onclick="filterProductByKeyword('xếp trượt')" class="hover:text-brand-accent transition">Cửa nhôm Xingfa 5 cánh / Xếp trượt</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-accent transition">Bảng báo giá cửa nhôm Xingfa</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh & Thời gian làm việc -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-brand-accent/60 inline-block">
                        Hỗ trợ khách hàng
                    </h4>
                    <ul class="space-y-2 text-xs mb-4">
                        <li><a href="#gioi-thieu" class="hover:text-brand-accent transition">Giới thiệu NT Window</a></li>
                        <li><a href="#cong-trinh" class="hover:text-brand-accent transition">Dự án đã thi công tại Đà Nẵng</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-accent transition">Tin tức & Tư vấn kỹ thuật</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-accent transition">Đăng ký khảo sát & báo giá</a></li>
                    </ul>
                    <div class="p-3 rounded-lg bg-white/10 text-xs">
                        <div class="font-bold text-brand-accent mb-1">Tư vấn kỹ thuật 24/7</div>
                        <div>Hotline / Zalo: <a href="tel:0982539678" class="text-white font-bold">0982.539.678</a></div>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-blue-200/80">
                <div>Copyright 2026 © Bản quyền thuộc về <strong class="text-white">NT Window</strong> (ntwindow.com)</div>
                <div>Địa chỉ: 183 Mạc Đăng Dung, Hòa Xuân, Đà Nẵng</div>
            </div>
        </div>
    </footer>

    <!-- =========================================================
         SECTION 14: CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         TƯƠNG THÍCH TỐT TRÊN CẢ MÁY TÍNH & ĐIỆN THOẠI, KHÔNG TRÀN VIỀN
    ========================================================== -->
    <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0982539678" target="_blank" rel="noopener" aria-label="Chat Zalo NT Window"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-black text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com/" target="_blank" rel="noopener" aria-label="Fanpage Facebook NT Window"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#145DBF] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition">
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white text-[#1877F2] text-xs flex items-center justify-center shrink-0"></i>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật có hiệu ứng nhịp sóng -->
        <a href="tel:0982539678" aria-label="Gọi Hotline 0982.539.678"
           class="hotline-pulse flex items-center gap-2 bg-brand-accent hover:bg-brand-accentDark text-white rounded-full shadow-xl px-3.5 py-2.5 sm:px-4 sm:py-2.5 transition">
            <i class="fa-solid fa-phone-volume text-sm animate-bounce"></i>
            <span class="text-xs sm:text-sm font-extrabold tracking-tight whitespace-nowrap">0982.539.678</span>
        </a>
    </div>

    <!-- =========================================================
         MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT (KHÔNG DÙNG ALERT)
    ========================================================== -->
    <div id="detailModal" class="fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button id="closeModalBtn" type="button" aria-label="Đóng" class="absolute top-3 right-3 z-10 w-8 h-8 rounded-full bg-slate-100 hover:bg-brand-navy hover:text-white text-slate-700 flex items-center justify-center transition">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modalBody" class="p-5 sm:p-6"></div>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT: XỬ LÝ ẢNH GOOGLE DRIVE, SLIDER, SẢN PHẨM, DỰ ÁN, BÀI VIẾT & FORM
    ========================================================== -->
    <script>
        /**
         * Hàm tạo URL ảnh nhúng trực tiếp từ Google Drive ID kèm chuỗi fallback an toàn
         * (Nếu ảnh bị giới hạn quyền xem hoặc lỗi mạng sẽ tự chuyển sang thumbnail rồi placeholder)
         */
        function getGdriveUrl(fileId) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
        }

        function attachGdriveFallback(imgEl, fileId, label) {
            imgEl.src = getGdriveUrl(fileId);
            imgEl.dataset.retry = '0';
            imgEl.onerror = function () {
                if (this.dataset.retry === '0') {
                    this.dataset.retry = '1';
                    this.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
                } else {
                    this.onerror = null;
                    this.src = `https://placehold.co/600x450/0A3D7A/FFFFFF?text=${encodeURIComponent(label || 'NT+Window')}`;
                }
            };
        }

        // Khởi tạo toàn bộ ảnh Google Drive tĩnh trên trang
        function initStaticGdriveImages() {
            document.querySelectorAll('img.gdrive-img').forEach(img => {
                const fileId = img.getAttribute('data-gdrive');
                const fallback = img.getAttribute('data-fallback') || 'NT Window';
                if (fileId) {
                    attachGdriveFallback(img, fileId, fallback);
                }
            });
        }

        /**
         * Danh sách 6 sản phẩm Cửa Nhôm Xingfa chính hãng kèm ảnh Google Drive thực tế,
         * giá bán, giá gốc và % giảm giá góc trên bên trái
         */
        const PRODUCTS = [
            {
                id: 1,
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                category: 'cua-di',
                gdriveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                originalPrice: 2300000,
                salePrice: 1950000,
                discount: 15,
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm nhập khẩu Quảng Đông, phụ kiện Kinlong đồng bộ, kính an toàn 6.38mm hoặc cường lực 8mm.'
            },
            {
                id: 2,
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                category: 'cua-di',
                gdriveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                originalPrice: 2400000,
                salePrice: 2050000,
                discount: 15,
                specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, ép góc CNC kín khít, gioăng EPDM chống ồn, khóa đa điểm chắc chắn.'
            },
            {
                id: 3,
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                category: 'cua-di',
                gdriveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                originalPrice: 2500000,
                salePrice: 2100000,
                discount: 16,
                specs: 'Thiết kế mở rộng tối đa không gian mặt tiền, thanh profile định hình sơn tĩnh điện ngoài trời bền màu.'
            },
            {
                id: 4,
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                category: 'cua-di',
                gdriveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                originalPrice: 2550000,
                salePrice: 2100000,
                discount: 18,
                specs: 'Lựa chọn hàng đầu cho cửa chính nhà phố & biệt thự Đà Nẵng, bản lề 3D chịu lực cao, kính cường lực 8mm.'
            },
            {
                id: 5,
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                category: 'xep-truot',
                gdriveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                originalPrice: 2700000,
                salePrice: 2250000,
                discount: 17,
                specs: 'Hệ nhôm xếp trượt 63 cao cấp (4-5-6 cánh), ray trượt chịu tải siêu êm, mở thông thoáng gần 100% khẩu độ.'
            },
            {
                id: 6,
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                category: 'cua-so',
                gdriveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                originalPrice: 2200000,
                salePrice: 1850000,
                discount: 16,
                specs: 'Hệ 55 dày 1.4mm, thanh định vị chống gió đập, mở thoáng ngay cả khi trời mưa mà không bị hắt nước.'
            }
        ];

        /**
         * Danh sách 6 dự án tiêu biểu tại Đà Nẵng kèm ảnh Google Drive
         */
        const PROJECTS = [
            {
                id: 1,
                title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                location: 'TP Đà Nẵng',
                scope: 'Thi công trọn gói hệ cửa nhôm Xingfa nhập khẩu và vách kính mặt dựng cách âm chuẩn khách sạn ven biển.',
                gdriveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ'
            },
            {
                id: 2,
                title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                location: 'Quảng Nam - Đà Nẵng',
                scope: 'Cung cấp & lắp đặt hệ cửa nhôm kính cao cấp, cửa đi xếp trượt sân vườn và phòng tắm kính cường lực.',
                gdriveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ'
            },
            {
                id: 3,
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                location: 'TP Đà Nẵng',
                scope: 'Gia công lắp đặt hệ thống cửa đi, cửa sổ nhôm Xingfa tem đỏ và lan can kính cường lực toàn tòa nhà.',
                gdriveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy'
            },
            {
                id: 4,
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                location: 'TP Đà Nẵng',
                scope: 'Hoàn thiện hạng mục cửa nhôm Xingfa cách âm phòng lưu trú, cửa kính tự động sảnh chính và vách tắm kính.',
                gdriveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64'
            },
            {
                id: 5,
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                location: 'TP Đà Nẵng',
                scope: 'Thi công đồng bộ cửa nhôm Xingfa cao cấp, vách kính hộp chống nắng hướng biển và cửa kính cường lực.',
                gdriveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt'
            },
            {
                id: 6,
                title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                location: 'Biển Mỹ Khê, TP Đà Nẵng',
                scope: 'Lắp đặt hệ nhôm kính chịu gió bão cấp cao, chống ăn mòn hơi muối biển, đảm bảo thẩm mỹ và độ bền lâu dài.',
                gdriveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc'
            }
        ];

        /**
         * Danh mục các bài viết tin tức hiển thị ngoài trang chủ
         */
        const ARTICLES = [
            {
                id: 1,
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
                date: '20/11/2026',
                excerpt: 'Tìm hiểu khả năng chống ăn mòn hơi muối, chịu gió bão và độ bền lớp sơn tĩnh điện của nhôm Xingfa nhập khẩu tại miền Trung.',
                gdriveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                content: 'Nhôm Xingfa nhập khẩu Quảng Đông được xử lý bề mặt và sơn tĩnh điện ngoài trời theo tiêu chuẩn quốc tế, kết hợp gioăng cao su EPDM kín khít và phụ kiện chống gỉ. Nhờ đó, cửa nhôm Xingfa hoàn toàn đáp ứng tốt điều kiện nắng nóng, mưa bão và hơi muối biển đặc trưng tại Đà Nẵng.'
            },
            {
                id: 2,
                title: 'Cách nhận biết cửa nhôm Xingfa nhập khẩu tem đỏ chính hãng 100%',
                date: '15/11/2026',
                excerpt: 'Hướng dẫn kiểm tra mã QR trên tem đỏ, ánh kim bên trong khoang nhôm và độ dày tiêu chuẩn 1.4mm – 2.0mm trước khi lắp đặt.',
                gdriveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                content: 'Nhôm Xingfa chính hãng có tem đỏ in sắc nét, quét mã QR truy xuất nguồn gốc rõ ràng, mặt cắt nhôm có các đường gân gia cường bên trong khoang trống cùng lớp mạ crom ánh kim chống oxy hóa. Khi chọn NT Window, khách hàng được kiểm tra mẫu góc thực tế trực tiếp trước khi ký hợp đồng.'
            },
            {
                id: 3,
                title: 'Nên chọn cửa nhôm Xingfa hay cửa nhựa lõi thép cho nhà phố?',
                date: '10/11/2026',
                excerpt: 'So sánh chi tiết độ bền kết cấu, thẩm mỹ, khả năng cách âm và chi phí đầu tư giữa cửa nhôm Xingfa và cửa nhựa lõi thép uPVC.',
                gdriveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                content: 'Cửa nhôm Xingfa nổi trội về độ cứng vững, khung viền thanh mảnh hiện đại và màu sắc sang trọng (xám ghi, đen, vân gỗ, trắng). Trong khi đó, cửa nhựa lõi thép uPVC có ưu thế cách âm tốt và giá thành kinh tế hơn cho các phòng ngủ hoặc công trình cần tối ưu ngân sách.'
            },
            {
                id: 4,
                title: 'Kinh nghiệm chọn kính cường lực phòng tắm & cầu thang an toàn',
                date: '05/11/2026',
                excerpt: 'Những lưu ý quan trọng về độ dày kính 10mm – 12mm, phụ kiện inox 304 chống gỉ sét giúp công trình bền đẹp trên 15 năm.',
                gdriveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                content: 'Đối với phòng tắm kính và cầu thang kính, nên ưu tiên kính cường lực độ dày 10mm đến 12mm đạt chuẩn tôi nhiệt an toàn, đi kèm bản lề, kẹp kính và tay nắm inox 304 chính hãng nhằm tránh ố vàng hay gỉ sét trong môi trường ẩm ướt.'
            }
        ];

        function formatVND(amount) {
            return amount.toLocaleString('vi-VN') + ' ₫';
        }

        // Render lưới sản phẩm (luôn giữ 2 cột trên điện thoại, không cắt chữ tên sản phẩm)
        function renderProducts(filter = 'all', searchKeyword = '') {
            const grid = document.getElementById('productGrid');
            if (!grid) return;

            // Cập nhật trạng thái nút lọc
            document.querySelectorAll('.prod-filter-btn').forEach(btn => {
                const isActive = btn.dataset.filter === filter && !searchKeyword;
                btn.className = isActive
                    ? 'prod-filter-btn px-3.5 py-1.5 rounded-full text-xs font-semibold bg-brand-navy text-white transition'
                    : 'prod-filter-btn px-3.5 py-1.5 rounded-full text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-light hover:text-brand-navy transition';
            });

            let list = PRODUCTS;
            if (filter !== 'all') {
                list = list.filter(p => p.category === filter);
            }
            if (searchKeyword) {
                const kw = searchKeyword.toLowerCase();
                list = list.filter(p => p.name.toLowerCase().includes(kw));
            }

            if (list.length === 0) {
                grid.innerHTML = `<div class="col-span-full text-center py-8 text-sm text-slate-500">Không tìm thấy sản phẩm phù hợp với từ khóa "${searchKeyword}". <button type="button" onclick="renderProducts('all')" class="text-brand-navy font-bold underline ml-1">Xem tất cả</button></div>`;
                return;
            }

            grid.innerHTML = list.map(product => `
                <article class="bg-white rounded-xl border border-slate-200/90 shadow-sm hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${product.id})">
                        <!-- Badge giảm giá % góc trên bên trái -->
                        <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded-md bg-brand-accent text-white text-[11px] sm:text-xs font-extrabold shadow">
                            -${product.discount}%
                        </span>
                        <img data-prod-id="${product.id}" alt="${product.name}" class="w-full h-full object-cover hover:scale-105 transition duration-500">
                    </div>

                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <h3 onclick="openProductModal(${product.id})" class="cursor-pointer text-xs sm:text-sm font-bold text-brand-navy hover:text-brand-accent leading-snug break-words transition">
                                ${product.name}
                            </h3>
                        </div>

                        <div class="space-y-2 pt-1">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-xs sm:text-base font-extrabold text-brand-accent">${formatVND(product.salePrice)}</span>
                                <span class="text-[10px] sm:text-xs text-slate-400 line-through">${formatVND(product.originalPrice)}</span>
                            </div>

                            <div class="grid grid-cols-2 gap-1.5">
                                <button type="button" onclick="openProductModal(${product.id})" class="py-1.5 px-1.5 rounded-lg border border-brand-navy text-brand-navy hover:bg-brand-light text-[11px] sm:text-xs font-semibold transition text-center">
                                    Chi tiết
                                </button>
                                <a href="#form-bao-gia" onclick="selectQuoteCategory('${product.name}')" class="py-1.5 px-1.5 rounded-lg bg-brand-navy hover:bg-brand-accent text-white text-[11px] sm:text-xs font-semibold transition text-center">
                                    Báo giá
                                </a>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');

            // Gắn ảnh Google Drive + fallback an toàn cho từng sản phẩm
            list.forEach(p => {
                const img = grid.querySelector(`img[data-prod-id="${p.id}"]`);
                if (img) attachGdriveFallback(img, p.gdriveId, p.name);
            });
        }

        function filterProductByKeyword(keyword) {
            renderProducts('all', keyword);
        }

        // Render 6 dự án Đà Nẵng
        function renderProjects() {
            const grid = document.getElementById('projectGrid');
            if (!grid) return;

            grid.innerHTML = PROJECTS.map(project => `
                <article onclick="openProjectModal(${project.id})" class="cursor-pointer group bg-white rounded-xl border border-slate-200/80 shadow-sm hover:shadow-md overflow-hidden transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img data-proj-id="${project.id}" alt="${project.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between gap-2">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-accent leading-snug uppercase transition break-words">
                            ${project.title}
                        </h3>
                        <p class="text-xs text-slate-600 line-clamp-2 leading-relaxed">
                            ${project.scope}
                        </p>
                        <div class="pt-1 flex items-center justify-between text-[11px] font-semibold text-brand-blue">
                            <span><i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>${project.location}</span>
                            <span class="group-hover:translate-x-0.5 transition">Xem chi tiết →</span>
                        </div>
                    </div>
                </article>
            `).join('');

            PROJECTS.forEach(proj => {
                const img = grid.querySelector(`img[data-proj-id="${proj.id}"]`);
                if (img) attachGdriveFallback(img, proj.gdriveId, proj.title);
            });
        }

        // Render danh mục các bài viết trang chủ
        function renderArticles() {
            const grid = document.getElementById('newsGrid');
            if (!grid) return;

            grid.innerHTML = ARTICLES.map(art => `
                <article onclick="openArticleModal(${art.id})" class="cursor-pointer group bg-white rounded-xl border border-slate-200/80 shadow-sm hover:shadow-md overflow-hidden transition flex flex-col">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img data-art-id="${art.id}" alt="${art.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between gap-2">
                        <div class="space-y-1.5">
                            <div class="text-[11px] text-slate-400 font-medium">
                                <i class="fa-regular fa-calendar mr-1 text-brand-accent"></i>${art.date}
                            </div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-accent leading-snug transition break-words">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed line-clamp-3">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="pt-1 text-xs font-semibold text-brand-blue group-hover:text-brand-accent">
                            Đọc tiếp →
                        </div>
                    </div>
                </article>
            `).join('');

            ARTICLES.forEach(art => {
                const img = grid.querySelector(`img[data-art-id="${art.id}"]`);
                if (img) attachGdriveFallback(img, art.gdriveId, 'Tin+Tuc+NT+Window');
            });
        }

        // Mở Modal chi tiết sản phẩm
        function openProductModal(id) {
            const p = PRODUCTS.find(item => item.id === id);
            if (!p) return;
            const modal = document.getElementById('detailModal');
            const body = document.getElementById('modalBody');

            body.innerHTML = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-center">
                    <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[4/3]">
                        <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-brand-accent text-white text-xs font-extrabold">-${p.discount}%</span>
                        <img id="modalDynamicImg" alt="${p.name}" class="w-full h-full object-cover">
                    </div>
                    <div class="space-y-3">
                        <div class="text-xs font-bold uppercase text-brand-accent">Cửa Nhôm Xingfa NT Window</div>
                        <h3 class="text-lg font-extrabold text-brand-navy leading-snug">${p.name}</h3>
                        <div class="flex items-baseline gap-2.5">
                            <span class="text-xl font-black text-brand-accent">${formatVND(p.salePrice)}/m²</span>
                            <span class="text-sm text-slate-400 line-through">${formatVND(p.originalPrice)}</span>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${p.specs}</p>
                        <div class="pt-2 flex flex-wrap gap-2.5">
                            <a href="#form-bao-gia" onclick="closeDetailModal(); selectQuoteCategory('${p.name}')" class="flex-1 py-2.5 px-4 rounded-lg bg-brand-navy hover:bg-brand-accent text-white text-xs sm:text-sm font-bold text-center transition">
                                Yêu cầu báo giá
                            </a>
                            <a href="tel:0982539678" class="py-2.5 px-4 rounded-lg border border-brand-navy text-brand-navy hover:bg-brand-light text-xs sm:text-sm font-bold text-center transition">
                                0982.539.678
                            </a>
                        </div>
                    </div>
                </div>
            `;
            attachGdriveFallback(document.getElementById('modalDynamicImg'), p.gdriveId, p.name);
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        // Mở Modal chi tiết dự án
        function openProjectModal(id) {
            const proj = PROJECTS.find(item => item.id === id);
            if (!proj) return;
            const modal = document.getElementById('detailModal');
            const body = document.getElementById('modalBody');

            body.innerHTML = `
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                        <img id="modalDynamicImg" alt="${proj.title}" class="w-full h-full object-cover">
                    </div>
                    <div class="space-y-2">
                        <div class="text-xs font-bold uppercase text-brand-accent">${proj.location}</div>
                        <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy">${proj.title}</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">${proj.scope}</p>
                        <div class="pt-2 flex items-center gap-3">
                            <a href="#form-bao-gia" onclick="closeDetailModal()" class="px-5 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-accent text-white text-xs sm:text-sm font-bold transition">
                                Tư vấn thi công tương tự
                            </a>
                        </div>
                    </div>
                </div>
            `;
            attachGdriveFallback(document.getElementById('modalDynamicImg'), proj.gdriveId, proj.title);
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        // Mở Modal đọc bài viết
        function openArticleModal(id) {
            const art = ARTICLES.find(item => item.id === id);
            if (!art) return;
            const modal = document.getElementById('detailModal');
            const body = document.getElementById('modalBody');

            body.innerHTML = `
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/9]">
                        <img id="modalDynamicImg" alt="${art.title}" class="w-full h-full object-cover">
                    </div>
                    <div class="text-xs text-slate-400 font-medium"><i class="fa-regular fa-calendar mr-1 text-brand-accent"></i>${art.date} • NT Window Đà Nẵng</div>
                    <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy leading-snug">${art.title}</h3>
                    <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
                    <div class="p-3.5 rounded-xl bg-brand-light text-xs text-brand-navy">
                        Cần tư vấn trực tiếp? Gọi ngay <strong>0982.539.678</strong> hoặc đến showroom <strong>183 Mạc Đăng Dung, Hòa Xuân, TP Đà Nẵng</strong>.
                    </div>
                </div>
            `;
            attachGdriveFallback(document.getElementById('modalDynamicImg'), art.gdriveId, art.title);
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Điền sẵn hạng mục vào Form Báo Giá khi người dùng nhấn từ sản phẩm / danh mục
        function selectQuoteCategory(label) {
            const noteInput = document.getElementById('qNote');
            const catSelect = document.getElementById('qCategory');
            if (catSelect) {
                for (let i = 0; i < catSelect.options.length; i++) {
                    if (catSelect.options[i].value.toLowerCase() === label.toLowerCase()) {
                        catSelect.selectedIndex = i;
                        return;
                    }
                }
            }
            if (noteInput) {
                noteInput.value = `Tôi cần báo giá chi tiết cho sản phẩm: ${label}`;
            }
        }

        // Khởi tạo Slider 2 Banner tự trượt chuyên nghiệp
        function initHeroSlider() {
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.slider-dot');
            const sliderContainer = document.getElementById('heroSlider');
            let currentIndex = 0;
            let autoTimer = null;

            function showSlide(index) {
                currentIndex = (index + slides.length) % slides.length;
                slides.forEach((s, i) => {
                    s.classList.toggle('active', i === currentIndex);
                });
                dots.forEach((d, i) => {
                    if (i === currentIndex) {
                        d.classList.add('w-6', 'bg-brand-accent');
                        d.classList.remove('w-2', 'bg-white/50');
                    } else {
                        d.classList.remove('w-6', 'bg-brand-accent');
                        d.classList.add('w-2', 'bg-white/50');
                    }
                });
            }

            function startAutoSlide() {
                stopAutoSlide();
                autoTimer = setInterval(() => showSlide(currentIndex + 1), 5000);
            }
            function stopAutoSlide() {
                if (autoTimer) clearInterval(autoTimer);
            }

            document.getElementById('prevSlideBtn').addEventListener('click', () => {
                showSlide(currentIndex - 1);
                startAutoSlide();
            });
            document.getElementById('nextSlideBtn').addEventListener('click', () => {
                showSlide(currentIndex + 1);
                startAutoSlide();
            });
            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    showSlide(parseInt(dot.dataset.index, 10));
                    startAutoSlide();
                });
            });

            // Hỗ trợ vuốt cảm ứng trên điện thoại
            let touchStartX = 0;
            sliderContainer.addEventListener('touchstart', e => {
                touchStartX = e.changedTouches[0].screenX;
                stopAutoSlide();
            }, { passive: true });
            sliderContainer.addEventListener('touchend', e => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    showSlide(diff > 0 ? currentIndex - 1 : currentIndex + 1);
                }
                startAutoSlide();
            }, { passive: true });

            sliderContainer.addEventListener('mouseenter', stopAutoSlide);
            sliderContainer.addEventListener('mouseleave', startAutoSlide);

            startAutoSlide();
        }

        // Khởi tạo Menu Mobile & Submenu + Form tìm kiếm + Form báo giá
        function initInteractions() {
            const mobileMenuBtn = document.getElementById('mobileMenuBtn');
            const closeMobileMenuBtn = document.getElementById('closeMobileMenuBtn');
            const mobileDrawer = document.getElementById('mobileDrawer');
            const mobileMenuOverlay = document.getElementById('mobileMenuOverlay');

            function openDrawer() {
                mobileDrawer.classList.remove('-translate-x-full');
                mobileMenuOverlay.classList.remove('hidden');
            }
            function closeDrawer() {
                mobileDrawer.classList.add('-translate-x-full');
                mobileMenuOverlay.classList.add('hidden');
            }

            mobileMenuBtn.addEventListener('click', openDrawer);
            closeMobileMenuBtn.addEventListener('click', closeDrawer);
            mobileMenuOverlay.addEventListener('click', closeDrawer);

            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', closeDrawer);
            });

            // Toggle submenu trên mobile
            document.querySelectorAll('.submenu-toggle').forEach(btn => {
                btn.addEventListener('click', () => {
                    const target = document.getElementById(btn.dataset.target);
                    if (!target) return;
                    target.classList.toggle('hidden');
                    const icon = btn.querySelector('i');
                    if (icon) icon.classList.toggle('rotate-180');
                });
            });

            // Nút Nhận báo giá trên header cuộn mượt xuống form báo giá
            document.getElementById('openQuoteQuickBtn').addEventListener('click', () => {
                document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
            });

            // Tìm kiếm sản phẩm trên Desktop & Mobile
            document.getElementById('searchForm').addEventListener('submit', e => {
                e.preventDefault();
                const kw = document.getElementById('searchInput').value.trim();
                renderProducts('all', kw);
                document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
            });
            document.getElementById('mobileSearchForm').addEventListener('submit', e => {
                e.preventDefault();
                const kw = document.getElementById('mobileSearchInput').value.trim();
                renderProducts('all', kw);
                closeDrawer();
                document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
            });

            // Đóng Modal khi nhấn nút X hoặc click ra nền tối
            document.getElementById('closeModalBtn').addEventListener('click', closeDetailModal);
            document.getElementById('detailModal').addEventListener('click', e => {
                if (e.target.id === 'detailModal') closeDetailModal();
            });

            // Xử lý Form yêu cầu báo giá (hiển thị hộp xác nhận ngay tại form, không dùng alert)
            document.getElementById('quoteRequestForm').addEventListener('submit', e => {
                e.preventDefault();
                const name = document.getElementById('qName').value.trim();
                const phone = document.getElementById('qPhone').value.trim();
                const category = document.getElementById('qCategory').value;

                const box = document.getElementById('quoteSuccessBox');
                const text = document.getElementById('quoteSuccessText');
                text.textContent = `Cảm ơn anh/chị ${name} (${phone}) đã đăng ký tư vấn hạng mục "${category}". Kỹ thuật viên NT Window sẽ liên hệ lại sớm nhất!`;
                box.classList.remove('hidden');
                e.target.reset();
            });
        }

        // Chạy toàn bộ khởi tạo khi tải trang xong
        window.addEventListener('DOMContentLoaded', () => {
            try {
                initStaticGdriveImages();
                renderProducts('all');
                renderProjects();
                renderArticles();
                initHeroSlider();
                initInteractions();
            } catch (err) {
                console.error('Lỗi khởi tạo giao diện NT Window:', err);
            }
        });
    </script>
</body>
</html>
