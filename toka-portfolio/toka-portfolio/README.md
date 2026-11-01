# Toka Ahmed Ali Ali Elwakeel: Portfolio

مشروع بورتفوليو كامل: ملف واحد `index.html` + مجلد `assets`. مفيش أي مكتبات ولا build.

## التشغيل
- افتحي `index.html` بالدبل كليك (الخطوط محتاجة إنترنت، من غيرها بيظهر خط بديل).
- أو من التيرمنال داخل المجلد: `python3 -m http.server 8000` وافتحي http://localhost:8000
- للنشر: ارفعي المجلد كله على Netlify أو GitHub Pages أو أي استضافة (لازم `index.html` و`assets` جنب بعض).

## التعديل (كله في أول الـ `<script>` داخل index.html، تحت `CONFIG`)
- **الألوان:** `CONFIG.theme` (p1 لـ p5 درجات الكحلي للخلفيات، p6 وp7 الوردي للنص والعناوين). وفيه زرار Theme في الموقع بيجرّب الألوان.
- **الإيميل والرقم والسوشيال:** `email` و`phone` و`whatsapp` و`social`.
- **صورة الهيرو:** استبدلي `assets/img/hero.webp` بصورتك PNG/WebP شفافة بنفس الاسم. **صورة About:** `assets/img/photo.jpg`. **QR الواتساب:** `assets/img/qr.png`.
- **أنواع الوظايف المكتوبة في الهيرو:** `CONFIG.roles`.
- **الفيديوهات (Video Editor):** `CONFIG.videos`. لكل فيديو: `title` و`cat` و`poster` (صورة مصغرة) و`preview` (مقطع قصير صامت بيشتغل في الكارت) و`drive` (ID الملف من لينك درايف: الجزء اللي بعد `/d/`) و`link`. لإضافة فيديو جديد انسخي سطر فيديو وغيّري القيم.
- **فيديوهات AI:** `CONFIG.ai` (`video` مسار ملف mp4 جوه assets أو لينك مباشر، و`poster`).
- **المنشورات والكابشنز:** `CONFIG.content`. **الجرافيك:** `CONFIG.graphics` (حقل `cat` بيعمل الفلتر لوحده). **الشهادات:** `CONFIG.certs` (صورة في `src` أو PDF في `pdf`).
- **أدوات البرامج:** `CONFIG.tools` و`CONFIG.videoTools`.
- **الكامبينز (28 شريحة):** صور `assets/img/campaign-01.webp` وما بعدها، والقائمة في `IMGS.slides`.
- ترتيب أي عنصر أو حذفه: غيّري ترتيب السطر في المصفوفة أو امسحيه.

## ملاحظات
- مشغّل درايف جوه النافذة بيحتاج إن الملف يكون "Anyone with the link".
- الفيديوهات الموجودة في `assets/video` مضغوطة. تقدري تستبدليها بنسخ أعلى جودة بنفس الاسم.
