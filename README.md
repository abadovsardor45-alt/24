# 🏎️ Neon Drift - Overdrive

HTML5 Canvas va JavaScript orqali yaratilgan, dinamik va tezkor **Cyberpunk/Synthwave** uslubidagi mini-oʻyin. Koinot kemangizni boshqaring, toʻsiqlardan qoching va eng uzoq masofani bosib oʻtib yangi rekordlarni oʻrnating!

## ✨ Xususiyatlari

*   **Minimalist & Premium Neon UI:** Koʻzni qamashtiruvchi va zamonaviy geym-dizayn.
*   **Smooth Control:** Sichqoncha yoki sensorli ekran (touch) orqali kemani silliq va kechikishlarsiz boshqarish.
*   **Parallax Effect:** Kosmik fazo muhitini yaratuvchi chuqurlashtirilgan yulduzli fon effekti.
*   **Dinamik Qiyinchilik Darajasi:** Masofa oshgan sari oʻyin tezligi va toʻsiqlar zichligi avtomatik ravishda ortib boradi.
*   **Bonus Tizimi:** Oʻyinda omon qolish va koʻproq ochko yigʻish uchun maxsus bonuslar:
    *   🔵 **Qalqon (Shield):** Toʻsiqlar bilan boʻladigan 1 ta toʻqnashuvdan himoya qiladi.
    *   🟣 **Bonus Ball:** Masofani srazu `+500 LY` (Yorugʻlik yili) ga oshiradi.


## 🛠️ Ishlatilgan Texnologiyalar

*   **HTML5** — Oʻyin tuzilmasi va Canvas maydoni uchun.
*   **CSS3** — Dark-mode va Neon neon effektli interfeys (UI) dizayni.
*   **JavaScript (Vanilla JS)** — Fizika, obektlar generatsiyasi, toʻqnashuvlarni aniqlash (Collision Detection) va animatsiyalar uchun.

## 🎮 Oʻyinni Ishga Tushirish

Loyiha hech qanday qoʻshimcha kutubxonalar yoki oʻrnatmalarni (`npm install`) talab qilmaydi. Oʻyinni ishga tushirish uchun:

1. Ushbu repozitoriyani kompyuteringizga yuklab oling (`Clone`).
2. `index.html` faylini istalgan brauzerda oching.

### Boshqaruv:
*   **PC:** Sichqonchani (Mouse) chapga-oʻngga surish orqali.
*   **Mobile:** Ekranga tegib, barmoqni chapga-oʻngga surish orqali (`Touchmove`).

## ⚙️ Texnik Kod Strukturasi

Oʻyin bitta faylda, sodda va toza arxitektura asosida yozilgan:
*   `Entity` klassi — toʻsiqlar va bonuslarni obyektga yoʻnaltirilgan dasturlash (OOP) prinsiplari asosida boshqaradi.
*   `requestAnimationFrame` — silliq 60 FPS kadrlar almashinuvini taʼminlaydi.
*   `Trail effect` — `ctx.fillRect` tarkibidagi alpha kanali orqali kemaning ortidan neon izi qolishi taʼminlangan.
---
Dasturchi: [@abadovsardor45-alt](https://github.com/abadovsardor45-alt)
