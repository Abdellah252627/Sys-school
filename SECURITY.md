# سياسة الأمان

نحن نأخذ أمان نظام إدارة المدارس على محمل الجد. يوضح هذا المستند سياسات الأمان الخاصة بنا وكيفية الإبلاغ عن الثغرات الأمنية.

## الإبلاغ عن ثغرات الأمن

إذا اكتشفت ثغرة أمنية، نرجو إبلاغنا بها على الفور عبر البريد الإلكتروني: **security@schoolsys.com**

### ما يجب تضمينه في التقرير
- وصفاً مفصلاً للثغرة
- خطوات إعادة إنتاج المشكلة
- أي رسائل خطأ أو سجلات ذات صلة
- إصدار النظام المتأثر
- أي إصلاحات أو حلول مؤقتة معروفة

### ما يمكنك توقعه
- سنقوم بالرد على تقريرك في غضون 48 ساعة
- سنقوم بالتحقيق في المشكلة بشكل كامل
- سنقوم بإصدار تصحيحات في أسرع وقت ممكن
- سنقوم بإضافة اسمك إلى قائمة المساهمين إذا رغبت في ذلك

## سياسة الكشف عن المعلومات

سيتم الإعلان عن الثغرات الأمنية بعد إصدار التصحيحات اللازمة. سيتم نشر إشعار أمان مع:
- وصفاً للثغرة
- الإصدارات المتأثرة
- خطوات التحديث
- أي إجراءات تخفيف مؤقتة

## المكافآت

نقدر جهود الباحثين عن الثغرات الأمنية. قد نقدم مكافآت نقدية أو شكراً علنياً للتقارير المؤثرة. يتم تحديد المكافآت بناءً على:
- شدة الثغرة
- جودة التقرير
- تأثير التصحيح

## نطاق الاختبار

يُسمح باختبار الأمان على:
- `*.schoolsys.com`
- التطبيقات المستضافة على النطاقات الفرعية

### ما هو خارج النطاق
- هجمات الحرمان من الخدمة (DDoS)
- هجمات القوة الغاشمة على حسابات المستخدمين
- استغلال الثغرات المعروفة في البرامج القديمة غير المحدثة
- هجمات الهندسة الاجتماعية
- الهجمات المادية

## أفضل الممارسات الأمنية

### للمستخدمين
- استخدم كلمات مرور قوية وفريدة
- قم بتحديث البرامج بانتظام
- لا تشارك بيانات الاعتماد الخاصة بك
- احذر من رسائل البريد الإلكتروني المشبوهة

### للمطورين
- اتبع مبدأ الامتيازات الأقل
- قم بتشفير البيانات الحساسة
- تحقق من صحة المدخلات
- استخدم استعلامات معاملية (Parameterized Queries)
- قم بتحديث المكتبات والتبعيات

## الإبلاغ عن مشاكل غير أمنية

بالنسبة للمشكلات غير الأمنية، يرجى استخدام [نظام تتبع المشكلات](https://github.com/Abdellah252627/Sys-school/issues) الخاص بنا.

## الترخيص

بإرسال تقرير أمان، فإنك توافق على أن تقريرك يخضع لشروط [رخصة المشروع](LICENSE).
