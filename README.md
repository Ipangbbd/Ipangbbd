# Muhammad Ali Irfansyah

Software engineer focused on building reliable, maintainable full-stack web applications.

I care about system design, clear tradeoffs, and shipping software that survives real usage—not demos.

---

## Focus

- Full-stack web applications
- Clean architecture & maintainable codebases
- Practical UI over visual theatrics
- Performance, correctness, and long-term maintainability

---

## Primary Stack

- **Frontend:** React, Next.js, TypeScript
- **Backend:** Node.js, Express, Laravel
- **Databases:** PostgreSQL, MySQL
- **Infrastructure:** Docker, Nginx, Vercel
- **Tooling:** Git, Linux, Postman

## Secondary Experience

- Flutter (mobile applications)
- Firebase
- AWS (basic services & deployment)

---

## Selected Projects

### Offline Music Player (Web)
A fully offline-first web music player designed to work without ads, accounts, or network dependency.

**Why this exists**  
I wanted a YouTube-like listening experience without ads, tracking, or forced connectivity.  
This project explores how far modern web APIs can go for offline media consumption.

**Key technical decisions**
- IndexedDB for local audio storage
- Service Workers for offline reliability
- Client-side playlist & queue management
- No backend dependency by design

**Challenges**
- Handling large audio files in-browser
- Maintaining performance with growing libraries
- Reliable playback state across reloads

**Tech:** React, TypeScript, Web Audio API, IndexedDB  
Repo: https://github.com/Ipangbbd/Offline-Music-Player-Ali

---

### SBACS — Shift-Based Anti-Corruption System
A full-stack system for managing shift-based operations with accountability tracking.

**Problem**
Manual or poorly logged shift systems are prone to manipulation and lack auditability.

**Architecture**
- Frontend: React.js (UI), Native CSS
- Backend: Node.js, Express
- Database: PostgreSQL

**Key focus areas**
- Role-based access separation
- Audit-friendly data modeling
- Explicit state transitions for shifts

**Tradeoffs**
- Monolithic backend for simplicity
- No real-time layer (yet)

**Tech:** React, Node.js, Express, PostgreSQL  
Repo: https://github.com/Ipangbbd/SBACS-Shift-Based-Anti-Corruption-System-

---

### FinFlow — Personal Finance Manager
A mobile application for personal budgeting and expense tracking.

**Why this exists**
Most finance apps are over-engineered. This project explores a simple, offline-first approach.

**Key decisions**
- Local SQLite storage for reliability and offline usage
- Minimal state management to reduce complexity

**Known limitations**
- No cloud sync
- Single-device usage only

**Tech:** Flutter, SQLite  
Repo: https://github.com/Ipangbbd/Flutter-Finance-Manager

---

### Game Store Marketplace
A small marketplace-style application for browsing and purchasing virtual items.

**Purpose**
Explore a standard MERN architecture with a realistic store flow.

**Features**
- Product listing & filtering
- Basic cart workflow
- Separation between client and server concerns

**Limitations**
- Payments are mocked
- No inventory locking or concurrency handling

**Tech:** MongoDB, Express, React, Node.js  
Repo: https://github.com/Ipangbbd/Game-Store-Marketplace

---

### MERN Hotel Management System
A basic hotel booking and administration system.

**Focus**
- Authentication and role separation
- CRUD reliability
- Admin vs user access boundaries

**Current gaps**
- Payments are mocked, not production-ready
- No rate limiting or caching

**Tech:** MongoDB, Express, React, Node.js  
Repo: https://github.com/Ipangbbd/MERN-HOTEL

---

### Laravel CRUD Template with Authentication
A starter template for CRUD applications with authentication.

**Purpose**
Reduce setup time for small Laravel projects.

**Tech:** Laravel, PHP, MySQL  
Repo: https://github.com/Ipangbbd/LARAVEL-CRUD-TEMPLATE-WITH-AUTH

---

## Engineering Values

- Prefer clarity over cleverness
- Explicit tradeoffs beat hidden magic
- Simple systems scale better than fragile ones
- Code should be readable by someone else in six months

---

## GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ipangbbd&show_icons=true&hide_border=true)

---

## Contact

GitHub: https://github.com/ipangbbd  
LinkedIn: https://linkedin.com/in/muhammad-ali-irfansyah
