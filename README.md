# ultrasonic-task


هذه المهمة عبارة في الحقيقة عن مهمتين داخل مهمة واحدة 

في  البداية مع مهمة تركيب ستة محركات والتي تمثل ثلاث محركات لكل ذراع.

 حددت نقطة بدايتها جميها بزاوية صفر حيث افترضت ان الذراع سوف يكون مسبل الى الاسفل .

وبرمجت حركة الثلاث محركات لكل ذراع بحيث المحرك الاول السؤول عن منطقة الكتف سوف يرفع بزاوية 90 والمحرك الثاني يكون بزاوية 45 وتكون مضمومة الى الداخل والاخير في نهاية الذراع يكون بزاوية 30 وفي هذي الحالة تكون حركة الذراع كأنه يسوي حضن استقبالي للعميل.

هذا في الاعلى مايخص المهمة الاولى.
 
 المهمة الثانية كانت بربط حساس المسافة مع البلوتوث بحيث عند وجود شخص امام الحساس لمدة 3 ثواني يرسل اشارة بلوتوث ويشتغل مقطع فيديو وتتحرك الذراع .
 
 طيب في هذا المهمة استخدمت اثنين اردينو وواحد منهم كان يقوم بدور البلوتوث بسبب انه خاصية البلوتوث غير متوفرة في التنكركاد .
 ودمجت حركة الذراع المطلوبة في المهمة الاولى مع هذه المهمة واستبدلت  شاشة عرض الفيديو ب ال إي دي بحيث تنوب عن الشاشة .
 
 طيب بالنسبة للتوصيل  فهو بسيط زي ماهو موضح في الصورة  
 
 الشرح راح يكون لطريقة البرمجة وربط الاثنين اردوينو ببعضها وهكذا 
 
 طيب راح ابدأ ب اول اردينو واللي راح يكون مسؤول عن حساس المسافة فقط وقياس المسافة 
 حساس المسافة اول دبوس يكون للبور والاخير قراوند والاثنين اللي في النص واحد مستقبل والثاني مرسل 
 
 كتبت كود بسيط لحساب المسافة وحددت 40 سم كمسافة افتراضية 
 اذا حس الحساس بأن المسافة اكبر من 40سم ماراح يحصل شى 
 بس اذا كان المسافة اقل راح يدخل للامر اللي تحته ويحسب الزمن ,اذا استمر الجسم امامه لمدة 3 ثواني راح يرسل اشارة للاردينو الثاني 
 
 الاردينو الثاني راح يستقبل اشارة بأن ينفذ الاوامر الموجودة عنده لمسافة اقل من 
 40 سم 
 
 ويقوم بتحريك الذراع وتشغيل ال اي دي 
 الين تجيه اشارة ثانية بان المسافة صارت اكبر او الجسم غادر المنطقة في راح يعطي امر انو كل شى يرجع للحالة الطبيعية حالة ايقاف التشغيل 
 
 
