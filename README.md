<!-- مصدر ريدمي بروفايل جيت هب العام (saqrelfirgany/saqrelfirgany).
     الملف ده هو المصدر. المنشور نسخة منه في github-profile/README.md.
     عدّلت هنا؟ انسخ وادفع من جوه github-profile — كوميت البراند مابيوصلش
     للبروفايل العام. التفاصيل في RULES.md تحت قاعدة ٢.
     الأرقام كلها من canon.yml. آخر مزامنة: 2026-08-05. -->

<div align="center">

<img width="1584" height="396" alt="2_cover_LinkedIn_1584x396" src="https://github.com/user-attachments/assets/c147379c-1ac3-465b-a65b-aba06d235dd1" />

<br/><br/>

<a href="mailto:saqrelfirgany@gmail.com"><img src="https://img.shields.io/badge/Email-0B1120?style=flat-square&logo=gmail&logoColor=EA4335&labelColor=0B1120" /></a>
<a href="https://www.linkedin.com/in/saqrelfirgany/"><img src="https://img.shields.io/badge/LinkedIn-0B1120?style=flat-square&logo=linkedin&logoColor=0A66C2&labelColor=0B1120" /></a>
<a href="https://dev.to/saqrelfirgany"><img src="https://img.shields.io/badge/dev.to-0B1120?style=flat-square&logo=devdotto&logoColor=white&labelColor=0B1120" /></a>
<a href="https://x.com/saqrelfirgany"><img src="https://img.shields.io/badge/X-0B1120?style=flat-square&logo=x&logoColor=white&labelColor=0B1120" /></a>
<a href="https://www.facebook.com/saqrelfirgany"><img src="https://img.shields.io/badge/Facebook-0B1120?style=flat-square&logo=facebook&logoColor=0866FF&labelColor=0B1120" /></a>
<a href="https://www.instagram.com/saqrelfirgany"><img src="https://img.shields.io/badge/Instagram-0B1120?style=flat-square&logo=instagram&logoColor=E4405F&labelColor=0B1120" /></a>
<a href="https://www.threads.net/@saqrelfirgany"><img src="https://img.shields.io/badge/Threads-0B1120?style=flat-square&logo=threads&logoColor=white&labelColor=0B1120" /></a>
<a href="https://wa.me/201025592065"><img src="https://img.shields.io/badge/WhatsApp-0B1120?style=flat-square&logo=whatsapp&logoColor=25D366&labelColor=0B1120" /></a>

</div>

<br/>

> **Ahmed ElFirgany · Software Engineer · Mobile Expert**
>
> Senior Flutter Developer.
>
> 5+ years building iOS and Android apps that shipped. **18+ apps · 600K+ downloads · 5 countries.**
>
> Clean Architecture and BLoC. A mobile team of three.

<br/>

## 🛠️ Tech Stack

<div align="center">

