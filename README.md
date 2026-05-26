<div align="center">

# 🏙️ MetroMate
### Residential Parking Management — Automated. Intelligent. Paperless.

[![Made by SNTL 84](https://img.shields.io/badge/Made%20by-SNTL%2084-01696f?style=for-the-badge&logo=github)](https://github.com/SNTL84)
[![License: MIT](https://img.shields.io/badge/License-MIT-gold?style=for-the-badge)](LICENSE)
[![Agentic AI](https://img.shields.io/badge/Agentic-AI%20Workflow-d95f3b?style=for-the-badge)](https://desidevloper.com)
[![Trilingual](https://img.shields.io/badge/Languages-EN%20%7C%20ગુ%20%7C%20हि-192840?style=for-the-badge)](#)
[![ResidentialParking](https://img.shields.io/badge/Service-Residential%20Parking%20Mgmt-2a7a52?style=for-the-badge)](#)

> **Stop losing money on unregistered vehicles, sticker fraud & parking disputes.**
> MetroMate automates the entire residential parking lifecycle — from digital registration to real-time dashboards — all via WhatsApp. No app installs. No paper. No excuses.

[📋 Vehicle Registration Form](./SNTL-84-Coral-Hieghts-Vehicle-Registration-Form-Englsh-May-2026.html) · [📊 Parking Dashboard (EN)](./SNTL-2784-Coral-Heights-A-building-May-2026-Vehicle-Count.html) · [📊 Parking Dashboard (ગુ)](./SNTL-2784-Gujarati-Coral-Heights-A-building-May-2026-Vehicle-Count.html) · [💬 WhatsApp](https://wa.me/919727413309)

</div>

---

## 🖼️ MetroMate in Action

![MetroMate 3-in-1 Services — On-Demand Companion | Gujarati | SNTL 84 Growth Engine](./assets/3in1-Metro-mate-git-services-image.jpg)

> *Left: English On-Demand Companion Service · Centre: Gujarati Shopping Assistant · Right: SNTL 84 Growth Engine*

---

## 💸 The Problem That's Costing Your Society Money

Every month, housing societies leak thousands of rupees in unregistered vehicles, missed sticker renewals, and parking disputes. Committee members spend hours chasing paper forms that never come back. Residents avoid registration because "the process is too complicated."

**MetroMate kills all of that.**

| Before MetroMate | After MetroMate |
|---|---|
| 📄 Paper forms lost in letterboxes | ✅ Digital form, WhatsApp submission instant |
| 🚫 No-shows on physical copy collection | ✅ Committee gets a timestamped message record |
| ❓ Unknown who owns which vehicle | ✅ Master register with reg numbers, models, colours |
| ⚠️ Parking disputes with no audit trail | ✅ Full vehicle-to-flat mapping, exportable |
| 🌐 Trilingual residents struggle with English-only forms | ✅ English + Gujarati + Hindi in one form |
| 🔢 Manual count of cars vs. slots | ✅ Live deficit/surplus dashboard auto-calculates |

---

## ✨ What's Inside

### 1. 📋 Vehicle Registration Form (Trilingual)
**File:** [`SNTL-84-Coral-Hieghts-Vehicle-Registration-Form-Englsh-May-2026.html`](./SNTL-84-Coral-Hieghts-Vehicle-Registration-Form-Englsh-May-2026.html)

A mobile-first, multi-step digital registration form that works on any smartphone browser — no app needed.

- **3-language UI**: Every field label in English · ગુજરાતી · हिन्दी
- **Smart sections**: Cars, Two-Wheelers, Bicycles with quantity spinners and YES/NO toggles
- **Vehicle details capture**: Registration number, make/model, colour — per vehicle
- **WhatsApp direct submit**: One tap sends a formatted message to the committee
- **Review modal**: Resident sees the full summary before sending — zero errors
- **Committee contacts**: President, Secretary, Treasurer — tap to WhatsApp or call
- **Validation**: Flat number format, 10-digit mobile, required field checks

### 2. 📊 Parking Master Dashboard (English)
**File:** [`SNTL-2784-Coral-Heights-A-building-May-2026-Vehicle-Count.html`](./SNTL-2784-Coral-Heights-A-building-May-2026-Vehicle-Count.html)

A live, auto-calculating parking intelligence dashboard for 42 flats across 11 floors.

- **Parking capacity compliance**: Overhead (15) + Basement (9) = 24 total slots
- **Real-time deficit alert**: Red card triggers if registered 4-wheelers exceed capacity
- **BIG vs SMALL car tracking**: Slot assignment based on actual car size
- **Full resident master table**: Sr. No · Owner/Rental badge · Flat · Name · Mobile · Car size · 4W count · Reg numbers · 2W count · Bicycles · Designation
- **Designation tags**: President, Secretary, Treasurer highlighted with pill badges
- **42 residents verified**: Owners and rentals clearly differentiated

### 3. 📊 Parking Master Dashboard (ગુજરાતી / Gujarati)
**File:** [`SNTL-2784-Gujarati-Coral-Heights-A-building-May-2026-Vehicle-Count.html`](./SNTL-2784-Gujarati-Coral-Heights-A-building-May-2026-Vehicle-Count.html)

Identical dataset, fully rendered in Gujarati script — for committee members and residents who prefer Gujarati. Complete parity with the English dashboard.

---

## 🗂️ Repository Structure

```
MetroMate/
│
├── 📋 SNTL-84-Coral-Hieghts-Vehicle-Registration-Form-Englsh-May-2026.html
│   └── Trilingual resident vehicle registration form → WhatsApp submission
│
├── 📊 SNTL-2784-Coral-Heights-A-building-May-2026-Vehicle-Count.html
│   └── English parking master dashboard — 42 flats, live deficit calculator
│
├── 📊 SNTL-2784-Gujarati-Coral-Heights-A-building-May-2026-Vehicle-Count.html
│   └── Gujarati parking master dashboard — same dataset, Gujarati script
│
├── 🖼️ assets/
│   └── 3in1-Metro-mate-git-services-image.jpg  ← MetroMate 3-in-1 services banner
│
└── README.md
```

> **Naming convention:** `SNTL-{ID}-{Society}-{Building}-{Month-Year}-{Type}.html`
> Sortable, society-specific, and version-safe across all deployments.

---

## 🚀 How to Deploy in Your Society — 5 Minutes Flat

```bash
# 1. Clone the repo
git clone https://github.com/SNTL84/MetroMate.git

# 2. Open the registration form in any browser
open SNTL-84-Coral-Hieghts-Vehicle-Registration-Form-Englsh-May-2026.html

# 3. Share the file link with residents via WhatsApp broadcast
# Host on GitHub Pages, Netlify, or any static host for a permanent URL

# 4. As registrations come in via WhatsApp, update the dashboard dataset
# Edit the residentsData array in the dashboard HTML

# 5. Share the dashboard link with the committee
```

**No server. No database. No monthly costs.** Pure HTML — runs everywhere.

---

## 🔁 The Agentic Automation Flow

```
Resident opens form (mobile browser)
        ↓
Fills flat number · name · contact · vehicles
        ↓
Taps "Review & Send on WhatsApp"
        ↓
WhatsApp opens with pre-filled structured message
        ↓
Resident taps Send → Committee WhatsApp receives instantly
        ↓
Committee updates master dashboard dataset
        ↓
Parking deficit/surplus recalculates automatically
        ↓
Monthly audit: dashboard screenshot → society minutes
```

---

## 📐 Technical Architecture

| Layer | Technology | Why |
|---|---|---|
| **UI** | Pure HTML5 + CSS3 + Vanilla JS | Zero dependencies, works offline, no CDN failures |
| **Fonts** | Google Fonts: Cormorant Garamond + Outfit | Premium typography, fast load |
| **Multilingual** | Noto Sans Gujarati + Noto Sans Devanagari | Native script rendering on all devices |
| **Submission** | WhatsApp `wa.me` deep link + `encodeURIComponent` | No backend needed — WhatsApp is the database |
| **Icons** | Inline SVG | Zero external icon library requests |
| **Data** | JS array literal in HTML | Single-file, zero-dependency dashboard |
| **Responsive** | CSS Grid + Flexbox + `clamp()` | Works on 375px phones to 1600px monitors |
| **Accessibility** | Semantic HTML, ARIA labels, focus rings | Keyboard navigable, screen reader compatible |

---

## 🌐 Use Cases Beyond Coral Heights

MetroMate is a **template system**. Duplicate and configure for:

- 🏢 Any residential society — change the `residentsData` array
- 🏬 Commercial building parking management
- 🏫 School/college vehicle gate passes
- 🏥 Hospital staff parking registers
- 🏗️ Builder possession handover vehicle surveys
- 🏨 Gated community visitor vehicle logs

---

## 🔧 Customisation Guide

### Change the Society / WhatsApp Number
```javascript
// In the registration form HTML, find:
document.getElementById('waLink').href = `https://wa.me/919727413309?text=${encoded}`;
// Replace 919727413309 with your committee WhatsApp number
```

### Add a New Resident to the Dashboard
```javascript
// In the dashboard HTML, add to the residentsData array:
{
  sr: 43, ownerType: 'Owner', flat: '1201', name: 'Your Resident Name',
  mobile: '98XXXXXXXX', carSize: 'BIG', fourWCount: 1,
  fourReg: 'GJ-05-XX-0000', twoWCount: 1,
  twoReg1: 'GJ-05-YY-1111', bicycle: 0, designation: ''
}
```

### Change Parking Capacity
```javascript
const OVERHEAD_SLOTS = 15;  // Overhead parking slots
const BASEMENT_SLOTS = 9;   // Basement parking slots
// Total will auto-recalculate
```

---

## 👤 Built by SNTL 84

**Automate What's Costing You Money**

`SNTL 84` · Agentic AI Workflow Professional

Specialising in: **Lead Generation · Fulfillment Automation · Bench Resource Availability · Full-Stack Builds · AI Workflows · Supply Chain Business Intelligence**

🚀 Follow for practical AI automation insights & founder systems.

| Platform | Link |
|---|---|
| 🌐 Website | [desidevloper.com](https://desidevloper.com) |
| 💬 WhatsApp | [wa.me/919727413309](https://wa.me/919727413309) |
| 🔗 LinkedIn | [linkedin.com/in/sntl2784](https://linkedin.com/in/sntl2784) |
| 💻 GitHub | [github.com/SNTL84](https://github.com/SNTL84) |
| 📸 Instagram | [@desibiztrade](https://www.instagram.com/desibiztrade) |
| 🔴 YouTube | [@SNTL84](https://youtube.com/@SNTL84) |

> 🚀 **If this repo saved your society time or money, star it ⭐ and share it with other housing societies.** That's the only metric that matters here.

---

## 📄 Licence

MIT — Free to use, adapt, and deploy for your society or clients. Attribution appreciated.

```
Copyright (c) 2026 SNTL 84 | desidevloper.com
```

---

<div align="center">

**MetroMate** · Residential Parking Management · Built by [SNTL 84](https://github.com/SNTL84)

*Automate What's Costing You Money*

</div>
