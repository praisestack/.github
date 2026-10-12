<p align="center">
  <img src="https://raw.githubusercontent.com/praisestack/.github/main/assets/logo-horizontal.svg" alt="PraiseStack Logo" width="500">
</p>

<p align="center">
  <strong>Open, high-performance production and presentation tools for modern worship.</strong>
</p>

<p align="center">
  <a href="https://praisestack.org">Website</a> •
  <a href="https://worshipcommons.org">Worship Commons</a> •
  <a href="#the-praisestack-ecosystem">Ecosystem</a> •
  <a href="#architecture--principles">Philosophy</a> •
  <a href="#contributing">Contributing</a>
</p>

---

## Welcome to PraiseStack

**PraiseStack** is an open-source collective dedicated to building reliable, fast, and accessible live presentation and media tools for churches and live worship gatherings. 

Modern church production demands zero-latency lyric transitions, multi-display video routing, and seamless volunteer workflows. PraiseStack provides a modular, independently designed software suite built on modern systems programming and open data standards.

---

## The PraiseStack Ecosystem

All PraiseStack tools are permissively licensed under the **MIT License**, ensuring churches of all sizes have full ownership and long-term stability of their production stack.

### 🖥️ Core Presentation & Media
* **PraiseStack Presenter** *(in active development)*  
  A modern, crash-resilient live presentation engine built from the ground up in **Rust**.
  * **Zero Sunday Morning Crashes:** Memory-safe, high-efficiency native rendering pipeline for projection, broadcast lower-thirds, and confidence monitors.
  * **Worship Commons Native:** First-class support for the [Worship Commons](https://worshipcommons.org) open song and arrangement standard.
  * **Direct Song Import:** Integrated CCLI SongSelect querying and automated arrangement builders.
  * **Multi-Screen Video Pipeline:** Independent outputs for stage displays, front-of-house screens, and NDI/SDI broadcast feeds.

### 📦 Utilities & Interoperability
* **StackPack**  
  A native macOS utility designed to package worship playlists, bundle presentation assets, and generate portable archives with zero external runtime dependencies.
* **PraiseLink** *(planned)*  
  Open control surface connectors and APIs for Bitfocus Companion, Stream Deck, and mobile web remotes.

---

## Architecture & Principles

### 1. Built for Stability (Rust-First)
Live church services cannot tolerate dropped frames, memory leaks, or spontaneous crashes. Our core engine is built in **Rust** to deliver bare-metal GPU performance and compile-time memory safety.

### 2. Open Standards Over Walled Gardens
Church content belongs to the church. We build natively around **Worship Commons** schemas, open JSON manifests, and cross-platform media formats so your libraries, chord charts, and arrangements are never locked behind proprietary or closed database formats.

### 3. Clean-Room Interoperability & Independent Implementation
PraiseStack adheres to clean-room engineering discipline to guarantee legal integrity and independent design:
* **Original Codebase:** All PraiseStack software is 100% newly authored from scratch under the MIT license. No proprietary source code or decompiled source is included or referenced in our repositories.
* **Specification-Driven Interoperability:** Compatibility with existing industry presentation formats or local network protocols is developed strictly through functional behavior analysis and format specifications.
* **Independent Architecture:** PraiseStack features its own data pipeline, modern UI paradigm, and graphics rendering stack built from first principles.

### 4. Permissive Open Source (MIT)
Everything we build is licensed under the **MIT License**. Use it, inspect it, contribute back, or adapt it to your church's unique workflow without restrictive licensing terms or costly ongoing subscriptions.

---

## How to Get Involved

PraiseStack is a community-driven initiative built by church AV volunteers, worship leaders, and systems engineers.

* **Code:** Explore our repositories below. Rust, Swift, and UI/UX contributors are always welcome.
* **Standards:** Learn more about song interoperability at [Worship Commons](https://worshipcommons.org).
* **Feedback:** Have feature ideas or need custom production workflows? Open an issue or join the discussions in any of our repositories.

---

<p align="center">
  <sub>PraiseStack is an independent open-source project released under the MIT License.</sub>
</p>
