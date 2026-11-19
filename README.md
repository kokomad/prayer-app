# 🕌 مواقيت — Prayer Times & Weather

مواقيت الصلاة (حساب فلكي محلي) + الطقس + شريط ملاحظات متحرك + منبّه صوتي.

## النشر كتطبيق ويب (PWA) عبر GitHub Pages
1. أنشئ مستودعًا جديدًا وارفع كل الملفات إلى فرع `main`.
2. Settings ← Pages ← Source: **GitHub Actions**.
3. بعد دقائق يعمل الرابط `https://USERNAME.github.io/REPO/`. افتحه من الجوال ثم «إضافة إلى الشاشة الرئيسية».

## بناء APK لأندرويد
Actions ← **Build Android APK** ← Run workflow (أو أنشئ وسم `git tag v1.0.0 && git push --tags` ليُرفق الـ APK في Releases).

## التطوير القادم
ودجت أندرويد أصلي + إشعارات خلفية: `@capacitor/local-notifications` ثم AppWidgetProvider بلغة Kotlin.
