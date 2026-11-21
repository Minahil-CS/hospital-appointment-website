# 🏥 Aetheris Medical Center — Hospital Appointment Booking System

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Design-Fully%20Responsive-10B981?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A clean, modern, and fully responsive **Hospital Appointment Website** engineered to streamline patient scheduling, clinical department exploration, and specialist discovery. Built with semantic HTML5, modern CSS3, and modular Vanilla JavaScript with zero external runtime dependencies.

---

## 🌐 Live Demo

🔗 **Live Website:** `https://<your-username>.github.io/hospital-appointment-website/`

---

## ✨ Key Features

- **🚨 24/7 Emergency Top Bar & Hero Overview:** Displays critical trauma hotline details, hospital trust metrics, clinic operating hours, and quick-action appointment triggers.
- **🩺 Clinical Departments & Services Catalog:** Interactive cards across 6 medical specialties (*Cardiology, Neurology, Pediatrics, Orthopedics, Dermatology, General Medicine*) displaying consultation fees, estimated session durations, and direct department-level booking.
- **🔍 Real-Time Doctor Search & Department Filtering:** Instant search by specialist name or qualification combined with category filter pills, displaying experience, ratings, and available clinic schedules.
- **📅 Smart Appointment Scheduling Modal:**
  - Dynamic department-to-doctor dependency filtering.
  - Interactive time-slot pill selection with visual active states.
  - Client-side form validation for patient contact details and appointment dates.
- **🧾 Instant Booking Confirmation & Unique Reference ID:** Generates an automated digital appointment receipt with a unique tracking code (`AMC-XXXXXX`) and one-click clipboard copy functionality.
- **💾 Persistent Appointment Manager (`localStorage`):** Patients can view active and cancelled bookings anytime via the **My Appointments** drawer and cancel upcoming visits with confirmation safeguards.
- **📱 Mobile-First Responsive UI:** Seamlessly adapts across desktop monitors, tablets, and mobile viewports.

---

## 🛠️ Tech Stack & Architecture

| Layer | Technology / Approach |
| :--- | :--- |
| **Structure** | Semantic HTML5 (`<header>`, `<nav>`, `<section>`, `<dialog>`/`modal` patterns) |
| **Styling** | Modern CSS3 (CSS Custom Properties, Flexbox, CSS Grid, Smooth Transitions) |
| **Interactivity** | Vanilla JavaScript (ES6+ DOM Manipulation, Event Delegation, Dynamic Rendering) |
| **State Persistence** | Browser `localStorage` API for client-side booking history |
| **Architecture** | Single-file self-contained architecture (`index.html`) for instant deployment |

---

## 📂 Project Structure

```text
hospital-appointment-website/
│
├── index.html          # Complete application (HTML structure, embedded CSS, and JS logic)
└── README.md           # Project documentation and setup guide
