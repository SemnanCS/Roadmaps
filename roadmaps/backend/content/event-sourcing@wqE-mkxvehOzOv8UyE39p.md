# Event Sourcing

Event sourcing یک الگوی طراحی است که در آن وضعیت یک سیستم به عنوان دنباله‌ای از وقایع که در طول زمان رخ داده‌اند، نمایان می‌شود. در یک سیستم مبتنی بر Event Sourcing، تغییرات در وضعیت سیستم به صورت وقایع ثبت شده و در یک event store ذخیره می‌شود. وضعیت فعلی سیستم از طریق پخش دوباره وقایع از event store به دست می‌آید.

یکی از مزایای اصلی Event Sourcing این است که تاریخچه واضح و قابل حسابرسی از تمامی تغییرات رخ داده در سیستم را ارائه می‌دهد. این می‌تواند برای اشکال‌زدایی و پیگیری تکامل سیستم در طول زمان مفید باشد.

Event Sourcing اغلب همراه با الگوهای دیگر، مانند Command Query Responsibility Segregation (CQRS) و طراحی مبتنی بر دامنه، برای ساخت سیستم‌های مقیاس‌پذیر و پاسخگو با منطق کسب‌وکار پیچیده استفاده می‌شود. همچنین برای ساخت سیستم‌هایی که نیاز به پشتیبانی از قابلیت‌های undo/redo یا ادغام با سیستم‌های خارجی دارند، مفید است.

برای یادگیری بیشتر به منابع زیر مراجعه کنید:

- [@article@Event Sourcing - Martin Fowler](https://martinfowler.com/eaaDev/EventSourcing.html)
- [@feed@Explore top posts about Architecture](https://app.daily.dev/tags/architecture?ref=roadmapsh)
