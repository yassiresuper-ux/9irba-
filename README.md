<!DOCTYPE html><!DOCTYPE html><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>عيادة الأسنان - الصفحة الرئيسية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-image: url('https://images.unsplash.com/photo-1559757148-5c350d0d3c56?ixlib=rb-4.0.3&auto=format&fit=crop&w=1350&q=80'); /* صورة جديدة لعيادة أسنان */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            background-color: rgba(255, 255, 255, 0.8);
            background-blend-mode: overlay;
            padding: 20px;
            margin: 0;
        }
        .videos {
            margin-top: 30px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 8px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        .videos h2 {
            margin-bottom: 20px;
        }
        .videos iframe {
            width: 100%;
            max-width: 600px;
            height: 600px; /* ارتفاع مناسب للريل */
            margin: 10px 0;
            border-radius: 8px;
        }
        .next-button {
            margin-top: 30px;
            padding: 15px 30px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 18px;
        }
        .next-button:hover {
            background-color: #0056b3;
        }
        .appointments {
            margin-top: 50px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 8px;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
            display: none; /* مخفي افتراضيًا */
        }
        form {
            max-width: 400px;
            margin: auto;
            background: rgba(255, 255, 255, 0.8);
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
            background: rgba(255, 255, 255, 0.9);
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
        .back-button {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #6c757d;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .back-button:hover {
            background-color: #5a6268;
        }
    </style>
    <script>
        function showAppointments() {
            document.querySelector('.videos').style.display = 'none';
            document.querySelector('.next-button').style.display = 'none';
            document.querySelector('.appointments').style.display = 'block';
        }
        function showVideos() {
            document.querySelector('.videos').style.display = 'block';
            document.querySelector('.next-button').style.display = 'block';
            document.querySelector('.appointments').style.display = 'none';
        }
    </script>
</head>
<body>
    <h1>مرحباً بك في عيادة الأسنان</h1>
    <p>شاهد فيديوهاتنا التعليمية والترويجية:</p>
    
    <!-- قسم الفيديوهات -->
    <div class="videos">
        <h2>فيديوهات تعليمية وترويجية</h2>
        
        <!-- الرييل الأول من إنستغرام -->
        <iframe src="https://www.instagram.com/reel/DChrKqsOYLm/embed/" frameborder="0" allowfullscreen></iframe>
        
        <!-- الرييل الثاني من إنستغرام -->
        <iframe src="https://www.instagram.com/reel/DABbGwLoHQP/embed/" frameborder="0" allowfullscreen></iframe>
        
        <!-- يمكنك إضافة المزيد من الفيديوهات هنا -->
    </div>
    
    <!-- زر التالي لإظهار قسم المواعيد -->
    <button class="next-button" onclick="showAppointments()">التالي - احجز موعد</button>
    
    <!-- قسم المواعيد -->
    <div class="appointments">
        <h2>احجز موعداً الآن</h2>
        <p>املأ النموذج أدناه:</p>
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
        
        <div class="contact">
            <h2>تواصل معنا</h2>
            <p><strong>رقم الهاتف:</strong> <a href="tel:0699002745">0699002745</a></p>
            <p><strong>Instagram:</strong> <a href="https://www.instagram.com/pro_tiz_dentair" target="_blank">@pro_tiz_dentair</a></p>
        </div>
        
        <!-- زر العودة إلى قسم الفيديوهات -->
        <button class="back-button" onclick="showVideos()">العودة إلى الفيديوهات</button>
    </div>
</body>
</html>
