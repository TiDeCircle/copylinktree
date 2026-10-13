# Green In Action — Link in bio

หน้าเว็บรวมลิงก์แบบ Linktree ของ greeninaction.space เขียนด้วย HTML/CSS ล้วน ไม่ต้อง build

## วิธีใช้
- เปิด `index.html` ในเบราว์เซอร์ได้เลย
- แก้ลิงก์ในปุ่มต่าง ๆ ได้ที่ `index.html` (ดูคอมเมนต์ "แก้ลิงก์ ... ตรงนี้")
- สี/ฟอนต์/สไตล์ แก้ได้ที่ `style.css` (ตัวแปรสีอยู่ด้านบนใน `:root`)

## รูปภาพ (โฟลเดอร์ `assets/`)
| ไฟล์ | ใช้ทำอะไร |
| --- | --- |
| `assets/hero.png` | รูปปกด้านบน (ท้องฟ้า + โลโก้ Green In Action) แนะนำสัดส่วนประมาณ 1 : 0.82 เช่น 960×790 px |
| `assets/favicon.png` | ไอคอนบนแท็บเบราว์เซอร์ |

ถ้ายังไม่มี `hero.png` หน้าเว็บจะแสดงพื้นหลังไล่สีพร้อมข้อความ "Green In Action" แทน

## Deploy
เปิด GitHub Pages ได้ที่ Settings → Pages → Deploy from branch แล้วเลือก branch และโฟลเดอร์ root
