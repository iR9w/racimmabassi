<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>سناب شات | معلومات وميزات</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #fffc00; /* Snapchat yellow */
      --secondary-color: #111;  /* Dark for contrast */
      --background-color: #f4f4f4; /* Soft light gray */
      --highlight-color: #ffd700; /* Accent yellow for important elements */
      --link-color: #0066cc; /* Blue for links */
      --button-color: #fffc00;
      --button-hover-color: #e6d800;
      --text-color: #333;
    }

    body {
      margin: 0;
      font-family: 'Cairo', sans-serif;
      background-color: var(--background-color);
      color: var(--text-color);
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      background-color: var(--primary-color);
      padding: 40px 0;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      animation: fadeInHeader 1s ease-in-out;
    }

    header img {
      width: 80px;
      margin-bottom: 15px;
      animation: bounce 1s ease-in-out infinite;
    }

    header h1 {
      margin: 0;
      font-size: 36px;
      font-weight: 700;
      color: var(--secondary-color);
    }

    header p {
      margin: 10px 0 0;
      font-size: 20px;
      color: var(--secondary-color);
      opacity: 0;
      animation: fadeInText 2s ease-in-out forwards;
      animation-delay: 1s;
    }

    .typing {
      font-size: 32px;
      color: var(--highlight-color);
      font-weight: 600;
      display: inline-block;
      white-space: nowrap;
      opacity: 0;
      animation: fadeInText 1.5s ease-in-out forwards, typing 3s steps(20) 1s forwards, blink 0.75s step-end infinite;
      animation-delay: 2s;
    }

    nav {
      display: flex;
      justify-content: center;
      background-color: var(--secondary-color);
      padding: 15px 0;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      animation: fadeIn 2s ease-in-out;
    }

    nav a {
      padding: 15px 30px;
      color: var(--primary-color);
      text-decoration: none;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1px;
      transition: color 0.3s, background 0.3s;
    }

    nav a:hover {
      background-color: var(--secondary-color);
      color: #fff;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 60px 30px;
      animation: fadeInContainer 1.5s ease-in-out;
    }

    section {
      background-color: #fff;
      border-radius: 10px;
      padding: 40px;
      margin-bottom: 40px;
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.05);
      opacity: 0;
      animation: fadeInSection 1s ease-in-out forwards;
    }

    section:nth-child(odd) {
      animation-delay: 0.5s;
    }

    h2 {
      color: var(--highlight-color);
      font-size: 28px;
      margin-bottom: 20px;
    }

    p {
      font-size: 18px;
      line-height: 1.8;
      color: #555;
    }

    ul {
      list-style-type: square;
      padding-right: 20px;
      margin: 20px 0;
    }

    ul li {
      margin-bottom: 10px;
      color: #444;
    }

    a.button {
      display: inline-block;
      padding: 14px 30px;
      background-color: var(--button-color);
      color: var(--secondary-color);
      text-decoration: none;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 1px;
      border-radius: 6px;
      transition: background 0.3s ease, transform 0.3s ease;
      margin-top: 20px;
    }

    a.button:hover {
      background-color: var(--button-hover-color);
      transform: scale(1.05);
    }

    footer {
      background-color: var(--secondary-color);
      color: var(--primary-color);
      text-align: center;
      padding: 25px;
      font-size: 14px;
      animation: fadeIn 2s ease-in-out;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 30px;
      }

      nav a {
        font-size: 16px;
        padding: 12px 20px;
      }

      .container {
        padding: 40px 20px;
      }

      section {
        padding: 30px;
      }
    }

    /* Animation Keyframes */
    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    @keyframes fadeInHeader {
      0% {
        opacity: 0;
        transform: translateY(-20px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInText {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }

    @keyframes fadeInContainer {
      0% {
        opacity: 0;
        transform: translateY(20px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes fadeInSection {
      0% {
        opacity: 0;
        transform: translateY(20px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }

    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 100%;
      }
    }

    @keyframes blink {
      50% {
        border-color: transparent;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="https://upload.wikimedia.org/wikipedia/en/thumb/c/c4/Snapchat_logo.svg/512px-Snapchat_logo.svg.png" alt="شعار سناب شات">
    <h1>سناب شات - معلومات وميزات 🌟</h1>
    <p>مقدم من: <span class="typing">racim abassi 👨‍💻</span></p>
  </header>

  <nav>
    <a href="#about">عن التطبيق 📱</a>
    <a href="#features">الميزات ✨</a>
    <a href="#download">التحميل 📥</a>
  </nav>

  <div class="container">
    <section id="about">
      <h2>ما هو سناب شات؟ 🤳</h2>
      <p>
        سناب شات هو تطبيق تواصل اجتماعي مبتكر يتيح للمستخدمين مشاركة اللحظات عن طريق صور وفيديوهات قصيرة تختفي بعد مشاهدتها. يتميز بسهولة الاستخدام والتركيز على المرح والإبداع.
      </p>
    </section>

    <section id="features">
      <h2>مزايا سناب شات 🌟</h2>
      <ul>
        <li>التقاط ومشاركة "سنابات" قصيرة 📸</li>
        <li>القصص اليومية (Stories) 📖</li>
        <li>فلاتر وتأثيرات ممتعة باستخدام الواقع المعزز 🤩</li>
        <li>خريطة سناب لتحديد مواقع الأصدقاء 🗺️</li>
        <li>دردشة نصية وصوتية ومكالمات فيديو 🎤📞</li>
        <li>اكتشاف محتوى من مشاهير وشركات عالمية 🌍</li>
      </ul>
    </section>

    <section id="download">
      <h2>تحميل سناب شات 📥</h2>
      <p>يمكنك تنزيل التطبيق مباشرة من المتاجر الرسمية:</p>
      <a class="button" href="https://play.google.com/store/apps/details?id=com.snapchat.android" target="_blank">Google Play 📱</a>
      <a class="button" href="https://apps.apple.com/app/snapchat/id447188370" target="_blank">App Store 🍏</a>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 | موقع تم إنشاؤه بواسطة <strong>racim abassi 👨‍💻</strong> - غير رسمي</p>
  </footer>

</body>
</html>
