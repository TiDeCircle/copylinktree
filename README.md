# Green In Action — Link in bio

หน้าเว็บรวมลิงก์แบบ Linktree ของ greeninaction.space เขียนด้วย HTML/CSS ล้วน ไม่ต้อง build

## วิธีใช้
- เปิด `index.html` ในเบราว์เซอร์ได้เลย
- แก้ลิงก์ในปุ่มต่าง ๆ ได้ที่ `index.html` (ดูคอมเมนต์ "แก้ลิงก์ ... ตรงนี้")
- สี/ฟอนต์/สไตล์ แก้ได้ที่ `style.css` (ตัวแปรสีอยู่ด้านบนใน `:root`)

## รูปภาพ
ไฟล์ต้นฉบับอยู่ใน `seminar_2_asset/` ส่วนหน้าเว็บใช้ไฟล์ใน `assets/` ที่ย่อขนาดเป็น `.webp` แล้ว (เบากว่ามาก)

| ไฟล์ใน `assets/` | ใช้ทำอะไร |
| --- | --- |
| `bg.webp` | รูปพื้นหลังปก (ท้องฟ้า เมฆ ดาว เนินหญ้า) |
| `logo.webp`, `logo.png` | โลโก้ Green In Action จาก `Asset 22` / รูปตอนแชร์ลิงก์ |
| `favicon.png` | ไอคอนแท็บเบราว์เซอร์ จาก `font/Asset 25` |

ถ้าเปลี่ยนรูปต้นฉบับ ให้ย่อแล้ววางทับไฟล์ชื่อเดิมใน `assets/`

## Deploy
เปิด GitHub Pages ได้ที่ Settings → Pages → Deploy from branch แล้วเลือก branch และโฟลเดอร์ root
