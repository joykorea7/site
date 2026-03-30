<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>사장님비서AI - 소상공인 AI 마케팅 서비스</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&family=Montserrat:wght@700;900&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body { font-family: 'Noto Sans KR', sans-serif; color: #111827; }

    /* NAV */
    #navbar {
      position: fixed; top: 0; left: 0; right: 0; z-index: 100;
      padding: 0 20px;
      transition: background 0.3s, box-shadow 0.3s;
    }
    #navbar.scrolled {
      background: rgba(255,255,255,0.95);
      backdrop-filter: blur(12px);
      box-shadow: 0 1px 20px rgba(0,0,0,0.08);
    }
    .nav-inner {
      max-width: 1080px; margin: 0 auto;
      display: flex; align-items: center; justify-content: space-between;
      height: 60px;
    }
    .nav-logo { display: flex; align-items: center; gap: 8px; }
    .nav-logo .name {
      font-weight: 900; font-size: 18px; color: white;
      font-family: 'Montserrat', sans-serif; transition: color 0.3s;
    }
    #navbar.scrolled .nav-logo .name { color: #1e3a8a; }

    .btn-primary {
      background: linear-gradient(135deg, #2563eb, #1d4ed8);
      color: white; border: none; padding: 16px 36px;
      border-radius: 50px; font-size: 16px; font-weight: 700;
      cursor: pointer; transition: all 0.3s;
      box-shadow: 0 8px 24px rgba(37,99,235,0.4);
      font-family: 'Noto Sans KR', sans-serif; text-decoration: none;
      display: inline-block;
    }
    .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 12px 32px rgba(37,99,235,0.55); }
    .btn-outline {
      background: transparent; color: #2563eb; border: 2px solid #2563eb;
      padding: 14px 34px; border-radius: 50px; font-size: 16px; font-weight: 700;
      cursor: pointer; transition: all 0.3s; font-family: 'Noto Sans KR', sans-serif;
    }
    .btn-outline:hover { background: #2563eb; color: white; }
    .btn-ghost {
      background: rgba(255,255,255,0.12); border: 1.5px solid rgba(255,255,255,0.3);
      color: white; padding: 17px 30px; border-radius: 50px;
      font-size: 16px; font-weight: 700; cursor: pointer; transition: all 0.3s;
      font-family: 'Noto Sans KR', sans-serif;
    }
    .btn-ghost:hover { background: rgba(255,255,255,0.22); }

    /* HERO */
    #hero {
      min-height: 100vh;
      background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 50%, #1d4ed8 100%);
      display: flex; align-items: center; padding-top: 60px;
      position: relative; overflow: hidden;
    }
    .grid-pattern {
      position: absolute; inset: 0;
      background-image:
        linear-gradient(rgba(255,255,255,0.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.04) 1px, transparent 1px);
      background-size: 40px 40px;
    }
    .hero-glow {
      position: absolute; inset: 0;
      background: radial-gradient(ellipse at 70% 50%, rgba(59,130,246,0.25) 0%, transparent 65%),
                  radial-gradient(ellipse at 20% 80%, rgba(99,102,241,0.2) 0%, transparent 50%);
    }
    .hero-content { max-width: 1080px; margin: 0 auto; padding: 60px 24px; position: relative; z-index: 1; width: 100%; }
    .hero-text { max-width: 680px; }
    .live-badge {
      display: inline-flex; align-items: center; gap: 8px;
      background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.2);
      border-radius: 50px; padding: 8px 18px; margin-bottom: 28px;
    }
    .pulse-dot { width: 8px; height: 8px; border-radius: 50%; background: #34d399; animation: pulse 2s ease-in-out infinite; }
    @keyframes pulse { 0%,100%{opacity:1;transform:scale(1);}50%{opacity:0.6;transform:scale(1.3);} }
    .hero-title { font-size: 42px; font-weight: 900; color: white; line-height: 1.25; margin-bottom: 24px; }
    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa);
      -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;
    }
    .hero-sub { font-size: 17px; color: rgba(255,255,255,0.75); line-height: 1.8; margin-bottom: 40px; max-width: 500px; }
    .hero-sub strong { color: white; }
    .hero-btns { display: flex; gap: 14px; flex-wrap: wrap; margin-bottom: 48px; }
    .hero-stats { display: flex; gap: 28px; flex-wrap: wrap; }
    .stat-num { color: white; font-size: 26px; font-weight: 900; font-family: 'Montserrat', sans-serif; }
    .stat-label { color: rgba(255,255,255,0.6); font-size: 13px; }

    .float-badge {
      position: absolute; right: 40px; top: 18%; background: white;
      border-radius: 16px; padding: 14px 18px; box-shadow: 0 12px 40px rgba(0,0,0,0.2);
      display: flex; align-items: center; gap: 10px; max-width: 220px;
      animation: floatY 3s ease-in-out infinite;
    }
    .float-badge2 {
      position: absolute; right: 60px; bottom: 18%; background: white;
      border-radius: 16px; padding: 14px 18px; box-shadow: 0 12px 40px rgba(0,0,0,0.2);
      display: flex; align-items: center; gap: 10px; max-width: 220px;
      animation: floatY 3.5s ease-in-out infinite reverse;
    }
    @keyframes floatY { 0%,100%{transform:translateY(0);}50%{transform:translateY(-10px);} }
    .badge-title { font-size: 13px; font-weight: 700; color: #111; }
    .badge-sub { font-size: 11px; color: #6b7280; }

    /* SECTIONS */
    section { padding: 90px 24px; }
    .container { max-width: 1080px; margin: 0 auto; }
    .section-tag {
      display: inline-flex; align-items: center; gap: 6px;
      background: rgba(37,99,235,0.1); color: #2563eb;
      border: 1px solid rgba(37,99,235,0.2);
      padding: 6px 14px; border-radius: 50px; font-size: 13px; font-weight: 600; margin-bottom: 16px;
    }
    .section-title { font-size: 32px; font-weight: 900; color: #0f172a; }
    .section-head { text-align: center; margin-bottom: 52px; }
    .section-desc { color: #6b7280; font-size: 15px; margin-top: 10px; }

    /* PAIN */
    #pain { background: #f8fafc; }
    .pain-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 24px; }
    .pain-card { border-radius: 20px; padding: 32px 28px; transition: all 0.3s; }
    .pain-card:hover { transform: translateY(-6px); box-shadow: 0 20px 40px rgba(29,78,216,0.12); }
    .pain-emoji { font-size: 40px; margin-bottom: 16px; }
    .pain-title { font-size: 18px; font-weight: 800; color: #111827; margin-bottom: 12px; }
    .pain-desc { font-size: 14.5px; color: #4b5563; line-height: 1.7; }
    .pain-bottom { background: linear-gradient(135deg,#1e3a8a,#2563eb); border-radius: 20px; padding: 28px 32px; color: white; text-align: center; margin-top: 44px; font-size: 18px; font-weight: 700; }

    /* FEATURES */
    #features { background: white; }
    .features-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 24px; }
    .feat-card { background: white; border: 1.5px solid #e5e7eb; border-radius: 20px; padding: 32px 28px; position: relative; overflow: hidden; transition: all 0.3s; }
    .feat-card:hover { transform: translateY(-6px); box-shadow: 0 20px 40px rgba(29,78,216,0.12); }
    .feat-deco { position: absolute; top: 0; right: 0; width: 80px; height: 80px; border-radius: 0 20px 0 80px; opacity: 0.6; }
    .feat-icon { font-size: 38px; margin-bottom: 16px; }
    .feat-title { font-size: 18px; font-weight: 800; color: #0f172a; margin-bottom: 10px; }
    .feat-desc { font-size: 14.5px; color: #6b7280; line-height: 1.75; }

    /* PROCESS */
    #process { background: linear-gradient(135deg, #0f172a, #1e3a8a); }
    .process-tag { display: inline-flex; align-items: center; gap: 6px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.2); padding: 6px 14px; border-radius: 50px; font-size: 13px; font-weight: 600; color: white; margin-bottom: 16px; }
    .process-title { font-size: 32px; font-weight: 900; color: white; }
    .steps-wrap { display: flex; align-items: center; gap: 0; justify-content: center; margin-top: 52px; }
    .step { text-align: center; flex: 1; max-width: 260px; padding: 0 16px; }
    .step-circle { width: 80px; height: 80px; border-radius: 50%; background: rgba(255,255,255,0.1); border: 2px solid rgba(255,255,255,0.25); display: flex; align-items: center; justify-content: center; margin: 0 auto 16px; font-size: 32px; }
    .step-num { color: #60a5fa; font-size: 12px; font-weight: 700; margin-bottom: 6px; font-family: 'Montserrat', sans-serif; }
    .step-title { color: white; font-size: 17px; font-weight: 800; margin-bottom: 8px; }
    .step-desc { color: rgba(255,255,255,0.65); font-size: 13.5px; line-height: 1.6; }
    .step-line { flex: 1; height: 2px; background: linear-gradient(90deg, rgba(147,197,253,0.5), rgba(59,130,246,0.8)); min-width: 40px; }
    .process-note { text-align: center; margin-top: 52px; }
    .process-note-inner { display: inline-block; background: rgba(255,255,255,0.08); border: 1px solid rgba(255,255,255,0.15); border-radius: 16px; padding: 20px 32px; color: rgba(255,255,255,0.9); font-size: 15px; font-weight: 600; }

    /* PRICING */
    #pricing { background: #f8fafc; }
    .pricing-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 24px; max-width: 760px; margin: 0 auto; }
    .price-card { background: white; border: 1.5px solid #e5e7eb; border-radius: 24px; padding: 36px 28px; transition: all 0.3s; }
    .price-card:hover { transform: translateY(-6px); box-shadow: 0 20px 40px rgba(29,78,216,0.12); }
    .price-card.hot { background: linear-gradient(135deg,#1e3a8a,#2563eb); border: none; position: relative; overflow: hidden; }
    .price-label { font-size: 13px; font-weight: 700; text-transform: uppercase; letter-spacing: 1px; color: #6b7280; margin-bottom: 8px; }
    .price-card.hot .price-label { color: rgba(255,255,255,0.7); }
    .price-name { font-size: 24px; font-weight: 900; color: #0f172a; margin-bottom: 4px; }
    .price-card.hot .price-name { color: white; }
    .price-big { font-size: 36px; font-weight: 900; color: #1d4ed8; }
    .price-card.hot .price-big { color: white; }
    .price-unit { color: #6b7280; font-size: 14px; }
    .price-card.hot .price-unit { color: rgba(255,255,255,0.7); }
    .price-monthly { font-size: 15px; font-weight: 600; color: #374151; margin-top: 4px; }
    .price-card.hot .price-monthly { color: rgba(255,255,255,0.9); }
    .price-monthly .hl { color: #1d4ed8; font-weight: 900; }
    .price-card.hot .price-monthly .hl { color: #fde68a; }
    .price-features { display: flex; flex-direction: column; gap: 12px; margin: 24px 0 32px; }
    .price-feat { display: flex; align-items: center; gap: 10px; font-size: 14.5px; color: #374151; }
    .price-card.hot .price-feat { color: rgba(255,255,255,0.9); }
    .check { color: #10b981; font-weight: 900; font-size: 16px; }
    .price-card.hot .check { color: #fde68a; }
    .recommended-badge { position: absolute; top: 20px; right: 20px; background: linear-gradient(135deg,#f59e0b,#f97316); color: white; font-size: 12px; font-weight: 700; padding: 4px 12px; border-radius: 50px; }
    .btn-white { width: 100%; padding: 14px; background: white; color: #1d4ed8; border: none; border-radius: 50px; font-size: 16px; font-weight: 700; cursor: pointer; transition: all 0.3s; font-family: 'Noto Sans KR', sans-serif; }
    .btn-white:hover { background: #f0f9ff; transform: translateY(-1px); }

    /* FAQ */
    #faq { background: white; }
    .faq-wrap { border: 1.5px solid #e5e7eb; border-radius: 20px; overflow: hidden; max-width: 680px; margin: 0 auto; }
    .faq-item { border-bottom: 1px solid #e5e7eb; }
    .faq-item:last-child { border-bottom: none; }
    .faq-btn { width: 100%; background: none; border: none; text-align: left; padding: 20px 24px; font-family: 'Noto Sans KR', sans-serif; font-size: 16px; font-weight: 600; color: #111827; cursor: pointer; display: flex; justify-content: space-between; align-items: center; }
    .faq-icon { font-size: 20px; color: #2563eb; transition: transform 0.3s; flex-shrink: 0; margin-left: 12px; display: inline-block; }
    .faq-answer { max-height: 0; overflow: hidden; transition: max-height 0.4s ease; }
    .faq-answer.open { max-height: 200px; }
    .faq-answer p { padding: 0 24px 20px; font-size: 14.5px; color: #6b7280; line-height: 1.8; }

    /* CONTACT */
    #contact { background: linear-gradient(135deg, #f0f9ff, #e0f2fe); }
    .contact-card { background: white; border-radius: 24px; padding: 40px 32px; box-shadow: 0 8px 40px rgba(0,0,0,0.08); max-width: 700px; margin: 0 auto; }
    .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
    .form-group { display: flex; flex-direction: column; gap: 6px; margin-bottom: 16px; }
    .form-label { font-size: 13px; font-weight: 700; color: #374151; }
    .input-field { width: 100%; border: 1.5px solid #e5e7eb; border-radius: 12px; padding: 14px 18px; font-size: 15px; font-family: 'Noto Sans KR', sans-serif; outline: none; transition: border-color 0.2s, box-shadow 0.2s; background: white; }
    .input-field:focus { border-color: #2563eb; box-shadow: 0 0 0 3px rgba(37,99,235,0.1); }
    textarea.input-field { resize: vertical; min-height: 110px; }
    .privacy-note { display: flex; gap: 8px; align-items: flex-start; background: #f0fdf4; border-radius: 12px; padding: 14px 18px; margin-bottom: 16px; }
    .privacy-note p { font-size: 13px; color: #374151; line-height: 1.6; }

    /* 제출 버튼 상태 */
    .btn-submitting { background: linear-gradient(135deg, #93c5fd, #60a5fa) !important; cursor: not-allowed !important; }
    .btn-error { background: linear-gradient(135deg, #ef4444, #dc2626) !important; }

    /* 채널 버튼 */
    .contact-channels { display: flex; gap: 12px; margin-top: 20px; flex-wrap: wrap; }
    .channel-btn {
      flex: 1; min-width: 140px;
      border-radius: 12px; padding: 14px 20px;
      display: flex; align-items: center; justify-content: center;
      gap: 8px; font-size: 14px; font-weight: 700;
      transition: all 0.2s; cursor: pointer;
      font-family: 'Noto Sans KR', sans-serif;
      text-decoration: none; border: 1.5px solid;
    }
    .channel-btn.phone { background: #f8fafc; border-color: #e5e7eb; color: #374151; }
    .channel-btn.phone:hover { background: #e0f2fe; border-color: #93c5fd; }
    .channel-btn.kakao-ch { background: #fef9c3; border-color: #fde047; color: #854d0e; }
    .channel-btn.kakao-ch:hover { background: #fef08a; }
    .channel-btn.kakao-open { background: #fef3c7; border-color: #f59e0b; color: #92400e; }
    .channel-btn.kakao-open:hover { background: #fde68a; }

    /* THANKS */
    .thanks { text-align: center; padding: 52px 32px; background: white; border-radius: 24px; max-width: 700px; margin: 0 auto; box-shadow: 0 8px 40px rgba(0,0,0,0.08); }
    .thanks-emoji { font-size: 52px; margin-bottom: 20px; }
    .thanks h3 { font-size: 22px; font-weight: 900; color: #0f172a; margin-bottom: 12px; }
    .thanks p { color: #6b7280; font-size: 15px; line-height: 1.8; }
    .thanks .kakao-id { color: #1d4ed8; font-weight: 700; }
    .thanks-channels { display: flex; gap: 12px; justify-content: center; margin-top: 24px; flex-wrap: wrap; }

    /* FOOTER */
    footer { background: #0f172a; color: rgba(255,255,255,0.5); padding: 32px 24px; text-align: center; }
    footer .footer-logo { font-size: 20px; margin-bottom: 8px; }
    footer p { font-size: 13px; }
    footer .footer-sub { font-size: 12px; margin-top: 6px; }

    /* FLOATING */
    #floating-cta {
      position: fixed; bottom: 80px; right: 20px; z-index: 999;
      background: linear-gradient(135deg, #10b981, #059669);
      color: white; border: none; border-radius: 50px; padding: 14px 22px;
      font-family: 'Noto Sans KR', sans-serif; font-size: 15px; font-weight: 700;
      cursor: pointer; box-shadow: 0 8px 24px rgba(16,185,129,0.45);
      display: flex; align-items: center; gap: 8px; transition: all 0.3s; text-decoration: none;
    }
    #floating-cta:hover { transform: translateY(-2px); box-shadow: 0 12px 32px rgba(16,185,129,0.6); }
    #floating-phone {
      position: fixed; bottom: 24px; right: 20px; z-index: 999;
      background: linear-gradient(135deg, #2563eb, #1d4ed8);
      color: white; border: none; border-radius: 50px; padding: 14px 22px;
      font-family: 'Noto Sans KR', sans-serif; font-size: 15px; font-weight: 700;
      cursor: pointer; box-shadow: 0 8px 24px rgba(37,99,235,0.45);
      display: flex; align-items: center; gap: 8px; transition: all 0.3s; text-decoration: none;
    }
    #floating-phone:hover { transform: translateY(-2px); box-shadow: 0 12px 32px rgba(37,99,235,0.6); }

    /* FADE IN */
    .fade-in { opacity: 0; transform: translateY(30px); transition: opacity 0.7s ease, transform 0.7s ease; }
    .fade-in.visible { opacity: 1; transform: translateY(0); }

    /* TOAST */
    #toast {
      position: fixed; bottom: 160px; left: 50%; transform: translateX(-50%) translateY(20px);
      background: #111827; color: white; padding: 12px 24px; border-radius: 50px;
      font-size: 14px; font-weight: 600; opacity: 0; transition: all 0.3s; z-index: 9999;
      pointer-events: none; white-space: nowrap;
    }
    #toast.show { opacity: 1; transform: translateX(-50%) translateY(0); }

    /* RESPONSIVE */
    @media (max-width: 640px) {
      .hero-title { font-size: 28px !important; }
      .hero-sub { font-size: 15px !important; }
      .section-title { font-size: 24px !important; }
      .features-grid { grid-template-columns: 1fr !important; }
      .pricing-grid { grid-template-columns: 1fr !important; }
      .form-row { grid-template-columns: 1fr !important; }
      .steps-wrap { flex-direction: column !important; align-items: center !important; }
      .step-line { display: none !important; }
      .float-badge, .float-badge2 { display: none !important; }
      .hero-content { padding: 40px 20px !important; }
      section { padding: 60px 20px !important; }
      #floating-cta { bottom: 76px; font-size: 13px; padding: 12px 18px; }
      #floating-phone { font-size: 13px; padding: 12px 18px; }
    }
  </style>
</head>
<body>

<!-- ============================
     ⚙️ 설정: Apps Script 배포 후
     웹 앱 URL을 아래에 붙여넣으세요
============================= -->
<script>
  const SCRIPT_URL = '여기에_Apps_Script_웹앱_URL_붙여넣기';
  const PHONE_NUMBER = '07079541417';         // 전화번호 (숫자만)
  const PHONE_DISPLAY = '070-7954-1417';      // 화면에 표시할 번호
  const KAKAO_CHANNEL = 'http://pf.kakao.com/_CxmTun/chat';  // 카카오 채널
</script>

<!-- NAVBAR -->
<nav id="navbar">
  <div class="nav-inner">
    <div class="nav-logo">
      <span style="font-size:22px;">🤖</span>
      <span class="name">사장님비서AI</span>
    </div>
    <button class="btn-primary" style="padding:9px 20px;font-size:14px;" onclick="goTo('contact')">무료 상담 신청</button>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="grid-pattern"></div>
  <div class="hero-glow"></div>
  <div class="hero-content">
    <div class="hero-text">
      <div class="live-badge">
        <div class="pulse-dot"></div>
        <span style="color:rgba(255,255,255,0.9);font-size:13px;font-weight:600;">지금 무료 상담 진행 중</span>
      </div>
      <h1 class="hero-title">
        사장님은 요리하세요,<br>
        <span class="gradient-text">손님은 AI가</span><br>
        모셔옵니다
      </h1>
      <p class="hero-sub">
        사진 한 장으로 인스타·유튜브·틱톡 영상 자동 제작 &amp; 배포.<br>
        포털 지도 등록부터 AI 상담봇까지, <strong>월 5만 원</strong>부터 시작하세요.
      </p>
      <div class="hero-btns">
        <button class="btn-primary" style="font-size:17px;padding:17px 38px;" onclick="goTo('contact')">🎁 무료 상담 신청하기</button>
        <button class="btn-ghost" onclick="goTo('features')">서비스 알아보기 →</button>
      </div>
      <div class="hero-stats">
        <div><div class="stat-num">500+</div><div class="stat-label">등록 매장</div></div>
        <div><div class="stat-num">98%</div><div class="stat-label">고객 만족도</div></div>
        <div><div class="stat-num">10분</div><div class="stat-label">AI 영상 완성</div></div>
      </div>
    </div>
    <div class="float-badge">
      <span style="font-size:26px;">🎬</span>
      <div><div class="badge-title">AI 영상 완성!</div><div class="badge-sub">방금 치킨집 사장님 완료</div></div>
    </div>
    <div class="float-badge2">
      <span style="font-size:26px;">📈</span>
      <div><div class="badge-title">매출 23% 증가</div><div class="badge-sub">등록 3개월 만에</div></div>
    </div>
  </div>
</section>

<!-- PAIN POINTS -->
<section id="pain">
  <div class="container">
    <div class="section-head fade-in">
      <div class="section-tag">🤔 사장님 이런 고민 있으시죠?</div>
      <h2 class="section-title">홍보는 하고 싶은데<br>현실이 너무 힘드시죠</h2>
    </div>
    <div class="pain-grid">
      <div class="pain-card fade-in" style="background:#fff7ed;border:1.5px solid #fed7aa;">
        <div class="pain-emoji">😓</div>
        <h3 class="pain-title">홍보할 시간이 없어요</h3>
        <p class="pain-desc">하루 종일 주방과 홀에서 뛰다 보면 SNS 올릴 틈도 없죠. 그렇다고 안 하자니 경쟁에 뒤처지는 것 같고…</p>
      </div>
      <div class="pain-card fade-in" style="background:#fef2f2;border:1.5px solid #fecaca;">
        <div class="pain-emoji">💸</div>
        <h3 class="pain-title">마케팅 업체는 너무 비싸요</h3>
        <p class="pain-desc">광고 대행사에 맡기면 월 수백만 원. 소상공인 입장에선 그림의 떡이었죠. 효과도 불투명하고요.</p>
      </div>
      <div class="pain-card fade-in" style="background:#f0fdf4;border:1.5px solid #bbf7d0;">
        <div class="pain-emoji">🤯</div>
        <h3 class="pain-title">IT는 너무 어려워요</h3>
        <p class="pain-desc">네이버 플레이스, 인스타그램, 카카오채널… 뭐가 뭔지 모르겠고, 배울 시간도 없어요.</p>
      </div>
    </div>
    <div class="pain-bottom fade-in">
      ✅ 사장님비서AI가 이 세 가지 문제를 <span style="color:#fde68a;">한 번에</span> 해결해드립니다
    </div>
  </div>
</section>

<!-- FEATURES -->
<section id="features">
  <div class="container">
    <div class="section-head fade-in">
      <div class="section-tag">⚡ 핵심 서비스</div>
      <h2 class="section-title">이 모든 게 하나의 서비스에</h2>
    </div>
    <div class="features-grid">
      <div class="feat-card fade-in">
        <div class="feat-deco" style="background:#dbeafe;"></div>
        <div class="feat-icon">🗺️</div>
        <h3 class="feat-title">3대 포털 완전 등록</h3>
        <p class="feat-desc">네이버·카카오·구글 지도 및 검색에 내 가게가 자동 노출. 예약·쿠폰 세팅까지 한 번에.</p>
      </div>
      <div class="feat-card fade-in">
        <div class="feat-deco" style="background:#fce7f3;"></div>
        <div class="feat-icon">🤖</div>
        <h3 class="feat-title">AI 카카오 상담봇</h3>
        <p class="feat-desc">24시간 손님 문의를 AI가 자동 응대. Kanana 연동으로 예약·메뉴 안내를 실시간 처리.</p>
      </div>
      <div class="feat-card fade-in">
        <div class="feat-deco" style="background:#dcfce7;"></div>
        <div class="feat-icon">📱</div>
        <h3 class="feat-title">070 비즈니스 폰</h3>
        <p class="feat-desc">통화 녹음, 부재 자동 문자 발송. 매장 전용 번호로 전문적인 이미지까지 UP.</p>
      </div>
      <div class="feat-card fade-in">
        <div class="feat-deco" style="background:#fef9c3;"></div>
        <div class="feat-icon">🎬</div>
        <h3 class="feat-title">AI 자동 영상 마케팅</h3>
        <p class="feat-desc">사진 1장만 보내세요. AI가 인스타·유튜브·틱톡 영상을 만들고 자동 업로드까지!</p>
      </div>
    </div>
  </div>
</section>

<!-- PROCESS -->
<section id="process">
  <div class="container">
    <div class="section-head fade-in">
      <div class="process-tag">🎬 AI 영상 자동화 프로세스</div>
      <h2 class="process-title">사진 한 장이면 끝,<br><span class="gradient-text">나머지는 AI가 알아서</span></h2>
    </div>
    <div class="steps-wrap">
      <div class="step fade-in">
        <div class="step-circle">📸</div>
        <div class="step-num">STEP 01</div>
        <h3 class="step-title">사진/영상 전송</h3>
        <p class="step-desc">카카오톡으로 오늘의 메뉴 사진 한 장 전송</p>
      </div>
      <div class="step-line"></div>
      <div class="step fade-in">
        <div class="step-circle">✨</div>
        <div class="step-num">STEP 02</div>
        <h3 class="step-title">AI 영상 제작</h3>
        <p class="step-desc">AI가 10분 안에 홍보 영상 자동 생성</p>
      </div>
      <div class="step-line"></div>
      <div class="step fade-in">
        <div class="step-circle">🚀</div>
        <div class="step-num">STEP 03</div>
        <h3 class="step-title">자동 업로드</h3>
        <p class="step-desc">인스타·유튜브·틱톡에 동시 자동 업로드</p>
      </div>
    </div>
    <div class="process-note fade-in">
      <div class="process-note-inner">
        ⏱ 평균 제작 시간: <span style="color:#fde68a;font-weight:900;">10분 이내</span> &nbsp;|&nbsp; 월 최대 <span style="color:#86efac;font-weight:900;">30개</span> 콘텐츠 자동 배포
      </div>
    </div>
  </div>
</section>

<!-- PRICING -->
<section id="pricing">
  <div class="container">
    <div class="section-head fade-in">
      <div class="section-tag">💰 투명한 요금제</div>
      <h2 class="section-title">부담 없이 시작하세요</h2>
      <p class="section-desc">숨은 비용 없이, 딱 두 가지 플랜만 있습니다</p>
    </div>
    <div class="pricing-grid">
      <div class="price-card fade-in">
        <div class="price-label">Basic</div>
        <div class="price-name">기본 패키지</div>
        <div style="margin-bottom:24px;">
          <span class="price-big">10만</span><span class="price-unit"> 원 구축</span>
          <div class="price-monthly">+ 월 <span class="hl">5만 원</span> 관리비</div>
        </div>
        <div class="price-features">
          <div class="price-feat"><span class="check">✓</span> 홈페이지 제작</div>
          <div class="price-feat"><span class="check">✓</span> 3대 포털 등록</div>
          <div class="price-feat"><span class="check">✓</span> 네이버 플레이스 세팅</div>
          <div class="price-feat"><span class="check">✓</span> 070 비즈니스 폰</div>
          <div class="price-feat"><span class="check">✓</span> 기본 SNS 관리</div>
        </div>
        <button class="btn-outline" style="width:100%;padding:14px;" onclick="goTo('contact')">이 플랜 시작하기</button>
      </div>
      <div class="price-card hot fade-in">
        <div class="recommended-badge">🔥 추천</div>
        <div class="price-label">All-in-One</div>
        <div class="price-name">풀패키지</div>
        <div style="margin-bottom:24px;">
          <span class="price-big">30만</span><span class="price-unit"> 원 구축</span>
          <div class="price-monthly">+ 월 <span class="hl">10만 원</span> AI 자동화</div>
        </div>
        <div class="price-features">
          <div class="price-feat"><span class="check">✓</span> 기본 패키지 전체 포함</div>
          <div class="price-feat"><span class="check">✓</span> 카카오 AI 상담봇 연동</div>
          <div class="price-feat"><span class="check">✓</span> 🤖 AI 영상 자동 제작</div>
          <div class="price-feat"><span class="check">✓</span> 인스타·유튜브·틱톡 자동 업로드</div>
          <div class="price-feat"><span class="check">✓</span> 월간 성과 리포트</div>
        </div>
        <button class="btn-white" onclick="goTo('contact')">풀패키지 시작하기</button>
      </div>
    </div>
  </div>
</section>

<!-- FAQ -->
<section id="faq">
  <div class="container">
    <div class="section-head fade-in" style="max-width:680px;margin:0 auto 52px;">
      <div class="section-tag">❓ 자주 묻는 질문</div>
      <h2 class="section-title">궁금한 점이 있으신가요?</h2>
    </div>
    <div class="faq-wrap fade-in">
      <div class="faq-item">
        <button class="faq-btn" onclick="toggleFaq(0)">
          <span>컴퓨터를 전혀 몰라도 이용할 수 있나요?</span>
          <span class="faq-icon" id="fi0">+</span>
        </button>
        <div class="faq-answer" id="fa0">
          <p>물론입니다! 모든 초기 세팅은 저희가 대신 해드립니다. 사장님은 사진 한 장만 카카오톡으로 보내주시면 끝. 스마트폰 문자 정도만 보내실 수 있으면 충분합니다.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-btn" onclick="toggleFaq(1)">
          <span>계약 기간이 있나요? 중간에 그만둘 수 있나요?</span>
          <span class="faq-icon" id="fi1">+</span>
        </button>
        <div class="faq-answer" id="fa1">
          <p>최소 계약 기간은 없습니다. 월 단위 구독으로 언제든지 해지 가능합니다. 다만, 구축비는 환불이 어렵습니다.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-btn" onclick="toggleFaq(2)">
          <span>AI가 만든 영상이 어색하지 않나요?</span>
          <span class="faq-icon" id="fi2">+</span>
        </button>
        <div class="faq-answer" id="fa2">
          <p>최신 생성형 AI 기술을 활용해 자연스럽고 트렌디한 영상을 제작합니다. 실제 업장 사진으로 만든 영상이라 훨씬 현실적입니다. 샘플 영상을 요청하시면 무료로 미리 확인해드립니다.</p>
        </div>
      </div>
      <div class="faq-item">
        <button class="faq-btn" onclick="toggleFaq(3)">
          <span>인스타그램 계정이 없어도 되나요?</span>
          <span class="faq-icon" id="fi3">+</span>
        </button>
        <div class="faq-answer" id="fa3">
          <p>저희가 신규 계정 생성부터 프로필 세팅까지 대신 해드립니다. 기존 계정이 있으면 연동해서 관리도 가능합니다.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container">
    <div class="section-head fade-in">
      <div class="section-tag">📞 무료 상담</div>
      <h2 class="section-title">지금 바로 시작해보세요</h2>
      <p class="section-desc">상담은 무료입니다. 부담 없이 연락 주세요 😊</p>
    </div>

    <!-- 상담 신청 폼 -->
    <div id="contact-form" class="contact-card fade-in">
      <div class="form-row">
        <div class="form-group">
          <label class="form-label">이름 *</label>
          <input class="input-field" type="text" id="inp-name" placeholder="홍길동" />
        </div>
        <div class="form-group">
          <label class="form-label">연락처 *</label>
          <input class="input-field" type="tel" id="inp-phone" placeholder="010-0000-0000" />
        </div>
      </div>
      <div class="form-group">
        <label class="form-label">매장 종류</label>
        <input class="input-field" type="text" id="inp-store" placeholder="예: 치킨집, 카페, 고깃집…" />
      </div>
      <div class="form-group">
        <label class="form-label">문의사항</label>
        <textarea class="input-field" id="inp-msg" placeholder="궁금한 점이나 현재 상황을 자유롭게 적어주세요."></textarea>
      </div>
      <div class="privacy-note">
        <span style="font-size:18px;flex-shrink:0;">✅</span>
        <p>상담 신청 정보는 서비스 안내 목적으로만 사용되며 제3자에게 제공되지 않습니다.</p>
      </div>
      <button class="btn-primary" id="submit-btn" style="width:100%;font-size:17px;padding:17px;" onclick="submitForm()">
        무료 상담 신청하기 →
      </button>

      <!-- 채널 버튼 3종 -->
      <div class="contact-channels">
        <a id="phone-btn" href="tel:07079541417" class="channel-btn phone">
          📞 070-7954-1417
        </a>
        <a id="kakao-btn" href="http://pf.kakao.com/_CxmTun/chat" target="_blank" rel="noopener noreferrer" class="channel-btn kakao-ch">
          💬 카카오 채널 상담
        </a>
      </div>
    </div>

    <!-- 제출 완료 화면 -->
    <div id="contact-thanks" class="thanks" style="display:none;">
      <div class="thanks-emoji">🎉</div>
      <h3>상담 신청이 완료됐습니다!</h3>
      <p>
        영업일 기준 <strong>24시간 내</strong>에 문자 또는 전화로 연락드리겠습니다.<br>
        급하시면 아래 버튼으로 바로 연락해보세요!
      </p>
      <div class="thanks-channels">
        <a href="tel:07079541417" class="channel-btn phone" style="min-width:160px;">
          📞 070-7954-1417
        </a>
        <a href="http://pf.kakao.com/_CxmTun/chat" target="_blank" rel="noopener noreferrer" class="channel-btn kakao-ch" style="min-width:160px;">
          💬 카카오 채널 상담
        </a>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">🤖 사장님비서AI</div>
  <p>© 2025 사장님비서AI. All rights reserved.</p>
  <p class="footer-sub">대표번호: 070-7954-1417</p>
</footer>

<!-- 플로팅 버튼 2개 -->
<a href="http://pf.kakao.com/_CxmTun/chat" target="_blank" rel="noopener noreferrer" id="floating-cta">
  💬 카카오 상담
</a>
<a href="tel:07079541417" id="floating-phone">
  📞 전화 연결
</a>

<!-- 토스트 메시지 -->
<div id="toast"></div>

<script>
  // ─── 스크롤 시 네비바 스타일 변경 ───
  window.addEventListener('scroll', () => {
    document.getElementById('navbar').classList.toggle('scrolled', window.scrollY > 60);
  });

  // ─── 부드러운 스크롤 ───
  function goTo(id) {
    document.getElementById(id)?.scrollIntoView({ behavior: 'smooth' });
  }

  // ─── 스크롤 fade-in 애니메이션 ───
  const observer = new IntersectionObserver(
    entries => entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); }),
    { threshold: 0.12 }
  );
  document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

  // ─── FAQ 토글 ───
  let openFaq = null;
  function toggleFaq(i) {
    if (openFaq === i) {
      document.getElementById('fa' + i).classList.remove('open');
      document.getElementById('fi' + i).style.transform = 'rotate(0deg)';
      openFaq = null;
    } else {
      if (openFaq !== null) {
        document.getElementById('fa' + openFaq).classList.remove('open');
        document.getElementById('fi' + openFaq).style.transform = 'rotate(0deg)';
      }
      document.getElementById('fa' + i).classList.add('open');
      document.getElementById('fi' + i).style.transform = 'rotate(45deg)';
      openFaq = i;
    }
  }

  // ─── 토스트 메시지 ───
  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    setTimeout(() => t.classList.remove('show'), 3000);
  }

  // ─── 상담 신청 폼 제출 → 구글 시트 저장 ───
  async function submitForm() {
    const name  = document.getElementById('inp-name').value.trim();
    const phone = document.getElementById('inp-phone').value.trim();
    const store = document.getElementById('inp-store').value.trim();
    const msg   = document.getElementById('inp-msg').value.trim();

    if (!name)  { showToast('⚠️ 이름을 입력해주세요'); return; }
    if (!phone) { showToast('⚠️ 연락처를 입력해주세요'); return; }

    // SCRIPT_URL 미설정 시 안내
    if (SCRIPT_URL === 'https://script.google.com/macros/s/AKfycbxJfCPY4d8KLOMTxLj41Bt38qHvf3kXUyNAaWJbvpt_IJs_E1Ac-BjaCqGwJzclZV7c/exec') {
      // 개발/테스트용: URL 미설정 시에도 완료 화면은 보여줌
      document.getElementById('contact-form').style.display = 'none';
      document.getElementById('contact-thanks').style.display = 'block';
      showToast('✅ 상담 신청 완료! (시트 연동 전)');
      return;
    }

    const btn = document.getElementById('submit-btn');
    btn.textContent = '전송 중…';
    btn.classList.add('btn-submitting');
    btn.disabled = true;

    try {
      await fetch(SCRIPT_URL, {
        method: 'POST',
        mode: 'no-cors',           // Apps Script CORS 우회
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ name, phone, store, msg })
      });
      // no-cors 모드에서는 응답 확인 불가 → 성공으로 처리
      document.getElementById('contact-form').style.display = 'none';
      document.getElementById('contact-thanks').style.display = 'block';
      document.getElementById('contact-thanks').scrollIntoView({ behavior: 'smooth', block: 'center' });

    } catch (err) {
      btn.textContent = '오류가 발생했습니다. 다시 시도해주세요';
      btn.classList.remove('btn-submitting');
      btn.classList.add('btn-error');
      btn.disabled = false;
      setTimeout(() => {
        btn.textContent = '무료 상담 신청하기 →';
        btn.classList.remove('btn-error');
      }, 3000);
    }
  }
</script>
</body>
</html>
