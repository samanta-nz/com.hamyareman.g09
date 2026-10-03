# آینهٔ تمیز g09

این مخزن یک snapshot تمیز از شاخهٔ `arena/01a0fe97-com-hamyareman-ir` در مخزن
`samanta-nz/com.hamyareman.ir` است؛ تاریخچهٔ ۹۵۰ مگابایتی منتقل نشده و این مقصد
یک commit مستقل دارد.

## منتقل‌شده

`apps/`، `shared/`، `gradle/`، wrapper و فایل‌های Gradle، `config/`، `content/`،
ابزارهای کاربردی `scripts/`، `tools/`، `bucket-sync/`، HTMLهای `Bucket/Html-files/`
و `0000/`، `debug.keystore` و مستندات ریشه منتقل شده‌اند. ورکفلوها با API اجرای
موفق تازه بررسی شدند؛ برای هر path بیشینهٔ مدت محاسبه شد و فقط اجراهای حداقل
۳۰ ثانیه‌ای نگه داشته شدند. ارجاع شاخهٔ `arena/*` در workflowها به `main` تبدیل شد.

## عمداً منتقل‌نشده

`Spliced-Books/`، `archive/`، `design-previews/`، `تصاویر یک/`، `docs/`,
`ci-report/`، `background-music.html` ریشه، zipهای `background-music-auto-theme*`,
`music-iframe-host-fix-bundle.zip`، `scripts/I-F-html-patch/`، APKها و خروجی‌های
موقت منتقل نشده‌اند. Secretها هم عمداً در Git قرار نگرفته‌اند و باید در Settings
مخزن مقصد ثبت شوند.

## خروجی

حجم checkout حدود ۸۵ مگابایت است. نسخهٔ مرجع ۲٫۴٫۴ / کد ۲۴۴ است و فهرست Secretها،
باکت `c539776.parspack.net` و قرارداد انتشار در README و RELEASES آمده‌اند.
