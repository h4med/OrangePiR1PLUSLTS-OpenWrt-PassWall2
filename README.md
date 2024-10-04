<div dir="rtl">

## فهرست مطالب

- [گام اول. سخت افزار](#گام-اول-سختافزار)
- [گام دوم: ریختن Image](#گام-دوم-ریختن-image)
- [عنوان سوم](#عنوان-سوم)

در این ریپو نحوه‌ی راه‌اندازی یک فیلترشکن سخت‌افزاری با استفاده از یک SBC ارزان قیمت به نام OrangePi R1 PLUS LTS تشریح خواهد شد.

نکته۱: در این آموزش ممکن است لینک‌هایی به سایت‌های فروش داده شود. این لینکها صرفا جهت راهنمایی خودم و شماست و هیچگونه جنبه‌ی تبلیغاتی نداشته و من نفعی از آن نمی‌برم.

نکته۲: شما می‌توانید با راهنماهای موجود در یوتیوب، مثل [این](https://www.youtube.com/watch?v=m-BAyaHNlV8)  یا سلسله راهنماهای [اینجا](https://ivpn.pro/category/openwrt/) از پایه OpenWrt را نصب کرده و سپس PassWall2 را نصب کرده و تک تک روشها را پیاده‌سازی کنید. اما بدلیل مشکلات اینترنت در ایران انجام این مراحل مشکلات زیادی دارد و ممکن است برای همه راحت نباشد. استفاده از یک Image آماده کار شما را خیلی راحت خواهد کرد.

## گام اول: سخت‌افزار
بورد Orange Pi R1 PLUS LTS یک پردازنده‌ی ۴ هسته ۶۴ بیتی با فرکانس 1.5GHz دارد و با داشتن 1GB RAM یک سخت‌افزار مناسب برای یک روتر خانگی است. مشخصات این بورد را از سایت سازنده می‌توانید ببنید [اینجا](http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/details/orange-pi-R1-Plus-LTS.html).

این بورد در بازار ایران نیز قابل تهیه است و مثلا در حال حاضر (مهر ۱۴۰۳) از وبسایت eca با قیمت ۲/۶۰۰/۰۰۰ تومان قابل تهیه است [لینک](https://eshop.eca.ir/%D8%AE%D8%A7%D9%86%D9%88%D8%A7%D8%AF%D9%87-orange-pi/21222-%D8%A8%D8%B1%D8%AF-%D8%A7%D9%88%D8%B1%D9%86%D8%AC-%D9%BE%D8%A7%DB%8C-orange-pi-r1-plus-lts-%D8%A8%D8%A7-%D8%B1%D9%85-1gb.html).


علاوه بر خود بورد برای راه‌اندازی آن به موارد زیر نیز نیاز است:
- آداپتور تغذیه 5V/3A با پورت Type C
- حافظه Micro SD حداقل 2GB به بالا

و همچنین لوازم جانبی مثل لپتاپ/کامپیوتر با پورت میکرو SD یا داشتن یک تبدیل میکروSD به USB و کابل شبکه برای ارتباط با روتر/SBC.

## گام دوم: ریختن Image
به مرور Imageهای آماده مختلف را برای استفاده با این بورد قرار خواهم داد. Image مدنظر خود را از جدول زیر دانلود کنید.

| عنوان | لینک دانلود |
| -------- | -------- |
| خام  | [لینک](https://github.com/h4med/OrangePiR1PLUSLTS-OpenWrt-PassWall2/raw/refs/heads/main/img1_WarpPlus_v1.zip)  |
| خام+WarpPlus  |  [لینک](https://github.com/h4med/OrangePiR1PLUSLTS-OpenWrt-PassWall2/raw/refs/heads/main/img1_WarpPlus_v1.zip) |


</div>
