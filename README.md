# Darul-ilm-Islamic-online-academy
Index.html<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darul Ilm Academy - دارالعلوم اسلامک اکیڈمی</title>
    <!-- Google Fonts for beautiful Urdu Typography -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;700&family=Noto+Sans+Arabic:wght@400;700&display=swap" rel="stylesheet">
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-blue: #0b1b3d;
            --accent-gold: #dfb143;
            --light-gold: #f4dc96;
            --white: #ffffff;
            --text-dark: #333333;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Noto Sans Arabic', sans-serif;
            background-color: #f9f9f9;
            color: var(--text-dark);
            line-height: 1.8;
        }

        .urdu-nastaliq {
            font-family: 'Noto Nastaliq Urdu', serif;
        }

        /* Header / Hero Section */
        header {
            background-color: var(--primary-blue);
            color: var(--white);
            text-align: center;
            padding: 3rem 1rem;
            border-bottom: 8px solid var(--accent-gold);
            position: relative;
        }

        .logo-text {
            font-size: 1.5rem;
            color: var(--accent-gold);
            letter-spacing: 1px;
            margin-bottom: 1rem;
            text-transform: uppercase;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--light-gold);
        }

        header p {
            font-size: 1.3rem;
            max-width: 600px;
            margin: 0 auto;
        }

        /* Main Container */
        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        /* Section Styling */
        .course-section {
            background: var(--white);
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            padding: 2rem;
            margin-bottom: 2rem;
            border-right: 5px solid var(--accent-gold);
        }

        .section-title {
            color: var(--primary-blue);
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            border-bottom: 2px solid var(--light-gold);
            padding-bottom: 0.5rem;
            display: inline-block;
        }

        /* Course List grid */
        .course-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .course-card {
            background: #fdfdfd;
            border: 1px solid #eaeaea;
            border-radius: 6px;
            padding: 1.2rem;
            transition: transform 0.3s ease;
        }

        .course-card:hover {
            transform: translateY(-3px);
            border-color: var(--accent-gold);
        }

        .course-card h3 {
            color: var(--primary-blue);
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .course-card p {
            font-size: 0.95rem;
            color: #666;
        }

        .meta-info {
            font-weight: bold;
            color: var(--accent-gold);
        }

        /* Admission Call to Action */
        .cta-box {
            background-color: var(--accent-gold);
            color: var(--primary-blue);
            text-align: center;
            padding: 1.5rem;
            border-radius: 8px;
            font-size: 1.5rem;
            font-weight: bold;
            margin: 2rem 0;
        }

        /* Footer / Contact Details */
        footer {
            background-color: var(--primary-blue);
            color: var(--white);
            padding: 3rem 1rem;
            text-align: center;
        }

        .contact-info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1.1rem;
        }

        .contact-item a {
            color: var(--light-gold);
            text-decoration: none;
            transition: color 0.2s;
        }

        .contact-item a:hover {
            color: var(--white);
        }

        .footer-note {
            font-size: 1.1rem;
            color: var(--light-gold);
            border-top: 1px solid rgba(255,255,255,0.1);
            padding-top: 1.5rem;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            .contact-info { flex-direction: column; gap: 1rem; }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo-text">Darul ilm academy</div>
        <h1 class="urdu-nastaliq">دارالعلوم اسلامک اکیڈمی کے تحت</h1>
        <p class="urdu-nastaliq">مندرجہ ذیل کورسز کروائے جاتے ہیں</p>
    </header>

    <div class="container">

        <!-- Regular/Main Courses Section -->
        <section class="course-section">
            <h2 class="section-title urdu-nastaliq">کورسز کی تفصیلات</h2>
            <div class="course-grid">
                <div class="course-card">
                    <h3><i class="fa-solid fa-book-open"></i> تفسیر تعلیم قرآن کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> 1 سالہ کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-book"></i> تفسیر صراط الجنان کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک سال کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-graduation-cap"></i> تجوید کورس</h3>
                    <p><span class="meta-info">اہلیت:</span> طالبہ کی قابلیت پر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-star-and-crescent"></i> ناظرہ قرآن مجید کورس</h3>
                    <p><span class="meta-info">اہلیت:</span> طالبہ کی قابلیت پر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-pen-to-square"></i> حدّ رِٹیسٹ کی تیاری</h3>
                    <p><span class="meta-info">اہلیت:</span> طالبہ کی قابلیت پر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-chalkboard-user"></i> درسِ نظامی ٹیوشن کلاس</h3>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-pen-clip"></i> نحو و صرف ٹیوشن کلاس</h3>
                </div>
            </div>
        </section>

        <!-- Short Courses Section -->
        <section class="course-section">
            <h2 class="section-title urdu-nastaliq">مختصر دورانیے اور خصوصی کورسز</h2>
            <div class="course-grid">
                <div class="course-card">
                    <h3><i class="fa-solid fa-person-dress"></i> مسائل النساء کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-heart"></i> محمدؐ شمائل مصطفیٰ کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-book-quran"></i> مدنی قاعدہ کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-wand-magic-sparkles"></i> احکامِ زینت کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> 3 ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-clock"></i> واقعات قرآن کورس</h3>
                    <p><span class="meta-info">اهلیت:</span> طالبہ کے حفظ پر منحصر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-user-gear"></i> تخصص کی ٹیوشن کلاس</h3>
                </div>
            </div>
        </section>

        <!-- Call to Action Box -->
        <div class="cta-box urdu-nastaliq">
            ابھی داخلہ لیں!
        </div>

    </div>

    <!-- Footer / Contact Section -->
    <footer>
        <div class="contact-info">
            <div class="contact-item">
                <i class="fa-brands fa-whatsapp" style="color: #25D366; font-size: 1.5rem;"></i>
                <a href="https://wa.me/923156821561" dir="ltr">+92 315 6821561</a>
            </div>
            <div class="contact-item">
                <i class="fa-solid fa-globe"></i>
                <a href="https://darulilm-islamic-acadmey.base44.app" target="_blank" dir="ltr">darulilm-islamic-acadmey.base44.app</a>
            </div>
            <div class="contact-item">
                <i class="fa-solid fa-envelope"></i>
                <a href="mailto:darul.ilmacademyy@gmail.com" dir="ltr">darul.ilmacademyy@gmail.com</a>
            </div>
        </div>
        
        <div class="footer-note urdu-nastaliq">
            علم دین سیکھنے کی کوئی عمر نہیں ہوتی اور نہ ہی کوئی عذر۔ آج ہی اس مبارک سفر کا حصہ بنیں!
        </div>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Darul Ilm Academy - دارالعلوم اسلامک اکیڈمی</title>
    <!-- Google Fonts for beautiful Urdu Typography -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;700&family=Noto+Sans+Arabic:wght@400;700&display=swap" rel="stylesheet">
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --primary-blue: #0b1b3d;
            --accent-gold: #dfb143;
            --light-gold: #f4dc96;
            --white: #ffffff;
            --text-dark: #333333;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Noto Sans Arabic', sans-serif;
            background-color: #f9f9f9;
            color: var(--text-dark);
            line-height: 1.8;
        }

        .urdu-nastaliq {
            font-family: 'Noto Nastaliq Urdu', serif;
        }

        /* Header / Hero Section */
        header {
            background-color: var(--primary-blue);
            color: var(--white);
            text-align: center;
            padding: 3rem 1rem;
            border-bottom: 8px solid var(--accent-gold);
            position: relative;
        }

        .logo-text {
            font-size: 1.5rem;
            color: var(--accent-gold);
            letter-spacing: 1px;
            margin-bottom: 1rem;
            text-transform: uppercase;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: var(--light-gold);
        }

        header p {
            font-size: 1.3rem;
            max-width: 600px;
            margin: 0 auto;
        }

        /* Main Container */
        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        /* Section Styling */
        .course-section {
            background: var(--white);
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            padding: 2rem;
            margin-bottom: 2rem;
            border-right: 5px solid var(--accent-gold);
        }

        .section-title {
            color: var(--primary-blue);
            font-size: 1.8rem;
            margin-bottom: 1.5rem;
            border-bottom: 2px solid var(--light-gold);
            padding-bottom: 0.5rem;
            display: inline-block;
        }

        /* Course List grid */
        .course-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }

        .course-card {
            background: #fdfdfd;
            border: 1px solid #eaeaea;
            border-radius: 6px;
            padding: 1.2rem;
            transition: transform 0.3s ease;
        }

        .course-card:hover {
            transform: translateY(-3px);
            border-color: var(--accent-gold);
        }

        .course-card h3 {
            color: var(--primary-blue);
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .course-card p {
            font-size: 0.95rem;
            color: #666;
        }

        .meta-info {
            font-weight: bold;
            color: var(--accent-gold);
        }

        /* Admission Call to Action */
        .cta-box {
            background-color: var(--accent-gold);
            color: var(--primary-blue);
            text-align: center;
            padding: 1.5rem;
            border-radius: 8px;
            font-size: 1.5rem;
            font-weight: bold;
            margin: 2rem 0;
        }

        /* Footer / Contact Details */
        footer {
            background-color: var(--primary-blue);
            color: var(--white);
            padding: 3rem 1rem;
            text-align: center;
        }

        .contact-info {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .contact-item {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            font-size: 1.1rem;
        }

        .contact-item a {
            color: var(--light-gold);
            text-decoration: none;
            transition: color 0.2s;
        }

        .contact-item a:hover {
            color: var(--white);
        }

        .footer-note {
            font-size: 1.1rem;
            color: var(--light-gold);
            border-top: 1px solid rgba(255,255,255,0.1);
            padding-top: 1.5rem;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            .contact-info { flex-direction: column; gap: 1rem; }
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo-text">Darul ilm academy</div>
        <h1 class="urdu-nastaliq">دارالعلوم اسلامک اکیڈمی کے تحت</h1>
        <p class="urdu-nastaliq">مندرجہ ذیل کورسز کروائے جاتے ہیں</p>
    </header>

    <div class="container">

        <!-- Regular/Main Courses Section -->
        <section class="course-section">
            <h2 class="section-title urdu-nastaliq">کورسز کی تفصیلات</h2>
            <div class="course-grid">
                <div class="course-card">
                    <h3><i class="fa-solid fa-book-open"></i> تفسیر تعلیم قرآن کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> 1 سالہ کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-book"></i> تفسیر صراط الجنان کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک سال کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-graduation-cap"></i> تجوید کورس</h3>
                    <p><span class="meta-info">اہلیت:</span> طالبہ کی قابلیت پر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-star-and-crescent"></i> ناظرہ قرآن مجید کورس</h3>
                    <p><span class="meta-info">اہلیت:</span> طالبہ کی قابلیت پر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-pen-to-square"></i> حدّ رِٹیسٹ کی تیاری</h3>
                    <p><span class="meta-info">اہلیت:</span> طالبہ کی قابلیت پر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-chalkboard-user"></i> درسِ نظامی ٹیوشن کلاس</h3>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-pen-clip"></i> نحو و صرف ٹیوشن کلاس</h3>
                </div>
            </div>
        </section>

        <!-- Short Courses Section -->
        <section class="course-section">
            <h2 class="section-title urdu-nastaliq">مختصر دورانیے اور خصوصی کورسز</h2>
            <div class="course-grid">
                <div class="course-card">
                    <h3><i class="fa-solid fa-person-dress"></i> مسائل النساء کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-heart"></i> محمدؐ شمائل مصطفیٰ کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-book-quran"></i> مدنی قاعدہ کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> ایک ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-wand-magic-sparkles"></i> احکامِ زینت کورس</h3>
                    <p><span class="meta-info">دورانیہ:</span> 3 ماہ کا کورس</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-clock"></i> واقعات قرآن کورس</h3>
                    <p><span class="meta-info">اهلیت:</span> طالبہ کے حفظ پر منحصر</p>
                </div>
                <div class="course-card">
                    <h3><i class="fa-solid fa-user-gear"></i> تخصص کی ٹیوشن کلاس</h3>
                </div>
            </div>
        </section>

        <!-- Call to Action Box -->
        <div class="cta-box urdu-nastaliq">
            ابھی داخلہ لیں!
        </div>

    </div>

    <!-- Footer / Contact Section -->
    <footer>
        <div class="contact-info">
            <div class="contact-item">
                <i class="fa-brands fa-whatsapp" style="color: #25D366; font-size: 1.5rem;"></i>
                <a href="https://wa.me/923156821561" dir="ltr">+92 315 6821561</a>
            </div>
            <div class="contact-item">
                <i class="fa-solid fa-globe"></i>
                <a href="https://darulilm-islamic-acadmey.base44.app" target="_blank" dir="ltr">darulilm-islamic-acadmey.base44.app</a>
            </div>
            <div class="contact-item">
                <i class="fa-solid fa-envelope"></i>
                <a href="mailto:darul.ilmacademyy@gmail.com" dir="ltr">darul.ilmacademyy@gmail.com</a>
            </div>
        </div>
        
        <div class="footer-note urdu-nastaliq">
            علم دین سیکھنے کی کوئی عمر نہیں ہوتی اور نہ ہی کوئی عذر۔ آج ہی اس مبارک سفر کا حصہ بنیں!
        </div>
    </footer>

</body>
  </html>
  /* ==========================================================================
   Darul Ilm Academy - Main Stylesheet
   ========================================================================== */

/* 1. Global Variables & Base Setup */
:root {
    --primary-blue: #0b1b3d;
    --accent-gold: #dfb143;
    --light-gold: #f4dc96;
    --bg-light: #f8fafc;
    --white: #ffffff;
    --text-dark: #1e293b;
    --text-muted: #64748b;
    --shadow-sm: 0 2px 4px rgba(0, 0, 0, 0.05);
    --shadow-md: 0 4px 20px rgba(11, 27, 61, 0.08);
    --transition-smooth: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Noto Sans Arabic', sans-serif;
    background-color: var(--bg-light);
    color: var(--text-dark);
    line-height: 1.8;
}

/* Typography Special Classes */
.urdu-nastaliq {
    font-family: 'Noto Nastaliq Urdu', serif;
    line-height: 2.2;
}

/* ==========================================================================
   2. Header & Hero Banner
   ========================================================================== */
header {
    background-color: var(--primary-blue);
    background-image: radial-gradient(circle at top right, rgba(223, 177, 67, 0.1), transparent);
    color: var(--white);
    text-align: center;
    padding: 4rem 1.5rem 3.5rem;
    border-bottom: 6px solid var(--accent-gold);
    box-shadow: var(--shadow-sm);
}

.logo-text {
    font-size: 1.4rem;
    font-weight: 700;
    color: var(--accent-gold);
    letter-spacing: 2px;
    margin-bottom: 1.2rem;
    text-transform: uppercase;
}

header h1 {
    font-size: 2.8rem;
    margin-bottom: 1rem;
    color: var(--light-gold);
    text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

header p {
    font-size: 1.4rem;
    max-width: 650px;
    margin: 0 auto;
    opacity: 0.95;
}

/* ==========================================================================
   3. Layout & Structure
   ========================================================================== */
.container {
    max-width: 1100px;
    margin: 3rem auto;
    padding: 0 1.5rem;
}

.course-section {
    background: var(--white);
    border-radius: 12px;
    box-shadow: var(--shadow-md);
    padding: 2.5rem;
    margin-bottom: 3rem;
    border-right: 6px solid var(--accent-gold);
    position: relative;
    overflow: hidden;
}

.course-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 4px;
    height: 100%;
    background-color: rgba(11, 27, 61, 0.05);
}

.section-title {
    color: var(--primary-blue);
    font-size: 2rem;
    margin-bottom: 2rem;
    border-bottom: 3px solid var(--light-gold);
    padding-bottom: 0.5rem;
    display: inline-block;
}

/* ==========================================================================
   4. Course Cards & Grid
   ========================================================================== */
.course-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
}

.course-card {
    background: var(--bg-light);
    border: 1px solid rgba(0, 0, 0, 0.04);
    border-radius: 8px;
    padding: 1.5rem;
    transition: var(--transition-smooth);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.course-card:hover {
    transform: translateY(-4px);
    background-color: var(--white);
    border-color: var(--accent-gold);
    box-shadow: 0 10px 20px rgba(223, 177, 67, 0.1);
}

.course-card h3 {
    color: var(--primary-blue);
    font-size: 1.3rem;
    margin-bottom: 0.75rem;
    display: flex;
    align-items: center;
    gap: 0.75rem;
}

.course-card h3 i {
    color: var(--accent-gold);
    font-size: 1.1rem;
    background: rgba(223, 177, 67, 0.1);
    padding: 0.5rem;
    border-radius: 6px;
    width: 35px;
    height: 35px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.course-card p {
    font-size: 1rem;
    color: var(--text-muted);
    margin-top: auto;
}

.meta-info {
    font-weight: 700;
    color: var(--primary-blue);
    background-color: var(--light-gold);
    padding: 0.15rem 0.5rem;
    border-radius: 4px;
    font-size: 0.85rem;
    margin-left: 0.25rem;
}

/* ==========================================================================
   5. Components (CTA Button)
   ========================================================================== */
.cta-box {
    background: linear-gradient(135s, var(--accent-gold), #cda033);
    color: var(--primary-blue);
    text-align: center;
    padding: 1.8rem;
    border-radius: 12px;
    font-size: 1.8rem;
    font-weight: 700;
    margin: 3rem 0;
    box-shadow: 0 6px 15px rgba(223, 177, 67, 0.3);
    letter-spacing: 1px;
    transition: var(--transition-smooth);
    cursor: pointer;
}

.cta-box:hover {
    transform: scale(1.02);
    box-shadow: 0 8px 25px rgba(223, 177, 67, 0.45);
}

/* ==========================================================================
   6. Footer & Contact Details
   ========================================================================== */
footer {
    background-color: var(--primary-blue);
    color: var(--white);
    padding: 4rem 1.5rem 3rem;
    text-align: center;
    border-top: 4px solid var(--accent-gold);
}

.contact-info {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2.5rem;
    margin-bottom: 3rem;
}

.contact-item {
    display: flex;
    align-items: center;
    gap: 0.75rem;
    font-size: 1.15rem;
    background: rgba(255, 255, 255, 0.03);
    padding: 0.75rem 1.5rem;
    border-radius: 50px;
    border: 1px solid rgba(255, 255, 255, 0.08);
    transition: var(--transition-smooth);
}

.contact-item:hover {
    background: rgba(255, 255, 255, 0.08);
    border-color: var(--light-gold);
}

.contact-item i {
    font-size: 1.3rem;
    color: var(--accent-gold);
}

.contact-item a {
    color: var(--white);
    text-decoration: none;
    transition: color 0.2s;
    font-weight: 500;
}

.contact-item a:hover {
    color: var(--light-gold);
}

.footer-note {
    font-size: 1.25rem;
    color: var(--light-gold);
    max-width: 700px;
    margin: 0 auto;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    padding-top: 2rem;
}

/* ==========================================================================
   7. Responsive Adaptations
   ========================================================================== */
@media (max-width: 768px) {
    header {
        padding: 3rem 1rem 2.5rem;
    }
    
    header h1 { 
        font-size: 2.1rem; 
    }
    
    header p {
        font-size: 1.2rem;
    }

    .course-section {
        padding: 1.5rem;
        margin-bottom: 2rem;
    }

    .section-title {
        font-size: 1.6rem;
        margin-bottom: 1.5rem;
    }

    .contact-info { 
        flex-direction: column; 
        gap: 1rem; 
        align-items: center;
    }

    .contact-item {
        width: 100%;
        max-width: 350px;
        justify-content: center;
    }
}Coloring csshttps://shuja-graphics.github.io/Darul-ilm-Islamic-academy-/

