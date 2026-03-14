# 📝 Lector-Line-bot

ระบบบันทึกตารางสอบผ่าน LINE LIFF ที่เชื่อมต่อกับ Firebase Firestore เพื่อการใช้งานที่สะดวกและรวดเร็วบนมือถือ

## 🚀 คุณสมบัติ (Features)
- บันทึกชื่อวิชา, วันที่ และเวลาสอบ
- ดึงข้อมูล User Profile จาก LINE อัตโนมัติ (UserId)
- บันทึกข้อมูลลงใน Firebase Firestore แบบ Real-time
- ปรับแต่งหน้าตาให้สวยงาม (Modern & Premium Design) และรองรับ Responsive (Mobile First)

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)
- **Frontend:** HTML, CSS, JavaScript (Vanilla JS)
- **Platform:** [LINE LIFF SDK v2](https://developers.line.biz/en/docs/liff/)
- **Backend/Database:** [Firebase Firestore](https://firebase.google.com/)

## ⚙️ การตั้งค่า (Configuration)
1. **Firebase:** นำ `firebaseConfig` จาก Firebase Console มาใส่ใน `index.html`
2. **LINE LIFF:** นำ `liffId` จาก LINE Developers Console มาใส่ในฟังก์ชัน `liff.init()` ใน `index.html`

## 📂 โครงสร้างโปรเจกต์
- `index.html`: ไฟล์หลักที่รวมทั้ง UI และ Logic การทำงาน
- `README.md`: รายละเอียดโปรเจกต์
