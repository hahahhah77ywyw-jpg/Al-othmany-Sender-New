# مشروع Al-othmany Sender Android

هذا مشروع Android Studio كامل لتطبيق Al-othmany Sender، مبني على الواجهة والمنطق الموجودين في الملفات المرفوعة.

## البناء
- افتح المجلد في Android Studio.
- انتظر مزامنة Gradle.
- Build > Build APK(s).

## بدون Android Studio
يوجد Workflow جاهز داخل `.github/workflows/build-apk.yml` لبناء APK عبر GitHub Actions.

## التشغيل على الهاتف
1. ثبّت APK.
2. افتح التطبيق.
3. اختر WhatsApp أو WhatsApp Business أو أي حزمة مدعومة مثبتة.
4. فعّل خدمة Accessibility للتطبيق من إعدادات إمكانية الوصول.
5. أضف روابط الدعوة.
6. اختياريًا فعّل النشر واكتب الرسالة.
7. ابدأ التشغيل.

## ملاحظة
التحكم في WhatsApp يتم عبر Accessibility وعناصر الواجهة، لذلك قد يحتاج محددات النص/العناصر إلى تحديث إذا غيّر WhatsApp واجهته.
