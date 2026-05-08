<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
  <title>박종건 ♥ 이경은 결혼합니다</title>

  <!-- =====================================================
       📸 사진 설정 — 여기만 수정하면 됩니다!
       ===================================================== -->
  <script>
    // GitHub 저장소 주소 (마지막 / 포함)
    const GITHUB = "https://raw.githubusercontent.com/dlruddmssjs/-/main/";

    // 메인 히어로 사진 (맨 위 큰 사진 1장)
    const heroPhoto = GITHUB + "hero.jpg";

    // 갤러리 사진 목록 (순서대로 표시, 30장까지 추가 가능)
    const galleryPhotos = [
      GITHUB + "photo01.jpg",
      GITHUB + "photo02.jpg",
      GITHUB + "photo03.jpg",
      GITHUB + "photo04.jpg",
      GITHUB + "photo05.jpg",
      GITHUB + "photo06.jpg",
      GITHUB + "photo07.jpg",
      GITHUB + "photo08.jpg",
      GITHUB + "photo09.jpg",
      GITHUB + "photo10.jpg",
      GITHUB + "photo11.jpg",
      GITHUB + "photo12.jpg",
      GITHUB + "photo13.jpg",
      GITHUB + "photo14.jpg",
      GITHUB + "photo15.jpg",
      GITHUB + "photo16.jpg",
      GITHUB + "photo17.jpg",
      GITHUB + "photo18.jpg",
      GITHUB + "photo19.jpg",
      GITHUB + "photo20.jpg",
      GITHUB + "photo21.jpg",
      GITHUB + "photo22.jpg",
      GITHUB + "photo23.jpg",
      GITHUB + "photo24.jpg",
      GITHUB + "photo25.jpg",
      GITHUB + "photo26.jpg",
      GITHUB + "photo27.jpg",
      GITHUB + "photo28.jpg",
      GITHUB + "photo29.jpg",
      GITHUB + "photo30.jpg"
    ];

    // 카카오톡 미리보기 사진 (갤러리 첫번째 사진과 같아도 OK)
    const ogImage = "https://raw.githubusercontent.com/dlruddmssjs/-/main/KakaoTalk_20260508_135716534_05.jpg";
  </script>
  <!-- ===================================================== -->

  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300;1,400&family=Nanum+Myeongjo:wght@400;700&family=Gowun+Batang&display=swap" rel="stylesheet" />

  <!-- 카카오 SDK -->
  <script src="https://t1.kakaocdn.net/kakao_js_sdk/2.7.2/kakao.min.js"
    integrity="sha384-TiCUE00h649CAMonG018J2ujOgDKW/kVWlChEuu4jK2vxfAAD0eZxzCKakxg55G4"
    crossorigin="anonymous"></script>

  <!-- OG 태그 (카카오톡 미리보기) -->
  <meta property="og:type" content="website" />
  <meta property="og:title" content="박종건 이경은 결혼합니다" />
  <meta property="og:description" content="2028년 5월 21일 토요일 오후 1시 · 그랜드웨딩홀 로즈홀" />
  <meta property="og:url" content="https://dlruddmssjs.github.io/-/" />
  <meta name="title" content="박종건 이경은 결혼합니다" />
  <script>
    // OG 이미지 동적 설정
    document.addEventListener('DOMContentLoaded', () => {
      const meta = document.createElement('meta');
      meta.setAttribute('property', 'og:image');
      meta.setAttribute('content', ogImage);
      document.head.appendChild(meta);
    });
  </script>

  <style>
    :root {
      --cream: #faf6f1;
      --petal: #e8c9b8;
      --rose: #c27b6a;
      --blush: #f0ddd4;
      --gold: #b89468;
      --dark: #3a2e2a;
      --text: #5c4a42;
      --light-text: #9b7e72;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      background: var(--cream);
      color: var(--text);
      font-family: 'Gowun Batang', 'Nanum Myeongjo', serif;
      max-width: 480px;
      margin: 0 auto;
      overflow-x: hidden;
    }

    /* ─── HERO ─── */
    .hero {
      position: relative; height: 100svh; min-height: 600px;
      display: flex; flex-direction: column; align-items: center; justify-content: center;
      overflow: hidden;
      background: linear-gradient(170deg, #fdf5ee 0%, #f5e6da 60%, #ede0d4 100%);
    }
    .hero-bg-circle { position: absolute; border-radius: 50%; opacity: 0.18; background: radial-gradient(circle, var(--petal), transparent 70%); }
    .hero-bg-circle.c1 { width: 340px; height: 340px; top: -60px; right: -80px; }
    .hero-bg-circle.c2 { width: 260px; height: 260px; bottom: 30px; left: -60px; }
    .floral-tl, .floral-br { position: absolute; opacity: 0.55; pointer-events: none; }
    .floral-tl { top: 0; left: 0; width: 160px; }
    .floral-br { bottom: 0; right: 0; width: 160px; transform: rotate(180deg); }
    .hero-inner {
      position: relative; z-index: 2; text-align: center; padding: 0 32px;
      opacity: 0; transform: translateY(28px);
      animation: fadeUp 1.2s cubic-bezier(.22,.68,0,1.2) 0.3s forwards;
    }
    .date-top { font-family: 'Cormorant Garamond', serif; font-style: italic; font-size: 13px; letter-spacing: 4px; color: var(--rose); margin-bottom: 28px; }
    .hero-divider { width: 1px; height: 44px; background: linear-gradient(to bottom, transparent, var(--gold), transparent); margin: 0 auto 28px; opacity: 0; animation: fadeIn 1s ease 0.9s forwards; }
    .couple-names { font-family: 'Cormorant Garamond', serif; font-size: 52px; font-weight: 300; color: var(--dark); line-height: 1.15; letter-spacing: -1px; margin-bottom: 8px; }
    .couple-names .amp { font-style: italic; color: var(--rose); font-size: 40px; display: inline-block; padding: 0 10px; }
    .couple-kr { font-size: 15px; color: var(--light-text); letter-spacing: 6px; margin-top: 10px; margin-bottom: 32px; }
    .date-badge { display: inline-block; border: 1px solid var(--gold); padding: 10px 28px; font-size: 13px; letter-spacing: 3px; color: var(--gold); font-family: 'Cormorant Garamond', serif; }
    .scroll-hint { position: absolute; bottom: 32px; left: 50%; transform: translateX(-50%); display: flex; flex-direction: column; align-items: center; gap: 6px; opacity: 0; animation: fadeIn 1s ease 1.8s forwards; }
    .scroll-hint span { font-size: 10px; letter-spacing: 3px; color: var(--light-text); }
    .scroll-dot { width: 6px; height: 6px; border-radius: 50%; background: var(--rose); animation: bounce 1.6s ease-in-out infinite; }

    /* ─── SECTIONS ─── */
    section { padding: 70px 32px; opacity: 0; transform: translateY(20px); transition: opacity 0.8s ease, transform 0.8s ease; }
    section.visible { opacity: 1; transform: translateY(0); }
    .section-label { font-family: 'Cormorant Garamond', serif; font-style: italic; font-size: 12px; letter-spacing: 4px; color: var(--rose); text-align: center; margin-bottom: 14px; }
    .section-title { font-family: 'Nanum Myeongjo', serif; font-size: 22px; text-align: center; color: var(--dark); line-height: 1.8; margin-bottom: 10px; }
    .gold-line { width: 40px; height: 1px; background: var(--gold); margin: 18px auto; }
    .invite-text { text-align: center; line-height: 2.2; font-size: 14.5px; color: var(--text); word-break: keep-all; }

    /* ─── HERO PHOTO ─── */
    .photo-section { padding: 0; position: relative; overflow: hidden; }
    .photo-section.visible { opacity: 1; transform: none; }
    .hero-photo { width: 100%; aspect-ratio: 3/4; object-fit: cover; display: block; cursor: pointer; transition: transform 0.3s ease; }
    .hero-photo:hover { transform: scale(1.02); }
    .photo-caption { position: absolute; bottom: 32px; left: 0; right: 0; text-align: center; font-family: 'Cormorant Garamond', serif; font-style: italic; font-size: 18px; color: white; text-shadow: 0 2px 12px rgba(60,30,20,0.45); letter-spacing: 2px; }

    /* ─── DATE & TIME ─── */
    .datetime-grid { display: grid; grid-template-columns: 1fr 1px 1fr; gap: 0 20px; margin: 28px 0; align-items: center; }
    .datetime-item { text-align: center; }
    .datetime-item .dt-label { font-size: 11px; letter-spacing: 3px; color: var(--light-text); margin-bottom: 8px; }
    .datetime-item .dt-value { font-family: 'Cormorant Garamond', serif; font-size: 28px; font-weight: 300; color: var(--dark); line-height: 1; }
    .datetime-item .dt-sub { font-size: 12px; color: var(--light-text); margin-top: 4px; letter-spacing: 1px; }
    .dt-sep { width: 1px; height: 60px; background: var(--petal); }

    /* ─── COUNTDOWN ─── */
    .countdown { display: flex; justify-content: center; gap: 20px; margin-top: 24px; padding: 20px; background: var(--blush); border-radius: 2px; }
    .countdown-item { text-align: center; }
    .countdown-num { font-family: 'Cormorant Garamond', serif; font-size: 34px; font-weight: 300; color: var(--rose); line-height: 1; display: block; }
    .countdown-label { font-size: 10px; letter-spacing: 2px; color: var(--light-text); margin-top: 4px; }
    .countdown-sep { font-family: 'Cormorant Garamond', serif; font-size: 28px; color: var(--petal); line-height: 1.2; align-self: flex-start; margin-top: 4px; }

    /* ─── VENUE ─── */
    .venue-card { border: 1px solid var(--petal); padding: 28px 24px; background: white; position: relative; margin-top: 24px; }
    .venue-card::before { content: ''; position: absolute; top: 6px; left: 6px; right: -6px; bottom: -6px; border: 1px solid var(--blush); z-index: -1; }
    .venue-name { font-size: 18px; color: var(--dark); margin-bottom: 6px; letter-spacing: 1px; }
    .venue-detail { font-size: 13px; color: var(--light-text); line-height: 2; }
    .map-placeholder { width: 100%; height: 180px; background: linear-gradient(135deg, #f5ece4 0%, #e8d8cc 100%); margin-top: 16px; display: flex; align-items: center; justify-content: center; gap: 10px; font-size: 13px; color: var(--light-text); letter-spacing: 2px; cursor: pointer; position: relative; overflow: hidden; border: 1px solid var(--petal); }
    .map-btn-row { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 14px; }
    .map-btn { padding: 12px; text-align: center; font-size: 12px; letter-spacing: 2px; border: 1px solid var(--petal); color: var(--text); cursor: pointer; background: white; transition: all 0.2s; text-decoration: none; display: block; }
    .map-btn:hover { background: var(--blush); }

    /* ─── GALLERY ─── */
    .gallery-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 4px; margin-top: 24px; }
    .gallery-item { aspect-ratio: 1; overflow: hidden; cursor: pointer; position: relative; background: var(--blush); }
    .gallery-item img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.4s ease; display: block; }
    .gallery-item:hover img { transform: scale(1.08); }
    .gallery-item .overlay { position: absolute; inset: 0; background: rgba(60,30,20,0); transition: background 0.3s; }
    .gallery-item:hover .overlay { background: rgba(60,30,20,0.15); }

    /* ─── LIGHTBOX ─── */
    .lightbox { position: fixed; inset: 0; background: rgba(0,0,0,0.92); z-index: 9999; display: none; align-items: center; justify-content: center; flex-direction: column; }
    .lightbox.active { display: flex; }
    .lightbox-img-wrap { position: relative; width: 100%; height: 100%; display: flex; align-items: center; justify-content: center; overflow: hidden; }
    .lightbox-img { max-width: 100vw; max-height: 90vh; object-fit: contain; display: block; user-select: none; transition: opacity 0.25s ease; }
    .lightbox-img.fade { opacity: 0; }
    .lightbox-close { position: absolute; top: 20px; right: 20px; width: 44px; height: 44px; background: rgba(255,255,255,0.15); border: 1px solid rgba(255,255,255,0.3); border-radius: 50%; color: white; font-size: 20px; display: flex; align-items: center; justify-content: center; cursor: pointer; z-index: 10; }
    .lightbox-nav { position: absolute; top: 50%; transform: translateY(-50%); width: 48px; height: 48px; background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.25); border-radius: 50%; color: white; font-size: 22px; display: flex; align-items: center; justify-content: center; cursor: pointer; z-index: 10; transition: background 0.2s; user-select: none; }
    .lightbox-nav:hover { background: rgba(255,255,255,0.25); }
    .lightbox-prev { left: 16px; }
    .lightbox-next { right: 16px; }
    .lightbox-counter { position: absolute; bottom: 28px; left: 50%; transform: translateX(-50%); display: flex; gap: 8px; flex-wrap: wrap; justify-content: center; max-width: 80vw; }
    .lightbox-dot { width: 6px; height: 6px; border-radius: 50%; background: rgba(255,255,255,0.35); transition: background 0.2s, transform 0.2s; cursor: pointer; }
    .lightbox-dot.active { background: white; transform: scale(1.3); }

    /* ─── ACCOUNT ─── */
    .account-tabs { display: flex; border-bottom: 1px solid var(--petal); }
    .account-tab { flex: 1; padding: 14px; text-align: center; font-size: 13px; letter-spacing: 2px; color: var(--light-text); cursor: pointer; transition: all 0.2s; border-bottom: 2px solid transparent; margin-bottom: -1px; }
    .account-tab.active { color: var(--rose); border-bottom-color: var(--rose); }
    .account-panel { display: none; padding: 24px 0; }
    .account-panel.active { display: block; }
    .account-row { display: flex; justify-content: space-between; align-items: center; padding: 16px 0; border-bottom: 1px solid var(--blush); }
    .account-info { line-height: 1.8; }
    .account-who { font-size: 13px; color: var(--dark); letter-spacing: 1px; }
    .account-num { font-family: 'Cormorant Garamond', serif; font-size: 17px; color: var(--text); }
    .account-bank { font-size: 12px; color: var(--light-text); }
    .copy-btn { padding: 8px 16px; border: 1px solid var(--petal); font-size: 11px; letter-spacing: 2px; color: var(--rose); background: white; cursor: pointer; transition: all 0.2s; white-space: nowrap; }
    .copy-btn:hover { background: var(--blush); }
    .copy-btn.copied { background: var(--rose); color: white; border-color: var(--rose); }

    /* ─── RSVP ─── */
    .rsvp-section { background: linear-gradient(160deg, #f8f0ea 0%, #f0e0d6 100%); }
    .rsvp-form { margin-top: 28px; }
    .form-group { margin-bottom: 18px; }
    .form-label { display: block; font-size: 11px; letter-spacing: 3px; color: var(--light-text); margin-bottom: 8px; }
    .form-input, .form-select { width: 100%; padding: 14px 16px; border: 1px solid var(--petal); background: white; font-family: 'Gowun Batang', serif; font-size: 14px; color: var(--dark); outline: none; transition: border-color 0.2s; -webkit-appearance: none; }
    .form-input:focus, .form-select:focus { border-color: var(--rose); }
    .rsvp-btn-row { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 18px; }
    .rsvp-choice { padding: 16px; text-align: center; border: 1px solid var(--petal); font-size: 13px; letter-spacing: 2px; color: var(--light-text); cursor: pointer; background: white; transition: all 0.2s; }
    .rsvp-choice.selected { background: var(--rose); color: white; border-color: var(--rose); }
    .submit-btn { width: 100%; padding: 18px; background: var(--dark); color: var(--cream); font-family: 'Gowun Batang', serif; font-size: 13px; letter-spacing: 4px; border: none; cursor: pointer; transition: background 0.2s; margin-top: 8px; }
    .submit-btn:hover { background: var(--rose); }

    /* ─── CONTACT ─── */
    .contact-row { display: flex; justify-content: space-between; align-items: center; padding: 18px 0; border-bottom: 1px solid var(--blush); }
    .contact-info .contact-role { font-size: 11px; letter-spacing: 2px; color: var(--light-text); margin-bottom: 4px; }
    .contact-info .contact-name { font-size: 16px; color: var(--dark); }
    .contact-btns { display: flex; gap: 8px; }
    .contact-btn { width: 40px; height: 40px; border: 1px solid var(--petal); background: white; display: flex; align-items: center; justify-content: center; cursor: pointer; font-size: 16px; text-decoration: none; transition: all 0.2s; }
    .contact-btn:hover { background: var(--blush); }

    /* ─── FOOTER ─── */
    footer { text-align: center; padding: 40px 32px 60px; border-top: 1px solid var(--petal); opacity: 0; transition: opacity 0.8s ease; }
    footer.visible { opacity: 1; }
    .footer-names { font-family: 'Cormorant Garamond', serif; font-size: 24px; font-style: italic; color: var(--dark); margin-bottom: 8px; }
    .footer-date { font-size: 12px; letter-spacing: 3px; color: var(--light-text); }

    /* ─── KAKAO SHARE ─── */
    .kakao-share-wrap { text-align: center; padding: 32px 0 0; }
    .kakao-share-btn {
      display: inline-flex; align-items: center; gap: 10px;
      background: #FEE500; color: #3A1D1D; border: none;
      padding: 14px 32px; font-family: 'Gowun Batang', serif;
      font-size: 14px; letter-spacing: 2px; cursor: pointer;
      border-radius: 2px; transition: opacity 0.2s; font-weight: bold;
    }
    .kakao-share-btn:hover { opacity: 0.85; }
    .kakao-share-btn img { width: 22px; height: 22px; }

    /* ─── TOAST ─── */
    .toast { position: fixed; bottom: 32px; left: 50%; transform: translateX(-50%) translateY(20px); background: var(--dark); color: var(--cream); padding: 12px 28px; font-size: 12px; letter-spacing: 2px; opacity: 0; transition: all 0.3s; pointer-events: none; z-index: 9998; white-space: nowrap; }
    .toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }

    @keyframes fadeUp { to { opacity: 1; transform: translateY(0); } }
    @keyframes fadeIn { to { opacity: 1; } }
    @keyframes bounce { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(8px); } }
  </style>
