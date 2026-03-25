# Digital Sergeant — E-Challan System
### Built for Islamabad Traffic Police (ITP)

A real-time traffic violation enforcement platform used by 
500+ field officers daily across Islamabad — replacing a 
fully manual paper-based challan system.

> This is a showcase repository. Source code is private 
> due to government deployment constraints.

---

## The Problem
ITP officers were managing traffic violations manually — 
paper challans, no real-time tracking, no data sync. 
Lost records, slow processing, zero visibility for management.

## The Solution
A Flutter mobile app that lets officers scan vehicles, 
generate digital challans, track violations in real time, 
and sync everything to a central Firebase backend — 
all from their phone in the field.

---

## Key Features
- Real-time violator tracking and fine payment management
- ML Kit OCR for automatic number plate scanning
- Native camera integration for evidence capture
- Native SMS integration for instant notifications
- Location services for violation geo-tagging
- Offline-first architecture with Firebase sync
- CI/CD pipeline via GitHub Actions + Shorebird

---

## Impact
| Metric | Result |
|--------|--------|
| Daily active officers | 500+ |
| Deployment | Live — Islamabad Traffic Police |
| Platform | Android + iOS |
| Data sync | Real-time via Firebase |

---

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Framework | Flutter + Dart |
| State Management | GetX |
| Backend | Firebase (Firestore, Storage, Auth) |
| OCR | ML Kit (Google) |
| Native SDKs | Camera, SMS, Location |
| Architecture | Clean Architecture + SOLID |
| CI/CD | GitHub Actions + Shorebird |
| Design | Figma |

---

## Architecture
```
lib/
├── core/
│   ├── models/
│   ├── services/
│   └── utils/
├── features/
│   ├── challan/
│   ├── officer/
│   ├── dashboard/
│   └── reports/
└── shared/
    ├── components/
    └── theme/
```

---

## Screenshots
> Coming soon — UI screenshots being prepared

---

## Developer
**Ehsan Yaqoob** — Flutter & iOS Developer  
📍 Islamabad, Pakistan  
📧 ehsanyaqoob07@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/ehsany) 
| [Portfolio](https://ehsan-dun.vercel.app)  
| [GitHub](https://github.com/ehsanyaqoob)
```
