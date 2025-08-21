---

# 🚀 React + Vite + TailwindCSS Starter Template

A streamlined setup for building modern React applications with Vite, styled using Tailwind CSS, and enhanced with essential development tools.

## ✨ Key Features

- **⚡ Vite** – Lightning-fast build and development environment.
- **⚛️ React** – Build dynamic user interfaces with the latest React version.
- **🎨 Tailwind CSS** – Utility-first CSS framework for rapid UI development.
- **🔍 ESLint** – Enforce code quality and consistency.
- **🧠 Redux Toolkit** – Simplified state management.
- **🔔 React Hot Toast** – Elegant toast notifications.
- **🧭 React Router DOM** – Declarative routing for single-page apps.

---

## 🛠️ Getting Started

### 1. Create a Vite Project

```bash
npm create vite@latest
```

Choose:
- Project name: `paste`
- Framework: `React`
- Variant: `JavaScript` or `TypeScript`

Then:

```bash
cd paste
```

### 2. Set Up Tailwind CSS

Install dependencies:

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

Update `tailwind.config.js`:

```js
export default {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  theme: { extend: {} },
  plugins: [],
}
```

Add Tailwind directives to `src/index.css`:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### 3. Install Project Dependencies

```bash
npm install
```

### 4. Start Development Server

```bash
npm run dev
```

Visit: `http://localhost:5173`

---

## 📜 Available Scripts

| Command           | Description                              |
|------------------|------------------------------------------|
| `npm run dev`     | Start development server with HMR        |
| `npm run build`   | Build for production                     |
| `npm run preview` | Preview production build                 |
| `npm run lint`    | Run ESLint for code analysis             |

---

## 📦 Packages Overview

### Dependencies

- `@reduxjs/toolkit`
- `lucide-react`
- `react`, `react-dom`
- `react-hot-toast`
- `react-redux`
- `react-router-dom`

### Dev Dependencies

- ESLint & plugins (`eslint`, `eslint-plugin-react`, etc.)
- Tailwind CSS & PostCSS
- Vite & React plugin
- TypeScript types (if applicable)

---

## 📁 Project Structure

```
paste/
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .eslintrc.js
├── tailwind.config.js
├── postcss.config.js
├── vite.config.js
└── package.json
```

---

## 🎯 Tailwind Configuration

Tailwind scans files in `src/` and `index.html` for class usage. Customize themes and plugins as needed.

---
