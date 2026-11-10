DOM Selectors :
هي الطريقه الي بنستخدمه في js علشان نختار عناصر HTML ونتعامل معها 


removeAttribute :
دي Method بنستخدمها علشان نحذف Attribute من عنصر HTML.


NodeList vs HTML Collection :
لما بتتعامل مع js وبتختار عناصر من HTML، ساعات بترجعلك مجموعة عناصر بدل عنصر واحد.
 
 1-HTMLCollection : 
 بتتحدث تلقائياً لما عناصر HTML تتضاف أو تتحذف من الصفحة
بتحتوي على عناصر HTML فقط
تقدر تستخدم of و for للتكرار
مش بتدعم forEach() مباشرة

2-NodeList :
querySelectorAll() بترجع مجموعة ثابتة، مش بتتحدث تلقائياً
ممكن تحتوي على أنواع مختلفة من Nodes حسب طريقة الحصول عليها
بتدعم forEach() في NodeList العادية
تقدر تستخدم for و of