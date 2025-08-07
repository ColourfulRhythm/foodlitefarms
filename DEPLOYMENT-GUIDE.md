# 🚀 FoodLite Farms - Deployment Guide

## Option 1: GitHub Pages (Recommended - Free)

### Step 1: Enable GitHub Pages
1. Go to https://github.com/ColourfulRhythm/foodlitefarms
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in the left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, select **main** and **/(root)**
6. Click **Save**

### Step 2: Wait for Deployment
- GitHub will automatically build and deploy your site
- You'll see a green checkmark when deployment is complete
- Your site will be live at: `https://colourfulrhythm.github.io/foodlitefarms`

### Step 3: Custom Domain (Optional)
1. In the same Pages settings
2. Under **Custom domain**, enter your domain (e.g., `foodlitefarms.com`)
3. Click **Save**
4. Update your DNS settings with your domain provider

---

## Option 2: Vercel (Alternative - Free)

### Step 1: Sign up for Vercel
1. Go to https://vercel.com
2. Sign up with your GitHub account
3. Click **New Project**

### Step 2: Import Repository
1. Find and select `foodlitefarms` from your GitHub repositories
2. Click **Import**
3. Keep default settings and click **Deploy**

### Step 3: Your Site is Live
- Vercel will automatically deploy your site
- You'll get a URL like: `https://foodlitefarms-xxx.vercel.app`
- You can add a custom domain in the Vercel dashboard

---

## Option 3: Netlify (Alternative - Free)

### Step 1: Sign up for Netlify
1. Go to https://netlify.com
2. Sign up with your GitHub account
3. Click **New site from Git**

### Step 2: Connect Repository
1. Choose GitHub
2. Select `foodlitefarms` repository
3. Keep default settings and click **Deploy site**

### Step 3: Your Site is Live
- Netlify will deploy your site automatically
- You'll get a URL like: `https://random-name.netlify.app`
- You can add a custom domain in the Netlify dashboard

---

## 🌐 Quick Deploy Links

### GitHub Pages
- **Repository**: https://github.com/ColourfulRhythm/foodlitefarms
- **Settings**: https://github.com/ColourfulRhythm/foodlitefarms/settings/pages
- **Live URL**: https://colourfulrhythm.github.io/foodlitefarms (after enabling Pages)

### Vercel
- **Dashboard**: https://vercel.com/dashboard
- **Deploy**: https://vercel.com/new

### Netlify
- **Dashboard**: https://app.netlify.com
- **Deploy**: https://app.netlify.com/start

---

## 📱 Testing Your Deployment

After deployment, test these features:
- [ ] Website loads correctly
- [ ] Navigation works on mobile
- [ ] Contact form submits properly
- [ ] Phone numbers are clickable
- [ ] WhatsApp button works
- [ ] All images load properly
- [ ] Responsive design works

---

## 🔄 Updating Your Site

### For GitHub Pages:
```bash
# Make changes locally
git add .
git commit -m "Update description"
git push origin main
# GitHub Pages will automatically redeploy
```

### For Vercel/Netlify:
- Changes are automatically deployed when you push to GitHub
- No additional steps needed

---

## 🎯 Recommended: GitHub Pages

**Why GitHub Pages is recommended:**
- ✅ Completely free
- ✅ Automatic deployment from GitHub
- ✅ Custom domain support
- ✅ SSL certificate included
- ✅ Fast and reliable
- ✅ Easy to manage

**Next Steps:**
1. Go to https://github.com/ColourfulRhythm/foodlitefarms/settings/pages
2. Enable GitHub Pages
3. Wait 2-5 minutes for deployment
4. Your site will be live!

---

**Need Help?** 
- GitHub Pages: https://docs.github.com/en/pages
- Vercel: https://vercel.com/docs
- Netlify: https://docs.netlify.com