</head>
<body>

<!-- ─── HERO ─── -->
<div class="hero">
  <div class="hero-bg-circle c1"></div>
  <div class="hero-bg-circle c2"></div>
  <svg class="floral-tl" viewBox="0 0 160 160" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path d="M0 0 Q80 20 160 80" stroke="#c27b6a" stroke-width="0.5" fill="none"/>
    <path d="M10 0 Q40 40 0 80" stroke="#c27b6a" stroke-width="0.5" fill="none"/>
    <circle cx="28" cy="28" r="18" stroke="#c27b6a" stroke-width="0.4" fill="none"/>
    <circle cx="28" cy="28" r="8" fill="#e8c9b8" opacity="0.4"/>
    <path d="M28 10 Q36 20 28 28 Q20 20 28 10Z" fill="#c27b6a" opacity="0.3"/>
    <path d="M46 28 Q36 36 28 28 Q36 20 46 28Z" fill="#c27b6a" opacity="0.3"/>
    <path d="M28 46 Q20 36 28 28 Q36 36 28 46Z" fill="#c27b6a" opacity="0.3"/>
    <path d="M10 28 Q20 20 28 28 Q20 36 10 28Z" fill="#c27b6a" opacity="0.3"/>
    <circle cx="28" cy="28" r="3" fill="#c27b6a" opacity="0.6"/>
    <circle cx="65" cy="18" r="8" stroke="#c27b6a" stroke-width="0.4" fill="none"/>
    <circle cx="65" cy="18" r="3" fill="#e8c9b8" opacity="0.5"/>
    <path d="M65 10 Q69 14 65 18 Q61 14 65 10Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M73 18 Q69 22 65 18 Q69 14 73 18Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M65 26 Q61 22 65 18 Q69 22 65 26Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M57 18 Q61 14 65 18 Q61 22 57 18Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M0 50 Q20 40 30 60" stroke="#b89468" stroke-width="0.6" fill="none"/>
    <path d="M0 70 Q30 55 40 80" stroke="#b89468" stroke-width="0.6" fill="none"/>
    <path d="M50 0 Q60 30 80 40" stroke="#b89468" stroke-width="0.6" fill="none"/>
    <path d="M70 0 Q75 20 95 30" stroke="#b89468" stroke-width="0.6" fill="none"/>
  </svg>
  <svg class="floral-br" viewBox="0 0 160 160" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path d="M0 0 Q80 20 160 80" stroke="#c27b6a" stroke-width="0.5" fill="none"/>
    <path d="M10 0 Q40 40 0 80" stroke="#c27b6a" stroke-width="0.5" fill="none"/>
    <circle cx="28" cy="28" r="18" stroke="#c27b6a" stroke-width="0.4" fill="none"/>
    <circle cx="28" cy="28" r="8" fill="#e8c9b8" opacity="0.4"/>
    <path d="M28 10 Q36 20 28 28 Q20 20 28 10Z" fill="#c27b6a" opacity="0.3"/>
    <path d="M46 28 Q36 36 28 28 Q36 20 46 28Z" fill="#c27b6a" opacity="0.3"/>
    <path d="M28 46 Q20 36 28 28 Q36 36 28 46Z" fill="#c27b6a" opacity="0.3"/>
    <path d="M10 28 Q20 20 28 28 Q20 36 10 28Z" fill="#c27b6a" opacity="0.3"/>
    <circle cx="28" cy="28" r="3" fill="#c27b6a" opacity="0.6"/>
    <circle cx="65" cy="18" r="8" stroke="#c27b6a" stroke-width="0.4" fill="none"/>
    <circle cx="65" cy="18" r="3" fill="#e8c9b8" opacity="0.5"/>
    <path d="M65 10 Q69 14 65 18 Q61 14 65 10Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M73 18 Q69 22 65 18 Q69 14 73 18Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M65 26 Q61 22 65 18 Q69 22 65 26Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M57 18 Q61 14 65 18 Q61 22 57 18Z" fill="#c27b6a" opacity="0.25"/>
    <path d="M0 50 Q20 40 30 60" stroke="#b89468" stroke-width="0.6" fill="none"/>
    <path d="M0 70 Q30 55 40 80" stroke="#b89468" stroke-width="0.6" fill="none"/>
    <path d="M50 0 Q60 30 80 40" stroke="#b89468" stroke-width="0.6" fill="none"/>
    <path d="M70 0 Q75 20 95 30" stroke="#b89468" stroke-width="0.6" fill="none"/>
  </svg>
  <div class="hero-inner">
    <div class="date-top">2028 · 05 · 21 · SAT</div>
    <div class="hero-divider"></div>
    <div class="couple-names">JongGun<span class="amp">&</span>GyeongEun</div>
    <div class="couple-kr">박종건 · 이경은</div>
    <div class="date-badge">WEDDING INVITATION</div>
  </div>
  <div class="scroll-hint"><span>SCROLL</span><div class="scroll-dot"></div></div>
