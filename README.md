# university-code-site
Learn and differentiate between programming languages
# university-code-site
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كود الجامعة 💻</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>كود الجامعة 👩‍💻</h1>
        <p>بوابتك لاكتشاف لغات البرمجة واختيار تخصصك بثقة.</p>
    </header>

    <main>
        <section class="comparison-tool">
            <h2>⚖️ أداة المقارنة التفاعلية</h2>
            <p>اختاري لغتين لتعرض لكِ أهم الفروقات والاستخدامات.</p>
            <select id="lang1">
                <option value="">اختر اللغة الأولى</option>
                <option value="Python">بايثون (Python)</option>
                <option value="JavaScript">جافاسكريبت (JavaScript)</option>
            </select>
            <span style="margin: 0 10px; font-weight: bold;">مقابل</span>
            <select id="lang2">
                <option value="">اختر اللغة الثانية</option>
                <option value="Python">بايثون (Python)</option>
                <option value="JavaScript">جافاسكريبت (JavaScript)</option>
            </select>
            <button onclick="compareLanguages()">قارن الآن</button>
            <div id="comparison-result"></div>
        </section>

        <hr>

        <section class="courses">
            <h2>📚 دورة: مدخل إلى بايثون - الدرس الأول (المتغيرات)</h2>
            <div class="lesson-card">
                <h3>💡 المفهوم: ما هي المتغيرات (Variables)؟</h3>
                <p>المتغيرات هي صناديق نستخدمها لتخزين البيانات داخل برنامجنا.</p>
                <div class="analogy">تشبيه: المتغير مثل علبة مكتوب عليها اسم وبداخلها قيمة.</div>
                <h3>✍️ مثال عملي</h3>
                <div class="code-block">
                    <pre>
# تعريف متغير رقمي
age = 25
# تعريف متغير نصي
name = "Sara"
# طباعة
print(name)
print(age)
                    </pre>
                </div>
            </div>
        </section>

        <hr>

        <section class="paths">
            <h2>🧭 مسارات التخصص</h2>
            <ul>
                <li>علم البيانات: Python</li>
                <li>تطوير الويب: JavaScript</li>
                <li>تطبيقات المؤسسات: Java, C#</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 كود الجامعة.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
