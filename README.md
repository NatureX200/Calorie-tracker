# 🔥 Fat Loss Tracker — PWA

แอปติดตามแคลอรี่สำหรับ iPhone (Progressive Web App)

---

## 📁 ไฟล์ในโฟลเดอร์นี้

```
index.html      ← ตัวแอปหลักทั้งหมด
manifest.json   ← ข้อมูล PWA (ชื่อแอป, ไอคอน)
sw.js           ← Service Worker (ใช้งาน offline ได้)
icon-192.png    ← ไอคอนแอป
icon-512.png    ← ไอคอนแอป (ใหญ่)
```

---

## 🚀 วิธี Deploy ขึ้น GitHub Pages

### ขั้นตอนที่ 1 — สร้าง Repository
1. เข้า [github.com](https://github.com) → กด **New repository**
2. ตั้งชื่อ เช่น `calorie-tracker`
3. เลือก **Public**
4. กด **Create repository**

### ขั้นตอนที่ 2 — อัปโหลดไฟล์
1. ในหน้า repo ใหม่ กด **Add file → Upload files**
2. ลากไฟล์ทั้งหมด 5 ไฟล์ใส่:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. กด **Commit changes**

### ขั้นตอนที่ 3 — เปิด GitHub Pages
1. ไปที่ **Settings** (ในหน้า repo)
2. เลือก **Pages** (ในเมนูซ้าย)
3. Source → เลือก **Deploy from a branch**
4. Branch → เลือก **main** → folder **/ (root)**
5. กด **Save**
6. รอ ~1 นาที จะได้ URL เช่น `https://username.github.io/calorie-tracker`

---

## 📱 วิธีเพิ่มลง Home Screen iPhone

1. เปิด URL ด้วย **Safari** (ต้องใช้ Safari เท่านั้น)
2. กดปุ่ม **Share** (กล่องมีลูกศรชี้ขึ้น) ที่แถบด้านล่าง
3. เลือก **"Add to Home Screen"** (เพิ่มไปยังหน้าจอโฮม)
4. ตั้งชื่อ → กด **Add**
5. ไอคอนจะปรากฏบนหน้าจอโฮม — เปิดแบบ fullscreen ไม่มี browser bar ✅

---

## ✨ ฟีเจอร์

- 📊 วงแหวนแสดงแคลอรี่วันนี้ เปลี่ยนสีตามสถานะ
- 🎯 Progress bar นับ deficit สะสมสู่การลดไขมัน 1 กก.
- ⭐ เมนูของฉัน — บันทึกเมนูประจำพร้อม emoji ใช้ซ้ำได้เร็ว
- 📅 ประวัติ 14 วัน
- ⚙ ปรับระดับกิจกรรม / TDEE ได้
- 💾 บันทึกข้อมูลใน localStorage (ไม่หายเมื่อปิดแอป)
- 📶 ใช้งาน offline ได้ (Service Worker)
