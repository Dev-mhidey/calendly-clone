# Calendly Frontend Clone (Pure HTML5 & CSS3)

A pixel-neat frontend clone of [Calendly](https://calendly.com/) created for a school project. Built with **100% pure semantic HTML5 and CSS3**—zero JavaScript, zero external scripting dependencies.

---

## 🚀 Key Features

- **All-in-One Compiled Entry (`index.html`)**: Self-contained single entry point containing all styles inlined for instant rendering and standalone deployment (or viewing directly without a server).
- **Pure CSS Interactive Hero Tabs**: Seamlessly switch between **Scheduling**, **Callie**, **Notetaker**, and **Payments** using CSS radio inputs (`input[type="radio"]`) and CSS sibling combinators—no JavaScript required.
- **Pure CSS Navigation Dropdowns**: Multi-column dropdown menus for *Product*, *Solutions*, and *Resources* with smooth hover transitions and invisible hover-bridges to prevent menu clipping.
- **4 Dedicated Showcase Sections**:
  1. **Scheduling**: Round-robin distribution, timezone recognition, custom buffers, and interactive booking slot selectors.
  2. **Callie AI Assistant**: Simulated conversational email thread with smart AI suggested time-chip slots.
  3. **Notetaker**: AI meeting recap document with interactive action-item checklists and CRM sync badges.
  4. **Payments**: Checkout summary preview with payment method selection (Credit Card, Apple Pay, PayPal).
- **Transparent Pricing Section**: Interactive tier comparison cards (Basic $0, Standard $10/mo, Teams $16/mo).
- **Responsive Layout**: Tailored media queries for desktop, tablet, and mobile screens.

---

## 📁 Repository Structure

```text
calendly-clone/
├── index.html
├── scheduling.html
├── callie.html
├── notetaker.html
├── payments.html
├── pricing.html
├── css/
│   └── styles.css
└── README.md
```

---

## 💻 How to View Locally

### Option 1: Direct File Opening
Double-click `index.html` in your file explorer to open it directly in any browser.

### Option 2: Local HTTP Server (PowerShell)
```powershell
python -m http.server 3000
```
Then visit: `http://localhost:3000`

---

## 📤 Push to GitHub (PowerShell Commands)

Run these commands in PowerShell from inside this directory:

```powershell
git add .
git commit -m "Update Calendly frontend clone documentation"
git push origin main
```