# Personal Hub - เฮีย Dashboard 📊

แอปบันทึกค่าใช้จ่าย และโน้ตเตือนความจำ พร้อม PWA Support

## 🚀 วิธีติดตั้งเป็นแอปบนมือถือ

### ขั้นตอนที่ 1: อัพโหลดขึ้น GitHub Pages

1. ไปที่ https://github.com → สร้าง Repository ใหม่
2. ตั้งชื่อ เช่น `personal-hub` (public repository)
3. อัพโหลดไฟล์ทั้งหมด:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`

4. ไปที่ Settings → Pages → Source: เลือก "main branch" → Save
5. รอ 1-2 นาที จะได้ URL: `https://ชื่อuser.github.io/personal-hub/`

### ขั้นตอนที่ 2: ติดตั้งบนมือถือ

#### **สำหรับ Android (Chrome/Edge)**
1. เปิด URL จากมือถือ
2. กด Menu (⋮) → **Add to Home screen**
3. ตั้งชื่อแอป → กด Add
4. เสร็จ! จะมีไอคอนบนหน้าจอ

#### **สำหรับ iPhone (Safari)**
1. เปิด URL ด้วย Safari
2. กด Share button (ไอคอนแชร์)
3. เลือก **Add to Home Screen**
4. ตั้งชื่อแอป → กด Add
5. เสร็จ! จะมีไอคอนบนหน้าจอ

---

## ✨ Features

- ✅ บันทึกค่าใช้จ่าย (แยก 5 หมวด)
- ✅ สรุปยอดรายวัน/สัปดาห์/เดือน
- ✅ กราฟแสดงสัดส่วนค่าใช้จ่าย
- ✅ โน้ตพร้อมระบบแท็ก
- ✅ ระดับความสำคัญ (สูง/กลาง/ต่ำ)
- ✅ Browser Notification สำหรับโน้ตสำคัญ
- ✅ ใช้งานออฟไลน์ได้ (PWA)
- ✅ ข้อมูลเก็บถาวรใน localStorage

---

## 🛠 Tech Stack

- HTML5 + CSS3 + Vanilla JavaScript
- Chart.js (กราฟ)
- Service Worker (offline support)
- LocalStorage (data persistence)
- PWA Manifest

---

## 📱 ความต้องการระบบ

- เบราว์เซอร์สมัยใหม่ (Chrome, Safari, Edge, Firefox)
- รองรับ localStorage
- รองรับ Service Worker (สำหรับโหมดออฟไลน์)

---

Made with ❤️ for เฮีย by Claude (Anthropic)
