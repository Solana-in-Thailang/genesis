# 🦀 Solana Thailand Genesis: A Transparent & Meritocratic Developer Community

> **"We build the system, the system builds the builders."**

ยินดีต้อนรับสู่ **Solana Thailand Genesis** — พื้นที่ของนักพัฒนาที่เน้นการลงมือทำจริง (Shippable Builders) เราคือ **Community-Led Organization** ที่ขับเคลื่อนด้วยความโปร่งใสผ่าน GitHub ทุกการตัดสินใจตรวจสอบได้ (**Provable Governance**) โดยเน้นระบบ **Meritocracy** (ระบอบความสามารถนิยม) ที่ให้ความสำคัญกับผลงาน (Proof of Work) มากกว่าการถือครอง Token

## ⚓️ The System: Proof of Work over Tokenomics
เพื่อรักษาคุณภาพและคัดกรองเฉพาะผู้ที่ตั้งใจจริง เราใช้ระบบ **Commitment Stake**:

1.  **Commitment Stake (วางมัดจำ):** ที่นี่คุณวางเงินเพื่อ "ซื้อสิทธิ์ในการพิสูจน์ฝีมือ" ผู้เข้าร่วมต้องโอน SOL เข้ากองกลางเพื่อยืนยันความตั้งใจในการเข้าร่วม Quest
2.  **Build (ลงมือทำ):** ทำโจทย์ (Quest) หรือโปรเจกต์ให้สำเร็จตามเงื่อนไขที่กำหนด
3.  **Unstake (รับเงินคืน):** เมื่อส่งงาน (PR/Issue) และผ่านการตรวจ (Merge) ระบบจะคืนเงินมัดจำให้ทันที
4.  **Forfeit (ริบเงิน):** หากทิ้งงานหรือหายตัวไป เงินมัดจำจะถูกริบเข้า **Treasury** เพื่อใช้พัฒนา Community ต่อไป

## 🎖 Ranks & Reputation (Governance)
สิทธิ์ในการตัดสินใจและทิศทางของระบบจะขึ้นอยู่กับ **Reputation** ที่สะสมจากการมีส่วนร่วม (Contribution):

### 🛡️ Core Maintainers (The Guardians)
* **👑 Owner:** System Architect & Strategic Lead ([@katopz](https://github.com/katopz))
* **✨ Holy Crab:** Mentors, Approvers & Judges (ผู้มีสิทธิ์ตัดสินผลงานและทิศทางระบบตาม Reputation)
* **🦀 King Crab:** Community Operator & Project Manager ([@ozoneRatchapon](https://github.com/ozoneRatchapon))

### ⚔️ Community Ranks (The Path)
* **🐺 Lone Wolf:** Developer ระดับสูงที่เน้นฉายเดี่ยว (Special Contributor)
* **🏹 Job Hunter (Rank 3):** ผู้ที่พิสูจน์ฝีมือแล้ว พร้อมรับงาน (Bounties) จากกองกลาง
* **🔨 Builder (Rank 2):** ผู้ที่ทำ Quest สำเร็จ (Unstaked) เขียนโค้ดได้จริง
* **🛡️ Challenger (Rank 1):** ผู้ที่วางเงิน Stake แล้ว และกำลังอยู่ในระหว่างการฝึกฝน
* **👀 Spectator (Rank 0):** ผู้สังเกตการณ์ทั่วไปใน Discord

## 🛠 How to Contribute

### 💻 For Developers (Code)
* ส่ง Pull Request (PR) เพื่อแก้ Quest, อัปเดต Docs หรือสร้าง Tools
* **Proof:** Merged PRs = Reputation

### 🎨 For Operations (No-Code)
* ช่วยจัด Event, ทำ Content, ติดต่อสถานที่
* สร้าง Issue ในหมวด `Budget & Event Proposal` เพื่อขออนุมัติ
* **Proof:** Completed Issues = Reputation

## ⚓️ Getting Started
1.  **Join Discord:** [https://discord.gg/PGbUgNmsns](https://discord.gg/PGbUgNmsns)
2.  **Read the Quests:** Explore `docs/content/quests` for current challenges.
3.  **Check Treasury:** Financial transparency is documented in `docs/content/treasury`.

## 🏗 Project Architecture

This project is built using [Zola](https://www.getzola.org/), a fast static site generator.

### Directory Structure
- `data/`: Contains core data files (e.g., `registry.json` for member lists).
- `docs/`: The main Zola project directory.
    - `content/`: Markdown files for site content (Rules, Leaderboard, Quests).
    - `sass/`: Global styles using SCSS.
    - `templates/`: HTML templates and layouts.
    - `static/`: Static assets like images and icons.
- `.github/`: GitHub workflows and issue templates for DAO operations.

## 🚀 Local Development

To run the site locally, you need to have [Zola](https://www.getzola.org/documentation/getting-started/installation/) installed.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/solana-thailand/genesis.git
    cd genesis/docs
    ```
2.  **Run the development server:**
    ```bash
    zola serve
    ```
3.  **View the site:** Open `http://127.0.0.1:1111` in your browser.


---
*Maintained by Solana Developer Thailand Core Team*
