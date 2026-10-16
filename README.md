# محاكي الخرائط الكونتورية — تطبيق أندرويد

تطبيق WebView يحمّل `app/src/main/assets/index.html` من عنوان https داخلي (`appassets.androidplatform.net`)
فيعمل الـ GPS وبقية واجهات المتصفح الآمنة. يحتاج إنترنت (صور الأقمار الصناعية وبيانات الارتفاع وThree.js).

- أندرويد 10 فأعلى. الصور المحفوظة تذهب إلى `Download/ContourSimulator`.
- للتحديث: استبدل `app/src/main/assets/index.html` ثم `git push`، وسيبني GitHub Actions ملف APK جديدًا.
- النتيجة: Actions ← آخر تشغيل ← Artifacts ← `ContourSimulator-apk`. ولإصدار دائم: `git tag v1.0 && git push --tags`.
