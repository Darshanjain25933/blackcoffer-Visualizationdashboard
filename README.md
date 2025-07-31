# Blackcoffer Visualization Dashboard

A modern, interactive data visualization dashboard built with React, Vite, TypeScript, Tailwind CSS, and Shadcn UI.

> 📢 **Note:** This project is strictly for internal assignment submission. Do not upload to public repositories or share publicly as per Blackcoffer's instructions.

---

## 🚀 Features

- 📊 Dynamic data loading from JSON  
- 📈 Interactive charts and analytics using Recharts  
- 🌍 Filter data by Region, Sector, Country, and Topic  
- 💻 Responsive design  
- 🎨 Clean, modern UI with Tailwind CSS and Shadcn UI  
- ⚡ Built with Vite for fast development experience  

---

## 📦 Getting Started

### 1. Extract the project

If downloaded as a ZIP file, extract it and open in your code editor.

Or, if using a private Git repo:

```bash
git clone <your-private-repo-url>
cd blackcoffer-visualizationdashboard


### 2. Install dependencies

```bash
npm install
# or
yarn install
# or
bun install
```

### 3. Run the development server

```bash
npm run dev
# or
yarn dev
# or
bun run dev
```

Open [http://localhost:8080](http://localhost:8080) (or the port shown in your terminal) in your browser.

---

## 🛠️ Build for Production

```bash
npm run build
```

The production-ready files will be in the `dist` folder.

---

## 📊 Data Source

- All dashboard data is loaded from [`public/data.json`](public/data.json).
- To update the dashboard, edit or replace this file with your own data.

---

## 📝 Project Structure

```
├── public/
│   └── data.json         # Main data file
├── src/
│   ├── components/       # UI components
│   ├── pages/
│   │   └── Index.tsx     # Main dashboard page
│   └── App.tsx           # App entry point
├── package.json
├── vite.config.ts
└── tailwind.config.ts
```

---



To deploy your own version:
- Push your code to GitHub
- Connect your repo to Netlify
- Set build command to `npm run build` and publish directory to `dist`

---

## 🙏 Credits

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Shadcn UI](https://ui.shadcn.com/)
- [Recharts](https://recharts.org/)

---

## 📄 License
