💣 SMS Bomber | ابزار تست نفوذ پیامک
⚠️ هشدار مهم
این ابزار صرفاً برای مقاصد آموزشی، تست نفوذ قانونی و تحقیقات امنیتی طراحی شده است.
استفاده غیرمجاز، ارسال اسپم، آزار و اذیت یا هر فعالیت غیرقانونی اکیداً ممنوع می‌باشد و پیگرد قانونی دارد.
توسعه‌دهنده مسئولیتی در قبال سوءاستفاده افراد ندارد.

🇮🇷 معرفی ابزار (فارسی)
SMS Bomber یک اسکریپت قدرتمند و ماژولار به زبان پایتون است که به متخصصان امنیت سایبری و توسعه‌دهندگان کمک می‌کند تا مقاومت سیستم‌های احراز هویت پیامکی (OTP) را در برابر حملات درخواست‌های انبوه پیامک تست کنند. این ابزار با بهره‌گیری از APIهای عمومی و واقعی سرویس‌های ایرانی، امکان ارسال تعداد زیادی پیامک به شماره هدف را فراهم می‌کند.

✨ ویژگی‌های کلیدی
🛰️ چند سرویسه و چند API: استفاده همزمان از APIهای متنوع سرویس‌های پیامکی معتبر برای افزایش نرخ ارسال و پوشش گسترده‌تر.

🧩 معماری ماژولار: امکان افزودن سرویس‌ها و APIهای جدید به آسانی بدون نیاز به تغییر ساختار کلی.

⚙️ تنظیمات سفارشی: قابلیت تعیین تعداد دقیق پیامک‌ها و پارامترهای مختلف جهت کنترل کامل حمله.

⚡ ارسال همزمان (Concurrency): ارسال سریع و همزمان درخواست‌ها برای شبیه‌سازی واقعی حملات استرس.

📊 گزارش‌دهی زنده: نمایش وضعیت هر درخواست (موفق یا ناموفق) به صورت بلادرنگ جهت بررسی اثربخشی.

🔐 امنیت و حریم خصوصی: تمامی داده‌ها به صورت محلی پردازش می‌شوند و هیچ داده‌ای به سرورهای خارجی ارسال نمی‌گردد.

🎯 موارد استفاده قانونی و اخلاقی
تست استرس و پایداری درگاه‌های ورود مبتنی بر پیامک.

آموزش و کارگاه‌های امنیت سایبری و مسابقات CTF.

تحقیق و تحلیل آسیب‌پذیری‌های سیستم‌های پیامکی و احراز هویت.

آزمایش‌های نفوذ (Pentesting) با مجوز صاحب سیستم.

🛠️ نصب و راه‌اندازی
برای شروع کار مراحل زیر را در ترمینال اجرا کنید:

bash
Copy
Edit
# 1. کلون کردن مخزن پروژه
git clone https://github.com/PouyaFakham/Sms-Bobmer.git

# 2. وارد شدن به پوشه پروژه
cd Sms-Bobmer

# 3. نصب وابستگی‌ها و کتابخانه‌های مورد نیاز
pip install -r requirements.txt

# 4. اجرای اسکریپت بمبر
python bomber.py
🇬🇧 SMS Bomber | SMS Penetration Testing Tool
⚠️ Important Disclaimer
This tool is designed exclusively for educational purposes, authorized penetration testing, and security research.
Any unauthorized use, spamming, harassment, or illegal activity is strictly prohibited and may be punishable by law.
The developer assumes no responsibility for any misuse of this project.

📝 Overview
SMS Bomber is a powerful, modular Python script aimed at cybersecurity professionals and developers to evaluate the resilience of SMS-based authentication systems (OTP) under heavy load. Utilizing real-world public APIs from various Iranian SMS services, it can flood a target phone number with numerous SMS messages.

✨ Key Features
🛰️ Multi-API Integration: Concurrent usage of multiple legitimate SMS service APIs to maximize message throughput.

🧩 Modular Design: Easily extendable architecture allowing new services and APIs to be added without major changes.

⚙️ Customizable Settings: Specify exact number of SMS messages and tailor attack parameters.

⚡ Concurrent Requests: High-speed, parallel request sending to simulate realistic stress testing.

📊 Live Feedback: Real-time reporting of each request's success or failure status.

🔐 Privacy-Friendly: Processes data locally without sending sensitive info to external servers.

🎯 Legal Use Cases
Stress testing and performance evaluation of SMS-based login and OTP endpoints.

Educational workshops and Capture The Flag (CTF) cybersecurity competitions.

Security research and vulnerability assessments of SMS authentication mechanisms.

Authorized penetration testing with proper permissions.

🛠️ Installation & Usage
Follow these commands in your terminal to get started:

bash
Copy
Edit
# 1. Clone the repository
git clone https://github.com/PouyaFakham/Sms-Bobmer.git

# 2. Navigate to the project directory
cd Sms-Bobmer

# 3. Install required dependencies
pip install -r requirements.txt

# 4. Run the bomber script
python bomber.py
