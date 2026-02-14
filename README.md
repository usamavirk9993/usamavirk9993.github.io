# Usama Virk - Portfolio Website

A highly professional, modern portfolio website showcasing your skills, projects, and experience as a Full-Stack Web Developer.

## 🎨 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast Loading**: Optimized HTML/CSS with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Contact Form**: Integrated contact form ready to connect
- **Downloadable Resume**: Direct download link for your resume

## 📁 Files Included

1. `index.html` - Main portfolio website
2. `profile.png` - Your profile photo
3. `Usama_Virk_Resume_Enhanced.docx` - Your professional resume

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended - FREE)

1. **Create a GitHub repository**
   - Go to https://github.com/new
   - Name it: `usamavirk9993.github.io`
   - Make it public
   - Don't initialize with README

2. **Upload your files**
   ```bash
   # In your terminal
   git init
   git add index.html profile.png Usama_Virk_Resume_Enhanced.docx
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin https://github.com/usamavirk9993/usamavirk9993.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from branch
   - Branch: main
   - Folder: / (root)
   - Click Save

4. **Your site will be live at**: `https://usamavirk9993.github.io`

5. **Add custom domain (Optional)**
   - Buy domain `usamavirk.dev` from Namecheap/GoDaddy
   - In GitHub repo settings → Pages → Custom domain
   - Add: `usamavirk.dev`
   - In your domain provider's DNS settings, add:
     - Type: A, Host: @, Value: 185.199.108.153
     - Type: A, Host: @, Value: 185.199.109.153
     - Type: A, Host: @, Value: 185.199.110.153
     - Type: A, Host: @, Value: 185.199.111.153
     - Type: CNAME, Host: www, Value: usamavirk9993.github.io

### Option 2: Vercel (FREE - Easiest)

1. Go to https://vercel.com
2. Sign up with GitHub
3. Click "Add New" → "Project"
4. Import your GitHub repository
5. Click Deploy
6. Done! Your site is live instantly

**Custom Domain on Vercel:**
- Go to Project Settings → Domains
- Add `usamavirk.dev`
- Follow DNS instructions

### Option 3: Netlify (FREE)

1. Go to https://netlify.com
2. Drag and drop your folder (with all 3 files)
3. Site is live immediately!

**Custom Domain on Netlify:**
- Site Settings → Domain Management
- Add custom domain
- Follow DNS instructions

### Option 4: Traditional Hosting (cPanel)

1. Login to your hosting cPanel
2. Go to File Manager
3. Navigate to `public_html`
4. Upload all files
5. Your site is live at your domain

## 📧 Contact Form Setup

The contact form currently uses Formspree placeholder. To activate it:

1. Go to https://formspree.io
2. Sign up for free
3. Create a new form
4. Copy your form endpoint
5. In `index.html`, find line with `action="https://formspree.io/f/YOUR_FORM_ID"`
6. Replace `YOUR_FORM_ID` with your actual Formspree ID

**Alternative:** Use EmailJS, Web3Forms, or your own backend API

## 🎨 Customization

### Change Colors
Edit the CSS variables in `index.html`:
```css
:root {
    --primary: #0A2463;        /* Main blue color */
    --accent: #3B82F6;         /* Accent blue */
    /* ... other colors */
}
```

### Update Content
All content is in `index.html`:
- Hero section: Lines 500-530
- About: Lines 540-560
- Skills: Lines 570-650
- Projects: Lines 660-850
- Contact: Lines 860-930

### Add More Projects
Copy a project card block and modify:
```html
<div class="project-card">
    <div class="project-image">🎯</div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Description here</p>
        <!-- ... -->
    </div>
</div>
```

## ✅ Before Going Live - Checklist

- [ ] Update contact form with your Formspree/EmailJS ID
- [ ] Test on mobile devices
- [ ] Verify all links work
- [ ] Check resume downloads correctly
- [ ] Test contact form submissions
- [ ] Add Google Analytics (optional)
- [ ] Set up custom domain

## 🔧 Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
- **Fonts**: Google Fonts (Syne + DM Sans)
- **Browser Support**: All modern browsers
- **Load Time**: < 2 seconds
- **Mobile Friendly**: 100% responsive

## 📱 Social Media

Don't forget to update your social profiles:
- Update LinkedIn with portfolio link
- Update GitHub profile README
- Add portfolio link to email signature

## 🎯 Next Steps

1. Deploy to GitHub Pages (5 minutes)
2. Set up contact form (5 minutes)
3. Share on LinkedIn/Twitter
4. Add to resume header
5. Include in job applications

## 📞 Need Help?

If you face any issues during deployment, common solutions:

**GitHub Pages not showing:**
- Wait 5-10 minutes after first deploy
- Check Settings → Pages is enabled
- Ensure files are in root directory

**Custom domain not working:**
- DNS propagation takes 24-48 hours
- Double-check DNS records
- Clear browser cache

**Contact form not working:**
- Verify Formspree endpoint is correct
- Check browser console for errors
- Test with a different email

---

**Your portfolio is ready! Deploy it now and start landing those remote jobs! 🚀**

Made with ❤️ for Usama Virk
