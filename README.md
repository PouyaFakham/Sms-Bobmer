💣 SMS Bomber | ابزار تست نفوذ پیامک
[!WARNING]
هشدار جدی: این ابزار صرفاً برای مقاصد آموزشی و تست نفوذ قانونی طراحی شده است. هرگونه سوءاستفاده از آن برای آزار و اذیت، اسپم یا فعالیت‌های غیرقانونی اکیداً ممنوع است. توسعه‌دهنده هیچ‌گونه مسئولیتی در قبال استفاده نادرست از این پروژه بر عهده ندارد.

🇮🇷 معرفی ابزار (فارسی)
SMS Bomber یک اسکریپت قدرتمند و ماژولار مبتنی بر پایتون است که به متخصصان امنیت سایبری و توسعه‌دهندگان اجازه می‌دهد تا مقاومت سیستم‌های احراز هویت پیامکی (OTP) را در برابر درخواست‌های انبوه آزمایش کنند. این ابزار با بهره‌گیری از APIهای عمومی سرویس‌های ایرانی، پیامک‌های متعدد را به شماره هدف ارسال می‌کند.

✨ ویژگی‌های کلیدی
🛰️ چند سرویسه: استفاده همزمان از APIهای متنوع و واقعی برای افزایش نرخ ارسال.

🧩 معماری ماژولار: قابلیت افزودن آسان سرویس‌ها و APIهای جدید.

⚙️ تنظیمات پیشرفته: امکان تعیین تعداد دقیق پیامک‌های ارسالی.

⚡ سرعت بالا: ارسال درخواست‌ها به‌صورت همزمان (Concurrent) برای شبیه‌سازی واقعی حملات.

📊 گزارش‌دهی زنده: نمایش وضعیت لحظه‌ای هر درخواست (موفق یا ناموفق).

🎯 موارد استفاده قانونی
تست استرس (Stress Testing): ارزیابی عملکرد و پایداری درگاه‌های ورود و سیستم‌های OTP.

اهداف آموزشی: استفاده در کارگاه‌های امنیت سایبری و مسابقات فتح پرچم (CTF).

تحقیقات امنیتی: تحلیل و بررسی آسیب‌پذیری‌های موجود در سرویس‌های پیامکی.

📥 نصب و راه‌اندازی
برای استفاده از ابزار، دستورات زیر را در ترمینال خود وارد کنید:

# 1. کلون کردن پروژه
git clone https://github.com/PouyaFakham/Sms-Bobmer.git

# 2. ورود به پوشه پروژه
cd Sms-Bobmer

# 3. نصب نیازمندی‌ها
pip install -r requirements.txt

# 4. اجرای اسکریپت
python bomber.py

<br>

🇬🇧 English Documentation
SMS Bomber is a powerful, modular Python-based script designed for cybersecurity professionals and developers to test the robustness of SMS-based authentication systems (OTP) under high load. It leverages publicly available APIs from various services to send a barrage of SMS messages to a target number.

[!CAUTION]
Disclaimer: This tool is intended for educational and authorized penetration testing purposes only. Any misuse for harassment, spamming, or illegal activities is strictly prohibited. The developer assumes no responsibility for any unethical use of this project.

✨ Key Features
🛰️ Multi-API Support: Utilizes multiple real-world SMS APIs to maximize the sending rate.

🧩 Modular Architecture: Easily extendable; new services and APIs can be added with minimal effort.

⚙️ Adjustable Count: Specify the exact number of messages to send.

⚡ High-Speed Delivery: Employs concurrent requests to simulate a real-world stress test scenario.

📊 Live Status Reporting: Provides real-time feedback on the status of each request (Success/Fail).

🎯 Legal Use Cases
Stress Testing: Evaluate the performance and stability of login gateways and OTP endpoints in a controlled environment.

Educational Purposes: Ideal for cybersecurity workshops and Capture The Flag (CTF) events.

Security Research: Analyze and investigate vulnerabilities within SMS service implementations.

🛠️ Installation & Usage
To get started with SMS Bomber, follow these steps in your terminal:

# 1. Clone the repository
git clone https://github.com/PouyaFakham/Sms-Bobmer.git

# 2. Navigate to the project directory
cd Sms-Bobmer

# 3. Install the required dependencies
pip install -r requirements.txt

# 4. Run the bomber script
python bomber.py
