## ۱-گیت چیست و چه کاربردی دارد؟
گیت یکی از محبوب‌ترین سیستم‌های کنترل ورژن (VSC) توزیع‌شده و متن‌باز جهان است که در سال ۲۰۰۵، لینوس توروالدز (Linus Torvalds)، خالق هسته سیستم‌عامل لینوکس، آن را ایجاد کرد. Git بیشتر برای ردیابی تغییرات فایل‌های پروژه به‌کار برده می‌شود.
گیت از بسیاری از سیستم‌های کنترل ورژن (VCS) مشابه مانند CVS و SVN و Mercurial قوی‌تر است. انجام تغییرات جدید، شاخه‌بندی، ادغام و مقایسه نسخه‌های قبلی همگی برای مدیریت پروژه شما دردسترس هستند. گیت از سیستم توزیع خوشه‌ای یا درختی استفاده می‌کند. برخلاف برخی از نرم‌افزارهای کنترل ورژن، Git هنگام ذخیره تاریخچه و نسخه‌های فایل، نام فایل‌ها را در نظر نمی‌گیرد و روی محتوای فایل متمرکز است. همچنین، مخزن گیت از ترکیب رمزگذاری دلتا برای ذخیره تفاوت‌های کد استفاده و درادامه با فشرده‌سازی، فایل‌ها را کاملاً ذخیره می‌کند

## ۲-دستورgit init چه کاری انجام میدهد؟ 
با این دستور یک پوشه‌ی .git مخفی (Hidden) در پوشه‌ای ساخته می‌شود که دستور را در آن اجرا کرده‌اید. این پوشه همان “Repository” (یا repo) است که گیت تمام داده‌های داخلی‌اش را در آن نگه می‌دارد. حالا می‌توانید فایل‌های موجود در پوشه‌ی اصلی را تغییر دهید و این تغییرات را پیگیری کنید.

## ۳-دستورgit status چه کاربردی دارد؟
با این دستور اطلاعاتی اولیه را خواهید دید. مثلاً اینکه کدام فایل‌ها اخیراً تغییر کرده‌اند.

## ۴-دستورgit add چه کاری انجام میدهد؟
این دستور پس از تغییر فایل‌ها، تغییراتتان را به صورت “staged” ذخیره می‌کند (یا “ready to be committed”).

## ۵-دستورgit commit چه کاری انجام میدهد؟
این دستور ویرایشگر متنِ خطِ فرمانِ پیش‌فرضتان را باز می‌کند و از شما می‌خواهد که یک Commit Message تایپ کنید. بعد از ذخیره‌ و خروج، Commit شما به صورت محلی ذخیره می‌شود.

این پیغام کامیت به سایر اشخاص کمک می‌کند بفهمند که چه چیزی را تغییر داده‌اید و دلیل آن چه بوده است.

## ۶-دستورgit log چه کاربردی دارد؟
