# Bangladesh Youth Community Verona – Official Web Portal

![Version](https://img.shields.io/badge/version-1.0.0-blue) ![Status](https://img.shields.io/badge/status-live-success) ![License](https://img.shields.io/badge/license-MIT-green)

> A dynamic, multi-lingual digital platform connecting the Bangladeshi expatriate community in Verona, Italy.

---

## 📋 Executive Summary

The **Bangladesh Youth Community Verona** website is a responsive digital platform designed to serve the Bangladeshi expatriate community living in Verona. The primary goal is to digitalize operations, ensure **100% transparency** regarding members and services, and facilitate seamless communication between the executive council and general members.

The solution utilizes a **Serverless Architecture (Static Web)**, leveraging **Google Sheets** as a real-time database and the **WhatsApp API** for instant communication, ensuring zero maintenance costs and high performance.

---

## 🎯 Project Objectives

- **Digital Identity:** Establish a professional online presence.
- **Transparency:** Display real-time data (Members, Services, Founders) directly from official records without manual coding.
- **Accessibility:** Break language barriers with support for **English 🇺🇸, Italian 🇮🇹, and Bengali 🇧🇩**.
- **Communication:** Bridge the gap between members and leaders via direct WhatsApp integration.
- **Information Hub:** Centralize info on Italian laws, jobs, housing, and consular services.

---

## 🛠 Technical Architecture

### Technology Stack
| Component | Technology Used |
| :--- | :--- |
| **Frontend** | HTML5 (Semantic) |
| **Styling** | CSS3 (Flexbox, Grid, Glassmorphism) |
| **Logic** | Vanilla JavaScript (ES6+) |
| **Database/CMS** | Google Sheets (iFrame Embeds) |
| **Communication** | WhatsApp API (`wa.me`) |
| **Icons & Fonts** | FontAwesome 6, Google Fonts (Poppins, Hind Siliguri) |

### Key Design Decisions
* **No-Backend Approach:** Runs without PHP/Node/Python databases, making it secure and free to host.
* **Mobile-First:** Optimized for touch interactions (swipeable tables, hamburger menus) since 90% of traffic is mobile.

---

## 🚀 Core Features

### 1. 🌐 Multi-Language System (i18n)
Users can toggle languages instantly without page reloads. A JavaScript dictionary (`langData`) dynamically injects text based on the selected language, catering to:
* First-generation immigrants (Bengali)
* Second-generation youth (Italian)
* International viewers (English)

### 2. 📊 Live Data Transparency
Official records are maintained in **Google Sheets** and embedded into the site.
* **Real-time Updates:** Admins update the Excel sheet, and the site updates automatically.
* **Mobile Optimization:** Wide spreadsheets are wrapped in a horizontally scrollable container with visual "Swipe" cues.

### 3. 💬 Direct WhatsApp Integration
* **Smart Contact Form:** Submitting the form constructs a pre-formatted WhatsApp message and sends it directly to the President.
* **Executive Chat:** Profile cards allow users to chat directly with leaders.
* **Floating Button:** A persistent chat button ensures help is always available.

### 4. 🎨 Interactive UI Components
* **Glassmorphism Header:** Navbar changes appearance on scroll.
* **Accordion Sections:** Clean organization for constitutional laws.
* **Gallery Overlays:** Hover effects on activity photos to reveal details.

---

## 🎨 UI/UX Design Strategy

The design reflects the national identity of Bangladesh while maintaining modern web standards.

* 🟢 **Primary:** `#006A4E` (Bangladesh Green)
* 🔴 **Secondary:** `#F42A41` (Red - Alerts/Buttons)
* ⚪ **Background:** `#F8FAFC` (Light Gray - Eye comfort)

**Typography:**
* *Poppins* (English/Italian)
* *Hind Siliguri* (Bengali)

---

## 🧩 Challenges & Solutions

| Challenge | Solution Implemented |
| :--- | :--- |
| **Large Excel Tables on Mobile** | Implemented `overflow-x: auto` with visual swipe hints. |
| **Non-Technical Admin Updates** | Used Google Sheets embedding; no coding required for data updates. |
| **Multilingual without DB** | Built a client-side JSON dictionary system for instant text swapping. |
| **Header Obscuring Titles** | Applied `scroll-margin-top` in CSS for precise scroll positioning. |

---

## 🔮 Future Scope

- [ ] **Event Registration:** Google Forms integration for tour sign-ups.
- [ ] **Blog Section:** Articles about life in Verona.
- [ ] **Dark Mode:** Toggle for low-light reading.

---

## 👨‍💻 Author

**Prepared by:** Md. Nazibul Islam  
**Status:** ✅ Deployed & Live
