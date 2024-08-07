# birthday-page
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عيد ميلاد محمود الكناني</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9; /* Light Gray */
            color: #333; /* Dark Gray */
            margin: 0;
            padding: 0;
            overflow-x: hidden; /* لمنع التمرير الأفقي */
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: #fff; /* White */
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #e64a19; /* Deep Orange */
            color: #fff; /* White */
            border-radius: 8px;
            position: relative;
            overflow: hidden;
        }

        header h1 {
            font-size: 24px;
            margin: 0;
            animation: slideIn 3s ease-out;
        }

        @keyframes slideIn {
            from {
                transform: translateY(-50px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        .animated-text {
            font-size: 22px;
            color: #fff; /* White */
            background: #e64a19; /* Deep Orange */
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            position: absolute;
            top: 20px;
            left: 50%;
            transform: translateX(-50%);
            animation: marquee 10s linear infinite;
            white-space: nowrap;
        }

        @keyframes marquee {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }

        .image-section {
            text-align: center;
            margin: 20px 0;
        }

        .image-section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            border: 5px solid #e64a19; /* Deep Orange */
        }

        .message-section, .poem-section {
            margin: 20px 0;
        }

        .message-section h2, .poem-section h2 {
            color: #e64a19; /* Deep Orange */
        }

        .poem-section p {
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            font-size: 16px;
        }

        footer a {
            color: #fff; /* White */
            background-color: #e64a19; /* Deep Orange */
            text-decoration: none;
            display: inline-block;
            padding: 12px 25px;
            font-size: 16px;
            border-radius: 5px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        footer a:hover {
            background-color: #d43f15; /* Dark Orange */
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="animated-text">عيد ميلاد أحلى أب محمود الكناني!</div>
            <h1>عيد ميلاد سعيد محمود الكناني!</h1>
            <p>منشئ الصفحة: ابنك العزيز زياد الكناني</p>
        </header>
        <section class="image-section">
            <img src="path_to_your_image.jpg" alt="محمود الكناني">
        </section>
        <section class="message-section">
            <h2>تهنئة</h2>
            <p>نتمنى لك عيد ميلاد سعيد ومليء بالسعادة والفرح! نأمل أن تحقق كل أحلامك وأن تكون سنة جديدة مليئة بالنجاح والإنجازات.</p>
        </section>
        <section class="poem-section">
            <h2>قصائد للأب</h2>
            <p>1. أبي، أنت النجم الذي ينير لي حياتي، ومصدر القوة والإلهام. كل سنة وأنت بخير.</p>
            <p>2. في يوم عيد ميلادك، أتمنى لك الصحة والسعادة، لأنك أعظم أب في العالم.</p>
            <p>3. لم أجد كلمات تعبر عن مدى حبي لك، لكني أقول لك: كل عام وأنت أفضل أب في الدنيا.</p>
        </section>
        <footer>
            <a href="mailto:someone@example.com?subject=عيد ميلاد سعيد محمود الكناني&body=مرحبا! لقد أنشأت صفحة خاصة بعيد ميلاد محمود الكناني. تفضل بزيارة الرابط: https://zeyad-elkenany.github.io/birthday-page/" class="button">أرسل الرابط بالبريد الإلكتروني</a>
            <br>
            <a href="https://www.youtube.com/watch?v=C11sKQphVwk" class="button" target="_blank">استمع إلى أغنية عيد ميلاد سعيد</a>
        </footer>
    </div>
</body>
</html>
