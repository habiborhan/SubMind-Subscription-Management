  SubMind – Subscription Management System

> **MIS 321 – Phase 1 & Phase 2 Project**  
> A smart, AI-powered subscription management system designed for the Turkish market.

---

##  Team Members

| Name |
|------|
| Fatih Mehmet AKBIYIK |
| Kaan BIÇAKCI |
| Faruk GÜNDOĞDU |
| Habib ORHAN |
| Yusuf SÜSİN |

---

##  Project Overview

**SubMind** is a mobile-first subscription management application that helps users track, manage, and optimize all their digital subscriptions in one place.

In today's digital age, people juggle multiple subscriptions — Netflix, Spotify, Amazon Prime, gym memberships, and more. SubMind solves the most common pain points:

-  Forgetting payment dates
-  Missing price increases
-  Paying for unused subscriptions after free trials end
-  Lack of visibility over total monthly subscription costs

SubMind is specifically designed for the **Turkish market**, with full integration into Turkish banking infrastructure, e-invoice systems, and compliance with **KVKK & GDPR** regulations.

---

##  Key Features

| Feature | Description |
|--------|-------------|
|  Subscription Dashboard | View all subscriptions in one place with renewal dates and costs |
|  Smart Notifications | Alerts for upcoming payments, free trial endings, and price changes |
|  AI Analytics | Spending insights, unused subscription detection, and recommendations |
|  Bank Integration | Auto-detection of subscriptions via Turkish Open Banking API |
|  E-Invoice Integration | Verified invoice tracking through the national e-invoice system |
|  Monthly Reports | Visual spending breakdowns by category (Entertainment, Productivity, etc.) |
|  Security | Two-factor authentication, TLS encryption, KVKK & GDPR compliance |

---

##  System Architecture

SubMind is built around **6 core processes**:

1. **1.0** – Manage User Accounts & Authentication
2. **2.0** – Manage Subscriptions & Preferences
3. **3.0** – Handle Payments & Invoices
4. **4.0** – Generate & Deliver Notifications
5. **5.0** – Analyze Usage & AI Insight
6. **6.0** – Management Reporting & Configuration

**External Entities:** User · Bank/Open Banking API · Service Providers (Netflix, Spotify, Amazon…) · AI Module · Accounting · Notification Service · Authentication/Security · Management

**Data Stores:** D1 User Accounts · D2 Subscriptions · D3 Budget & Notification Preferences · D4 Payments & Invoices · D5 Usage Logs · D6 Reports & Analytics

---

## 📁 Project Documents

| Document | Description |
|----------|-------------|
| [`docs/SubMind_Phase1_Report.pdf`](docs/SubMind_Phase1_Report.pdf) | Preliminary investigation report — SWOT, competitor analysis, interviews & survey results |
| [`docs/SubMind_Context_Diagram.pdf`](docs/SubMind_Context_Diagram.pdf) | Level-0 context diagram showing system boundaries |
| [`docs/SubMind_Diagrams.pdf`](docs/SubMind_Diagrams.pdf) | DFD Diagram 0 and child diagrams (2.0, 3.0, 5.0) |
| [`docs/SubMind_Data_Dict.pdf`](docs/SubMind_Data_Dict.pdf) | Full data dictionary — entities, flows, processes, data stores & elements |
| [`docs/SubMind_UI_NW.pdf`](docs/SubMind_UI_NW.pdf) | UI mockups — wireframes and high-fidelity mobile screens |

---

##  Market Research Highlights

A survey of **102 participants** (primarily students and young professionals) revealed:

- **60.8%** struggle to track price increases across their subscriptions
- **49%** forget to cancel unused subscriptions
- **84.3%** use video streaming services; **80.4%** use music subscriptions
- **46%** spend over **1,000 TL/month** on subscriptions
- **58.8%** want subscription comparison & alternative plan suggestions
- **58.8%** prefer a **mobile app** (iOS/Android)

---

##  Proposed Tech Stack

- **Mobile:** Flutter (iOS + Android from single codebase)
- **Backend:** Firebase (BaaS — auto-scaling, real-time database)
- **Security:** TLS encryption, Firebase Rules (role-based access), 2FA
- **Data:** Firestore (cloud-based, multi-device access)

---

##  UI Screens

The application includes the following screens:

- **Welcome / Login Page** — App introduction with "Get Started" CTA
- **Homepage / Dashboard** — Total spend, active subscriptions, upcoming renewals
- **Subscription Details Page** — Plan info, billing cycle, deduction history
- **AI Analytics Page** — Spending donut chart by category + AI recommendations
- **Add Subscription Page** — Service selection, billing config, reminder toggle
- **Account / Profile Page** — Settings, payment methods, notification preferences

---

##  References

- Tilley, S., & Rosenblatt, H. (2020). *Systems Analysis and Design* (12th ed.). Cengage Learning.
- User Survey — Google Forms, October 2025 (n=102)

---

*This project was developed as part of the MIS 321 course. All analyses, designs, and written content were produced by the project team.*