</div>

<!-- ─── INVITATION TEXT ─── -->
<section id="invite">
  <div class="section-label">Invitation</div>
  <div class="section-title">결혼합니다</div>
  <div class="gold-line"></div>
  <p class="invite-text">
    서로가 마주보며 다져온 사랑을<br>
    이제 함께 걸어갈 큰 사랑으로 키우고자 합니다.<br><br>
    오셔서 저희의 새로운 시작을<br>
    축복해 주시면 감사하겠습니다.<br><br>
    <span style="font-size:13px;color:var(--light-text);letter-spacing:2px;">
      000 · 000의 장남 <strong style="color:var(--dark)">종건</strong><br>
      000 · 000의 장녀 <strong style="color:var(--dark)">경은</strong>
    </span>
  </p>
</section>

<!-- ─── HERO PHOTO ─── -->
<section class="photo-section" style="padding:0; opacity:1; transform:none;">
  <div style="position:relative; overflow:hidden;">
    <img id="heroImg" class="hero-photo" src="" alt="박종건 이경은" onclick="openLightbox(-1)" />
    <div class="photo-caption">박종건 · 이경은</div>
  </div>
</section>

<!-- ─── DATE & TIME ─── -->
<section id="datetime">
  <div class="section-label">Date & Time</div>
  <div class="section-title">일시</div>
  <div class="gold-line"></div>
  <div class="datetime-grid">
    <div class="datetime-item">
      <div class="dt-label">DATE</div>
      <div class="dt-value">5.21</div>
      <div class="dt-sub">2028년 토요일</div>
    </div>
    <div class="dt-sep"></div>
    <div class="datetime-item">
      <div class="dt-label">TIME</div>
      <div class="dt-value">13:00</div>
      <div class="dt-sub">오후 1시</div>
    </div>
  </div>
  <div class="countdown">
    <div class="countdown-item"><span class="countdown-num" id="days">--</span><div class="countdown-label">DAYS</div></div>
    <div class="countdown-sep">:</div>
    <div class="countdown-item"><span class="countdown-num" id="hours">--</span><div class="countdown-label">HRS</div></div>
    <div class="countdown-sep">:</div>
    <div class="countdown-item"><span class="countdown-num" id="mins">--</span><div class="countdown-label">MIN</div></div>
    <div class="countdown-sep">:</div>
    <div class="countdown-item"><span class="countdown-num" id="secs">--</span><div class="countdown-label">SEC</div></div>
  </div>
