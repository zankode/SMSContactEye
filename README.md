# SMSContactEye

[فارسی](#persian) | [English](#english)

---

<a name="persian"></a>
## فارسی

> **⚠️ این ابزار فقط برای اهداف آموزشی و تست روی دستگاه شخصی ساخته شده است.**
>
> **❌ استفاده از آن روی دستگاه دیگران بدون اجازه صریح و آگاهانه مالک دستگاه، غیرقانونی است. ❌**
>
> **🚫 استفاده از این نرم‌افزار برای دسترسی غیرمجاز به اطلاعات، نظارت مخفیانه، کنترل دستگاه اشخاص دیگر یا جمع‌آوری اطلاعات شخصی بدون رضایت صریح و آگاهانه صاحب دستگاه ممنوع است.**
>
> **⚖️ مسئولیت هرگونه استفاده غیرقانونی تماماً بر عهده کاربر است.**

---

### این پروژه چیست

SMSContactEye یک اپلیکیشن اندرویدی است که نحوه دسترسی به پیامک، مخاطبین و برخی قابلیت‌های دستگاه را برای اهداف آموزشی نشان می‌دهد.

> **🔴 توجه: این برنامه یک وی‌پی‌ان واقعی نیست. هدف آن فقط آموزش و آشنایی با مفاهیم امنیتی است.**

### امکانات

- خواندن پیامک‌های دریافتی
- خواندن لیست مخاطبین
- ارسال خودکار به تلگرام
- قابلیت تنظیم مخفی (برای تست)
- ردیابی و مکان‌یابی
- مدیریت برنامه‌ها و حالت مخفی
- گزارش شبکه، اینترنت، حافظه و رم
- کنترل سخت‌افزار و هشدارها
- کنترل صدا و پیام‌رسانی
- دسترسی به اطلاعات و فایل‌ها

### فرامین و قابلیت‌ها

#### 📍 ردیابی و مکان‌یابی
- `/loc` یا `/gps` — دریافت موقعیت مکانی زنده (GPS Pin + لینک نقشه)
- `/status` — وضعیت کامل باتری، شارژر، مدل و سیستم
- `/sensors` — گزارش سنسورهای شتاب‌سنج، ژیروسکوپ، نور و قدم‌شمار

#### 👻 حالت مخفی و مدیریت برنامه‌ها
- `/stealth` یا `/hideapp` — مخفی‌سازی آیکون برنامه از منوی گوشی
- `/unstealth` یا `/unhideapp` — ظاهر کردن مجدد آیکون برنامه
- `/launch <نام_پکیج>` — اجرای مستقیم برنامه دلخواه از راه دور
- `/apps` — مشاهده لیست اپلیکیشن‌های نصب‌شده روی گوشی

#### 🌐 شبکه، اینترنت و ارتباطات
- `/netinfo` — مشخصات سیم‌کارت‌ها، نوع شبکه (4G/5G) و IP
- `/wifiscan` — اسکن شبکه‌های وای‌فای اطراف با قدرت سیگنال
- `/storage` — بررسی حافظه داخلی و کارت حافظه
- `/ram` — مشاهده مصرف لحظه‌ای رم دستگاه

#### 🛠️ کنترل سخت‌افزار و هشدارها
- `/torch on` یا `/torch off` — کنترل چراغ‌قوه
- `/alarm` و `/stopalarm` — پخش و قطع آژیر با حداکثر صدا
- `/vibrate` — ایجاد ویبره و لرزش مکرر
- `/wake` — روشن کردن صفحه نمایش گوشی
- `/record 10` — ضبط صدای محیط با میکروفون (۳ تا ۱۲۰ ثانیه)

#### 🔊 کنترل صدا و پیام‌رسانی
- `/say <متن>` — خواندن متن با صدای بلند (TTS)
- `/volume <0-100>` — تنظیم بلندی صدای دستگاه
- `/mute` و `/unmute` — حالت سکوت یا صدادار
- `/vibratemode` — فعال‌سازی حالت ویبره
- `/sendsms <شماره> <متن>` — ارسال پیامک مستقیم از سیم‌کارت گوشی
- `/dial <شماره>` — باز کردن صفحه تماس
- `/toast <متن>` — نمایش اعلان پاپ‌آپ کوتاه
- `/dialog <متن>` — نمایش پنجره هشدار روی گوشی
- `/open <آدرس>` — باز کردن لینک در مرورگر

#### 📋 دسترسی به اطلاعات و فایل‌ها
- `/getsms` — دریافت آخرین پیامک‌های گوشی
- `/getcontacts` — استخراج و ارسال لیست مخاطبین
- `/getphoto` — دریافت آخرین تصاویر گالری
- `/clipboard` — خواندن متن کپی‌شده در کلیپ‌بورد
- `/setclip <متن>` — کپی متن دلخواه در کلیپ‌بورد گوشی
- `/find <نام_فایل>` — جستجوی سریع در حافظه
- `/files` — باز کردن منوی پیشرفته فایل منیجر
- `/download <مسیر>` — دانلود فایل از گوشی
- `/delete <مسیر>` — حذف فایل از گوشی
- `/clearlogs` — پاکسازی لاگ‌های محلی

### روش کار با برنامه

بعد از نصب و اجرا، یک صفحه ساده می‌بینید. برای دسترسی به تنظیمات:

**۶ بار پشت سر هم روی دکمه امن کلیک کنید.**

پس از این کار، صفحه تنظیمات باز می‌شود و می‌توانید اطلاعات بات تلگرام خود را وارد کنید.

### ساخت بات تلگرام

برای ساخت بات، مراحل زیر را انجام دهید:

1. اپلیکیشن تلگرام را باز کنید
2. به بات [@BotFather](https://t.me/BotFather) پیام دهید
3. دستور `/newbot` را بفرستید
4. یک نام برای بات خود انتخاب کنید
5. یک یوزرنیم که به `bot` ختم شود انتخاب کنید
6. توکن دریافتی را کپی کنید

### گرفتن آیدی خود

برای گرفتن آیدی عددی خود:

1. به بات [@userinfobot](https://t.me/userinfobot) پیام دهید
2. بات آیدی عددی شما را نشان می‌دهد
3. آن را کپی کنید

### تنظیم در برنامه

- توکن دریافتی از @BotFather را در قسمت توکن وارد کنید
- آیدی عددی خود را در قسمت آیدی کاربری وارد کنید
- ذخیره کنید و خارج شوید

تمام. برنامه آماده تست روی دستگاه شخصی است.

---

> **🔴 هشدار نهایی: این برنامه فقط برای تست روی دستگاه شخصی خودتان ساخته شده است.**
>
> **❌ هیچ کاربردی در زمینه وی‌پی‌ان ندارد و صرفاً آموزشی است. ❌**
>
> **🚫 هرگونه استفاده برای نظارت مخفیانه، کنترل دستگاه دیگران یا جمع‌آوری اطلاعات بدون رضایت صریح مالک دستگاه ممنوع و غیرقانونی است.**
>
> **⚖️ مسئولیت استفاده غیرقانونی تماماً بر عهده کاربر است.**

---

### مجوز

GNU General Public License v3.0

### ارتباط با من

[ایمیل: zankodesec@gmail.com](mailto:zankodesec@gmail.com)

[وبسایت: zankode.ir](https://zankode.ir)

[تلگرام: @zankode](https://t.me/zankode)

developer: @zankode

---

<a name="english"></a>
## English

> **⚠️ This tool is for educational purposes only and for testing on your own device.**
>
> **❌ Using it on someone else's device without the owner's explicit and informed permission is illegal. ❌**
>
> **🚫 Using this software for unauthorized access to information, covert surveillance, controlling other people's devices, or collecting personal information without the explicit and informed consent of the device owner is prohibited.**
>
> **⚖️ The user bears full responsibility for any illegal use.**

---

### What is this

SMSContactEye is an Android app that demonstrates access to SMS, contacts, and some device capabilities for educational purposes.

> **🔴 Note: This is NOT a real VPN. It is only for learning security concepts.**

### Features

- Read incoming SMS messages
- Read device contacts
- Auto-forward to Telegram
- Hidden settings panel
- Location and GPS reporting
- App management and stealth mode
- Network, storage, and RAM reports
- Hardware control and alarms
- Audio control and messaging
- Access to information and files

### Commands and Capabilities

#### 📍 Location and Tracking
- `/loc` or `/gps` — Get live location (GPS pin + map link)
- `/status` — Battery, charger, model, and system status
- `/sensors` — Accelerometer, gyroscope, light, and step counter report

#### 👻 Stealth Mode and App Management
- `/stealth` or `/hideapp` — Hide the app icon from the launcher
- `/unstealth` or `/unhideapp` — Show the app icon again
- `/launch <package_name>` — Launch a specific app remotely
- `/apps` — List installed applications

#### 🌐 Network, Internet, and Connectivity
- `/netinfo` — SIM details, network type (4G/5G), and IP
- `/wifiscan` — Scan nearby Wi-Fi networks with signal strength
- `/storage` — Check internal storage and SD card
- `/ram` — View real-time RAM usage

#### 🛠️ Hardware Control and Alerts
- `/torch on` or `/torch off` — Control the flashlight
- `/alarm` and `/stopalarm` — Play and stop a loud alarm
- `/vibrate` — Trigger repeated vibration
- `/wake` — Wake the device screen
- `/record 10` — Record ambient audio via microphone (3–120 seconds)

#### 🔊 Audio Control and Messaging
- `/say <text>` — Text-to-speech playback
- `/volume <0-100>` — Set device volume
- `/mute` and `/unmute` — Mute or unmute
- `/vibratemode` — Enable vibration mode
- `/sendsms <number> <text>` — Send an SMS from the device SIM
- `/dial <number>` — Open the dialer
- `/toast <text>` — Show a short popup notification
- `/dialog <text>` — Show an alert dialog on the device
- `/open <url>` — Open a link in the browser

#### 📋 Information and File Access
- `/getsms` — Get recent SMS messages
- `/getcontacts` — Extract and send contacts
- `/getphoto` — Get recent gallery photos
- `/clipboard` — Read clipboard text
- `/setclip <text>` — Copy custom text to the clipboard
- `/find <filename>` — Search storage
- `/files` — Open the advanced file manager menu
- `/download <path>` — Download a file from the device
- `/delete <path>` — Delete a file from the device
- `/clearlogs` — Clear local logs

### How to use

After installing and opening the app:

**Tap the security button 6 times in a row.**

The settings panel will open. Here you can enter your Telegram bot token and user ID.

### Creating a Telegram bot

1. Open Telegram
2. Message [@BotFather](https://t.me/BotFather)
3. Send `/newbot`
4. Choose a name for your bot
5. Choose a username ending with `bot`
6. Copy the token you receive

### Getting your user ID

1. Message [@userinfobot](https://t.me/userinfobot)
2. The bot will show your numeric user ID
3. Copy it

### Setup in the app

- Enter the token from @BotFather in the token field
- Enter your numeric user ID in the user ID field
- Save and exit

Done. The app is ready for testing on your own device.

---

> **🔴 Final warning: This app is only for testing on your own device.**
>
> **❌ It has no VPN functionality. It is purely educational. ❌**
>
> **🚫 Any use for covert surveillance, controlling other people's devices, or collecting information without the explicit consent of the device owner is prohibited and illegal.**
>
> **⚖️ The user bears full responsibility for illegal use.**

---

### License

GNU General Public License v3.0

### Contact

[Email: zankodesec@gmail.com](mailto:zankodesec@gmail.com)

[Website: zankode.ir](https://zankode.ir)

[Telegram: @zankode](https://t.me/zankode)

developer: @zankode

---

Made for cybersecurity education | zankode
