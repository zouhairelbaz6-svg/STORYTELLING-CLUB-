# STORYTELLING-CLUB-<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مدونة كلاسيكية</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- الشريط العلوي -->
    <header>
        <div class="logo">
            <h1>مدونتي الكلاسيكية</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">الصفحة الرئيسية</a></li>
                <li><a href="#gallery">معرض الصور</a></li>
                <li><a href="#contact">نموذج التواصل</a></li>
            </ul>
        </nav>
    </header>

    <!-- الصفحة الرئيسية -->
    <section id="home" class="main-content">
        <article>
            <h2>أهلاً بك في مدونتي!</h2>
            <p>هنا ستجد مجموعة من المقالات و المواضيع المثيرة التي يمكن أن تهمك.</p>
            <!-- يمكن إضافة مقالات هنا -->
        </article>
    </section>

    <!-- معرض الصور -->
    <section id="gallery" class="gallery">
        <h2>معرض الصور</h2>
        <div class="image-gallery">
            <img src="image1.jpg" alt="صورة 1">
            <img src="image2.jpg" alt="صورة 2">
            <img src="image3.jpg" alt="صورة 3">
        </div>
    </section>

    <!-- نموذج التواصل -->
    <section id="contact" class="contact-form">
        <h2>نموذج التواصل</h2>
        <form action="#" method="POST">
            <label for="name">الاسم:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">الرسالة:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">إرسال</button>
        </form>
    </section>

    <!-- التذييل -->
    <footer>
        <p>جميع الحقوق محفوظة &copy; 2025</p>
    </footer>
</body>
</html>
