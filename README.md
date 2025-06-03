🚛 Yemen Fleet - نظام إدارة الشحن والخدمات اللوجستية
<p align="center"> <img src="images/yemen_fleet_logo.png" width="400" alt="Yemen Fleet Logo"> </p>
🌟 نظرة عامة على النظام
Yemen Fleet هو نظام متكامل لإدارة عمليات الشحن وتوصيل الطلبات، يتكون من:

1️⃣ لوحة تحكم الشركات (Laravel)
إدارة أساطيل الشاحنات والسائقين

متابعة الطلبات وتوزيعها على السائقين

إدارة المنتجات والعاملين

2️⃣ تطبيق العملاء (Flutter)
طلب المنتجات من التجار

تتبع الشحنات في الوقت الحقيقي

تقييم الخدمات والتجار

3️⃣ تطبيق السائقين (Flutter)
استقبال الطلبات المخصصة له

عرض مسارات التوصيل

تحديث حالات الشحن

4️⃣ لوحة تحكم الأدمن (Laravel)
إدارة اشتراكات الشركات

التحكم العام في النظام

إحصاءات وأداء النظام

📸 لقطات من النظام
<div align="center"> <h3>لوحة تحكم الشركة</h3> <img src="images/company_dashboard.png" width="800" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"> <table> <tr> <td><img src="images/customer_app.png" width="300" alt="تطبيق العملاء"></td> <td><img src="images/driver_app.png" width="300" alt="تطبيق السائقين"></td> </tr> <tr> <td align="center">تطبيق العملاء</td> <td align="center">تطبيق السائقين</td> </tr> </table> </div>
🔧 التقنيات المستخدمة
Diagram
Code






🚀 ميزات رئيسية
للشركات:
📊 لوحة تحكم شاملة للإدارة

🚛 إدارة أسطول الشاحنات

👥 إضافة وإدارة السائقين

📦 متابعة الطلبات في الوقت الفعلي

للعملاء:
🛒 طلب منتجات من متاجر متعددة

🗺️ تتبع موقع الشحنة

⭐ تقييم الخدمة والتجار

للسائقين:
📱 واجهة سهلة للطلبات

🗺️ خرائط التوصيل المباشرة

🔄 تحديث حالة التسليم

💻 كيفية التنصيب
bash
# استنساخ المشروع
git clone https://github.com/770883616/Yemen-Fleet-Dashboard.git
cd yemen-fleet

# تثبيت الاعتمادات
composer install
npm install
cp .env.example .env
php artisan key:generate

# تنفيذ الهجرة
php artisan migrate --seed
📞 التواصل والدعم
<p align="center"> <a href="mailto:support@yemenfleet.com"> <img src="https://img.shields.io/badge/Email-support%40yemenfleet.com-blue?style=for-the-badge&logo=gmail"> </a> <a href="tel:+967770883615"> <img src="https://img.shields.io/badge/Phone-%2B967770883615-green?style=for-the-badge&logo=whatsapp"> </a> </p><div align="center" style="margin-top: 40px;"> <sub>تم تطوير نظام Yemen Fleet بواسطة <a href="https://github.com/your-username" style="color: #2b7df8;">فريق التطوير</a> © 2024</sub> </div> ```