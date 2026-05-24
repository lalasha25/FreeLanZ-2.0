# FreeLanZ 2.0

FreeLanZ 2.0 adalah platform freelance berbasis web yang menghubungkan **Client** dan **Freelancer** secara dinamis menggunakan arsitektur **Multi-Tier / Layered Architecture** untuk performa, skalabilitas, dan keamanan yang optimal.

## Features
- **Multi-Role Authentication** (Client & Freelancer)
- **Secure Registration** dengan upload KTP & Portfolio Proposal
- **Explore Talent & Project Request** dengan filter kategori
- **Real-Time Chat & Project Milestone Tracking**
- **Profile Management & Avatar Upload**
- **JWT Authentication (7 Days)** & **Bcrypt Password Hashing**

## Tech Stack

### Frontend
- React.js + Vite
- Axios
- Vanilla CSS

### Backend
- NestJS (TypeScript)
- Prisma ORM
- JWT + Passport Guard
- Multer File Upload
- Swagger API Docs

### Database
- MySQL (`freelanz_db_fix`)

---

## Local Setup

### Backend
```bash
cd BackendFLZ
npm install
npx prisma migrate dev
npm run start:dev
