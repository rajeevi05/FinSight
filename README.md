
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/50/Bank_font_awesome.svg" width="100" alt="FinSight Logo"/>
</p>

<h1 align="center">FinSight</h1>

<p align="center"><em><strong>Your Intelligent Financial Companion</strong></em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-13+-black?style=for-the-badge&logo=next.js"/>
  <img src="https://img.shields.io/badge/TypeScript-blue?style=for-the-badge&logo=typescript"/>
  <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css"/>
  <img src="https://img.shields.io/badge/Appwrite-F02E65?style=for-the-badge&logo=appwrite"/>
  <img src="https://img.shields.io/badge/Plaid-6200EE?style=for-the-badge&logo=plaid"/>
  <img src="https://img.shields.io/badge/Dwolla-FF6900?style=for-the-badge"/>
</p>

---

## 📈 What is FinSight?

**FinSight** is a secure and modern fintech dashboard built with **Next.js** and **TypeScript**, designed to empower users with clear, actionable insights into their financial health. It seamlessly integrates banking APIs and transactional tools to make money management smart, intuitive, and transparent.

Built as a full-stack project with real-world use cases, FinSight leverages real-time banking integrations, responsive design, and user-first UX principles.

---

## ✨ Key Features

* 🔐 **Secure SSR Authentication** with Appwrite
* 💳 **Bank Account Linking** with Plaid
* 📅 **Real-time Transaction Updates** and categorization
* 💵 **Funds Transfer** using Dwolla
* 🔄 **Automated Expense Breakdown**
* 📊 **Interactive Charts** with Chart.js
* 📊 **Custom Analytics Dashboard**
* 🔎 **Clean, responsive UI** using TailwindCSS + ShadCN
* 📈 **Personalized Financial Insights**

---

## 📚 Tech Stack

| Layer           | Tech Used                                |
| --------------- | ---------------------------------------- |
| Frontend        | Next.js, TypeScript, TailwindCSS, ShadCN |
| Backend/Auth    | Appwrite                                 |
| API Integration | Plaid (transactions), Dwolla (transfers) |
| Forms & Schema  | React Hook Form, Zod                     |
| Charts          | Chart.js                                 |

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
https://github.com/yourusername/finsight.git
cd finsight

# 2. Install dependencies
yarn install
# or
npm install

# 3. Set up environment variables
cp .env.example .env.local
# Update .env.local with Appwrite, Plaid, and Dwolla credentials

# 4. Run the development server
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the app.

---

## 📊 Dashboard Preview

> *Add a preview screenshot or GIF of the dashboard here*

---

## 🌐 Deployment

You can deploy FinSight on platforms like:

* **Vercel** (Recommended)
* **Render** (with Appwrite self-hosted)
* **Netlify** (with API proxy setup)

---

## 👁️ Environment Variables

Make sure to define the following in your `.env.local` file:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT=
NEXT_PUBLIC_APPWRITE_PROJECT=
NEXT_PUBLIC_APPWRITE_DATABASE=
NEXT_PUBLIC_APPWRITE_COLLECTION=
PLAID_CLIENT_ID=
PLAID_SECRET=
DWOLLA_APP_KEY=
DWOLLA_APP_SECRET=
```

---

## 📄 Folder Structure

```
finsight/
├── components/       # Reusable UI components
├── pages/            # Route components (Next.js)
├── lib/              # Utility functions and API logic
├── styles/           # Global and module styles (Tailwind)
├── hooks/            # Custom React hooks
├── public/           # Static assets
└── .env.local        # Local environment config
```

---

## 🚜 Contributing

1. Fork the repo
2. Create a new branch: `git checkout -b feature/myFeature`
3. Commit your changes: `git commit -m "Added feature"`
4. Push: `git push origin feature/myFeature`
5. Create a Pull Request

---

## 👁‍🗨️ License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file.

---

<p align="center">
  <strong>FinSight — Helping You Make Smarter Financial Decisions 🌟</strong>
</p>
