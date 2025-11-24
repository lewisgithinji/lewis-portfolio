# Lewis Githinji - Portfolio Website

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS.

## 🚀 Live Demo

- **Free hosting**: `lewisgithinji.vercel.app` or `lewisgithinji.netlify.app`
- **Custom domain**: `lewisgithinji.dev` (optional)

## 🛠️ Tech Stack

- **Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Animations**: CSS animations with Intersection Observer

## 📦 Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/lewisgithinji/portfolio.git
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🚀 Deployment Options

### Option 1: Vercel (Recommended)

1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

Your site will be live at: `your-project-name.vercel.app`

### Option 2: Netlify

1. Push code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Connect your GitHub repository
5. Build command: `npm run build`
6. Publish directory: `dist`
7. Click "Deploy"

Your site will be live at: `your-project-name.netlify.app`

### Option 3: GitHub Pages

1. Install gh-pages: `npm install -D gh-pages`
2. Add to package.json scripts:
   ```json
   "predeploy": "npm run build",
   "deploy": "gh-pages -d dist"
   ```
3. Run: `npm run deploy`

## 🌐 Custom Domain Setup

### Buying a .dev domain

1. **Cloudflare** (~$10/year): [cloudflare.com/products/registrar](https://www.cloudflare.com/products/registrar/)
2. **Namecheap** (~$10.98/year): [namecheap.com](https://namecheap.com)
3. **Google Domains** (~$12/year): [get.dev](https://get.dev)

### Connecting to Vercel

1. Go to your project settings in Vercel
2. Click "Domains"
3. Add your custom domain (e.g., `lewisgithinji.dev`)
4. Update DNS records as instructed

### Connecting to Netlify

1. Go to Site settings → Domain management
2. Add custom domain
3. Follow DNS configuration instructions

## 📝 Customization

### Update Personal Info

Edit `src/App.tsx`:

- Hero section: Name, title, description
- About section: Bio, education, location
- Skills section: Add/remove technologies
- Projects section: Update portfolio items
- Contact section: Email, phone, social links

### Update Colors

Edit `tailwind.config.js` or update the CSS variables in `src/index.css`.

### Add Your Photo

Replace the initials placeholder in the About section with:

```tsx
<img 
  src="/your-photo.jpg" 
  alt="Lewis Githinji" 
  className="w-full h-full object-cover"
/>
```

## 📱 Features

- ✅ Fully responsive design
- ✅ Smooth scroll animations
- ✅ Dark theme optimized
- ✅ SEO optimized with meta tags
- ✅ Fast loading with Vite
- ✅ Accessible navigation
- ✅ Contact section with email/phone
- ✅ Social media links

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Contact

- **Email**: lewis@datacare.co.ke
- **Phone**: +254 784 155 752
- **Company**: [Datacare Limited](https://datacare.co.ke)

---

Built with ❤️ by Lewis Githinji
