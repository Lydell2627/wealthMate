# wealthMate

**WealthMate** is a modern, full-stack web application designed to help friends and groups seamlessly manage shared expenses. Create groups, add friends, track spending, split bills, and settle balances – all in one intuitive interface.

🔗 **Live Demo**: [wealth-mate.vercel.app](https://wealth-mate.vercel.app)

---

## 🚀 Features

- **User Authentication**: Secure sign-up and sign-in flows.
- **Profile Management**: Customize and view your personal profile.
- **Groups**: Create and join groups to track shared expenses.
- **Friends List**: Add, remove, and view friends across all groups.
- **Expense Tracking**: Record expenses with amount, description, and payer.
- **Bill Splitting**: Split expenses equally or assign custom shares.
- **Activity Feed**: See a real-time log of all group transactions.
- **Settlement**: Generate simplified settlement suggestions to clear debts.
- **Responsive UI**: Designed for both desktop and mobile devices.

---

## 🛠️ Tech Stack

- **Frontend**: React, TypeScript, Vite, React Router DOM
- **State & Data Fetching**: React Query, Context API
- **Styling**: Tailwind CSS
- **Environment**: Vite for fast build and hot-reloading
- **Deployment**: Vercel

---

## 💻 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Lydell2627/wealthMate.git
   cd wealthMate
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure environment**
   - Copy `.env.local.example` to `.env.local`
   - Set your API base URL and any other keys:
     ```ini
     VITE_API_URL=https://your-backend.example.com
     ```

4. **Run the development server**
   ```bash
   npm run dev
   ```
   - App will be available at `http://localhost:5173`

---

## 📁 Project Structure

```
wealthMate/
├── public/                 # Static assets and favicon
├── src/                    # Application source code
│   ├── _auth/              # Authentication layouts and forms
│   ├── _root/              # Main app layouts and pages
│   ├── components/         # Reusable UI components
│   ├── context/            # React Context providers (e.g., Auth)
│   ├── lib/                # API clients & React Query hooks
│   ├── constants/          # Static link definitions and assets
│   ├── hooks/              # Custom React hooks
│   ├── types/              # TypeScript interfaces and types
│   ├── App.tsx             # Root component and route definitions
│   ├── main.tsx            # Entry point
│   └── globals.css         # Base styles
├── .env.local.example      # Example environment variables
├── tailwind.config.js      # Tailwind CSS configuration
├── vite.config.ts          # Vite configuration
└── package.json            # NPM scripts and dependencies
```

---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/MyFeature`
3. Commit your changes: `git commit -m 'Add MyFeature'`
4. Push to the branch: `git push origin feature/MyFeature`
5. Open a Pull Request detailing your improvements.


---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

> Built with ❤️ and designed to keep your friendships—and finances—balanced.

