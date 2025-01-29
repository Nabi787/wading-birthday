<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wading & Birthday</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Wading & Birthday</h1>
        <a href="#register" class="cta-button">انضم إلى الاحتفال</a>
    </header>
    <section id="about">
        <h2>عن الحدث</h2>
        <p>احتفل معنا في يوم مميز يجمع بين المتعة والاسترخاء. وادينغ وبيوم الميلاد، نحتفل معًا بذكرى لا تُنسى.</p>
    </section>
    <section id="details">
        <h2>تفاصيل الحدث</h2>
        <p>التاريخ: [تاريخ الحدث]</p>
        <p>الوقت: [وقت الحدث]</p>
        <p>الموقع: [عنوان الحدث]</p>
    </section>
    <section id="register">
        <h2>سجل الآن</h2>
        <form>
            <label for="name">الاسم:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>
            <label for="guests">عدد الأشخاص:</label>
            <select id="guests" name="guests">
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
            </select>
            <button type="submit">سجل الآن</button>
        </form>
    </section>
    <footer>
        <h2>تواصل معنا</h2>
        <p>الهاتف: [رقم الهاتف]</p>
        <p>البريد الإلكتروني: [البريد الإلكتروني]</p>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
