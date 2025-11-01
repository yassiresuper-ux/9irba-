<!DOCTYPE html><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>عيادة الأسنان - حجز موعد</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to bottom, #e0f7fa, #ffffff);
            background-attachment: fixed;
            padding: 20px;
            margin: 0;
        }
        form {
            max-width: 400px;
            margin: auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, textarea, button {
            display: block;
            width: 100%;
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #007bff;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        .contact {
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 8px;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
        }
        .contact a {
            color: #007bff;
            text-decoration: none;
        }
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>مرحباً بك في عيادة الأسنان</h1>
    <p>احجز موعداً الآن عبر هذا النموذج البسيط:</p>
    <form action="https://formspree.io/f/mjkpplkb" method="POST">
        <input type="text" name="name" placeholder="اسمك الكامل" required>
        <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
        <input type="tel" name="phone" placeholder="رقم هاتفك" required>
        <input type="date" name="date" placeholder="تاريخ الموعد المفضل" required>
        <input type="time" name="time" placeholder="الوقت المفضل" required>
        <textarea name="message" placeholder="أي تفاصيل إضافية (مثل نوع الخدمة)" rows="4"></textarea>
        <button type="submit">احجز الموعد</button>
    </form>
    <p>سنتصل بك أو نرسل تأكيداً عبر البريد الإلكتروني خلال 24 ساعة.</p>
    
    <!-- قسم معلومات الاتصال الجديد -->
    <div class="contact">
        <h2>تواصل معنا</h2>
        <p><strong>رقم الهاتف:</strong> <a href="tel:0699002745">0699002745</a></p>
        <p><strong>Instagram:</strong> <a href="https://www.instagram.com/pro_tiz_dentair" target="_blank">@pro_tiz_dentair</a></p>
    </div>
</body>
</html>

    