</section>

<!-- ─── VENUE ─── -->
<section id="venue">
  <div class="section-label">Location</div>
  <div class="section-title">장소</div>
  <div class="gold-line"></div>
  <div class="venue-card">
    <div class="venue-name">그랜드 웨딩홀 · 로즈홀</div>
    <div class="venue-detail">서울특별시 00구 000로 123<br>어디어디어디 1층<br>☎ 02-1234-5678</div>
  </div>
  <div class="map-placeholder" onclick="alert('카카오 지도 API를 연결하세요')"><span>🗺</span><span>지도 보기</span></div>
  <div class="map-btn-row">
    <a class="map-btn" href="https://map.kakao.com" target="_blank">카카오맵</a>
    <a class="map-btn" href="https://naver.me" target="_blank">네이버지도</a>
  </div>
  <div style="margin-top:24px; padding:20px; background:var(--blush); border:1px solid var(--petal);">
    <div style="font-size:12px; letter-spacing:2px; color:var(--rose); margin-bottom:12px;">DIRECTIONS</div>
    <div style="font-size:13px; line-height:2.2; color:var(--text);">
      <strong>지하철</strong><br>2호선 00역 3번 출구에서 도보 5분<br>
      <strong>버스</strong><br>00역 정류장 하차 (140, 342, 3412번)<br>
      <strong>주차</strong><br>건물 내 지하 주차장 이용 (2시간 무료)
    </div>
  </div>
