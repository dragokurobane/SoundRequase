# ขอเพลง

จอใหญ่ที่ `/` · มือถือที่ `/remote`

จอใหญ่: แถบซ้ายแนวตั้งเป็น QR + คิวเพลง, ขวาเป็นกล่องวิดีโอ 16:9, แชทจากมือถือจะลอยทับวิดีโอวิ่งจากขวาไปซ้าย (ปุ่ม ⛶ เต็มจอ อยู่มุมขวาบนของวิดีโอ)

## รันในเครื่อง
    node server.js

## ขึ้น Render
1. push โฟลเดอร์นี้ขึ้น GitHub
2. Render → New → Web Service → เลือก repo
3. Build Command: (เว้นว่างหรือ `echo ok`)  Start Command: `node server.js`
4. เปิด https://ชื่อ.onrender.com บนคอมที่ต่อจอ แล้วสแกน QR
