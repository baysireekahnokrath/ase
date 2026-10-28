# ASE™ — A Sense of Ease

พื้นที่ทำงานกลางของแบรนด์ **ASE** (furniture & living brand) สำหรับเก็บ Brand Bible, ไฟล์โลโก้ (.ai), ระบบสี/ฟอนต์, sub-brands และงาน marketing ทั้งหมด

> *Ease is not emptiness. It is not simplicity without thought.
> It is the quiet result of everything being considered.*

📖 สรุปแบรนด์: [`01_brand-bible/BRAND_SUMMARY.md`](01_brand-bible/BRAND_SUMMARY.md)
🏭 ข้อมูลบริษัท / ประวัติ / ลูกค้า: [`01_brand-bible/COMPANY_PROFILE.md`](01_brand-bible/COMPANY_PROFILE.md)
💡 โจทย์ Design Opportunity: [`04_sub-brands/DESIGN_OPPORTUNITY_BRIEF.md`](04_sub-brands/DESIGN_OPPORTUNITY_BRIEF.md)
🖥️ Company Profile 2026 (deck ใหม่): [เปิดดู](https://claude.ai/artifact/GPwX86DijWKTj2EFiErDf3) · source: `07_marketing/presentations/company-profile-2026/`
📁 Google Drive: [ASE folder](https://drive.google.com/drive/folders/1HpjM8dxj2oA-ItN-U9O6p7dCzmaxv7I8) · ไฟล์ไหนอยู่ตรงไหน ดู [`DRIVE_INDEX.md`](DRIVE_INDEX.md)

---

## โครงสร้างโฟลเดอร์

| โฟลเดอร์ | เก็บอะไร |
|---|---|
| `01_brand-bible/` | Brand Bible ฉบับ final (PDF) + สรุปแบรนด์ |
| `02_logo/source/` | ไฟล์ต้นฉบับโลโก้ **.ai** (master) |
| `02_logo/export/{svg,png,pdf}/` | โลโก้ที่ export แล้ว พร้อมใช้งาน |
| `03_color-typography/` | Design tokens (`tokens.json`, `tokens.css`) + `fonts/` |
| `04_sub-brands/` | `ase-living`, `ase-projects`, `ase-studio`, `ase-reform` |
| `05_imagery/` | `moodboard/`, `photography/` |
| `06_applications/` | `stationery`, `packaging`, `merchandise`, `signage` |
| `07_marketing/` | `campaigns`, `social-media`, `presentations` |
| `08_website/` | งานเว็บไซต์ |
| `99_archive/` | เวอร์ชันเก่า / ไม่ใช้แล้ว (ห้ามลบ ย้ายมาไว้ที่นี่แทน) |

## การตั้งชื่อไฟล์

```
YYYYMMDD_ASE_<SubBrand>_<Item>_<Variant>_v<NN>.<ext>
```

ตัวอย่าง
- `20261028_ASE_Logo_Primary_Black_v01.ai`
- `20261028_ASE-LIVING_Logo_Lockup_Ivory_v02.svg`
- `20261105_ASE-PROJECTS_Catalogue_Cover_v01.pdf`

- ใช้ภาษาอังกฤษ ไม่มีเว้นวรรค (ใช้ `_` คั่นส่วน, `-` ภายในส่วน)
- เวอร์ชันใหม่ → เพิ่ม `v` ไม่เขียนทับ; ตัวที่เลิกใช้ย้ายไป `99_archive/`

## ไฟล์ขนาดใหญ่

- GitHub รับไฟล์ได้ **ไม่เกิน 100 MB ต่อไฟล์** — ไฟล์ .ai / .psd / วิดีโอที่ใหญ่กว่านี้ให้เก็บใน **Google Drive** แล้วใส่ลิงก์ไว้ใน README ของโฟลเดอร์นั้น
- ไฟล์ที่เล็กกว่า 100 MB เก็บใน repo ได้ตามปกติ (ตั้งให้เป็น binary ไว้ใน `.gitattributes`)

## Quick reference

**Colors** — Primary: ASE Black `#11120D` · Warm Ivory `#F6F2E8` · Architectural Taupe `#C8C2B7`
Secondary: Craft Brown `#56483B` · Deep Leather `#49110B` · Soft Sand `#AD9E89` · Olive Grey `#565449`

**Fonts** — Aktiv Grotesk Thai (headline, EN) · IBM Plex Sans Thai Looped (copy, TH)

**Sub-brands** — ASE LIVING · ASE PROJECTS · ASE STUDIO · ASE REFORM