</section>

<!-- ─── GALLERY ─── -->
<section id="gallery">
  <div class="section-label">Gallery</div>
  <div class="section-title">갤러리</div>
  <div class="gold-line"></div>
  <p style="text-align:center; font-size:13px; color:var(--light-text); margin-bottom:8px;">소중한 순간들</p>
  <div class="gallery-grid" id="galleryGrid"></div>
</section>

<!-- ─── ACCOUNT ─── -->
<section id="account">
  <div class="section-label">Gift</div>
  <div class="section-title">마음 전하기</div>
  <div class="gold-line"></div>
  <p style="text-align:center; font-size:13px; color:var(--light-text); margin-bottom:24px;">함께해 주시는 것만으로도 감사합니다</p>
  <div class="account-tabs">
    <div class="account-tab active" onclick="switchTab(this, 'groom')">신랑측</div>
    <div class="account-tab" onclick="switchTab(this, 'bride')">신부측</div>
  </div>
  <div class="account-panel active" id="groom-panel">
    <div class="account-row">
      <div class="account-info"><div class="account-who">신랑 박종건</div><div class="account-num">국민 00030-12-345-456789</div><div class="account-bank">국민은행</div></div>
      <button class="copy-btn" onclick="copyAccount(this, '0003012345456789')">복사</button>
    </div>
    <div class="account-row">
      <div class="account-info"><div class="account-who">아버지 000</div><div class="account-num">국민 000-000-000000</div><div class="account-bank">국민은행</div></div>
      <button class="copy-btn" onclick="copyAccount(this, '000000000000')">복사</button>
    </div>
    <div class="account-row" style="border-bottom:none;">
      <div class="account-info"><div class="account-who">어머니 000</div><div class="account-num">하나 555-444-333222</div><div class="account-bank">하나은행</div></div>
      <button class="copy-btn" onclick="copyAccount(this, '555444333222')">복사</button>
    </div>
  </div>
  <div class="account-panel" id="bride-panel">
    <div class="account-row">
      <div class="account-info"><div class="account-who">신부 이경은</div><div class="account-num">신한 110-470-432538</div><div class="account-bank">신한은행</div></div>
      <button class="copy-btn" onclick="copyAccount(this, '110470432538')">복사</button>
    </div>
    <div class="account-row">
      <div class="account-info"><div class="account-who">아버지 000</div><div class="account-num">우리 111-222-333444</div><div class="account-bank">우리은행</div></div>
      <button class="copy-btn" onclick="copyAccount(this, '111222333444')">복사</button>
    </div>
    <div class="account-row" style="border-bottom:none;">
      <div class="account-info"><div class="account-who">어머니 000</div><div class="account-num">농협 456-7890-12345</div><div class="account-bank">NH농협은행</div></div>
      <button class="copy-btn" onclick="copyAccount(this, '456789012345')">복사</button>
    </div>
  </div>
