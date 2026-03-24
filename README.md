# BankApp 💳

A frontend for full-stack banking application built with React.

🌐 **Live Demo:** https://bank-frontend-bay.vercel.app  
🔗 **Backend Repository:** https://github.com/kyrylo-sketch/spring-boot-BankApi  
📖 **API Docs:** https://spring-boot-bankapi-production.up.railway.app/swagger-ui/index.html

## Tech Stack
- **Frontend:** React, JavaScript
- **Deployment:** Vercel

## Features
- JWT authentication with refresh tokens
- Role-based access control (Admin/User)
- Dashboard with account overview
- Transaction history
- Transfer between accounts
- Deposit and withdrawal
- Currency display (PLN, EUR, USD)
- Admin panel for managing customers and accounts
- Mobile responsive design

## Setup
```bash
git clone https://github.com/kyrylo-sketch/bank-frontend
cd bank-frontend
npm install
npm run dev
```

Change API URL in `src/App.jsx`:
```javascript
const BASE = "http://localhost:8080";
```

## Backend
Backend repository: https://github.com/kyrylo-sketch/spring-boot-BankApi
