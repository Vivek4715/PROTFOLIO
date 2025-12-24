# Vivek Yadav - Portfolio Website

A world-class personal portfolio website built with React, TypeScript, TailwindCSS, and Framer Motion. Features modern design, smooth animations, and responsive layouts inspired by top Dribbble/Behance portfolios.

## ✨ Features

- **Modern Design**: Clean, minimalistic UI with premium aesthetics
- **Responsive**: Mobile-first design that works on all devices
- **Dark/Light Mode**: Seamless theme switching with system preference detection
- **Smooth Animations**: Powered by Framer Motion for delightful user experience
- **Interactive Components**: Hover effects, scroll animations, and micro-interactions
- **Performance Optimized**: Fast loading with optimized images and code splitting
- **SEO Ready**: Meta tags, semantic HTML, and proper structure

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript
- **Styling**: TailwindCSS, Custom CSS
- **Animations**: Framer Motion
- **UI Components**: shadcn/ui, Radix UI
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: Ready for Vercel, Netlify, GitHub Pages

## 🚀 Quick Start

### Prerequisites

- Node.js 16+ and npm installed
- Git for version control

### Local Development

```bash
# Clone the repository
git clone <YOUR_GIT_URL>
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install

# Start development server
npm run dev

# Open http://localhost:8080 in your browser
```

### Build for Production

```bash
# Create production build
npm run build

# Preview production build locally
npm run preview
```

## 🌐 Deployment Options

### 1. Vercel (Recommended)

**Option A: One-click deployment**
1. Visit [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Click "Deploy" - automatic builds on every push

**Option B: Vercel CLI**
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy from project directory
vercel

# Follow the prompts for configuration
```

### 2. Netlify

**Option A: Drag & Drop**
1. Run `npm run build`
2. Visit [netlify.com](https://netlify.com)
3. Drag the `dist` folder to the deploy area

**Option B: GitHub Integration**
1. Connect your GitHub repository
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Deploy automatically on every push

### 3. GitHub Pages

```bash
# Install gh-pages
npm install --save-dev gh-pages

# Add to package.json scripts:
# "predeploy": "npm run build",
# "deploy": "gh-pages -d dist"

# Deploy to GitHub Pages
npm run deploy
```

**GitHub Pages Setup:**
1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `gh-pages` branch
4. Your site will be available at `https://yourusername.github.io/repository-name`

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # shadcn/ui components
│   ├── Hero.tsx        # Hero section
│   ├── About.tsx       # About section
│   ├── Skills.tsx      # Skills showcase
│   ├── Projects.tsx    # Project portfolio
│   ├── Contact.tsx     # Contact form
│   ├── Navigation.tsx  # Header navigation
│   ├── Footer.tsx      # Footer component
│   └── ThemeToggle.tsx # Dark/light mode toggle
├── assets/             # Images and static files
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── pages/              # Page components
└── styles/             # Global styles
```

## 🎨 Customization

### Adding Your Information

1. **Personal Details**: Update name, title, and bio in respective components
2. **Profile Image**: Replace `src/assets/profile-placeholder.jpg` with your photo
3. **Projects**: Update project data in `src/components/Projects.tsx`
4. **Social Links**: Update URLs in `src/components/Contact.tsx` and `src/components/Footer.tsx`
5. **Skills**: Modify skills array in `src/components/Skills.tsx`

### Styling Customization

- **Colors**: Edit design tokens in `src/index.css`
- **Fonts**: Add Google Fonts in `index.html` and configure in `tailwind.config.ts`
- **Animations**: Modify Framer Motion variants in component files
- **Layout**: Adjust spacing and sizing using Tailwind classes

### Adding New Sections

1. Create new component in `src/components/`
2. Import and add to `src/pages/Index.tsx`
3. Update navigation in `src/components/Navigation.tsx`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💡 Tips for Success

- **Images**: Replace placeholder images with high-quality, optimized versions
- **Content**: Write compelling copy that showcases your unique value proposition
- **Performance**: Optimize images and test loading speed
- **SEO**: Update meta tags in `index.html` for better search visibility
- **Analytics**: Add Google Analytics or similar tracking
- **Domain**: Consider purchasing a custom domain for professional credibility

## 🐛 Issues & Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) section
2. Create a new issue with detailed description
3. Include browser version and error messages

---

**Built with ❤️ by Vivek Yadav**

*Ready to showcase your skills to the world? Deploy this portfolio and land your dream job!*
