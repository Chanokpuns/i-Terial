# i-Terial

เป็นเว็บไซต์จัดการคอร์สเรียนที่พัฒนาเป็นโปรเจกต์ในรายวิชา Fundamental Webprogramming จัดทำขึ้นเพื่อเป็นส่วนหนึ่งของการเรียนในรายวิชา Fundamental Webprogramming
โดยมีเป้าหมายเพื่อฝึกการพัฒนา Web Application แบบ Full Stack
ตั้งแต่การออกแบบหน้าเว็บไซต์ การพัฒนา Backend
การจัดการฐานข้อมูล และการเชื่อมต่อระหว่าง Frontend และ Backend

## รายละเอียดเกี่ยวกับโปรเจกต์

i-Terial เป็นเว็บไซต์ที่พัฒนาขึ้นเพื่อรวบรวมเกี่ยวกับคอร์สเรียน เนื้อหาในการสอบเข้าคณะเทคโนโลยีสารสนเทศ โดยจะแบ่งเป็น TPAT3,TGAT,A-level
ซึ่งช่วยให้ผู้ใช้งานสามารถเข้าถึงข้อมูลและจัดการข้อมูลผ่านเว็บไซต์ได้สะดวกมากขึ้น โดยไม่เสียค่าใช้จ่าย

โปรเจกต์นี้พัฒนาด้วย Node.js และ Express.js โดยใช้ EJS
สำหรับสร้างหน้าเว็บไซต์แบบ Dynamic และเชื่อมต่อกับฐานข้อมูล

## ฟีเจอร์หลัก

- แสดงข้อมูลคอร์สเรียน
- เข้าสู่ระบบเพื่อลงทะเบียนเรียน
- เพิ่มและจัดการข้อมูลภายในรายวิชา
- อัปโหลดไฟล์/วิดีโอ
- เชื่อมต่อฐานข้อมูล
- ระบบ Session สำหรับจัดการผู้ใช้งาน
- แสดงข้อมูลแบบ Dynamic ด้วย EJS

## เทคโนโลยีที่ใช้

### Frontend
- HTML
- CSS
- JavaScript
- EJS

### Backend
- Node.js
- Express.js

### Database
- MySQL
- SQLite

### Other
- Express Session
- Git / GitHub

## โครงสร้างโปรเจกต์

```text
i-Terial/
├── public/
├── views/
├── index.js
├── package.json
├── package-lock.json
└── README.md
```
## วิธีติดตั้งและใช้งาน i-Terial
1. git clone https://github.com/Chanokpuns/i-Terial.git
2. cd i-Terial
3. ติดตั้ง npm install
4. เริ่มต้น server ด้วยคำสั่ง node index.js
5. เปิดเว็บไซต์ผ่าน Browser ตาม Port ที่กำหนดไว้ในโปรเจกต์
