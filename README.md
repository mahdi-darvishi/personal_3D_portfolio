
# 🎨 3D Interactive Developer Portfolio

A modern, high-performance, and visually engaging **3D Interactive Portfolio** built with **React 19**, **Three.js**, **React Three Fiber**, and **Tailwind CSS v4**. 

This repository showcases interactive 3D models, smooth physics/math-driven animations, an interactive globe, dynamic contact forms, and responsive design tailored for all devices.

🚀 **Live Demo:** [personal-3-d-portfolio-beryl.vercel.app](https://personal-3-d-portfolio-beryl.vercel.app/)

---

## ✨ Features

- 🎭 **Interactive 3D Visuals:** Powered by `@react-three/fiber` and `@react-three/drei` for rendering complex 3D scenes seamlessly in the browser.
- 🌐 **Interactive 3D Globe:** Built using `cobe` for fast, WebGL-rendered interactive globe visualizations.
- ⚡ **Lightning Fast:** Built with **Vite 8** and **React 19** for optimized rendering and ultra-fast HMR (Hot Module Replacement).
- 🎨 **Modern Styling:** Styled using **Tailwind CSS v4** (`@tailwindcss/vite`) and `tailwind-merge` for clean, utility-first UI design.
- 🎬 **Smooth Animations:** Integrated with `motion` and `maath` for physics-based fluid transitions.
- 📬 **Functional Contact Form:** Direct email submission integrated using `@emailjs/browser`.
- 📱 **Fully Responsive:** Optimized across desktop, tablet, and mobile layouts using `react-responsive`.

---

## 🛠️ Tech Stack

### **Core**
- **Framework:** [React 19](https://react.dev/)
- **Build Tool:** [Vite 8](https://vitejs.dev/)
- **Language:** JavaScript (ES Modules)

### **3D & Math Graphics**
- **Three.js** (`three`) - 3D JavaScript Library
- **React Three Fiber** (`@react-three/fiber`) - React renderer for Three.js
- **React Three Drei** (`@react-three/drei`) - Useful helpers for R3F
- **Cobe** (`cobe`) - Lightweight WebGL Globe
- **Maath** (`maath`) - Math helpers for 3D/animation calculations

### **UI & Styling**
- **Tailwind CSS v4** (`tailwindcss`, `@tailwindcss/vite`)
- **Motion** (`motion`) - Dynamic UI animations
- **Tailwind Merge** (`tailwind-merge`)

### **Integrations & Utilities**
- **EmailJS** (`@emailjs/browser`) - Contact form email delivery
- **React Responsive** (`react-responsive`) - Media queries hook

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally on your machine.

### **Prerequisites**

Ensure you have **Node.js** (v18 or higher recommended) and **npm** installed on your system.

### **Installation & Running**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mahdi-darvishi/personal_3D_portfolio.git
   cd personal_3D_portfolio
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in Browser:**  
   Navigate to [http://localhost:5173](http://localhost:5173).

---

## 📜 Available Scripts

In the project directory, you can run:

| Command | Description |
| :--- | :--- |
| `npm run dev` | Runs the app in development mode with HMR. |
| `npm run build` | Builds the app for production to the `dist` folder. |
| `npm run preview` | Locally previews the production build. |
| `npm run lint` | Runs ESLint to check for code quality and style issues. |

---

## 🌐 Deployment

This project is deployed on **Vercel**.

To deploy your own instance:
1. Push your repository to GitHub.
2. Import the project into your [Vercel Dashboard](https://vercel.com/).
3. Vercel will automatically detect Vite and configure build settings (`npm run build`).
4. Click **Deploy**.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