</section>

<!-- ─── RSVP ─── -->
<section id="rsvp" class="rsvp-section">
  <div class="section-label">RSVP</div>
  <div class="section-title">참석 여부 알리기</div>
  <div class="gold-line"></div>
  <p style="text-align:center; font-size:13px; color:var(--light-text); margin-bottom:4px;">부담 없이 알려주세요 :)</p>
  <p style="text-align:center; font-size:12px; color:var(--light-text); letter-spacing:1px;">10월 10일까지 부탁드립니다</p>
  <div class="rsvp-form">
    <div class="rsvp-btn-row">
      <div class="rsvp-choice selected" onclick="selectRsvp(this)">✓ 참석합니다</div>
      <div class="rsvp-choice" onclick="selectRsvp(this)">✗ 참석이 어렵습니다</div>
    </div>
    <div class="form-group"><label class="form-label">이름</label><input class="form-input" type="text" placeholder="성함을 입력해주세요" /></div>
    <div class="form-group"><label class="form-label">참석 인원</label><select class="form-select"><option>1명</option><option>2명</option><option>3명</option><option>4명 이상</option></select></div>
    <div class="form-group"><label class="form-label">전하고 싶은 말 (선택)</label><input class="form-input" type="text" placeholder="축하 메시지를 남겨주세요" /></div>
    <button class="submit-btn" onclick="submitRsvp()">전송하기</button>
  </div>
