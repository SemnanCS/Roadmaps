# HTTPS

HTTPS یک روش امن برای ارسال داده‌ها بین یک وب سرور و یک مرورگر است.

ارتباط از طریق HTTPS با مرحله دست دادن (handshake) آغاز می‌شود، جایی که سرور و کلاینت توافق می‌کنند که چگونه ارتباط را رمزگذاری کنند. به طور خاص، آن‌ها یک الگوریتم رمزگذاری و یک کلید مخفی را انتخاب می‌کنند. پس از مرحله دست دادن، تمام ارتباطات بین سرور و کلاینت با استفاده از الگوریتم و کلید توافق‌شده رمزگذاری خواهد شد.

مرحله دست دادن از نوع خاصی از رمزنگاری به نام رمزنگاری نامتقارن استفاده می‌کند تا به طور امن ارتباط برقرار کند، حتی اگر کلاینت و سرور هنوز بر روی یک کلید مخفی توافق نکرده باشند. پس از مرحله دست دادن، ارتباط HTTPS با استفاده از رمزنگاری متقارن که بسیار کارآمدتر است، رمزگذاری می‌شود، اما نیاز به این دارد که کلاینت و سرور هر دو از کلید مخفی آگاه باشند.

برای یادگیری بیشتر به منابع زیر مراجعه کنید:

- [@article@What is HTTPS?](https://www.cloudflare.com/en-gb/learning/ssl/what-is-https/)
- [@article@Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)
- [@article@Enabling HTTPS on Your Servers](https://web.dev/articles/enable-https)
- [@article@How HTTPS works (comic)](https://howhttps.works/)
- [@video@SSL, TLS, HTTP, HTTPS Explained](https://www.youtube.com/watch?v=hExRDVZHhig)
- [@video@HTTPS — Stories from the field](https://www.youtube.com/watch?v=GoXgl9r0Kjk)
- [@article@HTTPS explained with carrier pigeons](https://baida.dev/articles/https-explained-with-carrier-pigeons)
