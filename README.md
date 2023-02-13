# به نام خدا
## ۱-گیت چیست و چه کاربردی دارد؟
گیت یکی از محبوب‌ترین سیستم‌های کنترل ورژن (VSC) توزیع‌شده و متن‌باز جهان است که در سال ۲۰۰۵، لینوس توروالدز (Linus Torvalds)، خالق هسته سیستم‌عامل لینوکس، آن را ایجاد کرد. Git بیشتر برای ردیابی تغییرات فایل‌های پروژه به‌کار برده می‌شود.
گیت از بسیاری از سیستم‌های کنترل ورژن (VCS) مشابه مانند CVS و SVN و Mercurial قوی‌تر است. انجام تغییرات جدید، شاخه‌بندی، ادغام و مقایسه نسخه‌های قبلی همگی برای مدیریت پروژه شما دردسترس هستند. گیت از سیستم توزیع خوشه‌ای یا درختی استفاده می‌کند. برخلاف برخی از نرم‌افزارهای کنترل ورژن، Git هنگام ذخیره تاریخچه و نسخه‌های فایل، نام فایل‌ها را در نظر نمی‌گیرد و روی محتوای فایل متمرکز است. همچنین، مخزن گیت از ترکیب رمزگذاری دلتا برای ذخیره تفاوت‌های کد استفاده و درادامه با فشرده‌سازی، فایل‌ها را کاملاً ذخیره می‌کند

## ۲-دستورgit init چه کاری انجام میدهد؟ 
برای ایجاد مخزن جدید، از دستور git init استفاده می‌شود. git init دستوری یک‌بارمصرف است که فقط هنگام راه‌اندازی اولیه و ایجاد مخزن جدید استفاده می‌شود. اجرای این دستور پوشه‌ای جدید به نام git. در دایرکتوری فعلی شما ایجاد می‌کند.
## ۳-دستورgit status چه کاربردی دارد؟
دستور Git Status برای نمایش وضعیت مخزن و ناحیه مرحله‌بندی استفاده می‌شود. با استفاده از این دستور، می‌توانید فایل‌های موجود در ناحیه مرحله‌بندی و فایل‌های ویرایش‌شده‌ و نیازمند به ثبت را مشاهده کنید. این دستور اطلاعاتی از Commitهای ثبت‌شده را نشان نمی‌دهد و برای نمایش وضعیت بین Git Add و Git Commit استفاده می‌شود. اگر گیت تغییرات فایل‌ها را به‌درستی ردیابی کند، پس از تغییر فایل، باید آن را در Git Status ببینیم.
## ۴-دستورgit add چه کاری انجام میدهد؟
دستور git add فایل‌های فعلی را به ناحیه نسخه‌بندی (Staging) اضافه می‌کند (قبل از ثبت تغییرات با Commit). هربار که فایلی را در پروژه خود اضافه یا به‌روز می‌کنید، برای ثبت تغییرات، باید به‌روز‌رسانی‌ها را به قسمت Staging ارسال کنید. دستور git add را می‌توان چندین‌بار قبل از انجام Commit اجرا کرد. در‌نهایت، همه این فایل‌ها را می‌توان با یک Commit ثبت کرد. دستور add فایل‌هایی را اضافه می‌کند که در خط فرمان مشخص شده‌اند.
## ۵-دستورgit commit چه کاری انجام میدهد؟
کامیت برای ثبت تغییرات فایل‌ها در مخزن و معمولاً بعد از git add استفاده می‌شود. هر Commit حاوی اطلاعات و پیام‌های مربوط به آن Commit است. وقتی فایلی را در Git با استفاده از دستور git add اضافه می‌کنید، در قسمت مرحله‌بندی ذخیره می‌شود. به‌عبارت‌دیگر، هر کامیت فایل‌های درون منطقه مرحله‌بندی را به مخزن گیت اضافه می‌کند.
## ۶-دستورgit log چه کاربردی دارد؟
دستور Git Log ابزاری کاربردی برای بررسی تغییرات ایجاد‌شده در مخزن گیت است. برای مشخص‌کردن تاریخچه سورس کد، می‌توانید از این دستور استفاده کنید. به‌طور‌کلی، Git Log رکوردی از Commitهای ثبت شده است.
## ۷-دستورgit branch چه کاری انجام میدهد؟
اغلب چند شاخه در مخزن Git وجود دارد. شاخه یا branch یک خط مستقل از توسعه کد است.

با دستور git branch می توانید شاخه ها را به طور موثر مدیریت کنید. گزینه ها و سوئیچ های مختلفی از Git branch وجود دارد
## ۸-دستورgit remote add چه کاری انجام میدهد و چه کاربردی دارد؟
این دستور مانند یک مرز اطراف مخزن عمل می کند. در صورت نیاز به ارتباط با دنیای خارج از مخزن باید از دستور git remote استفاده کنید. این دستور مخزن محلی را به ریموت متصل می کند.
## ۹-دستورgit push چه کاری انجام میدهد؟
دستور git push برای بارگذاری محتویات مخزن Local به مخزن remote استفاده می شود. با push کردن، شما commit های Local خود را به مخزن remote منتقل می کنید.
## ۱۰-دستورgit pull چه کاری انجام میدهد و برای چه استفاده میشود؟
دستور git pull محتوا را دانلود کرده (نه متاداده ها) و بلافاصله مخزن محلی را با جدیدترین مطالب به روزرسانی می کند.


