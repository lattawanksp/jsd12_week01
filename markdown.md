Creat yourself s markdown cheatsheet

Basic command
-----------------------------------------------------------------------
- ls (List) = แสดงรายชื่อไฟล์และโฟลเดอร์ในตำแหน่งปัจจุบัน
- mkdir (Make Directory) = สร้างโฟลเดอร์ใหม่
- cd (Change Directory) = เปลี่ยนหรือย้ายไปยังโฟลเดอร์อื่น
- touch (Touch) = สร้างไฟล์ใหม่ (ไฟล์ว่าง) หรืออัปเดตเวลาเข้าถึงไฟล์
- mv (Move) = ย้ายไฟล์/โฟลเดอร์ หรือใช้เพื่อเปลี่ยนชื่อ
- rm (Remove) = ลบไฟล์
- rmdir = ลบโฟลเดอร์
- pwd (Print Working Directory) = แสดงตำแหน่งพาธ (Path) ที่เราอยู่ปัจจุบัน
- chmod (Change Mode) = เปลี่ยนสิทธิ์การเข้าถึงไฟล์ (เช่น อ่าน/เขียน/รัน)
- code . = เปิดโฟลเดอร์ปัจจุบันที่เราอยู่
- code -r . = สั่งให้เปิดโปรเจคนี้ข้างใน vs code
- code ชื่อ = แก้/พิมพ์ไฟล์.md
- cd .. = ย้อนกลับไป 1 ชั้น
- cd ../.. = ย้อนกลับไป 2 ชั้น
- cd - = กลับไปโฟลเดอร์เดิมก่อนหน้า
-----------------------------------------------------------------------
remark: พิมพ์ --help ต่อได้ทุกคำสั่ง หากมีเวลาอ่านวิธีใช้


Git----------------------------------------------
git init     สร้างถังเก็บ (Repository) ใหม่ในโฟลเดอร์ปัจจุบัน ทำครั้งเดียวตอนเริ่ม
git add .     เพิ่มไฟล์เข้า staging
git add ชื่อไฟล์    เพิ่มเฉพาะไฟล์เดียว
git commit -m "describe what you changed"    Commit
git push origin main       Push ขึ้น GitHub
git push

git log --oneline   เช็ค history
git remote -v       เช็ค repository

rm -rf .git   remove recursive(ทั้งโฟลเดอร์และข้างใน) force(บังคับลบ) โฟลเดอร์ที่เก็บข้อมูล Git
ls -la    list files -l แสดงแบบ list รายละเอียด -a แสดงไฟล์ hidden

git branch -m main       เปลี่ยน branch

git clone URL    clone งานใน github มาใส่



---------------------------------------------------------------------
Woowoowoo
