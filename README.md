#  Angular Housing App (โปรเจคเรียนรู้ Angular)

##  เกี่ยวกับโปรเจคนี้

โปรเจคนี้เป็นการเรียนรู้ **Angular** ด้วยตนเอง โดยทำตาม [Angular Tutorials](https://angular.dev/tutorials/first-app) และดูคลิปสอนใน **YouTube**
เป็นแอปพลิเคชันแสดงรายการที่พัก สามารถ **ค้นหาตามชื่อเมือง** และกดดู **รายละเอียดที่พัก** ได้

---

## ✨ ฟีเจอร์ของแอป

* ✅ แสดงรายการที่พักพร้อมรูปภาพ
* ✅ กดดูรายละเอียดของแต่ละที่พัก
* ✅ กรอกข้อมูลสมัครเข้าพัก
* * ❌ ค้นหาที่พักตามชื่อเมือง (ยังไม่เสร็จ)


---

##  วิธีสร้างและรันโปรเจค Angular

###  1. ติดตั้ง Angular CLI (ถ้ายังไม่มี)

```bash
npm install -g @angular/cli
2. สร้างโปรเจค Angular ใหม่
Bash

ng new homes-app
จากนั้นเลือก CSS เป็นตัวเลือกสำหรับสไตล์

หมายเหตุ: โฟลเดอร์ homes-app จะถูกสร้างขึ้นพร้อมโครงสร้างของโปรเจค Angular

3. เข้าไปที่โฟลเดอร์โปรเจค
Bash

cd homes-app
4. ติดตั้ง Dependency
Bash

npm install
5. เริ่มต้น JSON Server สำหรับ API Mock Data
** โค้ดนี้สำคัญมากเพื่อให้การค้นหาข้อมูลทำงาน**

Bash

json-server --watch db.json --port 3000
จากนั้นสามารถเข้าถึง API ได้ที่:

Bash

http://localhost:3000/locations
6. รันโปรเจค Angular
Bash

ng serve
แล้วเปิดเบราว์เซอร์ที่:

http://localhost:4200
เทคโนโลยีที่ใช้
Angular - เฟรมเวิร์กสำหรับ Front-End
TypeScript - ภาษาสำหรับพัฒนา Angular
Bootstrap - ใช้สำหรับจัดรูปแบบ UI
JSON Server - จำลอง API สำหรับข้อมูลที่พัก
ตัวอย่างหน้าจอ
หน้าแรกของแอป
[ใส่รูปภาพหน้าแรกของแอป]

หน้ารายละเอียดที่พัก
[ใส่รูปภาพหน้ารายละเอียดที่พัก]

การอัปเดตโค้ดและอัปโหลดไป GitHub
ทุกครั้งที่มีการแก้ไขโค้ด สามารถอัปโหลดขึ้น GitHub ด้วยคำสั่งนี้:

Bash

git add .
git commit -m "อัปเดตโค้ดและแก้ไข UI"
git push origin main
