# نام دستگاه‌هایی

## محتوای درس

در این‌جا معمول‌ترین نام دستگاه‌هایی که ممکن است با آن‌ها برخورد کنید را با هم مرور می‌کنیم:

### ‏دستگاه‌های SCSI 

اگر از سیستم‌تان از نوعی سیستم ذخیره‌سازی با گنجایش بالا بهره می‌گیرد‌، احتمالش وجود
دارد که از پروتکل SCSI (به صورت «اسکازی» خوانده می‌شود) استفاده کند. SCSI مخفف
Small Computer System Interface پروتکلی است که امکان ارتباط بین دیسک‌های
ذخیره‌سازی، چاپگرها، اسکنر‌ها و دیگر لوازم جانبی را فراهم می‌کند. ممکن است شنیده
باشید که سخت‌افزار‌های SCSI در سیستم‌های امروزی مورد استفاده قرار نمی‌گیرند‌، اما
سیستم‌های لینوکسی دیسک‌های سخت را با این پروتکل مورد استفاده قرار می‌دهند و در
دایرکتوری ‎/dev ذخیره می‌کنند. فایل‌های مربوط به این سخت‌افزار‌ها با پیشوند sd (SCSI
disk)‎ ذخیره می‌شود:

فایل‌های سخت‌افزار‌های SCSI:

- ‏‎/dev/sda - اولین دیسک سخت
- ‎/dev/sdb - دومین دیسک سخت
- ‎/dev/sda3 - سومین پارتیشن دیسک سخت اول

### شبه دستگاه‌ها (Pseudo Devices)

همانطور که قبلا شرح دادیم‌، شبه دستگاه‌ها‌، به صورت فیزیکی به سیستم شما متصل
نشده‌اند. لیستی از عمده‌ترین شبه دستگاه‌ها را در زیر می‌بینید:

- ‏‎/dev/zero - ورودی‌های دریافتی‌اش را دور می‌ریزد و جریانی از بایت NULL (مقدار صفر) تولید می‌کند. 
- ‎/dev/null - ورودی‌های دریافتی‌اش را دور می‌ریزد و هیچ خروجی‌ای تولید نمی‌کند.
- ‎/dev/random - اعداد تصادفی تولید می‌کند. 

### دستگاه‌های PATA

گاها ممکن است در سیستم‌های قدیمی‌تر با دیسک سخت‌هایی روبرو شوید که با پیشوند hd ذخیره شده‌اند:

- ‏‎/dev/hda - اولین دیسک سخت
- ‎/dev/hdd4 - دومین پارتیشن روی چهارمین دیسک سخت

## تمرینات

مقداری ورودی روی یکی از شبه دستگاه‌ها بنویسید و ببینید که چه اتفاقی رخ می‌دهد. مراقب باشید که دیسک ذخیره‌سازی‌تان را روی آن‌ها ننویسید!

## سوالات آزمون

معمولا اولین پارتیشن از دومین دیسک SCSI با چه نامی در دایرکتوری ‎/dev ذخیره می‌شود؟

## پاسخ آزمون

sdb2