## ملصق روبوت رائع 

يمكنك استخدام صورة لإنشاء ملصق متدرج. وإذا كان بإمكانك استخدام صورة ذات خلفية شفافة، فسيكون التدرج واضحًا. 

كما يمكنك إنشاء تدرجات لتشغيلها في اتجاهات مختلفة. 

+ أضف ملصقًا إلى الملف `index.html` مستخدمًا الصورة `firerobot.png`:

	![screenshot](images/stickers-fire-html.png)

	يمكنك تعديل قيمة `height` لتغيير حجم الصورة، وستتغير قيمة `width` تلقائيًا. 

+ يتم تشغيل التدرج من أعلى إلى أسفل عادةً، لكن يمكن استخدام `to` لتغيير الاتجاه. على سبيل المثال: `to top` أو `to left` أو `to right`.

	يعمل التدرج القطري في اتجاهين. ويستخدم هذا المثالُ الاتجاهَ `to bottom left`.

	أضف هذا النمط إلى الملف `style.css` لتعطي ملصق الروبوت الجديد تدرجًا قطريًا وحدًا رائعًا:

	![screenshot](images/stickers-fire-gradient.png)

	لاحظ أنه يمكنك استخدام الخاصية `outline` لإنشاء إطار آخر خارج الحد المعتاد. 
	أما الخاصية `outline-offset` فتعطيك هذا التباعد بين الحد والإطار. 

+ لنضِف نصًا إلى هذا الملصق. 

	أضف وسم `<span>` يتضمن النص "ROBOTS" إلى الملف `index.html` وحدِّد له معرِّفًا. 

	![screenshot](images/stickers-fire-span.png)

+ سيظهر النص بشكل أفضل إذا قمت بتكبيره وتحديد موضع له. 

	لتحديد موضع النص، ستحتاج إلى إضافة `position: relative;` إلى `greensticker#` و`position: absolute` إلى `greentext#`. وقد تم تناول خاصية الموضع بمزيد من التفصيل في المشروع `صمِّم روبوتًا`. 

	أضف التعليمات البرمجية التالية إلى الملف `style.css`:

	![screenshot](images/stickers-fire-text-style.png)

+ ولإضافة الالتفاف كخطوة أخيرة، لنقم بتدوير النص باستخدام `transform: rotate`.

	![screenshot](images/stickers-fire-rotate.png)

	جرِّب تغيير عدد درجات التفاف النص. 



