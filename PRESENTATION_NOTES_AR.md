# ملاحظات سريعة للمناقشة — مشروع LUMINA

## أين أُظهر كل متطلب؟

1. **تقسيم المجلدات**: من جذر المشروع أظهر مجلدات `html`, `css`, `js`, `images`, `videos`, `fonts`, `ajax`, `vendor`.
2. **HTML Layout**: افتح `html/index.html` وأظهر العناصر: `header`, `nav`, `main`, `section`, `aside`, `footer`.
3. **عناصر HTML الأساسية**: العناوين والفقرات والقوائم موجودة في أغلب الصفحات، والجدول موجود في `html/about.html`.
4. **5 صفحات أو أكثر**: المشروع يحتوي 8 صفحات داخل `html/`.
5. **Contact + Font Awesome**: افتح `html/contact.html` وستجد أيقونات البريد والهاتف وWhatsApp وInstagram والموقع.
6. **إنشاء الحساب وتسجيل الدخول + Validation**: افتح `register.html` و`signin.html`. جرّب إرسال النموذج فارغاً، ثم جرّب كلمة مرور وتأكيد مختلفين.
7. **WOWSlider**: موجود أعلى الصفحة الرئيسية `html/index.html`، والملفات المحلية داخل `engine1/` و`data1/`.
8. **Flexbox / Grid**: بطاقات المنتجات تستخدم Bootstrap Grid، كما أن الهيدر وأجزاء عديدة تستخدم Flexbox.
9. **Responsive + Media Queries**: افتح `css/styles.css` وابحث عن `@media`. صغّر المتصفح لإظهار الاستجابة.
10. **Toast Notification**: اضغط `Add to Bag` أو أرسل نموذج التواصل/النشرة. مكتبة Toastify محلية داخل `vendor/toastify/`.
11. **Modal بواسطة Ajax**: في الصفحة الرئيسية يوجد زران داخل قسم **Interactive requirements**. كل زر يفتح Modal مختلفاً، ومحتواه يُجلب من `ajax/offer-modal.html` أو `ajax/shipping-modal.html` بواسطة `$.ajax()` في `js/app.js`.
12. **Bootstrap**: محلي داخل `css/bootstrap.css` و`js/bootstrap.bundle.min.js`.
13. **jQuery**: محلي داخل `js/jquery-2.0.0.min.js` ويُستخدم في الفلاتر والـAjax والنماذج.
14. **GitHub**: ارفع كل محتويات المجلد كما هي. ملف `index.html` في الجذر يحوّل تلقائياً إلى `html/index.html` لكي يعمل GitHub Pages.

## مهم قبل المناقشة

شغّل المشروع عبر **Live Server** وليس بفتح الملف مباشرة بـ `file://`، لأن المتصفحات تمنع Ajax المحلي غالباً. على GitHub Pages سيعمل Ajax بشكل طبيعي.
