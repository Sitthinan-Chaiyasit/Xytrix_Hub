# Xytrix Hub

แก้ข้อมูลทั้งหมดเพียงจุดเดียวใน `dist/index.html` ภายในตัวแปร `HUB_CONFIG`:

- `profileImage` สำหรับรูปโปรไฟล์
- `social` สำหรับชื่อบัญชีและลิงก์ Facebook, Instagram, YouTube, TikTok, Discord, LINE และ GitHub
- `games` สำหรับชื่อและรหัส RoV / MLBB รวมถึงชื่อผู้เล่นและลิงก์โปรไฟล์ Roblox
- `supportUrl` สำหรับลิงก์สนับสนุน

ปล่อยค่าว่าง (`""`) ไว้ได้ หน้าเว็บจะแสดง “เร็ว ๆ นี้” และซ่อนปุ่มที่กดไม่ได้ให้อัตโนมัติ

โปรเจกต์ตั้งค่าให้ Vercel เผยแพร่ไฟล์จาก `dist` ผ่าน `vercel.json` แล้ว
