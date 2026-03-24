# BankApp 💳

A frontend for full-stack banking application built with React. This is the frontend part of the BankApi project.

🌐 **Live Demo:** https://bank-frontend-bay.vercel.app  
🔗 **Backend Repository:** https://github.com/kyrylo-sketch/spring-boot-BankApi

## Tech Stack
- **Frontend:** React, JavaScript
- **Deployment:** Vercel

## Pages
- **Login / Register** — authentication
- **Dashboard** — account overview and balance
- **Accounts** — account list and transaction history
- **Transfer** — send money between accounts
- **Deposit / Withdraw** — manage account balance
- **Transactions** — full transaction history
- **Admin Panel** — manage customers and accounts (Admin only)

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
