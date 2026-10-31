# PiSLA — نسخة Windows

## البناء على GitHub
1. أنشئ مستودعًا جديدًا وارفع محتويات هذا المجلد كما هي (مع المجلد المخفي `.github`).
2. بعد الدفع إلى فرع `main` يبدأ البناء تلقائيًا (تبويب **Actions**).
3. حمّل الملفات من **Artifacts → PiSLA-windows**:
   - `PiSLA-Setup-<الإصدار>.exe` مثبّت.
   - `PiSLA-Portable-<الإصدار>.exe` يعمل دون تثبيت.
4. للنشر في **Releases**: `git tag v1.8.4 && git push origin v1.8.4`.

## التجربة محليًا
`npm install` ثم `npm start`، وللبناء `npm run dist`.

لتحديث التطبيق استبدل `app/index.html` وارفع التغيير.
