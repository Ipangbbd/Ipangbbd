# Muhammad Ali Irfansyah

Software engineer focused on building reliable, maintainable full-stack web applications.

I prioritize system design, explicit tradeoffs, and shipping software that holds up under real usage.

---

## Focus

- Full-stack web applications  
- Clean architecture and maintainable codebases  
- Practical UI over visual theatrics  
- Performance, correctness, and long-term reliability  

---

## Stack

**Frontend**  
React, Next.js, TypeScript  

**Backend**  
Node.js, Express, Laravel  

**Databases**  
PostgreSQL, MySQL, MongoDB  

**Infrastructure & Tooling**  
Docker, Nginx, Vercel, Git, Linux, Postman  

**Additional Experience**  
Flutter, Firebase, AWS (core services & deployment)  

---

## Selected Projects

### Offline Music Player (Web)
A fully offline-first web music player designed to work without ads, accounts, or network dependency. 

**Why this exists** I wanted a YouTube-like listening experience without ads, tracking, or forced connectivity. This project explores how far modern web APIs can go for offline media consumption.

**Architecture & Decisions**
- IndexedDB for local audio storage  
- Service Workers for offline reliability  
- Client-side playlist and queue management  
- No backend by design  

**Engineering Challenges**
- Large file handling in-browser  
- Performance with growing local libraries  
- Playback state persistence across reloads  

**Tech:** React, TypeScript, Web Audio API, IndexedDB  
Repo: https://github.com/Ipangbbd/Offline-Music-Player-Ali  

---

### SBACS — Shift-Based Anti-Corruption System
Accountability-focused system designed to reduce internal fraud in shift-based operations.

**Problem**
In many small and mid-sized businesses, shift logs are manually adjusted, weakly audited, or retroactively edited—creating opportunities for cash leakage and responsibility evasion.

**System Intent**
SBACS enforces explicit accountability by making shift state changes traceable, constrained, and reviewable.

**Architecture**
- Frontend: React (Native CSS)
- Backend: Node.js, Express
- Database: PostgreSQL

**Design Decisions**
- Explicit shift state transitions to prevent silent edits
- Role-based access separation (operator vs supervisor)
- Audit-oriented data modeling over convenience
- Server-side validation for all critical state changes

**Tradeoffs**
- Monolithic backend to keep authority centralized
- No real-time updates to avoid unnecessary complexity

**Tech:** React, Node.js, Express, PostgreSQL  
Repo: CURRENTLY NOT AVAILABLE FOR PUBLIC

---

### FinFlow — Personal Finance Manager
Offline-first mobile app for personal budgeting and expense tracking.

**Design Choices**
- Local SQLite storage for reliability  
- Minimal state management  

**Limitations**
- No cloud sync  
- Single-device usage  

**Tech:** Flutter, SQLite  
Repo: https://github.com/Ipangbbd/Flutter-Finance-Manager  

---

## Contact

GitHub: https://github.com/ipangbbd  
LinkedIn: https://linkedin.com/in/muhammad-ali-irfansyah
