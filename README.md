# 3D Button Component with Framer Motion

A stunning 3D interactive button component built with Next.js 15 and Framer Motion, featuring perspective transformations and smooth animations.

![Component Preview](https://img.shields.io/badge/Next.js-15.3.3-black?style=for-the-badge&logo=next.js)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-12.15.0-blue?style=for-the-badge&logo=framer)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)

## ✨ Features

- **3D Perspective Effects** - CSS perspective and transform-style for depth
- **Smooth Animations** - Powered by Framer Motion
- **Interactive Hover States** - Dynamic rotation and shadow effects
- **Responsive Design** - Works across all screen sizes
- **TypeScript Support** - Fully typed for better DX
- **TailwindCSS 4** - Modern utility-first styling

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/YogiRajNeelamsetti/button-component-framer-motion.git

# Navigate to project directory
cd component1

# Install dependencies
npm install
# or
yarn install
# or
pnpm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the component in action.

## 📦 Tech Stack

- **Framework:** Next.js 15.3.3
- **Animation:** Framer Motion 12.15.0
- **Styling:** TailwindCSS 4
- **Language:** TypeScript 5
- **Font:** Geist (Vercel)

## 🎨 Component Structure

```
component1/
├── src/
│   └── app/
│       ├── page.tsx       # Main page
│       ├── layout.tsx     # Root layout
│       └── globals.css    # Global styles
├── components/
│   └── Content.tsx        # 3D Button component
└── public/
```

## 💻 Usage

Import the component into your project:

```tsx
import { Content } from '@/components/Content';

export default function Page() {
  return <Content />;
}
```

## 🎯 Animation Properties

The button features:
- **Hover Effects:** 3D rotation (X: 15°, Y: 10°) with elevation
- **Box Shadow:** Dynamic glow effect on hover
- **Tap Feedback:** Subtle press animation
- **Smooth Transitions:** Optimized for performance

## 🌐 Deployment

### Deploy on Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YogiRajNeelamsetti/button-component-framer-motion)

1. Push your code to GitHub
2. Import the project to [Vercel](https://vercel.com)
3. Vercel will automatically detect Next.js and deploy

### Deploy on Netlify

```bash
npm run build
```

Deploy the `.next` output directory to Netlify.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👤 Author

Yogi Raj - [@im_yogiraj](https://twitter.com/im_yogiraj)

---

⭐ Star this repo if you find it helpful!
