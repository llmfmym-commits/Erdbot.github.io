این پوشه برای پچ‌های آینده روی فایل‌های native اندروید (مثل `MainActivity.java`) نگه‌داشته شده.

برای بازی Bricks Breaker Quest در حال حاضر نیازی به پچ خاصی نیست — بازی فقط از:
- Canvas 2D
- Web Audio API
- Vibration API
- LocalStorage

استفاده می‌کند که همگی داخل WebView استاندارد Capacitor به‌درستی کار می‌کنند.
مجوز VIBRATE به‌صورت خودکار توسط `build.yml` به AndroidManifest اضافه می‌شود.

اگر بعداً خواستی AdMob یا هر SDK بومی دیگری اضافه کنی، فایل `MainActivity.java` پچ‌شده را همین‌جا قرار بده؛
workflow به‌صورت خودکار آن را جایگزین می‌کند.
