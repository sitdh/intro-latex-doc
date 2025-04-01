# From Code to Docs: จัดการเอกสารแบบมือโปรด้วย LaTeX + Git

👨‍💻 เอกสารก็เหมือนโค้ด — สวย เป๊ะ และควบคุมเวอร์ชันได้!

## 📌 เกี่ยวกับเวิร์กช็อปนี้

เวิร์กช็อปนี้เหมาะสำหรับนักพัฒนาโปรแกรมหรือผู้ที่ต้องการเขียนเอกสารอย่างมีประสิทธิภาพ โดยใช้ **LaTeX** ในการจัดรูปเล่มเอกสาร และควบคุมเวอร์ชันด้วย **Git** แบบเดียวกับการเขียนโปรแกรม

ผู้เข้าร่วมจะได้เรียนรู้ตั้งแต่พื้นฐานการใช้ LaTeX ไปจนถึงเทคนิคการจัดการโปรเจกต์เอกสารอย่างเป็นระบบ

---

## 🧠 สิ่งที่คุณจะได้เรียนรู้

- ทำความรู้จักกับ LaTeX และความแตกต่างจาก Word
- การติดตั้งและใช้งาน LaTeX (Overleaf และ VS Code)
- โครงสร้างพื้นฐานของไฟล์ `.tex`
- การพิมพ์ภาษาไทยใน LaTeX
- เทคนิคการจัดหน้า จัดรูปแบบ แทรกรูป ตาราง ฯลฯ
- การใช้ Git ควบคุมเวอร์ชันของเอกสาร
- การแยกไฟล์ LaTeX เป็นโมดูล
- ตัวอย่าง workflow ที่ใช้ได้จริง

---

## 🛠️ เครื่องมือที่ใช้

| หมวดหมู่ | เครื่องมือ |
|----------|-------------|
| Editor   | Overleaf / VS Code |
| Compiler | pdfLaTeX / LuaLaTeX |
| Version Control | Git / GitHub |
| Font     | TH Sarabun New (ภาษาไทย) |

---

## 📂 โครงสร้างโปรเจกต์

```text
project/
├── main.tex              # ไฟล์หลักของเอกสาร
├── sections/             # แยกเนื้อหาย่อยออกเป็นไฟล์
│   ├── intro.tex
│   └── conclusion.tex
├── images/               # เก็บไฟล์รูปภาพ
├── .gitignore            # ไฟล์ ignore ไฟล์ชั่วคราวจาก LaTeX
└── README.md             # คำอธิบายโปรเจกต์นี้