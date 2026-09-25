# الرزاق | ALRAZZAQ — Android APK project

تم تحويل نسخة الـPWA المرفوعة إلى مشروع Android WebView مستقل، مع:
- اسم التطبيق: الرزاق
- أيقونة الرزاق
- شاشة عمودية مناسبة للموبايل
- 4 اختصارات Android: وقت الرغبة، القرآن، الأذكار، الصلاة
- كل اختصار يفتح القسم مباشرة
- دعم WhatsApp من داخل التطبيق
- JavaScript + LocalStorage + اتصال الإنترنت لخدمات القرآن والمواقيت
- طلب إذن إشعارات Android 13+

## البناء
افتح هذا المجلد في Android Studio ثم Build > Build APK(s).
أو بعد تثبيت Android SDK وGradle:

```bash
gradle :app:assembleDebug
```

الـAPK الناتج:
`app/build/outputs/apk/debug/app-debug.apk`

ملاحظة: بيئة التنفيذ الحالية لا تحتوي Android SDK/Gradle، لذلك تم تجهيز مشروع APK كامل بدل الادعاء بإخراج APK غير مبني.