| **Category** | **Technologies** |
|:---:|:---|
| **Languages** | ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| **Frameworks** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) |
| **AI-Assisted Dev** | `Claude Code` `MCP (Model Context Protocol)` `Figma-to-Flutter` `AI Pair-Programming` `Prompt Engineering` |
| **Architecture** | `Clean Architecture` `MVVM` `Repository Pattern` `Modular Design` `SOLID` |
| **State Management** | `BLoC` `Cubit` `Provider` `Riverpod` `GetX` |
| **Backend & APIs** | `REST` `GraphQL` `WebSocket` `Dio` `Retrofit` `JWT` `OAuth` |
| **Firebase** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) Auth · Firestore · Storage · Analytics · FCM |
| **Database** | `SQLite` `Hive` `SQL` `Secure Storage` |
| **Payments** | `Stripe` `PayPal` `Mada` `Visa/Mastercard` `In-App Purchases` |
| **Maps & Location** | `Google Maps API` `Geofencing` `Clustering` `Route Planning` |
| **Security** | `Biometric Auth` `SSL Pinning` `Encryption` `RBAC` `Token Management` |
| **CI/CD** | `GitHub Actions` `Fastlane` `Codemagic` `Firebase Distribution` |
| **Testing** | `Unit` `Widget` `Integration` `E2E` `TDD` `Mockito` |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white) ![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |

</div>

<br/>

---

## 💼 Work Experience & Projects

### TechnoIsland — Senior Flutter Developer

> **Apr 2025 – Present** · Full-time · Cairo, Egypt
>
> Three apps on both stores in 14 months · `Clean Architecture` · `Offline-first` · `RBAC`

I own the mobile codebase for three products here. I also wrote the Flutter standard the team builds on.

<details>
<summary>🏥 <b>Dacttra — Clinic Management</b> — the app clinic staff run the day on</summary>

<br/>

Clinic staff and owners run the day from the phone.

Appointments · patient records · billing · branches · subscriptions.

**What I built:**
- Role-based access across **17 modules × 5 actions**, with the role switchable at runtime
- Multi-branch isolation — every request carries the active branch and its timezone
- Arabic **RTL invoices rendered as PDF on the device**, no server round-trip
- A day board for the waiting list, and appointment editing without a reload

**Hardest part:** switching role or branch changes what the whole app may read and write. Doing it without a restart meant one permission source, read by every screen.

**Scale:** `203 feature modules` · `186 endpoints` · `280 tests`

**Tech:** `Flutter` `Clean Architecture` `BLoC` `GetIt` `Dio` `RBAC` `PDF`

[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/us/app/id6763802371)

</details>

<details>
<summary>🩺 <b>Dacttra — Your Health Partner</b> — the patient side</summary>

<br/>

Patients search for doctors and clinics, read ratings, browse specialties, and book an appointment.

**What I built:**
- Search and filtering over doctors, centres, and specialties
- Booking against live availability, with the clinic's own timezone
- A broker for the **WHO ICD-11** code service. No key ships inside the app

**Hardest part:** the same appointment slot is visible to many patients at once. The check that it is still free happens on the server, never on the phone.

**Scale:** `51 endpoints` · `56 tests`

**Tech:** `Flutter` `Clean Architecture` `BLoC` `Dio` `Firebase`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.dacttra.platform) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/us/app/id6756008573)

</details>

<details>
<summary>⏱️ <b>KronosPay</b> — attendance, rostering, and payroll</summary>

<br/>

Teams clock in and out, managers build rosters, and payroll reads the result. It works on site, remote, and across locations.

**What I built:**
- **A punch queue that works with no signal.** SQLite holds it, and a background isolate uploads on reconnect
- Partial-success reconciliation: some punches upload, some fail, and the queue keeps the failures
- **A trusted time source.** The server clock decides, so the phone clock changes nothing
- Geofencing where the site radius comes from the server, not the app

**Hardest part:** a punch is a payroll record. It cannot be lost, duplicated, or timed by a clock the user controls.

**Scale:** `50 endpoints` · `94 tests`

**Tech:** `Flutter` `SQLite` `WorkManager` `Geofencing` `Offline-first` `BLoC`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.innovative.kronospay) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/us/app/id6755912599)

</details>

<details>
<summary>📐 <b>The engineering standard</b> — written once, followed by the team</summary>

<br/>

**What I wrote:**
- A **589-line Flutter project blueprint** — layering, naming, folder shape, and what belongs where
- Team standards for code review, pull requests, naming, and documentation
- Architecture decision records, so a choice is written down with its reason

The same structure is now used in a repo I do not maintain. That is the part I am proud of.

</details>

---

### Smartware — Senior Flutter Developer

> **Jul 2024 – Present** · Freelance · Remote · Riyadh, Saudi Arabia
>
> Maintenance and rebuild on live enterprise apps, then two new apps from scratch

<details>
<summary>💼 <b>TBS Self Services</b> — employee HR portal</summary>

<br/>

Employees request leave, loans, and expense claims, clock in by location, and download payslips. Managers approve from the same app.

