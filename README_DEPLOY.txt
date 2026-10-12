4 JOP 41 — Public Release v12
==============================

ไฟล์สำหรับ deploy
- index.html              หน้าแผนที่หลัก
- manifest.webmanifest    metadata สำหรับ mobile web app
- icon-192.png            ไอคอนมือถือ
- icon-512.png            ไอคอนมือถือความละเอียดสูง
- QA_CHECKLIST.txt        checklist ก่อนเปิดใช้จริง

วิธี deploy
1. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไปยัง static web hosting
2. ตั้ง index.html เป็นหน้าเริ่มต้น
3. ต้องให้เว็บไซต์เปิดผ่าน HTTPS
4. หลังได้ URL จริง ให้ทดสอบบน iPhone Safari/Camera QR และ Android Chrome
5. เมื่อ URL คงที่แล้ว จึงสร้าง QR สำหรับงาน

ข้อจำกัดที่ต้องทราบ
- แผนที่ 3D และแผนที่ฐานต้องใช้อินเทอร์เน็ต
- ระบบใช้ MapLibre/OpenFreeMap จากภายนอก
- ปุ่มนำทางส่งต่อไปยัง Google Maps
- NU Transit และกำหนดการงานเปิดจากเว็บไซต์ภายนอก
- ยังไม่มี Zone polygon เพราะยังไม่ได้ยืนยันขอบเขตจริง