</section>

<!-- ─── CONTACT ─── -->
<section id="contact">
  <div class="section-label">Contact</div>
  <div class="section-title">연락하기</div>
  <div class="gold-line"></div>
  <div class="contact-row">
    <div class="contact-info"><div class="contact-role">신랑</div><div class="contact-name">박종건</div></div>
    <div class="contact-btns"><a class="contact-btn" href="tel:010-1234-5678">📞</a><a class="contact-btn" href="sms:010-1234-5678">💬</a></div>
  </div>
  <div class="contact-row">
    <div class="contact-info"><div class="contact-role">신부</div><div class="contact-name">이경은</div></div>
    <div class="contact-btns"><a class="contact-btn" href="tel:010-3118-5475">📞</a><a class="contact-btn" href="sms:010-3118-5475">💬</a></div>
  </div>
  <div class="contact-row">
    <div class="contact-info"><div class="contact-role">신랑측 혼주</div><div class="contact-name">000 · 000</div></div>
    <div class="contact-btns"><a class="contact-btn" href="tel:010-1111-2222">📞</a></div>
  </div>
  <div class="contact-row" style="border-bottom:none;">
    <div class="contact-info"><div class="contact-role">신부측 혼주</div><div class="contact-name">000 · 000</div></div>
    <div class="contact-btns"><a class="contact-btn" href="tel:010-3333-4444">📞</a></div>
  </div>
</section>

<!-- ─── KAKAO SHARE ─── -->
<section id="share">
  <div class="section-label">Share</div>
  <div class="section-title">청첩장 공유하기</div>
  <div class="gold-line"></div>
  <p style="text-align:center; font-size:13px; color:var(--light-text); margin-bottom:4px;">소중한 분들께 전달해 주세요</p>
  <div class="kakao-share-wrap">
    <button class="kakao-share-btn" onclick="shareKakao()">
      <img src="https://developers.kakao.com/assets/img/about/logos/kakaolink/kakaolink_btn_medium.png" alt="kakao" />
      카카오톡으로 공유
    </button>
  </div>
</section>

<!-- ─── FOOTER ─── -->
<footer id="footer">
  <div style="margin-bottom:20px; opacity:0.4;">
    <svg width="40" height="40" viewBox="0 0 40 40">
      <circle cx="20" cy="20" r="14" stroke="#c27b6a" stroke-width="0.6" fill="none"/>
      <path d="M20 6 Q24 12 20 20 Q16 12 20 6Z" fill="#c27b6a" opacity="0.4"/>
      <path d="M34 20 Q28 24 20 20 Q28 16 34 20Z" fill="#c27b6a" opacity="0.4"/>
      <path d="M20 34 Q16 28 20 20 Q24 28 20 34Z" fill="#c27b6a" opacity="0.4"/>
      <path d="M6 20 Q12 16 20 20 Q12 24 6 20Z" fill="#c27b6a" opacity="0.4"/>
      <circle cx="20" cy="20" r="2.5" fill="#c27b6a" opacity="0.7"/>
    </svg>
  </div>
  <div class="footer-names">JongGun & GyeongEun</div>
  <div class="footer-date">2028 · 05 · 21 · SATURDAY 1PM</div>
  <div style="margin-top:20px; font-size:11px; letter-spacing:2px; color:var(--light-text);">그랜드웨딩홀 · 로즈홀</div>
</footer>

<!-- ─── LIGHTBOX ─── -->
<div class="lightbox" id="lightbox">
  <div class="lightbox-img-wrap">
    <img class="lightbox-img" id="lightboxImg" src="" alt="" />
    <div class="lightbox-close" onclick="closeLightbox()">✕</div>
    <div class="lightbox-nav lightbox-prev" onclick="navLightbox(-1)">&#8249;</div>
    <div class="lightbox-nav lightbox-next" onclick="navLightbox(1)">&#8250;</div>
  </div>
  <div class="lightbox-counter" id="lightboxDots"></div>
</div>

<div class="toast" id="toast"></div>

