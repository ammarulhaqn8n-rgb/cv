<img align="right" width="170" src="images/ammar.jpg" alt="Ammar Ul Haq" />

# Ammar Ul Haq

**Senior iOS Developer &amp; Team Lead** — Pakistan · Remote

[Portfolio](https://ammarulhaq.me) ·
[Email](mailto:amarulhak@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/ammar-ul-haq-045051a1/) ·
[Medium](https://medium.com/@amarulhak) ·
[GitHub](https://github.com/ammarulhaqn8n-rgb) ·
[CV (PDF)](Ammar-Ul-Haq-CV.pdf)

> 10+ years building high-performance, native iOS apps — from real-time
> Bluetooth firing systems to social, fintech and enterprise products. Expert in
> Swift, SwiftUI, UIKit, BLE and real-time processing, with a track record of
> leading teams, owning the App Store release pipeline and shipping products
> people rely on every day.

<br clear="all" />

## About

Senior iOS Developer and Team Lead with a decade of production experience
designing, building and optimizing mobile applications for clients in the US, UK
and beyond. I own the full lifecycle — architecture, implementation, CI/CD, App
Store release and post-launch iteration — and I gravitate toward the hard
problems: real-time systems, BLE / hardware integration, and apps where
reliability is non-negotiable. I also build modern web front-ends (React /
Next.js) when a product needs a companion site.

## Tech Stack

**Languages:** Swift · Objective-C · TypeScript

**iOS &amp; UI:** SwiftUI · UIKit · Combine · Core Graphics · AVFoundation ·
Vision · RealityKit · Auto Layout

**Architecture:** MVVM · TCA (The Composable Architecture) · VIPER · Clean
Architecture · Swift Package Manager · protocol-oriented dependency injection

**Concurrency &amp; performance:** Swift Concurrency (async/await, actors) · GCD ·
Metal · Instruments (Time Profiler, Allocations, Leaks)

**Real-time &amp; hardware:** Core Bluetooth (BLE) · NFC · Multipeer
Connectivity · WebSockets

**Networking &amp; data:** REST · GraphQL · Alamofire · URLSession · Codable ·
Core Data · SwiftData · CloudKit · Firebase (Firestore)

**Measurement &amp; growth:** Firebase Analytics · Crashlytics · Remote Config ·
Cloud Messaging · AppsFlyer (attribution + deep linking) · Universal Links /
Dynamic Links

**CI/CD &amp; delivery:** Fastlane (`match`) · Bitrise · Xcode Cloud · App Store
Connect (phased release, TestFlight) · App Privacy labels · ATT

**Testing:** XCTest · Quick / Nimble · Snapshot testing · Xcode Previews

**Web (full-stack):** React · Next.js · TypeScript · Tailwind CSS · Node.js

**Tooling:** Git / GitHub · SwiftLint / SwiftFormat · CocoaPods · SPM · JIRA ·
Figma · Agile / Scrum

## Experience

| Period | Role | Company |
| --- | --- | --- |
| Nov 2018 – Present | Senior iOS Developer &amp; Team Lead | [IGNITE Firing Systems](https://www.ignitefiringsystems.com) (USA) · Remote |
| Aug 2017 – Oct 2018 | Senior iOS Developer | DPL · Pakistan |
| Nov 2016 – Sep 2017 | iOS Developer | Ifisol · Pakistan |
| Aug 2015 – Nov 2016 | iOS Developer (Part-time) | Binex Solutions · Pakistan |

---

### IGNITE Firing Systems — Senior iOS Developer &amp; Team Lead
**Nov 2018 – Present · USA · Remote** &nbsp;·&nbsp; **Impact:** &lt;300ms fail-safe firing latency · +30% client revenue from automation · led &amp; mentored the iOS team

As Senior iOS Developer and Team Lead I own the architecture and delivery of IGNITE, PyroCast and TNT — apps that fire real fireworks over Bluetooth with life-safety-grade reliability. I set technical direction, mentor the iOS team, run the CI/CD and App Store release pipeline, and work end-to-end with clients across US and Pakistan time zones.

**What I did**
- Lead and mentor a team of iOS developers — architecture decisions, code reviews and technical direction.
- Own the full lifecycle: design, implementation, testing, release and client communication.
- Define coding standards and a modular MVVM / TCA architecture in Swift Package Manager modules.
- Instrument, measure and grow the product with analytics, attribution and crash monitoring.

**Technical highlights**
- **Real-time BLE firing engine (sub-300ms):** Core Bluetooth (GATT) control of firing modules with sub-300ms precision and fail-safe misfire protection on a deterministic paused-timeline scheduler; Multipeer Connectivity / WebSocket fallbacks and background BLE state restoration.
- **SwiftUI + Combine → Swift Concurrency:** migrated core flows from UIKit, then to async/await and actors for compile-time concurrency safety; Core Graphics / Metal firing-sequence visualizer.
- **Analytics, attribution &amp; crash monitoring:** Firebase Analytics + Crashlytics (crash-free-users as a release gate); AppsFlyer for paid-social install attribution (Meta / TikTok) and OneLink deferred deep linking; Remote Config feature flags.
- **Revenue-driving automation:** designed automated firework sequencing that increased client revenue by ~30% and became a headline selling point.

**Engineering &amp; delivery**
- **Architecture:** Modular MVVM + TCA across SPM modules · protocol-oriented dependency injection · Combine → async/await + actors · feature-flagged rollouts (Remote Config).
- **3rd-party SDKs:** Firebase (Analytics, Crashlytics, Remote Config, Cloud Messaging) · AppsFlyer (attribution + OneLink) · StoreKit 2 / RevenueCat · Sentry · Lottie.
- **CI/CD &amp; Fastlane:** Fastlane lanes (beta, release, screenshots) + `match` code signing · Bitrise + Xcode Cloud → TestFlight · App Store Connect API key for headless build/version bumps · semantic versioning + changelog from PRs.
- **App Store config:** phased release &amp; staged rollout · TestFlight internal/external groups · App Privacy nutrition labels + ATT · entitlements/capabilities (background modes, push, associated domains / Universal Links) · App Review handling.
- **Code quality &amp; PRs:** trunk-based Git with short-lived branches · SwiftLint + SwiftFormat in CI · green-CI + peer approval before squash-merge · conventional commits · mentoring via reviews.
- **Testing &amp; performance:** XCTest + snapshot testing · Instruments (Time Profiler, Allocations, Leaks) · cold-launch/memory tuning · crash-free-users release gate.

**Stack:** Swift 5 · SwiftUI · UIKit · Combine · Swift Concurrency · Core Graphics · Core Bluetooth (BLE) · Multipeer Connectivity · WebSockets · MVVM · TCA · SPM · Firebase · Crashlytics · AppsFlyer · Universal Links · App Store Connect · TestFlight · Fastlane · Bitrise · Xcode Cloud · XCTest

---

### DPL — Senior iOS Developer
**Aug 2017 – Oct 2018 · Pakistan**

Worked on TalkBack, a social news app for trending local stories, and improved the Alif Elan app. Modernized the codebase toward MVVM and Codable networking, and integrated the real-time backend, push and deep-linking a social product needs.

**What I did**
- Develop features for a social news app — feeds, trending content and engagement flows.
- Integrate REST and real-time APIs and improve app performance.
- Collaborate on new features to boost user engagement and retention.

**Technical highlights**
- **Modern MVVM + Codable networking:** Swift 4 with MVVM and coordinator navigation; migrated from AFNetworking / RestKit toward Alamofire + URLSession with Codable, and Core Data caching (NSFetchedResultsController) for offline feeds.
- **Real-time content &amp; push:** Firebase (Firestore, Auth, Cloud Messaging) for live content and push notifications that re-engaged users.
- **Shareable deep links + retention:** Firebase Dynamic Links / Branch so shared links opened the exact story in-app; engagement funnels in Firebase Analytics.
- **Smooth, fast feeds:** profiled with Instruments and optimized scroll performance + async image loading (SDWebImage).

**Engineering &amp; delivery**
- **Architecture:** MVVM with coordinator navigation · Codable models · Core Data + NSFetchedResultsController.
- **3rd-party SDKs:** Firebase (Firestore, Auth, FCM, Analytics) · Branch / Dynamic Links · SDWebImage · Fabric Crashlytics.
- **CI/CD &amp; App Store:** Fastlane code signing + TestFlight · App Store Connect release management · CocoaPods.
- **Code quality &amp; process:** Git feature-branch workflow with peer PR reviews · SwiftLint · Agile sprints in JIRA.

**Stack:** Swift 4 · UIKit · MVVM · Alamofire · URLSession · Codable · Core Data · SDWebImage · Firestore · Firebase Auth · Cloud Messaging · Dynamic Links / Branch · Fastlane · TestFlight · CocoaPods

---

### Ifisol — iOS Developer
**Nov 2016 – Sep 2017 · Pakistan**

Developed the Attendo employee-management app, serving thousands of employees, and owned enterprise distribution end-to-end — provisioning, certificates, entitlements and reliable deployments across iOS updates.

**What I did**
- Build attendance and employee-management features for a large user base.
- Manage provisioning profiles for Ad Hoc, Enterprise and App Store builds.
- Keep the app stable across iOS releases with frequent, reliable deployments.

**Technical highlights**
- **Attendance at scale:** Swift 3 + UIKit with Core Data local storage and a REST sync layer (AFNetworking) keeping records consistent for thousands of employees.
- **Push &amp; background sync:** APNs push notifications for attendance reminders and background fetch.
- **Enterprise distribution ownership:** Ad Hoc, in-house Enterprise (.ipa) and App Store distribution — certificates, provisioning profiles and entitlements, with frequent OTA updates.
- **Crash &amp; usage monitoring:** Fabric Crashlytics and Google / Firebase Analytics.

**Engineering &amp; delivery**
- **Architecture:** MVC / UIKit + Core Data · REST sync with conflict handling · APNs + background fetch.
- **App Store &amp; distribution:** Ad Hoc / Enterprise / App Store builds · certificates, provisioning &amp; entitlements · frequent OTA deployments.
- **SDKs &amp; tooling:** AFNetworking · Fabric Crashlytics · Google/Firebase Analytics · Fastlane (emerging) · CocoaPods · Git · Agile.

**Stack:** Swift 3 · Objective-C · UIKit · Storyboards / XIBs · Auto Layout · Core Data · AFNetworking · REST · APNs · Fabric Crashlytics · CocoaPods

---

### Binex Solutions — iOS Developer (Part-time)
**Aug 2015 – Nov 2016 · Pakistan**

Contributed to several business apps, integrating ad networks and REST APIs and maintaining shared codebases. Where I built the iOS fundamentals — UIKit, Auto Layout, memory management and clean, HIG-compliant UI — that everything since has been built on.

**What I did**
- Build and maintain features across multiple business apps.
- Integrate third-party SDKs (ad networks, REST APIs).
- Follow Apple Human Interface Guidelines and Agile practices, using Git for version control.

**Technical highlights**
- **Objective-C → Swift transition:** Objective-C and early Swift (2.x / 3), UIKit with Storyboards / XIBs and Auto Layout, ARC memory management.
- **Monetization &amp; integrations:** AdMob and Chartboost; REST via AFNetworking; Core Data persistence.
- **Fundamentals &amp; workflow:** CocoaPods, Git (feature branches + reviews), Apple HIG, Agile/Scrum, early crash reporting (Fabric) and analytics (Flurry / Google Analytics).

**Stack:** Objective-C · Swift 2/3 · UIKit · Storyboards / XIBs · Auto Layout · AFNetworking · REST · Core Data · AdMob · Chartboost · CocoaPods · Git

## Education

| Period | Qualification | Institution |
| --- | --- | --- |
| 2012 – 2016 | BSCS — Bachelor of Computer Science | SZABIST University · Islamabad, Pakistan |

## Selected Apps

### IGNITE Firing Systems

<img src="images/projects/ignite.png" width="480" alt="IGNITE Firing Systems" />

[App Store](https://apps.apple.com/us/app/ignite-firing-systems/id1544453017) · [Website](https://www.ignitefiringsystems.com)

Smartphone-controlled fireworks firing system with life-safety-grade reliability. **Rated 4.9** on the App Store.
- **Real-time BLE engine:** Core Bluetooth (GATT) control of firing modules with **sub-300ms** latency, fail-safe handshakes and misfire guards.
- **Deterministic scheduling:** paused-timeline show engine; Multipeer Connectivity / WebSocket fallback for multi-module shows and background BLE state restoration.
- **Architecture:** SwiftUI + Combine → Swift Concurrency; modular **MVVM / TCA** in Swift Package Manager modules; Core Graphics / Metal firing-sequence visualizer.
- **Measurement &amp; delivery:** Firebase Analytics + Crashlytics, AppsFlyer attribution, Remote Config flags; Fastlane + Xcode Cloud → TestFlight, App Store Connect phased releases.

### PyroCast

<img src="images/projects/pyrocast.png" width="120" alt="PyroCast" />

[App Store](https://apps.apple.com/us/app/pyrocast/id1583221898)

Companion firing-system app in the IGNITE family for real-time control and show sequencing.
- Shares the **Core Bluetooth** real-time engine; low-latency module control and cue playback.
- Swift · **MVVM**; offline-capable show storage and reliable reconnection handling.

### Social Detox

<img src="images/projects/social-detox.png" width="480" alt="Social Detox" />

[App Store](https://apps.apple.com/pk/app/social-detox/id6497330800) · [Website](https://socialdetox.auraapps.online)

Digital-wellbeing app that helps people reclaim focus and build healthier screen-time habits.
- Built on Apple's **Screen Time / Family Controls** (DeviceActivity + ManagedSettings) to block distracting apps and enforce focus schedules.
- **SwiftUI**; App Groups to share state with the shield extension; local notifications for focus sessions and usage insights.
- Companion marketing site tuned for SEO and conversion.

### Attendo Plus

<img src="images/projects/attendo-plus.png" width="480" alt="Attendo Plus" />

[App Store](https://apps.apple.com/us/app/attendo-plus/id1260460403) · [Website](https://www.attendoplus.com)

Attendance management for organizations — native iOS app plus a web dashboard.
- Check-ins, live reports and rosters kept in sync via **REST**; **Core Data** offline cache with background sync.
- **APNs** push reminders, role-based access, and CSV/report exports for admins.
- Web dashboard companion for real-time monitoring across teams.

### Spent

<img src="images/projects/spent.png" width="480" alt="Spent" />

[App Store](https://apps.apple.com/kz/app/spent-speak-it-its-saved/id6779672290) · [Website](https://www.spent.auraapps.online)

Voice-first personal expense tracking with smart budgeting.
- **Speech framework / Siri** voice capture — "speak it, it's saved" — with smart categorization.
- **SwiftUI + Swift Charts** for spend insights; Core Data / iCloud persistence and budget alerts.
- Product landing page with SEO and App Store deep links.

### GuardsPro

<img src="images/projects/guardspro.png" width="480" alt="GuardsPro" />

[App Store](https://apps.apple.com/us/app/guardspro-security-guard-app/id1238303335) · [Website](https://www.guardspro.com)

Security workforce management platform used by security companies in the field.
- **Live GPS** guard-tour tracking with Core Location + geofencing and checkpoint scans.
- **Offline-first** incident reporting (photos, notes) synced to the backend when connectivity returns.
- Scheduling, real-time dashboards and multi-role access across app and web.

### Appic Fleet

<img src="images/projects/appic-fleet.png" width="120" alt="Appic Fleet" />

[App Store](https://apps.apple.com/us/app/appic-fleet/id6498920162)

Fleet-management app for logistics and vehicle tracking.
- **MapKit + Core Location** live vehicle tracking, routes and trip logging.
- REST backend integration with efficient background location updates.

### Roamie Travel

<img src="images/projects/roamie-travel.png" width="480" alt="Roamie Travel" />

[Website](https://roamietravel.com)

AI trip-planning web app — trips, expenses and documents in one place.
- **React / Next.js + TypeScript** SPA with server-prerendered, SEO-optimized marketing pages.
- AI-assisted itinerary planning, expense tracking and shared trip ledgers; deferred deep links to the mobile app.

### DietPal

<img src="images/projects/dietpal.png" width="480" alt="DietPal" />

[Website](https://dietpal.auraapps.online)

Nutrition companion — describe what you ate and it does the USDA math.
- Voice/text meal logging that transcribes speech, looks it up in **USDA FoodData Central**, and stores calories &amp; macros.
- **Privacy-first:** the recording is deleted as soon as the text is captured.
- **Next.js** static export with trailing-slash routes, cached assets and a fast, mobile-first UI.

## Contact

- **Email:** amarulhak@gmail.com
- **Phone:** +92 331 5145607
- **Portfolio:** https://ammarulhaq.me
- **LinkedIn:** https://www.linkedin.com/in/ammar-ul-haq-045051a1/
- **Location:** Pakistan · available remote worldwide

<sub>This CV lives on GitHub. An interactive version with per-role deep dives is at
<a href="https://ammarulhaq.me/#career">ammarulhaq.me</a>.</sub>
