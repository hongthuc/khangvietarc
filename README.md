<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH KHANG VIỆT - ARC | Thiết Kế &amp; Thi Công Kiến Trúc - Nội Thất - Xây Dựng Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH KHANG VIỆT - ARC chuyên thiết kế và thi công Kiến trúc, Nội thất, Xây dựng nhà phố, biệt thự, căn hộ, khách sạn, quán cà phê trọn gói tại Đà Nẵng. Hotline: 0788.502.789." />

  <!-- Meta Open Graph & Thumbnail chia sẻ link trang web (sử dụng chính logo công ty) -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="CÔNG TY TNHH KHANG VIỆT - ARC" />
  <meta property="og:url" content="https://khangvietarc.com/" />
  <meta property="og:title" content="CÔNG TY TNHH KHANG VIỆT - ARC | Kiến Tạo Ngôi Nhà Việt" />
  <meta property="og:description" content="Thiết kế &amp; Thi công Kiến trúc - Nội thất - Xây dựng trọn gói tại Đà Nẵng. Địa chỉ: 397 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng. Hotline: 0788.502.789." />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6" />
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6" />
  <meta property="og:image:alt" content="Logo CÔNG TY TNHH KHANG VIỆT - ARC" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH KHANG VIỆT - ARC | khangvietarc.com" />
  <meta name="twitter:description" content="Thiết kế &amp; Thi công Kiến trúc - Nội thất - Xây dựng chuyên nghiệp tại Đà Nẵng." />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6" />
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6" />

  <!-- Google Font: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: '#1B365D',   /* Xanh kiến trúc chủ đạo hài hòa với nhận diện logo */
              dark: '#10223D',      /* Xanh navy đậm sang trọng */
              accent: '#C88A2B',    /* Vàng đồng kiến trúc điểm nhấn */
              accentHover: '#AD741F',
              light: '#F6F8FB',
              border: '#E2E8F0',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền ngang và không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      max-width: 100%;
      overflow-x: hidden;
    }

    body {
      font-family: 'Inter', system-ui, -apple-system, sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
    }

    /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
    .kv-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .kv-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0px;
        padding-right: 0px;
      }
    }

    /* Đường gạch chân tiêu đề phong cách Flatsome UX Builder */
    .flatsome-title {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-title::after {
      content: "";
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background-color: #C88A2B;
      border-radius: 999px;
    }
    .flatsome-title-left::after {
      left: 0;
      transform: none;
    }

    /* Menu dropdown Flatsome mượt mà */
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

    /* 2 Banner tự trượt cùng kích thước tuyệt đối bằng CSS Grid Stack */
    .banner-stage {
      display: grid;
      grid-template-columns: 1fr;
      grid-template-rows: 1fr;
      width: 100%;
    }
    .banner-slide {
      grid-column: 1 / 2;
      grid-row: 1 / 2;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.65s ease, visibility 0.65s ease;
    }
    .banner-slide.is-active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 2;
    }

    /* Hiệu ứng nút liên hệ nổi bật */
    @keyframes softPulse {
      0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.45); }
      70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
      100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
    }
    .pulse-hotline {
      animation: softPulse 2s infinite;
    }

    /* Ẩn thanh cuộn phụ nhưng vẫn vuốt mượt trên mobile nếu cần */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Hiệu ứng zoom nhẹ ảnh Flatsome */
    .kv-img-zoom {
      transition: transform 0.45s ease;
    }
    .kv-card:hover .kv-img-zoom {
      transform: scale(1.05);
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- SECTION 1: TOP BAR THÔNG TIN (Sạch sẽ, không hiển thị thanh UXBuilder) -->
  <!-- ===================================================================== -->
  <div class="w-full bg-brand-dark text-slate-200 text-[12px] border-b border-white/10">
    <div class="kv-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:0788502789" class="inline-flex items-center gap-1.5 hover:text-brand-accent transition-colors whitespace-nowrap">
          <i class="fa-solid fa-phone text-brand-accent text-[11px]"></i>
          <span class="font-medium">0788.502.789</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <a href="mailto:khangviet.arc.group@gmail.com" class="inline-flex items-center gap-1.5 hover:text-brand-accent transition-colors whitespace-nowrap">
          <i class="fa-solid fa-envelope text-brand-accent text-[11px]"></i>
          <span>khangviet.arc.group@gmail.com</span>
        </a>
      </div>
      <div class="hidden md:flex items-center gap-4">
        <span class="inline-flex items-center gap-1.5 text-slate-300 whitespace-nowrap">
          <i class="fa-solid fa-location-dot text-brand-accent text-[11px]"></i>
          <span>397 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</span>
        </span>
        <span class="text-white/30">|</span>
        <a href="https://www.facebook.com/NhadepKhangVietArc/" target="_blank" rel="noopener noreferrer" class="hover:text-brand-accent transition-colors" aria-label="Fanpage Facebook">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- SECTION 2: HEADER CHÍNH (Logo gọn nhỏ, Menu 1 hàng, KHÔNG nút gọi ngay) -->
  <!-- ===================================================================== -->
  <header id="mainHeader" class="sticky top-0 z-40 w-full bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
    <div class="kv-container py-2.5 flex items-center justify-between gap-3">
      <!-- Logo gọn nhỏ lại -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
        <img
          src="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6"
          data-fallback="https://drive.google.com/thumbnail?id=1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6&sz=w400"
          data-placeholder="https://placehold.co/160x60/1B365D/C88A2B?text=KHANG+VIET+ARC"
          alt="Logo CÔNG TY TNHH KHANG VIỆT - ARC"
          class="h-10 sm:h-11 lg:h-11 w-auto max-w-[130px] object-contain rounded"
          onerror="handleDriveImageError(this)"
        />
        <div class="leading-tight">
          <div class="text-[13px] sm:text-[14px] font-extrabold text-brand-primary tracking-tight whitespace-nowrap">KHANG VIỆT - ARC</div>
          <div class="text-[10px] font-medium text-brand-accent tracking-wide whitespace-nowrap">Kiến tạo ngôi nhà Việt</div>
        </div>
      </a>

      <!-- Menu trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không ngắt dòng tên danh mục -->
      <nav aria-label="Menu chính" class="hidden lg:flex items-center justify-end flex-1 min-w-0">
        <ul class="flex flex-wrap items-center justify-end gap-x-3 xl:gap-x-5 gap-y-1 text-[12px] xl:text-[13px] font-semibold text-slate-700 uppercase tracking-tight">
          <li class="shrink-0">
            <a href="#trang-chu" class="block py-2 text-brand-primary hover:text-brand-accent transition-colors whitespace-nowrap">Trang chủ</a>
          </li>
          <li class="shrink-0">
            <a href="#gioi-thieu" class="block py-2 hover:text-brand-accent transition-colors whitespace-nowrap">Giới thiệu</a>
          </li>
          <li class="nav-item relative shrink-0">
            <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1 py-2 hover:text-brand-accent transition-colors whitespace-nowrap">
              <span>Công trình thực tế</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown absolute left-0 top-full pt-1 w-60 z-50">
              <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5 text-[12.5px] normal-case font-medium text-slate-700">
                <a href="#cong-trinh-thuc-te" onclick="filterProjects('can-ho')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Khách sạn – Căn hộ – Phòng trọ</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Biệt thự</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Nhà phố</a>
                <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Văn phòng – Quán Cà phê</a>
              </div>
            </div>
          </li>
          <li class="nav-item relative shrink-0">
            <a href="#linh-vuc-hoat-dong" class="inline-flex items-center gap-1 py-2 hover:text-brand-accent transition-colors whitespace-nowrap">
              <span>Lĩnh vực hoạt động</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown absolute left-0 top-full pt-1 w-60 z-50">
              <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5 text-[12.5px] normal-case font-medium text-slate-700">
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a>
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Thi công phần thô</a>
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Thi công hoàn thiện</a>
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Thi công nội thất trọn gói</a>
              </div>
            </div>
          </li>
          <li class="nav-item relative shrink-0">
            <a href="#du-an-da-nang" class="inline-flex items-center gap-1 py-2 hover:text-brand-accent transition-colors whitespace-nowrap">
              <span>Mẫu thiết kế</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
              <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5 text-[12.5px] normal-case font-medium text-slate-700">
                <a href="#du-an-da-nang" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Mẫu thiết kế nhà phố</a>
                <a href="#du-an-da-nang" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Mẫu thiết kế biệt thự</a>
                <a href="#du-an-da-nang" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Mẫu thiết kế nội thất</a>
              </div>
            </div>
          </li>
          <li class="shrink-0">
            <a href="#du-an-da-nang" class="block py-2 hover:text-brand-accent transition-colors whitespace-nowrap">Dự án Đà Nẵng</a>
          </li>
          <li class="nav-item relative shrink-0">
            <a href="#bao-gia" class="inline-flex items-center gap-1 py-2 hover:text-brand-accent transition-colors whitespace-nowrap">
              <span>Báo giá</span>
              <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
            </a>
            <div class="nav-dropdown absolute right-0 top-full pt-1 w-60 z-50">
              <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5 text-[12.5px] normal-case font-medium text-slate-700">
                <a href="#bao-gia" onclick="presetQuoteType('Thiết kế Kiến trúc - Nội thất')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Báo giá thiết kế kiến trúc</a>
                <a href="#bao-gia" onclick="presetQuoteType('Thi công phần thô')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Báo giá thi công phần thô</a>
                <a href="#bao-gia" onclick="presetQuoteType('Thi công hoàn thiện')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Báo giá thi công hoàn thiện</a>
                <a href="#bao-gia" onclick="presetQuoteType('Thi công xây dựng trọn gói')" class="block px-4 py-2 hover:bg-brand-light hover:text-brand-primary whitespace-nowrap">Báo giá thi công trọn gói</a>
              </div>
            </div>
          </li>
          <li class="shrink-0">
            <a href="#bai-viet" class="block py-2 hover:text-brand-accent transition-colors whitespace-nowrap">Tin tức</a>
          </li>
          <li class="shrink-0">
            <a href="#lien-he" class="block py-2 hover:text-brand-accent transition-colors whitespace-nowrap">Liên hệ</a>
          </li>
        </ul>
      </nav>

      <!-- Nút mở Menu Mobile (Không đặt nút gọi ngay trên header để tránh tràn viền) -->
      <button
        id="mobileMenuBtn"
        type="button"
        aria-label="Mở menu điều hướng"
        class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-light transition-colors shrink-0"
      >
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Menu trượt xuống trên Điện thoại / Tablet -->
    <div id="mobileMenuPanel" class="hidden lg:hidden w-full bg-white border-t border-slate-200 shadow-lg">
      <div class="kv-container py-3 flex flex-col divide-y divide-slate-100 text-[13.5px] font-semibold text-slate-700">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 hover:text-brand-accent">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 hover:text-brand-accent">Giới thiệu</a>
        <div class="py-2.5">
          <a href="#cong-trinh-thuc-te" class="mobile-nav-link block hover:text-brand-accent">Công trình thực tế</a>
          <div class="pl-3 mt-1.5 grid grid-cols-2 gap-1.5 text-[12px] font-normal text-slate-600">
            <a href="#cong-trinh-thuc-te" onclick="filterProjects('can-ho')" class="mobile-nav-link py-1 hover:text-brand-primary">• Khách sạn – Căn hộ</a>
            <a href="#cong-trinh-thuc-te" onclick="filterProjects('biet-thu')" class="mobile-nav-link py-1 hover:text-brand-primary">• Biệt thự</a>
            <a href="#cong-trinh-thuc-te" onclick="filterProjects('nha-pho')" class="mobile-nav-link py-1 hover:text-brand-primary">• Nhà phố</a>
            <a href="#cong-trinh-thuc-te" onclick="filterProjects('van-phong')" class="mobile-nav-link py-1 hover:text-brand-primary">• Văn phòng – Cà phê</a>
          </div>
        </div>
        <a href="#linh-vuc-hoat-dong" class="mobile-nav-link py-2.5 hover:text-brand-accent">Lĩnh vực hoạt động</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 hover:text-brand-accent">Dự án tại Đà Nẵng</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 hover:text-brand-accent">Đối tác</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 hover:text-brand-accent">Báo giá &amp; Tư vấn</a>
        <a href="#bai-viet" class="mobile-nav-link py-2.5 hover:text-brand-accent">Tin tức &amp; Bài viết</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 hover:text-brand-accent">Liên hệ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu" class="w-full overflow-x-hidden">

    <!-- =================================================================== -->
    <!-- SECTION 3: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU -->
    <!-- Chữ & ảnh nằm gọn bên trong banner, cách xa viền, không mất chữ     -->
    <!-- =================================================================== -->
    <section aria-label="Banner nổi bật" class="w-full bg-brand-light py-3 sm:py-5">
      <div class="kv-container">
        <div
          id="heroSlider"
          class="relative w-full rounded-2xl overflow-hidden shadow-lg bg-brand-dark"
        >
          <div class="banner-stage">

            <!-- BANNER 1 -->
            <div class="banner-slide is-active relative w-full bg-gradient-to-br from-[#10223D] via-[#1B365D] to-[#13294B]">
              <!-- Ảnh nền nhẹ mờ tạo chiều sâu -->
              <img
                src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1200"
                data-placeholder="https://placehold.co/1400x600/10223D/C88A2B?text=Khang+Viet+ARC"
                alt="Công trình thi công Khang Việt - ARC"
                class="absolute inset-0 w-full h-full object-cover opacity-20"
                onerror="handleDriveImageError(this)"
              />
              <!-- Khung nội dung cách xa viền banner ở cả 4 cạnh -->
              <div class="relative z-10 w-full h-full px-8 py-9 sm:px-14 sm:py-12 md:px-20 md:py-14 lg:px-24 lg:py-16 flex items-center">
                <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <!-- Nội dung chữ bên trái -->
                  <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                    <div class="inline-block text-[11px] sm:text-[12px] font-bold uppercase tracking-[0.16em] text-brand-accent border-b border-brand-accent/60 pb-1">
                      CÔNG TY TNHH KHANG VIỆT - ARC
                    </div>
                    <h1 class="text-[20px] sm:text-[28px] md:text-[34px] lg:text-[40px] font-extrabold leading-[1.22] tracking-tight text-white">
                      THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                    </h1>
                    <p class="text-[13px] sm:text-[14.5px] lg:text-[15.5px] text-slate-200 leading-relaxed max-w-2xl">
                      Kiến trúc – Nội thất – Xây dựng Nhà phố, Biệt thự, Căn hộ, Khách sạn và Quán Cà phê. Cam kết đúng tiến độ, chuẩn kỹ thuật và tối ưu chi phí đầu tư.
                    </p>
                    <div class="pt-2 flex flex-wrap items-center gap-3">
                      <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-[13px] sm:text-[14px] font-semibold shadow-md transition-all">
                        Nhận báo giá miễn phí
                      </a>
                      <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white text-[13px] sm:text-[14px] font-semibold transition-all">
                        Xem công trình thực tế
                      </a>
                    </div>
                  </div>
                  <!-- Ảnh công trình nằm gọn trong khung banner -->
                  <div class="md:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-2xl bg-slate-900 aspect-[16/10] md:aspect-[4/3]">
                      <img
                        src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                        data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1000"
                        data-placeholder="https://placehold.co/800x600/1B365D/C88A2B?text=Cong+Trinh+Khang+Viet+ARC"
                        alt="Công trình thực tế Khang Việt - ARC Đà Nẵng"
                        class="w-full h-full object-cover"
                        onerror="handleDriveImageError(this)"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 -->
            <div class="banner-slide relative w-full bg-gradient-to-br from-[#162742] via-[#1D3B64] to-[#0F2038]">
              <img
                src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                data-fallback="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w1200"
                data-placeholder="https://placehold.co/1400x600/162742/C88A2B?text=Khang+Viet+ARC+Noi+That"
                alt="Kiến trúc và nội thất Khang Việt - ARC"
                class="absolute inset-0 w-full h-full object-cover opacity-20"
                onerror="handleDriveImageError(this)"
              />
              <!-- Khung nội dung cách xa viền banner ở cả 4 cạnh -->
              <div class="relative z-10 w-full h-full px-8 py-9 sm:px-14 sm:py-12 md:px-20 md:py-14 lg:px-24 lg:py-16 flex items-center">
                <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-6 lg:gap-10 items-center">
                  <!-- Nội dung chữ bên trái -->
                  <div class="md:col-span-7 text-white space-y-3 sm:space-y-4">
                    <div class="inline-block text-[11px] sm:text-[12px] font-bold uppercase tracking-[0.16em] text-brand-accent border-b border-brand-accent/60 pb-1">
                      KHANG VIỆT – KIẾN TẠO KHÔNG GIAN VIỆT
                    </div>
                    <h2 class="text-[20px] sm:text-[28px] md:text-[34px] lg:text-[40px] font-extrabold leading-[1.22] tracking-tight text-white">
                      CHUYÊN GIA CẢI TẠO NHÀ PHỐ &amp; THI CÔNG NỘI THẤT XƯỞNG TRỰC TIẾP
                    </h2>
                    <p class="text-[13px] sm:text-[14.5px] lg:text-[15.5px] text-slate-200 leading-relaxed max-w-2xl">
                      Sở hữu xưởng sản xuất nội thất trực tiếp tại Ngũ Hành Sơn, Đà Nẵng. Giải pháp trọn gói từ bản vẽ 3D đến bàn giao chìa khóa trao tay, bảo hành dài hạn.
                    </p>
                    <div class="pt-2 flex flex-wrap items-center gap-3">
                      <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-[13px] sm:text-[14px] font-semibold shadow-md transition-all">
                        Khám phá dự án Đà Nẵng
                      </a>
                      <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white text-[13px] sm:text-[14px] font-semibold transition-all">
                        Liên hệ tư vấn 24/7
                      </a>
                    </div>
                  </div>
                  <!-- Ảnh công trình nằm gọn trong khung banner -->
                  <div class="md:col-span-5">
                    <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-2xl bg-slate-900 aspect-[16/10] md:aspect-[4/3]">
                      <img
                        src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                        data-fallback="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w1000"
                        data-placeholder="https://placehold.co/800x600/1B365D/C88A2B?text=Noi+That+Khang+Viet+ARC"
                        alt="Thi công hoàn thiện nội thất Khang Việt - ARC"
                        class="w-full h-full object-cover"
                        onerror="handleDriveImageError(this)"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển slide trái/phải gọn gàng sát mép ngoài vùng chữ -->
          <button
            type="button"
            id="prevBannerBtn"
            aria-label="Banner trước"
            class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
          >
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button
            type="button"
            id="nextBannerBtn"
            aria-label="Banner tiếp theo"
            class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
          >
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chấm chỉ báo 2 banner -->
          <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" data-banner-dot="0" aria-label="Chuyển tới Banner 1" class="banner-dot w-7 h-2 rounded-full bg-brand-accent transition-all"></button>
            <button type="button" data-banner-dot="1" aria-label="Chuyển tới Banner 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 4: DỊCH VỤ TIÊU BIỂU (Bố cục 3 cột giống web mẫu Flatsome)   -->
    <!-- =================================================================== -->
    <section id="linh-vuc-hoat-dong" class="w-full py-10 md:py-14 bg-white">
      <div class="kv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title text-[20px] sm:text-[24px] md:text-[26px] font-extrabold text-brand-primary uppercase tracking-tight">
            Dịch vụ tiêu biểu
          </h2>
          <p class="mt-3 text-[13.5px] sm:text-[14.5px] text-slate-600 max-w-2xl mx-auto">
            Giải pháp toàn diện từ ý tưởng kiến trúc, thi công phần thô đến hoàn thiện nội thất chìa khóa trao tay.
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-5 lg:gap-6">
          <!-- Dịch vụ 1: THIẾT KẾ -->
          <div class="kv-card group bg-brand-light rounded-xl overflow-hidden border border-slate-200 hover:border-brand-accent/60 hover:shadow-lg transition-all flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                data-placeholder="https://placehold.co/800x500/1B365D/C88A2B?text=THIET+KE"
                alt="Dịch vụ Thiết kế Kiến trúc - Nội thất"
                class="kv-img-zoom w-full h-full object-cover"
                onerror="handleDriveImageError(this)"
              />
            </div>
            <div class="p-5 text-center flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[17px] font-extrabold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition-colors">
                  THIẾT KẾ
                </h3>
                <p class="mt-2 text-[13.5px] text-slate-600 leading-relaxed">
                  Thiết kế kiến trúc nhà phố, biệt thự, khách sạn, căn hộ cho thuê, quán cà phê tối ưu công năng và thẩm mỹ hiện đại.
                </p>
              </div>
              <a href="#bao-gia" onclick="presetQuoteType('Thiết kế Kiến trúc - Nội thất')" class="mt-4 inline-flex items-center justify-center gap-1.5 text-[13px] font-semibold text-brand-accent hover:text-brand-primary transition-colors">
                <span>Xem chi tiết &amp; Báo giá</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 2: THI CÔNG -->
          <div class="kv-card group bg-brand-light rounded-xl overflow-hidden border border-slate-200 hover:border-brand-accent/60 hover:shadow-lg transition-all flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                data-fallback="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w900"
                data-placeholder="https://placehold.co/800x500/1B365D/C88A2B?text=THI+CONG"
                alt="Dịch vụ Thi công Xây dựng trọn gói"
                class="kv-img-zoom w-full h-full object-cover"
                onerror="handleDriveImageError(this)"
              />
            </div>
            <div class="p-5 text-center flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[17px] font-extrabold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition-colors">
                  THI CÔNG
                </h3>
                <p class="mt-2 text-[13.5px] text-slate-600 leading-relaxed">
                  Thi công phần thô, thi công hoàn thiện, xây nhà trọn gói và cải tạo nâng tầng với quy trình giám sát kỹ thuật nghiêm ngặt.
                </p>
              </div>
              <a href="#bao-gia" onclick="presetQuoteType('Thi công xây dựng trọn gói')" class="mt-4 inline-flex items-center justify-center gap-1.5 text-[13px] font-semibold text-brand-accent hover:text-brand-primary transition-colors">
                <span>Xem chi tiết &amp; Báo giá</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>

          <!-- Dịch vụ 3: NỘI THẤT -->
          <div class="kv-card group bg-brand-light rounded-xl overflow-hidden border border-slate-200 hover:border-brand-accent/60 hover:shadow-lg transition-all flex flex-col">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
              <img
                src="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                data-fallback="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w900"
                data-placeholder="https://placehold.co/800x500/1B365D/C88A2B?text=NOI+THAT"
                alt="Dịch vụ Sản xuất và Thi công Nội thất"
                class="kv-img-zoom w-full h-full object-cover"
                onerror="handleDriveImageError(this)"
              />
            </div>
            <div class="p-5 text-center flex-1 flex flex-col justify-between">
              <div>
                <h3 class="text-[17px] font-extrabold text-brand-primary uppercase tracking-wide group-hover:text-brand-accent transition-colors">
                  NỘI THẤT
                </h3>
                <p class="mt-2 text-[13.5px] text-slate-600 leading-relaxed">
                  Sản xuất và lắp đặt nội thất gỗ trực tiếp từ xưởng tại K71 Bình Kỳ, Ngũ Hành Sơn – sắc nét từng đường nét, giá xuất xưởng.
                </p>
              </div>
              <a href="#bao-gia" onclick="presetQuoteType('Thi công nội thất trọn gói')" class="mt-4 inline-flex items-center justify-center gap-1.5 text-[13px] font-semibold text-brand-accent hover:text-brand-primary transition-colors">
                <span>Xem chi tiết &amp; Báo giá</span>
                <i class="fa-solid fa-arrow-right text-[11px]"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 5: GIỚI THIỆU CÔNG TY & THẾ MẠNH (Bố cục chuẩn web mẫu)      -->
    <!-- =================================================================== -->
    <section id="gioi-thieu" class="w-full py-10 md:py-14 bg-brand-light border-y border-slate-200/80">
      <div class="kv-container">
        <!-- Khối Giới thiệu Công ty -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-12">
          <div class="lg:col-span-6 space-y-4">
            <h2 class="flatsome-title flatsome-title-left text-[20px] sm:text-[24px] md:text-[26px] font-extrabold text-brand-primary uppercase tracking-tight">
              CÔNG TY TNHH KHANG VIỆT - ARC
            </h2>
            <p class="text-[14px] sm:text-[15px] text-slate-700 leading-relaxed">
              <strong>KHANG VIỆT - ARC</strong> là đơn vị uy tín chuyên Thiết kế – Xây dựng – Nội thất các công trình Nhà ở, Nhà phố, Biệt thự, Căn hộ, Khách sạn, Cửa hàng và Quán Coffee tại khu vực <strong>Đà Nẵng – Quảng Nam</strong>.
            </p>
            <p class="text-[14px] sm:text-[15px] text-slate-600 leading-relaxed">
              Với phương châm <strong>“Khang Việt – Kiến tạo ngôi nhà Việt”</strong>, chúng tôi đặt cái <strong>“TÂM”</strong> trong từng bản vẽ và từng hạng mục thi công để mỗi công trình đều đạt chuẩn <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – THẨM MỸ BỀN VỮNG</strong>. Sở hữu đội ngũ kiến trúc sư, kỹ sư giàu kinh nghiệm cùng xưởng sản xuất nội thất trực tiếp, Khang Việt - ARC đồng hành cùng khách hàng tạo dựng không gian sống đẳng cấp và trọn vẹn nhất.
            </p>
            <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 pt-2">
              <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                <div class="text-[20px] sm:text-[22px] font-extrabold text-brand-primary">100+</div>
                <div class="text-[12px] text-slate-600 mt-0.5">Công trình hoàn thiện</div>
              </div>
              <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center">
                <div class="text-[20px] sm:text-[22px] font-extrabold text-brand-accent">100%</div>
                <div class="text-[12px] text-slate-600 mt-0.5">Đúng tiến độ cam kết</div>
              </div>
              <div class="bg-white rounded-xl p-3.5 border border-slate-200 text-center col-span-2 sm:col-span-1">
                <div class="text-[20px] sm:text-[22px] font-extrabold text-brand-primary">Xưởng riêng</div>
                <div class="text-[12px] text-slate-600 mt-0.5">Nội thất Ngũ Hành Sơn</div>
              </div>
            </div>
          </div>

          <div class="lg:col-span-6">
            <div class="grid grid-cols-2 gap-3 sm:gap-4">
              <div class="rounded-xl overflow-hidden shadow-md bg-white aspect-[4/3]">
                <img
                  src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                  data-fallback="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w900"
                  data-placeholder="https://placehold.co/600x450/1B365D/C88A2B?text=Thi+Cong+Thuc+Te"
                  alt="Thi công thực tế Khang Việt - ARC"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImageError(this)"
                />
              </div>
              <div class="rounded-xl overflow-hidden shadow-md bg-white aspect-[4/3]">
                <img
                  src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                  data-fallback="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w900"
                  data-placeholder="https://placehold.co/600x450/1B365D/C88A2B?text=Hoan+Thien+Nha+Pho"
                  alt="Bàn giao công trình nhà phố Đà Nẵng"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImageError(this)"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- Thế mạnh của chúng tôi (6 hộp icon giống mẫu Tín Trường Thịnh) -->
        <div class="text-center mb-7">
          <h3 class="flatsome-title text-[19px] sm:text-[22px] font-extrabold text-brand-primary uppercase">
            Thế mạnh của chúng tôi
          </h3>
        </div>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 lg:gap-5">
          <div class="bg-white rounded-xl p-5 border border-slate-200 hover:shadow-md transition-shadow flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-compass-drafting text-lg"></i>
            </div>
            <div>
              <h4 class="text-[14.5px] font-bold text-brand-primary">Đội ngũ KTS, kỹ sư chuyên nghiệp</h4>
              <p class="mt-1 text-[13px] text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng kỹ sư giám sát giàu kinh nghiệm và đội thợ lành nghề trực tiếp thi công.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-slate-200 hover:shadow-md transition-shadow flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-brand-accent/15 text-brand-accent flex items-center justify-center shrink-0">
              <i class="fa-solid fa-layer-group text-lg"></i>
            </div>
            <div>
              <h4 class="text-[14.5px] font-bold text-brand-primary">Cập nhật xu hướng thiết kế hiện đại</h4>
              <p class="mt-1 text-[13px] text-slate-600 leading-relaxed">Cá nhân hóa từng không gian sống, kết hợp xu hướng vật liệu mới và bản sắc kiến trúc Việt tinh tế.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-slate-200 hover:shadow-md transition-shadow flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-clipboard-check text-lg"></i>
            </div>
            <div>
              <h4 class="text-[14.5px] font-bold text-brand-primary">Giám sát tiến độ chuẩn xác</h4>
              <p class="mt-1 text-[13px] text-slate-600 leading-relaxed">Báo cáo tiến độ thường xuyên theo từng giai đoạn thi công, giúp chủ đầu tư an tâm theo dõi mọi lúc mọi nơi.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-slate-200 hover:shadow-md transition-shadow flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-brand-accent/15 text-brand-accent flex items-center justify-center shrink-0">
              <i class="fa-solid fa-shield-halved text-lg"></i>
            </div>
            <div>
              <h4 class="text-[14.5px] font-bold text-brand-primary">Bảo hành công trình lâu dài</h4>
              <p class="mt-1 text-[13px] text-slate-600 leading-relaxed">Chính sách hậu mãi rõ ràng, hỗ trợ bảo trì nhanh chóng và tận tâm ngay cả sau khi bàn giao sử dụng.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-slate-200 hover:shadow-md transition-shadow flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-hand-holding-dollar text-lg"></i>
            </div>
            <div>
              <h4 class="text-[14.5px] font-bold text-brand-primary">Chi phí hợp lý, minh bạch</h4>
              <p class="mt-1 text-[13px] text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, không phát sinh chi phí ẩn, tối ưu ngân sách tốt nhất cho gia chủ.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-slate-200 hover:shadow-md transition-shadow flex items-start gap-4">
            <div class="w-11 h-11 rounded-lg bg-brand-accent/15 text-brand-accent flex items-center justify-center shrink-0">
              <i class="fa-solid fa-headset text-lg"></i>
            </div>
            <div>
              <h4 class="text-[14.5px] font-bold text-brand-primary">Hỗ trợ tư vấn miễn phí 24/7</h4>
              <p class="mt-1 text-[13px] text-slate-600 leading-relaxed">Sẵn sàng khảo sát thực tế, tư vấn phương án thiết kế và khái toán chi phí xây dựng miễn phí tại Đà Nẵng.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 6: CÔNG TRÌNH THỰC TẾ (9 ảnh Drive thực tế, 2 cột Mobile)   -->
    <!-- Không dán nhãn trên ảnh, chữ danh mục nhỏ gọn, tên sản phẩm đầy đủ  -->
    <!-- =================================================================== -->
    <section id="cong-trinh-thuc-te" class="w-full py-10 md:py-14 bg-white">
      <div class="kv-container">
        <div class="text-center mb-6">
          <h2 class="flatsome-title text-[20px] sm:text-[24px] md:text-[26px] font-extrabold text-brand-primary uppercase tracking-tight">
            Công trình thực tế
          </h2>
          <p class="mt-3 text-[13.5px] text-slate-600">
            Hình ảnh thi công và bàn giao thực tế do đội ngũ <strong>Khang Việt - ARC</strong> trực tiếp thực hiện.
          </p>
        </div>

        <!-- Thanh danh mục lọc nhỏ gọn, tên danh mục viết liền không xuống dòng -->
        <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
          <button type="button" data-filter="all" onclick="filterProjects('all')" class="project-tab active px-3.5 py-1.5 rounded-lg text-[12px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-primary text-white border border-brand-primary transition-all">
            Tất cả
          </button>
          <button type="button" data-filter="can-ho" onclick="filterProjects('can-ho')" class="project-tab px-3.5 py-1.5 rounded-lg text-[12px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-light text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Khách sạn - Căn hộ - Phòng trọ
          </button>
          <button type="button" data-filter="biet-thu" onclick="filterProjects('biet-thu')" class="project-tab px-3.5 py-1.5 rounded-lg text-[12px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-light text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Biệt thự
          </button>
          <button type="button" data-filter="nha-pho" onclick="filterProjects('nha-pho')" class="project-tab px-3.5 py-1.5 rounded-lg text-[12px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-light text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Nhà phố
          </button>
          <button type="button" data-filter="van-phong" onclick="filterProjects('van-phong')" class="project-tab px-3.5 py-1.5 rounded-lg text-[12px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-light text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Văn phòng - Cà phê
          </button>
        </div>

        <!-- Lưới công trình thực tế: 2 cột trên điện thoại, 3 cột trên máy tính -->
        <div id="realProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
          <!-- Render tự động bằng JS từ danh sách 9 ảnh thi công thực tế -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 7: CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ảnh Drive dự án Đà Nẵng)         -->
    <!-- 2 cột trên điện thoại, 4-5 cột trên desktop, không nhãn dán         -->
    <!-- =================================================================== -->
    <section id="du-an-da-nang" class="w-full py-10 md:py-14 bg-brand-light border-y border-slate-200/80">
      <div class="kv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title text-[20px] sm:text-[24px] md:text-[26px] font-extrabold text-brand-primary uppercase tracking-tight">
            Các dự án tại Đà Nẵng
          </h2>
          <p class="mt-3 text-[13.5px] sm:text-[14.5px] text-slate-600 max-w-2xl mx-auto">
            Tổng hợp các dự án thiết kế kiến trúc, xây dựng nhà trọn gói và hoàn thiện nội thất nổi bật của Khang Việt - ARC tại TP. Đà Nẵng.
          </p>
        </div>

        <!-- Lưới dự án Đà Nẵng: 2 cột Mobile, 3 cột Tablet, 5 cột Desktop rộng 95% -->
        <div id="danangProjectsGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render tự động bằng JS từ 10 ảnh dự án tại Đà Nẵng -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 8: DANH MỤC CÁC ĐỐI TÁC VẬT TƯ & XÂY DỰNG                   -->
    <!-- =================================================================== -->
    <section id="doi-tac" class="w-full py-10 md:py-12 bg-white">
      <div class="kv-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-title text-[20px] sm:text-[23px] font-extrabold text-brand-primary uppercase tracking-tight">
            Đối tác của chúng tôi
          </h2>
          <p class="mt-3 text-[13.5px] text-slate-600">
            Hợp tác cùng các thương hiệu vật liệu xây dựng và nội thất chính hãng hàng đầu Việt Nam.
          </p>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">AN CƯỜNG</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Gỗ nội thất</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">HÒA PHÁT</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">JOTUN</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn cao cấp</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">DULUX</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">XINGFA</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Cửa nhôm kính</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">CADIVI</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Dây cáp điện</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">INAX</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
          </div>
          <div class="bg-brand-light border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
            <span class="text-[14px] font-extrabold text-brand-primary tracking-wide">VICOSTONE</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Đá thạch anh</span>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 9: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ (Giống mẫu Flatsome)    -->
    <!-- =================================================================== -->
    <section id="bao-gia" class="w-full py-10 md:py-14 bg-brand-primary text-white">
      <div class="kv-container">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
          <!-- Thông tin tư vấn bên trái -->
          <div class="lg:col-span-5 space-y-4">
            <div class="text-[12px] font-bold uppercase tracking-[0.15em] text-brand-accent">
              MIỄN PHÍ TƯ VẤN &amp; KHÁI TOÁN CHI PHÍ
            </div>
            <h2 class="text-[22px] sm:text-[26px] md:text-[30px] font-extrabold leading-tight">
              ĐĂNG KÝ NHẬN BÁO GIÁ THIẾT KẾ &amp; THI CÔNG TRỌN GÓI
            </h2>
            <p class="text-[14px] text-slate-200 leading-relaxed">
              Để lại thông tin nhu cầu công trình, đội ngũ Kiến trúc sư &amp; Kỹ sư <strong>CÔNG TY TNHH KHANG VIỆT - ARC</strong> sẽ liên hệ tư vấn phương án tối ưu và gửi bảng báo giá chi tiết hoàn toàn miễn phí.
            </p>
            <div class="space-y-2.5 pt-2 text-[13.5px] text-slate-100">
              <div class="flex items-center gap-2.5">
                <i class="fa-solid fa-circle-check text-brand-accent"></i>
                <span>Khảo sát hiện trạng thực tế miễn phí tại Đà Nẵng</span>
              </div>
              <div class="flex items-center gap-2.5">
                <i class="fa-solid fa-circle-check text-brand-accent"></i>
                <span>Dự toán minh bạch, cam kết không phát sinh chi phí</span>
              </div>
              <div class="flex items-center gap-2.5">
                <i class="fa-solid fa-circle-check text-brand-accent"></i>
                <span>Ưu đãi giảm đến 100% chi phí thiết kế khi thi công trọn gói</span>
              </div>
            </div>
          </div>

          <!-- Form đăng ký bên phải -->
          <div class="lg:col-span-7">
            <form id="quoteForm" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-2xl space-y-4">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="customerName" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Họ và tên <span class="text-red-500">*</span></label>
                  <input
                    id="customerName"
                    name="customerName"
                    type="text"
                    required
                    placeholder="Nhập họ tên của bạn"
                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-[13.5px] focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                  />
                </div>
                <div>
                  <label for="customerPhone" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Số điện thoại / Zalo <span class="text-red-500">*</span></label>
                  <input
                    id="customerPhone"
                    name="customerPhone"
                    type="tel"
                    required
                    placeholder="VD: 0788.502.789"
                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-[13.5px] focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                  />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="projectType" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Loại công trình / Dịch vụ</label>
                  <select
                    id="projectType"
                    name="projectType"
                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-[13.5px] bg-white focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                  >
                    <option value="Nhà phố">Nhà phố</option>
                    <option value="Biệt thự">Biệt thự</option>
                    <option value="Khách sạn - Căn hộ cho thuê - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                    <option value="Văn phòng - Quán Cà phê - Cửa hàng">Văn phòng – Quán Cà phê – Cửa hàng</option>
                    <option value="Cải tạo sửa chữa - Nâng tầng">Cải tạo sửa chữa – Nâng tầng</option>
                    <option value="Thiết kế Kiến trúc - Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                    <option value="Thi công phần thô">Thi công phần thô</option>
                    <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                    <option value="Thi công xây dựng trọn gói">Thi công xây dựng trọn gói</option>
                    <option value="Thi công nội thất trọn gói">Thi công nội thất trọn gói</option>
                  </select>
                </div>
                <div>
                  <label for="budgetLevel" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                  <select
                    id="budgetLevel"
                    name="budgetLevel"
                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-[13.5px] bg-white focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                  >
                    <option value="Chưa xác định">Chưa xác định</option>
                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                  </select>
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <div>
                  <label for="customerEmail" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Email (nếu có)</label>
                  <input
                    id="customerEmail"
                    name="customerEmail"
                    type="email"
                    placeholder="example@gmail.com"
                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-[13.5px] focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                  />
                </div>
                <div>
                  <label for="projectArea" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Diện tích &amp; Quy mô dự kiến</label>
                  <input
                    id="projectArea"
                    name="projectArea"
                    type="text"
                    placeholder="VD: 5x20m, 3 tầng, Cẩm Lệ"
                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-[13.5px] focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                  />
                </div>
              </div>

              <div>
                <label for="customerNote" class="block text-[12.5px] font-semibold text-slate-700 mb-1">Ghi chú yêu cầu</label>
                <textarea
                  id="customerNote"
                  name="customerNote"
                  rows="2"
                  placeholder="Mô tả phong cách mong muốn hoặc thời gian dự kiến khởi công..."
                  class="w-full px-3.5 py-2 rounded-lg border border-slate-300 text-[13.5px] focus:outline-none focus:ring-2 focus:ring-brand-accent focus:border-brand-accent"
                ></textarea>
              </div>

              <button
                type="submit"
                class="w-full py-3 px-6 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-[14px] uppercase tracking-wide shadow-md transition-colors"
              >
                Gửi yêu cầu tư vấn &amp; báo giá
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 10: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ               -->
    <!-- 2 cột trên điện thoại, 4 cột trên desktop, không nhãn dán           -->
    <!-- =================================================================== -->
    <section id="bai-viet" class="w-full py-10 md:py-14 bg-white">
      <div class="kv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title text-[20px] sm:text-[24px] md:text-[26px] font-extrabold text-brand-primary uppercase tracking-tight">
            Tin tức &amp; Kinh nghiệm xây nhà
          </h2>
          <p class="mt-3 text-[13.5px] text-slate-600">
            Cập nhật kiến thức thiết kế kiến trúc, kỹ thuật thi công và bảng giá xây dựng mới nhất tại Đà Nẵng.
          </p>
        </div>

        <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render bài viết từ JS -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- SECTION 11: FANPAGE FACEBOOK & GOOGLE MAPS NGAY TRÊN TRANG CHỦ      -->
    <!-- =================================================================== -->
    <section id="lien-he" class="w-full py-10 md:py-14 bg-brand-light border-t border-slate-200">
      <div class="kv-container">
        <div class="text-center mb-8">
          <h2 class="flatsome-title text-[20px] sm:text-[24px] md:text-[26px] font-extrabold text-brand-primary uppercase tracking-tight">
            Kết nối Fanpage &amp; Chỉ đường văn phòng
          </h2>
          <p class="mt-3 text-[13.5px] text-slate-600">
            Ghé thăm văn phòng giao dịch tại <strong>397 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</strong> hoặc theo dõi tiến độ công trình hàng ngày trên Fanpage.
          </p>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
          <!-- Cột trái: Google Map ra ngoài trang chủ -->
          <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-map-location-dot text-brand-accent text-base"></i>
                <h3 class="text-[14.5px] font-bold text-brand-primary">Bản đồ Google Maps – Trụ sở Khang Việt - ARC</h3>
              </div>
              <a
                href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJk_7unZ4ZQjERaPHdburH6oA"
                target="_blank"
                rel="noopener noreferrer"
                class="text-[12px] font-semibold text-brand-accent hover:text-brand-primary transition-colors whitespace-nowrap"
              >
                Mở bản đồ lớn <i class="fa-solid fa-arrow-up-right-from-square text-[10px] ml-0.5"></i>
              </a>
            </div>
            <div class="w-full flex-1 min-h-[320px] sm:min-h-[360px] bg-slate-100">
              <iframe
                title="Bản đồ CÔNG TY TNHH KHANG VIỆT - ARC - 397 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng"
                src="https://maps.google.com/maps?q=397+Nguy%E1%BB%85n+H%E1%BB%AFu+Th%E1%BB%8D,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full min-h-[320px] sm:min-h-[360px] border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Cột phải: Fanpage Facebook ra ngoài trang chủ -->
          <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2">
                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                <h3 class="text-[14.5px] font-bold text-brand-primary">Fanpage chính thức</h3>
              </div>
              <a
                href="https://www.facebook.com/NhadepKhangVietArc/"
                target="_blank"
                rel="noopener noreferrer"
                class="text-[12px] font-semibold text-[#1877F2] hover:underline whitespace-nowrap"
              >
                Theo dõi Fanpage
              </a>
            </div>

            <!-- Thẻ giới thiệu nhanh Fanpage kết hợp nhúng Facebook Page Plugin -->
            <div class="p-4 flex-1 flex flex-col gap-3">
              <div class="flex items-center gap-3 p-3 rounded-xl bg-brand-light border border-slate-200">
                <img
                  src="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6"
                  data-fallback="https://drive.google.com/thumbnail?id=1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6&sz=w300"
                  data-placeholder="https://placehold.co/80x80/1B365D/C88A2B?text=KV"
                  alt="Avatar Fanpage Nhà đẹp Khang Việt - Arc"
                  class="w-12 h-12 rounded-lg object-contain bg-white p-1 border border-slate-200 shrink-0"
                  onerror="handleDriveImageError(this)"
                />
                <div class="min-w-0">
                  <div class="text-[13.5px] font-bold text-brand-primary leading-snug">
                    Nhà đẹp Khang Việt - Arc "Kiến trúc, Nội thất, Xây dựng"
                  </div>
                  <div class="text-[12px] text-slate-500">facebook.com/NhadepKhangVietArc</div>
                </div>
              </div>

              <div class="w-full flex-1 min-h-[250px] rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                <iframe
                  title="Fanpage Nhà đẹp Khang Việt - Arc"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FNhadepKhangVietArc%2F&tabs=timeline&width=500&height=300&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  class="w-full h-[270px] border-0"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                  loading="lazy"
                ></iframe>
              </div>

              <a
                href="https://www.facebook.com/NhadepKhangVietArc/"
                target="_blank"
                rel="noopener noreferrer"
                class="w-full py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white text-[13px] font-semibold text-center transition-colors inline-flex items-center justify-center gap-2"
              >
                <i class="fa-brands fa-facebook-f"></i>
                <span>Xem thêm công trình trên Facebook Fanpage</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ===================================================================== -->
  <!-- SECTION 12: FOOTER CHUẨN FLATSOME (3 cột thông tin gọn gàng)          -->
  <!-- ===================================================================== -->
  <footer class="w-full bg-brand-dark text-slate-300 pt-10 pb-6 border-t-4 border-brand-accent">
    <div class="kv-container">
      <div class="grid grid-cols-1 md:grid-cols-12 gap-8 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="md:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <img
              src="https://lh3.googleusercontent.com/d/1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6"
              data-fallback="https://drive.google.com/thumbnail?id=1k3J9XaXtq_DZqTy1TvODKOsWfh_ik8Y6&sz=w300"
              data-placeholder="https://placehold.co/120x48/1B365D/C88A2B?text=KHANG+VIET"
              alt="Logo CÔNG TY TNHH KHANG VIỆT - ARC"
              class="h-11 w-auto bg-white rounded-lg p-1 object-contain"
              onerror="handleDriveImageError(this)"
            />
            <div>
              <h3 class="text-[15px] font-extrabold text-white uppercase">CÔNG TY TNHH KHANG VIỆT - ARC</h3>
              <p class="text-[12px] text-brand-accent font-medium">Khang Việt – Kiến tạo ngôi nhà Việt</p>
            </div>
          </div>
          <ul class="space-y-2 text-[13px] pt-1">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-building text-brand-accent mt-1 w-4 text-center shrink-0"></i>
              <span><strong>Trụ sở Văn phòng:</strong> 397 Nguyễn Hữu Thọ, Phường Cẩm Lệ, TP Đà Nẵng</span>
            </li>
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-industry text-brand-accent mt-1 w-4 text-center shrink-0"></i>
              <span><strong>Xưởng nội thất:</strong> K71 Bình Kỳ, Ngũ Hành Sơn, TP. Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-brand-accent w-4 text-center shrink-0"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0788502789" class="text-white font-semibold hover:text-brand-accent">0788.502.789</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-envelope text-brand-accent w-4 text-center shrink-0"></i>
              <span><strong>Email:</strong> khangviet.arc.group@gmail.com</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-brand-accent w-4 text-center shrink-0"></i>
              <span><strong>Website:</strong> khangvietarc.com &nbsp;|&nbsp; <strong>MST:</strong> 0402074354</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="md:col-span-3 space-y-3">
          <h4 class="text-[14px] font-bold text-white uppercase tracking-wide border-b border-brand-accent/60 pb-2 inline-block">
            Lĩnh vực hoạt động
          </h4>
          <ul class="space-y-2 text-[13px]">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-accent transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-accent transition-colors">Thi công phần thô</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-accent transition-colors">Thi công hoàn thiện trọn gói</a></li>
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-accent transition-colors">Sản xuất &amp; Thi công nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-accent transition-colors">Cải tạo nhà phố – Quán Cà phê</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục nhanh -->
        <div class="md:col-span-4 space-y-3">
          <h4 class="text-[14px] font-bold text-white uppercase tracking-wide border-b border-brand-accent/60 pb-2 inline-block">
            Danh mục trang web
          </h4>
          <div class="grid grid-cols-2 gap-2 text-[13px]">
            <a href="#trang-chu" class="hover:text-brand-accent transition-colors">Trang chủ</a>
            <a href="#gioi-thieu" class="hover:text-brand-accent transition-colors">Giới thiệu</a>
            <a href="#cong-trinh-thuc-te" class="hover:text-brand-accent transition-colors">Công trình thực tế</a>
            <a href="#du-an-da-nang" class="hover:text-brand-accent transition-colors">Dự án tại Đà Nẵng</a>
            <a href="#doi-tac" class="hover:text-brand-accent transition-colors">Đối tác</a>
            <a href="#bao-gia" class="hover:text-brand-accent transition-colors">Báo giá xây dựng</a>
            <a href="#bai-viet" class="hover:text-brand-accent transition-colors">Tin tức &amp; Bài viết</a>
            <a href="#lien-he" class="hover:text-brand-accent transition-colors">Liên hệ &amp; Bản đồ</a>
          </div>
          <div class="pt-2">
            <a href="https://www.facebook.com/NhadepKhangVietArc/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 text-[13px] text-slate-200 hover:text-brand-accent transition-colors">
              <i class="fa-brands fa-facebook text-[#3B82F6] text-base"></i>
              <span>facebook.com/NhadepKhangVietArc</span>
            </a>
          </div>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[12px] text-slate-400 text-center">
        <div>Copyright 2026 © <strong>CÔNG TY TNHH KHANG VIỆT - ARC</strong> (khangvietarc.com). All rights reserved.</div>
        <div>Thiết kế chuẩn Flatsome – Tối ưu máy tính &amp; điện thoại</div>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Desktop & Mobile)   -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút lên đầu trang -->
    <button
      id="backToTopBtn"
      type="button"
      aria-label="Lên đầu trang"
      onclick="window.scrollTo({top: 0, behavior: 'smooth'})"
      class="hidden w-10 h-10 sm:w-11 sm:h-11 rounded-full bg-slate-800/85 hover:bg-brand-primary text-white shadow-lg flex items-center justify-center transition-all"
    >
      <i class="fa-solid fa-chevron-up text-sm"></i>
    </button>

    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/NhadepKhangVietArc/"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Liên hệ Facebook Khang Việt - ARC"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
    >
      <i class="fa-brands fa-facebook-f w-5 h-5 flex items-center justify-center text-base"></i>
      <span class="hidden md:inline text-[12.5px] font-bold pr-1 whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0788502789"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo 0788.502.789"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054D1] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all"
    >
      <span class="w-5 h-5 flex items-center justify-center font-extrabold text-[11px] bg-white text-[#0068FF] rounded-full leading-none">Z</span>
      <span class="hidden md:inline text-[12.5px] font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0788502789"
      aria-label="Gọi Hotline 0788.502.789"
      class="pulse-hotline flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition-all"
    >
      <i class="fa-solid fa-phone-volume w-5 h-5 flex items-center justify-center text-base"></i>
      <span class="hidden md:inline text-[13px] font-extrabold tracking-wide whitespace-nowrap">0788.502.789</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT & THÔNG BÁO GỬI FORM         -->
  <!-- ===================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-[60] hidden items-center justify-center bg-black/70 p-3 sm:p-5 backdrop-blur-xs">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-[15px] sm:text-[17px] font-bold text-brand-primary pr-4">Chi tiết công trình</h3>
        <button type="button" onclick="closeDetailModal()" aria-label="Đóng hộp thoại" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-5 space-y-4">
        <div id="modalImageWrap" class="w-full rounded-xl overflow-hidden bg-slate-100">
          <img id="modalImage" src="" alt="" class="w-full max-h-[420px] object-contain mx-auto bg-slate-900" />
        </div>
        <div id="modalMeta" class="text-[12.5px] font-semibold text-brand-accent"></div>
        <p id="modalDesc" class="text-[13.5px] sm:text-[14.5px] text-slate-700 leading-relaxed"></p>
        <div class="pt-2 flex flex-wrap items-center gap-3">
          <a href="#bao-gia" onclick="closeDetailModal()" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-[13px] font-bold transition-colors">
            Nhận báo giá mẫu này
          </a>
          <a href="tel:0788502789" class="px-5 py-2.5 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-light text-[13px] font-bold transition-colors">
            Hotline: 0788.502.789
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- Hộp thông báo Toast (thay thế hoàn toàn alert()) -->
  <div id="toastBox" class="fixed top-20 left-1/2 -translate-x-1/2 z-[70] hidden max-w-[92vw] w-auto bg-brand-dark text-white border border-brand-accent px-5 py-3.5 rounded-xl shadow-2xl flex items-center gap-3">
    <i class="fa-solid fa-circle-check text-brand-accent text-lg shrink-0"></i>
    <div id="toastText" class="text-[13.5px] font-medium leading-snug"></div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: DỮ LIỆU CÔNG TRÌNH, DỰ ÁN ĐÀ NẴNG, BANNER, FILTER & FORM  -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Hàm dự phòng tải ảnh từ Google Drive:
     * Bước 1: Dùng lh3.googleusercontent.com/d/{id}
     * Bước 2: Nếu lỗi, chuyển sang drive.google.com/thumbnail?id={id}&sz=w1000
     * Bước 3: Nếu vẫn lỗi, hiển thị ảnh placeholder chuyên nghiệp
     */
    function handleDriveImageError(imgEl) {
      const stage = imgEl.getAttribute('data-err-stage') || '0';
      if (stage === '0' && imgEl.getAttribute('data-fallback')) {
        imgEl.setAttribute('data-err-stage', '1');
        imgEl.src = imgEl.getAttribute('data-fallback');
      } else if (stage !== '2') {
        imgEl.setAttribute('data-err-stage', '2');
        imgEl.src = imgEl.getAttribute('data-placeholder') || 'https://placehold.co/800x600/1B365D/C88A2B?text=Khang+Viet+-+ARC';
      }
    }

    function driveUrl(id) {
      return 'https://lh3.googleusercontent.com/d/' + id;
    }

    function driveThumb(id) {
      return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w1000';
    }

    // -----------------------------------------------------------------------
    // 1. DỮ LIỆU 9 ẢNH THI CÔNG THỰC TẾ (Từ Google Drive & Fanpage Khang Việt - ARC)
    // -----------------------------------------------------------------------
    const realConstructionProjects = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        category: 'can-ho',
        categoryLabel: 'Khách sạn - Căn hộ - Phòng trọ',
        title: 'Tòa Căn Hộ Cho Thuê & Penthouse Tiểu La – TP. Đà Nẵng',
        meta: 'Chủ đầu tư: Anh Q.Anh | Quy mô: 6 căn hộ, Penthouse bể bơi & thang máy',
        desc: 'Công trình thi công trọn gói xây dựng và nội thất tòa căn hộ dịch vụ đường Tiểu La, TP. Đà Nẵng gồm mặt bằng kinh doanh, nhà xe, 6 phòng căn hộ khép kín và 1 căn Penthouse có bể bơi riêng.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Nhà Phố Hiện Đại 2 Tầng – Anh Vũ, TP. Đà Nẵng',
        meta: 'Chủ đầu tư: Mr Vũ | Quy mô: 2 tầng trọn gói',
        desc: 'Thiết kế và thi công trọn gói nhà phố 2 tầng phong cách hiện đại trẻ trung, tối ưu ánh sáng tự nhiên và không gian sinh hoạt ấm cúng cho gia đình trẻ tại Đà Nẵng.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Thi Công Hoàn Thiện Nhà Phố 3 Tầng – Hòa Cường, Đà Nẵng',
        meta: 'Chủ đầu tư: Mr Q.A | Địa điểm: Hòa Cường, Hải Châu, Đà Nẵng',
        desc: 'Công trình nhà phố 3 tầng tại Hòa Cường được Khang Việt - ARC thiết kế kiến trúc hiện đại, thi công phần thô và hoàn thiện đồng bộ nội thất.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Cải Tạo Nâng Tầng Nhà Phố 4 Tầng 1 Tum – Tiểu La, Đà Nẵng',
        meta: 'Chủ đầu tư: Ms T.Tuyền | Quy mô: Cải tạo nâng tầng 4 tầng 1 tum',
        desc: 'Hạng mục gia cố kết cấu, đổ bê tông nối sàn và cải tạo nâng tầng nhà phố 4 tầng 1 tum đường Tiểu La đảm bảo an toàn kết cấu và tiến độ bàn giao.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Thi Công Phần Thô Nhà Phố 3 Tầng – Chú Tình, Hòa Xuân',
        meta: 'Chủ đầu tư: Chú Tình | Địa điểm: Hòa Xuân, Cẩm Lệ, TP. Đà Nẵng',
        desc: 'Thi công móng, kết cấu khung sàn bê tông cốt thép chuẩn kỹ thuật, giám sát chặt chẽ từng đợt đổ bê tông sàn tại khu đô thị Hòa Xuân, Cẩm Lệ.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        title: 'Cải Tạo Tối Giản Nhà Phố 3 Tầng – Điện Biên Phủ, Đà Nẵng',
        meta: 'Chủ đầu tư: Mr Thiện | Quy mô: Cải tạo trọn gói 3 tầng',
        desc: 'Bàn giao gói cải tạo tối giản nhà phố 3 tầng mặt tiền Điện Biên Phủ, nâng cấp toàn diện công năng, mặt tiền và hệ thống điện nước nội thất.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        title: 'Biệt Thự Phố Tân Cổ Điển 4 Tầng – Anh Thái, Hòa Xuân',
        meta: 'Chủ đầu tư: Mr Thái | Quy mô: 4 tầng phong cách Tân Cổ Điển',
        desc: 'Công trình biệt thự phố Tân Cổ Điển 4 tầng tại Hòa Xuân với đường nét phào chỉ tinh tế, thi công cất nóc và hoàn thiện sắc nét.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        category: 'van-phong',
        categoryLabel: 'Văn phòng - Cà phê',
        title: 'Thiết Kế & Cải Tạo Trọn Gói Quán DORY Cafe – TP. Đà Nẵng',
        meta: 'Hạng mục: Cải tạo trọn gói kiến trúc & nội thất quán cà phê',
        desc: 'Lột xác không gian quán cà phê theo phong cách mới trẻ trung, tối ưu bố trí quầy pha chế, ánh sáng và chất liệu nội thất hút khách tại Đà Nẵng.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        title: 'Biệt Thự Nhà Phố Hiện Đại Mang Bản Sắc Việt – Đà Nẵng',
        meta: 'Hạng mục: Thiết kế kiến trúc & Thi công hoàn thiện nội thất',
        desc: 'Cá nhân hóa không gian nhà ở hiện đại hòa quyện cùng vật liệu tự nhiên và bản sắc kiến trúc Việt, mang lại sự thông thoáng và bền vững.'
      }
    ];

    // -----------------------------------------------------------------------
    // 2. DỮ LIỆU 10 ẢNH CÁC DỰ ÁN TẠI ĐÀ NẴNG (Từ Google Drive)
    // -----------------------------------------------------------------------
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự Án Nhà Phố Hiện Đại 3 Tầng – Hòa Xuân, Cẩm Lệ',
        meta: 'Khu vực: Hòa Xuân, Quận Cẩm Lệ, TP. Đà Nẵng',
        desc: 'Thiết kế kiến trúc mặt tiền thông thoáng kết hợp mảng xanh ban công và thi công trọn gói hoàn thiện nội thất gỗ tại Hòa Xuân.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Dự Án Căn Hộ Dịch Vụ Cho Thuê – Hải Châu, Đà Nẵng',
        meta: 'Khu vực: Quận Hải Châu, TP. Đà Nẵng',
        desc: 'Tòa nhà căn hộ cho thuê tối ưu số lượng phòng khai thác kinh doanh, đầy đủ thang máy và hệ thống PCCC theo tiêu chuẩn.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Dự Án Biệt Thự 2 Mặt Tiền – Nam Việt Á, Ngũ Hành Sơn',
        meta: 'Khu vực: Nam Việt Á, Ngũ Hành Sơn, TP. Đà Nẵng',
        desc: 'Biệt thự 2 mặt tiền sang trọng với hình khối hiện đại, vật liệu cao cấp và sân vườn thoáng mát quanh nhà.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Dự Án Hoàn Thiện Nội Thất Nhà Phố – Cẩm Lệ, Đà Nẵng',
        meta: 'Khu vực: Phường Cẩm Lệ, TP. Đà Nẵng',
        desc: 'Sản xuất và lắp đặt trọn gói nội thất phòng khách, bếp, phòng ngủ trực tiếp từ xưởng nội thất Khang Việt - ARC.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Dự Án Quán Cà Phê & Không Gian Kinh Doanh – Đà Nẵng',
        meta: 'Khu vực: Trung tâm TP. Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói mô hình quán cà phê mang dấu ấn thương hiệu riêng, tối ưu chi phí đầu tư và tiến độ khai trương.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Dự Án Nhà Phố Kết Hợp Văn Phòng – Nguyễn Hữu Thọ',
        meta: 'Khu vực: Trục đường Nguyễn Hữu Thọ, Đà Nẵng',
        desc: 'Nhà phố đa năng kết hợp không gian văn phòng làm việc ở tầng dưới và khu sinh hoạt gia đình riêng tư các tầng trên.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Dự Án Biệt Thự Sân Vườn Hiện Đại – Hòa Quý, Đà Nẵng',
        meta: 'Khu vực: Khu đô thị Hòa Quý, Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Không gian biệt thự nghỉ dưỡng trong lòng phố với thiết kế mở kết nối sân vườn, giếng trời đón gió biển tự nhiên.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Dự Án Khách Sạn & Căn Hộ Biển – Sơn Trà, Đà Nẵng',
        meta: 'Khu vực: Quận Sơn Trà, TP. Đà Nẵng',
        desc: 'Công trình lưu trú cao cấp gần biển được thiết kế tinh gọn, hiện đại, dễ bảo trì và thu hút khách du lịch quanh năm.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Dự Án Cải Tạo Nhà Phố Trọn Gói – Thanh Khê, Đà Nẵng',
        meta: 'Khu vực: Quận Thanh Khê, TP. Đà Nẵng',
        desc: 'Cải tạo nâng cấp nhà phố cũ thành không gian sống hiện đại, sáng rộng và tiện nghi như xây mới với chi phí tiết kiệm.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Dự Án Thiết Kế & Thi Công Showroom – Hải Châu, Đà Nẵng',
        meta: 'Khu vực: Quận Hải Châu, TP. Đà Nẵng',
        desc: 'Thi công hoàn thiện không gian văn phòng và showroom trưng bày chuyên nghiệp, hệ thống chiếu sáng nổi bật sản phẩm.'
      }
    ];

    // -----------------------------------------------------------------------
    // 3. DỮ LIỆU DANH MỤC BÀI VIẾT TRANG CHỦ
    // -----------------------------------------------------------------------
    const homeArticles = [
      {
        imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        date: '15/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật khi xây nhà',
        excerpt: 'Quy trình bảo dưỡng bê tông đạt chuẩn giúp tăng cường độ chịu lực, hạn chế nứt bề mặt và nâng cao tuổi thọ công trình.',
        content: 'Trong quá trình thi công phần thô nhà phố và biệt thự tại khí hậu miền Trung nắng gió như Đà Nẵng, công tác tưới nước giữ ẩm bảo dưỡng bê tông trong 7 ngày đầu tiên đóng vai trò quyết định đến độ bền kết cấu công trình. Khang Việt - ARC luôn áp dụng quy trình che phủ và kiểm tra độ sụt bê tông nghiêm ngặt tại công trường.'
      },
      {
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        date: '08/11/2026',
        title: 'Báo giá thiết kế và thi công nhà trọn gói tại Đà Nẵng mới nhất 2026',
        excerpt: 'Cập nhật đơn giá thiết kế kiến trúc, thi công phần thô và xây nhà chìa khóa trao tay minh bạch từng hạng mục vật tư.',
        content: 'Chi phí xây dựng nhà ở phụ thuộc vào diện tích sàn, điều kiện thi công, phong cách kiến trúc (hiện đại hay tân cổ điển) và gói vật tư hoàn thiện. Khi chọn thi công trọn gói tại Khang Việt - ARC, khách hàng được bóc tách khối lượng chi tiết và hỗ trợ ưu đãi chi phí thiết kế.'
      },
      {
        imgId: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        date: '29/10/2026',
        title: 'Kinh nghiệm cải tạo nhà phố cũ và quán cà phê tiết kiệm chi phí',
        excerpt: 'Những lưu ý quan trọng khi khảo sát kết cấu cũ, nâng tầng và thay đổi phong cách nội thất để tránh phát sinh.',
        content: 'Trước khi cải tạo nhà phố hoặc quán cà phê, cần đánh giá chính xác hiện trạng móng, cột, hệ thống cấp thoát nước và chống thấm. Một bản thiết kế 3D rõ ràng kết hợp dự toán trọn gói sẽ giúp chủ đầu tư kiểm soát tốt ngân sách và rút ngắn thời gian thi công.'
      },
      {
        imgId: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        date: '18/10/2026',
        title: '03 nỗi lo lớn nhất khi xây nhà và giải pháp từ Khang Việt - ARC',
        excerpt: 'Lo ngại phát sinh chi phí, chậm tiến độ hay chất lượng thi công không như bản vẽ đều được giải quyết bằng quy trình chuẩn.',
        content: 'Để xây dựng tổ ấm an tâm tuyệt đối, gia chủ nên lựa chọn đơn vị có đầy đủ năng lực thiết kế, đội ngũ thi công trực tiếp và xưởng nội thất riêng. Khang Việt - ARC cam kết hợp đồng minh bạch, báo cáo tiến độ định kỳ và bảo hành công trình lâu dài.'
      }
    ];

    // -----------------------------------------------------------------------
    // 4. RENDER CÔNG TRÌNH THỰC TẾ (Không dán nhãn trên ảnh, 2 cột Mobile)
    // -----------------------------------------------------------------------
    function renderRealProjects(filterKey) {
      const container = document.getElementById('realProjectsGrid');
      if (!container) return;

      const list = filterKey === 'all'
        ? realConstructionProjects
        : realConstructionProjects.filter(item => item.category === filterKey);

      container.innerHTML = list.map((item) => `
        <article
          onclick="openProjectModal('${item.id}', '${escapeJs(item.title)}', '${escapeJs(item.meta)}', '${escapeJs(item.desc)}')"
          class="kv-card group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all flex flex-col"
        >
          <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="${driveUrl(item.id)}"
              data-fallback="${driveThumb(item.id)}"
              data-placeholder="https://placehold.co/800x600/1B365D/C88A2B?text=Khang+Viet+ARC"
              alt="${escapeHtml(item.title)}"
              loading="lazy"
              class="kv-img-zoom w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            />
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[12.5px] sm:text-[14px] md:text-[14.5px] font-bold text-brand-primary group-hover:text-brand-accent leading-snug break-words transition-colors">
              ${escapeHtml(item.title)}
            </h3>
            <p class="mt-1.5 text-[11.5px] sm:text-[12px] text-slate-500 leading-snug">
              ${escapeHtml(item.categoryLabel)}
            </p>
          </div>
        </article>
      `).join('');
    }

    function filterProjects(categoryKey) {
      const tabs = document.querySelectorAll('.project-tab');
      tabs.forEach(tab => {
        const isActive = tab.getAttribute('data-filter') === categoryKey;
        if (isActive) {
          tab.classList.add('bg-brand-primary', 'text-white', 'border-brand-primary');
          tab.classList.remove('bg-brand-light', 'text-slate-700', 'border-slate-200');
        } else {
          tab.classList.remove('bg-brand-primary', 'text-white', 'border-brand-primary');
          tab.classList.add('bg-brand-light', 'text-slate-700', 'border-slate-200');
        }
      });
      renderRealProjects(categoryKey);
    }

    // -----------------------------------------------------------------------
    // 5. RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (Không dán nhãn trên ảnh, 2 cột Mobile)
    // -----------------------------------------------------------------------
    function renderDanangProjects() {
      const container = document.getElementById('danangProjectsGrid');
      if (!container) return;

      container.innerHTML = danangProjects.map((item) => `
        <article
          onclick="openProjectModal('${item.id}', '${escapeJs(item.title)}', '${escapeJs(item.meta)}', '${escapeJs(item.desc)}')"
          class="kv-card group cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all flex flex-col"
        >
          <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="${driveUrl(item.id)}"
              data-fallback="${driveThumb(item.id)}"
              data-placeholder="https://placehold.co/800x600/1B365D/C88A2B?text=Du+An+Da+Nang"
              alt="${escapeHtml(item.title)}"
              loading="lazy"
              class="kv-img-zoom w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-primary group-hover:text-brand-accent leading-snug break-words transition-colors">
              ${escapeHtml(item.title)}
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-[11.5px] text-slate-500 leading-snug">
              TP. Đà Nẵng
            </p>
          </div>
        </article>
      `).join('');
    }

    // -----------------------------------------------------------------------
    // 6. RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
    // -----------------------------------------------------------------------
    function renderArticles() {
      const container = document.getElementById('articlesGrid');
      if (!container) return;

      container.innerHTML = homeArticles.map((art) => `
        <article
          onclick="openProjectModal('${art.imgId}', '${escapeJs(art.title)}', 'Đăng ngày ${art.date} | Khang Việt - ARC', '${escapeJs(art.content)}')"
          class="kv-card group cursor-pointer bg-brand-light rounded-xl overflow-hidden border border-slate-200 hover:border-brand-accent hover:shadow-md transition-all flex flex-col"
        >
          <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
            <img
              src="${driveUrl(art.imgId)}"
              data-fallback="${driveThumb(art.imgId)}"
              data-placeholder="https://placehold.co/800x500/1B365D/C88A2B?text=Tin+Tuc+Xay+Dung"
              alt="${escapeHtml(art.title)}"
              loading="lazy"
              class="kv-img-zoom w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[11px] text-slate-500 mb-1">${art.date}</div>
              <h3 class="text-[12.5px] sm:text-[14px] font-bold text-brand-primary group-hover:text-brand-accent leading-snug break-words transition-colors">
                ${escapeHtml(art.title)}
              </h3>
              <p class="mt-2 text-[12px] text-slate-600 leading-relaxed hidden sm:block">
                ${escapeHtml(art.excerpt)}
              </p>
            </div>
            <div class="mt-3 text-[12px] font-semibold text-brand-accent group-hover:text-brand-primary transition-colors">
              Đọc tiếp &rarr;
            </div>
          </div>
        </article>
      `).join('');
    }

    // -----------------------------------------------------------------------
    // 7. BANNER TỰ TRƯỢT (2 BANNER KÍCH THƯỚC BẰNG NHAU + VUỐT MOBILE)
    // -----------------------------------------------------------------------
    let currentBannerIndex = 0;
    let bannerTimer = null;

    function initBannerSlider() {
      const slides = document.querySelectorAll('#heroSlider .banner-slide');
      const dots = document.querySelectorAll('#heroSlider .banner-dot');
      const sliderEl = document.getElementById('heroSlider');
      if (!slides.length) return;

      function showSlide(index) {
        currentBannerIndex = (index + slides.length) % slides.length;
        slides.forEach((slide, i) => {
          slide.classList.toggle('is-active', i === currentBannerIndex);
        });
        dots.forEach((dot, i) => {
          if (i === currentBannerIndex) {
            dot.classList.add('w-7', 'bg-brand-accent');
            dot.classList.remove('w-2.5', 'bg-white/50');
          } else {
            dot.classList.remove('w-7', 'bg-brand-accent');
            dot.classList.add('w-2.5', 'bg-white/50');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        bannerTimer = setInterval(() => {
          showSlide(currentBannerIndex + 1);
        }, 5000);
      }

      function stopAutoSlide() {
        if (bannerTimer) {
          clearInterval(bannerTimer);
          bannerTimer = null;
        }
      }

      document.getElementById('prevBannerBtn')?.addEventListener('click', () => {
        showSlide(currentBannerIndex - 1);
        startAutoSlide();
      });

      document.getElementById('nextBannerBtn')?.addEventListener('click', () => {
        showSlide(currentBannerIndex + 1);
        startAutoSlide();
      });

      dots.forEach((dot) => {
        dot.addEventListener('click', () => {
          const targetIdx = parseInt(dot.getAttribute('data-banner-dot'), 10);
          showSlide(targetIdx);
          startAutoSlide();
        });
      });

      // Tạm dừng khi di chuột vào banner trên máy tính
      sliderEl.addEventListener('mouseenter', stopAutoSlide);
      sliderEl.addEventListener('mouseleave', startAutoSlide);

      // Hỗ trợ vuốt cảm ứng trên điện thoại
      let touchStartX = 0;
      sliderEl.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      sliderEl.addEventListener('touchend', (e) => {
        const diff = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diff) > 40) {
          showSlide(diff > 0 ? currentBannerIndex - 1 : currentBannerIndex + 1);
          startAutoSlide();
        }
      }, { passive: true });

      showSlide(0);
      startAutoSlide();
    }

    // -----------------------------------------------------------------------
    // 8. MODAL CHI TIẾT, FORM BÁO GIÁ & TIỆN ÍCH GIAO DIỆN
    // -----------------------------------------------------------------------
    function openProjectModal(imgId, title, meta, desc) {
      const modal = document.getElementById('detailModal');
      const imgEl = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalMeta').textContent = meta;
      document.getElementById('modalDesc').textContent = desc;

      imgEl.removeAttribute('data-err-stage');
      imgEl.setAttribute('data-fallback', driveThumb(imgId));
      imgEl.setAttribute('data-placeholder', 'https://placehold.co/900x600/1B365D/C88A2B?text=Khang+Viet+-+ARC');
      imgEl.src = driveUrl(imgId);
      imgEl.alt = title;
      imgEl.onerror = function () { handleDriveImageError(this); };

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function presetQuoteType(val) {
      const select = document.getElementById('projectType');
      if (select) {
        select.value = val;
      }
    }

    let toastTimeout = null;
    function showToast(message) {
      const box = document.getElementById('toastBox');
      const text = document.getElementById('toastText');
      text.textContent = message;
      box.classList.remove('hidden');
      clearTimeout(toastTimeout);
      toastTimeout = setTimeout(() => {
        box.classList.add('hidden');
      }, 4500);
    }

    function escapeHtml(str) {
      return String(str)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    function escapeJs(str) {
      return String(str)
        .replace(/\\/g, '\\\\')
        .replace(/'/g, "\\'")
        .replace(/"/g, '\\"');
    }

    // Khởi tạo toàn bộ sự kiện khi tải trang
    document.addEventListener('DOMContentLoaded', () => {
      try {
        renderRealProjects('all');
        renderDanangProjects();
        renderArticles();
        initBannerSlider();

        // Toggle Menu Mobile
        const menuBtn = document.getElementById('mobileMenuBtn');
        const menuPanel = document.getElementById('mobileMenuPanel');
        menuBtn?.addEventListener('click', () => {
          menuPanel.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach((link) => {
          link.addEventListener('click', () => {
            menuPanel.classList.add('hidden');
          });
        });

        // Đóng modal khi bấm nền tối hoặc phím ESC
        document.getElementById('detailModal')?.addEventListener('click', (e) => {
          if (e.target.id === 'detailModal') closeDetailModal();
        });
        document.addEventListener('keydown', (e) => {
          if (e.key === 'Escape') closeDetailModal();
        });

        // Xử lý Form Yêu cầu & Báo giá (không dùng alert())
        const quoteForm = document.getElementById('quoteForm');
        quoteForm?.addEventListener('submit', (e) => {
          e.preventDefault();
          const name = document.getElementById('customerName').value.trim();
          const phone = document.getElementById('customerPhone').value.trim();
          if (!name || !phone) {
            showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để nhận báo giá.');
            return;
          }
          showToast('Cảm ơn ' + name + '! Khang Việt - ARC đã nhận yêu cầu và sẽ gọi lại số ' + phone + ' trong thời gian sớm nhất.');
          quoteForm.reset();
        });

        // Hiện nút lên đầu trang khi cuộn
        const topBtn = document.getElementById('backToTopBtn');
        window.addEventListener('scroll', () => {
          if (window.scrollY > 360) {
            topBtn?.classList.remove('hidden');
          } else {
            topBtn?.classList.add('hidden');
          }
        }, { passive: true });
      } catch (err) {
        console.error('Lỗi khởi tạo giao diện:', err);
      }
    });
  </script>
</body>
</html>
