<div align="center">
  <a href="https://swordsouloflabrynth.github.io/portfolio/">
    <img src="https://raw.githubusercontent.com/SwordsoulOfLabrynth/portfolio/main/assets/branding/github/kzyh-github-banner-v2-1280x320.png" alt="Kyaw Zay Ya Hein — Product Builder · Software Engineer · Experimental Engineer" width="100%" />
  </a>

  # Kyaw Zay Ya Hein
  **Product Builder · Software Engineer · Experimental Engineer**

  [![Portfolio](https://img.shields.io/badge/Portfolio-swordsouloflabrynth.github.io-7447C8?style=flat-square&logo=googlechrome&logoColor=white)](https://swordsouloflabrynth.github.io/portfolio/)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Kyaw_Zay_Ya_Hein-0B0920?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kyaw-zay-ya-hein-00aba927b)
  [![Focus](https://img.shields.io/badge/Focus-C%23%20%2F%20.NET%20%7C%20Flutter%20%7C%20Web%20Systems-A879FF?style=flat-square)](#-technical-stack)
</div>

---

### 🏛️ Engineering Background & Approach

I am a **final-year Computer Science & Engineering student at MIIT, expected to graduate in 2027**. My work centers on backend systems, transactional data workflows, and offline-capable mobile applications.

> I translate product ideas into technical specifications, system designs, and test requirements. I use AI-assisted development tools to accelerate implementation, then review, debug, and validate the results through testing and iteration. In team settings, I lead core software implementation while collaborating with peers on specifications, documentation, and validation.

---

### 🚀 Selected Engineering Projects

#### 1. [MatchGuard (TrustedMarketplace)](https://github.com/SwordsoulOfLabrynth/TrustedMarketplace)
*Trust-based escrow and automated transaction settlement backend.*  
**Role**: Sole Developer (Individual Project)
* **Architecture**: ASP.NET Core (.NET 10), Entity Framework Core 10, PostgreSQL 16, MediatR (CQRS), FluentValidation.
* **Test Verification**: **167 automated unit tests passed locally** (xUnit) verifying domain invariants, escrow state machine transitions (Draft → Placed → EscrowFunded → Dispatched → Completed / Disputed), and settlement workflows.
* **Security & Infrastructure**: Role-based JWT authentication and authorization policies, ASP.NET Core Identity password hashing, multi-stage Docker API build, and local PostgreSQL 16 container setup (`docker-compose.yml`).
* **Integration Tests & CI**: 87 integration test methods are implemented in code (unexecuted locally, require live PostgreSQL container); a GitHub Actions CI workflow file is defined in the repository (remote run execution unverified).

#### 2. [Baganetic Mobile](https://github.com/SwordsoulOfLabrynth/BaganeticMobileApp)
*Mobile companion designed for low-connectivity heritage travel.*  
**Role**: Lead Developer (University Team Project)
* *Independently handled nearly all software implementation, while collaborating with teammates on requirements, documentation, and validation.*
* **Architecture**: Flutter, Dart, SQLite (`sqflite`), Provider state management.
* **Offline Graph Routing**: Implements on-device route calculations using a bundled adjacency graph (`offline_route_graph.json`) that functions fully without cellular data.
* **Map Tile Integration**: Integrates `flutter_map_tile_caching` service architecture with bounded coordinates for the Bagan archaeological zone.
* **Local Persistence & UI**: SQLite database for local itineraries and monument notes; bilingual UI (English / Myanmar).

#### 3. [Baganetic Routing Engine & Portal](https://github.com/SwordsoulOfLabrynth/Baganetic)
*Cultural heritage routing platform and custom pathfinder (MIIT University Special Project).*  
**Role**: Lead Developer (4-person Academic Team)
* *Independently handled nearly all software implementation, while collaborating with teammates on requirements, documentation, and validation.*
* **Architecture**: Hybrid system pairing a Python (Flask) pathfinding microservice with a Node.js (Express) web portal and MongoDB data storage.
* **Core Algorithm**: Custom A\* search engine in Python (`improved_pathfinder.py`) calculating optimized heritage circuits over a coordinate graph of historical monuments and unpaved road networks in Bagan.
* **Verification**: Offline graph traversal and route reconstruction logic personally tested and verified on local heritage datasets.

#### 4. [GeoAlert AI](https://github.com/SwordsoulOfLabrynth/GeoAlert-AI-HACK-MM-041)
*Geospatial infrastructure hazard risk visualization prototype.*  
**Role**: Team Contributor (Hackathon Project)
* **Architecture**: Python, Streamlit, PyDeck (deck.gl), Pandas.
* **Implementation**: Analyzes simulated flood and landslide hazard polygons against regional telecommunication tower coordinates to compute vulnerability and infrastructure exposure in Mon State.

---

### 🛠️ Technical Stack

* **Languages (Repository Evidence)**: C#, Dart, Python, TypeScript, SQL, JavaScript.
* **Backend & Web Frameworks (Repository Evidence)**: ASP.NET Core (.NET 10), Entity Framework Core, Node.js / Express, Flask, Django, React.
* **Databases & Storage (Repository Evidence)**: PostgreSQL, SQLite, MongoDB.
* **Testing & Tools**: xUnit, Moq, Git, Docker, Postman, Figma.
* **General Familiarity & Academic Coursework**: Java, C.

---

### 🎓 Education

* **B.E. Computer Science and Engineering** — Myanmar Institute of Information Technology (MIIT)  
  *Final-year student, expected graduation in 2027.*
* **Relevant Coursework**: Software Engineering, Software Testing & QA, Relational Database Management Systems, Data Structures & Algorithms, Computer Networks.
