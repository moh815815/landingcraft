# ⚡ LandingCraft — منشئ صفحات الهبوط

## الملفات والمجلدات

```
landingcraft/
├── index.html          # الصفحة الرئيسية
├── editor/
│   └── index.html      # محرر السحب والإفلات
├── admin/
│   └── index.html      # لوحة تحكم الأدمن
├── 404.html            # صفحة الخطأ
├── _redirects          # إعادة التوجيه (Cloudflare)
└── _headers            # ترويسات الأمان (Cloudflare)
```

## الرفع على Cloudflare Pages

### الطريقة الأولى: رفع مباشر (الأسرع)
1. افتح: https://pages.cloudflare.com
2. اضغط "Create a project" > "Direct Upload"
3. ارفع ملف ZIP هذا مباشرة
4. اضغط "Deploy site"

### الطريقة الثانية: عبر GitHub
1. ارفع الملفات على GitHub
2. ادخل Cloudflare Pages
3. اربط الـ Repository
4. اترك إعدادات البناء فارغة (Static site)
5. اضغط Deploy

## الاستخدام

- **الرئيسية**: `/`
- **المحرر**: `/editor/`
- **الأدمن**: `/admin/`

## المميزات
- ✅ سحب وإفلات حقيقي
- ✅ 20+ نوع عنصر
- ✅ 5 قوالب جاهزة
- ✅ معاينة على الموبايل/تابلت/ديسكتوب
- ✅ تصدير HTML نظيف
- ✅ لوحة أدمن كاملة
- ✅ حفظ في localStorage
- ✅ Undo/Redo (Ctrl+Z)
- ✅ اختصارات لوحة مفاتيح
