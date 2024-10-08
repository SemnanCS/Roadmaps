# Server-Sent Events

**Server-Sent Events (SSE)** یک فناوری است که به سرور وب این امکان را می‌دهد تا داده‌ها را به صورت زنده به یک کلاینت ارسال کند. این فناوری از یک اتصال HTTP برای ارسال جریان داده‌ها از سرور به کلاینت استفاده می‌کند و کلاینت می‌تواند این رویدادها را گوش داده و زمانی که دریافت می‌شوند، اقدام لازم را انجام دهد.

SSE برای برنامه‌هایی که به بروزرسانی‌های زنده نیاز دارند، مانند سیستم‌های چت، نشانگرهای سهام، و فیدهای رسانه‌های اجتماعی مفید است. این یک روش ساده و کارآمد برای ایجاد یک ارتباط طولانی‌مدت بین کلاینت و سرور است و توسط اکثر مرورگرهای وب مدرن پشتیبانی می‌شود.

برای استفاده از SSE، کلاینت باید یک شیء **EventSource** ایجاد کند و URL اسکریپت سمت سرور که رویدادها را ارسال می‌کند، مشخص کند. سپس سرور می‌تواند با نوشتن رویدادها به جریان پاسخ با فرمت مناسب، رویدادها را ارسال کند.

برای یادگیری بیشتر به منابع زیر مراجعه کنید:

- [@article@Server-Sent Events - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)
