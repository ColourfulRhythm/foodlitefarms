# FoodLite Farms - Deployment Guide

This guide provides step-by-step instructions for deploying the FoodLite Farms website to various hosting platforms.

## 🚀 Quick Start

### Option 1: Netlify (Recommended - Free)
1. Go to [netlify.com](https://netlify.com)
2. Sign up/Login with your GitHub account
3. Click "New site from Git" or drag and drop your project folder
4. Your site will be live in minutes with a URL like: `https://your-site-name.netlify.app`

### Option 2: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Sign up/Login with your GitHub account
3. Click "New Project" and import your repository
4. Deploy automatically with a URL like: `https://your-project.vercel.app`

### Option 3: GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at: `https://username.github.io/repository-name`

## 📁 File Structure for Deployment

Ensure your deployment includes these files:
```
foodlitefarms/
├── index.html
├── styles.css
├── script.js
├── README.md
└── DEPLOYMENT.md
```

## 🌐 Custom Domain Setup

### For Netlify:
1. Go to Site Settings > Domain Management
2. Click "Add custom domain"
3. Enter your domain name
4. Follow DNS configuration instructions

### For Vercel:
1. Go to Project Settings > Domains
2. Add your custom domain
3. Configure DNS as instructed

## 🔧 Local Development

### Using Python (Built-in)
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### Using Node.js
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server -p 8000
```

### Using PHP
```bash
php -S localhost:8000
```

## 📱 Testing Checklist

Before deploying, test these features:

- [ ] Website loads correctly
- [ ] Navigation works on mobile
- [ ] Contact form submits properly
- [ ] Phone numbers are clickable
- [ ] WhatsApp button works
- [ ] All links work correctly
- [ ] Images load properly
- [ ] Responsive design works on different screen sizes

## 🔒 Security & Performance

### HTTPS
- Most modern hosting platforms provide HTTPS automatically
- Ensure your custom domain has SSL certificate

### Performance Optimization
- Images are optimized (when added)
- CSS and JS are minified (consider using build tools)
- Enable gzip compression on your server

## 📊 Analytics Setup

### Google Analytics
1. Create a Google Analytics account
2. Get your tracking ID (GA-XXXXXXXXX)
3. Add this script to your HTML head section:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🛠️ Maintenance

### Regular Updates
- Keep contact information current
- Update product descriptions as needed
- Monitor website performance
- Check for broken links

### Backup Strategy
- Keep a local copy of all files
- Use version control (Git) for tracking changes
- Regular backups of hosting account

## 📞 Support Contacts

### Technical Issues
- Contact your web developer
- Check hosting provider documentation
- Review browser console for errors

### Content Updates
- Edit HTML files directly
- Use a code editor like VS Code
- Test changes locally before deploying

## 🎯 SEO Optimization

### Meta Tags
The website includes basic SEO meta tags. For better optimization:

1. **Google Search Console**
   - Add your site to Google Search Console
   - Submit sitemap (if you have one)

2. **Local SEO**
   - Add Google My Business listing
   - Include local keywords in content

3. **Social Media**
   - Add Open Graph tags for social sharing
   - Create social media accounts for the business

## 📈 Monitoring

### Performance Monitoring
- Use Google PageSpeed Insights
- Monitor Core Web Vitals
- Check mobile usability

### Analytics
- Track visitor behavior
- Monitor conversion rates
- Analyze traffic sources

---

**Need Help?** Contact your web developer or hosting provider support for assistance with deployment issues.