**What I did:** I joined a live codebase, not a new one.
- Built parts of the request forms and their validation
- Fixed defects across attendance, requests, and notifications
- Raised the Android target API and cleaned up what the upgrade broke
- Improved code health in the areas I touched

**Tech:** `Flutter` `BLoC` `GetIt` `Odoo` `Biometrics` `Localization`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=sa.com.takamoltbs.selfservices) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/sa/app/id6447533663)

</details>

<details>
<summary>📊 <b>TBS EPM</b> — portfolio and project reporting (tablet)</summary>

<br/>

Portfolio and programme managers read the dashboards and reports.

Project status · risks · issues · deliverables · budget · scheduling.

Landscape only, built for tablet.

**What I did:**
- Built parts of the reporting modules and their paging
- Fixed defects and restored a codebase that no longer ran
- Improved code health in the areas I touched

**Tech:** `Flutter` `BLoC` `fl_chart` `Syncfusion` `Pagination` `Tablet UI`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=sa.com.takamoltbs.epm) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/sa/app/id6450037705)

</details>

<details>
<summary>🚚 <b>Two companion apps</b> — under store review, so no name yet</summary>

<br/>

A customer app and a driver app for one Saudi platform. They share one live order lifecycle. Written from scratch. **In store review now**, so the product stays unnamed here — the engineering does not.

**What I built:**
- **A token lifecycle state machine.** One refresh at a time, and every waiting request resolves off it
- **Real-time over SignalR with transport fallback** — WebSockets, then server-sent events, then long polling
- **Background GPS in its own isolate**, with its own HTTP client. It stops itself when the session ends
- Live route and distance on the map, biometric lock, and Arabic as the primary language

**Hardest part:** two apps must agree on one order state, over a network that drops. Order status moves through seven steps. Both sides have to land on the same one.

**Scale:** `71 screens` · `120 endpoints` · `~175K lines` · the token service alone has `22 tests`

**Tech:** `Flutter` `SignalR` `Google Maps` `Geolocator` `Background Service` `Clean Architecture` `BLoC`

</details>

---

### Aqarmap — Senior Flutter Developer

> **Jan 2023 – Mar 2025** · Full-time · Hybrid · Cairo, Egypt
>
> Egyptian real estate marketplace · `500K+ downloads` · `200K+ listings` · `~30% faster load times`

<details>
<summary>🏘️ <b>Aqarmap Egypt</b> — Real Estate Marketplace &nbsp;|&nbsp; 500K+ Downloads</summary>

<br/>

Egyptian real estate marketplace with **200K+ property listings** and **500K+ downloads on Google Play**. Buyers search, compare, and contact verified agents.

**What I Built:**
- Advanced search engine with **15+ dynamic filters** (price, location, area, bedrooms, amenities)
- Interactive map with **property clustering, heat maps**, and neighborhood analytics
- **~30% faster** load times through performance optimization

**Tech:** `Flutter` `BLoC` `Clean Architecture` `Google Maps API` `REST APIs` `Firebase Analytics` `Image Caching` `Lazy Loading`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.aqarmap.android) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/app/id642633889)

</details>

<details>
<summary>🏘️ <b>Aqarmap KSA</b> — Saudi Property Marketplace</summary>

<br/>

Real estate platform for the **Saudi Arabian market**. It runs in Arabic and English, and follows Saudi property regulations.

**What I Built:**
- Shared codebase with Aqarmap Egypt, split by market
- **Hijri calendar** integration for contract dates
- Currency conversion and **investment ROI calculators**
- Saudi Ejar platform integration for official rental contracts
- Full **bilingual UI (Arabic/English)** with RTL layout support

**Tech:** `Flutter` `BLoC` `Clean Architecture` `Localization (l10n)` `RTL Support` `REST APIs` `Firebase`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.aqarmap.invest) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/app/id6470154017)

</details>

