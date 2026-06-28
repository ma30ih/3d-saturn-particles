<div align="center">

![JavaScript](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/UI-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![MediaPipe](https://img.shields.io/badge/AI_Engine-MediaPipe-00BCD4?style=for-the-badge&logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

# 🌌 3D Holographic Saturn & Particles

<p align="center">
  <b>An interactive 3D math-physics engine powered by AI hand tracking and gesture recognition.</b>
  <br />
  <b>یک موتور رندر سه‌بعدی ریاضیاتی و تعاملی بر پایه هوش مصنوعی و تشخیص حرکات دست.</b>
</p>

</div>

---



![Magic Particle Fingers Demo](demo.gif)

An interactive 3D holographic universe using AI hand tracking and Z-sorted point clouds.

## 🌟 Try the Live Demo
👉 **[Click Here to Experience It Live!](https://ma30ih.github.io/3d-saturn-particles/)** 👈
*(Note: Requires camera access to track your hand gestures. All AI processing runs locally on your device.)*

## 🎮 How It Works
Hold your hand in front of the camera to interact with the 3D physics engine:
* **Fist (0 fingers):** Summons a massive, rotating **3D Saturn** with Z-sorted asteroid belts!
* **1 to 4 fingers:** Particles form the numbers **"1", "2", "3", "4"** in real-time.
* **5 fingers (Open hand):** The universe elegantly scatters into a cosmic void.
* Features immersive space background audio and interactive SFX.

## 🇮🇷 توضیحات فارسی
این پروژه یک موتور پردازش سه‌بعدی (3D Engine) است که روی Canvas مرورگر اجرا می‌شود. با استفاده از هوش مصنوعی، حرکات دست شما از طریق دوربین تشخیص داده شده و ذرات کیهانی به شکل‌های مختلف درمی‌آیند.

* **شاهکار پروژه (سیاره زحل):** با مشت کردن دست، یک سیاره غول‌پیکر با کمربند سیارکی سه‌بعدی ساخته می‌شود که دارای عمق (Z-sorting) و پرسپکتیو است.
* **حریم خصوصی:** تمام پردازش‌های هوش مصنوعی مستقیماً روی مرورگر (لوکال) انجام می‌شود و هیچ ویدیویی ذخیره یا به سروری ارسال نمی‌گردد.

---

## 🔬 Technical Breakdown / تشریح فنی پروژه

### 🇬🇧 English Description
This project is built from scratch without relying on heavy 3D frameworks like Three.js. It demonstrates core computer graphics and engine architecture principles:

* **Custom 3D Projection Pipeline:** Translates 3D space coordinates $(X, Y, Z)$ into a 2D screen viewport using perspective divide and matrix transformation mathematics.
* **Z-Sorting Engine:** Implements a manual depth-buffering algorithm to sort particles based on their distance from the virtual camera. This prevents visual artifacts and ensures the Saturn rings render correctly behind and in front of the planet.
* **On-Device Computer Vision:** Utilizes Google MediaPipe for real-time, low-latency hand landmark tracking. The gesture analysis runs entirely inside the client's browser, maintaining absolute data privacy.

### 🇮🇷 توضیحات فارسی
این پروژه به صورت کامل از صفر (Vanilla JS) و بدون وابستگی به فریم‌ورک‌های سنگین سه‌بعدی مانند Three.js توسعه یافته است و اصول پایه گرافیک کامپیوتری را به نمایش می‌گذارد:

* **خط‌لوله پرسپکتیو و پایپ‌لاین سه‌بعدی:** تبدیل مختصات فضای سه‌بعدی $(X, Y, Z)$ به صفحات دوبعدی مانیتور با استفاده از محاسبات ماتریسی و پرسپکتیو مپینگ.
* **موتور دست‌ساز Z-Sorting:** پیاده‌سازی الگوریتم مرتب‌سازی عمق ذرات بر اساس فاصله از دوربین مجازی؛ این ساختار مانع از تداخل بصری شده و رندر صحیح لایه‌های جلو و عقب کمربند سیارکی زحل را تضمین می‌کند.
* **بینایی ماشین در لبه (On-Device AI):** استفاده از هوش مصنوعی MediaPipe برای ترکینگ آنی و بدون تاخیر دست، به طوری که تمام پردازش‌ها درون مرورگر کاربر انجام شده و امنیت داده‌ها حفظ می‌شود.

---


## 🛠️ Tech Stack
* HTML5 / CSS3
* Vanilla JavaScript & Math Physics (Z-sorting, Projection)
* HTML5 `<canvas>` API
* [Google MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands)

## 💻 Local Installation
To run this project locally, use a local server (due to browser security restrictions regarding camera access):
* **VS Code:** Install "Live Server" extension and click "Go Live".
* **Python:** Run `python -m http.server` in your terminal.

## 📫 Get In Touch
I'm an independent game developer and tech enthusiast. Whether it's discussing Unreal Engine 5.7 mechanics, collaborating on new business ventures, or just geeking out over hardware and code, I'd love to connect!
* **Email:** msyhan85@gmail.com
