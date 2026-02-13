<!-- GUSON README -->

<a id="readme-top"></a>

[![Contributors](https://img.shields.io/github/contributors/namput/guson.svg?style=for-the-badge)](https://github.com/namput/guson/graphs/contributors)
[![Stars](https://img.shields.io/github/stars/namput/guson.svg?style=for-the-badge)](https://github.com/namput/guson/stargazers)
[![Issues](https://img.shields.io/github/issues/namput/guson.svg?style=for-the-badge)](https://github.com/namput/guson/issues)

<br />
<div align="center">
  <a href="https://guson.co">
    <img src="https://guson0storage0account.blob.core.windows.net/guson-container/mainwebsiteconfig/logo/1768286994921-qq.webp" alt="Guson Logo" width="90" height="90">
  </a>

  <h3 align="center">Guson</h3>

  <p align="center">
    โครงสร้างพื้นฐานดิจิทัลสำหรับครูอิสระ
    <br />
    <a href="https://guson.co"><strong>เข้าใช้งานแพลตฟอร์ม »</strong></a>
    <br /><br />
    <a href="https://guson.co">เว็บไซต์จริง</a>
    ·
    <a href="https://github.com/namput/guson/issues">รายงานปัญหา</a>
    ·
    <a href="https://github.com/namput/guson/issues">เสนอฟีเจอร์</a>
  </p>
</div>

---

## สารบัญ

* [เกี่ยวกับโครงการ](#เกี่ยวกับโครงการ)
* [เทคโนโลยีที่ใช้](#เทคโนโลยีที่ใช้)
* [เริ่มต้นใช้งาน](#เริ่มต้นใช้งาน)
* [การใช้งาน](#การใช้งาน)
* [Roadmap](#roadmap)
* [การมีส่วนร่วม](#การมีส่วนร่วม)
* [License](#license)
* [ติดต่อ](#ติดต่อ)

---

## เกี่ยวกับโครงการ

Guson คือแพลตฟอร์ม Marketplace สำหรับครูอิสระ ออกแบบโดยยึด “ครูเป็นศูนย์กลาง” แทนการรวมไว้ใต้แบรนด์แพลตฟอร์ม

สิ่งที่แตกต่าง:

* ระบบ Sub-domain สำหรับครูแต่ละคน
* โครงสร้าง SEO แยกต่อครู
* ระบบกำหนดราคาต่อชั่วโมง / ต่อคอร์ส
* ระบบบทความเพื่อเพิ่มการค้นพบแบบ Organic
* รองรับการเข้าสู่ระบบด้วย ThaiD
* Stripe Integration สำหรับการชำระเงิน

แพลตฟอร์มจริง:
[https://guson.co](https://guson.co)

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## เทคโนโลยีที่ใช้

* Next.js (App Router)
* TypeScript
* MUI
* Zustand
* PostgreSQL
* Redis
* Azure Blob Storage
* Docker
* Azure App Service
* GitHub Actions (CI/CD)
* Stripe
* ThaiD Integration

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## เริ่มต้นใช้งาน

### Prerequisites

* Node.js 18+
* npm
* PostgreSQL
* (optional) Redis

### Installation

```sh
git clone https://github.com/namput/guson.git
cd guson
npm install
npm run dev
```

สร้างไฟล์ `.env.local`

```env
NEXT_PUBLIC_API_URL=
NEXT_PUBLIC_STORAGE_URL=
NEXT_PUBLIC_STRIPE_PUBLIC_KEY=
DATABASE_URL=
```

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## การใช้งาน

โครงสร้างหลักของระบบ:

```
/app
/components
/hooks
/stores
/lib
/theme
/utils
```

หลักการออกแบบ:

* Mobile-first
* ลด Client-side hydration ที่ไม่จำเป็น
* Optimize Core Web Vitals
* บีบอัดและปรับขนาดภาพตามอุปกรณ์
* แยก state อย่างชัดเจน

Performance Targets:

* LCP < 2.5s
* INP < 200ms
* CLS < 0.1

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## Roadmap

* [x] ระบบ Sub-domain ครู
* [x] ระบบบทความ
* [x] Stripe Integration
* [x] ThaiD Login
* [ ] ระบบ Referral
* [ ] Dashboard วิเคราะห์ข้อมูลครู
* [ ] Dynamic Image Resize Pipeline
* [ ] Commission Model Marketplace

ดูรายการ issue ทั้งหมดได้ที่:
[https://github.com/namput/guson/issues](https://github.com/namput/guson/issues)

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## การมีส่วนร่วม

หากคุณต้องการมีส่วนร่วม:

1. Fork โปรเจกต์
2. สร้าง Feature Branch
3. Commit การเปลี่ยนแปลง
4. เปิด Pull Request

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## License

Core Infrastructure: Proprietary
บางโมดูลอาจเปิดเป็น Open Source ในอนาคตตามกลยุทธ์

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>

---

## ติดต่อ

Website: [https://guson.co](https://guson.co)
Email: [support@guson.co](mailto:support@guson.co)

Project Repository:
[https://github.com/namput/guson](https://github.com/namput/guson)

<p align="right">(<a href="#readme-top">กลับด้านบน</a>)</p>
