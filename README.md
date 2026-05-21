<!--DOCTYPE html-->
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدرسة دير أبي سعيد الثانوية للبنين - الرئيسية</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Cairo', sans-serif; }
        body { background-color: #f8f9fa; color: #333; }
        .navbar { position: fixed; top: 0; width: 100%; background-color: #ffffff; box-shadow: 0 4px 10px rgba(0,0,0,0.1); padding: 15px 0; z-index: 1000; }
        .nav-container { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 0 20px; }
        .logo { font-size: 24px; font-weight: bold; color: #2c3e50; text-decoration: none; }
        .nav-links { display: flex; list-style: none; }
        .nav-links li a { color: #2c3e50; text-decoration: none; padding: 10px 15px; transition: color 0.3s; }
        .nav-links li a:hover, .nav-links li a.active { color: #3498db; font-weight: bold; }
        .hero-section { height: 75vh; background: linear-gradient(135deg, #2c3e50, #3498db); display: flex; justify-content: center; align-items: center; text-align: center; color: white; padding: 0 20px; margin-top: 60px; }
        .hero-content h1 { font-size: 40px; margin-bottom: 20px; line-height: 1.4; }
        .hero-content p { font-size: 18px; margin-bottom: 30px; max-width: 600px; margin: 0 auto; }
        .btn-primary { background-color: #e74c3c; color: white; padding: 12px 30px; text-decoration: none; border-radius: 25px; font-weight: bold; transition: all 0.3s; display: inline-block; }
        .btn-primary:hover { background-color: #c0392b; transform: scale(1.05); }
        .services-section { padding: 80px 20px; max-width: 1200px; margin: 0 auto; text-align: center; }
        .section-title { font-size: 32px; margin-bottom: 50px; color: #2c3e50; }
        .cards-container { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; }
        .card { background: white; padding: 30px 20px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.05); transition: transform 0.3s; }
        .card:hover { transform: translateY(-10px); }
        .card h3 { margin-bottom: 15px; color: #3498db; }
        .main-footer { background-color: #2c3e50; color: #ffffff; padding: 30px 20px; margin-top: 50px; text-align: center; }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <a href="index.html" class="logo">مدرسة دير أبي سعيد</a>
            <ul class="nav-links">
                <li><a href="index.html" class="active">الرئيسية</a></li>
                <li><a href="about.html">من نحن</a></li>
                <li><a href="classes.html">الصفوف</a></li>
            </ul>
        </div>
    </nav>
    <header class="hero-section">
        <div class="hero-content">
            <h1>مرحباً بكم في موقع مدرسة دير أبي سعيد الثانوية للبنين</h1>
            <p>نحو بيئة تعليمية ذكية ومتميزة تدعم مسيرة أبنائنا الطلبة بأحدث التقنيات.</p>
            <a href="classes.html" class="btn-primary">استكشف الصفوف والشعب</a>
        </div>
    </header>
    <section class="services-section">
        <h2 class="section-title">لماذا مدرستنا؟</h2>
        <div class="cards-container">
            <div class="card">
                <div style="font-size: 40px; margin-bottom: 15px;">👨‍🏫</div>
                <h3>تعليم متميز</h3>
                <p>مناهج دراسية قوية ونخبة من المعلمين الأكفاء ذوي الخبرة العالية في لواء الكورة.</p>
            </div>
            <div class="card">
                <div style="font-size: 40px; margin-bottom: 15px;">🔬</div>
                <h3>بيئة تفاعلية</h3>
                <p>مختبرات علمية وحاسوبية مجهزة بالكامل لتطبيق الأنشطة والابتكارات الرقمية.</p>
            </div>
            <div class="card">
                <div style="font-size: 40px; margin-bottom: 15px;">🤝</div>
                <h3>متابعة مستمرة</h3>
                <p>تواصل دائم وبناء بين الإدارة وأولياء الأمور لضمان مصلحة الطالب.</p>
            </div>
        </div>
    </section>
    <footer class="main-footer">
        <p>جميع الحقوق محفوظة &copy; 2026 | مدرسة دير أبي سعيد الثانوية للبنين</p>
    </footer>
</body>
</html>
