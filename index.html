<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A&M Code | تطوير وتصميم الحلول البرمجية والمواقع الإلكترونية</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-deep: #050508;
            --bg-card: #0e0e14;
            --bg-card-hover: #161622;
            --burgundy: #990033;
            --burgundy-glow: rgba(153, 0, 51, 0.45);
            --gold-accent: #d4af37;
            --gold-glow: rgba(212, 175, 55, 0.35);
            --text-white: #f8fafc;
            --text-muted: #94a3b8;
            --border-glow: rgba(212, 175, 55, 0.2);
            --glass-bg: rgba(14, 14, 20, 0.88);
        }

        body.light-mode {
            --bg-deep: #f8fafc;
            --bg-card: #ffffff;
            --bg-card-hover: #f1f5f9;
            --burgundy: #990033;
            --burgundy-glow: rgba(153, 0, 51, 0.2);
            --gold-accent: #b8860b;
            --gold-glow: rgba(184, 134, 11, 0.2);
            --text-white: #0f172a;
            --text-muted: #64748b;
            --border-glow: rgba(153, 0, 51, 0.15);
            --glass-bg: rgba(255, 255, 255, 0.9);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Cairo', sans-serif;
            scroll-behavior: smooth;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        body {
            background: linear-gradient(135deg, var(--bg-deep) 0%, var(--bg-card) 100%);
            color: var(--text-white);
            overflow-x: hidden;
            line-height: 1.7;
            min-height: 100vh;
        }

        #binary-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            opacity: 0.04;
            pointer-events: none;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            position: relative;
            z-index: 1;
        }

        /* Navbar Design */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: var(--glass-bg);
            backdrop-filter: blur(20px);
            z-index: 100;
            border-bottom: 1px solid var(--border-glow);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 80px;
        }

        .logo {
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 10px;
            cursor: pointer;
        }

        .logo-img {
            width: 48px;
            height: 48px;
            border-radius: 50%;
            border: 1.5px solid var(--gold-accent);
            object-fit: cover;
            box-shadow: 0 0 12px var(--gold-glow);
            transition: 0.3s ease;
        }

        .logo:hover .logo-img {
            transform: scale(1.08);
            box-shadow: 0 0 18px var(--gold-glow);
        }

        .logo-text { 
            color: var(--text-white); 
            font-size: 1.3rem; 
            font-weight: 800; 
            letter-spacing: 0.5px;
        }

        .nav-links {
            display: flex;
            gap: 25px;
            list-style: none;
            align-items: center;
        }

        .nav-links a {
            color: var(--text-muted);
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            transition: 0.3s ease;
            cursor: pointer;
        }

        .nav-links a:hover, .nav-links a.active-link { color: var(--gold-accent); text-shadow: 0 0 8px var(--gold-glow); }

        .nav-actions {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .theme-toggle-btn {
            background: rgba(153, 0, 51, 0.1);
            border: 1px solid var(--burgundy);
            color: var(--text-white);
            width: 42px;
            height: 42px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            box-shadow: 0 0 12px var(--burgundy-glow);
            transition: 0.3s ease;
        }

        .theme-toggle-btn:hover { transform: scale(1.1); background: var(--burgundy); }

        .btn-order-nav {
            background: linear-gradient(135deg, var(--burgundy), #59001d);
            border: 1px solid var(--gold-accent);
            color: #ffffff;
            padding: 10px 24px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            box-shadow: 0 0 18px var(--burgundy-glow);
            transition: 0.3s ease;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            cursor: pointer;
        }

        .btn-order-nav:hover {
            transform: translateY(-2px);
            box-shadow: 0 0 25px var(--gold-glow);
        }

        /* نظام الصفحات الديناميكي */
        .page-view {
            display: none;
            padding: 150px 0 90px;
            animation: fadeInPage 0.4s cubic-bezier(0.16, 1, 0.3, 1) forwards;
        }

        .page-view.active-page {
            display: block;
        }

        @keyframes fadeInPage {
            from { opacity: 0; transform: translateY(12px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Hero / Gemini Style Home Screen */
        .gemini-hero {
            min-height: 70vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 20px;
        }

        .gemini-welcome-title {
            font-size: 3rem;
            font-weight: 900;
            color: var(--text-white);
            margin-bottom: 40px;
            text-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
        }

        /* تصميم مستطيل البحث الشبيه بـ Gemini تماماً مع إضافة مرفق الصور والميكروفون */
        .gemini-chat-box {
            width: 100%;
            max-width: 750px;
            background: rgba(14, 14, 20, 0.75);
            backdrop-filter: blur(20px);
            border: 1.5px solid var(--border-glow);
            border-radius: 36px;
            padding: 12px 20px;
            display: flex;
            align-items: center;
            gap: 15px;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.5);
            transition: 0.3s ease;
        }

        .gemini-chat-box:focus-within {
            border-color: var(--gold-accent);
            box-shadow: 0 0 30px var(--gold-glow);
            background: rgba(14, 14, 20, 0.95);
        }

        .gemini-action-icon {
            background: transparent;
            border: none;
            color: var(--text-muted);
            font-size: 1.2rem;
            cursor: pointer;
            transition: 0.3s ease;
            width: 36px;
            height: 36px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
        }

        .gemini-action-icon:hover {
            color: var(--gold-accent);
            background: rgba(212, 175, 55, 0.1);
        }

        .gemini-action-icon.recording {
            color: #ff3366 !important;
            background: rgba(255, 51, 102, 0.15) !important;
            animation: pulseRecord 1.5s infinite;
        }

        @keyframes pulseRecord {
            0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(255, 51, 102, 0.4); }
            70% { transform: scale(1.08); box-shadow: 0 0 0 10px rgba(255, 51, 102, 0); }
            100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(255, 51, 102, 0); }
        }

        .gemini-main-input {
            flex: 1;
            background: transparent;
            border: none;
            outline: none;
            color: var(--text-white);
            font-size: 1.05rem;
            font-weight: 600;
            text-align: right;
        }

        .gemini-main-input::placeholder {
            color: var(--text-muted);
            font-weight: 400;
        }

        .gemini-submit-btn {
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--burgundy), var(--gold-accent));
            border: none;
            color: #fff;
            font-size: 1rem;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 0 15px var(--gold-glow);
            transition: 0.3s ease;
            flex-shrink: 0;
        }

        .gemini-submit-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 0 22px var(--gold-glow);
        }

        /* حاوية المعاينة للصور أو الفويس نوت مع مشغل الصوت */
        .image-preview-container {
            margin-top: 15px;
            display: none;
            align-items: center;
            gap: 12px;
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid var(--border-glow);
            border-radius: 16px;
            padding: 10px 18px;
            max-width: 750px;
            width: 100%;
        }

        .image-preview-container.active {
            display: flex;
        }

        .preview-img {
            width: 45px;
            height: 45px;
            border-radius: 8px;
            object-fit: cover;
            border: 1px solid var(--gold-accent);
        }

        /* تصميم مشغل الفويس نوت التفاعلي للسماع */
        .voice-player-wrapper {
            display: flex;
            align-items: center;
            gap: 12px;
            flex: 1;
        }

        .play-voice-btn {
            background: var(--gold-accent);
            border: none;
            color: #000;
            width: 36px;
            height: 36px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 0.95rem;
            transition: 0.3s;
            box-shadow: 0 0 10px var(--gold-glow);
        }

        .play-voice-btn:hover {
            transform: scale(1.1);
        }

        .voice-wave-bars {
            display: flex;
            align-items: center;
            gap: 3px;
            flex: 1;
            height: 20px;
        }

        .wave-bar {
            flex: 1;
            background: var(--gold-accent);
            border-radius: 4px;
            height: 8px;
            animation: wavePulse 1s infinite alternate;
        }

        .wave-bar:nth-child(2) { animation-delay: 0.2s; height: 16px; }
        .wave-bar:nth-child(3) { animation-delay: 0.4s; height: 12px; }
        .wave-bar:nth-child(4) { animation-delay: 0.6s; height: 18px; }
        .wave-bar:nth-child(5) { animation-delay: 0.3s; height: 10px; }

        @keyframes wavePulse {
            0% { opacity: 0.4; transform: scaleY(0.6); }
            100% { opacity: 1; transform: scaleY(1.2); }
        }

        .remove-img-btn {
            background: rgba(255, 51, 102, 0.2);
            border: 1px solid #ff3366;
            color: #ff3366;
            width: 26px;
            height: 26px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            font-size: 0.8rem;
            margin-right: auto;
        }

        .remove-img-btn:hover {
            background: #ff3366;
            color: #fff;
        }

        /* العناوين والأقسام العامة */
        .section-header {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title {
            font-size: 2.4rem;
            font-weight: 900;
            margin-bottom: 12px;
            position: relative;
            display: inline-block;
            color: var(--text-white);
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 4px;
            background: linear-gradient(90deg, var(--burgundy), var(--gold-accent));
            margin: 8px auto 0;
            border-radius: 2px;
        }

        .section-desc { color: var(--text-muted); font-size: 1.05rem; }

        /* Services Grid */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
        }

        .service-card {
            background: var(--bg-card);
            border: 1px solid var(--border-glow);
            border-radius: 20px;
            padding: 35px 25px;
            transition: 0.35s ease;
            box-shadow: 0 10px 30px rgba(0,0,0,0.25);
        }

        .service-card:hover {
            transform: translateY(-6px);
            background: var(--bg-card-hover);
            border-color: var(--gold-accent);
            box-shadow: 0 15px 35px var(--gold-glow);
        }

        .service-icon {
            width: 60px;
            height: 60px;
            background: rgba(212, 175, 55, 0.1);
            border: 1px solid var(--gold-accent);
            border-radius: 14px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.6rem;
            color: var(--gold-accent);
            margin-bottom: 22px;
            box-shadow: 0 0 12px var(--gold-glow);
        }

        .service-card h3 { font-size: 1.3rem; margin-bottom: 10px; font-weight: 700; color: var(--text-white); }
        .service-card p { color: var(--text-muted); font-size: 0.92rem; }

        /* Calculator Section */
        .calculator-section {
            background: var(--bg-card);
            border: 1px solid var(--border-glow);
            border-radius: 24px;
            padding: 40px;
            max-width: 800px;
            margin: 0 auto;
            box-shadow: 0 20px 50px rgba(0,0,0,0.4);
        }

        .calc-result-box {
            background: rgba(212, 175, 55, 0.08);
            border: 1px solid var(--gold-accent);
            border-radius: 16px;
            padding: 20px;
            margin-top: 25px;
            text-align: center;
        }

        .calc-result-box h4 { font-size: 1.25rem; color: var(--gold-accent); margin-bottom: 5px; }

        /* Input Fields */
        .input-group { margin-bottom: 22px; text-align: right; }
        .input-group label { display: block; margin-bottom: 8px; font-weight: 600; color: var(--text-white); font-size: 0.95rem; }
        .input-group input, .input-group textarea, .input-group select {
            width: 100%;
            padding: 15px 18px;
            background: rgba(255, 255, 255, 0.025);
            border: 1.5px solid var(--border-glow);
            border-radius: 14px;
            color: var(--text-white);
            font-size: 0.98rem;
            outline: none;
            transition: 0.3s ease;
        }

        .input-group select option { background-color: #0e0e14; color: #ffffff; padding: 12px; }

        .input-group input:focus, .input-group textarea:focus, .input-group select:focus {
            border-color: var(--gold-accent);
            box-shadow: 0 0 15px var(--gold-glow);
            background: rgba(255, 255, 255, 0.05);
        }

        /* Pricing Grid */
        .pricing-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .price-card {
            background: var(--bg-card);
            border: 1px solid var(--border-glow);
            border-radius: 24px;
            padding: 40px 30px;
            text-align: center;
            position: relative;
            transition: 0.3s ease;
        }

        .price-card.featured {
            border-color: var(--burgundy);
            box-shadow: 0 0 35px var(--burgundy-glow);
            transform: scale(1.02);
        }

        .price-card h3 { font-size: 1.5rem; margin-bottom: 12px; color: var(--text-white); }
        .price-features { list-style: none; margin: 25px 0; text-align: right; }
        .price-features li { margin-bottom: 12px; font-size: 0.93rem; color: var(--text-muted); }
        .price-features li i { color: var(--gold-accent); margin-left: 8px; }

        /* Portfolio */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 25px;
        }

        .portfolio-card {
            background: var(--bg-card);
            border: 1px solid var(--border-glow);
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.25);
            transition: 0.3s ease;
        }

        .portfolio-card:hover { transform: translateY(-5px); border-color: var(--gold-accent); box-shadow: 0 15px 35px var(--gold-glow); }

        .portfolio-img {
            height: 170px;
            background: linear-gradient(135deg, rgba(153, 0, 51, 0.3), rgba(212, 175, 55, 0.2));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.8rem;
            color: var(--text-white);
        }

        .portfolio-info { padding: 22px; }
        .portfolio-info h4 { font-size: 1.15rem; margin-bottom: 8px; color: var(--text-white); }
        .portfolio-info p { color: var(--text-muted); font-size: 0.88rem; }

        /* Wizard & Protection Boxes */
        .wizard-section, .protection-section, .rating-section, .faq-section {
            background: var(--bg-card);
            border: 1px solid var(--border-glow);
            border-radius: 26px;
            padding: 45px;
            max-width: 850px;
            margin: 0 auto;
            box-shadow: 0 25px 60px rgba(0, 0, 0, 0.5);
        }

        .progress-bar-container {
            display: flex;
            justify-content: space-between;
            margin-bottom: 40px;
            position: relative;
            padding: 0 15px;
        }

        .progress-bar-container::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 40px;
            right: 40px;
            height: 2px;
            background: rgba(255, 255, 255, 0.08);
            z-index: 0;
            transform: translateY(-50%);
        }

        .progress-step-item {
            width: 44px;
            height: 44px;
            border-radius: 50%;
            background: var(--bg-deep);
            border: 2px solid rgba(255, 255, 255, 0.12);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 800;
            font-size: 1rem;
            color: var(--text-muted);
            position: relative;
            z-index: 1;
            transition: 0.3s ease;
        }

        .progress-step-item.active {
            border-color: #ff3366;
            background: var(--burgundy);
            color: #ffffff;
            box-shadow: 0 0 20px var(--burgundy-glow);
            transform: scale(1.1);
        }

        .progress-step-item.completed {
            border-color: var(--gold-accent);
            background: var(--gold-accent);
            color: #ffffff;
            box-shadow: 0 0 15px var(--gold-glow);
        }

        .wizard-step { display: none; }
        .wizard-step.active { display: block; animation: fadeInPage 0.3s ease; }

   