# CiterLab
[Türkçe](README.md) · [English](README.en.md) · [Deutsch](README.de.md) · [العربية](README.ar.md)

**حزمة برامج أكاديمية متعددة الأغراض**

CiterLab تطبيق لسطح مكتب Windows يجمع أدوات العمل بالمصادر وأرشيف الاقتباسات الشخصي والتحليل الإحصائي والمستندات.

هذا المستودع عرض رسمي لمنتج CiterLab. لا يحتوي على الشفرة المصدرية للتطبيق أو حزمة تثبيت قابلة للتشغيل.

يجري إعداد الإصدار. راجع الموقع الرسمي لمعرفة توفر التنزيل والشراء حاليًا.

![CiterLab](images/og.png)

## أربعة أمثلة عمل حقيقية

**28 نوعًا من التبويبات ونافذة واحدة للتحويل إلى VCF: مجموعها 29 أداة.**

تظهر كل أداة مع أيقونتها في التطبيق وشاشة عمل حقيقية. تشمل القائمة مشاريعي؛ وتفتح أداة VCF في نافذة حوار مستقلة.

تعرض الصور الواجهة التركية بسمة التطبيق الفعلية وعلى مقياس Windows بنسبة 125٪. البيانات التجريبية والأمثلة المحلولة ليست نتائج بحثية. قيّم النتائج مع مراعاة البيانات والمنهج ونطاق المصادر.

<table>
<tr>
<td><a href="#module-excel_analiz"><img src="images/gallery/excel_analiz.webp" alt="نتائج تحليل التباين المحسوبة في مساحة التحليل الكمي في CiterLab" width="360"></a><br><a href="#module-excel_analiz"><strong>التحليل الكمي</strong></a></td>
<td><a href="#module-bib"><img src="images/gallery/bib.webp" alt="نتائج البحث عن المنشورات ومعلومات المصادر في تبويب البحث في الأدبيات في CiterLab" width="360"></a><br><a href="#module-bib"><strong>البحث في الأدبيات</strong></a></td>
</tr>
<tr>
<td><a href="#module-bibliometric"><img src="images/gallery/bibliometric.webp" alt="نتائج محسوبة من بيانات المنشورات في التحليل الببليومتري في CiterLab" width="360"></a><br><a href="#module-bibliometric"><strong>التحليل الببليومتري</strong></a></td>
<td><a href="#module-calc"><img src="images/gallery/calc.webp" alt="الدالة الأسية e مرفوعة للقوة x مرسومة في مساحة الرسوم البيانية والهندسة في CiterLab" width="360"></a><br><a href="#module-calc"><strong>الرسوم البيانية والهندسة</strong></a></td>
</tr>
</table>

<a id="tool-overview"></a>

## جميع الأدوات بنظرة واحدة

