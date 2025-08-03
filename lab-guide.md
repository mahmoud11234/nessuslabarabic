# إنشاء مسح شبكة متقدم

1. افتح المتصفح.

1. اكتب عنوان الرابط: <https://localhost:8834/>

1. إذا ظهرت الرسالة التالية، انقر على (خيارات متقدمة - Advanced) ثم (المتابعة إلى localhost - Proceed to localhost): 
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/c6745965f0524f0b77303b583e342e519dc33a78/1.png)

1. أدخل اسم المستخدم وكلمة المرور (اسم المستخدم: admin كلمة المرور: Infosec4TC-2023):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/2.png)

1. إذا ظهرت هذه النافذة، انقر على (إغلاق - Close):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/3.png)

1. انقر على (إنشاء مسح جديد - Create a new scan):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/4.png)

1. اختر (مسح متقدم - Advanced Scan):
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/5.png)

1. أدخل اسم المسح (Advanced Scan):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/6.png)

1. أدخل في حقل (الأهداف - Targets) عنوان IP الخاص بالخادم. للحصول على عنوان IP، انقر على قائمة ابدأ (Start menu) واختر (تشغيل - Run):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/7.png)

1. اكتب (cmd) ثم انقر موافق (OK):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/8.png)

1. اكتب (ipconfig) ثم اضغط مفتاح Enter على لوحة المفاتيح:
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/9.png)

1. افحص عنوان IP الظاهر على شاشتك وقم بإدخاله في حقل (الأهداف - Targets):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/10.png)

1. على الجانب الأيسر، انقر على (اكتشاف - Discovery) ثم اختر (مسح المنافذ - Port Scanning) ثم استبدل (افتراضي - default) بـ (الكل - all):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/11.png)
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/12.png)

 1. انقر على علامة التبويب (بيانات الاعتماد - Credentials) أعلى الصفحة ثم انقر على (Windows):
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/13.png)

1. اكتب اسم المستخدم وكلمة المرور:

    اسم المستخدم: infosec
    كلمة المرور: Infosec4TC-2023
    ثم انقر على (حفظ - Save)

1. ستنتقل إلى صفحة (مسوحاتي - My Scans) وسترى المسح الذي أنشأته. انقر على زر التشغيل (الرمز ▶) لبدء المسح:
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/14.png)

1. سيبدأ المسح في العمل:
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/15.png)

1. بمجرد انتهاء المسح، انقر عليه لرؤية النتائج:
    
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/16.png)

 1. انقر على علامة التبويب (الثغرات الأمنية - Vulnerabilities)، وسترى جميع الثغرات الأمنية التي تم اكتشافها على المضيف:
    ![alt text](https://raw.githubusercontent.com/mahmoud11234/nessuslabarabic/refs/heads/main/17.png)
