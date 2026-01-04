# 🦀 Solana Thailand Genesis: A Transparent & Meritocratic Developer Community

> **"We build the system, the system builds the builders."**

Welcome to **Solana Thailand Genesis** — a workspace for Shippable Builders. We are a **Community-Led Organization** driven by transparency through GitHub; every decision is auditable (**Provable Governance**). We operate on a **Meritocracy** system that prioritizes Proof of Work over token holding.

## ⚓️ The System: Proof of Work over Tokenomics
To maintain quality and ensure only serious participants join, we use a **Commitment Stake** system:

1.  **Commitment Stake:** Here, you stake SOL to "buy the right to prove your skills." Participants must transfer SOL to the vault to confirm their intent to join a Quest.
2.  **Build:** Complete the mission (Quest) or project according to the specified conditions.
3.  **Unstake:** Once the work (PR/Issue) is submitted and merged, the stake is returned immediately.
4.  **Forfeit:** If you abandon the task or disappear, the stake will be forfeited to the **Treasury** to support further community development.

## 🎖 Ranks & Reputation (Governance)
Decision-making rights and system direction are based on **Reputation** accumulated through contributions:

### 🛡️ Core Maintainers (The Guardians)
* **👑 Owner:** System Architect & Strategic Lead ([@katopz](https://github.com/katopz))
* **✨ Holy Crab:** Mentors, Approvers & Judges (Authority based on Reputation)
* **🦀 King Crab:** Community Operator & Project Manager ([@ozoneRatchapon](https://github.com/ozoneRatchapon))

### ⚔️ Community Ranks (The Path)
* **🐺 Lone Wolf:** High-level Developer focused on solo contributions (Special Contributor)
* **🏹 Job Hunter (Rank 3):** Proven builders ready for mid-level tasks/bounties.
* **🔨 Builder (Rank 2):** Those who completed Quests (Unstaked) and demonstrated actual coding skills.
* **🛡️ Challenger (Rank 1):** Those who have placed a Stake and are currently in training.
* **👀 Spectator (Rank 0):** General observers in Discord.

## 🛠 How to Contribute

### 💻 For Developers (Code)
* Submit Pull Requests (PRs) to solve Quests, update Docs, or build Tools.
* **Proof:** Merged PRs = Reputation

### 🎨 For Operations (No-Code)
* Help organize events, create content, or coordinate venues.
* Create Issues under the `Budget & Event Proposal` category for approval.
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
