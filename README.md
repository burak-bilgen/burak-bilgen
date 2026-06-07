# Hi there, I'm Burak! 👋
### Senior iOS Developer  <img src="https://img.shields.io/badge/-Apple-000000?style=flat-square&logo=apple&logoColor=white" height="18" alt="Apple" />

<div align="center" style="background-color: #000000; border-radius: 8px; padding: 10px;">
  <img src="hello.gif" width="60%" alt="Hello in different languages" />
</div>

An experienced iOS developer with over **four years of experience** building mobile apps for fintech and cryptocurrency. Skilled at designing high‑performance trading interfaces, KYC verification flows, multi‑currency wallets and real‑time data streams. Values modular architectures with Swift, SwiftUI and Combine, writes clean code and always balances performance with security. Continues to refine product design and user experience through side projects.

* 🏗️ **Architecture & Concurrency:** Modular architectures, protocol-oriented design, structured concurrency.
* 🔒 **Fintech Security:** SSL pinning, secure storage, real-time WebSocket communication, KYC compliance.
* 🧪 **Engineering Practices:** Memory profiling, Swift 6 Strict Concurrency, TDD, CI/CD automation.

---

## 🛠️ Technical Toolbox

| Category | Technologies & Frameworks |
| :--- | :--- |
| **Languages & Frameworks** | `Swift` • `SwiftUI` • `UIKit` • `Combine` • `RxSwift` |
| **Architectures** | `MVVM-C` • `VIPER` • `Clean Architecture` • `Unidirectional Data Flow` • `Modular Monolith` |
| **Networking & Data** | `WebSockets` • `REST APIs` • `Core Data` • `Realm` • `Firebase` |
| **Security & Analytics** | `SSL Pinning` • `Keychain` • `Secure Storage` • `MASAK Compliance` • `Firebase Crashlytics` |
| **DevOps & Tools** | `Git` • `Xcode` • `Xcode Cloud` • `CircleCI` • `SPM` • `CocoaPods` • `Proxyman` |

---

## 📊 GitHub Analytics

<p align="center">
  <a href="https://github.com/burak-bilgen">
    <img height="180em" src="https://github-readme-stats-swart-seven.vercel.app/api?username=burak-bilgen&show_icons=true&theme=dark&hide_border=true" alt="GitHub Stats" />
    <img height="180em" src="https://github-readme-stats-swart-seven.vercel.app/api/top-langs?username=burak-bilgen&layout=compact&langs_count=8&theme=dark&hide_border=true" alt="Top Languages" />
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=burak-bilgen&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=burak-bilgen&theme=github-dark&hide_border=true" width="95%" alt="Activity Graph"/>
</p>

---

## 🗂️ Projects

### 1. 🌤️ ForeWiz — Personal Weather Decision Assistant
> `v2.0` • `📱 iOS 17+` • `🍏 WeatherKit` • `🧪 Decision Engines`

> **Focus:** Weather Intelligence, Decision Engines, Route Planning.

ForeWiz transforms Apple WeatherKit data into personalized, actionable decisions. It doesn't just show the weather — it tells you when to go out, what to wear, and how it might affect your health.

* **Architecture:** `Clean Architecture` + `MVVM-C` with Swift actors and protocol-driven repositories.
* **Highlights:**
  * **Decision Engine** — Scores outdoor conditions (0–100) with activity windows, outfit recommendations, and health impact analysis (migraine, sleep, joints, respiratory, stamina).
  * **WizPath** — Climate-aware route planning SPM package with multi-modal routing (driving, cycling, walking, EV), weather-coded map overlays, safety alerts, and departure optimization.
  * **Liquid Glass Design System** — Premium dark-mode UI with animated gradient orbs, glass cards, and weather-responsive themes.
  * **Monetization** — Google AdMob integration with smart fatigue prevention and consent management.
  * **Siri Shortcuts** — 6 intents for quick weather queries.
* **Tech Stack:** Swift, SwiftUI, WeatherKit, MapKit, TipKit, Google AdMob, SPM (WizPathKit).
* 🔗 **Repository:** [View on GitHub](https://github.com/burak-bilgen/ForeWiz)

---

### 2. 🎬 DeFilms — Movie Discovery
> `✅ App Store Ready` • `🧪 88 tests` • `🍏 Apple Intelligence` • `🌐 EN / TR / AR`

> **Focus:** TMDB API, Apple Intelligence, Localization.

A SwiftUI movie discovery app built with the TMDB API. Approached as a small product rather than a one-off demo — stable navigation, testable state, polished localization.

* **Architecture:** Feature-oriented `MVVM` + Coordinator pattern with protocol-driven dependencies.
* **Highlights:**
  * **AI Picks** — On-device movie recommendations via Apple Foundation Models, with mood-based prompts and graceful fallback when unavailable.
  * **Custom Lists** — Multiple named lists instead of a single flat "saved" bucket, with full CRUD and movie management.
  * **Localization** — English, Turkish, and Arabic with RTL-aware layout handling.
  * **Search** — With validation, recent history, and advanced filter/sort controls.
  * **88 tests** (72 unit + 16 UI), all passing.
* **Tech Stack:** Swift, SwiftUI, Swift Concurrency, Core Data, Keychain, CryptoKit, Apple Foundation Models, XCTest.
* 🔗 **Repository:** [View on GitHub](https://github.com/burak-bilgen/DeFilms)

---

### 3. 📰 NewsApto — Intelligent News Reader
> `🔋 Zero Dependencies` • `🧪 49 tests` • `📰 6 Sources` • `🌐 EN / TR`

> **Focus:** Multi-Source Aggregation, Zero Dependencies, Smart Scoring.

An intelligent news reader that aggregates content from 6 sources (NewsAPI, Guardian, NYT, GNews, NewsData.io, HackerNews), then scores and ranks articles using a custom algorithm.

* **Architecture:** `Clean Architecture` with strict dependency inversion, Swift actors for thread-safety.
* **Highlights:**
  * **SmartArticleScorer** — Multi-factor ranking (recency, content quality, source authority, trending) with cross-source deduplication.
  * **Zero Dependencies** — 100% native Apple frameworks. No SPM, no CocoaPods, no third-party SDKs.
  * **Terminal-Inspired UI** — Cyberpunk aesthetic with matrix code rain, glitch reveals, and neon accents.
  * **Offline-First** — Two-tier cache (50MB memory + 200MB disk) with seamless degradation.
  * **Smart Categorization** — 7 categories with 150+ API mappings and 300+ keyword fallback.
  * **49 tests**, 0 build warnings.
* **Tech Stack:** Swift, SwiftUI, URLSession, Core Data, Actors, XCTest.
* 🔗 **Repository:** [View on GitHub](https://github.com/burak-bilgen/NewsApto)

---

## 📈 Approach

* **Stability:** I use Xcode Instruments (Allocations/Leaks) to track and fix memory issues in production.
* **Code Quality:** I follow SOLID principles and use automated linting to keep the codebase consistent.
* **Learning:** Currently working with Swift 6 Strict Concurrency and exploring new architecture patterns.

---

<p align="center">
  <img src="city.gif" width="80%" alt="Pixel City" />
</p>

## 📫 Let's Talk

I'm open to **Senior iOS Developer** roles and freelance opportunities — especially in fintech, trading platforms, and beyond.

<p align="center">
  <a href="https://linkedin.com/in/burak-bilgen"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:bilgenburak@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/burak-bilgen"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://burakbilgen.lovable.app"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/></a>
</p>
