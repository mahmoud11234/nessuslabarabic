إنشاء مسح شبكة متقدم

    افتح المتصفح.

    اكتب عنوان الرابط: <https://localhost:8834/>

    إذا ظهرت الرسالة التالية، انقر على (خيارات متقدمة - Advanced) ثم (المتابعة إلى localhost - Proceed to localhost):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/c6745965f0524f0b77303b583e342e519dc33a78/1.png)

    أدخل اسم المستخدم وكلمة المرور (اسم المستخدم: admin كلمة المرور: Infosec4TC-2023):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/2.png)

    إذا ظهرت هذه النافذة، انقر على (إغلاق - Close):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/3.png)

    انقر على (إنشاء مسح جديد - Create a new scan):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/4.png)

    اختر (مسح متقدم - Advanced Scan):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/5.png)

    أدخل اسم المسح (Advanced Scan):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/6.png)

    أدخل في حقل (الأهداف - Targets) عنوان IP الخاص بالخادم. للحصول على عنوان IP، انقر على قائمة ابدأ (Start menu) واختر (تشغيل - Run):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/7.png)

    اكتب (cmd) ثم انقر موافق (OK):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/8.png)

    اكتب (ipconfig) ثم اضغط مفتاح Enter على لوحة المفاتيح:
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/9.png)

    افحص عنوان IP الظاهر على شاشتك وقم بإدخاله في حقل (الأهداف - Targets):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/10.png)

    على الجانب الأيسر، انقر على (اكتشاف - Discovery) ثم اختر (مسح المنافذ - Port Scanning) ثم استبدل (افتراضي - default) بـ (الكل - all):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/11.png)
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/12.png)

    انقر على علامة التبويب (بيانات الاعتماد - Credentials) أعلى الصفحة ثم انقر على (Windows):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/13.png)

    اكتب اسم المستخدم وكلمة المرور:

        اسم المستخدم: infosec

        كلمة المرور: Infosec4TC-2023

        ثم انقر على (حفظ - Save)

    ستنتقل إلى صفحة (مسوحاتي - My Scans) وسترى المسح الذي أنشأته. انقر على زر التشغيل (الرمز ▶) لبدء المسح:
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/14.png)

    سيبدأ المسح في العمل:
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/15.png)

    بمجرد انتهاء المسح، انقر عليه لرؤية النتائج:
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/16.png)

    انقر على علامة التبويب (الثغرات الأمنية - Vulnerabilities)، وسترى جميع الثغرات الأمنية التي تم اكتشافها على المضيف:
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/17.png)