<details>
<summary>📊 <b>Aqarmap CRM (AM Live)</b> — Enterprise CRM &nbsp;|&nbsp; 100K+ Leads/Month</summary>

<br/>

CRM for real estate companies and brokers. Agents manage leads, listings, viewings, and sales reports.

**What I Built:**
- Complete **5-stage lead pipeline** (New → Contacted → Qualified → Negotiation → Closed)
- **Offline mode** — agents work with no internet, and data syncs when it returns
- Real-time notifications for lead activities and client inquiries
- Calendar sync with **automated follow-up reminders**
- Analytics dashboard with performance metrics and conversion rates

**Tech:** `Flutter` `BLoC` `Clean Architecture` `SQLite` `Push Notifications` `Firebase Messaging` `Background Services`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.project.aqarmap.crm) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/eg/app/id1271197604)

</details>

---

### NamaaIT — Flutter Developer & Team Lead

> **Dec 2021 – Dec 2022** · Full-time · Cairo, Egypt
>
> Led a team of 3 · `7 apps shipped` · `4 countries` · Mentored juniors to mid-level · Scalable architecture

<details>
<summary>💊 <b>Adam Pharmacy</b> — Online Pharmacy & Healthcare</summary>

<br/>

Saudi online pharmacy — home delivery, camera-based prescription reading, and medication reminders.

**What I Built:**
- Camera reading of handwritten prescriptions, with a pharmacist confirm step
- Image pre-processing so a phone photo is readable before it is parsed
- Live order tracking and medication reminders
- Payment gateway, push notifications, and delivery integration

