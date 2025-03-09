# 🏠 Angular Housing App (โปรเจคเรียนรู้ Angular)

## 🔹 เกี่ยวกับโปรเจคนี้
โปรเจคนี้เป็นการเรียนรู้ **Angular** ด้วยตนเอง โดยทำตาม [Angular Tutorials](https://angular.dev/tutorials/first-app) และดูคลิปสอนใน **YouTube**  
เป็นแอปพลิเคชันแสดงรายการที่พัก สามารถ **ค้นหาตามชื่อเมือง** และกดดู **รายละเอียดที่พัก** ได้  

---

## ✨ ฟีเจอร์ของแอป
✅ แสดงรายการที่พักพร้อมรูปภาพ  
✅ **ค้นหาที่พักตามชื่อเมือง**  
✅ กดดูรายละเอียดของแต่ละที่พัก  
✅ กรอกข้อมูลสมัครเข้าพัก  

---

## 🚀 วิธีสร้างและรันโปรเจค Angular

### 🔹 1. ติดตั้ง Angular CLI (ถ้ายังไม่มี)
```bash
npm install -g @angular/cli
🔹 2. สร้างโปรเจค Angular ใหม่
ng new homes-app
```
```bash
🔹 3. เข้าไปที่โฟลเดอร์โปรเจค
cd homes-app
```
🔹 4. ติดตั้ง Dependency
bash
คัดลอก
แก้ไข
npm install
🔹 5. เริ่มต้น JSON Server สำหรับ API Mock Data
📌 โค้ดนี้สำคัญมากเพื่อให้การค้นหาข้อมูลทำงาน

bash
คัดลอก
แก้ไข
json-server --watch db.json --port 3000
จากนั้นสามารถเข้าถึง API ได้ที่:

bash
คัดลอก
แก้ไข
http://localhost:3000/locations
🔹 6. รันโปรเจค Angular
bash
คัดลอก
แก้ไข
ng serve
แล้วเปิดเบราว์เซอร์ที่:

arduino
คัดลอก
แก้ไข
http://localhost:4200
📜 เทคโนโลยีที่ใช้
Angular - เฟรมเวิร์กสำหรับ Front-End
TypeScript - ภาษาสำหรับพัฒนา Angular
Bootstrap - ใช้สำหรับจัดรูปแบบ UI
JSON Server - จำลอง API สำหรับข้อมูลที่พัก
📸 ตัวอย่างหน้าจอ
🎨 หน้าแรกของแอป

🏡 หน้ารายละเอียดที่พัก

🔄 การอัปเดตโค้ดและอัปโหลดไป GitHub
ทุกครั้งที่มีการแก้ไขโค้ด สามารถอัปโหลดขึ้น GitHub ด้วยคำสั่งนี้:

bash
คัดลอก
แก้ไข
git add .
git commit -m "อัปเดตโค้ดและแก้ไข UI"
git push origin main
