# AI Company Profile Studio

واجهة عربية RTL تعمل في المتصفح باستخدام HTML5 وCSS3 وJavaScript.

## التشغيل
افتح index.html في متصفح حديث واتصل بالإنترنت لتحميل المكتبات من CDN. إذا واجهت قيوداً في فتح الملفات محلياً، استخدم Live Server في Visual Studio Code.

## النشر على Vercel
استورد المستودع في Vercel باعتباره Static Site. لا يتطلب Build Command، ومجلد الإخراج هو جذر المستودع.

## الأمان
حقل OpenAI API في الواجهة للتجربة فقط؛ لا تضع مفتاح إنتاجي في تطبيق عام. استخدم Vercel Function وخزّن المفتاح في Environment Variables قبل إتاحة الذكاء الاصطناعي للجمهور.

## ملاحظات
- PDF.js يستخرج النصوص من PDF؛ لا يستخرج التطبيق الصور المضمّنة داخل ملفات PDF تلقائياً.
- Mammoth.js يستخرج النصوص من DOCX وSheetJS يقرأ ملفات Excel.
- الوضع المحلي ينشئ مسودة أولية وليس نموذج ذكاء اصطناعي كاملاً.
- راجع ملف PPTX في PowerPoint، خاصة اتجاه النص العربي وتوفر خط Sakkal Majalla.
