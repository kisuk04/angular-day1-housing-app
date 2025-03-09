# 🏠 Angular Housing App (โปรเจคเรียนรู้ Angular)

## 📌 เกี่ยวกับโปรเจคนี้
โปรเจคนี้เป็นการเรียนรู้ **Angular** ด้วยตนเอง โดยทำตาม [Angular Tutorials](https://angular.dev/tutorials/first-app) และดูคลิปสอนใน **YouTube**  
เป็นแอปพลิเคชันแสดงรายการที่พัก สามารถ **ค้นหาตามชื่อเมือง** และกดดู **รายละเอียดที่พัก** ได้  

---

## ✨ ฟีเจอร์ของแอป
✅ **แสดงรายการที่พัก** พร้อมรูปภาพ  
✅ **กดดูรายละเอียด** ของแต่ละที่พัก  
✅ **กรอกข้อมูล** สมัครเข้าพัก  
❌ **ค้นหาที่พักตามชื่อเมือง** *(ยังไม่เสร็จ - อยู่ระหว่างพัฒนา! 🚧)*  

---

## 🚀 วิธีติดตั้งและรันโปรเจค

### 🔹 1. ติดตั้ง Angular CLI (ถ้ายังไม่มี)
```bash
npm install -g @angular/cli
```
###🔹2. Clone โปรเจคนี้จาก GitHub
```bash
git clone https://github.com/kisuk04/angular-day1-housing-app.git
```
###🔹3. ติดตั้ง Dependencies
```bash
npm install
```
###🔹4. เริ่มต้น JSON Server สำหรับ API Mock Data 
```bash
json-server --watch db.json --port 3000
```
📌 หลังจากรันคำสั่งนี้ สามารถเข้าถึง API ได้ที่
👉 http://localhost:3000/locations
###🔹 5. รันโปรเจค Angular
```bash
ng serve
```
📌 จากนั้นเปิดเว็บเบราว์เซอร์ที่
👉 http://localhost:4200
📸 ตัวอย่างหน้าจอ
🎨 หน้าแรกของแอป
![image](https://github.com/user-attachments/assets/733e6605-69df-4aad-ad2b-eeca6c970990)

🏡 หน้ารายละเอียดที่พัก
![image](https://github.com/user-attachments/assets/cdb27873-8a17-4eae-ae67-11560f74f889)
