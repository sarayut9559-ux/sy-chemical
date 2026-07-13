วิธีใช้งานไฟล์เว็บ S.Y. Chemical

1) เปิดดูในเครื่องแบบง่ายสุด
- แตกไฟล์ ZIP
- เข้าโฟลเดอร์ sy-chemical-static
- ดับเบิลคลิกไฟล์ index.html

2) ถ้าจะอัปขึ้น Vercel
หมายเหตุ: หน้า Dashboard ของ Vercel ที่คุณเปิดอยู่ ไม่ได้มีปุ่มอัปโหลด ZIP ตรง ๆ แบบง่ายเหมือน Netlify Drop
วิธีที่ตรงที่สุดจากเอกสาร Vercel คือใช้ Vercel CLI จากโฟลเดอร์โปรเจกต์
- ติดตั้ง Node.js
- เปิด Terminal ในโฟลเดอร์นี้
- รันคำสั่ง:
  npm i -g vercel
  vercel --prod

Vercel ระบุว่าสามารถ deploy ได้ตรงจาก CLI โดยไม่ต้องต่อ Git
อ้างอิง: Vercel Docs เรื่อง Deploying to Vercel และ vercel deploy

3) ถ้าจะอัปแบบลากไฟล์ง่ายกว่า
- ใช้ Netlify Drop
- แตกไฟล์ ZIP
- ลากโฟลเดอร์ sy-chemical-static ไปวางใน Netlify Drop
Netlify Docs ระบุว่าลากโฟลเดอร์ที่มีไฟล์ HTML ขึ้นได้โดยตรง

ไฟล์หลัก
- index.html
- styles.css
- images/

ข้อมูลที่ใส่ไว้แล้ว
- โลโก้ S.Y. Chemical
- รูปสินค้าจริง 6 ตัวหลัก
- เบอร์โทรไทย/ลาวแบบกดโทรได้
- อีเมล เว็บไซต์ และ YouTube
