# akibkst.dev

# Akibul Islam - Full-Stack Developer Portfolio

<div align="center">

**A modern, interactive portfolio showcasing full-stack development expertise with Next.js, TypeScript, and contemporary web technologies.**

[Live Demo](https://terminal-base-portfolio-chi.vercel.app) • [GitHub Profile](https://github.com/AkibKST) • [LinkedIn](https://linkedin.com/in/akibul-islam) • [Contact Me](#contact)

</div>

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Component Architecture](#component-architecture)
- [Performance Optimizations](#performance-optimizations)
- [Deployment](#deployment)
- [Contact & Links](#contact--links)

---

## 🎯 Overview

This is a professional, high-performance portfolio website designed to showcase full-stack development capabilities. Built with **Next.js 14** and **TypeScript**, it features a cyberpunk-inspired design with smooth animations, interactive elements, and a focus on user experience.

The portfolio demonstrates:

- ✅ Production-grade React/Next.js implementation
- ✅ Type-safe TypeScript development
- ✅ Advanced CSS animations and interactions
- ✅ Responsive design principles
- ✅ Performance-optimized components
- ✅ Accessibility best practices

---

## ✨ Features

### Core Features

- **Interactive Terminal UI** - Simulated terminal-style interface for content display
- **Smooth Scroll Animations** - Parallax effects and reveal animations on scroll
- **Matrix Rain Background** - Animated falling characters effect
- **Dynamic Typewriter Effect** - Auto-typing role list with smooth transitions
- **Live Project Showcase** - Card-based project gallery with hover interactions
- **Responsive Design** - Fully mobile-optimized interface
- **Dark Mode** - Cyberpunk/hacker aesthetic throughout
- **Custom Cursor** - Themed custom cursor following user mouse

### Interactive Elements

- **Hover Effects** - Cards expand with glow effects and animations
- **Progress Bar** - Scroll progress indicator at the top
- **Skill Animations** - Progress bars animate when scrolled into view
- **Dynamic Stats** - Counter animations for achievements
- **Toggle Navigation** - Smooth transitions between sections
- **Contact Links** - Hover-enhanced contact information

### Design Elements

- **Glitch Effect** - Animated text glitch on headings
- **Neon Glow** - Green/cyan color scheme with shadow effects
- **Code Snippets** - Floating code syntax in side columns
- **Terminal Windows** - Professional terminal-style containers
- **Status Indicators** - Color-coded availability status

---

## 🛠 Tech Stack

### Frontend

- **Framework:** Next.js 14.2.5 (React 18)
- **Language:** TypeScript 5.x
- **Styling:** Tailwind CSS + Custom CSS
- **Fonts:** Share Tech Mono, Orbitron, VT323

### Development Tools

- **Bundler:** Next.js Built-in (Webpack)
- **Linter:** ESLint with Next.js config
- **CSS Processing:** PostCSS + Autoprefixer
- **Package Manager:** npm/yarn

### Deployment

- **Hosting:** Vercel (Recommended)
- **Build System:** Next.js Build Optimization
- **CDN:** Vercel Edge Network

### Development Environment

- **Node.js:** 18+ recommended
- **Browser Support:** Modern browsers (Chrome, Firefox, Safari, Edge)

---

## 📁 Project Structure

```
akibkst-portfolio/
│
├── app/
│   ├── layout.tsx          # Root layout with metadata & fonts
│   ├── page.tsx            # Main portfolio page
│   ├── globals.css         # Global styles & animations
│   └── favicon.ico
│
├── components/
│   ├── Hero.tsx            # Hero section with typewriter effect
│   ├── About.tsx           # About section with system info JSON
│   ├── Skills.tsx          # Tech stack categories with progress bars
│   ├── Projects.tsx        # Project showcase with cards
│   ├── Approach.tsx        # Development approach methodology
│   ├── Contact.tsx         # Contact information & links
│   ├── Navbar.tsx          # Navigation with smooth scroll links
│   ├── Footer.tsx          # Footer with credits
│   ├── SideColumns.tsx     # Floating code snippet columns
│   ├── MatrixRain.tsx      # Canvas-based Matrix effect
│   ├── Cursor.tsx          # Custom cursor behavior
│   └── ProgressBar.tsx     # Scroll progress indicator
│
├── public/                 # Static assets
├── package.json            # Dependencies & scripts
├── tsconfig.json           # TypeScript configuration
├── tailwind.config.ts      # Tailwind CSS configuration
├── next.config.js          # Next.js configuration
├── postcss.config.js       # PostCSS configuration
└── .gitignore              # Git ignore patterns
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js:** 18.0.0 or higher
- **npm** or **yarn** package manager
- **Git** for version control

### Installation

1. **Clone the Repository**

```bash
git clone https://github.com/AkibKST/akibkst-portfolio.git
cd akibkst-portfolio
```

2. **Install Dependencies**

```bash
npm install
# or
yarn install
```

3. **Run Development Server**

```bash
npm run dev
# or
yarn dev
```

4. **Open in Browser**
   Navigate to `http://localhost:3000` in your web browser.

### Build for Production

```bash
npm run build
npm start
# or
yarn build
yarn start
```

---

## 🏗 Component Architecture

### Hero Component

Displays the main introduction with animated typewriter effect for role cycling.

- **Features:** Terminal UI, typewriter animation, particle effects
- **Key Props:** None (self-contained component)

### About Component

Shows professional information and statistics with counter animations.

- **Features:** JSON-style system info display, animated counters
- **Key Props:** None (self-contained component)

### Skills Component

Displays technical skills organized by categories with animated progress bars.

- **Features:** Category cards, progress bar animations on scroll
- **Key Props:** None (self-contained component)

### Projects Component

Showcases completed projects with detailed descriptions and tech stacks.

- **Features:** Project cards, live demo links, case studies
- **Key Props:** None (self-contained component)

### Approach Component

Explains development methodology and problem-solving approach.

- **Features:** Approach cards with pulse animation
- **Key Props:** None (self-contained component)

### Contact Component

Provides multiple contact channels with enhanced hover effects.

- **Features:** Contact links, interactive hover states
- **Key Props:** None (self-contained component)

### Navbar Component

Fixed navigation with smooth scroll anchoring.

- **Features:** Fixed positioning, link hover effects
- **Key Props:** None (self-contained component)

---

## ⚡ Performance Optimizations

### Code Optimization

- **Next.js Image Optimization:** Automatic WebP conversion
- **Code Splitting:** Automatic code splitting for routes
- **Tree Shaking:** Unused CSS and JavaScript removal
- **Minification:** Production bundle minification

### Runtime Performance

- **Client Components:** Strategic use of `"use client"` for interactivity
- **Intersection Observer:** Lazy animation triggering on scroll
- **requestAnimationFrame:** Smooth 60fps animations
- **CSS Animations:** GPU-accelerated transforms
- **Event Delegation:** Efficient event listener management

### Render Optimization

- **React Memo:** Component memoization where beneficial
- **useCallback:** Event handler optimization
- **useState/useEffect:** Proper hooks dependency management
- **No Unnecessary Re-renders:** Strategic component structure

### Bundle Size

- **Next.js 14:** ~65KB (gzipped)
- **No External UI Frameworks:** Custom CSS only
- **Optimized Images:** All assets WebP format
- **Tree-shaking:** Only used code in final bundle

---

## 🎨 Design System

### Color Palette

- **Primary Green:** `#00ff41` - Main accent color
- **Secondary Cyan:** `#00e5ff` - Highlights
- **Background Dark:** `#0a0a0a` - Primary background
- **Background Darker:** `#0d0d0d` - Secondary background

### Typography

- **Headings:** Orbitron (900 weight)
- **Body:** Share Tech Mono (monospace)
- **Code:** VT323 (retro computer style)

### Animation Timing

- **Fast:** 0.2s (hover effects)
- **Standard:** 0.4s - 0.6s (transitions)
- **Slow:** 1.2s - 2s (entrance animations)

---

## 📱 Responsive Design

### Breakpoints

- **Mobile:** < 640px
- **Tablet:** 640px - 1024px
- **Desktop:** > 1024px

### Mobile Optimizations

- Side columns hidden on mobile
- Simplified animations for performance
- Touch-friendly interactive elements
- Optimized font sizes for readability

---

## 🚢 Deployment

### Deploy to Vercel (Recommended)

1. **Push to GitHub**

```bash
git add .
git commit -m "Deploy portfolio"
git push origin main
```

2. **Connect to Vercel**

- Go to [vercel.com](https://vercel.com)
- Click "New Project"
- Import your GitHub repository
- Deploy with default settings

3. **Custom Domain**

- Add your domain in Vercel settings
- Update DNS records as instructed

### Environment Variables

No environment variables required for this project.

---

## 📊 SEO & Metadata

### Meta Tags

- **Title:** Configurable in `layout.tsx`
- **Description:** Professional full-stack developer pitch
- **Keywords:** Full-Stack, Next.js, TypeScript, React, etc.
- **OG Image:** Custom Open Graph protocol support

### Sitemap & Robots

- Automatic sitemap generation
- SEO-optimized URL structure
- robots.txt configured for crawlers

---

## 🔐 Security

- **No External Dependencies:** Minimal security surface
- **Content Security Policy:** Headers configured in Next.js
- **XSS Protection:** React's built-in XSS protection
- **HTTPS Only:** Enforced on production

---

## 📝 Customization Guide

### Change Personal Information

**Update in `components/Hero.tsx` and other components:**

```tsx
// Change name and role
const roles = ["Your Role Here", "Another Role"];

// Update skills
const skills = ["Your", "Skills", "Here"];
```

**Update in `app/layout.tsx`:**

```tsx
export const metadata: Metadata = {
  title: "Your Name | Your Title",
  description: "Your description here",
};
```

### Modify Color Scheme

**Update in `app/globals.css`:**

```css
:root {
  --green: #your-color;
  --cyan: #your-accent;
  /* ... other colors ... */
}
```

### Add New Sections

1. Create new component in `components/`
2. Import in `app/page.tsx`
3. Add to page layout with proper ID for navigation
4. Update Navbar links if needed

---

## 🐛 Troubleshooting

### Common Issues

**Port 3000 already in use:**

```bash
npm run dev -- -p 3001
```

**Module not found error:**

```bash
npm install
# or
rm -rf node_modules
npm install
```

**Build failure:**

```bash
npm run build -- --debug
```

---

## 📄 License

This portfolio is open source and available under the MIT License.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📞 Contact & Links

<div align="center">

**Akibul Islam** | Full-Stack Developer

| Platform    | Link                                                                 |
| ----------- | -------------------------------------------------------------------- |
| 📧 Email    | [akibkst22@gmail.com](mailto:akibkst22@gmail.com)                    |
| 📱 Phone    | [+880 1533-039625](tel:+8801533039625)                               |
| 💼 LinkedIn | [linkedin.com/in/akibul-islam](https://linkedin.com/in/akibul-islam) |
| 🐙 GitHub   | [github.com/AkibKST](https://github.com/AkibKST)                     |
| 📍 Location | Kushtia, Bangladesh                                                  |

**Status:** 🟢 Open to Work

</div>

---

## 📚 Additional Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Tailwind CSS](https://tailwindcss.com)
- [Web Performance Tips](https://web.dev/performance/)

---

<div align="center">

**Built with ❤️ by [Akibul Islam](https://github.com/AkibKST)**

**© 2025 Akibul Islam — All Rights Reserved**

</div>
