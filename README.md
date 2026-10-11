# العدوي شوب، عرض رحلة العميل على تطبيق الموبايل

<div dir="rtl">

## إيه ده؟
ده **التطبيق الحقيقي (Flutter) بحالته النهارده** · مش نموذج تخيّلي ولا ماكيت. الشاشات اللي جوه هي فعلًا شاشات التطبيق نفسه (٢٠ شاشة) موضوعة جوه إطارات موبايل، مجمّعة على ٧ مراحل من رحلة العميل، ومعاها جدول بيحصر **كل** شاشات التطبيق وحالتها.

آخر تحديث ضاف كمان: **شاشة الأونبوردينج** اللي بتشرح التطبيق أول تشغيل، و**بانر التحديث** و**شيت التحديث الإجباري**، و**كارت التقييم** اللي بيظهر بعد ما تبعث طلب.

## إيه اللي مش ده؟
ده **ديمو للعرض بس**: مفيش أي حاجة بتتبعت لأي سيرفر، مفيش دفع أونلاين، ومفيش تسجيل دخول حقيقي. كود الـ OTP ثابت، ورقم الطلب والـ PDF والمشاركة والمزامنة كلها محاكاة.

## إزاي تفتحه؟
دوس دبل كليك على ملف **`index.html`** · بيفتح في أي متصفح و**شغّال بدون إنترنت** (كل حاجة جواه: الصور، الخطوط، الشعارات). ملف واحد بس، يتنسخ أو يتبعت لوحده.

## لو فتحته من موبايل
أول ما تفتحه من موبايل هيطلعلك إشعار يشرحلك الاختيارين: تكمّل بعرض الموبايل (شاشات التطبيق واحدة ورا التانية بحجم كامل)، أو تشغّل **عرض سطح المكتب** بضغطة واحدة عشان تشوف اللوحة كلها زي الديسكتوب. وفي الحالتين تقدر تكبّر بإصبعين. ولو غيّرت رأيك، فيه زرار **«رجوع لعرض الموبايل»** ثابت تحت الشاشة.

## الموبايل التفاعلي (فوق خالص)
فوق في قسم **«تفاعلي · جرّب بنفسك»** فيه موبايل حقيقي **مش صورة** · دوس وجرّب: افتح منتج، زوّد للسلة، اتفرج على السلة والدفع، غيّر الأقسام.

## المفاتيح الثلاثة (في الشريط العلوي)
- **EN / ع**: تبديل اللغة عربي/إنجليزي.
- **شرح (Explain)**: يظهر/يخفي لوحات الشرح التوضيحية.
- **داكن / فاتح**: تبديل الوضع الليلي/النهاري.

## إزاي تقرا المفتاحين
**١) لوحة الشرح (فوق كل موبايل):**
- **منفَّذ**: الشاشة شغّالة فعلًا في التطبيق.
- **محاكى**: الواجهة موجودة بس النتيجة محاكاة في الديمو.
- **غير موجود**: الحاجة دي لسه مش في التطبيق.

**٢) شيب الحالة (جنب اسم كل شاشة):**
- **كاملة**: الشاشة مكتملة.
- **جزئية**: شغّالة بس فيها جزء ناقص أو للعرض فقط.
- **واجهة فقط**: الشكل موجود من غير وظيفة حقيقية.

## الـ ٧ مراحل
**الدخول · الاستكشاف · القرار · الطلب · التأكيد · المتابعة · الحساب**

## اللي معلّم صراحة إنه ناقص
الدفع أونلاين · كيان الأوردر المدفوع · المخزون/كمية المتاح · تسعير وموعد التوصيل المضمون · مكان بيانات الإيميل/النشاط/الملاحظات في السيرفر · حفظ خيارات المنتج في السلة · المفضلة.

> الجدول تحت («كل شاشات التطبيق وحالتها») وقسم «اللي لسه ناقص» هما المرجع الكامل لأي تفاصيل.

</div>

---

# AlAdawy Shop, Mobile Customer-Journey Presentation

## What this is
The **real Flutter app as it stands today**, not an imagined mockup. The screens are taken from the app itself (20 screens) shown inside phone frames, grouped into 7 journey stages, plus a table listing **every** app screen and its status.

The latest update also added: the **first-run onboarding**, the **update banner** and the **forced-update sheet**, and the **rating card** that appears after you send a request.

## What this is NOT
A **demo for viewing only**: nothing is sent anywhere, there is no online payment, and no real login. The OTP code is fixed, and the order number, PDF, share and sync indicator are all simulated.

## How to open it
Double-click **`index.html`**, it opens in any browser and **works offline** (images, fonts and brand marks are all inside the file). It is a single file: copy or send it on its own.

## If you open it on a phone
A notice explains the two options: keep the phone view (the app screens one after another at full size), or switch on **desktop view** with one tap to see the whole board the way it looks on a desktop. Either way you can pinch to zoom, and while desktop view is on a fixed **Back to phone view** button sits at the bottom.

## The live phone (top of the page)
Under **“LIVE · TRY IT YOURSELF”** there is a real phone, **not an image**. Tap and try: open a product, add to cart, view the cart and checkout, switch categories.

## The three toggles (top bar)
- **EN / ع**: switch Arabic / English.
- **شرح (Explain)**: show/hide the annotation plates.
- **داكن / فاتح (Dark / Light)**: switch night / day mode.

## How to read the two keys
**1) Annotation plates (above each phone):**
- **منفَّذ (Implemented)**: the screen genuinely works in the real app.
- **محاكى (Simulated)**: the UI exists but the result is simulated in the demo.
- **غير موجود (Missing)**: this capability is not in the app yet.

**2) Status chips (beside each screen name):**
- **كاملة (Full)**: the screen is fully complete.
- **جزئية (Partial)**: it works but part of it is missing or UI-only.
- **واجهة فقط (UI only)**: the look exists with no real behaviour.

## The 7 stages
**ENTRY · DISCOVERY · DECISION · ORDER · CONFIRMATION · FOLLOW-UP · ACCOUNT**

## What is deliberately marked as missing
Online payment · paid-order entity · inventory / stock quantity · guaranteed delivery pricing & slot · server payload home for email/business/notes · product-option selection persisting to the cart · favorites.

> The table below (“Every app screen and its status”) and the “What is still missing” section are the full source of truth for any detail.
