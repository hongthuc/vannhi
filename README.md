<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH VÂN NHI TÚY LOAN | Tổng Kho Gạch Ốp Lát & Thiết Bị Vệ Sinh Đà Nẵng - vannhi.vn</title>
  <meta name="description" content="CÔNG TY TNHH VÂN NHI TÚY LOAN (vannhi.vn) - Chuyên phân phối gạch lát nền, gạch ốp tường, gạch khổ lớn, gạch trang trí, thiết bị vệ sinh chính hãng tại Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng. Hotline: 0905.567.811 - 0934.999.429">
  
  <!-- Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://vannhi.vn/">
  <meta property="og:title" content="CÔNG TY TNHH VÂN NHI TÚY LOAN - Gạch Men & Thiết Bị Vệ Sinh Đà Nẵng">
  <meta property="og:description" content="Tổng kho phân phối Gạch ốp lát, Gạch khổ lớn, Gạch trang trí & Thiết bị vệ sinh uy tín tại Đà Nẵng. Đ/c: Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng.">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m">
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <!-- Google Fonts Roboto & Inter chuẩn Flatsome -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brand: {
              dark: '#0c2d57',
              DEFAULT: '#134686',
              light: '#1e5fac',
              accent: '#d9381e',
              gold: '#c88a2b',
              bg: '#f5f7fa'
            }
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif']
          }
        }
      }
    }
  </script>

  <style>
    /* Khóa tràn viền ngang tuyệt đối & đảm bảo không lệch phải */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100%;
      max-width: 100%;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f6f7f9;
      color: #222222;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính chuẩn 1500px theo yêu cầu */
    .container-1500 {
      width: 100%;
      max-width: 1500px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 768px) {
      .container-1500 {
        padding-left: 20px;
        padding-right: 20px;
      }
    }

    /* Tiêu đề Section chuẩn Flatsome UX Builder */
    .section-title-container {
      margin-bottom: 18px;
    }
    .section-title-normal {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #e2e8f0;
      padding-bottom: 8px;
      gap: 12px;
    }
    .section-title-main {
      font-weight: 700;
      text-transform: uppercase;
      color: #134686;
      position: relative;
      display: inline-block;
    }
    .section-title-main::after {
      content: '';
      position: absolute;
      bottom: -10px;
      left: 0;
      width: 100%;
      height: 3px;
      background-color: #d9381e;
    }

    /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d9381e;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 6px 7px;
      border-radius: 50%;
      min-width: 36px;
      min-height: 36px;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }

    /* Tên danh mục luôn nằm trên 1 dòng không bị rớt chữ */
    .cat-nowrap {
      white-space: nowrap !important;
    }

    /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không tràn ra ngoài và không bị cắt mất chữ */
    .product-title-full {
      word-wrap: break-word;
      overflow-wrap: break-word;
      word-break: break-word;
      white-space: normal;
      line-height: 1.38;
    }

    /* Hiệu ứng nút liên hệ nổi bật */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 56, 30, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 56, 30, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 56, 30, 0); }
    }
    .contact-float-pulse {
      animation: pulse-ring 2s infinite;
    }

    /* Dropdown danh mục Flatsome */
    .nav-item-has-dropdown:hover .nav-dropdown {
      display: block;
    }
  </style>
