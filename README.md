# 🚀 Sanket's Portfolio

A modern, responsive, and performance-optimized portfolio website showcasing technical expertise in **Azure Cloud**, **DevOps**, and **Full-Stack Development**.

**Live Demo:** [sanketswani.in](https://sanketswani.in)

---

## 📋 About

Technical Lead with **8+ years of experience** in:
- ☁️ **Microsoft Azure Cloud** (AKS, App Service, Cosmos DB, Azure SQL, Key Vault)
- 🔧 **DevOps & Infrastructure as Code** (GitHub Actions, Docker, Kubernetes, Terraform, Helm)
- 💻 **Full-Stack Development** (.NET Core, Angular, TypeScript/JavaScript)
- 🏆 **Cloud Migrations** (Led 100+ application migrations to Azure)

### Certifications
- 🎓 **CKA** — Certified Kubernetes Administrator (Linux Foundation)
- 🎓 **AZ-305** — Azure Solutions Architect Expert (Microsoft)
- 🎓 **AZ-500** — Azure Security Engineer Associate (Microsoft)
- 🎓 **AZ-104** — Azure Administrator Associate (Microsoft)
- 🎓 **AZ-204** — Azure Developer Associate (Microsoft)
- 🎓 **GitHub Actions** — Certified for GitHub Actions (GitHub)

---

## ⚡ Features

### Performance Optimizations
- **WebP Image Format** — All images converted to WebP for 60%+ file size reduction
- **Lazy Loading** — Non-critical images lazy-loaded for faster First Contentful Paint
- **Minified Assets** — Optimized CSS and JavaScript
- **Deferred Scripts** — Non-blocking script loading with `defer` attribute
- **DNS Prefetch** — Preconnect to Google Fonts and CDN resources

### Technical Stack
- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Animations:** AOS (Animate on Scroll)
- **Image Gallery:** GLightbox, Isotope Layout, ImagesLoaded
- **Contact Form:** EmailJS for serverless form submission
- **Responsive Design:** Mobile-first, fully responsive layout

### Accessibility
- Semantic HTML structure
- ARIA labels and alt text for all images
- Keyboard navigation support
- High contrast color scheme

---

## 📁 Project Structure

```
portfolio/
├── index.html                 # Main portfolio page
├── assets/
│   ├── css/
│   │   ├── main.css          # Main stylesheet
│   │   └── vendor/           # Vendor CSS (Bootstrap, AOS, GLightbox)
│   ├── js/
│   │   ├── main.js           # Custom JavaScript
│   │   └── vendor/           # Vendor JS libraries
│   ├── img/
│   │   ├── profile/          # Profile images (WebP optimized)
│   │   ├── certifications/   # Certification badges (WebP)
│   │   ├── awards/           # Award certificates (WebP)
│   │   └── misc/             # Miscellaneous assets
│   └── resume/               # Resume files
├── helm_values/              # Kubernetes Helm configurations
│   ├── values.yaml
│   ├── values-ite.yaml
│   └── templates/
├── Dockerfile                # Docker image configuration
├── convert_to_webp.sh        # Image conversion script
└── .gitignore               # Git ignore rules
```

---

## 🎯 Key Sections

### 1. **Hero Section**
Eye-catching introduction with call-to-action buttons and key statistics.

### 2. **About**
Professional summary with personal details and key credentials.

### 3. **Skills**
Four core competency areas with proficiency indicators:
- Azure Infrastructure & Services (90%)
- DevOps Tools (95%)
- Scripting & Automation (80%)
- Software Development & Programming (70%)

### 4. **Work Experience**
Timeline of professional roles and achievements at Tata Consultancy Services.

### 5. **Education**
Academic background (Bachelor of Engineering, Computer Science).

### 6. **Certifications**
Interactive carousel showcasing all industry certifications with links to verify.

### 7. **Awards & Recognitions**
Gallery of professional awards and team recognition certificates.

### 8. **Contact**
Contact information and integrated contact form with EmailJS.

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- For local development: Node.js (optional, for build tools)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sanketswani/portfolio.git
   cd portfolio
   ```

2. **Open in browser:**
   ```bash
   open index.html
   ```
   Or use a local HTTP server:
   ```bash
   python3 -m http.server 8000
   # Visit http://localhost:8000
   ```

### Docker Deployment

Build and run with Docker:
```bash
docker build -t sanketswani/portfolio:v2.0 .
docker run -p 8080:80 sanketswani/portfolio:v2.0
```

### Kubernetes Deployment

Deploy to Kubernetes using Helm:
```bash
helm install portfolio ./helm_values \
  -f helm_values/values.yaml
```

---

## 📊 Performance Metrics

| Metric | Before | After | Improvement |
|--------|--------|-------|------------|
| **Total Image Size** | ~24 MB | ~5.1 MB | 78% reduction |
| **Page Load Time** | ~44s | ~3-4s | 91% faster |
| **First Contentful Paint** | ~15s | ~1.5s | 90% faster |
| **Lighthouse Score** | N/A | 95+ | ⭐ Excellent |

---

## 📝 Configuration

### Contact Form Setup

The contact form uses **EmailJS**. To enable submissions:

1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create an email service and template
3. Update the public key in `index.html`:
   ```javascript
   emailjs.init({
     publicKey: "YOUR_PUBLIC_KEY"
   });
   ```
---

## 📞 Contact

- **Email:** [wanisankets@gmail.com](mailto:wanisankets@gmail.com)
- **Phone:** +91 9689816185
- **LinkedIn:** [sanket-wani](https://www.linkedin.com/in/sanket-wani-2753b4122)
- **GitHub:** [@sanketswani](https://github.com/sanketswani)
- **Location:** Pune, Maharashtra, India

---

## 📚 Resources

### Cloud & DevOps
- [Microsoft Azure Documentation](https://learn.microsoft.com/en-us/azure/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)

### Web Performance
- [Web.dev Performance Guide](https://web.dev/performance/)
- [WebP Image Format](https://developers.google.com/speed/webp)

### Frontend Technologies
- [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.0/)
- [MDN Web Docs](https://developer.mozilla.org/)

---

**Last Updated:** February 7, 2026  
**Version:** 3.0

Made with ❤️ by Sanket Wani
