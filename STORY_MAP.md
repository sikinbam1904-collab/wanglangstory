# แผนผังเนื้อเรื่องและจุดจบ

ทุกบทมี 3 ทางเลือก คะแนนสะสมและธงเหตุการณ์เปลี่ยนตามคำตอบ แต่เนื้อเรื่องหลักเดินครบ 20 บท ข้อความผลลัพธ์หลังเลือกจะต่างกันทันที และคะแนนจะเปลี่ยนจุดจบในบทสุดท้าย

## คะแนน
- `love` ความรัก
- `power` อำนาจ
- `wisdom` ปัญญา
- `revenge` ความแค้น
- `trust` ความไว้วางใจ
- `secret` ความลับ

## จุดจบ 6 แบบ (ตรวจตามลำดับใน `resolveEnding()`)
1. **หงส์เหนือบัลลังก์** — อำนาจสูงและเป็นคะแนนเด่น (โดยทั่วไป power ≥ 22)
2. **บุปผาคู่บัลลังก์** — love ≥ 15 และ trust ≥ 10
3. **ผู้พิพากษาแห่งรุ่งอรุณ** — wisdom ≥ 20 และ secret ≥ 8
4. **เพลิงแค้นใต้หิมะ** — revenge ≥ 18 และ power ≥ 12
5. **นกนอกกรงทอง** — love + trust ≥ 22 และ power < 18
6. **เงาที่ไม่มีชื่อ** — เส้นทางลับ/คะแนนไม่เข้าเงื่อนไขอื่น

## รายชื่อฉากหลัง
- `assets/scenes/ch01_gate.svg` — ประตูวังยามสาม
- `assets/scenes/ch02_hall.svg` — โถงรับราชโองการ
- `assets/scenes/ch03_tea.svg` — ห้องชา
- `assets/scenes/ch04_garden.svg` — สวนเหมย
- `assets/scenes/ch05_archive.svg` — หอจดหมายเหตุ
- `assets/scenes/ch06_market.svg` — ตลาดตะวันตก
- `assets/scenes/ch07_temple.svg` — ศาลบรรพชน
- `assets/scenes/ch08_rain.svg` — ระเบียงกลางฝน
- `assets/scenes/ch09_feast.svg` — งานเลี้ยงโคม
- `assets/scenes/ch10_prison.svg` — คุกหลวง
- `assets/scenes/ch11_pharmacy.svg` — ห้องยา
- `assets/scenes/ch12_lake.svg` — ศาลาริมสระ
- `assets/scenes/ch13_workshop.svg` — โรงช่างเงิน
- `assets/scenes/ch14_secret.svg` — ทางลับ
- `assets/scenes/ch15_court.svg` — ท้องพระโรง
- `assets/scenes/ch16_snow.svg` — ลานหิมะ
- `assets/scenes/ch17_tower.svg` — หอชมจันทร์
- `assets/scenes/ch18_wedding.svg` — พิธีเลือกคู่
- `assets/scenes/ch19_dawn.svg` — ประตูอรุณ
- `assets/scenes/ch20_throne.svg` — บัลลังก์มังกร

## รายชื่อตัวละคร placeholder
- `assets/characters/heroine.svg` — นางเอก: หญิงสาวผู้ซ่อนชาติกำเนิด
- `assets/characters/prince.svg` — องค์ชายเซียวเหยียน: องค์ชายผู้สุขุมและอ่านยาก
- `assets/characters/consort.svg` — พระสนมเอกหลัน: ผู้ทรงอำนาจในฝ่ายใน
- `assets/characters/eunuch.svg` — ขันทีเฒ่าจาง: ผู้เฝ้ากุญแจความลับ
- `assets/characters/envoy.svg` — ผู้ส่งสารไร้ตรา: ชายปริศนาจากนอกวัง
- `assets/characters/doctor.svg` — หมอหลวงเว่ย: ผู้รู้เรื่องพิษและยา
- `assets/characters/scribe.svg` — เสมียนหลวง: ผู้บันทึกคำสั่งลับ
- `assets/characters/witness.svg` — พยานในคดีเก่า: ผู้รอดชีวิตจากคืนเพลิงไหม้
- `assets/characters/old_woman.svg` — หญิงชรา: ผู้จำอดีตของมารดานางเอก
- `assets/characters/guard.svg` — องครักษ์หลวง: ผู้ภักดีต่อคำสั่งหรือความถูกต้อง