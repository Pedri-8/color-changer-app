# 🎨 Color Changer App

A simple and responsive React + Vite + Tailwind CSS web app that lets users change the background color of the screen by clicking on color-coded buttons. This project demonstrates React's `useState` hook, event handling, and clean styling with Tailwind CSS.

---

## 🔥 Features

- Instantly change background color using color buttons
- Includes 11 colors: Red, Green, Blue, Olive, Gray, Yellow, Pink, Purple, Lavender, White, Black
- Smooth transitions with `duration` styling
- Responsive layout with Tailwind CSS
- Fully deployable via GitHub Pages

---

## ⚙️ Tech Stack

- **React** (via Vite)
- **Tailwind CSS**
- **GitHub Pages** (deployment)

---

## 🛠️ Getting Started

Clone and run locally:

```bash
git clone https://github.com/Pedri-8/color-changer-app.git 
cd color-changer-app
npm install
npm run dev
```

---

## 🚀 Deployment

1. Update `vite.config.js`:

```js
export default defineConfig({
  base: '/color-changer-app/',
  plugins: [react()],
})
```

2. Add this to `package.json`:

```json
"homepage": "https://pedri-8.github.io/color-changer-app",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

3. Deploy to GitHub Pages:

```bash
npm run build
npm run deploy
```

---

## 🌍 Live Demo

👉 [https://pedri-8.github.io/color-changer-app](https://pedri-8.github.io/color-changer-app)

---

## 🙌 Credits

This project is based on the [Chai aur React](https://github.com/hiteshchoudhary/chai-aur-react/tree/main/04bgChanger) tutorial series by [Hitesh Choudhary](https://github.com/hiteshchoudhary).  
Adapted and deployed by [Snehashis (Pedri-8)](https://github.com/Pedri-8)

---

