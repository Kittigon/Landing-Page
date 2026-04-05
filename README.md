# Landing Page Project

โปรเจกต์หน้าเว็บแบบหลายหน้า (Multi-page) ที่พัฒนาด้วย HTML + Tailwind CSS
ประกอบด้วยหน้า Home, Gallery และ Location พร้อมเมนูนำทางเชื่อมทุกหน้า

## Features

- หน้า Home สำหรับแสดง Hero section และเนื้อหาหลัก
- หน้า Gallery สำหรับแสดงรูปภาพแบบ Grid
- หน้า Location สำหรับดึงพิกัดปัจจุบันของผู้ใช้ด้วย Geolocation API
- แสดงแผนที่ Google Maps จากพิกัดปัจจุบันของผู้ใช้
- Responsive layout รองรับมือถือและเดสก์ท็อป

## Project Structure

```
.
|-- index.html
|-- gallery.html
|-- location.html
|-- hero.png
|-- 1.png ... 11.png
|-- LICENSE
`-- README.md
```

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Geolocation API (Browser)

## How to Run

1. Clone หรือดาวน์โหลดโปรเจกต์นี้
2. เปิดโฟลเดอร์โปรเจกต์
3. เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์

หมายเหตุ:
- หากเปิดหน้า `location.html` แล้วกดปุ่ม Get Location เบราว์เซอร์จะขอสิทธิ์เข้าถึงตำแหน่ง
- ควรอนุญาตตำแหน่งเพื่อให้ระบบแสดงพิกัดและแผนที่ได้ถูกต้อง

## Pages

- Home: `index.html`
- Gallery: `gallery.html`
- Location: `location.html`

## License

โปรเจกต์นี้อยู่ภายใต้สัญญาอนุญาต MIT ตามไฟล์ LICENSE
