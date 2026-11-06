# PROJECT: CAMPUSCODE — REBUILD '26 ROUND 1
## Pixel-Accurate Website Recreation & Google Stitch MCP Integration

This project is a 1:1 pixel-accurate recreation of the original **CampusCode** platform ([https://campuscode.co.in](https://campuscode.co.in)) for the **ReBuild '26 Round 1** hackathon challenge.

* 🌐 **Live Vercel Deployment**: [https://yes-livid-two.vercel.app](https://yes-livid-two.vercel.app)
* 🐙 **GitHub Repository**: [https://github.com/Akhand-shukla/campuscode](https://github.com/Akhand-shukla/campuscode)
* 🛡️ **AI Attestation (14.3%)**: [`.ai-attestation.yaml`](./.ai-attestation.yaml) (Compliant with < 40% rule)

---

## 📌 Executive Summary

* **Single Source of Truth**: [https://campuscode.co.in](https://campuscode.co.in)
* **Design Philosophy**: Zero redesign, zero dark-neon washouts, zero extraneous gradients. Minimalist brutalist/editorial aesthetic with strict adherence to official brand tokens.
* **Google Stitch MCP Project**: `14961696676016107976` ("CampusCode ReBuild 26")
  * **Canvas URL**: [https://stitch.google.com/projects/14961696676016107976](https://stitch.google.com/projects/14961696676016107976)

---

## 🎨 Official Brand System Alignment

| Token | Exact Hex Value | Usage |
| :--- | :--- | :--- |
| **Background** | `#f7f7f4` | Warm editorial newsprint/off-white substrate |
| **Card White** | `#ffffff` | Clean elevated content cards |
| **Ink Black** | `#111111` | Primary text, titles, buttons |
| **Electric Purple** | `#7665ff` | Slanted slash logo mark (Bar 2), active pills |
| **Primary Lime** | `#a8e62e` | Live pulse indicators, highlights |
| **Secondary Lime** | `#82b91a` | Slanted slash logo mark (Bar 3) |
| **Hairline Borders**| `#deded8` | Subtle structural division lines |

### Brand Typography
* **Primary / Headings**: `Inter` and `Space Grotesk`
* **Technical Labels & Statuses**: `DM Mono`
* **Signature Logo**: Original 3-slash mark skewed at `-17deg` with triple bars (`#111111`, `#7665ff`, `#82b91a`). Never redrawn, distorted, or recolored.

---

## 🗺️ The Four Mandatory Pages

### 1. Landing Page (`/`)
* **Navigation Bar**: Authentic 3-slash logo, monospaced tracking links (`ABOUT`, `HOW IT WORKS`, `HACKATHONS`, `COMMUNITY`), `LOGIN`, and `ENTER THE ARENA ↗`.
* **Hero Section**: `THE DIGITAL HOME FOR STUDENT INNOVATION`, `CHENNAI · INDIA`, `CAMPUSCODE / 001`, `BUILD COMPETE SHIP.`, description, `EXPLORE HACKATHONS ↗`, `01 / 05` scroll counter.
* **Infinite Marquee**: `IDEAS ✦ PEOPLE ✦ PRODUCTS ✦ INNOVATION ✦ COMMUNITY`.
* **Section 01 (What is CampusCode?)**: `WHERE STUDENTS BUILD.`, orbital rings A, B, C with core `CC` and numbered node tags.
* **Section 02 (The Experience)**: Original video player (`videos/what-is-campuscode.mp4`) with scroll autoplay and tap-to-sound controls.
* **Section 03 (How It Works)**: 4-step pipeline cards (`01 DISCOVER`, `02 TEAM UP`, `03 BUILD`, `04 SHIP`).
* **Section 04 (Enter The Arena)**: Hackathon rows (`01 AI INNOVATION`, `02 FUTURE WEB`, `03 CAMPUS TECH`) with live status indicators.
* **Section 05 & 06 (Mission & Community)**: `GREAT IDEAS NEED BUILDERS.`, network particle orbit.
* **Call to Action & Footer**: `JOIN CAMPUSCODE ↗`, full 4-column footer, copyright notice `© 2026 CAMPUSCODE`.

### 2. Login Page (`/login`)
* **Brand Header**: Slanted logo mark with `← BACK TO HOME` action.
* **Left Identity Panel**: `CAMPUSCODE / AUTHENTICATION`, index `ACCESS 01 / 02`, headline `ENTER THE ARENA.`, network telemetry.
* **Right Auth Card**: Clean `#ffffff` card with Campus Email, Password, `FORGOT PASSWORD?`, `ENTER THE ARENA ↗`, and `Create an account` link.

### 3. Registration Page (`/register`)
* **Brand Header**: Slanted logo mark with `← BACK TO HOME` action.
* **Left Identity Panel**: `CAMPUSCODE / REGISTRATION`, index `CREATE 02 / 02`, headline `BUILD WITH US.`.
* **Registration Form**: Full Name, University / College, Department, Campus Email, Password, Specialization track selection, and `LOG IN →` route.

### 4. Student Dashboard (`/student`)
* **Terminal Sidebar**:
  * CampusCode brandmark and workspace status.
  * Nav items: `Dashboard Overview`, `My Events`, `Events / EventHub`, `HackMate AI`, `IdeaCheck AI`, `RuleBot AI`, `Student Guide`, `Digital Card`, `Profile`, `Log Out`.
* **Dashboard Overview**:
  * Active sprint status (`AI INNOVATION Round 1`).
  * 3-Round Pipeline Visualizer (R1 Ideation & Problem Brief, R2 Code & Prototype, R3 Live Jury Demo).
  * Squad roster (Team NovaLabs members).
* **My Events**: Team workspace, stage review, and submission pipeline.
* **Events**: Hackathons explorer with track filters, deadlines, and one-click enrollment.

---

## 🧵 Google Stitch MCP Recreation Canvas

All four screens have been generated in your Google Stitch workspace:

1. **Landing Page**: [Node ID `338fbc75dba64281a15c1250c97ada95`](https://stitch.google.com/projects/14961696676016107976?node-id=338fbc75dba64281a15c1250c97ada95)
2. **Login Page**: [Node ID `152da4caf26749cb93e82d7448e8a328`](https://stitch.google.com/projects/14961696676016107976?node-id=152da4caf26749cb93e82d7448e8a328)
3. **Registration Page**: [Node ID `0894236bdf4a4cda9b2c7d2fc3a9476a`](https://stitch.google.com/projects/14961696676016107976?node-id=0894236bdf4a4cda9b2c7d2fc3a9476a)
4. **Student Dashboard**: [Node ID `a96ba25189794147bd76bf5759bb2c48`](https://stitch.google.com/projects/14961696676016107976?node-id=a96ba25189794147bd76bf5759bb2c48)

---

## 🚀 Running the Project Locally

```powershell
# Start local server
npm run dev
```

Visit the routes in your browser:
* **Landing Page**: [http://localhost:3000/](http://localhost:3000/)
* **Login Page**: [http://localhost:3000/login](http://localhost:3000/login)
* **Registration Page**: [http://localhost:3000/register](http://localhost:3000/register)
* **Student Dashboard**: [http://localhost:3000/student](http://localhost:3000/student)
