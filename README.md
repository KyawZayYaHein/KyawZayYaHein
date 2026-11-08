<!-- 01 / IDENTITY MASTHEAD -->
<p align="center">
  <a href="https://swordsouloflabrynth.github.io/portfolio/">
    <img alt="Kyaw Zay Ya Hein — Product Builder · Software Engineer · Experimental Engineer" src="assets/kzyh-github-hero-banner.png" width="100%">
  </a>
</p>

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-swordsouloflabrynth.github.io-4A44C6?style=flat-square&logo=google-chrome&logoColor=white)](https://swordsouloflabrynth.github.io/portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kyaw--zay--ya--hein-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kyaw-zay-ya-hein-00aba927b)
[![Email](https://img.shields.io/badge/Email-kyawzayyahein.mdy%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:kyawzayyahein.mdy@gmail.com)
[![Résumé](https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-17132F?style=flat-square&logo=adobe-acrobat-reader&logoColor=white)](https://swordsouloflabrynth.github.io/portfolio/assets/documents/Kyaw_Zay_Ya_Hein_CV_Resume.pdf)

<p align="center">
  <code>🎓 MIIT Final-Year CSE ('27)</code> &bull;
  <code>⚡ C# · .NET 10 · MediatR</code> &bull;
  <code>📱 Flutter · Offline SQLite</code> &bull;
  <code>🧪 167 Automated Tests</code> &bull;
  <code>🏆 Project Show Award &amp; Grade A</code>
</p>

</div>

---

## / Featured Systems &amp; Engineering Work

Empirical architectures, deterministic domain state machines, and spatial algorithms. Click any **"Inspect Architecture"** bar below to expand its full-width vector model.

---

### `SYS.01` [MatchGuard](https://github.com/SwordsoulOfLabrynth/TrustedMarketplace) — Non-Custodial Trust Engine
`C#` &bull; `.NET 10` &bull; `MediatR (CQRS)` &bull; `PostgreSQL 16` &bull; `Entity Framework Core` &bull; `xUnit`

A peer-to-peer trust platform enforcing formal order progression milestones without holding, routing, custodying, or settling user funds.

- **Non-Custodial Architecture**: The state machine governs transaction lifecycle milestones rather than holding financial custody, eliminating payment intermediary liability.
- **Deterministic Aggregate State Machine**: Strict status progression (`Placed` &rarr; `Accepted` &rarr; `Shipped` &rarr; `Completed`) guarded by actor-authorization invariants (only verified buyer confirms completion; only assigned seller records dispatch).
- **167 Passing xUnit Tests**: Automated test suite verifying domain invariants, aggregate state transitions, actor guards, and MediatR pipeline behaviors.

<details open>
  <summary><b>🔍 Inspect System Architecture &amp; State Machine Diagram</b> <i>(Full Width)</i></summary>
  <br/>
  <p align="center">
    <img src="assets/matchguard-lifecycle.svg" alt="MatchGuard — Trust-Based Marketplace Architecture" width="100%" />
  </p>
  <blockquote>
    <b>Architecture Highlights:</b> In-process MediatR CQRS pipeline &bull; PBKDF2 Password Hashing with ASP.NET Core Identity &bull; Stateless JWT claims &bull; Auditable <code>OrderStatusHistory</code> append-only log &bull; Containerized PostgreSQL 16 via Docker.<br/>
    &rarr; <a href="https://github.com/SwordsoulOfLabrynth/TrustedMarketplace"><b>Explore TrustedMarketplace Repository</b></a>
  </blockquote>
</details>

---

### `SYS.02` [Baganetic Mobile](https://github.com/SwordsoulOfLabrynth/BaganeticMobileApp) — Offline-First Spatial Navigation
`Flutter` &bull; `Dart` &bull; `SQLite (sqflite)` &bull; `flutter_map_tile_caching` &bull; `Firebase Auth` &bull; `Provider`

An on-device mobile companion engineered for seamless travel in zero-connectivity environments across the Bagan archaeological zone.

- **Network-Independent Navigation**: On-device routing graph with **7,035 road nodes and 7,344 edges**, paired with a 70-waypoint pagoda transit backbone.
- **On-Device Local Persistence**: Multi-table SQLite schemas managing custom itineraries, offline stops, bookmarks, road condition reports, and bilingual (EN/MY) localization.
- **Recognition**: Received **Team Special Award** at the university project show.

<details>
  <summary><b>🔍 Inspect Spatial Network &amp; On-Device Storage Architecture</b> <i>(Full Width)</i></summary>
  <br/>
  <p align="center">
    <img src="assets/baganetic-route-network.svg" alt="Baganetic Mobile — Offline Route Network &amp; On-Device Persistence" width="100%" />
  </p>
  <blockquote>
    <b>Architecture Highlights:</b> <code>flutter_map_tile_caching</code> (FMTC) prefetch bounds across Bagan coordinates (20.9717&deg; N &ndash; 21.3717&deg; N) &bull; SQLite schema v14 &bull; Hybrid Firebase Auth with local SQLite fallback for low-connectivity environments.<br/>
    &rarr; <a href="https://github.com/SwordsoulOfLabrynth/BaganeticMobileApp"><b>Explore BaganeticMobileApp Repository</b></a>
  </blockquote>
</details>

---

### `SYS.03` [Baganetic Engine](https://github.com/SwordsoulOfLabrynth/Baganetic) — Custom A* Pathfinding Service
`Python` &bull; `Flask` &bull; `Node.js` &bull; `Express` &bull; `MongoDB` &bull; `REST APIs`

A specialized algorithmic routing microservice calculating optimal travel paths across complex rural road topographies.

- **Custom A\* Min-Heap Algorithm**: Implemented `improved_pathfinder.py` (~580 LOC) using Python min-heap priority queues (`heapq`).
- **Mathematical Heuristics**: Formulated cost function $f(n) = g(n) + h(n)$ combining Haversine great-circle distance with surface-weighted traversal friction (1.35x unpaved dirt track penalty).
- **Cohort Top Honor**: Capstone project evaluated with cohort-highest **Grade A** award.

<details>
  <summary><b>🔍 Inspect A* Min-Heap Pathfinding Exploration Heuristics</b> <i>(Full Width)</i></summary>
  <br/>
  <p align="center">
    <img src="assets/astar-search-visual.svg" alt="Baganetic — A* Min-Heap Graph Exploration Heuristics" width="100%" />
  </p>
  <blockquote>
    <b>Architecture Highlights:</b> Python Flask algorithmic microservice &bull; Node.js Express web portal &bull; MongoDB geospatial queries &bull; Dynamic edge pruning verified against physical coordinates.<br/>
    &rarr; <a href="https://github.com/SwordsoulOfLabrynth/Baganetic"><b>Explore Baganetic Repository</b></a>
  </blockquote>
</details>

---

### `SYS.04` [GeoAlert AI](https://github.com/SwordsoulOfLabrynth/GeoAlert-AI-HACK-MM-041) — Geospatial Hazard Simulation
`Python` &bull; `Streamlit` &bull; `PyDeck (deck.gl)` &bull; `Pandas` &bull; `NASA SRTM`

Interactive 3D simulation analyzing infrastructure exposure and computing risk-weighted evacuation paths during natural hazards.

- **Topographic Hazard Modeling**: Simulated 100-year flood zone polygons &amp; landslide slope contours across Mon State using NASA SRTM 30m DEM &amp; CHIRPS rainfall telemetry.
- **Evacuation Routing**: Risk-weighted Dijkstra algorithm (penalties: low=1x, med=2x, high=5x) to bypass active high-hazard segments.
- **Context**: Developed during Hackathon `HACK-MM-041`.

<details>
  <summary><b>🔍 Inspect Geospatial Hazard Simulation &amp; Exposure Model</b> <i>(Full Width)</i></summary>
  <br/>
  <p align="center">
    <img src="assets/geoalert-geospatial.svg" alt="GeoAlert AI — Geospatial Hazard Simulation" width="100%" />
  </p>
  <blockquote>
    <b>Architecture Highlights:</b> Composite vulnerability scoring (Flood: 45% rain + 35% inverse elevation + 20% waterway; Landslide: 60% slope + 40% rain) rendered via interactive 3D PyDeck column overlays.<br/>
    &rarr; <a href="https://github.com/SwordsoulOfLabrynth/GeoAlert-AI-HACK-MM-041"><b>Explore GeoAlert-AI Repository</b></a>
  </blockquote>
</details>

---

## / Technical Toolkit

```
LANGUAGES          C# · Java · Dart · Python · TypeScript · SQL · JavaScript · C
BACKEND & APIS     ASP.NET Core (.NET 10) · MediatR (CQRS) · Entity Framework Core · REST APIs · Node.js / Express
MOBILE & CLIENT    Flutter · Provider · SQLite (sqflite) · Tailwind CSS · React · Streamlit
DATABASES          PostgreSQL 16 · SQLite · MongoDB · Firebase / Firestore
TESTING & DEVOPS   xUnit (167 passing tests) · Moq · Docker · Git · Postman · CI Workflows
DESIGN & PRODUCT   Figma · Design Systems · Interactive Prototyping · Responsive Layouts
```

---

<div align="center">

```
BUILD WITH INTENT. TEST WITH EVIDENCE.
```

**Kyaw Zay Ya Hein** &bull; Final-Year CSE @ MIIT ('27) &bull; Mandalay, Myanmar<br/>
[Portfolio](https://swordsouloflabrynth.github.io/portfolio/) &bull; [LinkedIn](https://linkedin.com/in/kyaw-zay-ya-hein-00aba927b) &bull; [Email](mailto:kyawzayyahein.mdy@gmail.com) &bull; [GitHub Profile](https://github.com/SwordsoulOfLabrynth)

</div>
