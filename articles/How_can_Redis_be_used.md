# چگونه می‌توان از Redis استفاده کرد؟

[متن اصلی](https://twitter.com/alexxubyte/status/1610678713087295490)

کاربرد های Redis فقط به caching خلاصه نمی‌شود.

از Redis میتوانیم در سناریوهای مختلفی استفاده کنیم که به طور خلاصه در شکل زیر آمده است.

![image](https://user-images.githubusercontent.com/24452551/210812169-e181cb3b-22d6-454f-a548-267009d58e83.png)

<h3 dir="rtl">
Session
</h3>

از Redis برای اشتراک‌گذاری نشست کاربران بین سرویس‌های مختلف می‌توانیم استفاده کنیم.  

<h3 dir="rtl">Cache</h3>

برای کش کردن داده‌ها براساس محلیت آنها می‌توانیم از Redis استفاده کنیم.
<h3 dir="rtl">Distributed lock</h3>

می‌توان ساختمان داده ی String در Redis استفاده کرد تا در سیستم های توزیع شده قفل برقرار کنیم.

<h3 dir="rtl">Counter</h3>

میتوانیم بشمریم که یک مقاله چه تعداد لایک یا خواننده پیدا کرده است.

<h3 dir="rtl">Rate limiter</h3>

میتوانیم برای IP های کاربران محدودیت قرار دهیم.

<h3 dir="rtl">Shopping cart</h3>

می‌توانیم از Hash در Redis استفاده کنیم تا  کلید و مقدار های سبد خرید را نگهداری کنیم.

<h3 dir="rtl">Calculate user retention</h3>

با استفاده از Bitmap که لاگین کردن روزانه کاربرها را نشان می دهد می توان user retention را محسابه کرد.

<h3 dir="rtl">Message queue</h3>

می توان از List به عنوان message queue استفاده کرد.

<h3 dir="rtl">Ranking</h3>

میتوانیم از ZSet برای مرتب سازی مقاله ها استفاده کنیم.