**Tech:** `Flutter` `Firebase` `REST APIs` `Payment Gateway` `OCR` `Push Notifications` `Google Maps`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.namaait.adampharmacy) [![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=app-store&logoColor=white)](https://apps.apple.com/app/id1672276218)

</details>

<details>
<summary>👕 <b>ALNASSER</b> — Fashion & Sports Retail (Kuwait)</summary>

<br/>

Kuwaiti fashion and sports retail brand. Shoppers earn loyalty points, and campaign links open the right product.

**What I Built:**
- Product catalog with advanced filtering and size guide
- Loyalty points system and exclusive member discounts
- Checkout with multiple payment methods
- Deep linking for marketing campaigns

**Tech:** `Flutter` `Provider` `REST APIs` `Payment Integration` `Deep Linking` `Firebase Analytics`

[![Google Play](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.namaait.alnasser)

</details>

<details>
<summary>🚗 <b>BizBuradayız</b> — On-Demand Services (Turkey)</summary>

<br/>

Turkish on-demand platform — connecting customers with professionals across home, beauty, car, and delivery services.

**What I Built:**
- **Dual-app system** (Customer + Service Provider)
- Real-time booking with instant provider matching
- Live location tracking for service-provider arrival
- In-app chat and **Pusher real-time** order updates
- Rating & review system with photo uploads

**Tech:** `Flutter` `BLoC` `Pusher` `Google Maps` `Real-time Tracking` `Firebase Messaging` `In-App Chat`

[![Customer App](https://img.shields.io/badge/Customer_App-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.namaait.bizburadayiz) [![Driver App](https://img.shields.io/badge/Driver_App-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.namaait.bizburadayiz.driver)

</details>

<details>
<summary>👗 <b>De'Odela</b> — Fashion E-commerce</summary>

<br/>

Egyptian fashion platform — modest wear, abayas, and hijabs. **AR virtual try-on** and express delivery.

**What I Built:**
- High-quality image galleries with AR try-on for accessories
- Personalized style recommendation engine
- Size prediction based on purchase history
- Same-day express delivery integration

**Tech:** `Flutter` `Provider` `AR Integration` `REST APIs` `Firebase` `Payment Gateway`

_The owner has since taken this one down, so there is nothing left to link._

</details>

---


### Military Service

> **Nov 2020 – Nov 2021** · Egypt

---

### Freelance — Android Developer (Kotlin)

> **Jul 2020 – Oct 2020** · Freelance · Cairo, Egypt
>
> First paid development work. Native Android in Kotlin, before Flutter.

---

## 🏗️ Architecture Deep Dive

<details>
<summary><b>📐 Clean Architecture — How I Structure Apps</b></summary>

<br/>

```
📱 Presentation Layer
│ ├── Screens / Pages
│ ├── Widgets
│ └── BLoC / Cubit (State Management)
│
💼 Domain Layer
│ ├── Entities
│ ├── Use Cases
│ └── Repository Interfaces
│
🗄️ Data Layer
├── Models
├── Repository Implementations
├── Data Sources (Remote / Local)
└── Mappers
```

**What it buys me:** a new client app starts wired. DI, routing, theming, and tests.

</details>

<details>
<summary><b>🤖 AI-Assisted Development — How I Work</b></summary>

<br/>

I use AI into my day-to-day engineering to move faster **without** sacrificing code quality:

- **Claude Code (CLI)** — automating boilerplate, tests, refactors, and documentation
- **MCP (Model Context Protocol)** integrations, including **Figma-to-Flutter**. It turns a design file into Flutter UI that matches the project architecture
- **AI-assisted delivery** — I use Claude Code and MCP daily for boilerplate, tests, and refactors
- AI-assisted **code review and rapid prototyping**

</details>

<details>
<summary><b>🔄 State Management — When to Use What</b></summary>

<br/>

| Solution | Best For | My Usage |
|:---|:---|:---|
| **BLoC / Cubit** | Complex apps with heavy business logic | Primary choice ⭐ |
| **Provider** | Medium-sized apps, moderate complexity | Secondary |
| **Riverpod** | Type-safety & testability requirements | When needed |
| **GetX** | Rapid prototyping, simple apps | Quick MVPs |

</details>

<details>
<summary><b>🔥 Advanced Techniques I Use</b></summary>

<br/>

Custom Painting & Canvas · Platform Channels (iOS/Android native) · Isolates & Multithreading · Custom Render Objects · Complex Animation Sequences · Stream Management & Reactive Programming · Code Generation (build_runner, freezed, json_serializable) · Widget Tree Optimization

</details>

---

## 🌟 Open Source

### [Flutter Enterprise Template](https://github.com/saqrelfirgany/flutter_template)

> The starter I build new client apps on — three-layer Clean Architecture, BLoC, DI, tests

![Stars](https://img.shields.io/github/stars/saqrelfirgany/flutter_template?style=flat-square&color=f59e0b) ![Forks](https://img.shields.io/github/forks/saqrelfirgany/flutter_template?style=flat-square&color=3b82f6) ![Issues](https://img.shields.io/github/issues/saqrelfirgany/flutter_template?style=flat-square&color=ef4444)

**Includes:** Clean Architecture (3-Layer) · BLoC · Dependency Injection (GetIt) · Dio with Interceptors · Multi-language (i18n) · Dark Mode · Testing Setup · Code Generation (Freezed, Json)

```bash
git clone https://github.com/saqrelfirgany/flutter_template.git
cd flutter_template && flutter pub get
flutter pub run build_runner build --delete-conflicting-outputs
flutter run
```

---

## 🎓 Education & Certifications

| | Details |
|:---|:---|
| 🎓 **B.Sc. Computer Science — IT** | Sinai University, Al-Arish, Egypt (2016–2020) · GPA: 3.16/4.0 · Graduation Project: **A+** |
| 🎖️ **Military Service** | Egyptian Armed Forces (Nov 2020 – Dec 2021) |
| 📜 **Flutter Development Bootcamp** | Udemy (2021) |
| 📜 **One Million Arab Coders** | Udacity / MBRGI — Data Analysis Track (2019) |

---

<div align="center">

<img width="2000" height="208" alt="footer" src="https://github.com/user-attachments/assets/1a280d9f-f45e-4f9b-9948-db79dee28416" />

</div>
