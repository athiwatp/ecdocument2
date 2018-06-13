# ecdocument2
electronic document

ระบบเอกสารที่ผมได้ทำขึ้นมาใช้เครื่องมือในการพัฒนาคือ VSCODE และ Framework ของ ภาษา PHP คือ Laravel 5.6 ส่วน CSS ใช้ Framework Bootstrap 4.1 ในการพัฒนาเช่นกัน ซึ่งไว้ว่าการแจกจ่าย Source code จะเป็นตัวอย่าง code ให้กับผู้ที่สนใจศึกษา Laravel เหมือนผมเช่นกัน และระบบที่ผมนำมาแจกนั้นใช้ Template จาก PikeAdmin ซึ่งมีการใช้ bootstrap 4 ในการทำ Template และในสุดท้ายนี้หากใครมีปัญหาการติดตั้ง สามารถแสดงความเห็นไว้ด้านล่างนี้นะครับ

ระบบเอกสารมีตาราง 3 ตารางได้แก่ ตาราง users, categories, documents

# ความสามารถของโปรแกรม
1. สามารถกำหนดสิทธิ์การเข้าถึงตามผู้ใช้และผู้ดูแลได้ โดยผู้ใช้สามารถอ่านเอกสารได้อย่างเดียว
2. เอกสารสามารถอัพโหลดไฟล์ได้เฉพาะนามสกุล PDF และป้องกันไม่ให้อัพโหลดนามสกุลอื่น
3. มีหมวดหมู่เพื่อจำแนกประเภทเอกสารได้
4. มีระบบตรวจสอบสิทธิ์การเข้าถึง โดยต้องระบบทุกครั้งที่ใช้งาน

# ความต้องการของโปรแกรม
1. PHP version 7.1.3 หรือมากกว่า
2. ฐานข้อมูล maria DB

# ทดสอบการใช้งาน
username : tawatsak

password : 123456

# การติดตั้ง
1. ดาวน์โหลด Project มาแล้ว เปิด Command line เข้าไปโฟล์เดอร์ Project
2. พิมพ์ composer install
3. พิมพ์ php artisan key:generate
4. สร้างฐานข้อมูล และ ตั้งค่าข้อมูลในไฟล์ .env
5. พิมพ์ php artisan migrate
6. พิมพ์ npm install
7. พิมพ์ npm run dev
8. พิมพ์ php artisan serve
9. เข้าเว็บ http://127.0.0.1:8000
10. ตั้งค่ากำหนดสิทธิ์อัพโหลดไฟล์ที่โฟล์เดอร์ storage ให้ทุกคนสามารถอัพโหลดได้ (CHMOD 777)

# Special Thanks
ขอขอบคุณทุกๆท่านที่ทำให้นักพัฒนามีแรงบรรดาลใจในการพัฒนาต่อไปโดยการ บอกต่อ(Share)

ธวัชศักดิ์ แตงเอี่ยม


ขอบคุณครับ
