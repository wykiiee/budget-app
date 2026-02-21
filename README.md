<div align="center">
  <img src="https://via.placeholder.com/150/0f172a/60a5fa?text=Nexus" alt="Nexus Wealth Tracker Logo" height="80">

  # Nexus Wealth Tracker 💎
  
  **Your personal command center for modern financial management.**

  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
  [![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](./LICENSE)

  [**Live Demo (HTML Preview)**](https://htmlpreview.github.io/?https://github.com/wykiiee/budget-app/blob/main/index.html) •
  [**Deploy to Vercel**](#deployment)

  ---
</div>

## 📸 See it in action

<div align="center">
  <img src="./demo.webp" alt="Nexus Wealth Tracker Demo" width="800">
</div>

Nexus Wealth Tracker is a beautiful, intuitive, and responsive budget tracking application. It is completely standalone but features seamless Firebase integration out of the box, offering secure user authentication and real-time cloud sync.

## ✨ Features

- 💸 **Comprehensive Dashboard**: View your net worth, income vs. expense progress, and monthly trends instantly.
- 💳 **Smart Transactions**: Categorized tracking for all your daily cash flow. Fast to input, easy to analyze.
- 🏦 **Multiple Accounts**: Track multiple wallets, bank accounts, and mobile money effortlessly.
- 🎯 **Visual Savings Goals**: Build habits and measure your savings against concrete goals with progress visualizations.
- 📈 **Interactive Analytics**: Elegant Charts.js visualizations help analyze spending habits at a glance.
- ⚡ **Local-First & Offline Ready**: Runs perfectly offline with `localStorage` and smoothly syncs to the cloud when connected.
- 🎨 **Glassmorphism UI**: Beautifully crafted dark-mode components with modern styling.

## 🚀 Tech Stack

- **Frontend**: React 18, Tailwind CSS, Babel (Standalone)
- **Data Visualization**: Chart.js v4
- **Backend/BaaS**: Firebase (Authentication & Realtime Database)
- **Exporting**: SheetJS for Excel generation
- **Fonts & Styling**: Google Fonts (Inter), Vanilla CSS micro-animations

## 🛠️ Local Setup & Development

This app requires zero build steps by default because it heavily leverages CDNs to make jumping into the code seamless!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/wykiiee/budget-app.git
   cd budget-app
   ```

2. **Open the App:**
   Simply open `index.html` in your favorite modern browser. No complex node tools required!
   *(Or spin up a local server using `npx serve .` or the VS Code Live Server extension)*

3. **(Optional) Configure Firebase:**
   By default, the app runs entirely in your local browser storage. To enable cloud sync:
   - Create a project on [Firebase Console](https://console.firebase.google.com/).
   - Replace the `firebaseConfig` object inside `<script type="text/babel">` in `index.html` with your newly generated config.

## 🌐 Deployment

You can deploy this instantly to any static hosting provider.

### Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fwykiiee%2Fbudget-app)

1. Click the deploy button above or link your GitHub repo directly inside your Vercel dashboard.
2. Vercel automatically detects the HTML entry point.
3. Done in seconds. Enjoy your live URL!

### Render or Railway

Since the app is purely static:
1. Connect your GitHub account.
2. Create a "Static Site" service.
3. Leave the build command empty, and set the publish directory to `.`.

## 🤝 Contributing

Contributions are always welcome. To contribute, simply fork the repository, create a new branch, and submit a pull request!
