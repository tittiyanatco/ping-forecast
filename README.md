# Ping Forecast — P.1 เชียงใหม่

เว็บสาธิตพยากรณ์น้ำท่ารายวันที่สถานี P.1 แม่น้ำปิง

เปิดเว็บ: https://tittiyanatco.github.io/ping-forecast/

หน้าเว็บแสดง snapshot ของรอบที่ระบุไว้ด้านบน ไม่ได้สร้าง forecast ใหม่เมื่อเปิดหน้า
และจะแจ้งเมื่อวันข้อมูลเก่ากว่ารอบรายวันล่าสุด ข้อมูล RID เป็น provisional
โมเดลใช้ discharge-only set 1b และโมเดล NWP ทดลองเฉพาะแอป
ไม่ใช่โมเดล set 4 ที่ได้รับเลือกในงานวิจัย และยังไม่ใช่ระบบเตือนภัยน้ำท่วม

repository นี้เก็บเฉพาะ dashboard, metadata ของรอบ และ workflow เผยแพร่
ไม่เก็บข้อมูลฝึก โมเดล เอกสารวิทยานิพนธ์ หรือ prospective log ฉบับเต็ม

การ push snapshot ใหม่เข้า `main` หรือเรียก workflow ด้วยมือจะ deploy ผ่าน
GitHub Actions และ GitHub Pages ยังไม่ได้ตั้งงานสร้าง forecast รายวันอัตโนมัติ
