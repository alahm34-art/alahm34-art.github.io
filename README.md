# Ahmed AL-Zahrani — Portfolio / موقع السيرة الذاتية

سيرة ذاتية تفاعلية **ثنائية اللغة** (عربي/إنجليزي بزر تبديل) + صفحات المشاريع والمبادرات.
A **bilingual** interactive CV (Arabic/English toggle) with project and initiative pages.

## ⚠️ مهم جداً عند الرفع على GitHub

ارفع **محتويات** هذا المجلد، **لا المجلد نفسه**.

بعد الرفع يجب أن ترى `index.html` مباشرة في الصفحة الرئيسية للمستودع — وليس مجلداً باسم `site`.
إذا رأيت مجلداً، فالرفع خاطئ: ادخله، وانقل الملفات للأعلى.

## بنية الملفات

```
index.html                    ← الصفحة الرئيسية (ابدأ من هنا)
README.md
projects/
  ids-survey.html                 أساسيات الأمن السيبراني
  rootkit-detection.html          أمن أنظمة التشغيل
  whatsapp-crypto.html            التشفير
  network-security.html           أمن الشبكات
  tsp-algorithms.html             الخوارزميات المتقدمة
  research-methods.html           منهجيات البحث
  operational-planning-app.html
  school-plans-app.html
initiatives/
  tamkeen.html                    مبادرة تمكين
  rased.html                      مبادرة مِرصاد
  itqan.html                      مبادرة إتقان
files/
  CV_Ahmed_AR.pdf / .docx         السيرة عربي (PDF + Word للتعديل)
  CV_Ahmed_EN.pdf / .docx         السيرة إنجليزي (PDF + Word للتعديل)
  IDS_Survey.pdf
  WhatsApp_Crypto_Analysis.pdf
  TSP_Project.pdf
  Network_Security_Presentation.pdf
  OS_Security_Report.pdf
```

**كل صفحة مستقلة بذاتها** — التنسيق مدمج بداخلها، فلا يوجد ملف CSS خارجي يمكن أن ينكسر.

## كيف أعدّل؟

- **النصوص:** افتح أي ملف HTML بـ VS Code أو Notepad.
  - النص العربي داخل `<span data-lang="ar">...</span>` أو `<div data-lang="ar">`
  - النص الإنجليزي داخل `<span data-lang="en">...</span>` أو `<div data-lang="en">`
  - عدّل الاثنين معاً حتى تتطابق اللغتان.
- **الألوان:** في أعلى كل ملف داخل `<style>` تحت `:root`.
- **السيرة الذاتية (Word):** `files/CV_Ahmed_AR.docx` و `files/CV_Ahmed_EN.docx` — افتحها بـ Word وعدّل مباشرة.

## النشر على GitHub Pages

1. أنشئ مستودعاً باسم `USERNAME.github.io` (استبدل USERNAME باسم حسابك) — **Public**.
2. `Add file` ← `Upload files` ← اسحب **محتويات** هذا المجلد (بما فيها مجلدات projects و initiatives و files).
3. اضغط `Commit changes`.
4. `Settings` ← `Pages` ← Branch: `main` ← `Save`.
5. انتظر ١–٢ دقيقة. الرابط: `https://USERNAME.github.io`

### إذا لم يعمل الموقع
- تأكد أن `index.html` في **جذر** المستودع (وليس داخل مجلد).
- تأكد أن المستودع **Public** لا Private.
- تأكد أن اسم المستودع بالضبط `USERNAME.github.io`.
- انتظر دقيقتين وحدّث الصفحة (Ctrl+Shift+R).

---
© 2026 Ahmed Atiyah Hassan AL-Zahrani
