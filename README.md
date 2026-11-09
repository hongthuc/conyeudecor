<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CON YÊU DECOR - Trang Trí Thôi Nôi, Sinh Nhật & Phụ Kiện Đà Nẵng - Quảng Nam</title>
    <meta name="description" content="Con Yêu Decor (conyeudecor.com) chuyên trang trí thôi nôi, sinh nhật trọn gói, cung cấp set bóng trang trí, phụ kiện chibi, bảng thông tin cho bé tại Đà Nẵng - Quảng Nam. Hotline: 0866 480 868 - 0383 476 076.">
    <link rel="canonical" href="https://conyeudecor.com/">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://conyeudecor.com/">
    <meta property="og:site_name" content="CON YÊU DECOR - conyeudecor.com">
    <meta property="og:title" content="CON YÊU DECOR - Trang Trí Thôi Nôi & Phụ Kiện Sinh Nhật Đà Nẵng - Quảng Nam">
    <meta property="og:description" content="Dịch vụ trang trí thôi nôi, sinh nhật, sự kiện trọn gói & phụ kiện trang trí thiết kế riêng theo yêu cầu. Hotline: 0866 480 868 - 0383 476 076.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y">
    <meta property="og:image:alt" content="Logo Con Yêu Decor - conyeudecor.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CON YÊU DECOR - conyeudecor.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter & Quicksand chuẩn giao diện Mẹ & Bé / Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Quicksand:wght@600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#fff1f4',
                            100: '#ffe3e9',
                            200: '#ffc9d6',
                            300: '#ff9eb5',
                            400: '#ff668c',
                            500: '#f43f6e',
                            600: '#e11d53',
                            700: '#be1243',
                            800: '#9f123c',
                            900: '#881337',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Quicksand', 'Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch sang phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #fdf8f9;
            color: #2d3748;
            scroll-behavior: smooth;
        }

        /* Chuẩn khung 1500px của Flatsome trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 768px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 18px;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #ffe3e9;
            padding-bottom: 8px;
            gap: 10px;
            flex-wrap: wrap;
        }
        .section-title-main {
            font-family: 'Quicksand', 'Inter', sans-serif;
            font-weight: 700;
            color: #e11d53;
            position: relative;
            text-transform: uppercase;
            letter-spacing: 0.02em;
        }
        .section-title-main::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #e11d53;
            border-radius: 2px;
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ gãy dòng trong 1 tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 14px;
            list-style: none;
            margin: 0;
            padding: 6px 0;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            color: #ffffff;
            padding: 5px 8px;
            border-radius: 6px;
            transition: all 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            cursor: pointer;
            text-decoration: none;
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            background-color: rgba(255, 255, 255, 0.2);
            color: #fff;
        }

        /* Nhãn giảm giá chuẩn Flatsome ở góc trên bên trái */
        .flatsome-badge-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background: linear-gradient(135deg, #e11d53, #f43f6e);
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 9999px;
            box-shadow: 0 2px 6px rgba(225, 29, 83, 0.35);
            pointer-events: none;
        }

        /* Tên sản phẩm đầy đủ, không bị cắt chữ (...) và không tràn khung */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
            display: block;
            width: 100%;
        }

        /* Hiệu ứng thẻ sản phẩm Flatsome */
        .flatsome-product-box {
            background: #ffffff;
            border: 1px solid #fce7ec;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.22s ease, box-shadow 0.22s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .flatsome-product-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -5px rgba(225, 29, 83, 0.12);
            border-color: #ffc9d6;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 83, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(225, 29, 83, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 83, 0); }
        }
        .floating-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==========================================
         TOP BAR (Chuẩn Flatsome Top Bar gọn gàng)
    =========================================== -->
    <div class="bg-brand-50 border-b border-brand-100 text-slate-700 text-xs py-1.5">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 font-medium text-brand-700 truncate max-w-full">
                <i class="fa-solid fa-wand-magic-sparkles text-brand-500"></i>
                <span class="truncate">CON YÊU DECOR - Trang Trí Thôi Nôi, Sinh Nhật & Phụ Kiện Tiệc Đà Nẵng - Quảng Nam</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-xs text-slate-600">
                <span><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Khu vực: Đà Nẵng - Quảng Nam</span>
                <span><i class="fa-solid fa-globe text-brand-600 mr-1"></i>conyeudecor.com</span>
                <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="text-brand-600 hover:underline font-medium">
                    <i class="fa-brands fa-facebook mr-1"></i>Fanpage Con Yêu Decor
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER (Gọn nhẹ, Logo chỉnh nhỏ gọn, KHÔNG để nút gọi ngay tránh tràn viền)
    =========================================== -->
    <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-brand-100">
        <!-- Header Main -->
        <div class="flatsome-container py-2.5">
            <div class="flex items-center justify-between gap-2 md:gap-6">
                
                <!-- Nút mở Menu danh mục trên điện thoại -->
                <button type="button" onclick="toggleMobileDrawer()" class="lg:hidden flex items-center justify-center w-9 h-9 rounded-lg bg-brand-50 text-brand-600 border border-brand-200 shrink-0" aria-label="Menu danh mục">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo thu nhỏ gọn gàng + Tên thương hiệu -->
                <a href="#top" onclick="filterByCategory('all')" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 md:w-12 md:h-12 rounded-full overflow-hidden border-2 border-brand-300 shadow-sm shrink-0 bg-brand-50 flex items-center justify-center">
                        <img src="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y"
                             onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y&sz=w400';}else{this.onerror=null;this.src='https://placehold.co/120x120/ffe3e9/e11d53?text=CYD';}"
                             alt="Logo Con Yêu Decor"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="leading-tight">
                        <span class="block font-display font-bold text-base md:text-xl text-brand-600 tracking-tight">CON YÊU DECOR</span>
                        <span class="block text-[10px] md:text-xs text-slate-500 font-medium">conyeudecor.com</span>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-auto">
                    <form onsubmit="handleSearch(event)" class="w-full flex items-center bg-brand-50/60 border border-brand-200 rounded-full overflow-hidden focus-within:border-brand-500 focus-within:bg-white transition">
                        <input id="desktopSearchInput" type="text" placeholder="Tìm set bóng thôi nôi, chibi bé, bảng thông tin, phụ kiện sinh nhật..." class="w-full px-4 py-2 text-xs md:text-sm bg-transparent focus:outline-none text-slate-700">
                        <button type="submit" class="px-4 py-2 bg-brand-600 hover:bg-brand-700 text-white text-xs md:text-sm font-semibold shrink-0 transition">
                            <i class="fa-solid fa-magnifying-glass mr-1"></i>Tìm
                        </button>
                    </form>
                </div>

                <!-- Các nút tiện ích gọn nhẹ bên phải (Không có nút gọi ngay trên header) -->
                <div class="flex items-center gap-2 shrink-0">
                    <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-brand-50 hover:bg-brand-100 text-brand-700 border border-brand-200 text-xs font-semibold transition">
                        <i class="fa-regular fa-pen-to-square"></i>
                        <span>Nhận Báo Giá</span>
                    </a>
                    <button type="button" onclick="openCartModal()" class="relative inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full bg-brand-600 hover:bg-brand-700 text-white text-xs font-semibold transition">
                        <i class="fa-solid fa-bag-shopping"></i>
                        <span class="hidden sm:inline">Giỏ hàng</span>
                        <span id="cartCountBadge" class="inline-flex items-center justify-center min-w-[18px] h-[18px] px-1 rounded-full bg-white text-brand-700 font-bold text-[11px]">0</span>
                    </button>
                </div>
            </div>

            <!-- Thanh tìm kiếm gọn trên Điện thoại -->
            <div class="mt-2 md:hidden">
                <form onsubmit="handleMobileSearch(event)" class="w-full flex items-center bg-brand-50/70 border border-brand-200 rounded-full overflow-hidden">
                    <input id="mobileSearchInput" type="text" placeholder="Tìm set trang trí thôi nôi, phụ kiện sinh nhật..." class="w-full px-3.5 py-1.5 text-xs bg-transparent focus:outline-none text-slate-700">
                    <button type="submit" class="px-3.5 py-1.5 bg-brand-600 text-white text-xs font-semibold shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>
        </div>

        <!-- Thanh Danh Mục Header trên Máy Tính (Header Bottom chuẩn Flatsome)
             Chữ nhỏ gọn, viết liền trên 1 hàng hoặc tự xuống hàng 2, tuyệt đối không gãy chữ trong từng tên danh mục -->
        <nav class="hidden lg:block bg-gradient-to-r from-brand-600 via-brand-500 to-brand-600 shadow-inner">
            <div class="flatsome-container">
                <ul class="desktop-nav-list">
                    <li><a href="#top" onclick="filterByCategory('all')" class="desktop-nav-item active"><i class="fa-solid fa-house text-[11px]"></i>Trang chủ</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Set bóng trang trí')" class="desktop-nav-item">Set bóng trang trí</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc cho bé')" class="desktop-nav-item">Trang trí tiệc cho bé</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Phụ kiện thôi nôi')" class="desktop-nav-item">Phụ kiện thôi nôi</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Sản phẩm thiết kế riêng')" class="desktop-nav-item">Sản phẩm thiết kế riêng</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Tất cả phụ kiện')" class="desktop-nav-item">Tất cả phụ kiện</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc người lớn')" class="desktop-nav-item">Trang trí tiệc người lớn</a></li>
                    <li><a href="#san-pham-all" onclick="filterByCategory('Cưới hỏi, tình yêu')" class="desktop-nav-item">Cưới hỏi, tình yêu</a></li>
                    <li><a href="#dich-vu-tron-goi" class="desktop-nav-item">Dịch vụ trọn gói</a></li>
                    <li><a href="#form-bao-gia" class="desktop-nav-item">Yêu cầu & Báo giá</a></li>
                    <li><a href="#tin-tuc-trang-chu" class="desktop-nav-item">Tin tức</a></li>
                    <li><a href="#lien-he-ban-do" class="desktop-nav-item">Liên hệ</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ==========================================
         MENU DRAWER TRÊN ĐIỆN THOẠI (Chuẩn Off-Canvas Flatsome)
    =========================================== -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/50 z-50 hidden transition-opacity" onclick="toggleMobileDrawer()"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[82vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="p-3.5 bg-brand-600 text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <img src="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y"
                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y&sz=w200';}"
                     alt="Logo" class="w-8 h-8 rounded-full bg-white object-cover">
                <span class="font-display font-bold text-sm">DANH MỤC CON YÊU DECOR</span>
            </div>
            <button type="button" onclick="toggleMobileDrawer()" class="w-7 h-7 rounded-full bg-white/20 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark text-sm"></i>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-brand-100 text-xs font-semibold text-slate-700">
            <a href="#top" onclick="filterByCategory('all'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 text-brand-600">
                <span><i class="fa-solid fa-house mr-2"></i>Trang chủ</span>
                <i class="fa-solid fa-chevron-right text-[10px]"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Set bóng trang trí'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-wand-magic-sparkles text-brand-500 mr-2"></i>Set bóng trang trí (Bé trai / Bé gái)</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc cho bé'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-cake-candles text-brand-500 mr-2"></i>Trang trí tiệc cho bé trọn gói</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Phụ kiện thôi nôi'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-baby text-brand-500 mr-2"></i>Phụ kiện thôi nôi cho bé</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Sản phẩm thiết kế riêng'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-id-card text-brand-500 mr-2"></i>Sản phẩm thiết kế riêng (Chibi, Bảng tên)</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Tất cả phụ kiện'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-gift text-brand-500 mr-2"></i>Tất cả phụ kiện sinh nhật</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc người lớn'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-champagne-glasses text-brand-500 mr-2"></i>Trang trí tiệc người lớn & Sự kiện</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#san-pham-all" onclick="filterByCategory('Cưới hỏi, tình yêu'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-heart text-brand-500 mr-2"></i>Phụ kiện cưới hỏi, phòng tân hôn</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50 text-brand-700">
                <span><i class="fa-solid fa-file-signature text-brand-600 mr-2"></i>Form Yêu Cầu & Nhận Báo Giá</span>
                <i class="fa-solid fa-chevron-right text-[10px]"></i>
            </a>
            <a href="#tin-tuc-trang-chu" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-regular fa-newspaper text-brand-500 mr-2"></i>Chuyên mục bài viết & Kinh nghiệm</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#lien-he-ban-do" onclick="toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50">
                <span><i class="fa-solid fa-map-location-dot text-brand-500 mr-2"></i>Bản đồ & Fanpage Liên hệ</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
        </div>
        <div class="p-3.5 bg-brand-50 border-t border-brand-100 text-xs text-slate-600 space-y-1">
            <div class="font-bold text-brand-700">HOTLINE HỖ TRỢ 24/7:</div>
            <div><i class="fa-solid fa-phone text-brand-600 mr-1.5"></i>0866 480 868 - 0383 476 076</div>
            <div><i class="fa-solid fa-location-dot text-brand-600 mr-1.5"></i>Đà Nẵng - Quảng Nam</div>
        </div>
    </aside>

    <!-- ==========================================
         MAIN CONTENT (Chuẩn cấu trúc Section UX Builder Flatsome)
    =========================================== -->
    <main id="top">

        <!-- 1. BANNER SLIDER TỰ TRƯỢT CHUYÊN NGHIỆP (2 SLIDES KÍCH THƯỚC BẰNG NHAU)
                - Thiết kế banner Máy tính (Desktop) và Điện thoại (Mobile) KHÁC NHAU hoàn toàn.
                - Chữ bên trong ảnh được thu nhỏ gọn gàng, nằm trọn 100% bên trong khung banner, không tràn viền. -->
        <section class="py-3 md:py-4">
            <div class="flatsome-container">
                <div class="relative rounded-2xl overflow-hidden shadow-md border border-brand-200 bg-brand-50">

                    <!-- ================= SLIDE 1 ================= -->
                    <div id="bannerSlide0" class="banner-slide block transition-opacity duration-500">
                        
                        <!-- BANNER 1 - GIAO DIỆN MÁY TÍNH (Chỉ hiện trên màn hình md trở lên, chiều cao cố định 380px) -->
                        <div class="hidden md:grid md:grid-cols-12 items-center h-[380px] bg-gradient-to-r from-[#fff0f3] via-[#ffe4ec] to-[#ffd5e2] px-10 lg:px-14 relative overflow-hidden">
                            <div class="col-span-7 pr-6 z-10">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/90 text-brand-600 text-xs font-bold mb-2.5 shadow-sm">
                                    <span>CONYEUDECOR.COM • ĐÀ NẴNG - QUẢNG NAM</span>
                                </div>
                                <h1 class="font-display font-bold text-2xl lg:text-3xl text-brand-800 leading-snug mb-2">
                                    DỊCH VỤ TRANG TRÍ THÔI NÔI & SINH NHẬT TRỌN GÓI CHO BÉ YÊU
                                </h1>
                                <p class="text-slate-700 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                                    Thiết kế backdrop 3D theo chủ đề riêng, cổng bong bóng nghệ thuật, bàn gallery lung linh, tặng kèm hình Chibi & bảng thông tin bé. Thi công tận nơi tại nhà, nhà hàng khu vực Đà Nẵng - Quảng Nam.
                                </p>
                                <div class="flex flex-wrap items-center gap-3 mb-4 text-xs font-semibold text-brand-800">
                                    <span class="bg-white/85 px-3 py-1.5 rounded-lg border border-brand-200"><i class="fa-solid fa-phone-volume text-brand-600 mr-1"></i>0866 480 868 - 0383 476 076</span>
                                    <span class="bg-white/85 px-3 py-1.5 rounded-lg border border-brand-200"><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i>Đà Nẵng - Quảng Nam</span>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#form-bao-gia" class="px-4 py-2 rounded-full bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold shadow transition">
                                        Nhận Báo Giá Trọn Gói
                                    </a>
                                    <a href="#san-pham-all" class="px-4 py-2 rounded-full bg-white hover:bg-brand-50 text-brand-700 border border-brand-300 text-xs font-bold transition">
                                        Xem Mẫu Thực Tế
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 grid grid-cols-2 gap-3 z-10">
                                <div class="rounded-xl overflow-hidden border-4 border-white shadow-md h-40">
                                    <img src="https://lh3.googleusercontent.com/d/1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad&sz=w800';}"
                                         alt="Mẫu trang trí thôi nôi Con Yêu Decor 1" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-xl overflow-hidden border-4 border-white shadow-md h-40">
                                    <img src="https://lh3.googleusercontent.com/d/1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY&sz=w800';}"
                                         alt="Mẫu trang trí thôi nôi Con Yêu Decor 2" class="w-full h-full object-cover">
                                </div>
                                <div class="col-span-2 rounded-xl overflow-hidden border-4 border-white shadow-md h-36">
                                    <img src="https://lh3.googleusercontent.com/d/1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m&sz=w800';}"
                                         alt="Mẫu trang trí sinh nhật Con Yêu Decor 3" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 1 - GIAO DIỆN ĐIỆN THOẠI (Thiết kế riêng biệt, chiều cao cố định 290px, chữ nhỏ gọn nằm hoàn toàn trong ảnh) -->
                        <div class="block md:hidden h-[290px] bg-gradient-to-b from-[#fff0f4] via-[#ffe2eb] to-[#ffd6e4] p-3.5 flex flex-col justify-between relative overflow-hidden">
                            <div class="text-center px-2">
                                <span class="inline-block px-2.5 py-0.5 rounded-full bg-white text-brand-600 text-[10px] font-bold border border-brand-200 mb-1">
                                    CON YÊU DECOR • ĐÀ NẴNG - QUẢNG NAM
                                </span>
                                <h2 class="font-display font-bold text-sm text-brand-800 leading-tight mb-1">
                                    TRANG TRÍ THÔI NÔI & SINH NHẬT TRỌN GÓI
                                </h2>
                                <p class="text-[11px] text-slate-700 leading-snug">
                                    Thiết kế theo chủ đề riêng • Tặng Chibi & Bảng thông tin bé • SĐT: 0866 480 868 - 0383 476 076
                                </p>
                            </div>
                            <div class="grid grid-cols-3 gap-2 my-1.5 px-1">
                                <div class="h-24 rounded-lg overflow-hidden border-2 border-white shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad&sz=w600';}"
                                         alt="Trang trí thôi nôi 1" class="w-full h-full object-cover">
                                </div>
                                <div class="h-24 rounded-lg overflow-hidden border-2 border-white shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY&sz=w600';}"
                                         alt="Trang trí thôi nôi 2" class="w-full h-full object-cover">
                                </div>
                                <div class="h-24 rounded-lg overflow-hidden border-2 border-white shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m&sz=w600';}"
                                         alt="Trang trí thôi nôi 3" class="w-full h-full object-cover">
                                </div>
                            </div>
                            <div class="flex items-center justify-center gap-2 pb-1">
                                <a href="#form-bao-gia" class="px-3 py-1 rounded-full bg-brand-600 text-white text-[11px] font-bold">
                                    Nhận Báo Giá Ngay
                                </a>
                                <a href="#san-pham-all" class="px-3 py-1 rounded-full bg-white text-brand-700 border border-brand-300 text-[11px] font-bold">
                                    Xem Set Trang Trí
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- ================= SLIDE 2 ================= -->
                    <div id="bannerSlide1" class="banner-slide hidden transition-opacity duration-500">
                        
                        <!-- BANNER 2 - GIAO DIỆN MÁY TÍNH (Cùng kích thước 380px với Slide 1) -->
                        <div class="hidden md:grid md:grid-cols-12 items-center h-[380px] bg-gradient-to-r from-[#fff5f0] via-[#ffe8df] to-[#ffd9cc] px-10 lg:px-14 relative overflow-hidden">
                            <div class="col-span-7 pr-6 z-10">
                                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/90 text-brand-600 text-xs font-bold mb-2.5 shadow-sm">
                                    <span>PHỤ KIỆN SINH NHẬT & THIẾT KẾ CHIBI THEO YÊU CẦU</span>
                                </div>
                                <h2 class="font-display font-bold text-2xl lg:text-3xl text-brand-800 leading-snug mb-2">
                                    SET BÓNG TỰ TRANG TRÍ, CHIBI BÉ, BẢNG THÔNG TIN & KHUNG 12 THÁNG
                                </h2>
                                <p class="text-slate-700 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                                    Cung cấp đầy đủ set bóng sinh nhật cho bé trai, bé gái, người lớn, phòng cưới; in phông bạt, bảng tên, cây welcome, khung ảnh 12 tháng sắc nét. Giao hàng nhanh chóng tại Đà Nẵng - Quảng Nam và toàn quốc.
                                </p>
                                <div class="flex flex-wrap items-center gap-3 mb-4 text-xs font-semibold text-brand-800">
                                    <span class="bg-white/85 px-3 py-1.5 rounded-lg border border-brand-200"><i class="fa-solid fa-gift text-brand-600 mr-1"></i>Tặng kèm bơm tay & keo dán bóng</span>
                                    <span class="bg-white/85 px-3 py-1.5 rounded-lg border border-brand-200"><i class="fa-solid fa-phone-volume text-brand-600 mr-1"></i>0866 480 868 - 0383 476 076</span>
                                </div>
                                <div class="flex items-center gap-3">
                                    <a href="#san-pham-thiet-ke" class="px-4 py-2 rounded-full bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold shadow transition">
                                        Đặt Làm Chibi & Phụ Kiện
                                    </a>
                                    <a href="#form-bao-gia" class="px-4 py-2 rounded-full bg-white hover:bg-brand-50 text-brand-700 border border-brand-300 text-xs font-bold transition">
                                        Tư Vấn Chọn Set
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 grid grid-cols-2 gap-3 z-10">
                                <div class="rounded-xl overflow-hidden border-4 border-white shadow-md h-40">
                                    <img src="https://lh3.googleusercontent.com/d/13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ&sz=w800';}"
                                         alt="Set phụ kiện sinh nhật Con Yêu Decor 4" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-xl overflow-hidden border-4 border-white shadow-md h-40">
                                    <img src="https://lh3.googleusercontent.com/d/1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH&sz=w800';}"
                                         alt="Set phụ kiện sinh nhật Con Yêu Decor 5" class="w-full h-full object-cover">
                                </div>
                                <div class="col-span-2 rounded-xl overflow-hidden border-4 border-white shadow-md h-36">
                                    <img src="https://lh3.googleusercontent.com/d/1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M&sz=w800';}"
                                         alt="Set phụ kiện sinh nhật Con Yêu Decor 6" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 - GIAO DIỆN ĐIỆN THOẠI (Cùng chiều cao 290px với Slide 1, thiết kế riêng cho điện thoại) -->
                        <div class="block md:hidden h-[290px] bg-gradient-to-b from-[#fff5f0] via-[#ffe6dc] to-[#ffd8c9] p-3.5 flex flex-col justify-between relative overflow-hidden">
                            <div class="text-center px-2">
                                <span class="inline-block px-2.5 py-0.5 rounded-full bg-white text-brand-600 text-[10px] font-bold border border-brand-200 mb-1">
                                    SET PHỤ KIỆN & IN CHIBI THEO YÊU CẦU
                                </span>
                                <h2 class="font-display font-bold text-sm text-brand-800 leading-tight mb-1">
                                    SET BÓNG SINH NHẬT • BẢNG TÊN • KHUNG 12 THÁNG
                                </h2>
                                <p class="text-[11px] text-slate-700 leading-snug">
                                    Đầy đủ phụ kiện tự trang trí tại nhà • Giao nhanh Đà Nẵng - Quảng Nam • 0866 480 868
                                </p>
                            </div>
                            <div class="grid grid-cols-3 gap-2 my-1.5 px-1">
                                <div class="h-24 rounded-lg overflow-hidden border-2 border-white shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ&sz=w600';}"
                                         alt="Phụ kiện thôi nôi 4" class="w-full h-full object-cover">
                                </div>
                                <div class="h-24 rounded-lg overflow-hidden border-2 border-white shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH&sz=w600';}"
                                         alt="Phụ kiện thôi nôi 5" class="w-full h-full object-cover">
                                </div>
                                <div class="h-24 rounded-lg overflow-hidden border-2 border-white shadow-sm">
                                    <img src="https://lh3.googleusercontent.com/d/1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M&sz=w600';}"
                                         alt="Phụ kiện thôi nôi 6" class="w-full h-full object-cover">
                                </div>
                            </div>
                            <div class="flex items-center justify-center gap-2 pb-1">
                                <a href="#san-pham-thiet-ke" class="px-3 py-1 rounded-full bg-brand-600 text-white text-[11px] font-bold">
                                    Xem Phụ Kiện Lê & Set
                                </a>
                                <a href="#form-bao-gia" class="px-3 py-1 rounded-full bg-white text-brand-700 border border-brand-300 text-[11px] font-bold">
                                    Tư Vấn Miễn Phí
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Nút điều hướng Slider trái / phải -->
                    <button type="button" onclick="prevBannerSlide()" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-white/80 hover:bg-white text-brand-700 shadow flex items-center justify-center z-20" aria-label="Slide trước">
                        <i class="fa-solid fa-chevron-left text-xs"></i>
                    </button>
                    <button type="button" onclick="nextBannerSlide()" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-white/80 hover:bg-white text-brand-700 shadow flex items-center justify-center z-20" aria-label="Slide tiếp">
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>

                    <!-- Chấm tròn chỉ báo Slide -->
                    <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                        <button type="button" id="sliderDot0" onclick="goToBannerSlide(0)" class="w-5 h-2 rounded-full bg-brand-600 transition-all" aria-label="Slide 1"></button>
                        <button type="button" id="sliderDot1" onclick="goToBannerSlide(1)" class="w-2 h-2 rounded-full bg-brand-300 transition-all" aria-label="Slide 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- 2. DANH MỤC SẢN PHẨM TRANG CHỦ (Chuẩn Product Categories UX Builder Flatsome)
                - Thiết kế đẹp trên cả máy tính và điện thoại, chữ danh mục ở trang chủ nhỏ gọn -->
        <section class="py-4">
            <div class="flatsome-container">
                <div class="bg-white rounded-2xl p-4 md:p-5 border border-brand-100 shadow-sm">
                    <div class="section-title-container">
                        <div class="section-title-normal">
                            <h2 class="section-title-main text-sm md:text-base">DANH MỤC SẢN PHẨM & DỊCH VỤ</h2>
                            <span class="text-xs text-slate-500">Chọn danh mục để lọc nhanh sản phẩm</span>
                        </div>
                    </div>

                    <!-- Chia 4 cột trên điện thoại, 8 cột trên máy tính, chữ danh mục nhỏ gọn -->
                    <div class="grid grid-cols-4 lg:grid-cols-8 gap-2.5 md:gap-4 pt-1">
                        <!-- Danh mục 1 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Set bóng trang trí')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad&sz=w300';}"
                                     alt="Set bóng trang trí" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Set bóng trang trí</span>
                        </a>

                        <!-- Danh mục 2 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc cho bé')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY&sz=w300';}"
                                     alt="Trang trí tiệc cho bé" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Trang trí tiệc cho bé</span>
                        </a>

                        <!-- Danh mục 3 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Phụ kiện thôi nôi')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m&sz=w300';}"
                                     alt="Phụ kiện thôi nôi" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Phụ kiện thôi nôi</span>
                        </a>

                        <!-- Danh mục 4 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Sản phẩm thiết kế riêng')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ&sz=w300';}"
                                     alt="Thiết kế Chibi & Bảng tên" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Chibi & Bảng thông tin</span>
                        </a>

                        <!-- Danh mục 5 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Tất cả phụ kiện')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH&sz=w300';}"
                                     alt="Tất cả phụ kiện" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Tất cả phụ kiện</span>
                        </a>

                        <!-- Danh mục 6 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc người lớn')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M&sz=w300';}"
                                     alt="Trang trí người lớn" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Tiệc người lớn</span>
                        </a>

                        <!-- Danh mục 7 -->
                        <a href="#san-pham-all" onclick="filterByCategory('Cưới hỏi, tình yêu')" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1gpru4TGUZ6CJfeB16mH0t8_pnJczuVRb"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1gpru4TGUZ6CJfeB16mH0t8_pnJczuVRb&sz=w300';}"
                                     alt="Cưới hỏi tình yêu" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Cưới hỏi, tình yêu</span>
                        </a>

                        <!-- Danh mục 8 -->
                        <a href="#dich-vu-tron-goi" class="group flex flex-col items-center text-center p-2 rounded-xl hover:bg-brand-50 transition">
                            <div class="w-14 h-14 md:w-16 md:h-16 rounded-full overflow-hidden border-2 border-brand-200 group-hover:border-brand-500 shadow-sm mb-1.5">
                                <img src="https://lh3.googleusercontent.com/d/1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN"
                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN&sz=w300';}"
                                     alt="Dịch vụ trọn gói" class="w-full h-full object-cover group-hover:scale-105 transition">
                            </div>
                            <span class="text-[11px] md:text-xs font-semibold text-slate-700 group-hover:text-brand-600 leading-tight">Dịch vụ trọn gói</span>
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- 3. KHU VỰC LỌC NHANH & TẤT CẢ SẢN PHẨM THỰC TẾ TRANG CHỦ
                - Chia 2 cột trên điện thoại (grid-cols-2), 3-4 cột trên máy tính.
                - Tên sản phẩm hiển thị đầy đủ không cắt chữ, không tràn viền.
                - Chỉ có duy nhất nhãn % giảm giá chuẩn Flatsome ở góc trên bên trái, không có nhãn dán dư thừa. -->
        <section id="san-pham-all" class="py-4">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 id="activeCategoryHeading" class="section-title-main text-sm md:text-lg">
                            SẢN PHẨM & MẪU TRANG TRÍ THỰC TẾ NỔI BẬT
                        </h2>
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button type="button" onclick="filterByCategory('all')" class="cat-pill px-2.5 py-1 rounded-full text-xs font-semibold bg-brand-600 text-white">Tất cả (9 mẫu thực tế)</button>
                            <button type="button" onclick="filterByCategory('Trang trí tiệc cho bé')" class="cat-pill px-2.5 py-1 rounded-full text-xs font-semibold bg-white border border-brand-200 text-slate-700 hover:bg-brand-50">Trang trí thôi nôi & sinh nhật bé</button>
                            <button type="button" onclick="filterByCategory('Set bóng trang trí')" class="cat-pill px-2.5 py-1 rounded-full text-xs font-semibold bg-white border border-brand-200 text-slate-700 hover:bg-brand-50">Set bóng trang trí</button>
                            <button type="button" onclick="filterByCategory('Sản phẩm thiết kế riêng')" class="cat-pill px-2.5 py-1 rounded-full text-xs font-semibold bg-white border border-brand-200 text-slate-700 hover:bg-brand-50">Thiết kế riêng & Phụ kiện</button>
                        </div>
                    </div>
                </div>

                <!-- Grid Sản Phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên tablet, 4 cột trên màn hình 1500px -->
                <div id="mainProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-5">
                    <!-- Được render tự động từ mảng 9 sản phẩm thực tế Google Drive bên dưới -->
                </div>
            </div>
        </section>

        <!-- 4. SECTION CHUYÊN BIỆT: SET BÓNG TRANG TRÍ & PHỤ KIỆN THÔI NÔI (Chuẩn bố cục Ruby Phụ Kiện Sinh Nhật) -->
        <section id="san-pham-thiet-ke" class="py-4">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm md:text-lg">
                            SẢN PHẨM THIẾT KẾ RIÊNG & PHỤ KIỆN SINH NHẬT BÁN CHẠY
                        </h2>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-brand-600 hover:underline">
                            Đặt thiết kế theo tên bé <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>
                </div>

                <!-- Grid 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div id="accessoryProductGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-5">
                    <!-- Được render từ danh sách phụ kiện chuẩn mẫu Ruby Shop kết hợp ảnh thực tế -->
                </div>
            </div>
        </section>

        <!-- 5. SECTION DỊCH VỤ TRANG TRÍ TRỌN GÓI ĐÀ NẴNG - QUẢNG NAM -->
        <section id="dich-vu-tron-goi" class="py-5">
            <div class="flatsome-container">
                <div class="bg-white rounded-2xl p-4 md:p-6 border border-brand-100 shadow-sm">
                    <div class="section-title-container">
                        <div class="section-title-normal">
                            <h2 class="section-title-main text-sm md:text-lg">
                                DỊCH VỤ TRANG TRÍ TRỌN GÓI TẠI ĐÀ NẴNG - QUẢNG NAM
                            </h2>
                            <span class="text-xs text-slate-500">Hotline: 0866 480 868 - 0383 476 076</span>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                        <div class="rounded-xl border border-brand-100 bg-brand-50/40 p-4 flex flex-col justify-between">
                            <div>
                                <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
                                    <i class="fa-solid fa-baby"></i>
                                </div>
                                <h3 class="font-bold text-sm md:text-base text-slate-800 mb-1.5">Trang Trí Thôi Nôi & Sinh Nhật Cho Bé</h3>
                                <p class="text-xs text-slate-600 leading-relaxed mb-3">
                                    Lên ý tưởng và thiết kế demo 3D theo tuổi bé (Bé trai, Bé gái), thi công phông cứng ফোম/bạt khung tròn, line bóng nghệ thuật, bục đôn gallery, chibi và bảng thông tin bé.
                                </p>
                            </div>
                            <a href="#form-bao-gia" onclick="prefillService('Trang trí thôi nôi - sinh nhật trọn gói cho bé')" class="inline-flex items-center text-xs font-bold text-brand-600 hover:underline">
                                Đăng ký báo giá <i class="fa-solid fa-chevron-right ml-1 text-[10px]"></i>
                            </a>
                        </div>

                        <div class="rounded-xl border border-brand-100 bg-brand-50/40 p-4 flex flex-col justify-between">
                            <div>
                                <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
                                    <i class="fa-solid fa-champagne-glasses"></i>
                                </div>
                                <h3 class="font-bold text-sm md:text-base text-slate-800 mb-1.5">Trang Trí Sinh Nhật Người Lớn & Sự Kiện</h3>
                                <p class="text-xs text-slate-600 leading-relaxed mb-3">
                                    Trang trí sinh nhật người lớn phong cách sang trọng, lung linh tại nhà hàng, khách sạn, resort; trang trí khai trương cửa hàng, tiệc kỷ niệm, Year End Party.
                                </p>
                            </div>
                            <a href="#form-bao-gia" onclick="prefillService('Trang trí sinh nhật người lớn / Khai trương')" class="inline-flex items-center text-xs font-bold text-brand-600 hover:underline">
                                Đăng ký báo giá <i class="fa-solid fa-chevron-right ml-1 text-[10px]"></i>
                            </a>
                        </div>

                        <div class="rounded-xl border border-brand-100 bg-brand-50/40 p-4 flex flex-col justify-between">
                            <div>
                                <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
                                    <i class="fa-solid fa-heart"></i>
                                </div>
                                <h3 class="font-bold text-sm md:text-base text-slate-800 mb-1.5">Trang Trí Phòng Cưới & Cầu Hôn Lãng Mạn</h3>
                                <p class="text-xs text-slate-600 leading-relaxed mb-3">
                                    Set up phòng tân hôn, bóng bay trần, chữ Happy Wedding, nến điện tử Pillar Led, hoa tươi và backdrop đám cưới ấm cúng, ngọt ngào.
                                </p>
                            </div>
                            <a href="#form-bao-gia" onclick="prefillService('Trang trí phòng cưới / Cầu hôn lãng mạn')" class="inline-flex items-center text-xs font-bold text-brand-600 hover:underline">
                                Đăng ký báo giá <i class="fa-solid fa-chevron-right ml-1 text-[10px]"></i>
                            </a>
                        </div>

                        <div class="rounded-xl border border-brand-100 bg-brand-50/40 p-4 flex flex-col justify-between">
                            <div>
                                <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
                                    <i class="fa-solid fa-wand-magic-sparkles"></i>
                                </div>
                                <h3 class="font-bold text-sm md:text-base text-slate-800 mb-1.5">Bơm Bóng Bay & Cho Thuê Phụ Kiện</h3>
                                <p class="text-xs text-slate-600 leading-relaxed mb-3">
                                    Dịch vụ bơm bóng bay an toàn, cho thuê khung sắt tròn, bục đôn trụ tròn, khăn trải bàn, đèn led, khay kệ bánh kem giá tiết kiệm tại Đà Nẵng - Quảng Nam.
                                </p>
                            </div>
                            <a href="#form-bao-gia" onclick="prefillService('Thuê phụ kiện trang trí / Bơm bóng bay')" class="inline-flex items-center text-xs font-bold text-brand-600 hover:underline">
                                Đăng ký báo giá <i class="fa-solid fa-chevron-right ml-1 text-[10px]"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 6. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (Thiết kế nổi bật, dễ chỉnh sửa trong UX Builder) -->
        <section id="form-bao-gia" class="py-5">
            <div class="flatsome-container">
                <div class="bg-gradient-to-r from-brand-50 via-white to-brand-50 rounded-2xl border-2 border-brand-200 p-4 md:p-7 shadow-sm">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        
                        <!-- Cột thông tin cam kết báo giá -->
                        <div class="lg:col-span-5 space-y-3">
                            <span class="inline-block px-3 py-1 rounded-full bg-brand-100 text-brand-700 text-xs font-bold">
                                TƯ VẤN & BÁO GIÁ NHANH 24/7
                            </span>
                            <h2 class="font-display font-bold text-lg md:text-2xl text-brand-800 leading-snug">
                                GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ CHI TIẾT TỪ CON YÊU DECOR
                            </h2>
                            <p class="text-xs md:text-sm text-slate-600 leading-relaxed">
                                Ba/Mẹ đang chuẩn bị tiệc thôi nôi, đầy tháng, sinh nhật cho bé hoặc cần mua set phụ kiện tự trang trí tại nhà? Hãy để lại thông tin, đội ngũ <strong>Con Yêu Decor</strong> sẽ gửi mẫu thực tế và bảng báo giá chi tiết phù hợp ngân sách ngay lập tức!
                            </p>
                            <div class="space-y-2 pt-1 text-xs md:text-sm text-slate-700">
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-circle-check text-brand-600"></i>
                                    <span>Thiết kế chủ đề riêng theo tên, tuổi và sở thích của bé</span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-circle-check text-brand-600"></i>
                                    <span>Nhiều gói dịch vụ linh hoạt từ cơ bản đến cao cấp</span>
                                </div>
                                <div class="flex items-center gap-2.5">
                                    <i class="fa-solid fa-circle-check text-brand-600"></i>
                                    <span>Thi công nhanh chóng, đúng giờ tại Đà Nẵng - Quảng Nam</span>
                                </div>
                            </div>
                            <div class="p-3.5 rounded-xl bg-white border border-brand-200 flex flex-wrap items-center justify-between gap-2">
                                <div>
                                    <div class="text-[11px] text-slate-500 font-medium">Hotline / Zalo tư vấn trực tiếp:</div>
                                    <div class="text-sm md:text-base font-extrabold text-brand-600">0866 480 868 - 0383 476 076</div>
                                </div>
                                <a href="https://zalo.me/0866480868" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold transition">
                                    Chat Zalo Ngay
                                </a>
                            </div>
                        </div>

                        <!-- Cột Form Yêu Cầu & Báo Giá -->
                        <div class="lg:col-span-7 bg-white rounded-xl p-4 md:p-6 border border-brand-100 shadow-sm">
                            <h3 class="font-display font-bold text-base md:text-lg text-slate-800 mb-3 pb-2 border-b border-brand-100">
                                <i class="fa-solid fa-file-invoice text-brand-600 mr-1.5"></i>FORM YÊU CẦU TƯ VẤN & BÁO GIÁ
                            </h3>
                            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên của bạn *</label>
                                        <input id="qName" type="text" required placeholder="Nhập họ tên Ba/Mẹ..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
                                        <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905 xxx xxx" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                                        <select id="qService" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500 bg-white">
                                            <option value="Trang trí thôi nôi - sinh nhật trọn gói cho bé">Trang trí thôi nôi - sinh nhật trọn gói cho bé</option>
                                            <option value="Mua Set bóng trang trí tự làm tại nhà">Mua Set bóng trang trí tự làm tại nhà</option>
                                            <option value="Đặt làm Chibi, Bảng thông tin, Khung 12 tháng">Đặt làm Chibi, Bảng thông tin, Khung 12 tháng</option>
                                            <option value="Trang trí sinh nhật người lớn / Khai trương">Trang trí sinh nhật người lớn / Khai trương</option>
                                            <option value="Trang trí phòng cưới / Cầu hôn lãng mạn">Trang trí phòng cưới / Cầu hôn lãng mạn</option>
                                            <option value="Thuê phụ kiện trang trí / Bơm bóng bay">Thuê phụ kiện trang trí / Bơm bóng bay</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-700 mb-1">Khu vực & Ngày dự kiến tổ chức</label>
                                        <input id="qLocationDate" type="text" placeholder="Đà Nẵng / Quảng Nam - Ngày tổ chức..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-700 mb-1">Ngân sách dự kiến</label>
                                        <select id="qBudget" class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500 bg-white">
                                            <option value="Mua lẻ phụ kiện / Set tự trang trí (150.000đ - 500.000đ)">Mua phụ kiện / Set tự làm (150k - 500k)</option>
                                            <option value="Gói trang trí cơ bản tiết kiệm (1.200.000đ - 2.000.000đ)">Gói trang trí cơ bản (1.2tr - 2tr)</option>
                                            <option value="Gói trang trí tiêu chuẩn (2.000.000đ - 3.500.000đ)">Gói trang trí tiêu chuẩn (2tr - 3.5tr)</option>
                                            <option value="Gói thiết kế cao cấp theo yêu cầu (Trên 3.500.000đ)">Gói thiết kế cao cấp (Trên 3.5tr)</option>
                                            <option value="Cần tư vấn báo giá theo mẫu riêng">Cần tư vấn báo giá theo mẫu riêng</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-700 mb-1">Chủ đề / Tông màu yêu thích</label>
                                        <input id="qTheme" type="text" placeholder="VD: Bé gái tuổi Mèo màu hồng, Bé trai tuổi Rồng..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500">
                                    </div>
                                </div>

                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Ghi chú yêu cầu chi tiết</label>
                                    <textarea id="qNote" rows="2" placeholder="Nhập thêm tên bé, biệt danh hoặc mẫu sản phẩm bạn đang quan tâm..." class="w-full px-3 py-2 text-xs md:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-500"></textarea>
                                </div>

                                <button type="submit" class="w-full py-2.5 px-5 rounded-lg bg-brand-600 hover:bg-brand-700 text-white font-bold text-xs md:text-sm shadow transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU & NHẬN BẢNG BÁO GIÁ NGAY</span>
                                </button>
                            </form>

                            <!-- Hộp thông báo kết quả gửi form -->
                            <div id="quoteSuccessAlert" class="hidden mt-3 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs space-y-1.5">
                                <div class="font-bold text-sm flex items-center gap-1.5">
                                    <i class="fa-solid fa-circle-check text-emerald-600"></i>
                                    <span>Đã ghi nhận yêu cầu báo giá thành công!</span>
                                </div>
                                <p id="quoteSummaryText" class="leading-relaxed"></p>
                                <div class="pt-1 flex flex-wrap gap-2">
                                    <a href="https://zalo.me/0866480868" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded bg-emerald-600 text-white font-bold text-xs">
                                        Gửi qua Zalo 0866 480 868
                                    </a>
                                    <a href="tel:0866480868" class="px-3 py-1.5 rounded bg-white border border-emerald-300 text-emerald-800 font-bold text-xs">
                                        Gọi 0866 480 868
                                    </a>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </section>

        <!-- 7. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Blog Posts Element chuẩn Flatsome) -->
        <section id="tin-tuc-trang-chu" class="py-5">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm md:text-lg">
                            DANH MỤC BÀI VIẾT & KINH NGHIỆM TRANG TRÍ TIỆC
                        </h2>
                        <!-- Danh mục con của bài viết -->
                        <div class="flex flex-wrap items-center gap-1.5">
                            <button type="button" onclick="filterPosts('all')" class="post-cat-btn px-2.5 py-1 rounded-full text-xs font-semibold bg-brand-600 text-white">Tất cả bài viết</button>
                            <button type="button" onclick="filterPosts('Kinh nghiệm thôi nôi')" class="post-cat-btn px-2.5 py-1 rounded-full text-xs font-semibold bg-white border border-brand-200 text-slate-700 hover:bg-brand-50">Kinh nghiệm thôi nôi</button>
                            <button type="button" onclick="filterPosts('Mẫu tiệc thực tế')" class="post-cat-btn px-2.5 py-1 rounded-full text-xs font-semibold bg-white border border-brand-200 text-slate-700 hover:bg-brand-50">Mẫu tiệc thực tế</button>
                            <button type="button" onclick="filterPosts('Hướng dẫn tự trang trí')" class="post-cat-btn px-2.5 py-1 rounded-full text-xs font-semibold bg-white border border-brand-200 text-slate-700 hover:bg-brand-50">Hướng dẫn tự trang trí</button>
                        </div>
                    </div>
                </div>

                <div id="blogPostsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                    <!-- Được render từ danh sách bài viết bên dưới -->
                </div>
            </div>
        </section>

        <!-- 8. ĐƯA FANPAGE FACEBOOK VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
        <section id="lien-he-ban-do" class="py-5">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <div class="section-title-normal">
                        <h2 class="section-title-main text-sm md:text-lg">
                            KẾT NỐI FANPAGE & BẢN ĐỒ ĐỊA CHỈ CON YÊU DECOR (ĐÀ NẴNG - QUẢNG NAM)
                        </h2>
                        <span class="text-xs text-slate-500">conyeudecor.com</span>
                    </div>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                    
                    <!-- CỘT 1: FANPAGE FACEBOOK TRANG CHỦ -->
                    <div class="lg:col-span-5 bg-white rounded-2xl border border-brand-100 p-4 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between mb-3 pb-2 border-b border-brand-100">
                                <h3 class="font-bold text-sm md:text-base text-slate-800 flex items-center gap-2">
                                    <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                    <span>FANPAGE CON YÊU DECOR</span>
                                </h3>
                                <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-blue-600 hover:underline">
                                    Mở Facebook <i class="fa-solid fa-up-right-from-square ml-0.5 text-[10px]"></i>
                                </a>
                            </div>

                            <!-- Khung hiển thị Fanpage trực tiếp ngoài trang chủ -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                                <!-- Ảnh bìa & Avatar Fanpage -->
                                <div class="relative h-32 bg-gradient-to-r from-brand-500 to-brand-400 overflow-hidden">
                                    <img src="https://lh3.googleusercontent.com/d/1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN"
                                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN&sz=w800';}"
                                         alt="Bìa Fanpage Con Yêu Decor" class="w-full h-full object-cover opacity-85">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-black/20 to-transparent"></div>
                                    <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                        <img src="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y"
                                             onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y&sz=w300';}"
                                             alt="Logo Fanpage" class="w-14 h-14 rounded-full border-2 border-white bg-white object-cover shrink-0 shadow">
                                        <div class="text-white min-w-0">
                                            <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="font-bold text-sm md:text-base hover:underline block truncate">
                                                Con Yêu Decor - Trang Trí Thôi Nôi Đà Nẵng
                                            </a>
                                            <span class="text-[11px] text-white/90 block">@trangtrithoinoidanang • Dịch vụ tổ chức sự kiện & Phụ kiện</span>
                                        </div>
                                    </div>
                                </div>

                                <!-- Nội dung & Nút tương tác Fanpage -->
                                <div class="p-3.5 space-y-3 bg-white">
                                    <div class="flex flex-wrap items-center gap-2">
                                        <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="flex-1 py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold text-center transition">
                                            <i class="fa-brands fa-facebook-f mr-1"></i>Theo Dõi Fanpage
                                        </a>
                                        <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="flex-1 py-2 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-800 text-xs font-bold text-center transition">
                                            <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i>Nhắn Tin Tư Vấn
                                        </a>
                                    </div>

                                    <!-- Album ảnh thực tế mới cập nhật trên Fanpage -->
                                    <div class="text-xs text-slate-600">
                                        <p class="font-semibold text-slate-800 mb-2">Hình ảnh thực tế cập nhật trên Fanpage:</p>
                                        <div class="grid grid-cols-3 gap-2">
                                            <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="block h-20 rounded-lg overflow-hidden border border-slate-200">
                                                <img src="https://lh3.googleusercontent.com/d/1gpru4TGUZ6CJfeB16mH0t8_pnJczuVRb"
                                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1gpru4TGUZ6CJfeB16mH0t8_pnJczuVRb&sz=w400';}"
                                                     alt="Ảnh thực tế fanpage 1" class="w-full h-full object-cover hover:scale-105 transition">
                                            </a>
                                            <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="block h-20 rounded-lg overflow-hidden border border-slate-200">
                                                <img src="https://lh3.googleusercontent.com/d/1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN"
                                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN&sz=w400';}"
                                                     alt="Ảnh thực tế fanpage 2" class="w-full h-full object-cover hover:scale-105 transition">
                                            </a>
                                            <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="block h-20 rounded-lg overflow-hidden border border-slate-200">
                                                <img src="https://lh3.googleusercontent.com/d/1PlCjGm6cyTUhKqSVMwrMHnsLAX8y5Uiv"
                                                     onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1PlCjGm6cyTUhKqSVMwrMHnsLAX8y5Uiv&sz=w400';}"
                                                     alt="Ảnh thực tế fanpage 3" class="w-full h-full object-cover hover:scale-105 transition">
                                            </a>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="mt-3 pt-2 border-t border-brand-50 text-xs text-slate-600 flex items-center justify-between">
                            <span>Link Fanpage chính thức:</span>
                            <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="text-brand-600 font-semibold truncate max-w-[220px]">
                                facebook.com/trangtrithoinoidanang
                            </a>
                        </div>
                    </div>

                    <!-- CỘT 2: HÌNH ẢNH & BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ -->
                    <div class="lg:col-span-7 bg-white rounded-2xl border border-brand-100 p-4 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex flex-wrap items-center justify-between gap-2 mb-3 pb-2 border-b border-brand-100">
                                <h3 class="font-bold text-sm md:text-base text-slate-800 flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-brand-600 text-lg"></i>
                                    <span>BẢN ĐỒ GOOGLE MAP - KHU VỰC ĐÀ NẴNG - QUẢNG NAM</span>
                                </h3>
                                <a href="https://www.google.com/maps/search/?api=1&query=Da+Nang+Quang+Nam" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-brand-600 hover:underline">
                                    Xem bản đồ lớn <i class="fa-solid fa-diamond-turn-right ml-0.5"></i>
                                </a>
                            </div>

                            <!-- Bản đồ Google Map trực quan ngoài trang chủ -->
                            <div class="rounded-xl overflow-hidden border border-slate-200 h-64 md:h-72 bg-slate-100 relative">
                                <iframe
                                    title="Bản đồ Google Map Con Yêu Decor Đà Nẵng - Quảng Nam"
                                    src="https://www.google.com/maps?q=%C4%90%C3%A0+N%E1%BA%B5ng+Qu%E1%BA%A3ng+Nam&output=embed"
                                    class="w-full h-full border-0"
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>

                        <!-- Thông tin địa chỉ & số điện thoại dưới bản đồ -->
                        <div class="mt-3 grid grid-cols-1 sm:grid-cols-3 gap-2.5 text-xs">
                            <div class="p-2.5 rounded-lg bg-brand-50/70 border border-brand-100">
                                <div class="font-bold text-brand-700 mb-0.5"><i class="fa-solid fa-location-dot mr-1"></i>Địa chỉ phục vụ:</div>
                                <div class="text-slate-700 font-medium">Đà Nẵng - Quảng Nam</div>
                            </div>
                            <div class="p-2.5 rounded-lg bg-brand-50/70 border border-brand-100">
                                <div class="font-bold text-brand-700 mb-0.5"><i class="fa-solid fa-phone-volume mr-1"></i>Hotline / Zalo:</div>
                                <div class="text-slate-700 font-bold">0866 480 868 - 0383 476 076</div>
                            </div>
                            <div class="p-2.5 rounded-lg bg-brand-50/70 border border-brand-100">
                                <div class="font-bold text-brand-700 mb-0.5"><i class="fa-solid fa-globe mr-1"></i>Website chính thức:</div>
                                <div class="text-slate-700 font-medium">conyeudecor.com</div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <!-- ==========================================
         FOOTER (Chuẩn cấu trúc 4 cột Flatsome Footer)
    =========================================== -->
    <footer class="bg-white border-t-2 border-brand-200 mt-6 text-slate-700">
        <div class="flatsome-container py-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 text-xs md:text-sm">
                
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y"
                             onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=1SKiuxNG4KFr-XMzdbzJsi3to3LXuwh8Y&sz=w200';}"
                             alt="Logo Con Yêu Decor" class="w-11 h-11 rounded-full border border-brand-300 object-cover shrink-0">
                        <div>
                            <div class="font-display font-bold text-base text-brand-600">CON YÊU DECOR</div>
                            <div class="text-xs text-slate-500">Website: conyeudecor.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Chuyên cung cấp phụ kiện trang trí sinh nhật, thôi nôi, thiết kế chibi, bảng thông tin bé và dịch vụ trang trí tiệc trọn gói uy tín tại Đà Nẵng - Quảng Nam.
                    </p>
                    <div class="space-y-1.5 text-xs">
                        <div><i class="fa-solid fa-location-dot text-brand-600 w-5"></i><strong>Địa chỉ:</strong> Đà Nẵng - Quảng Nam</div>
                        <div><i class="fa-solid fa-phone text-brand-600 w-5"></i><strong>SĐT:</strong> 0866 480 868 - 0383 476 076</div>
                        <div><i class="fa-solid fa-globe text-brand-600 w-5"></i><strong>Web:</strong> conyeudecor.com</div>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="font-display font-bold text-sm text-brand-700 uppercase mb-3 pb-1.5 border-b border-brand-100">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-all" onclick="filterByCategory('Set bóng trang trí')" class="hover:text-brand-600">Set bóng trang trí (Bé trai, Bé gái, Người lớn)</a></li>
                        <li><a href="#san-pham-all" onclick="filterByCategory('Trang trí tiệc cho bé')" class="hover:text-brand-600">Trang trí thôi nôi & sinh nhật cho bé</a></li>
                        <li><a href="#san-pham-all" onclick="filterByCategory('Sản phẩm thiết kế riêng')" class="hover:text-brand-600">Sản phẩm thiết kế riêng (Chibi, Bảng thông tin)</a></li>
                        <li><a href="#san-pham-all" onclick="filterByCategory('Tất cả phụ kiện')" class="hover:text-brand-600">Tất cả phụ kiện sinh nhật, rèm, nến, bóng số</a></li>
                        <li><a href="#san-pham-all" onclick="filterByCategory('Cưới hỏi, tình yêu')" class="hover:text-brand-600">Phụ kiện trang trí phòng cưới, cầu hôn</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dịch vụ & Chính sách -->
                <div>
                    <h4 class="font-display font-bold text-sm text-brand-700 uppercase mb-3 pb-1.5 border-b border-brand-100">
                        Dịch Vụ & Hỗ Trợ Khách Hàng
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#dich-vu-tron-goi" class="hover:text-brand-600">Dịch vụ trang trí thôi nôi - sinh nhật trọn gói</a></li>
                        <li><a href="#dich-vu-tron-goi" class="hover:text-brand-600">Dịch vụ bơm bóng bay & cho thuê phụ kiện</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-brand-600">Gửi yêu cầu tư vấn & Nhận báo giá nhanh</a></li>
                        <li><a href="#tin-tuc-trang-chu" class="hover:text-brand-600">Chính sách giao hàng & Đổi trả phụ kiện</a></li>
                        <li><a href="#lien-he-ban-do" class="hover:text-brand-600">Câu hỏi thường gặp khi đặt tiệc</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối nhanh -->
                <div>
                    <h4 class="font-display font-bold text-sm text-brand-700 uppercase mb-3 pb-1.5 border-b border-brand-100">
                        Liên Hệ Nhanh
                    </h4>
                    <p class="text-xs text-slate-600 mb-3 leading-relaxed">
                        Liên hệ trực tiếp với Con Yêu Decor qua Hotline, Zalo hoặc Fanpage để được gửi mẫu phù hợp nhất cho bé yêu:
                    </p>
                    <div class="space-y-2 text-xs font-bold">
                        <a href="tel:0866480868" class="flex items-center gap-2 px-3 py-2 rounded-lg bg-brand-50 text-brand-700 border border-brand-200 hover:bg-brand-100">
                            <i class="fa-solid fa-phone-volume"></i>
                            <span>Hotline 1: 0866 480 868</span>
                        </a>
                        <a href="tel:0383476076" class="flex items-center gap-2 px-3 py-2 rounded-lg bg-brand-50 text-brand-700 border border-brand-200 hover:bg-brand-100">
                            <i class="fa-solid fa-phone-volume"></i>
                            <span>Hotline 2: 0383 476 076</span>
                        </a>
                        <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 px-3 py-2 rounded-lg bg-blue-50 text-blue-700 border border-blue-200 hover:bg-blue-100">
                            <i class="fa-brands fa-facebook"></i>
                            <span>Fanpage Con Yêu Decor</span>
                        </a>
                    </div>
                </div>

            </div>
        </div>

        <div class="bg-brand-700 text-white text-center text-xs py-3 px-4">
            Copyright © CON YÊU DECOR (conyeudecor.com) • Trang Trí Thôi Nôi, Sinh Nhật Đà Nẵng - Quảng Nam • SĐT: 0866 480 868 - 0383 476 076
        </div>
    </footer>

    <!-- ==========================================
         CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích mượt mà trên cả máy tính và điện thoại, không gây tràn viền
    =========================================== -->
    <div class="fixed bottom-4 right-3 md:right-5 z-40 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/trangtrithoinoidanang" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#1877F2] hover:bg-blue-700 text-white shadow-lg transition"
           title="Fanpage Con Yêu Decor">
            <i class="fa-brands fa-facebook-messenger text-base md:text-lg"></i>
            <span class="text-[11px] md:text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0866480868" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#0068FF] hover:bg-blue-600 text-white shadow-lg transition"
           title="Chat Zalo 0866 480 868">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-[11px] md:text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Hotline 2: 0383 476 076 -->
        <a href="tel:0383476076"
           class="flex items-center gap-2 px-3 py-2 rounded-full bg-rose-500 hover:bg-rose-600 text-white shadow-lg transition"
           title="Gọi 0383 476 076">
            <i class="fa-solid fa-phone text-xs md:text-sm"></i>
            <span class="text-[11px] md:text-xs font-bold">0383 476 076</span>
        </a>

        <!-- Nút Hotline 1 chính: 0866 480 868 -->
        <a href="tel:0866480868"
           class="floating-btn-pulse flex items-center gap-2 px-3.5 py-2.5 rounded-full bg-brand-600 hover:bg-brand-700 text-white shadow-xl transition"
           title="Gọi 0866 480 868">
            <i class="fa-solid fa-phone-volume text-sm md:text-base"></i>
            <span class="text-xs md:text-sm font-extrabold">0866 480 868</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT / GIỎ HÀNG
    =========================================== -->
    <div id="infoModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3" onclick="closeInfoModal(event)">
        <div class="bg-white rounded-2xl max-w-lg w-full max-h-[90vh] overflow-y-auto p-4 md:p-6 shadow-2xl border border-brand-200" onclick="event.stopPropagation()">
            <div class="flex items-center justify-between pb-3 border-b border-brand-100 mb-3">
                <h3 id="modalTitle" class="font-display font-bold text-base md:text-lg text-brand-700">Thông tin chi tiết</h3>
                <button type="button" onclick="hideInfoModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 flex items-center justify-center text-slate-600">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modalBody" class="text-xs md:text-sm text-slate-700 space-y-3"></div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SẢN PHẨM, SLIDER, BÁO GIÁ & GIỎ HÀNG
    =========================================== -->
    <script>
        // Danh sách 9 sản phẩm thực tế lấy trực tiếp từ 9 file Google Drive của Con Yêu Decor
        const realProducts = [
            {
                id: 'CYD-01',
                driveId: '1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad',
                name: 'Set Trang Trí Thôi Nôi - Sinh Nhật Cho Bé Phông Cứng Cao Cấp Kèm Bóng Nghệ Thuật CYD01',
                category: 'Trang trí tiệc cho bé',
                oldPrice: 1850000,
                price: 1490000,
                discount: 19,
                desc: 'Trọn gói trang trí phông in thiết kế riêng theo tên bé, line bong bóng pastel phối màu Hàn Quốc, bục đôn trưng bày, hình chibi và bảng thông tin bé tại Đà Nẵng - Quảng Nam.'
            },
            {
                id: 'CYD-02',
                driveId: '1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY',
                name: 'Gói Trang Trí Sinh Nhật Bé Gái Tông Hồng Ngọt Ngào Kèm Chibi & Bảng Tên Thiết Kế Riêng CYD02',
                category: 'Trang trí tiệc cho bé',
                oldPrice: 2200000,
                price: 1790000,
                discount: 19,
                desc: 'Mẫu thực tế trang trí thôi nôi - sinh nhật bé gái ngọt ngào, đầy đủ phông nền, trụ bóng, mô hình chibi bé, cây welcome và phụ kiện bàn gallery.'
            },
            {
                id: 'CYD-03',
                driveId: '1FS2wcUuUI40OTx0IuP8q8FCoXv_eJQ8m',
                name: 'Gói Trang Trí Thôi Nôi Bé Trai Chủ Đề Hoàng Tử Nhí Đáng Yêu Trọn Gói Tại Nhà CYD03',
                category: 'Phụ kiện thôi nôi',
                oldPrice: 2100000,
                price: 1690000,
                discount: 20,
                desc: 'Thiết kế và thi công tận nơi tại Đà Nẵng - Quảng Nam, bao gồm backdrop tên bé, bóng bay nghệ thuật, chibi bé trai và phụ kiện trang trí đồng bộ.'
            },
            {
                id: 'CYD-04',
                driveId: '13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ',
                name: 'Set Bóng Trang Trí Sinh Nhật Tự Làm Tại Nhà Kèm Phông Bạt & Chibi Thiết Kế Theo Yêu Cầu CYD04',
                category: 'Set bóng trang trí',
                oldPrice: 450000,
                price: 349000,
                discount: 22,
                desc: 'Set phụ kiện đầy đủ bóng nhũ, dây kết bóng, rèm trang trí, chữ Happy Birthday, tặng kèm bơm tay và keo dán chuyên dụng.'
            },
            {
                id: 'CYD-05',
                driveId: '1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH',
                name: 'Combo Phụ Kiện Thôi Nôi - Bảng Thông Tin Sinh Nhật, Khung Ảnh 12 Tháng & Chibi Cho Bé CYD05',
                category: 'Sản phẩm thiết kế riêng',
                oldPrice: 380000,
                price: 299000,
                discount: 21,
                desc: 'In ấn sắc nét trên chất liệu formex cứng cáp, thiết kế riêng theo hình ảnh của bé yêu, lưu giữ trọn vẹn khoảnh khắc đầu đời.'
            },
            {
                id: 'CYD-06',
                driveId: '1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M',
                name: 'Gói Decor Backdrop Sinh Nhật Sang Trọng Cho Bé & Người Lớn Phong Cách Hiện Đại CYD06',
                category: 'Trang trí tiệc người lớn',
                oldPrice: 2500000,
                price: 1990000,
                discount: 20,
                desc: 'Phù hợp tổ chức tại nhà hàng, khách sạn hoặc tại gia với hệ khung tròn, đèn led hắt sáng, bóng nhũ chrome sang trọng.'
            },
            {
                id: 'CYD-07',
                driveId: '1gpru4TGUZ6CJfeB16mH0t8_pnJczuVRb',
                name: 'Set Trang Trí Phòng Cưới & Tiệc Kỷ Niệm Ngọt Ngào Lãng Mạn Kèm Bóng Nhũ & Đèn Led CYD07',
                category: 'Cưới hỏi, tình yêu',
                oldPrice: 490000,
                price: 389000,
                discount: 21,
                desc: 'Trọn bộ bóng Happy Wedding, bóng tim, cánh hoa hồng, nến điện tử lãng mạn dành cho phòng tân hôn và lễ kỷ niệm.'
            },
            {
                id: 'CYD-08',
                driveId: '1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN',
                name: 'Gói Trang Trí Thôi Nôi - Sinh Nhật Cao Cấp Thiết Kế 3D Riêng Biệt Theo Tuổi Bé CYD08',
                category: 'Trang trí tiệc cho bé',
                oldPrice: 3200000,
                price: 2650000,
                discount: 17,
                desc: 'Gói trang trí cao cấp nhiều lớp phông 3D, bục đôn gallery, đèn led, bong bóng pastel Hàn Quốc và bộ chibi gia đình.'
            },
            {
                id: 'CYD-09',
                driveId: '1PlCjGm6cyTUhKqSVMwrMHnsLAX8y5Uiv',
                name: 'Set Phụ Kiện Trang Trí Bàn Gallery Sinh Nhật Trọn Bộ Kèm Bóng Số Tuổi Cỡ Lớn CYD09',
                category: 'Tất cả phụ kiện',
                oldPrice: 350000,
                price: 279000,
                discount: 20,
                desc: 'Đầy đủ khăn trải bàn, bóng số tuổi cỡ đại 70cm, nón sinh nhật, dây treo Happy Birthday và hình chibi để bàn.'
            }
        ];

        // Danh sách sản phẩm phụ kiện bán chạy chuẩn mẫu Ruby Phụ Kiện Sinh Nhật kết hợp ảnh thực tế
        const accessoryProducts = [
            {
                id: 'PK-01',
                driveId: '13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ',
                name: 'Hình Chibi Sinh Nhật Thiết Kế Theo Hình Bé Cao 30cm - 40cm Sắc Nét',
                category: 'Sản phẩm thiết kế riêng',
                oldPrice: 55000,
                price: 39000,
                discount: 29,
                desc: 'Chibi bé trai, chibi bé gái cắt viền tỉ mỉ kèm chân đế đứng vững chắc.'
            },
            {
                id: 'PK-02',
                driveId: '1Jgkvm4Hbw1LNlpbbmWKpYFEfpWP8adWH',
                name: 'Bảng Thông Tin Sinh Nhật & Khung Hình 12 Tháng Thiết Kế Riêng Cho Bé',
                category: 'Sản phẩm thiết kế riêng',
                oldPrice: 250000,
                price: 199000,
                discount: 20,
                desc: 'Ghi lại sở thích, cân nặng, chiều cao và 12 tháng phát triển đầu đời của bé.'
            },
            {
                id: 'PK-03',
                driveId: '1PlCjGm6cyTUhKqSVMwrMHnsLAX8y5Uiv',
                name: 'Hộp Chữ BABY Trong Suốt Đựng Bong Bóng Trang Trí Thôi Nôi Sinh Nhật',
                category: 'Tất cả phụ kiện',
                oldPrice: 290000,
                price: 190000,
                discount: 34,
                desc: 'Bộ 4 hộp chữ BABY kèm bóng bên trong, dễ dàng lắp ráp trang trí góc chụp hình.'
            },
            {
                id: 'PK-04',
                driveId: '1pJMDacpy6I9DY8Z_D9Ic9w9A-1DsPM-M',
                name: 'Bóng Jumbo Nhũ To In Tên Bé Theo Yêu Cầu Trang Trí Tiệc Sinh Nhật',
                category: 'Tất cả phụ kiện',
                oldPrice: 350000,
                price: 280000,
                discount: 20,
                desc: 'Quả bóng Jumbo cỡ lớn lồng kim tuyến lấp lánh, in decal tên bé và lời chúc.'
            }
        ];

        // Danh sách bài viết trang chủ
        const blogPosts = [
            {
                id: 'POST-1',
                category: 'Kinh nghiệm thôi nôi',
                date: '15/10/2026',
                driveId: '1gbq8BTdhO-q0I9lBFHY5hgpnNoDFedad',
                title: 'Kinh nghiệm chuẩn bị tiệc thôi nôi trọn vẹn và tiết kiệm cho bé tại Đà Nẵng - Quảng Nam',
                excerpt: 'Tổng hợp các bước lựa chọn chủ đề trang trí, chuẩn bị bàn gallery, hình chibi và đặt dịch vụ trang trí thôi nôi tại nhà đẹp mắt.'
            },
            {
                id: 'POST-2',
                category: 'Mẫu tiệc thực tế',
                date: '24/10/2026',
                driveId: '1CnYt-Nca1NbGw9rm6b8tHRCBxRGiaPZY',
                title: 'Top 9 mẫu trang trí thôi nôi & sinh nhật bé gái, bé trai đẹp lung linh tại Con Yêu Decor',
                excerpt: 'Cùng ngắm nhìn những không gian tiệc thực tế do đội ngũ Con Yêu Decor thiết kế và thi công tận nơi cho các thiên thần nhỏ.'
            },
            {
                id: 'POST-3',
                category: 'Hướng dẫn tự trang trí',
                date: '02/11/2026',
                driveId: '13PdtL_e3XU6bEulb7H9qtHP5iq0xnytJ',
                title: 'Cách tự kết dây bong bóng nghệ thuật và bố trí phụ kiện sinh nhật tại nhà cực dễ',
                excerpt: 'Hướng dẫn từng bước sử dụng dây kết bóng, keo chấm bi và bơm bóng để Ba/Mẹ tự tay làm góc chụp ảnh sinh nhật cho con.'
            },
            {
                id: 'POST-4',
                category: 'Kinh nghiệm thôi nôi',
                date: '07/11/2026',
                driveId: '1amvkaV0dTnPNUGXyHPsb-YcoPmlbx-VN',
                title: 'Cách chọn ảnh bé để in Chibi, Bảng thông tin và Khung ảnh 12 tháng sắc nét nhất',
                excerpt: 'Bí quyết chọn ảnh rõ nét, biểu cảm đáng yêu để Con Yêu Decor thiết kế bộ phụ kiện chibi độc quyền cho tiệc của bé.'
            }
        ];

        let cartItems = [];

        function formatVND(amount) {
            return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + '₫';
        }

        // Tạo thẻ sản phẩm chuẩn Flatsome:
        // - Nhãn giảm giá (-XX%) nằm góc trên bên trái
        // - Không có bất kỳ nhãn dán thừa nào khác
        // - Tên sản phẩm hiển thị đầy đủ không cắt chữ
        function createProductCardHTML(item) {
            return `
                <div class="flatsome-product-box">
                    <div class="relative aspect-square w-full bg-brand-50 overflow-hidden">
                        <span class="flatsome-badge-sale">-${item.discount}%</span>
                        <img src="https://lh3.googleusercontent.com/d/${item.driveId}"
                             onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800';}else{this.onerror=null;this.src='https://placehold.co/600x600/fff1f4/e11d53?text=Con+Yeu+Decor';}"
                             alt="${item.name}"
                             loading="lazy"
                             onclick="viewProductDetail('${item.id}')"
                             class="w-full h-full object-cover cursor-pointer hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] md:text-[11px] text-slate-400 font-medium mb-1">${item.category}</div>
                            <h3 onclick="viewProductDetail('${item.id}')" class="product-title-full font-semibold text-xs md:text-sm text-slate-800 hover:text-brand-600 cursor-pointer mb-2">
                                ${item.name}
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] md:text-xs text-slate-400">${formatVND(item.oldPrice)}</del>
                                <ins class="no-underline font-extrabold text-xs md:text-sm text-brand-600">${formatVND(item.price)}</ins>
                            </div>
                            <div class="grid grid-cols-2 gap-1.5">
                                <button type="button" onclick="addToCart('${item.id}')" class="py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white font-bold text-[11px] md:text-xs transition">
                                    Đặt hàng
                                </button>
                                <a href="#form-bao-gia" onclick="prefillService('${item.name}')" class="py-1.5 px-2 rounded-lg bg-brand-50 hover:bg-brand-100 text-brand-700 border border-brand-200 font-bold text-[11px] md:text-xs text-center transition">
                                    Báo giá
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            `;
        }

        function renderMainProducts(list) {
            const container = document.getElementById('mainProductGrid');
            if (!list.length) {
                container.innerHTML = `<div class="col-span-full bg-white rounded-xl p-6 text-center text-xs md:text-sm text-slate-500 border border-brand-100">Không tìm thấy sản phẩm phù hợp. <button onclick="filterByCategory('all')" class="text-brand-600 font-bold underline ml-1">Xem tất cả sản phẩm</button></div>`;
                return;
            }
            container.innerHTML = list.map(createProductCardHTML).join('');
        }

        function renderAccessoryProducts() {
            const container = document.getElementById('accessoryProductGrid');
            container.innerHTML = accessoryProducts.map(createProductCardHTML).join('');
        }

        function filterByCategory(catName) {
            const heading = document.getElementById('activeCategoryHeading');
            if (catName === 'all') {
                heading.textContent = 'SẢN PHẨM & MẪU TRANG TRÍ THỰC TẾ NỔI BẬT';
                renderMainProducts(realProducts);
            } else {
                heading.textContent = 'DANH MỤC: ' + catName.toUpperCase();
                const filtered = realProducts.filter(p => p.category.toLowerCase() === catName.toLowerCase());
                renderMainProducts(filtered.length ? filtered : realProducts);
            }
        }

        function handleSearch(e) {
            e.preventDefault();
            const kw = document.getElementById('desktopSearchInput').value.trim().toLowerCase();
            runKeywordSearch(kw);
        }

        function handleMobileSearch(e) {
            e.preventDefault();
            const kw = document.getElementById('mobileSearchInput').value.trim().toLowerCase();
            runKeywordSearch(kw);
        }

        function runKeywordSearch(kw) {
            if (!kw) {
                filterByCategory('all');
                return;
            }
            const allItems = [...realProducts, ...accessoryProducts];
            const matches = allItems.filter(p => p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw));
            document.getElementById('activeCategoryHeading').textContent = `KẾT QUẢ TÌM KIẾM: "${kw.toUpperCase()}"`;
            renderMainProducts(matches);
            document.getElementById('san-pham-all').scrollIntoView({ behavior: 'smooth' });
        }

        // Render danh mục bài viết trang chủ
        function renderBlogPosts(categoryFilter = 'all') {
            const container = document.getElementById('blogPostsGrid');
            const list = categoryFilter === 'all'
                ? blogPosts
                : blogPosts.filter(p => p.category === categoryFilter);

            container.innerHTML = list.map(post => `
                <article class="bg-white rounded-xl border border-brand-100 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-video w-full overflow-hidden bg-brand-50">
                            <img src="https://lh3.googleusercontent.com/d/${post.driveId}"
                                 onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=${post.driveId}&sz=w600';}"
                                 alt="${post.title}"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3.5">
                            <div class="flex items-center justify-between text-[11px] text-brand-600 font-semibold mb-1.5">
                                <span>${post.category}</span>
                                <span class="text-slate-400 font-normal">${post.date}</span>
                            </div>
                            <h3 onclick="viewPostDetail('${post.id}')" class="font-bold text-xs md:text-sm text-slate-800 hover:text-brand-600 cursor-pointer leading-snug mb-2">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                ${post.excerpt}
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3.5">
                        <button type="button" onclick="viewPostDetail('${post.id}')" class="text-xs font-bold text-brand-600 hover:underline">
                            Xem chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        function filterPosts(cat) {
            renderBlogPosts(cat);
        }

        // Xem chi tiết sản phẩm trong Modal
        function viewProductDetail(id) {
            const all = [...realProducts, ...accessoryProducts];
            const item = all.find(p => p.id === id);
            if (!item) return;

            document.getElementById('modalTitle').textContent = item.name;
            document.getElementById('modalBody').innerHTML = `
                <div class="rounded-xl overflow-hidden border border-brand-100 max-h-72 bg-brand-50">
                    <img src="https://lh3.googleusercontent.com/d/${item.driveId}"
                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=${item.driveId}&sz=w800';}"
                         alt="${item.name}" class="w-full h-full object-contain mx-auto max-h-72">
                </div>
                <div class="flex items-center gap-2 pt-1">
                    <span class="px-2.5 py-0.5 rounded-full bg-brand-600 text-white text-xs font-bold">Giảm ${item.discount}%</span>
                    <del class="text-xs text-slate-400">${formatVND(item.oldPrice)}</del>
                    <span class="text-base font-extrabold text-brand-600">${formatVND(item.price)}</span>
                </div>
                <p class="text-xs md:text-sm text-slate-600 leading-relaxed">${item.desc}</p>
                <div class="p-3 rounded-lg bg-brand-50 border border-brand-100 text-xs space-y-1">
                    <div><strong>Thương hiệu:</strong> CON YÊU DECOR (conyeudecor.com)</div>
                    <div><strong>Khu vực:</strong> Đà Nẵng - Quảng Nam</div>
                    <div><strong>Hotline / Zalo:</strong> 0866 480 868 - 0383 476 076</div>
                </div>
                <div class="flex gap-2 pt-2">
                    <button type="button" onclick="addToCart('${item.id}'); hideInfoModal();" class="flex-1 py-2.5 rounded-lg bg-brand-600 text-white font-bold text-xs">
                        Thêm vào giỏ hàng
                    </button>
                    <a href="#form-bao-gia" onclick="prefillService('${item.name}'); hideInfoModal();" class="flex-1 py-2.5 rounded-lg bg-brand-100 text-brand-700 font-bold text-xs text-center">
                        Nhận báo giá mẫu này
                    </a>
                </div>
            `;
            showInfoModal();
        }

        function viewPostDetail(postId) {
            const post = blogPosts.find(p => p.id === postId);
            if (!post) return;
            document.getElementById('modalTitle').textContent = post.title;
            document.getElementById('modalBody').innerHTML = `
                <div class="rounded-xl overflow-hidden border border-brand-100 max-h-64">
                    <img src="https://lh3.googleusercontent.com/d/${post.driveId}"
                         onerror="if(!this.dataset.thumb){this.dataset.thumb='1';this.src='https://drive.google.com/thumbnail?id=${post.driveId}&sz=w800';}"
                         alt="${post.title}" class="w-full h-full object-cover">
                </div>
                <div class="text-xs text-brand-600 font-semibold">${post.category} • Ngày đăng: ${post.date}</div>
                <p class="text-xs md:text-sm text-slate-700 leading-relaxed">${post.excerpt}</p>
                <p class="text-xs md:text-sm text-slate-700 leading-relaxed">
                    Tại <strong>Con Yêu Decor (conyeudecor.com)</strong>, mỗi bữa tiệc thôi nôi và sinh nhật đều được chăm chút tỉ mỉ từ khâu lên ý tưởng chủ đề, phối màu bong bóng đến thiết kế chibi và bảng thông tin riêng cho bé. Liên hệ ngay Hotline <strong>0866 480 868 - 0383 476 076</strong> để được tư vấn tận tình tại Đà Nẵng - Quảng Nam.
                </p>
            `;
            showInfoModal();
        }

        function addToCart(productId) {
            const all = [...realProducts, ...accessoryProducts];
            const item = all.find(p => p.id === productId);
            if (!item) return;
            cartItems.push(item);
            document.getElementById('cartCountBadge').textContent = cartItems.length;
            openCartModal();
        }

        function openCartModal() {
            document.getElementById('modalTitle').textContent = `Giỏ hàng của bạn (${cartItems.length} sản phẩm)`;
            if (!cartItems.length) {
                document.getElementById('modalBody').innerHTML = `
                    <div class="py-6 text-center text-slate-500 text-xs">
                        Chưa có sản phẩm nào trong giỏ hàng. Hãy chọn mẫu trang trí hoặc phụ kiện bạn yêu thích nhé!
                    </div>
                `;
            } else {
                const total = cartItems.reduce((sum, i) => sum + i.price, 0);
                document.getElementById('modalBody').innerHTML = `
                    <div class="divide-y divide-brand-100 max-h-60 overflow-y-auto">
                        ${cartItems.map((c, idx) => `
                            <div class="py-2 flex items-center justify-between gap-2">
                                <div class="text-xs font-medium text-slate-800">${idx + 1}. ${c.name}</div>
                                <div class="text-xs font-bold text-brand-600 shrink-0">${formatVND(c.price)}</div>
                            </div>
                        `).join('')}
                    </div>
                    <div class="pt-3 border-t border-brand-200 flex items-center justify-between font-bold text-sm">
                        <span>Tổng cộng tạm tính:</span>
                        <span class="text-brand-600">${formatVND(total)}</span>
                    </div>
                    <div class="pt-2 flex gap-2">
                        <a href="#form-bao-gia" onclick="prefillService('Đặt giỏ hàng (${cartItems.length} sản phẩm - Tổng: ${formatVND(total)})'); hideInfoModal();" class="flex-1 py-2.5 rounded-lg bg-brand-600 text-white text-center font-bold text-xs">
                            Gửi đơn & Nhận xác nhận
                        </a>
                        <a href="https://zalo.me/0866480868" target="_blank" rel="noopener noreferrer" class="flex-1 py-2.5 rounded-lg bg-blue-600 text-white text-center font-bold text-xs">
                            Chốt đơn qua Zalo
                        </a>
                    </div>
                `;
            }
            showInfoModal();
        }

        function showInfoModal() {
            const modal = document.getElementById('infoModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function hideInfoModal() {
            const modal = document.getElementById('infoModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function closeInfoModal(e) {
            if (e.target.id === 'infoModal') hideInfoModal();
        }

        // Điền nhanh tên dịch vụ/sản phẩm vào Form Báo Giá
        function prefillService(serviceName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = `Cần tư vấn & báo giá mẫu: ${serviceName}`;
            }
        }

        // Xử lý gửi Form Yêu Cầu & Báo Giá Trang Chủ
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const service = document.getElementById('qService').value;
            const locDate = document.getElementById('qLocationDate').value.trim() || 'Đà Nẵng - Quảng Nam';
            const budget = document.getElementById('qBudget').value;
            const theme = document.getElementById('qTheme').value.trim() || 'Tư vấn theo mẫu thực tế';

            const alertBox = document.getElementById('quoteSuccessAlert');
            const summaryText = document.getElementById('quoteSummaryText');
            summaryText.innerHTML = `Cảm ơn <strong>${name}</strong> (SĐT: <strong>${phone}</strong>). Con Yêu Decor đã nhận yêu cầu báo giá hạng mục <strong>${service}</strong> (${budget}) tại <strong>${locDate}</strong> - Chủ đề: <strong>${theme}</strong>. Nhân viên tư vấn sẽ liên hệ qua Zalo/SĐT của bạn trong ít phút!`;
            alertBox.classList.remove('hidden');
        }

        // Đóng/mở Menu trên điện thoại
        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const overlay = document.getElementById('mobileMenuOverlay');
            const isHidden = drawer.classList.contains('-translate-x-full');
            if (isHidden) {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            }
        }

        // Slider 2 Banner tự động trượt mượt mà
        let currentSlideIndex = 0;
        const totalSlides = 2;
        let bannerInterval = null;

        function goToBannerSlide(index) {
            currentSlideIndex = (index + totalSlides) % totalSlides;
            for (let i = 0; i < totalSlides; i++) {
                const slide = document.getElementById('bannerSlide' + i);
                const dot = document.getElementById('sliderDot' + i);
                if (i === currentSlideIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                    dot.className = 'w-5 h-2 rounded-full bg-brand-600 transition-all';
                } else {
                    slide.classList.add('hidden');
                    slide.classList.remove('block');
                    dot.className = 'w-2 h-2 rounded-full bg-brand-300 transition-all';
                }
            }
        }

        function nextBannerSlide() {
            goToBannerSlide(currentSlideIndex + 1);
            resetBannerTimer();
        }

        function prevBannerSlide() {
            goToBannerSlide(currentSlideIndex - 1);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                goToBannerSlide(currentSlideIndex + 1);
            }, 5000);
        }

        window.onload = function () {
            renderMainProducts(realProducts);
            renderAccessoryProducts();
            renderBlogPosts('all');
            resetBannerTimer();
        };
    </script>
</body>
</html>
