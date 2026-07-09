<p align="center">
  <a href="https://github.com/burak-bilgen/Vade">
    <img src="https://img.shields.io/badge/🔥_Check_out_my_new_project-Vade_Multi_Currency_Debt_Tracking-8B5CF6?style=for-the-badge&logo=swift&logoColor=white" alt="Check out my new project: Vade" />
  </a>
</p>

---

# Burak Bilgen
### <img src="https://img.shields.io/badge/--black?style=flat-square&logo=apple&logoColor=white" height="18" style="vertical-align: middle;" alt="Apple" /> Senior iOS Developer — Fintech & Cryptocurrency

Senior iOS Developer with **4+ years of experience** shipping production apps in fintech and cryptocurrency. Focused on building high-performance trading interfaces, KYC verification flows, multi-currency wallets, and real-time data streams at scale.

Practices modular architectures with `Swift`, `SwiftUI`, and `Combine` — balancing performance with security at every layer. Refines product design and user experience through published App Store projects.

- **Architecture & Concurrency:** Modular architectures, protocol-oriented design, structured concurrency (Swift 6)
- **Fintech Security:** SSL pinning, secure storage, WebSocket communication, KYC compliance
- **Engineering Practices:** Memory profiling (Instruments), Swift 6 Strict Concurrency, TDD, CI/CD automation

---

## Technical Toolbox

| Category | Technologies |
|---|---|
| **Languages & Frameworks** | `Swift` • `SwiftUI` • `UIKit` • `Combine` • `RxSwift` |
| **Architecture** | `MVVM` • `MVVM-C` • `VIPER` • `Clean Architecture` |
| **Networking & Data** | `REST APIs` • `WebSockets` • `Firebase` • `Core Data` • `Realm` |
| **Security** | `SSL Pinning` • `Keychain` • `Secure Storage` |
| **Tools & DevOps** | `Xcode` • `Xcode Cloud` • `CircleCI` • `SPM` • `Postman` • `Proxyman` • `Firebase Crashlytics` |
| **Engineering Practices** | `TDD` • `Unit Testing` • `Code Review` • `Agile (Scrum, Kanban)` |

---

## GitHub Analytics

<p align="center">
  <a href="https://github.com/burak-bilgen">
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=burak-bilgen&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" />
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs?username=burak-bilgen&layout=compact&langs_count=8&theme=dark&hide_border=true" alt="Top Languages" />
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=burak-bilgen&theme=dark&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=burak-bilgen&theme=github-dark&hide_border=true&radius=6" width="95%" alt="Contribution Graph" />
</p>

---

## Featured Projects

### 🚀 Vade — Multi-Currency Debt Tracking
> `Swift 6` • `SwiftUI` • `MVVM-C` • `Clean Architecture` • `SwiftData + CloudKit` • `12 Modular SPM Packages`

Production-grade iOS app for tracking debts and receivables across TRY, USD, EUR, and physical gold. Built with Swift 6 strict concurrency, offline-first SwiftData + CloudKit sync, and a modular 12-package architecture.

- **Clean Architecture:** 3-layer separation — Domain (pure Swift), Data (SwiftData repositories), Presentation (SwiftUI)
- **Swift 6 Concurrency:** Complete data-race safety with Sendable, MainActor, and structured async/await
- **SwiftData + CloudKit:** Offline-first with automatic iCloud sync via user's private database. Append-only audit trail.
- **Design System:** 16+ in-house components, dark-only financial palette, custom entrance animation engine
- **Testing:** Swift Testing framework (no XCTest), 86%+ coverage, native snapshot testing
- **Security:** Face ID / Touch ID app lock with background blur. No backend — user data stays in iCloud.
- **Features:** Multi-currency + physical gold · Live TCMB exchange rates with offline caching · Partial payments · PDF/CSV export · WidgetKit widget · Turkish & English localization · VoiceOver accessibility
- 🔗 [Repository](https://github.com/burak-bilgen/Vade)

---

### ForeWiz — Weather Decision Assistant
> `iOS 17+` • `WeatherKit` • `Decision Engine` • `Route Planning`

ForeWiz transforms Apple WeatherKit data into actionable decisions. It scores outdoor conditions (0–100), recommends activities and outfits, and analyzes health impact — migraine, sleep, joints, respiratory, stamina.

- **WizPath** — Climate-aware route planning with multi-modal routing (driving, cycling, walking, EV), weather-coded map overlays, safety alerts, and departure optimization
- **Liquid Glass Design System** — Premium dark-mode UI with animated gradient orbs, glass cards, and weather-responsive themes
- **Monetization** — AdMob with smart fatigue prevention and consent management
- **6 Siri Shortcuts** — Quick weather queries
- **Tech:** `Swift` • `SwiftUI` • `WeatherKit` • `MapKit` • `TipKit` • `AdMob` • `WizPathKit`
- 🔗 [Repository](https://github.com/burak-bilgen/ForeWiz) · 📱 [App Store](https://apps.apple.com/us/app/forewiz-weather-decisions/id6768601251)

---

### DeFilms — Movie Discovery
> `88 tests` • `Apple Intelligence` • `EN / TR / AR`

A SwiftUI movie discovery app built with the TMDB API. Approached as a product rather than a demo — stable navigation, testable state, polished localization.

- **AI Picks** — On-device movie recommendations via Apple Foundation Models with mood-based prompts and graceful fallback
- **Custom Lists** — Multiple named lists with full CRUD instead of a single flat saved bucket
- **Localization** — English, Turkish, Arabic with RTL-aware layout
- **88 tests** (72 unit + 16 UI), all passing
- **Tech:** `Swift` • `SwiftUI` • `Core Data` • `Keychain` • `CryptoKit` • `Apple Foundation Models`
- 🔗 [Repository](https://github.com/burak-bilgen/DeFilms) · 📱 [App Store](https://apps.apple.com/us/app/defilms/id6764787409)

---

### NewsApto — Intelligent News Reader
> `Zero Dependencies` • `49 tests` • `6 Sources` • `EN / TR`

Aggregates content from 6 sources (NewsAPI, Guardian, NYT, GNews, NewsData.io, HackerNews), ranks articles with a custom scoring algorithm, and serves them in a terminal-inspired cyberpunk interface.

- **SmartArticleScorer** — Multi-factor ranking: recency, content quality, source authority, trending, cross-source deduplication
- **Zero Dependencies** — 100% native Apple frameworks. No SPM, no CocoaPods, no third-party SDKs
- **Terminal-Inspired UI** — Cyberpunk aesthetic with matrix code rain, glitch reveals, neon accents
- **Offline-First** — Two-tier cache (50 MB memory + 200 MB disk) with seamless degradation
- **49 tests**, 0 build warnings
- **Tech:** `Swift` • `SwiftUI` • `URLSession` • `Core Data` • `Actors`
- 🔗 [Repository](https://github.com/burak-bilgen/NewsApto) · 📱 [App Store](https://apps.apple.com/us/app/newsapto/id6769076161)

---

## Approach

- **Stability** — Uses Xcode Instruments (Allocations / Leaks) to track and fix memory issues in production
- **Code Quality** — SOLID principles, automated linting, consistent codebase
- **Growth** — Currently working with Swift 6 Strict Concurrency and exploring new architecture patterns

---

## Let's Talk

Open to **Senior iOS Developer** roles and freelance opportunities — especially in fintech, trading platforms, and cryptocurrency.

<p align="center">
  <a href="https://www.linkedin.com/in/burakbilgen"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:bilgenburak@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email" /></a>
  <a href="https://burakbilgen.lovable.app"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
</p>
