# 🚀 Ankit Singh - Space Portfolio

A stunning space-themed portfolio website built with Next.js, TypeScript, Three.js, and Tailwind CSS.

## 👨‍💻 About Me

I'm **Ankit Singh** ([@ankitbotmaker](https://github.com/ankitbotmaker)) - a passionate Full Stack Developer and AI/ML enthusiast specializing in:
- 🤖 Bot Development & Automation
- 🌐 Modern Web Applications
- 🎨 Creative Digital Solutions
- 💡 Innovative Technology Integration

## ✨ Features

- **3D Space Background**: Interactive star field using Three.js
- **Smooth Animations**: Framer Motion powered scroll animations
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Modern Stack**: Built with Next.js 14 and TypeScript
- **Performance Optimized**: Fast loading and smooth interactions
- **Black Hole Effect**: Stunning video background on hero section

## 🛠️ Tech Stack

### Frontend
- **Next.js 14** - React Framework with App Router
- **React 18** - Modern React with Hooks
- **TypeScript** - Type Safety
- **Tailwind CSS** - Utility-first CSS
- **Framer Motion** - Smooth Animations

### 3D Graphics
- **Three.js** - 3D Graphics Library
- **React Three Fiber** - React renderer for Three.js
- **@react-three/drei** - Helper components

### Tools & Libraries
- **React Icons** - Icon library
- **React Intersection Observer** - Scroll detection
- **ESLint** - Code linting
- **PostCSS** - CSS processing

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ankitbotmaker/space-portfolio.git
cd space-portfolio
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📁 Project Structure

```
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/
│   ├── main/              # Main section components
│   │   ├── About.tsx
│   │   ├── Hero.tsx
│   │   ├── Skills.tsx
│   │   ├── Projects.tsx
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   └── StarBackground.tsx
│   └── sub/               # Sub-components
│       ├── HeroContent.tsx
│       ├── ProjectCard.tsx
│       └── SkillDataProvider.tsx
├── constants/             # Data constants
│   └── index.ts          # Skills, socials, etc.
├── public/                # Static assets
│   ├── blackhole.webm    # Video background
│   └── ...               # Images and SVGs
└── utils/                 # Utility functions
    └── motion.ts         # Animation variants
```

## 🎨 Customization

### Update Personal Information

1. **Profile Details**: Edit `components/main/About.tsx`
2. **Skills**: Modify `constants/index.ts`
3. **Social Links**: Update `constants/index.ts` in the `Socials` array
4. **Hero Content**: Edit `components/sub/HeroContent.tsx`
5. **Metadata**: Update `app/layout.tsx` for SEO

### Change Theme Colors

The project uses these main colors:
- Background: `#030014` (Deep space black)
- Primary Gradient: `purple-500` to `cyan-500`
- Border: `#7042f88b` (Purple with transparency)
- Text: `white`, `gray-200`, `gray-400`

Update colors in Tailwind classes throughout components.

## 📦 Build for Production

```bash
npm run build
npm run start
```

## 🌐 Deploy

### Vercel (Recommended)
1. Push your code to GitHub
2. Import project in [Vercel](https://vercel.com)
3. Deploy with one click

### Other Platforms
- Netlify
- Railway
- AWS Amplify
- Any platform supporting Next.js

## 🎯 Key Features Explained

### 3D Star Field
- **5000 animated stars** rendered with WebGL
- Continuous rotation animation
- Optimized with frustum culling

### Video Background
- Looping black hole animation
- Responsive positioning for all screen sizes
- Minimal performance impact

### Smooth Animations
- Framer Motion for scroll animations
- Intersection Observer for triggering
- Custom animation variants in `utils/motion.ts`

### Responsive Design
- Mobile-first approach
- Breakpoints: `md: 768px`, `lg: 1024px`
- Flex layouts for adaptability

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🤝 Connect with Me

- **GitHub**: [@ankitbotmaker](https://github.com/ankitbotmaker)
- **LinkedIn**: [Ankit Singh](https://www.linkedin.com/in/ankit-singh/)
- **Email**: ankitbotmaker@gmail.com
- **Discord**: ankitbotmaker

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Original template inspired by space-themed portfolios
- Built with modern web technologies
- Three.js for amazing 3D capabilities
- Framer Motion for smooth animations

---

⭐ If you like this project, give it a star on GitHub!

**Made with ❤️ by Ankit Singh**