</head>
<body class="w-full overflow-x-hidden">

  <!-- TOP BAR CHUẨN FLATSOME (Không hiển thị tùy chọn UX Builder) -->
  <div id="top-bar" class="bg-brand-dark text-white text-xs py-1.5 border-b border-white/10">
    <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-3 overflow-hidden">
        <span class="font-semibold tracking-wide truncate">
          <i class="fa-solid fa-building-columns text-amber-400 mr-1"></i>
          CÔNG TY TNHH VÂN NHI TÚY LOAN - TỔNG KHO GẠCH MEN & TBVS ĐÀ NẴNG
        </span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-[11.5px] text-slate-200">
        <span class="cat-nowrap"><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</span>
        <span class="text-white/30">|</span>
        <span class="cat-nowrap"><i class="fa-regular fa-clock text-amber-400 mr-1"></i>07:00 - 17:30 (T2 - CN)</span>
        <span class="text-white/30">|</span>
        <a href="https://www.facebook.com/vannhiceramic" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition cat-nowrap">
          <i class="fa-brands fa-facebook mr-1"></i>fb.com/vannhiceramic
        </a>
      </div>
    </div>
  </div>

  <!-- HEADER CHÍNH (Logo chỉnh gọn nhỏ lại, không để nút gọi ngay trên header tránh tràn viền) -->
  <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
    <div class="container-1500 py-2.5 flex items-center justify-between gap-3">
      
      <!-- Nút mở menu trên điện thoại -->
      <button onclick="toggleMobileMenu()" aria-label="Menu danh mục" class="lg:hidden p-2 rounded border border-slate-200 text-brand hover:bg-slate-50 shrink-0">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>

      <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
      <a href="#" class="flex items-center gap-2.5 shrink-0 min-w-0">
        <img 
          src="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m" 
          onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m&sz=w300';"
          alt="Logo Công Ty TNHH Vân Nhi Túy Loan" 
          class="h-9 sm:h-10 w-auto object-contain rounded border border-slate-100 p-0.5 bg-white shrink-0"
        >
        <div class="min-w-0">
          <div class="text-brand font-extrabold text-xs sm:text-sm md:text-base leading-tight tracking-tight truncate">
            VÂN NHI TÚY LOAN
          </div>
          <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium truncate">
            vannhi.vn - Gạch Men & TBVS Đà Nẵng
          </div>
        </div>
      </a>

      <!-- Ô tìm kiếm sản phẩm giống Flatsome -->
      <div class="hidden md:flex flex-1 max-w-xl mx-4">
        <div class="relative flex w-full">
          <input 
            id="searchInputDesktop"
            type="text" 
            oninput="handleSearchProducts(this.value)"
            placeholder="Tìm gạch lát nền 60x60, 80x80, gạch ốp tường, gạch khổ lớn, thiết bị vệ sinh..." 
            class="w-full pl-3.5 pr-10 py-2 text-xs sm:text-sm border border-slate-300 rounded-l focus:outline-none focus:border-brand bg-slate-50/60"
          >
          <button onclick="handleSearchProducts(document.getElementById('searchInputDesktop').value)" class="bg-brand hover:bg-brand-dark text-white px-4 rounded-r text-sm transition">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>

      <!-- Khu vực thông tin phụ gọn gàng bên phải (Không đặt nút gọi ngay để tránh tràn viền) -->
      <div class="flex items-center gap-2 shrink-0">
        <a href="#bao-gia" class="text-xs font-semibold text-brand border border-brand/30 bg-brand/5 hover:bg-brand hover:text-white px-2.5 py-1.5 rounded transition cat-nowrap">
          <i class="fa-regular fa-file-lines mr-1"></i>Nhận Báo Giá
        </a>
        <a href="#ban-do" class="hidden sm:inline-flex text-xs font-semibold text-slate-700 border border-slate-200 hover:border-brand hover:text-brand px-2.5 py-1.5 rounded transition cat-nowrap">
          <i class="fa-solid fa-map-location-dot text-brand-accent mr-1"></i>Chỉ Đường
        </a>
      </div>
    </div>

    <!-- Ô tìm kiếm trên điện thoại -->
    <div class="md:hidden container-1500 pb-2">
      <div class="relative flex w-full">
        <input 
          id="searchInputMobile"
          type="text" 
          oninput="handleSearchProducts(this.value)"
          placeholder="Tìm kiếm mẫu gạch, thiết bị vệ sinh..." 
          class="w-full pl-3 pr-9 py-1.5 text-xs border border-slate-300 rounded-l focus:outline-none focus:border-brand bg-slate-50"
        >
        <button onclick="handleSearchProducts(document.getElementById('searchInputMobile').value)" class="bg-brand text-white px-3 rounded-r text-xs">
          <i class="fa-solid fa-magnifying-glass"></i>
        </button>
      </div>
    </div>

    <!-- THANH MENU DANH MỤC MÁY TÍNH: Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm, không bao giờ đứt dòng tên danh mục -->
    <nav class="hidden lg:block bg-brand text-white border-t border-brand-dark">
      <div class="container-1500">
        <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-0.5 py-1 text-[12px] font-semibold tracking-tight">
          <li>
            <a href="#" onclick="filterCategory('all'); return false;" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition bg-white/10">
              <i class="fa-solid fa-house mr-1.5 text-amber-300"></i>TRANG CHỦ
            </a>
          </li>

          <!-- GẠCH LÁT NỀN -->
          <li class="relative nav-item-has-dropdown">
            <a href="#san-pham" onclick="filterCategory('GẠCH LÁT NỀN')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">
              GẠCH LÁT NỀN <i class="fa-solid fa-chevron-down text-[9px] ml-1 opacity-80"></i>
            </a>
            <div class="nav-dropdown hidden absolute left-0 top-full w-48 bg-white text-slate-800 shadow-lg rounded-b border border-slate-200 py-1 z-50">
              <a href="#san-pham" onclick="filterCategory('GẠCH 60X60')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 60X60</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 80X80')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 80X80</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 100X100')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 100X100</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 120X120')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 120X120</a>
            </div>
          </li>

          <!-- GẠCH ỐP TƯỜNG -->
          <li class="relative nav-item-has-dropdown">
            <a href="#san-pham" onclick="filterCategory('GẠCH ỐP TƯỜNG')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">
              GẠCH ỐP TƯỜNG <i class="fa-solid fa-chevron-down text-[9px] ml-1 opacity-80"></i>
            </a>
            <div class="nav-dropdown hidden absolute left-0 top-full w-48 bg-white text-slate-800 shadow-lg rounded-b border border-slate-200 py-1 z-50">
              <a href="#san-pham" onclick="filterCategory('GẠCH 30X60')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 30X60</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 60X120')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 60X120</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 80X160')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 80X160</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 75X150')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 75X150</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 90X180')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 90X180</a>
            </div>
          </li>

          <!-- GẠCH KHỔ LỚN -->
          <li class="relative nav-item-has-dropdown">
            <a href="#san-pham" onclick="filterCategory('GẠCH KHỔ LỚN')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">
              GẠCH KHỔ LỚN <i class="fa-solid fa-chevron-down text-[9px] ml-1 opacity-80"></i>
            </a>
            <div class="nav-dropdown hidden absolute left-0 top-full w-52 bg-white text-slate-800 shadow-lg rounded-b border border-slate-200 py-1 z-50">
              <a href="#san-pham" onclick="filterCategory('GẠCH 1600X3200')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 1600X3200</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 1200X2400')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 1200X2400</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 1200X2800')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 1200X2800</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH 1200X1800')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH 1200X1800</a>
            </div>
          </li>

          <!-- GẠCH TRANG TRÍ -->
          <li class="relative nav-item-has-dropdown">
            <a href="#san-pham" onclick="filterCategory('GẠCH TRANG TRÍ')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">
              GẠCH TRANG TRÍ <i class="fa-solid fa-chevron-down text-[9px] ml-1 opacity-80"></i>
            </a>
            <div class="nav-dropdown hidden absolute left-0 top-full w-48 bg-white text-slate-800 shadow-lg rounded-b border border-slate-200 py-1 z-50">
              <a href="#san-pham" onclick="filterCategory('GẠCH TERRAZZO')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH TERRAZZO</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH GIẢ GỖ')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH GIẢ GỖ</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH MOSAIC')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH MOSAIC</a>
              <a href="#san-pham" onclick="filterCategory('GẠCH BÔNG')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">GẠCH BÔNG</a>
            </div>
          </li>

          <!-- THIẾT BỊ VỆ SINH -->
          <li class="relative nav-item-has-dropdown">
            <a href="#san-pham" onclick="filterCategory('THIẾT BỊ VỆ SINH')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">
              THIẾT BỊ VỆ SINH <i class="fa-solid fa-chevron-down text-[9px] ml-1 opacity-80"></i>
            </a>
            <div class="nav-dropdown hidden absolute left-0 top-full w-56 bg-white text-slate-800 shadow-lg rounded-b border border-slate-200 py-1 z-50">
              <a href="#san-pham" onclick="filterCategory('TỦ LAVABO')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">TỦ LAVABO</a>
              <a href="#san-pham" onclick="filterCategory('BỒN CẦU')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">BỒN CẦU</a>
              <a href="#san-pham" onclick="filterCategory('VÒI SEN TẮM')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">VÒI SEN TẮM</a>
              <a href="#san-pham" onclick="filterCategory('COMBO THIẾT BỊ VỆ SINH')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">COMBO THIẾT BỊ VỆ SINH</a>
              <a href="#san-pham" onclick="filterCategory('PHỤ KIỆN NHÀ TẮM')" class="block px-3.5 py-1.5 text-xs hover:bg-slate-100 hover:text-brand cat-nowrap">PHỤ KIỆN NHÀ TẮM</a>
            </div>
          </li>

          <!-- CÁC MỤC CHÍNH KHÁC TRÊN CÙNG HÀNG HOẶC XUỐNG HÀNG 2 NGUYÊN CỤM -->
          <li><a href="#san-pham" onclick="filterCategory('GẠCH 60X120')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">GẠCH 60X120</a></li>
          <li><a href="#san-pham" onclick="filterCategory('GẠCH 80X160')" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">GẠCH 80X160</a></li>
          <li><a href="#cong-trinh" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">CÔNG TRÌNH ĐÀ NẴNG</a></li>
          <li><a href="#doi-tac" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">ĐỐI TÁC</a></li>
          <li><a href="#bai-viet" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">BÀI VIẾT</a></li>
          <li><a href="#bao-gia" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">BÁO GIÁ</a></li>
          <li><a href="#ban-do" class="cat-nowrap inline-flex items-center px-2.5 py-1.5 rounded hover:bg-white/15 transition">LIÊN HỆ</a></li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- MENU DRAWER CHO ĐIỆN THOẠI -->
  <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/50 z-50 hidden"></div>
  <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="p-3.5 bg-brand text-white flex items-center justify-between">
      <div class="flex items-center gap-2">
        <img src="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m" alt="Logo" class="h-8 w-auto bg-white rounded p-0.5">
        <span class="font-bold text-xs cat-nowrap">VÂN NHI TÚY LOAN</span>
      </div>
      <button onclick="toggleMobileMenu()" class="text-white p-1.5 hover:bg-white/10 rounded">
        <i class="fa-solid fa-xmark text-lg"></i>
      </button>
    </div>
    <div class="p-3 overflow-y-auto flex-1 divide-y divide-slate-100 text-xs font-semibold text-slate-700">
      <a href="#" onclick="filterCategory('all'); toggleMobileMenu(); return false;" class="block py-2.5 text-brand">TRANG CHỦ</a>
      <a href="#san-pham" onclick="filterCategory('GẠCH LÁT NỀN'); toggleMobileMenu();" class="block py-2.5">GẠCH LÁT NỀN (60x60, 80x80, 100x100)</a>
      <a href="#san-pham" onclick="filterCategory('GẠCH ỐP TƯỜNG'); toggleMobileMenu();" class="block py-2.5">GẠCH ỐP TƯỜNG (30x60, 60x120, 80x160)</a>
      <a href="#san-pham" onclick="filterCategory('GẠCH KHỔ LỚN'); toggleMobileMenu();" class="block py-2.5">GẠCH KHỔ LỚN (1200x2400, 1600x3200)</a>
      <a href="#san-pham" onclick="filterCategory('GẠCH TRANG TRÍ'); toggleMobileMenu();" class="block py-2.5">GẠCH TRANG TRÍ (Terrazzo, Giả Gỗ, Mosaic)</a>
      <a href="#san-pham" onclick="filterCategory('THIẾT BỊ VỆ SINH'); toggleMobileMenu();" class="block py-2.5">THIẾT BỊ VỆ SINH ĐÀ NẴNG</a>
      <a href="#cong-trinh" onclick="toggleMobileMenu();" class="block py-2.5">CÔNG TRÌNH THỰC TẾ ĐÀ NẴNG</a>
      <a href="#doi-tac" onclick="toggleMobileMenu();" class="block py-2.5">ĐỐI TÁC PHÂN PHỐI</a>
      <a href="#bai-viet" onclick="toggleMobileMenu();" class="block py-2.5">TIN TỨC & BÀI VIẾT</a>
      <a href="#bao-gia" onclick="toggleMobileMenu();" class="block py-2.5">YÊU CẦU & BÁO GIÁ</a>
      <a href="#ban-do" onclick="toggleMobileMenu();" class="block py-2.5">BẢN ĐỒ & FANPAGE</a>
    </div>
    <div class="p-3 bg-slate-50 border-t border-slate-200 text-xs">
      <div class="font-bold text-brand mb-1">HOTLINE TƯ VẤN:</div>
      <a href="tel:0905567811" class="block font-bold text-red-600 py-0.5">0905.567.811</a>
      <a href="tel:0934999429" class="block font-bold text-red-600 py-0.5">0934.999.429</a>
    </div>
  </aside>

  <!-- =====================================================================
       2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       - Tách riêng thiết kế Banner Máy Tính (hidden md:block) và Banner Điện Thoại (block md:hidden)
       - Tối ưu chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền
  ====================================================================== -->
  <section class="py-3 bg-white border-b border-slate-200">
    <div class="container-1500">
      <div class="relative w-full overflow-hidden rounded-lg shadow-sm border border-slate-200 bg-brand-dark">

        <!-- ================= SLIDE 1 ================= -->
        <div id="banner-slide-0" class="banner-slide transition-opacity duration-500 opacity-100 block">
          
          <!-- 1A. BANNER MÁY TÍNH SLIDE 1 (Cố định chiều cao 390px bằng nhau) -->
          <div class="hidden md:grid md:grid-cols-12 w-full h-[390px] bg-gradient-to-r from-[#0a2547] via-[#134686] to-[#1a569e] relative overflow-hidden">
            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 z-10 text-white">
              <div class="inline-flex items-center gap-2 bg-amber-400/20 border border-amber-300/40 text-amber-300 text-xs font-bold px-3 py-1 rounded w-fit mb-2.5 cat-nowrap">
                CÔNG TY TNHH VÂN NHI TÚY LOAN - VANNHI.VN
              </div>
              <h1 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white mb-2 uppercase">
                TỔNG KHO GẠCH ỐP LÁT & THIẾT BỊ VỆ SINH CAO CẤP TẠI ĐÀ NẴNG
              </h1>
              <p class="text-xs lg:text-sm text-slate-100 leading-relaxed mb-4 max-w-xl">
                Chuyên phân phối Gạch lát nền 60x60, 80x80, 100x100, Gạch ốp tường 30x60, 60x120, Gạch khổ lớn, Gạch trang trí & Thiết bị vệ sinh chính hãng giá sỉ tận kho.
              </p>
              <div class="flex flex-wrap items-center gap-2.5 text-xs">
                <span class="bg-white/10 border border-white/20 px-3 py-1.5 rounded font-medium cat-nowrap">
                  <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng
                </span>
                <span class="bg-brand-accent text-white px-3 py-1.5 rounded font-bold cat-nowrap">
                  <i class="fa-solid fa-phone-volume mr-1"></i>0905.567.811 - 0934.999.429
                </span>
              </div>
            </div>
            <div class="col-span-5 relative h-[390px] p-4 flex items-center justify-center">
              <div class="w-full h-full rounded-lg overflow-hidden border-2 border-white/30 shadow-lg relative">
                <img 
                  src="https://lh3.googleusercontent.com/d/1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6" 
                  onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6&sz=w1000';"
                  alt="Cửa hàng VLXD & Gạch Men Vân Nhi Túy Loan" 
                  class="w-full h-full object-cover"
                >
                <div class="absolute bottom-2 left-2 right-2 bg-black/65 backdrop-blur-sm text-white text-[11px] px-2.5 py-1 rounded text-center truncate">
                  Showroom Vân Nhi Túy Loan - Đường Quảng Xương, Hòa Vang, Đà Nẵng
                </div>
              </div>
            </div>
          </div>

          <!-- 1B. BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế riêng cho màn hình điện thoại, chữ nhỏ gọn nằm trọn bên trong) -->
          <div class="flex md:hidden flex-col justify-between w-full h-[270px] bg-gradient-to-b from-[#0c2d57] to-[#134686] p-3.5 text-white relative overflow-hidden">
            <div class="flex items-center gap-2.5">
              <img 
                src="https://lh3.googleusercontent.com/d/1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6" 
                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6&sz=w600';"
                alt="Showroom Vân Nhi" 
                class="w-20 h-20 object-cover rounded border border-white/40 shrink-0"
              >
              <div class="min-w-0 flex-1">
                <div class="text-[10px] font-bold text-amber-300 uppercase leading-tight mb-0.5">
                  CÔNG TY TNHH VÂN NHI TÚY LOAN
                </div>
                <h2 class="text-[13px] font-extrabold leading-snug text-white uppercase">
                  TỔNG KHO GẠCH MEN & THIẾT BỊ VỆ SINH ĐÀ NẴNG
                </h2>
                <p class="text-[11px] text-slate-200 leading-tight mt-1">
                  Gạch Lát Nền • Gạch Ốp Tường • Gạch Khổ Lớn
                </p>
              </div>
            </div>
            <div class="bg-white/10 rounded p-2 text-[11px] leading-snug border border-white/15">
              <div class="truncate"><i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</div>
              <div class="font-bold text-amber-300 mt-0.5"><i class="fa-solid fa-phone mr-1"></i>0905.567.811 - 0934.999.429</div>
            </div>
            <div class="flex items-center justify-between text-[10px] text-slate-200 pt-0.5">
              <span>Website: vannhi.vn</span>
              <span class="bg-brand-accent text-white px-2 py-0.5 rounded font-semibold">Chiết khấu cao cho công trình</span>
            </div>
          </div>

        </div>

        <!-- ================= SLIDE 2 ================= -->
        <div id="banner-slide-1" class="banner-slide transition-opacity duration-500 opacity-0 hidden">
          
          <!-- 2A. BANNER MÁY TÍNH SLIDE 2 (Cố định chiều cao 390px bằng nhau với Slide 1) -->
          <div class="hidden md:grid md:grid-cols-12 w-full h-[390px] bg-gradient-to-r from-[#143763] via-[#0f3e78] to-[#0a2547] relative overflow-hidden">
            <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 z-10 text-white">
              <div class="inline-flex items-center gap-2 bg-red-500/30 border border-red-300/40 text-amber-200 text-xs font-bold px-3 py-1 rounded w-fit mb-2.5 cat-nowrap">
                MẪU GẠCH MỚI NHẤT 2026 - CHIẾT KHẤU ĐẾN 25%
              </div>
              <h2 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white mb-2 uppercase">
                GẠCH KHỔ LỚN 60X120, 80X160, 1200X2400 & THIẾT BỊ PHÒNG TẮM
              </h2>
              <p class="text-xs lg:text-sm text-slate-100 leading-relaxed mb-4 max-w-xl">
                Đa dạng mẫu gạch vân đá Marble, gạch giả gỗ, gạch Terrazzo, Mosaic và trọn bộ thiết bị vệ sinh cao cấp cho nhà phố, biệt thự, khách sạn tại Đà Nẵng.
              </p>
              <div class="flex flex-wrap items-center gap-2.5 text-xs">
                <span class="bg-white/10 border border-white/20 px-3 py-1.5 rounded font-medium cat-nowrap">
                  <i class="fa-solid fa-truck-fast text-amber-400 mr-1"></i>Giao hàng tận chân công trình Đà Nẵng
                </span>
                <span class="bg-amber-500 text-slate-950 px-3 py-1.5 rounded font-bold cat-nowrap">
                  <i class="fa-solid fa-headset mr-1"></i>Tư vấn & Báo giá: 0905.567.811
                </span>
              </div>
            </div>
            <div class="col-span-5 relative h-[390px] p-4 grid grid-cols-2 gap-2.5 items-center">
              <div class="h-[340px] rounded-lg overflow-hidden border-2 border-white/30 shadow-md">
                <img 
                  src="https://lh3.googleusercontent.com/d/1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak" 
                  onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak&sz=w800';"
                  alt="Sản phẩm thực tế Vân Nhi 1" 
                  class="w-full h-full object-cover"
                >
              </div>
              <div class="h-[340px] rounded-lg overflow-hidden border-2 border-white/30 shadow-md">
                <img 
                  src="https://lh3.googleusercontent.com/d/1OdF6gqej6dCfjOqaMf7atJxYrfRcD_5R" 
                  onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1OdF6gqej6dCfjOqaMf7atJxYrfRcD_5R&sz=w800';"
                  alt="Sản phẩm thực tế Vân Nhi 2" 
                  class="w-full h-full object-cover"
                >
              </div>
            </div>
          </div>

          <!-- 2B. BANNER ĐIỆN THOẠI SLIDE 2 (Kích thước h-[270px] bằng đúng Slide 1 điện thoại, chữ gọn trong khung) -->
          <div class="flex md:hidden flex-col justify-between w-full h-[270px] bg-gradient-to-b from-[#134686] to-[#0a2547] p-3.5 text-white relative overflow-hidden">
            <div class="flex items-center gap-2.5">
              <img 
                src="https://lh3.googleusercontent.com/d/1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak" 
                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak&sz=w600';"
                alt="Mẫu gạch thực tế" 
                class="w-20 h-20 object-cover rounded border border-white/40 shrink-0"
              >
              <div class="min-w-0 flex-1">
                <div class="text-[10px] font-bold text-amber-300 uppercase leading-tight mb-0.5">
                  MẪU GẠCH MỚI NHẤT 2026
                </div>
                <h2 class="text-[13px] font-extrabold leading-snug text-white uppercase">
                  GẠCH KHỔ LỚN 60X120, 80X160 & THIẾT BỊ VỆ SINH
                </h2>
                <p class="text-[11px] text-slate-200 leading-tight mt-1">
                  Ưu đãi giảm giá từ 15% - 25% tại Showroom
                </p>
              </div>
            </div>
            <div class="bg-white/10 rounded p-2 text-[11px] leading-snug border border-white/15">
              <div class="truncate"><i class="fa-solid fa-check-circle text-amber-300 mr-1"></i>Hàng chính hãng loại 1 - Giao nhanh tại Đà Nẵng</div>
              <div class="font-bold text-amber-300 mt-0.5"><i class="fa-solid fa-phone mr-1"></i>Hotline: 0905.567.811 - 0934.999.429</div>
            </div>
            <div class="flex items-center justify-between text-[10px] text-slate-200 pt-0.5">
              <span>Đ/c: Quảng Xương, Hòa Vang</span>
              <span class="bg-amber-500 text-slate-950 px-2 py-0.5 rounded font-bold">Báo giá sỉ & lẻ</span>
            </div>
          </div>

        </div>

        <!-- Nút chuyển trái/phải và chấm tròn trượt Banner -->
        <button onclick="changeBanner(-1)" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20 transition">
          <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
        </button>
        <button onclick="changeBanner(1)" aria-label="Banner tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20 transition">
          <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
          <button id="banner-dot-0" onclick="goToBanner(0)" aria-label="Slide 1" class="w-2.5 h-2.5 rounded-full bg-amber-400 transition-all"></button>
          <button id="banner-dot-1" onclick="goToBanner(1)" aria-label="Slide 2" class="w-2.5 h-2.5 rounded-full bg-white/50 transition-all"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       DANH MỤC SẢN PHẨM TRANG CHỦ (Giống mẫu gachmendanang.vn - Flatsome)
       - Thiết kế tối ưu trên cả máy tính và điện thoại
       - Chữ danh mục nhỏ gọn, viết liền trên 1 hàng (cat-nowrap), không bị đứt dòng
  ====================================================================== -->
  <section class="py-5 bg-white border-b border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-sm sm:text-base md:text-lg">
            DANH MỤC SẢN PHẨM
          </h2>
          <span class="text-xs text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>
      </div>

      <!-- Khối Danh Mục Chính chia cột chuẩn Flatsome (2 cột trên điện thoại, 6 cột trên máy tính) -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3 mb-4">
        
        <!-- Danh mục 1: GẠCH LÁT NỀN -->
        <div onclick="filterCategory('GẠCH LÁT NỀN')" class="cursor-pointer group bg-slate-50 hover:bg-brand hover:text-white border border-slate-200 rounded-lg p-2.5 transition flex flex-col items-center text-center">
          <div class="w-full h-24 sm:h-28 rounded overflow-hidden mb-2 bg-white border border-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak&sz=w500';" alt="Gạch lát nền" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="cat-nowrap text-[12px] sm:text-[13px] font-bold text-brand group-hover:text-white">GẠCH LÁT NỀN</h3>
          <p class="cat-nowrap text-[10.5px] text-slate-500 group-hover:text-slate-200 mt-0.5">60x60 • 80x80 • 100x100</p>
        </div>

        <!-- Danh mục 2: GẠCH ỐP TƯỜNG -->
        <div onclick="filterCategory('GẠCH ỐP TƯỜNG')" class="cursor-pointer group bg-slate-50 hover:bg-brand hover:text-white border border-slate-200 rounded-lg p-2.5 transition flex flex-col items-center text-center">
          <div class="w-full h-24 sm:h-28 rounded overflow-hidden mb-2 bg-white border border-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1dc2fcG70o6i9F7R2jh_-oQeLhhBCc4Kx" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dc2fcG70o6i9F7R2jh_-oQeLhhBCc4Kx&sz=w500';" alt="Gạch ốp tường" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="cat-nowrap text-[12px] sm:text-[13px] font-bold text-brand group-hover:text-white">GẠCH ỐP TƯỜNG</h3>
          <p class="cat-nowrap text-[10.5px] text-slate-500 group-hover:text-slate-200 mt-0.5">30x60 • 60x120 • 80x160</p>
        </div>

        <!-- Danh mục 3: GẠCH KHỔ LỚN -->
        <div onclick="filterCategory('GẠCH KHỔ LỚN')" class="cursor-pointer group bg-slate-50 hover:bg-brand hover:text-white border border-slate-200 rounded-lg p-2.5 transition flex flex-col items-center text-center">
          <div class="w-full h-24 sm:h-28 rounded overflow-hidden mb-2 bg-white border border-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1PwnmGEj3-LdlAWnghxaAjzE7_oP-zBV-" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1PwnmGEj3-LdlAWnghxaAjzE7_oP-zBV-&sz=w500';" alt="Gạch khổ lớn" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="cat-nowrap text-[12px] sm:text-[13px] font-bold text-brand group-hover:text-white">GẠCH KHỔ LỚN</h3>
          <p class="cat-nowrap text-[10.5px] text-slate-500 group-hover:text-slate-200 mt-0.5">1200x2400 • 1600x3200</p>
        </div>

        <!-- Danh mục 4: GẠCH TRANG TRÍ -->
        <div onclick="filterCategory('GẠCH TRANG TRÍ')" class="cursor-pointer group bg-slate-50 hover:bg-brand hover:text-white border border-slate-200 rounded-lg p-2.5 transition flex flex-col items-center text-center">
          <div class="w-full h-24 sm:h-28 rounded overflow-hidden mb-2 bg-white border border-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1V58uojvshVdrsCCgiFpzviO0y1R412Bu" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1V58uojvshVdrsCCgiFpzviO0y1R412Bu&sz=w500';" alt="Gạch trang trí" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="cat-nowrap text-[12px] sm:text-[13px] font-bold text-brand group-hover:text-white">GẠCH TRANG TRÍ</h3>
          <p class="cat-nowrap text-[10.5px] text-slate-500 group-hover:text-slate-200 mt-0.5">Terrazzo • Giả Gỗ • Mosaic</p>
        </div>

        <!-- Danh mục 5: THIẾT BỊ VỆ SINH -->
        <div onclick="filterCategory('THIẾT BỊ VỆ SINH')" class="cursor-pointer group bg-slate-50 hover:bg-brand hover:text-white border border-slate-200 rounded-lg p-2.5 transition flex flex-col items-center text-center">
          <div class="w-full h-24 sm:h-28 rounded overflow-hidden mb-2 bg-white border border-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1dYi-rm1ESinh_JzOkupdSgLArBauR4Y7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dYi-rm1ESinh_JzOkupdSgLArBauR4Y7&sz=w500';" alt="Thiết bị vệ sinh" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="cat-nowrap text-[12px] sm:text-[13px] font-bold text-brand group-hover:text-white">THIẾT BỊ VỆ SINH</h3>
          <p class="cat-nowrap text-[10.5px] text-slate-500 group-hover:text-slate-200 mt-0.5">Bồn Cầu • Lavabo • Sen Tắm</p>
        </div>

        <!-- Danh mục 6: CÔNG TRÌNH ĐÀ NẴNG -->
        <a href="#cong-trinh" class="cursor-pointer group bg-slate-50 hover:bg-brand hover:text-white border border-slate-200 rounded-lg p-2.5 transition flex flex-col items-center text-center">
          <div class="w-full h-24 sm:h-28 rounded overflow-hidden mb-2 bg-white border border-slate-100">
            <img src="https://lh3.googleusercontent.com/d/1IVJi0fliWvL09tfUtBIHj-VJKvja-SBp" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1IVJi0fliWvL09tfUtBIHj-VJKvja-SBp&sz=w500';" alt="Công trình Đà Nẵng" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
          </div>
          <h3 class="cat-nowrap text-[12px] sm:text-[13px] font-bold text-brand group-hover:text-white">CÔNG TRÌNH ĐÀ NẴNG</h3>
          <p class="cat-nowrap text-[10.5px] text-slate-500 group-hover:text-slate-200 mt-0.5">7 Dự án tiêu biểu thực tế</p>
        </a>

      </div>

      <!-- Dải danh mục kích thước chi tiết giống gachmendanang.vn (Chữ nhỏ gọn, viết liền trên 1 hàng hoặc tự xuống dòng 2 nguyên nút, không gãy chữ) -->
      <div class="bg-slate-50 border border-slate-200 rounded-lg p-2.5">
        <div class="flex flex-wrap items-center gap-1.5">
          <button onclick="filterCategory('all')" class="cat-pill active-cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-semibold bg-brand text-white transition">
            TẤT CẢ SẢN PHẨM
          </button>
          <button onclick="filterCategory('GẠCH 60X60')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 60X60
          </button>
          <button onclick="filterCategory('GẠCH 80X80')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 80X80
          </button>
          <button onclick="filterCategory('GẠCH 100X100')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 100X100
          </button>
          <button onclick="filterCategory('GẠCH 120X120')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 120X120
          </button>
          <button onclick="filterCategory('GẠCH 30X60')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 30X60
          </button>
          <button onclick="filterCategory('GẠCH 60X120')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 60X120
          </button>
          <button onclick="filterCategory('GẠCH 80X160')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 80X160
          </button>
          <button onclick="filterCategory('GẠCH 1200X2400')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 1200X2400
          </button>
          <button onclick="filterCategory('GẠCH 1600X3200')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH 1600X3200
          </button>
          <button onclick="filterCategory('GẠCH TERRAZZO')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH TERRAZZO
          </button>
          <button onclick="filterCategory('GẠCH GIẢ GỖ')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH GIẢ GỖ
          </button>
          <button onclick="filterCategory('GẠCH MOSAIC')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            GẠCH MOSAIC
          </button>
          <button onclick="filterCategory('THIẾT BỊ VỆ SINH')" class="cat-pill cat-nowrap px-2.5 py-1 rounded text-[11.5px] font-medium bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">
            THIẾT BỊ VỆ SINH
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       DANH SÁCH SẢN PHẨM THỰC TẾ TRANG CHỦ (11 Ảnh thực tế từ Google Drive)
       - Điện thoại chia đúng 2 cột (grid-cols-2)
       - Góc trên bên trái có % giảm giá chuẩn Flatsome (-23%, -21%,...)
       - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài và không bị cắt chữ
       - Không để các nhãn dán rườm rà khác ở trang chủ
  ====================================================================== -->
  <section id="san-pham" class="py-6">
    <div class="container-1500">
      
      <!-- Khối hiển thị kết quả lọc hoặc Tất cả sản phẩm thực tế -->
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 id="currentCategoryTitle" class="section-title-main text-sm sm:text-base md:text-lg">
            SẢN PHẨM THỰC TẾ TẠI SHOWROOM VÂN NHI
          </h2>
          <button onclick="filterCategory('all')" class="text-xs font-semibold text-brand hover:underline cat-nowrap">
            Xem tất cả (11 mẫu thực tế) <i class="fa-solid fa-angle-right ml-0.5"></i>
          </button>
        </div>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4 cột laptop, 5 cột màn hình 1500px -->
      <div id="productGrid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
        <!-- Được render tự động từ mảng 11 sản phẩm thực tế bên dưới -->
      </div>

      <!-- PHÂN NHÓM THEO MẪU GACHMENDANANG.VN TRÊN TRANG CHỦ -->
      <div class="mt-8 space-y-8">
        
        <!-- Nhóm 1: GẠCH LÁT NỀN & GẠCH ỐP TƯỜNG (60X60, 80X80, 60X120) -->
        <div>
          <div class="section-title-container">
            <div class="section-title-normal">
              <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                GẠCH LÁT NỀN & GẠCH ỐP TƯỜNG (60X60, 80X80, 60X120)
              </h2>
              <button onclick="filterCategory('GẠCH LÁT NỀN')" class="text-xs font-semibold text-brand hover:underline cat-nowrap">
                Xem thêm <i class="fa-solid fa-angle-right"></i>
              </button>
            </div>
          </div>
          <div id="groupGrid1" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
        </div>

        <!-- Nhóm 2: GẠCH KHỔ LỚN & GẠCH TRANG TRÍ CAO CẤP (80X160, 1200X2400, TERRAZZO, MOSAIC) -->
        <div>
          <div class="section-title-container">
            <div class="section-title-normal">
              <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                GẠCH KHỔ LỚN & GẠCH TRANG TRÍ (80X160, 1200X2400, GIẢ GỖ, MOSAIC)
              </h2>
              <button onclick="filterCategory('GẠCH KHỔ LỚN')" class="text-xs font-semibold text-brand hover:underline cat-nowrap">
                Xem thêm <i class="fa-solid fa-angle-right"></i>
              </button>
            </div>
          </div>
          <div id="groupGrid2" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
        </div>

        <!-- Nhóm 3: THIẾT BỊ VỆ SINH & PHỤ KIỆN PHÒNG TẮM ĐÀ NẴNG -->
        <div>
          <div class="section-title-container">
            <div class="section-title-normal">
              <h2 class="section-title-main text-sm sm:text-base md:text-lg">
                THIẾT BỊ VỆ SINH & PHỤ KIỆN NHÀ TẮM ĐÀ NẴNG
              </h2>
              <button onclick="filterCategory('THIẾT BỊ VỆ SINH')" class="text-xs font-semibold text-brand hover:underline cat-nowrap">
                Xem thêm <i class="fa-solid fa-angle-right"></i>
              </button>
            </div>
          </div>
          <div id="groupGrid3" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-3 gap-2.5 sm:gap-4"></div>
        </div>

      </div>

    </div>
  </section>

  <!-- =====================================================================
       DANH MỤC CÁC CÔNG TRÌNH Ở ĐÀ NẴNG (7 Ảnh công trình thực tế từ Google Drive)
  ====================================================================== -->
  <section id="cong-trinh" class="py-6 bg-white border-t border-b border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-sm sm:text-base md:text-lg">
            DANH MỤC CÁC CÔNG TRÌNH THỰC TẾ TẠI ĐÀ NẴNG
          </h2>
          <span class="text-xs text-slate-500 hidden sm:inline">Cung cấp gạch ốp lát & thiết bị vệ sinh trọn gói tại Đà Nẵng</span>
        </div>
      </div>

      <!-- Điện thoại chia 2 cột, máy tính chia 4 cột gọn đẹp -->
      <div id="projectsGrid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
        <!-- Render từ 7 ảnh công trình thực tế -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       GIỚI THIỆU CỬA HÀNG VÂN NHI TÚY LOAN & TẠI SAO CHỌN CHÚNG TÔI (Giống cấu trúc gachmendanang.vn)
  ====================================================================== -->
  <section class="py-6">
    <div class="container-1500">
      <div class="bg-white border border-slate-200 rounded-lg p-4 sm:p-6">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
          <div class="lg:col-span-5">
            <div class="rounded-lg overflow-hidden border border-slate-200 shadow-sm">
              <img 
                src="https://lh3.googleusercontent.com/d/1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6" 
                onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6&sz=w1000';"
                alt="Showroom Công ty TNHH Vân Nhi Túy Loan Đà Nẵng" 
                class="w-full h-64 sm:h-80 object-cover"
              >
            </div>
          </div>
          <div class="lg:col-span-7 space-y-3">
            <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-brand uppercase">
              CÔNG TY TNHH VÂN NHI TÚY LOAN – TỔNG KHO GẠCH MEN & THIẾT BỊ VỆ SINH ĐÀ NẴNG
            </h2>
            <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
              <strong>CÔNG TY TNHH VÂN NHI TÚY LOAN</strong> (<a href="https://vannhi.vn" class="text-brand font-semibold hover:underline">vannhi.vn</a>) là đơn vị uy tín hàng đầu chuyên cung cấp gạch lát nền, gạch ốp tường, gạch trang trí, gạch khổ lớn cao cấp và thiết bị vệ sinh chính hãng tại Đà Nẵng và khu vực miền Trung.
            </p>
            <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
              Với showroom trưng bày quy mô tại <strong>Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</strong>, chúng tôi đáp ứng đầy đủ số lượng, kích thước và mẫu mã mới nhất cho nhà phố, biệt thự, căn hộ, khách sạn và các dự án xây dựng lớn nhỏ.
            </p>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs">
              <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                <div class="font-bold text-brand mb-0.5"><i class="fa-solid fa-medal text-brand-accent mr-1.5"></i>Chất Lượng Chính Hãng Loại 1</div>
                <p class="text-slate-600">Độ bền cao, chống thấm, chống trầy xước, màu men sắc nét bền vững theo thời gian.</p>
              </div>
              <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                <div class="font-bold text-brand mb-0.5"><i class="fa-solid fa-tags text-brand-accent mr-1.5"></i>Giá Kho Cạnh Tranh & Ưu Đãi</div>
                <p class="text-slate-600">Chiết khấu trực tiếp từ 15% - 25%, miễn phí vận chuyển nội thành và hỗ trợ giao hàng tận công trình.</p>
              </div>
            </div>
            <div class="pt-1 text-xs sm:text-sm font-semibold text-slate-800 space-y-1">
              <div><i class="fa-solid fa-location-dot text-brand-accent mr-1.5"></i>Địa chỉ: Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</div>
              <div><i class="fa-solid fa-phone-volume text-brand-accent mr-1.5"></i>Điện thoại: <a href="tel:0905567811" class="text-brand-accent font-bold">0905.567.811</a> - <a href="tel:0934999429" class="text-brand-accent font-bold">0934.999.429</a></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ
  ====================================================================== -->
  <section id="bao-gia" class="py-6 bg-white border-t border-b border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-sm sm:text-base md:text-lg">
            ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ CÔNG TRÌNH
          </h2>
          <span class="text-xs text-slate-500 hidden sm:inline">Phản hồi nhanh trong 5 phút qua Điện thoại / Zalo</span>
        </div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 bg-slate-50 border border-slate-200 rounded-lg p-4 sm:p-6">
        <div class="lg:col-span-5 flex flex-col justify-between space-y-4">
          <div>
            <h3 class="text-sm sm:text-base font-bold text-brand uppercase mb-2">
              NHẬN BẢNG GIÁ GẠCH MEN & THIẾT BỊ VỆ SINH MỚI NHẤT 2026
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-3">
              Quý khách hàng, chủ nhà, nhà thầu xây dựng và kiến trúc sư cần báo giá chi tiết theo khối lượng công trình vui lòng điền thông tin bên cạnh. Bộ phận kinh doanh của <strong>Vân Nhi Túy Loan</strong> sẽ gửi mẫu thực tế và bảng giá chiết khấu tốt nhất.
            </p>
            <ul class="space-y-2 text-xs text-slate-700">
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-green-600"></i> Tư vấn phối màu gạch 3D phù hợp không gian nội thất</li>
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-green-600"></i> Báo giá sỉ tận gốc cho nhà thầu & công trình dân dụng</li>
              <li class="flex items-center gap-2"><i class="fa-solid fa-check text-green-600"></i> Hỗ trợ vận chuyển nhanh chóng tận chân công trình tại Đà Nẵng</li>
            </ul>
          </div>
          <div class="bg-white p-3.5 rounded border border-slate-200 text-xs space-y-1.5">
            <div class="font-bold text-brand uppercase">LIÊN HỆ TRỰC TIẾP PHÒNG KINH DOANH:</div>
            <div><i class="fa-solid fa-phone text-brand-accent mr-1.5"></i>Hotline 1: <a href="tel:0905567811" class="font-bold text-brand-accent">0905.567.811</a></div>
            <div><i class="fa-solid fa-phone text-brand-accent mr-1.5"></i>Hotline 2: <a href="tel:0934999429" class="font-bold text-brand-accent">0934.999.429</a></div>
            <div><i class="fa-solid fa-location-dot text-brand mr-1.5"></i>Đ/c: Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</div>
          </div>
        </div>

        <div class="lg:col-span-7 bg-white p-4 sm:p-5 rounded-lg border border-slate-200 shadow-sm">
          <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand">
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục quan tâm</label>
                <select id="qCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand bg-white">
                  <option value="Gạch lát nền (60x60, 80x80, 100x100)">Gạch lát nền (60x60, 80x80, 100x100)</option>
                  <option value="Gạch ốp tường (30x60, 60x120, 80x160)">Gạch ốp tường (30x60, 60x120, 80x160)</option>
                  <option value="Gạch khổ lớn (1200x2400, 1600x3200)">Gạch khổ lớn (1200x2400, 1600x3200)</option>
                  <option value="Gạch trang trí (Terrazzo, Giả gỗ, Mosaic)">Gạch trang trí (Terrazzo, Giả gỗ, Mosaic)</option>
                  <option value="Trọn bộ Thiết bị vệ sinh">Trọn bộ Thiết bị vệ sinh</option>
                  <option value="Báo giá tổng thể toàn bộ công trình">Báo giá tổng thể toàn bộ công trình</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Địa điểm giao hàng / Công trình</label>
                <input id="qAddress" type="text" placeholder="VD: Hòa Vang, Cẩm Lệ, Hải Châu, Đà Nẵng..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand">
              </div>
            </div>

            <div>
              <label class="block text-xs font-semibold text-slate-700 mb-1">Ghi chú yêu cầu (Kích thước, diện tích m², mã sản phẩm...)</label>
              <textarea id="qNote" rows="3" placeholder="Nhập nhu cầu cụ thể của quý khách..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand"></textarea>
            </div>

            <button type="submit" class="w-full sm:w-auto bg-brand-accent hover:bg-red-700 text-white font-bold text-xs sm:text-sm px-6 py-2.5 rounded transition shadow-sm">
              <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       ĐƯA GOOGLE MAP VÀ FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
       - Địa chỉ: Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng
       - Map link: https://maps.app.goo.gl/7ekvgym6ehCJMmSZ9
       - Fanpage: https://www.facebook.com/vannhiceramic
  ====================================================================== -->
  <section id="ban-do" class="py-6">
    <div class="container-1500">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
        
        <!-- CỘT 1: BẢN ĐỒ GOOGLE MAPS TRỰC QUAN NGOÀI TRANG CHỦ (7 CỘT) -->
        <div class="lg:col-span-7 bg-white border border-slate-200 rounded-lg p-4 shadow-sm flex flex-col justify-between">
          <div>
            <div class="section-title-container">
              <div class="section-title-normal">
                <h2 class="section-title-main text-sm sm:text-base">
                  BẢN ĐỒ CHỈ ĐƯỜNG GOOGLE MAPS
                </h2>
                <a href="https://maps.app.goo.gl/7ekvgym6ehCJMmSZ9" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-brand-accent hover:underline cat-nowrap">
                  <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở ứng dụng Google Maps
                </a>
              </div>
            </div>

            <p class="text-xs text-slate-600 mb-3">
              <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>
              <strong>Showroom Công Ty TNHH Vân Nhi Túy Loan:</strong> Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng
            </p>

            <!-- Iframe Google Map thực tế + Khung thẻ bản đồ trực quan -->
            <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-200 mb-3 relative bg-slate-100">
              <iframe 
                title="Bản đồ Công ty TNHH Vân Nhi Túy Loan"
                src="https://www.google.com/maps?q=C%E1%BB%ADa+H%C3%A0ng+VLXD+V%C3%A2n+Nhi+Qu%E1%BA%A3ng+X%C6%B0%C6%A1ng+H%C3%B2a+Vang+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <div class="flex flex-wrap items-center justify-between gap-2 bg-slate-50 p-3 rounded border border-slate-200 text-xs">
            <div>
              <div class="font-bold text-brand">CÔNG TY TNHH VÂN NHI TÚY LOAN</div>
              <div class="text-slate-600">Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</div>
            </div>
            <a href="https://maps.app.goo.gl/7ekvgym6ehCJMmSZ9" target="_blank" rel="noopener noreferrer" class="bg-brand hover:bg-brand-dark text-white font-semibold px-3.5 py-2 rounded transition cat-nowrap">
              <i class="fa-solid fa-map-location-dot mr-1.5"></i>Xem Bản Đồ Lớn & Chỉ Đường
            </a>
          </div>
        </div>

        <!-- CỘT 2: FANPAGE FACEBOOK TRỰC TIẾP NGOÀI TRANG CHỦ (5 CỘT) -->
        <div class="lg:col-span-5 bg-white border border-slate-200 rounded-lg p-4 shadow-sm flex flex-col justify-between">
          <div>
            <div class="section-title-container">
              <div class="section-title-normal">
                <h2 class="section-title-main text-sm sm:text-base">
                  FANPAGE FACEBOOK CHÍNH THỨC
                </h2>
                <a href="https://www.facebook.com/vannhiceramic" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-blue-600 hover:underline cat-nowrap">
                  <i class="fa-brands fa-facebook mr-1"></i>Theo dõi Fanpage
                </a>
              </div>
            </div>

            <!-- Thẻ Fanpage trực quan kết hợp Plugin Facebook -->
            <div class="border border-slate-200 rounded-lg overflow-hidden mb-3">
              <div class="relative h-32 bg-brand-dark overflow-hidden">
                <img 
                  src="https://lh3.googleusercontent.com/d/1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6" 
                  onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KnONC1oBpD9ezNUT8anOWja1_KdPrtr6&sz=w800';"
                  alt="Ảnh bìa Fanpage Vân Nhi Ceramic" 
                  class="w-full h-full object-cover opacity-80"
                >
                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m" 
                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m&sz=w200';"
                    alt="Logo Vân Nhi" 
                    class="w-12 h-12 rounded-full border-2 border-white bg-white object-contain p-0.5 shrink-0"
                  >
                  <div class="text-white min-w-0">
                    <div class="font-bold text-sm truncate">Vân Nhi Ceramic - VLXD & TTNT</div>
                    <div class="text-[11px] text-slate-200 truncate">facebook.com/vannhiceramic</div>
                  </div>
                </div>
              </div>

              <!-- Nhúng Plugin Facebook Page chuẩn -->
              <div class="p-2 bg-slate-50 flex justify-center overflow-hidden">
                <iframe 
                  title="Fanpage Vân Nhi Ceramic"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fvannhiceramic&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                  width="340" 
                  height="180" 
                  style="border:none;overflow:hidden;max-width:100%;" 
                  scrolling="no" 
                  frameborder="0" 
                  allowfullscreen="true" 
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                </iframe>
              </div>
            </div>
          </div>

          <div class="flex flex-wrap items-center justify-between gap-2 bg-blue-50/70 p-3 rounded border border-blue-200 text-xs">
            <div class="text-slate-700">
              Cập nhật mẫu gạch mới & công trình thực tế mỗi ngày trên Fanpage
            </div>
            <a href="https://www.facebook.com/vannhiceramic" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white font-semibold px-3.5 py-2 rounded transition cat-nowrap">
              <i class="fa-brands fa-facebook-messenger mr-1.5"></i>Nhắn Tin Fanpage
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm chọn gạch)
  ====================================================================== -->
  <section id="bai-viet" class="py-6 bg-white border-t border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-sm sm:text-base md:text-lg">
            DANH MỤC BÀI VIẾT & KINH NGHIỆM CHỌN GẠCH ỐP LÁT
          </h2>
          <span class="text-xs text-slate-500 hidden sm:inline">Kiến thức xây dựng & xu hướng nội thất 2026</span>
        </div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        
        <!-- Bài viết 1 -->
        <article class="bg-slate-50 border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1PwnmGEj3-LdlAWnghxaAjzE7_oP-zBV-" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1PwnmGEj3-LdlAWnghxaAjzE7_oP-zBV-&sz=w600';" alt="Kinh nghiệm chọn gạch lát nền phòng khách" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Tư vấn chọn gạch</div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug mb-1.5">
                Kinh Nghiệm Chọn Gạch Lát Nền Phòng Khách 80x80 Và 60x120 Sang Trọng, Bền Đẹp
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Hướng dẫn cách phối màu gạch vân đá bóng kiếng giúp không gian phòng khách nhà phố, biệt thự tại Đà Nẵng rộng rãi và đẳng cấp hơn.
              </p>
            </div>
            <a href="#bao-gia" class="text-xs font-semibold text-brand hover:underline mt-3 inline-block">Nhận tư vấn mẫu <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-slate-50 border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/17IqN0-NJjYItC7jA1L5RhcR9PUUCdCPs" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17IqN0-NJjYItC7jA1L5RhcR9PUUCdCPs&sz=w600';" alt="Báo giá gạch ốp tường Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Báo giá gạch men</div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug mb-1.5">
                Bảng Báo Giá Gạch Ốp Tường 30x60, 60x120 Mới Nhất Tại Đà Nẵng Năm 2026
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Tổng hợp các mẫu gạch ốp tường phòng khách, phòng bếp và nhà tắm chống thấm, chống bám bẩn với mức chiết khấu tốt nhất tại Vân Nhi Túy Loan.
              </p>
            </div>
            <a href="#bao-gia" class="text-xs font-semibold text-brand hover:underline mt-3 inline-block">Xem chi tiết giá <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-slate-50 border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1dYi-rm1ESinh_JzOkupdSgLArBauR4Y7" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dYi-rm1ESinh_JzOkupdSgLArBauR4Y7&sz=w600';" alt="Trọn bộ thiết bị vệ sinh" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Thiết bị phòng tắm</div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug mb-1.5">
                Cách Chọn Combo Thiết Bị Vệ Sinh Chính Hãng Tiết Kiệm Chi Phí Cho Nhà Mới
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Trọn bộ bồn cầu một khối, tủ lavabo, sen cây tắm nóng lạnh và phụ kiện phòng tắm inox 304 đồng bộ, bảo hành chính hãng dài hạn.
              </p>
            </div>
            <a href="#bao-gia" class="text-xs font-semibold text-brand hover:underline mt-3 inline-block">Nhận báo giá combo <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-slate-50 border border-slate-200 rounded-lg overflow-hidden hover:shadow-md transition flex flex-col">
          <div class="h-40 overflow-hidden bg-slate-200">
            <img src="https://lh3.googleusercontent.com/d/1ThR9MHUhG2J3isq314Dc8zDGADo5AGlv" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ThR9MHUhG2J3isq314Dc8zDGADo5AGlv&sz=w600';" alt="Xu hướng gạch khổ lớn" class="w-full h-full object-cover hover:scale-105 transition duration-300">
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-500 mb-1"><i class="fa-regular fa-calendar mr-1"></i>Xu hướng kiến trúc</div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug mb-1.5">
                Xu Hướng Sử Dụng Gạch Khổ Lớn & Gạch Giả Gỗ Cho Biệt Thự Hiện Đại Tại Đà Nẵng
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                Giải pháp ốp lát liền mạch ít đường ron với gạch khổ lớn 80x160, 1200x2400 kết hợp gạch giả gỗ ấm cúng cho phòng ngủ và sân thượng.
              </p>
            </div>
            <a href="#cong-trinh" class="text-xs font-semibold text-brand hover:underline mt-3 inline-block">Xem công trình thực tế <i class="fa-solid fa-arrow-right ml-1"></i></a>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI
  ====================================================================== -->
  <section id="doi-tac" class="py-6 bg-slate-50 border-t border-slate-200">
    <div class="container-1500">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-sm sm:text-base md:text-lg">
            DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
          </h2>
          <span class="text-xs text-slate-500 hidden sm:inline">Cam kết phân phối sản phẩm chính hãng 100%</span>
        </div>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2.5 sm:gap-3">
        <div class="bg-white border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center h-20 hover:border-brand transition">
          <span class="font-extrabold text-sm sm:text-base text-brand tracking-wider">VIGLACERA</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Gạch ốp lát & TBVS</span>
        </div>
        <div class="bg-white border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center h-20 hover:border-brand transition">
          <span class="font-extrabold text-sm sm:text-base text-red-700 tracking-wider">PRIME GROUP</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Gạch men cao cấp</span>
        </div>
        <div class="bg-white border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center h-20 hover:border-brand transition">
          <span class="font-extrabold text-sm sm:text-base text-emerald-800 tracking-wider">ĐỒNG TÂM</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Gạch Granite & Ceramic</span>
        </div>
        <div class="bg-white border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center h-20 hover:border-brand transition">
          <span class="font-extrabold text-sm sm:text-base text-sky-800 tracking-wider">INAX / TOTO</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
        </div>
        <div class="bg-white border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center h-20 hover:border-brand transition">
          <span class="font-extrabold text-sm sm:text-base text-amber-700 tracking-wider">TASA / CATALAN</span>
          <span class="text-[10px] text-slate-500 mt-0.5">Gạch khổ lớn & Vân đá</span>
        </div>
        <div class="bg-white border border-slate-200 rounded p-3 flex flex-col items-center justify-center text-center h-20 hover:border-brand transition">
          <span class="font-extrabold text-sm sm:text-base text-slate-800 tracking-wider">SCG / TAICERA</span>
          <span class="text-[10px] text-slate-500 mt-0.5">VLXD & Gạch trang trí</span>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       FOOTER CHUẨN FLATSOME (CÔNG TY TNHH VÂN NHI TÚY LOAN - VANNHI.VN)
  ====================================================================== -->
  <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brand-accent text-xs">
    <div class="container-1500">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
        
        <!-- Thông tin công ty -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <img 
              src="https://lh3.googleusercontent.com/d/1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m" 
              onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1n17-O86Q_l6f44NX6IvUtgFD81QWcK0m&sz=w200';"
              alt="Logo Công Ty TNHH Vân Nhi Túy Loan" 
              class="h-10 w-auto bg-white rounded p-0.5 object-contain"
            >
            <div>
              <h3 class="font-extrabold text-sm text-white uppercase">CÔNG TY TNHH VÂN NHI TÚY LOAN</h3>
              <p class="text-[11px] text-amber-300">Website chính thức: vannhi.vn</p>
            </div>
          </div>
          <p class="text-slate-300 leading-relaxed">
            Tổng kho phân phối Gạch lát nền, Gạch ốp tường, Gạch khổ lớn, Gạch trang trí và Thiết bị vệ sinh uy tín, chất lượng hàng đầu tại Đà Nẵng.
          </p>
          <ul class="space-y-1.5 text-slate-200 pt-1">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-4"></i> <strong>Địa chỉ:</strong> Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-4"></i> <strong>Hotline:</strong> <a href="tel:0905567811" class="text-amber-300 font-bold hover:underline">0905.567.811</a> - <a href="tel:0934999429" class="text-amber-300 font-bold hover:underline">0934.999.429</a></li>
            <li><i class="fa-brands fa-facebook text-amber-400 w-4"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/vannhiceramic" target="_blank" rel="noopener noreferrer" class="hover:underline">facebook.com/vannhiceramic</a></li>
            <li><i class="fa-solid fa-map-pin text-amber-400 w-4"></i> <strong>Bản đồ:</strong> <a href="https://maps.app.goo.gl/7ekvgym6ehCJMmSZ9" target="_blank" rel="noopener noreferrer" class="hover:underline">Xem vị trí trên Google Maps</a></li>
          </ul>
        </div>

        <!-- Danh mục sản phẩm -->
        <div class="lg:col-span-4 space-y-2">
          <h4 class="font-bold text-white uppercase text-xs border-b border-white/15 pb-1.5">DANH MỤC SẢN PHẨM CHÍNH</h4>
          <div class="grid grid-cols-2 gap-1.5 text-slate-300">
            <a href="#san-pham" onclick="filterCategory('GẠCH LÁT NỀN')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch Lát Nền Đà Nẵng</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH ỐP TƯỜNG')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch Ốp Tường</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH KHỔ LỚN')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch Khổ Lớn</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH TRANG TRÍ')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch Trang Trí</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH 60X60')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch 60x60</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH 80X80')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch 80x80</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH 60X120')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch 60x120</a>
            <a href="#san-pham" onclick="filterCategory('GẠCH 80X160')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Gạch 80x160</a>
            <a href="#san-pham" onclick="filterCategory('THIẾT BỊ VỆ SINH')" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Thiết Bị Vệ Sinh</a>
            <a href="#cong-trinh" class="hover:text-amber-300 cat-nowrap"><i class="fa-solid fa-angle-right mr-1 text-[10px]"></i>Công Trình Đà Nẵng</a>
          </div>
        </div>

        <!-- Chính sách hỗ trợ -->
        <div class="lg:col-span-3 space-y-2">
          <h4 class="font-bold text-white uppercase text-xs border-b border-white/15 pb-1.5">CHÍNH SÁCH KHÁCH HÀNG</h4>
          <ul class="space-y-1.5 text-slate-300">
            <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Cam kết hàng chính hãng loại 1</li>
            <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Giao hàng tận nơi tại TP. Đà Nẵng</li>
            <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Hỗ trợ đổi trả linh hoạt tại kho</li>
            <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Chiết khấu cao cho thầu thợ & dự án</li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>© 2026 Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH VÂN NHI TÚY LOAN (vannhi.vn)</strong>.</div>
        <div>Địa chỉ: Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
       - Nằm gọn bên trong khung nhìn, không gây tràn viền
  ====================================================================== -->
  <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
    
    <!-- Nút Zalo nổi bật -->
    <a 
      href="https://zalo.me/0905567811" 
      target="_blank" 
      rel="noopener noreferrer"
      title="Chat Zalo 0905.567.811"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold pr-1 hidden sm:inline cat-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Facebook Fanpage nổi bật -->
    <a 
      href="https://www.facebook.com/vannhiceramic" 
      target="_blank" 
      rel="noopener noreferrer"
      title="Fanpage Vân Nhi Ceramic"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="text-xs font-bold pr-1 hidden sm:inline cat-nowrap">Facebook</span>
    </a>

    <!-- Nút Hotline 1 nổi bật -->
    <a 
      href="tel:0905567811" 
      title="Gọi 0905.567.811"
      class="contact-float-pulse flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-brand-accent flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-extrabold pr-1 cat-nowrap">0905.567.811</span>
    </a>

    <!-- Nút Hotline 2 nổi bật -->
    <a 
      href="tel:0934999429" 
      title="Gọi 0934.999.429"
      class="flex items-center gap-2 bg-brand hover:bg-brand-dark text-white px-3 py-2 rounded-full shadow-lg transition"
    >
      <span class="w-6 h-6 rounded-full bg-amber-400 text-slate-950 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="text-xs font-extrabold pr-1 cat-nowrap">0934.999.429</span>
    </a>

  </div>

  <!-- MODAL XEM CHI TIẾT SẢN PHẨM / CÔNG TRÌNH & NHẬN BÁO GIÁ -->
  <div id="detailModal" class="fixed inset-0 bg-black/65 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-lg max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-4 py-3 bg-brand text-white">
        <h3 id="modalTitle" class="font-bold text-sm sm:text-base truncate pr-2">Chi tiết sản phẩm</h3>
        <button onclick="closeDetailModal()" class="text-white hover:bg-white/15 p-1 rounded">
          <i class="fa-solid fa-xmark text-lg"></i>
        </button>
      </div>
      <div class="p-4 grid grid-cols-1 sm:grid-cols-12 gap-4 items-center">
        <div class="sm:col-span-6 h-60 sm:h-72 rounded overflow-hidden border border-slate-200 bg-slate-100">
          <img id="modalImg" src="" alt="Ảnh thực tế" class="w-full h-full object-cover">
        </div>
        <div class="sm:col-span-6 space-y-2.5 text-xs sm:text-sm">
          <div id="modalCat" class="inline-block bg-slate-100 text-brand font-semibold px-2.5 py-0.5 rounded text-xs"></div>
          <div id="modalName" class="font-bold text-base text-slate-800 leading-snug"></div>
          <div id="modalPriceBox" class="flex items-center gap-2 pt-1"></div>
          <p id="modalDesc" class="text-xs text-slate-600 leading-relaxed"></p>
          <div class="pt-2 space-y-2 border-t border-slate-200 text-xs">
            <div><i class="fa-solid fa-building text-brand mr-1.5"></i><strong>Đơn vị:</strong> CÔNG TY TNHH VÂN NHI TÚY LOAN</div>
            <div><i class="fa-solid fa-location-dot text-brand-accent mr-1.5"></i><strong>Địa chỉ:</strong> Đường Quảng Xương, Xã Hòa Vang, TP. Đà Nẵng</div>
          </div>
          <div class="pt-2 flex flex-wrap gap-2">
            <a href="tel:0905567811" class="bg-brand-accent hover:bg-red-700 text-white font-bold text-xs px-3.5 py-2 rounded transition">
              <i class="fa-solid fa-phone mr-1"></i>Gọi 0905.567.811
            </a>
            <a href="https://zalo.me/0905567811" target="_blank" rel="noopener noreferrer" class="bg-[#0068ff] hover:bg-blue-700 text-white font-bold text-xs px-3.5 py-2 rounded transition">
              Chat Zalo Nhận Giá Sỉ
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- HỘP THÔNG BÁO GỬI BÁO GIÁ THÀNH CÔNG (Thay thế hoàn toàn alert) -->
  <div id="toastMessage" class="fixed top-4 right-4 z-50 hidden bg-emerald-700 text-white text-xs sm:text-sm px-4 py-3 rounded-lg shadow-xl border border-emerald-500 max-w-sm">
    <div class="font-bold mb-0.5"><i class="fa-solid fa-circle-check mr-1.5"></i>Đã ghi nhận yêu cầu báo giá!</div>
    <div id="toastText" class="text-emerald-100 text-xs">Công ty TNHH Vân Nhi Túy Loan sẽ liên hệ tư vấn quý khách ngay.</div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU 11 ẢNH SẢN PHẨM THỰC TẾ, 7 CÔNG TRÌNH & BANNER
  ====================================================================== -->
  <script>
    // Danh sách 11 ảnh sản phẩm thực tế từ Google Drive được phân vào đúng danh mục chuẩn gachmendanang.vn
    const actualProducts = [
      {
        id: 'VN01',
        driveId: '1zM_pXGbRC_EkN1eEw84GeqjoUcyQm-Ak',
        name: 'Gạch Lát Nền 80x80 Vân Đá Bóng Kiếng VN8801 Đà Nẵng',
        category: 'GẠCH LÁT NỀN',
        subCategory: 'GẠCH 80X80',
        oldPrice: '390.000 ₫',
        newPrice: '295.000 ₫',
        discount: '-24%',
        group: 1,
        desc: 'Mẫu gạch lát nền Porcelain 80x80 thực tế tại Showroom Vân Nhi Túy Loan, bề mặt bóng kiếng kim cương chống trầy xước.'
      },
      {
        id: 'VN02',
        driveId: '1OdF6gqej6dCfjOqaMf7atJxYrfRcD_5R',
        name: 'Gạch Lát Nền 60x60 Vân Đá Tự Nhiên VN6602 Đà Nẵng',
        category: 'GẠCH LÁT NỀN',
        subCategory: 'GẠCH 60X60',
        oldPrice: '280.000 ₫',
        newPrice: '215.000 ₫',
        discount: '-23%',
        group: 1,
        desc: 'Gạch lát nền 60x60 xương đá Granite cứng cáp, phù hợp lát nền phòng khách, phòng ngủ nhà phố và biệt thự.'
      },
      {
        id: 'VN03',
        driveId: '15F5bXav7G7HedIMGOK6vLBPpfDiuRwtN',
        name: 'Gạch Lát Nền 100x100 Vân Đá Cao Cấp VN1010 Đà Nẵng',
        category: 'GẠCH LÁT NỀN',
        subCategory: 'GẠCH 100X100',
        oldPrice: '620.000 ₫',
        newPrice: '480.000 ₫',
        discount: '-23%',
        group: 1,
        desc: 'Gạch khổ lớn lát nền 100x100 và 120x120 vân đá sang trọng cho không gian phòng khách rộng và sảnh lớn.'
      },
      {
        id: 'VN04',
        driveId: '1dc2fcG70o6i9F7R2jh_-oQeLhhBCc4Kx',
        name: 'Gạch Ốp Tường 30x60 Vân Đá Sáng Màu VN3604 Đà Nẵng',
        category: 'GẠCH ỐP TƯỜNG',
        subCategory: 'GẠCH 30X60',
        oldPrice: '260.000 ₫',
        newPrice: '198.000 ₫',
        discount: '-24%',
        group: 1,
        desc: 'Mẫu gạch ốp tường 30x60 thực tế chống thấm, dễ vệ sinh lau chùi, chuyên dụng cho tường phòng khách, bếp và nhà tắm.'
      },
      {
        id: 'VN05',
        driveId: '1uyJe4VIa-Mm1Kdy1641Z1TLHwgxLUgkR',
        name: 'Gạch Ốp Lát 60x120 Vân Đá Marble VN61205 Đà Nẵng',
        category: 'GẠCH ỐP TƯỜNG',
        subCategory: 'GẠCH 60X120',
        oldPrice: '480.000 ₫',
        newPrice: '370.000 ₫',
        discount: '-23%',
        group: 2,
        desc: 'Gạch khổ 60x120 đa năng vừa ốp tường vừa lát nền, hiệu ứng vân đá liên hoàn sang trọng chuẩn xu hướng 2026.'
      },
      {
        id: 'VN06',
        driveId: '1PwnmGEj3-LdlAWnghxaAjzE7_oP-zBV-',
        name: 'Gạch Khổ Lớn 80x160 Vân Đá Nhập Khẩu VN81606 Đà Nẵng',
        category: 'GẠCH KHỔ LỚN',
        subCategory: 'GẠCH 80X160',
        oldPrice: '582.000 ₫',
        newPrice: '455.000 ₫',
        discount: '-22%',
        group: 2,
        desc: 'Gạch khổ lớn 80x160 xương Porcelain cao cấp tại kho Vân Nhi Túy Loan, độ phẳng tuyệt đối và hạn chế đường ron.'
      },
      {
        id: 'VN07',
        driveId: '17IqN0-NJjYItC7jA1L5RhcR9PUUCdCPs',
        name: 'Gạch Khổ Lớn 1200x2400 Vân Đá Tự Nhiên VN1224 Đà Nẵng',
        category: 'GẠCH KHỔ LỚN',
        subCategory: 'GẠCH 1200X2400',
        oldPrice: '830.000 ₫',
        newPrice: '610.000 ₫',
        discount: '-27%',
        group: 2,
        desc: 'Gạch Big Slab khổ lớn 1200x2400 và 1600x3200 chuyên ốp vách tivi, mặt tiền, sảnh biệt thự và khách sạn tại Đà Nẵng.'
      },
      {
        id: 'VN08',
        driveId: '1V58uojvshVdrsCCgiFpzviO0y1R412Bu',
        name: 'Gạch Trang Trí Terrazzo & Mosaic Nghệ Thuật VNTR08 Đà Nẵng',
        category: 'GẠCH TRANG TRÍ',
        subCategory: 'GẠCH TERRAZZO',
        oldPrice: '420.000 ₫',
        newPrice: '330.000 ₫',
        discount: '-21%',
        group: 2,
        desc: 'Mẫu gạch trang trí Terrazzo, gạch Mosaic và gạch bông tạo điểm nhấn độc đáo cho phòng tắm, quầy bar và mặt tiền.'
      },
      {
        id: 'VN09',
        driveId: '1OaEIqnOhjNHkYOt17Cjg-4FC6elYqeg3',
        name: 'Gạch Giả Gỗ 20x100 & 15x80 Chống Trơn VNGO09 Đà Nẵng',
        category: 'GẠCH TRANG TRÍ',
        subCategory: 'GẠCH GIẢ GỖ',
        oldPrice: '340.000 ₫',
        newPrice: '265.000 ₫',
        discount: '-22%',
        group: 3,
        desc: 'Gạch vân gỗ tự nhiên ấm cúng, chống mối mọt, chống thấm nước tuyệt đối cho phòng ngủ, ban công và sân vườn.'
      },
      {
        id: 'VN10',
        driveId: '1dYi-rm1ESinh_JzOkupdSgLArBauR4Y7',
        name: 'Combo Bồn Cầu 1 Khối & Tủ Lavabo Cao Cấp VNTB10 Đà Nẵng',
        category: 'THIẾT BỊ VỆ SINH',
        subCategory: 'COMBO THIẾT BỊ VỆ SINH',
        oldPrice: '5.800.000 ₫',
        newPrice: '4.350.000 ₫',
        discount: '-25%',
        group: 3,
        desc: 'Bộ thiết bị vệ sinh chính hãng men Nano kháng khuẩn chống bám bẩn, xả xoáy siêu êm tiết kiệm nước tại Showroom Vân Nhi.'
      },
      {
        id: 'VN11',
        driveId: '16Ja3yGm0LmlsQZKZtI6fxp9ppfQsEBTV',
        name: 'Bộ Sen Cây Tắm Nóng Lạnh & Phụ Kiện Phòng Tắm VNTB11',
        category: 'THIẾT BỊ VỆ SINH',
        subCategory: 'VÒI SEN TẮM',
        oldPrice: '3.200.000 ₫',
        newPrice: '2.450.000 ₫',
        discount: '-23%',
        group: 3,
        desc: 'Sen cây tắm đứng nóng lạnh kết hợp trọn bộ phụ kiện nhà tắm cao cấp, bền bỉ chống gỉ sét trong môi trường ẩm.'
      }
    ];

    // Danh sách 7 ảnh công trình thực tế tại Đà Nẵng từ Google Drive
    const actualProjects = [
      {
        driveId: '1IVJi0fliWvL09tfUtBIHj-VJKvja-SBp',
        name: 'Công Trình Nhà Phố Hiện Đại Tại Hòa Vang - TP. Đà Nẵng',
        items: 'Cung cấp trọn gói gạch lát nền 80x80 & gạch ốp tường 30x60'
      },
      {
        driveId: '1ThR9MHUhG2J3isq314Dc8zDGADo5AGlv',
        name: 'Công Trình Biệt Thự Gia Đình Tại Túy Loan - Đà Nẵng',
        items: 'Hạng mục gạch khổ lớn 60x120 vân đá & thiết bị phòng tắm'
      },
      {
        driveId: '1YwwLTGtaqX1lds_chhBX7oZfu7EuTWss',
        name: 'Công Trình Nhà Ở Dân Dụng Khu Đô Thị Hòa Xuân - Cẩm Lệ',
        items: 'Hoàn thiện gạch lát nền bóng kiếng & gạch giả gỗ phòng ngủ'
      },
      {
        driveId: '1la5vwc_287D1hB4o5z4djcErFNhVZp-u',
        name: 'Công Trình Nhà Phố 3 Tầng Quận Hải Châu - TP. Đà Nẵng',
        items: 'Cung cấp gạch ốp mặt tiền, gạch lát nền và combo thiết bị vệ sinh'
      },
      {
        driveId: '1wnhGyQvKOZsi7RGWJhmqLHZzxZUsMuCa',
        name: 'Công Trình Biệt Thự Nghỉ Dưỡng Ngũ Hành Sơn - Đà Nẵng',
        items: 'Gạch khổ lớn 80x160, gạch Terrazzo và gạch trang trí ngoại thất'
      },
      {
        driveId: '1qhiReC3HcOidofY3RO7Out4DmBnobbjz',
        name: 'Công Trình Căn Hộ & Dịch Vụ Quận Sơn Trà - Đà Nẵng',
        items: 'Cung cấp sỉ gạch lát nền 60x60, 80x80 và thiết bị nhà tắm đồng bộ'
      },
      {
        driveId: '1hkmpto5RoUiSvr94CL79p8iLe7tIiT5a',
        name: 'Công Trình Nhà Mới Đường Quảng Xương - Hòa Vang, Đà Nẵng',
        items: 'Giao hàng tận công trình gạch ốp lát chính hãng loại 1 Vân Nhi'
      }
    ];

    // Hàm tạo thẻ HTML cho 1 sản phẩm chuẩn Flatsome (Góc trên bên trái có % giảm giá, tên sản phẩm đầy đủ không cắt chữ, không nhãn dán thừa)
    function createProductCardHTML(product) {
      const imgUrl = `https://lh3.googleusercontent.com/d/${product.driveId}`;
      const fallbackUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w800`;
      return `
        <div onclick="openProductModal('${product.id}')" class="cursor-pointer group bg-white border border-slate-200 rounded-lg overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
          <div>
            <div class="relative w-full aspect-square bg-slate-100 overflow-hidden">
              <!-- Duy nhất nhãn % giảm giá góc trên bên trái chuẩn Flatsome -->
              <div class="flatsome-sale-badge">${product.discount}</div>
              <img 
                src="${imgUrl}" 
                onerror="this.onerror=null;this.src='${fallbackUrl}';"
                alt="${product.name}" 
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              >
            </div>
            <div class="p-2.5 sm:p-3">
              <div class="text-[10px] sm:text-[11px] text-slate-400 uppercase font-medium mb-0.5">${product.subCategory}</div>
              <!-- Tên sản phẩm đầy đủ, không tràn ra ngoài và không bị thiếu chữ -->
              <h3 class="product-title-full text-[12.5px] sm:text-[13.5px] font-semibold text-slate-800 group-hover:text-brand transition">
                ${product.name}
              </h3>
            </div>
          </div>
          <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-slate-100 flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
            <del class="text-[11px] sm:text-xs text-slate-400">${product.oldPrice}</del>
            <ins class="text-xs sm:text-sm font-extrabold text-brand-accent no-underline">${product.newPrice}</ins>
          </div>
        </div>
      `;
    }

    // Render toàn bộ sản phẩm và phân nhóm trang chủ
    function renderAllProducts(list) {
      const mainGrid = document.getElementById('productGrid');
      if (list.length === 0) {
        mainGrid.innerHTML = `
          <div class="col-span-full bg-white border border-slate-200 rounded-lg p-6 text-center text-xs sm:text-sm text-slate-600">
            Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng nhấn <button onclick="filterCategory('all')" class="text-brand font-bold underline">Xem tất cả sản phẩm</button> hoặc gọi <strong>0905.567.811</strong> để nhận mẫu qua Zalo.
          </div>
        `;
        return;
      }
      mainGrid.innerHTML = list.map(createProductCardHTML).join('');
    }

    function renderGroupedSections() {
      document.getElementById('groupGrid1').innerHTML = actualProducts.filter(p => p.group === 1).map(createProductCardHTML).join('');
      document.getElementById('groupGrid2').innerHTML = actualProducts.filter(p => p.group === 2).map(createProductCardHTML).join('');
      document.getElementById('groupGrid3').innerHTML = actualProducts.filter(p => p.group === 3).map(createProductCardHTML).join('');
    }

    // Render 7 công trình thực tế tại Đà Nẵng
    function renderProjects() {
      const pGrid = document.getElementById('projectsGrid');
      pGrid.innerHTML = actualProjects.map((proj, idx) => {
        const imgUrl = `https://lh3.googleusercontent.com/d/${proj.driveId}`;
        const fallbackUrl = `https://drive.google.com/thumbnail?id=${proj.driveId}&sz=w800`;
        return `
          <div onclick="openProjectModal(${idx})" class="cursor-pointer group bg-slate-50 border border-slate-200 rounded-lg overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
            <div class="w-full h-40 sm:h-48 bg-slate-200 overflow-hidden">
              <img 
                src="${imgUrl}" 
                onerror="this.onerror=null;this.src='${fallbackUrl}';"
                alt="${proj.name}" 
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
              >
            </div>
            <div class="p-2.5 sm:p-3">
              <h3 class="product-title-full text-[12.5px] sm:text-[13.5px] font-bold text-brand group-hover:text-brand-accent transition mb-1">
                ${proj.name}
              </h3>
              <p class="product-title-full text-[11px] sm:text-xs text-slate-600">
                ${proj.items}
              </p>
            </div>
          </div>
        `;
      }).join('');
    }

    // Lọc danh mục sản phẩm
    function filterCategory(catKey) {
      const titleEl = document.getElementById('currentCategoryTitle');
      if (catKey === 'all') {
        titleEl.textContent = 'SẢN PHẨM THỰC TẾ TẠI SHOWROOM VÂN NHI';
        renderAllProducts(actualProducts);
      } else {
        titleEl.textContent = 'DANH MỤC: ' + catKey;
        const filtered = actualProducts.filter(p => 
          p.category.toUpperCase().includes(catKey.toUpperCase()) ||
          p.subCategory.toUpperCase().includes(catKey.toUpperCase()) ||
          p.name.toUpperCase().includes(catKey.toUpperCase())
        );
        renderAllProducts(filtered.length > 0 ? filtered : actualProducts);
      }
      const section = document.getElementById('san-pham');
      if (section) {
        section.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }

    // Tìm kiếm sản phẩm
    function handleSearchProducts(keyword) {
      const kw = (keyword || '').trim().toLowerCase();
      const titleEl = document.getElementById('currentCategoryTitle');
      if (!kw) {
        titleEl.textContent = 'SẢN PHẨM THỰC TẾ TẠI SHOWROOM VÂN NHI';
        renderAllProducts(actualProducts);
        return;
      }
      titleEl.textContent = `KẾT QUẢ TÌM KIẾM: "${keyword}"`;
      const filtered = actualProducts.filter(p =>
        p.name.toLowerCase().includes(kw) ||
        p.category.toLowerCase().includes(kw) ||
        p.subCategory.toLowerCase().includes(kw) ||
        p.desc.toLowerCase().includes(kw)
      );
      renderAllProducts(filtered);
    }

    // Mở Modal chi tiết sản phẩm
    function openProductModal(id) {
      const p = actualProducts.find(item => item.id === id);
      if (!p) return;
      document.getElementById('modalTitle').textContent = 'Chi Tiết Mẫu Sản Phẩm Thực Tế';
      document.getElementById('modalImg').src = `https://lh3.googleusercontent.com/d/${p.driveId}`;
      document.getElementById('modalCat').textContent = `${p.category} • ${p.subCategory}`;
      document.getElementById('modalName').textContent = p.name;
      document.getElementById('modalPriceBox').innerHTML = `
        <del class="text-slate-400 text-xs">${p.oldPrice}</del>
        <span class="text-brand-accent font-extrabold text-base">${p.newPrice}</span>
        <span class="bg-brand-accent text-white text-[11px] font-bold px-2 py-0.5 rounded">${p.discount}</span>
      `;
      document.getElementById('modalDesc').textContent = p.desc;
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    // Mở Modal chi tiết công trình Đà Nẵng
    function openProjectModal(index) {
      const proj = actualProjects[index];
      if (!proj) return;
      document.getElementById('modalTitle').textContent = 'Hình Ảnh Công Trình Thực Tế Tại Đà Nẵng';
      document.getElementById('modalImg').src = `https://lh3.googleusercontent.com/d/${proj.driveId}`;
      document.getElementById('modalCat').textContent = 'CÔNG TRÌNH THỰC TẾ ĐÀ NẴNG';
      document.getElementById('modalName').textContent = proj.name;
      document.getElementById('modalPriceBox').innerHTML = `
        <span class="text-brand font-bold text-xs">Cung cấp bởi: CÔNG TY TNHH VÂN NHI TÚY LOAN</span>
      `;
      document.getElementById('modalDesc').textContent = proj.items + '. Quý khách cần tư vấn mẫu gạch tương tự công trình vui lòng liên hệ Hotline/Zalo 0905.567.811 - 0934.999.429.';
      const modal = document.getElementById('detailModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    // Điều khiển đóng/mở Menu Điện Thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      const overlay = document.getElementById('mobileMenuOverlay');
      const isClosed = drawer.classList.contains('-translate-x-full');
      if (isClosed) {
        drawer.classList.remove('-translate-x-full');
        overlay.classList.remove('hidden');
      } else {
        drawer.classList.add('-translate-x-full');
        overlay.classList.add('hidden');
      }
    }

    // Xử lý gửi Form Báo Giá
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const cat = document.getElementById('qCategory').value;
      const toast = document.getElementById('toastMessage');
      const toastText = document.getElementById('toastText');
      toastText.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu báo giá "${cat}" đã được gửi đến phòng kinh doanh Vân Nhi Túy Loan!`;
      toast.classList.remove('hidden');
      document.getElementById('quoteForm').reset();
      setTimeout(() => {
        toast.classList.add('hidden');
      }, 5000);
    }

    // Điều khiển 2 Banner Tự Trượt Chuyên Nghiệp
    let currentBannerIndex = 0;
    const totalBanners = 2;
    let bannerInterval = null;

    function showBanner(index) {
      for (let i = 0; i < totalBanners; i++) {
        const slide = document.getElementById(`banner-slide-${i}`);
        const dot = document.getElementById(`banner-dot-${i}`);
        if (i === index) {
          slide.classList.remove('hidden', 'opacity-0');
          slide.classList.add('block', 'opacity-100');
          dot.classList.remove('bg-white/50');
          dot.classList.add('bg-amber-400');
        } else {
          slide.classList.remove('block', 'opacity-100');
          slide.classList.add('hidden', 'opacity-0');
          dot.classList.remove('bg-amber-400');
          dot.classList.add('bg-white/50');
        }
      }
    }

    function changeBanner(step) {
      currentBannerIndex = (currentBannerIndex + step + totalBanners) % totalBanners;
      showBanner(currentBannerIndex);
      resetBannerTimer();
    }

    function goToBanner(index) {
      currentBannerIndex = index;
      showBanner(currentBannerIndex);
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(() => {
        currentBannerIndex = (currentBannerIndex + 1) % totalBanners;
        showBanner(currentBannerIndex);
      }, 5000);
    }

    // Khởi chạy khi tải trang
    window.addEventListener('DOMContentLoaded', () => {
      renderAllProducts(actualProducts);
      renderGroupedSections();
      renderProjects();
      resetBannerTimer();
    });
  </script>
</body>
</html>
