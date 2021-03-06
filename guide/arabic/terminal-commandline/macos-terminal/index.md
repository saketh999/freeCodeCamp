---
title: Mac OS Terminal
localeTitle: Mac OS Terminal
---
# باستخدام المحطة الطرفية في نظام التشغيل Mac OS

معظم الوقت يتفاعل المستخدمون من خلال واجهة المستخدم الرسومية للتفاعل مع الكمبيوتر. يمكنك استخدام الماوس للإشارة والنقر لفتح أو نقل أو إنشاء ملفات جديدة أو فتح التطبيقات. ولكن ، يمكنك أيضًا استخدام التطبيق الطرفي للتفاعل مع جهازك من خلال الأوامر المكتوبة. عندما تستخدم الجهاز ، فإنه يسمح لك بحفر أعمق وتخصيصه بطريقة غير ممكنة من خلال واجهة المستخدم الرسومية.

### فتح المحطة والملاحة الدلائل

المحطة الطرفية الخاصة بك موجودة في دليل التطبيقات. افتح تطبيقك في المحطة. يجب أن تشاهد موجه في نافذة المحطة. يكون shoudl له اسم الكمبيوتر (ABC's Macbook) ، يتبعه اسم المستخدم (ABC) ، ثم "$." إذا كنت في الدليل الجذر ، فسيكون الحرف الأخير هو "#."

لمعرفة ما الدليل الذي تعمل فيه ، ما عليك سوى كتابة الأمر

`pwd`

pwd لتقف على "طباعة دليل العمل". الدليل هو كلمة أخرى للمجلد.

إذا كنت تريد إدراج محتويات دليلك ، استخدم الأمر:

`ls`

للتبديل إلى دليل جديد ، يمكنك استخدام الأمر:

`cd`

والتي تقف على تغيير الدليل.

وهنا لائحة من الأوامر المشتركة:

القيادة | استعمال ------------ | ------------- pwd | طباعة دليل العمل (أين أنا؟) ls | قائمة محتويات الدليل الحالي mkdir | قم بإنشاء دليل جديد المس | قم بإنشاء ملف جديد حزب المحافظين | انسخ الملف جمهورية مقدونيا قم بإزالة ملف rm -rf | قم بإزالة دليل

### أمثلة الاستخدام

بعض الأوامر المذكورة أعلاه ليست واضحة دون أمثلة. فيما يلي بعض أمثلة الاستخدام للمساعدة في تزويدك ببعض السياق.

#### صنع دليل

`mkdir #YOUR-NEW-FOLDER-NAME-HERE`

#### صنع ملف

`touch YOUR-FILE-NAME.JS`

يمكنك إنشاء ملف بأي ملحق تختاره. طالما أنه في صيغة مقبولة من قبل المجلد أو الجهاز.

#### نسخ ملف

استخدم بناء الجملة التالي لنسخ ملف من الجهاز:

**_وجهة_ _مصدر_ cp**

على سبيل المثال ، إذا كان لدينا ملف ، _"test.txt"_ تم تخزينه في دليل _/ سطح المكتب الخاص_ بنا ونريد نسخه إلى المجلد _/ Documents_ ، فسيبدو أمرنا كما يلي:

 `cp ~/Desktop/test.txt ~/Documents 
` 

#### حذف ملف

استخدم بناء الجملة التالي لحذف ملف

**RM _\# PATH_ إلى _ملف_**