| الأيقونة | الأداة | الميزات الرئيسية |
| --- | --- | --- |
| <img src="images/gallery/icon-excel_analiz.png" alt="" width="32" height="32"> | [التحليل الكمي](#module-excel_analiz) | قارن المجموعات بتحليل التباين<br>حدّد أدوار المتغيرات بوضوح<br>انقل النتائج إلى تقريرك |
| <img src="images/gallery/icon-qda.png" alt="" width="32" height="32"> | [التحليل النوعي](#module-qda) | رمّز المقاطع مباشرة<br>اعرض المصادر والرموز معًا<br>استكشف الموضوعات بالمصفوفات |
| <img src="images/gallery/icon-bib.png" alt="" width="32" height="32"> | [البحث في الأدبيات](#module-bib) | راجع المنشورات في قائمة واحدة<br>انتقل إلى ملخصات المصادر<br>صدّر نتائج البحث |
| <img src="images/gallery/icon-bibliometric.png" alt="" width="32" height="32"> | [التحليل الببليومتري](#module-bibliometric) | شاهد توزيع المنشورات حسب السنة<br>قارن المؤلفين والمصادر<br>راجع جودة البيانات |
| <img src="images/gallery/icon-calc.png" alt="" width="32" height="32"> | [الرسوم البيانية والهندسة](#module-calc) | شاهد منحنى eˣ<br>استكشف المشتقات والتكاملات<br>أنشئ عناصر هندسية |
| <img src="images/gallery/icon-desing.png" alt="" width="32" height="32"> | [تصميم البحث](#module-desing) | استكشف التصاميم مع شروحها<br>خطّط لأدوار المتغيرات<br>قيّم خيارات التحليل |
| <img src="images/gallery/icon-concept_library.png" alt="" width="32" height="32"> | [مكتبة المفاهيم](#module-concept_library) | اقرأ التعريف مع مصدره<br>تتبّع المفاهيم المرتبطة<br>أضف محتوى موثّقًا إلى نصك |
| <img src="images/gallery/icon-databank.png" alt="" width="32" height="32"> | [بنك البيانات](#module-databank) | استكشف مصادر البيانات<br>استورد ملفًا محليًا<br>رشّح جدولك وافحصه |
| <img src="images/gallery/icon-cheatsheets.png" alt="" width="32" height="32"> | [الأدلة المرجعية](#module-cheatsheets) | تنقّل سريعًا بين الموضوعات<br>شاهد الصيغ مع أمثلتها<br>صدّر الأدلة بصيغة PDF أو DOCX |
| <img src="images/gallery/icon-library.png" alt="" width="32" height="32"> | [أرشيف المصادر](#module-library) | ابحث في أرشيفك<br>راجع بيانات المصادر<br>عُد إلى الوثائق المحفوظة |
| <img src="images/gallery/icon-bibliography_check.png" alt="" width="32" height="32"> | [تدقيق الاستشهادات](#module-bibliography_check) | قارن الاستشهادات بالمراجع<br>راجع المطابقات معًا<br>افتح تقرير التدقيق |
| <img src="images/gallery/icon-lo_docx.png" alt="" width="32" height="32"> | [DOCX](#module-lo_docx) | نسّق نصك<br>أضف الجداول والصور<br>حرّر داخل مساحة عملك |
| <img src="images/gallery/icon-lo_xlsx.png" alt="" width="32" height="32"> | [XLSX](#module-lo_xlsx) | حرّر الخلايا مباشرة<br>احسب باستخدام الصيغ<br>احفظ مصنفك |
| <img src="images/gallery/icon-lo_pptx.png" alt="" width="32" height="32"> | [العروض التقديمية](#module-lo_pptx) | حرّر شرائحك<br>اجمع النصوص والصور<br>احفظ عرضك التقديمي |
| <img src="images/gallery/icon-lo_draw.png" alt="" width="32" height="32"> | [وثائق الرسم](#module-lo_draw) | اشرح بالأشكال<br>رتّب النصوص والصور<br>احفظ وثيقة الرسم |
| <img src="images/gallery/icon-lo_math.png" alt="" width="32" height="32"> | [محرّر الصيغ](#module-lo_math) | اعمل على الصيغ في تبويب<br>حرّر الترميز الرياضي<br>احفظ وثيقة الصيغ |
| <img src="images/gallery/icon-lo_base.png" alt="" width="32" height="32"> | [محرّر قواعد البيانات](#module-lo_base) | افتح وثيقة قاعدة بيانات<br>اعمل في تبويب مخصص<br>احفظ وثيقتك |
| <img src="images/gallery/icon-text.png" alt="" width="32" height="32"> | [محرّر النصوص](#module-text) | ابدأ بتدوين الملاحظات<br>حرّر النص العادي مباشرة<br>احفظ نصك في ملف |
| <img src="images/gallery/icon-tex.png" alt="" width="32" height="32"> | [استوديو TeX](#module-tex) | حرّر مصدر LaTeX<br>راجع مخرجات التجميع<br>اعمل مع معاينة الوثيقة |
| <img src="images/gallery/icon-pdf.png" alt="" width="32" height="32"> | [محرّر PDF](#module-pdf) | تنقّل بين الصفحات<br>ابحث في نص الوثيقة<br>اضبط عرض القراءة |
| <img src="images/gallery/icon-paint.png" alt="" width="32" height="32"> | [دفتر الرسم](#module-paint) | ارسم بحرية<br>اختر الألوان والأقلام<br>أنشئ مسودات بصرية |
| <img src="images/gallery/icon-epub.png" alt="" width="32" height="32"> | [قارئ EPUB](#module-epub) | تنقّل عبر الفهرس<br>ابحث داخل الكتاب<br>اضبط حجم الخط |
| <img src="images/gallery/icon-web.png" alt="" width="32" height="32"> | [متصفّح الويب](#module-web) | افتح الصفحة بعنوانها<br>تنقّل بين الصفحات<br>راجع المصادر جنبًا إلى جنب |
| <img src="images/gallery/icon-media.png" alt="" width="32" height="32"> | [مشغّل الوسائط](#module-media) | افتح الصوت والفيديو<br>تنقّل على الخط الزمني<br>تحكّم في التشغيل |
| <img src="images/gallery/icon-automation.png" alt="" width="32" height="32"> | [عمليات الوثائق](#module-automation) | اجمع الملفات في قائمة واحدة<br>اختر عملية للوثائق<br>تابع حالة العملية |
| <img src="images/gallery/icon-mini_calc.png" alt="" width="32" height="32"> | [الآلة الحاسبة](#module-mini_calc) | احسب العمليات الأساسية<br>شاهد النتيجة فورًا<br>راجع سجل الحسابات |
| <img src="images/gallery/icon-signature.png" alt="" width="32" height="32"> | [مدير التوقيعات](#module-signature) | ارسم توقيعًا<br>اقتصص الصورة وحسّنها<br>راجع المعاينة الشفافة |
| <img src="images/gallery/icon-projects.png" alt="" width="32" height="32"> | [مشاريعي](#module-projects) | شاهد المشاريع في قائمة واحدة<br>عُد إلى وثائقك<br>اجمع ملاحظات المشروع |
| <img src="images/gallery/icon-contacts_vcf.png" alt="" width="32" height="32"> | [من Excel إلى جهات الاتصال (VCF)](#module-contacts_vcf) | اختر جدول جهات الاتصال<br>طابق الحقول بوضوح<br>جهّز ملف VCF |

## استكشف كل أداة

<a id="module-excel_analiz"></a>

<details>
<summary><img src="images/gallery/icon-excel_analiz.png" alt="" width="24" height="24"> <strong>التحليل الكمي</strong> · تبويب</summary>

### من البيانات إلى النتائج

اختر المتغيرات ونفّذ التحليل المناسب، ثم راجع النتائج المحسوبة في تقريرك.

- قارن المجموعات بتحليل التباين
- حدّد أدوار المتغيرات بوضوح
- انقل النتائج إلى تقريرك

<img src="images/gallery/excel_analiz.webp" alt="نتائج تحليل التباين المحسوبة في مساحة التحليل الكمي في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/excel_analiz.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-qda"></a>

<details>
<summary><img src="images/gallery/icon-qda.png" alt="" width="24" height="24"> <strong>التحليل النوعي</strong> · تبويب</summary>

### أظهر المعنى بالترميز

رمّز نصوص المصادر وراجع المقاطع المختارة والملاحظات والعلاقات بين الموضوعات.

- رمّز المقاطع مباشرة
- اعرض المصادر والرموز معًا
- استكشف الموضوعات بالمصفوفات

<img src="images/gallery/qda.webp" alt="نص المصدر وشجرة الرموز والمقاطع المرمّزة في التحليل النوعي في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/qda.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-bib"></a>

<details>
<summary><img src="images/gallery/icon-bib.png" alt="" width="24" height="24"> <strong>البحث في الأدبيات</strong> · تبويب</summary>

### تتبّع سؤالك البحثي

ابحث في المصادر الأكاديمية وراجع المنشورات وملخصات المصادر والجمل المختارة في عروض منظمة.

- راجع المنشورات في قائمة واحدة
- انتقل إلى ملخصات المصادر
- صدّر نتائج البحث

<img src="images/gallery/bib.webp" alt="نتائج البحث عن المنشورات ومعلومات المصادر في تبويب البحث في الأدبيات في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/bib.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-bibliometric"></a>

<details>
<summary><img src="images/gallery/icon-bibliometric.png" alt="" width="24" height="24"> <strong>التحليل الببليومتري</strong> · تبويب</summary>

### اكتشف أنماط الأدبيات

حلّل السنوات والمؤلفين والمصادر والمصطلحات في بيانات المنشورات لتتعرّف إلى مجالك البحثي بعمق أكبر.

- شاهد توزيع المنشورات حسب السنة
- قارن المؤلفين والمصادر
- راجع جودة البيانات

<img src="images/gallery/bibliometric.webp" alt="نتائج محسوبة من بيانات المنشورات في التحليل الببليومتري في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/bibliometric.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-calc"></a>

<details>
<summary><img src="images/gallery/icon-calc.png" alt="" width="24" height="24"> <strong>الرسوم البيانية والهندسة</strong> · تبويب</summary>

### استكشف الرياضيات بصريًا

ارسم الدوال وأضف العناصر الرياضية واستكشف الهندسة على المستوى الإحداثي نفسه.

- شاهد منحنى eˣ
- استكشف المشتقات والتكاملات
- أنشئ عناصر هندسية

<img src="images/gallery/calc.webp" alt="الدالة الأسية e مرفوعة للقوة x مرسومة في مساحة الرسوم البيانية والهندسة في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/calc.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-desing"></a>

<details>
<summary><img src="images/gallery/icon-desing.png" alt="" width="24" height="24"> <strong>تصميم البحث</strong> · تبويب</summary>

### من السؤال إلى المنهج

استكشف تصاميم البحث ونظّم متغيراتك وخيارات التحليل ضمن خطة واضحة.

- استكشف التصاميم مع شروحها
- خطّط لأدوار المتغيرات
- قيّم خيارات التحليل

<img src="images/gallery/desing.webp" alt="تصميم بحث مختار وشرحه المنهجي في مساحة تصميم البحث في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/desing.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-concept_library"></a>

<details>
<summary><img src="images/gallery/icon-concept_library.png" alt="" width="24" height="24"> <strong>مكتبة المفاهيم</strong> · تبويب</summary>

### افهم المفاهيم في سياقها

استكشف المفاهيم مع تعريفاتها ومصادرها، وانتقل بين المصطلحات المرتبطة وأضف محتوى موثّقًا إلى نصك البحثي.

- اقرأ التعريف مع مصدره
- تتبّع المفاهيم المرتبطة
- أضف محتوى موثّقًا إلى نصك

<img src="images/gallery/concept_library.webp" alt="تعريف ومفاهيم مرتبطة ومصادر في مكتبة المفاهيم في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/concept_library.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-databank"></a>

<details>
<summary><img src="images/gallery/icon-databank.png" alt="" width="24" height="24"> <strong>بنك البيانات</strong> · تبويب</summary>

### اربط البيانات ببحثك

استكشف مصادر البيانات أو افتح ملفًا محليًا، ثم رشّح الجداول لمراجعة المشاهدات التي تحتاجها.

- استكشف مصادر البيانات
- استورد ملفًا محليًا
- رشّح جدولك وافحصه

<img src="images/gallery/databank.webp" alt="جدول بيانات وأدوات ترشيح في مساحة بنك البيانات في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/databank.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-cheatsheets"></a>

<details>
<summary><img src="images/gallery/icon-cheatsheets.png" alt="" width="24" height="24"> <strong>الأدلة المرجعية</strong> · تبويب</summary>

### المعرفة في متناولك

اقرأ أدلة الموضوعات مع الصيغ والأمثلة، وابحث في محتواها وصدّر الدليل الذي تختاره.

- تنقّل سريعًا بين الموضوعات
- شاهد الصيغ مع أمثلتها
- صدّر الأدلة بصيغة PDF أو DOCX

<img src="images/gallery/cheatsheets.webp" alt="قائمة موضوعات وصفحة دليل تحتوي على صيغ في الأدلة المرجعية في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/cheatsheets.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-library"></a>

<details>
<summary><img src="images/gallery/icon-library.png" alt="" width="24" height="24"> <strong>أرشيف المصادر</strong> · تبويب</summary>

### عُد إلى مصادرك

ابحث في المنشورات والوثائق المؤرشفة، وراجع بيانات مصادرها ومحتواها المحفوظ إلى جانب بحثك.

- ابحث في أرشيفك
- راجع بيانات المصادر
- عُد إلى الوثائق المحفوظة

<img src="images/gallery/library.webp" alt="نتائج بحث وسجل مصدر مختار في أرشيف المصادر في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/library.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-bibliography_check"></a>

<details>
<summary><img src="images/gallery/icon-bibliography_check.png" alt="" width="24" height="24"> <strong>تدقيق الاستشهادات</strong> · تبويب</summary>

### تحقّق من مسار الاستشهاد

راجع تطابق استشهادات الوثيقة مع مراجعها، وشاهد العناصر المتطابقة والنقاط التي تحتاج إلى مراجعة في التقرير.

- قارن الاستشهادات بالمراجع
- راجع المطابقات معًا
- افتح تقرير التدقيق

<img src="images/gallery/bibliography_check.webp" alt="نتائج مطابقة استشهادات الوثيقة مع المراجع في أداة تدقيق الاستشهادات في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/bibliography_check.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-lo_docx"></a>

<details>
<summary><img src="images/gallery/icon-lo_docx.png" alt="" width="24" height="24"> <strong>DOCX</strong> · تبويب</summary>

### حوّل النتائج إلى كلمات

اكتب وثيقتك البحثية في مساحة العمل ونظّمها بالعناوين والجداول والصور، ثم احفظ عملك.

- نسّق نصك
- أضف الجداول والصور
- حرّر داخل مساحة عملك

<img src="images/gallery/lo_docx.webp" alt="وثيقة بحثية منسّقة بصيغة DOCX مفتوحة داخل CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/lo_docx.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-lo_xlsx"></a>

<details>
<summary><img src="images/gallery/icon-lo_xlsx.png" alt="" width="24" height="24"> <strong>XLSX</strong> · تبويب</summary>

### حافظ على تنظيم بياناتك

افتح جدول بياناتك في مساحة العمل وحرّر خلاياه وصيغه وتنسيقه مباشرة.

- حرّر الخلايا مباشرة
- احسب باستخدام الصيغ
- احفظ مصنفك

<img src="images/gallery/lo_xlsx.webp" alt="جدول بيانات بصيغة XLSX يحتوي على بيانات ومفتوح داخل CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/lo_xlsx.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-lo_pptx"></a>

<details>
<summary><img src="images/gallery/icon-lo_pptx.png" alt="" width="24" height="24"> <strong>العروض التقديمية</strong> · تبويب</summary>

### قدّم بحثك للجمهور

حرّر شرائح العرض داخل مساحة عملك وابنِ قصة بحثك بالنصوص والصور.

- حرّر شرائحك
- اجمع النصوص والصور
- احفظ عرضك التقديمي

<img src="images/gallery/lo_pptx.webp" alt="شريحة بحثية في محرّر العروض التقديمية داخل CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/lo_pptx.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-lo_draw"></a>

<details>
<summary><img src="images/gallery/icon-lo_draw.png" alt="" width="24" height="24"> <strong>وثائق الرسم</strong> · تبويب</summary>

### امنح أفكارك شكلًا بصريًا

اجمع الأشكال والنصوص والصور في وثيقة رسم لإنشاء شروح بصرية واضحة.

- اشرح بالأشكال
- رتّب النصوص والصور
- احفظ وثيقة الرسم

<img src="images/gallery/lo_draw.webp" alt="صفحة رسم تحتوي على أشكال ونصوص في محرّر وثائق الرسم في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/lo_draw.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-lo_math"></a>

<details>
<summary><img src="images/gallery/icon-lo_math.png" alt="" width="24" height="24"> <strong>محرّر الصيغ</strong> · تبويب</summary>

### صُغ التعبيرات الرياضية

أنشئ وثيقة صيغ في تبويب مستقل وحرّر الترميز الرياضي، ثم احفظ عملك.

- اعمل على الصيغ في تبويب
- حرّر الترميز الرياضي
- احفظ وثيقة الصيغ

<img src="images/gallery/lo_math.webp" alt="تعبير رياضي مفتوح في محرّر الصيغ في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/lo_math.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-lo_base"></a>

<details>
<summary><img src="images/gallery/icon-lo_base.png" alt="" width="24" height="24"> <strong>محرّر قواعد البيانات</strong> · تبويب</summary>

### مساحة للعمل بقواعد البيانات

افتح وثائق قواعد البيانات في تبويب مخصص داخل مساحة العمل واستخدم محرّر قواعد البيانات.

- افتح وثيقة قاعدة بيانات
- اعمل في تبويب مخصص
- احفظ وثيقتك

<img src="images/gallery/lo_base.webp" alt="محرّر وثائق قواعد البيانات داخل CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/lo_base.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-text"></a>

<details>
<summary><img src="images/gallery/icon-text.png" alt="" width="24" height="24"> <strong>محرّر النصوص</strong> · تبويب</summary>

### دوّن الفكرة فورًا

اكتب ملاحظاتك النصية وحرّرها في تبويب وثيقة، ثم احفظها في ملف.

- ابدأ بتدوين الملاحظات
- حرّر النص العادي مباشرة
- احفظ نصك في ملف

<img src="images/gallery/text.webp" alt="ملاحظات بحثية في تبويب محرّر النصوص في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/text.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-tex"></a>

<details>
<summary><img src="images/gallery/icon-tex.png" alt="" width="24" height="24"> <strong>استوديو TeX</strong> · تبويب</summary>

### صُغ نصك العلمي بعناية

حرّر مصدر TeX وLaTeX، وراجع مخرجات التجميع وطوّر عملك باستخدام معاينة الوثيقة.

- حرّر مصدر LaTeX
- راجع مخرجات التجميع
- اعمل مع معاينة الوثيقة

<img src="images/gallery/tex.webp" alt="شيفرة مصدر LaTeX ومعاينة وثيقة في استوديو TeX في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/tex.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-pdf"></a>

<details>
<summary><img src="images/gallery/icon-pdf.png" alt="" width="24" height="24"> <strong>محرّر PDF</strong> · تبويب</summary>

### اربط القراءة بالبحث

تنقّل بين صفحات PDF وابحث في النص وراجع الوثائق في مساحة العمل نفسها التي تضم أدوات بحثك.

- تنقّل بين الصفحات
- ابحث في نص الوثيقة
- اضبط عرض القراءة

<img src="images/gallery/pdf.webp" alt="وثيقة بحثية مفتوحة مع أدوات الصفحات في مساحة PDF في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/pdf.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-paint"></a>

<details>
<summary><img src="images/gallery/icon-paint.png" alt="" width="24" height="24"> <strong>دفتر الرسم</strong> · تبويب</summary>

### ارسم بداية الفكرة

ارسم بحرية وفكّر بالألوان وحوّل فكرتك البحثية إلى مسودة بصرية.

- ارسم بحرية
- اختر الألوان والأقلام
- أنشئ مسودات بصرية

<img src="images/gallery/paint.webp" alt="لوحة رسم وأدوات أقلام في دفتر الرسم في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/paint.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-epub"></a>

<details>
<summary><img src="images/gallery/icon-epub.png" alt="" width="24" height="24"> <strong>قارئ EPUB</strong> · تبويب</summary>

### تنقّل في الكتب براحة

افتح كتاب EPUB واصل إلى القسم الذي تحتاجه باستخدام الفهرس والبحث النصي وإعدادات القراءة.

- تنقّل عبر الفهرس
- ابحث داخل الكتاب
- اضبط حجم الخط

<img src="images/gallery/epub.webp" alt="فصل كتاب وقائمة محتويات في قارئ EPUB في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/epub.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-web"></a>

<details>
<summary><img src="images/gallery/icon-web.png" alt="" width="24" height="24"> <strong>متصفّح الويب</strong> · تبويب</summary>

### أبقِ بحث الويب قريبًا

افتح صفحات الويب في تبويب داخل مساحة العمل وراجع المصادر إلى جانب وثائقك.

- افتح الصفحة بعنوانها
- تنقّل بين الصفحات
- راجع المصادر جنبًا إلى جنب

<img src="images/gallery/web.webp" alt="صفحة بحثية مفتوحة في تبويب متصفّح الويب في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/web.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-media"></a>

<details>
<summary><img src="images/gallery/icon-media.png" alt="" width="24" height="24"> <strong>مشغّل الوسائط</strong> · تبويب</summary>

### راجع الصوت والفيديو

افتح الصوت أو الفيديو في مساحة عملك واستخدم عناصر التشغيل والخط الزمني لمراجعة الأجزاء المطلوبة.

- افتح الصوت والفيديو
- تنقّل على الخط الزمني
- تحكّم في التشغيل

<img src="images/gallery/media.webp" alt="فيديو مفتوح وخط زمني للتشغيل في مشغّل الوسائط في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/media.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-automation"></a>

<details>
<summary><img src="images/gallery/icon-automation.png" alt="" width="24" height="24"> <strong>عمليات الوثائق</strong> · تبويب</summary>

### اجمع مهام الوثائق

أضف الملفات إلى قائمة العمليات واستخدم خيارات التحويل أو الدمج أو التقسيم.

- اجمع الملفات في قائمة واحدة
- اختر عملية للوثائق
- تابع حالة العملية

<img src="images/gallery/automation.webp" alt="قائمة ملفات وخيارات معالجة الوثائق في مساحة عمليات الوثائق في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/automation.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-mini_calc"></a>

<details>
<summary><img src="images/gallery/icon-mini_calc.png" alt="" width="24" height="24"> <strong>الآلة الحاسبة</strong> · تبويب</summary>

### أنجز الحسابات السريعة

نفّذ الحسابات اليومية وراجع الخطوات السابقة في سجل العمليات.

- احسب العمليات الأساسية
- شاهد النتيجة فورًا
- راجع سجل الحسابات

<img src="images/gallery/mini_calc.webp" alt="نتيجة رقمية وسجل عمليات في الآلة الحاسبة في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/mini_calc.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-signature"></a>

<details>
<summary><img src="images/gallery/icon-signature.png" alt="" width="24" height="24"> <strong>مدير التوقيعات</strong> · تبويب</summary>

### جهّز صورة توقيعك

ارسم توقيعًا أو حرّر صورته، ثم عاينها وجهّزها للإدراج في وثيقة.

- ارسم توقيعًا
- اقتصص الصورة وحسّنها
- راجع المعاينة الشفافة

<img src="images/gallery/signature.webp" alt="توقيع تجريبي مرسوم ومعاينة صورته في مدير التوقيعات في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/signature.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-projects"></a>

<details>
<summary><img src="images/gallery/icon-projects.png" alt="" width="24" height="24"> <strong>مشاريعي</strong> · تبويب</summary>

### استأنف بحثك

شاهد مساحات العمل ووثائق المشاريع معًا، ثم واصل عملك مع تفاصيل المشروع وملاحظاته في متناولك.

- شاهد المشاريع في قائمة واحدة
- عُد إلى وثائقك
- اجمع ملاحظات المشروع

<img src="images/gallery/projects.webp" alt="قائمة مشاريع ووثائق وتفاصيل مشروع في مساحة مشاريعي في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/projects.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

<a id="module-contacts_vcf"></a>

<details>
<summary><img src="images/gallery/icon-contacts_vcf.png" alt="" width="24" height="24"> <strong>من Excel إلى جهات الاتصال (VCF)</strong> · نافذة حوار</summary>

### من الجدول إلى جهات الاتصال

طابق حقول جهات الاتصال في جدول Excel وجهّز ملف VCF لاستيراده إلى دفتر جهات الاتصال.

- اختر جدول جهات الاتصال
- طابق الحقول بوضوح
- جهّز ملف VCF

<img src="images/gallery/contacts_vcf.webp" alt="مطابقة حقول جهات الاتصال في نافذة التحويل من Excel إلى VCF في CiterLab" width="1100">

[افتح صورة الشاشة كاملة](images/gallery/contacts_vcf.webp) · [العودة إلى قائمة الأدوات](#tool-overview)

</details>

## مصادر الصور وسياقها

تُحفظ أدناه أوصاف المصادر والتنبيهات الواردة في العرض السابق. راجع [ATTRIBUTIONS.txt](ATTRIBUTIONS.txt) لترخيص المقالة ومصادر الصور.

- [**استوديو الرسوم البيانية**](images/screen-charts.png) — رسوم أُنتجت في التطبيق الحقيقي من بيانات تجريبية اصطناعية؛ وليست نتائج بحثية.
- [**أطلس المفاهيم**](images/screen-concepts.png) — تبقى بيانات المصادر وحالة مراجعة الترجمات ظاهرة في الواجهة.
- [**فحص المراجع**](images/screen-citations.png) — صفحة داخلية من مقالة حقيقية مفتوحة الوصول. صفحة العنوان مستبعدة ومرشح الاقتباسات المطابقة محدد. النتائج مطابقات خوارزمية ولا تعني التحقق من المنشورات الأصلية.

## النطاق والاستخدام

يمكن استخدام الأدوات المحلية ومكوّنات المكتبة والنماذج المنزّلة دون اتصال. يتطلب التفعيل الأول وتنزيل المكوّنات والاستعلام عن المصادر عبر الإنترنت اتصالًا. يعتمد دعم الملفات والتحليلات على العملية. يجب مراجعة المطابقات والافتراضات الإحصائية ومخرجات الذكاء الاصطناعي.

## روابط رسمية

- [الموقع](https://citerlab.com)
- الدعم: [info@citerlab.com](mailto:info@citerlab.com)

## الحقوق ومصادر الصور

يتضمن NOTICE.md بيان الحقوق للمواد الأصلية لـ CiterLab. تحتفظ المقالات والمصادر الخارجية بتراخيصها؛ راجع ATTRIBUTIONS.txt. هذا العرض ليس شهادة ملكية للشفرة المصدرية أو ختمًا زمنيًا موثوقًا.

تاريخ سجل العرض: 2026-11-08.
