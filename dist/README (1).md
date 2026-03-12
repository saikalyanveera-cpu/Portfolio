# 🏎️ Sai Kalyan Veera — Portfolio

> Personal portfolio website built with **React**, **Three.js**, and **GSAP** — inspired by [teshank.dev](https://teshank.dev).

[![Live Demo](https://img.shields.io/badge/Live-Demo-00E5FF?style=for-the-badge&logo=vercel)](https://saikalyanveera.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/sai-kalyan-veera-7711213b6/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/saikalyanveera-cpu)

---

## ✨ Features

- **3D Animated Dog** — GLTF model loaded via `@react-three/fiber` with ambient + spot lighting
- **Floating Skill Cloud** — Three.js sprite text orbiting in 3D space
- **3D CSS Cube Project Cards** — CSS `preserve-3d` cubes that unfold on hover
- **GSAP Flip Accordion** — Experience cards that expand with elastic spring animation
- **Letter Scramble Headers** — Section titles animate in with random character cycling
- **Rotating Role Text** — Hero subtitle flips between two roles on the Y-axis
- **Fully Responsive** — Mobile nav drawer, adaptive layouts for all screen sizes

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| Framework | React 18 |
| 3D | Three.js, @react-three/fiber, @react-three/drei |
| Animation | GSAP 3 (ScrollTrigger, Flip) |
| Styling | Styled Components |
| Build | Vite |
| Deploy | Vercel |

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/saikalyanveera-cpu/portfolio.git

# Navigate into the project
cd portfolio

# Install dependencies
npm install

# Start dev server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📦 Build & Deploy

```bash
# Build for production
npm run build

# Preview the build locally
npm run preview

# Deploy to Vercel
npx vercel --prod
```

---

## 📁 Project Structure

```
src/
├── assets/
│   ├── 3d/          # GLTF models
│   └── images/      # Project screenshots
├── components/
│   ├── Navbar/      # Fixed nav with GSAP dot animation
│   ├── form/        # Brutalist button, input, textarea
│   └── ui/          # PageHeader, Grid, Logo
├── data/
│   ├── experiences.js   # Work history
│   └── projects.js      # Project cards
├── pages/
│   ├── home/        # Hero + 3D model
│   ├── Projects/    # 3D CSS cube cards + carousel
│   ├── Experience/  # GSAP accordion cards
│   ├── About/       # Bio + skill word cloud
│   └── Contact/     # Form + social links
└── utils/
    ├── colors.js    # Full color system (blue/green/yellow/pink/red)
    └── typography.js # Type scale
```

---

## 🎨 Customization

**To update your info**, edit these two files:

- `src/data/experiences.js` — work history (name, dates, role, bio, color)
- `src/data/projects.js` — project cards (title, image, description, links)

**To change colors**, each section uses a color from `src/utils/colors.js`. Pass any color object (blue, green, yellow, pink, red) to the `color` prop.

---

## 📄 License

This project is based on [teshank2137/portfolio](https://github.com/teshank2137/portfolio) by Teshank Raut, licensed under the [Apache License 2.0](LICENSE).

Portions of this code were originally developed by Teshank Raut — [teshank.dev](https://teshank.dev).

---

## 📬 Contact

**Sai Kalyan Veera**  
📧 saikalyanveera@gmail.com  
🔗 [linkedin.com/in/sai-kalyan-veera-7711213b6](https://www.linkedin.com/in/sai-kalyan-veera-7711213b6/)  
✍️ [medium.com/@kalyanvsk333](https://medium.com/@kalyanvsk333)
