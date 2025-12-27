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
System for managing shift-based operations with auditability and accountability.

**Problem**
Manual or weakly logged shift systems are easy to manipulate and hard to audit.

**Architecture**
- Frontend: React (Native CSS)  
- Backend: Node.js, Express  
- Database: PostgreSQL  

**Key Focus**
- Role-based access separation  
- Audit-friendly data modeling  
- Explicit shift state transitions  

**Tradeoffs**
- Monolithic backend for operational simplicity  
- No real-time layer  

**Tech:** React, Node.js, Express, PostgreSQL  
Repo: https://github.com/Ipangbbd/SBACS-Shift-Based-Anti-Corruption-System-  

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
