# Islem 2 – قائمة الطعام

موقع ثابت (HTML) لا يحتاج أي خادم أو قاعدة بيانات.

## الملفات
- index.html : الصفحة كاملة
- images/ : صور الأطباق
- .nojekyll : يجعل GitHub Pages يعرض الملفات كما هي

## النشر على GitHub Pages
1. أنشئ مستودعًا جديدًا Public على github.com
2. ارفع كل محتويات هذا المجلد (index.html و images و .nojekyll) إلى جذر المستودع
3. Settings > Pages > Source: Deploy from a branch > main > / (root) > Save

## التعديل
- الأسعار والأطباق والأسماء: داخل index.html في كتلة JSON داخل <script type="application/json" id="data">
- استبدال صورة: ضع الصورة الجديدة في images/ وغيّر اسمها في حقل "img"