<script>
  // ─── 카카오 초기화 & 공유
  Kakao.init('c64517d05ac5e8fa88a4783d7dec627d');

  function shareKakao() {
    Kakao.Share.sendDefault({
      objectType: 'feed',
      content: {
        title: '박종건 이경은 결혼합니다',
        description: '2028년 5월 21일 토요일 오후 1시 · 그랜드웨딩홀 로즈홀',
        imageUrl: 'https://raw.githubusercontent.com/dlruddmssjs/-/main/KakaoTalk_20260508_135716534_05.jpg',
        link: {
          mobileWebUrl: 'https://dlruddmssjs.github.io/-/',
          webUrl: 'https://dlruddmssjs.github.io/-/',
        },
      },
      buttons: [
        {
          title: '모바일 청첩장 보기',
          link: {
            mobileWebUrl: 'https://dlruddmssjs.github.io/-/',
            webUrl: 'https://dlruddmssjs.github.io/-/',
          },
        },
      ],
    });
  }

  // ─── 갤러리 동적 생성
  window.addEventListener('DOMContentLoaded', () => {
    // 히어로 사진
    document.getElementById('heroImg').src = heroPhoto;

    // 갤러리 그리드
    const grid = document.getElementById('galleryGrid');
    galleryPhotos.forEach((url, i) => {
      const item = document.createElement('div');
      item.className = 'gallery-item';
      item.onclick = () => openLightbox(i);
      item.innerHTML = `<img src="${url}" alt="photo ${i+1}" loading="lazy" /><div class="overlay"></div>`;
      grid.appendChild(item);
    });
  });

  // ─── Lightbox
  let currentIndex = 0;

  function buildDots() {
    const dotsEl = document.getElementById('lightboxDots');
    dotsEl.innerHTML = '';
    galleryPhotos.forEach((_, i) => {
      const d = document.createElement('div');
      d.className = 'lightbox-dot' + (i === currentIndex ? ' active' : '');
      d.onclick = () => goToLightbox(i);
      dotsEl.appendChild(d);
    });
  }

  function openLightbox(idx) {
    // -1이면 히어로 사진 (갤러리 첫번째로 처리)
    currentIndex = idx < 0 ? 0 : idx;
    document.getElementById('lightboxImg').src = galleryPhotos[currentIndex];
    document.getElementById('lightbox').classList.add('active');
    document.body.style.overflow = 'hidden';
    buildDots();
  }

  function closeLightbox() {
    document.getElementById('lightbox').classList.remove('active');
    document.body.style.overflow = '';
  }

  function goToLightbox(idx) {
    currentIndex = idx;
    const img = document.getElementById('lightboxImg');
    img.classList.add('fade');
    setTimeout(() => {
      img.src = galleryPhotos[currentIndex];
      img.classList.remove('fade');
      buildDots();
    }, 200);
  }

  function navLightbox(dir) {
    goToLightbox((currentIndex + dir + galleryPhotos.length) % galleryPhotos.length);
  }

  // 스와이프
  let touchStartX = 0;
  document.getElementById('lightbox').addEventListener('touchstart', e => { touchStartX = e.touches[0].clientX; }, { passive: true });
  document.getElementById('lightbox').addEventListener('touchend', e => {
    const dx = e.changedTouches[0].clientX - touchStartX;
    if (Math.abs(dx) > 40) navLightbox(dx < 0 ? 1 : -1);
  }, { passive: true });

  // 키보드
  document.addEventListener('keydown', e => {
    if (!document.getElementById('lightbox').classList.contains('active')) return;
    if (e.key === 'ArrowLeft') navLightbox(-1);
    if (e.key === 'ArrowRight') navLightbox(1);
    if (e.key === 'Escape') closeLightbox();
  });

  // ─── Intersection Observer
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); observer.unobserve(e.target); } });
  }, { threshold: 0.12 });
  document.querySelectorAll('section, footer').forEach(el => observer.observe(el));

  // ─── Countdown
  const wedding = new Date('2028-05-21T13:00:00');
  function updateCountdown() {
    const diff = wedding - new Date();
    if (diff <= 0) { ['days','hours','mins','secs'].forEach(id => document.getElementById(id).textContent = '0'); return; }
    document.getElementById('days').textContent = String(Math.floor(diff/86400000)).padStart(2,'0');
    document.getElementById('hours').textContent = String(Math.floor((diff%86400000)/3600000)).padStart(2,'0');
    document.getElementById('mins').textContent = String(Math.floor((diff%3600000)/60000)).padStart(2,'0');
    document.getElementById('secs').textContent = String(Math.floor((diff%60000)/1000)).padStart(2,'0');
  }
  updateCountdown(); setInterval(updateCountdown, 1000);

  // ─── Copy
  function copyAccount(btn, number) {
    navigator.clipboard.writeText(number).then(() => {
      btn.textContent = '완료!'; btn.classList.add('copied');
      showToast('계좌번호가 복사되었습니다');
      setTimeout(() => { btn.textContent = '복사'; btn.classList.remove('copied'); }, 2000);
    });
  }

  // ─── Tab
  function switchTab(tab, id) {
    document.querySelectorAll('.account-tab').forEach(t => t.classList.remove('active'));
    document.querySelectorAll('.account-panel').forEach(p => p.classList.remove('active'));
    tab.classList.add('active');
    document.getElementById(id + '-panel').classList.add('active');
  }

  // ─── RSVP
  function selectRsvp(el) { document.querySelectorAll('.rsvp-choice').forEach(c => c.classList.remove('selected')); el.classList.add('selected'); }
  function submitRsvp() { showToast('참석 여부가 전달되었습니다 💌'); }

  // ─── Toast
  function showToast(msg) { const t = document.getElementById('toast'); t.textContent = msg; t.classList.add('show'); setTimeout(() => t.classList.remove('show'), 2500); }
</script>
</body>
</html>
