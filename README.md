# คู่มือกลยุทธ์พ่อค้าแห่งต้าชิง

เว็บคู่มือภาษาไทยแบบอินเทอร์แอคทีฟ รวบรวม 15 กลยุทธ์ธุรกิจจากซีรีส์ "พ่อค้าแห่งต้าชิง" พร้อมตัวกรองหมวดหมู่ การค้นหา รายการบันทึก และรายละเอียดเชิงลึก

## Requirements

- Node.js 20.19+ หรือ 22.12+
- npm
- การเชื่อมต่ออินเทอร์เน็ตสำหรับ Tailwind CSS, Alpine.js และ Google Fonts ที่โหลดจาก CDN

## เริ่มใช้งาน

```sh
npm install
npm run dev
```

Vite จะแสดง URL สำหรับเปิดเว็บในเครื่อง โดยปกติคือ `http://localhost:5173/`.

## คำสั่ง

```sh
npm run dev      # เริ่ม development server
npm run build    # สร้าง production build ใน dist/
npm run preview  # เปิดดู production build ในเครื่อง
```

## โครงสร้างหลัก

- `index.html` - หน้าเว็บและจุดเริ่มต้นของ Vite
- `พ่อค้าแห่งต้าชิง.html` - ไฟล์ HTML ต้นฉบับที่เก็บไว้เป็น reference
- `dist/` - ผลลัพธ์จาก production build (สร้างด้วย `npm run build`)
