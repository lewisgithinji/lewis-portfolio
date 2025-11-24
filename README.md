# Lewis Githinji - Portfolio Website

A modern, professional portfolio website showcasing full-stack development and AI solutions expertise. Built with React, TypeScript, and Tailwind CSS.

## 🚀 Live Demo

**Production**: [lewis-portfolio.pages.dev](https://lewis-portfolio.pages.dev) (Cloudflare Pages)

## ✨ Features

- ✅ Professional photo branding with logo integration
- ✅ Comprehensive SEO optimization (meta tags, JSON-LD, Open Graph, Twitter Cards)
- ✅ Resume download (HTML format, print to PDF)
- ✅ Calendly booking integration
- ✅ Real GitHub projects showcase with live demo links
- ✅ Client testimonials section
- ✅ "How I Work" process documentation
- ✅ 6 service offerings with detailed descriptions
- ✅ International work highlights (timezones, languages, tools)
- ✅ Certifications display (Microsoft Partner, AWS, Google Cloud, Cisco)
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scroll animations with Intersection Observer
- ✅ Dark theme with emerald/cyan gradient accents
- ✅ WhatsApp and social media integration
- ✅ Security headers and caching optimization
- ✅ Sitemap and robots.txt for SEO

## 🛠️ Tech Stack

- **Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS 3.4
- **Build Tool**: Vite 5
- **Animations**: Custom CSS animations with Intersection Observer
- **Font**: Plus Jakarta Sans from Google Fonts
- **Hosting**: Cloudflare Pages
- **Version Control**: Git + GitHub

## 📦 Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/lewisgithinji/lewis-portfolio.git
cd lewis-portfolio

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The dev server will start at `http://localhost:5173/`

## 🚀 Deployment (Cloudflare Pages)

This project is configured for Cloudflare Pages deployment with automatic builds from GitHub.

### Setup Instructions:

1. **Push to GitHub** (already done)
   ```bash
   git add .
   git commit -m "Your changes"
   git push
   ```

2. **Connect to Cloudflare Pages**:
   - Go to [Cloudflare Dashboard](https://dash.cloudflare.com)
   - Navigate to "Workers & Pages"
   - Click "Create application" → "Pages" → "Connect to Git"
   - Select `lewisgithinji/lewis-portfolio` repository

3. **Configure Build Settings**:
   - **Project name**: `sirlewis` (or your preferred name)
   - **Production branch**: `main`
   - **Framework preset**: `None` or `Vite`
   - **Build command**: `npm run build`
   - **Build output directory**: `dist`

4. **Deploy**: Click "Save and Deploy"

### Automatic Deployments

Every push to the `main` branch will automatically trigger a new deployment on Cloudflare Pages.

### Configuration Files

- **`.node-version`**: Specifies Node.js 18
- **`_headers`**: Security headers and caching rules
- **`_redirects`**: URL redirects (e.g., `/resume` → `/Lewis_Githinji_Resume.html`)
- **`wrangler.toml`**: Cloudflare Workers configuration (optional)

## 📁 Project Structure

```
lewis-portfolio/
├── public/
│   ├── wech.jpg                      # Profile photo
│   ├── favicon.svg                   # Site favicon
│   ├── og-image.svg                  # Open Graph social media image
│   ├── Lewis_Githinji_Resume.html    # Downloadable resume
│   ├── robots.txt                    # Search engine crawler rules
│   ├── sitemap.xml                   # Site structure for SEO
│   ├── _headers                      # Cloudflare Pages headers
│   └── _redirects                    # Cloudflare Pages redirects
├── src/
│   ├── App.tsx                       # Main application component
│   ├── main.tsx                      # React entry point
│   └── index.css                     # Global styles + Tailwind
├── index.html                        # HTML entry with SEO meta tags
├── package.json                      # Dependencies and scripts
├── tailwind.config.js                # Tailwind configuration
├── tsconfig.json                     # TypeScript configuration
├── vite.config.ts                    # Vite configuration
└── README.md                         # This file
```

## 📝 Key Sections

### 1. Navigation
- Logo with profile photo
- Resume download button
- Smooth scroll navigation links

### 2. Hero Section
- Professional headline with gradient text
- 3 key stats (12+ years, 500+ organizations, 50+ projects)
- Calendly booking integration
- GitHub profile link

### 3. About Section
- Professional bio with international work highlights
- Timezone flexibility (EAT/GMT+3, adaptable globally)
- Languages (English, Swahili)
- Collaboration tools (Slack, Teams, Zoom, GitHub)

### 4. Skills Section
- 6 skill categories with detailed technologies
- Certifications (Microsoft Partner, AWS, Google Cloud, Cisco)

### 5. Projects Section
- 6 real projects from GitHub
- Live demo links and GitHub repo links
- Category tags and descriptions
- Projects included:
  - Datacare Platform
  - IJSSE Academic Journals
  - TNT Sacco
  - FNM Law Advocates
  - Loop Energy
  - Tusker Expeditions

### 6. How I Work Section
- 4-step process documentation
- Discovery, Design, Development, Delivery

### 7. Testimonials Section
- 3 client testimonials with names and companies

### 8. Services Section
- 6 service offerings in 3-column grid:
  - Web & Mobile Development
  - AI & Automation
  - Microsoft 365 & Google Workspace
  - Cybersecurity Services
  - Email Security Solutions
  - Digital Transformation Consulting

### 9. Contact Section
- Calendly call-to-action
- WhatsApp contact link
- Email and phone
- Social media links (GitHub, LinkedIn, Twitter, Facebook, Instagram)

### 10. Footer
- Logo branding
- Quick links
- Copyright

## 🎨 Customization

### Update Personal Information

Edit `src/App.tsx` to customize:
- Name and professional title
- Bio and experience
- Skills and certifications
- Project portfolio
- Contact information
- Social media links
- Testimonials

### Change Colors

The site uses emerald-to-cyan gradient accents. To customize:

1. Edit `tailwind.config.js` for theme colors
2. Update gradient classes in `src/App.tsx`
3. Modify `src/index.css` for global styles

### Replace Profile Photo

Replace `public/wech.jpg` with your own professional photo (recommended: square, high-resolution, professional setting).

### Update Resume

Edit `public/Lewis_Githinji_Resume.html` with your professional details. The file is designed for printing to PDF.

## 🔍 SEO Features

- Comprehensive meta tags (keywords, description, author)
- Geographic targeting (Nairobi, Kenya)
- Open Graph tags for social media sharing
- Twitter Card meta tags
- JSON-LD structured data (Person and ProfessionalService schemas)
- Canonical URLs
- Sitemap.xml for search engines
- Robots.txt for crawler guidance
- Mobile-optimized viewport
- Fast loading with Vite

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px+

## 🔒 Security & Performance

- Content Security Policy headers
- X-Frame-Options: DENY
- X-Content-Type-Options: nosniff
- Referrer-Policy: strict-origin-when-cross-origin
- Cache-Control headers for static assets
- Optimized images and assets

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Contact

- **Email**: lewis@datacare.co.ke
- **Phone**: +254 784 155 752
- **WhatsApp**: [+254 784 155 752](https://wa.me/254784155752)
- **LinkedIn**: [linkedin.com/in/waweru](https://www.linkedin.com/in/waweru/)
- **GitHub**: [github.com/lewisgithinji](https://github.com/lewisgithinji)
- **Company**: [Datacare Limited](https://datacare.co.ke)
- **Schedule a Call**: [calendly.com/sir-lewis/30min](https://calendly.com/sir-lewis/30min)

---

**Lewis Githinji** - Full-Stack Developer & AI Solutions Architect
