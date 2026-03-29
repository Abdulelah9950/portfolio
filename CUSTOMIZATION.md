# 🎯 QUICK CUSTOMIZATION GUIDE

Follow these steps in order to customize your portfolio with YOUR information. This should take 10-15 minutes!

## Step 1: Update Hero Section (1 minute)

Open `index.html` and find line ~60:

```html
<h1 class="hero-title">Abdulelah</h1>
<p class="hero-subtitle">Computer Science Student | Backend Developer | AI/NLP Enthusiast</p>
<p class="hero-description">
    Building scalable web applications and AI-powered solutions. Graduating June 2026.
    Open to co-op and internship opportunities.
</p>
```

**✏️ TO CUSTOMIZE:**
Replace `Abdulelah` with your name
Update the subtitle to match your focus
Update the description with your goals

---

## Step 2: Update Contact Information (2 minutes)

Find the Contact Section around line ~480 and update:

```html
<!-- Your Email -->
<a href="mailto:your-email@example.com">your-email@example.com</a>

<!-- Your Phone -->
<a href="tel:+966xxxxxxxxxx">+966 XX XXX XXXX</a>

<!-- Your Location -->
<p>Saudi Arabia</p>
```

**✏️ TO CUSTOMIZE:**
Replace `your-email@example.com` with your actual email
Replace phone number with your actual number
Update location if needed

---

## Step 3: Update Social Links (2 minutes)

Find these lines and replace with YOUR profiles:

```html
<!-- Line ~80 and ~85 in Hero section -->
<a href="https://github.com" target="_blank" rel="noopener noreferrer">
<a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">

<!-- Also at the bottom, around line ~530 -->
<a href="https://github.com" target="_blank" rel="noopener noreferrer">
<a href="https://linkedin.com" target="_blank" rel="noopener noreferrer">
```

**✏️ TO CUSTOMIZE:**
Replace `https://github.com` with `https://github.com/YOUR-USERNAME`
Replace `https://linkedin.com` with `https://linkedin.com/in/YOUR-PROFILE`

---

## Step 4: Update Project Links (5 minutes)

For each project card, find the Live Demo and GitHub links:

**PROJECT 1: Freelancer Platform** (around line ~250)
```html
<a href="#" class="project-link" target="_blank">  <!-- Change # to your live URL or remove link -->
    <i class="fas fa-globe"></i> Live Demo
</a>
<a href="https://github.com" class="project-link" target="_blank">  <!-- Add your repo URL -->
    <i class="fab fa-github"></i> GitHub
</a>
```

**PROJECT 2: AI Hotel Search** (around line ~290)
```html
<!-- Update links here -->
```

**PROJECT 3: Library Management** (around line ~330)
```html
<!-- Update links here -->
```

**PROJECT 4: Game Selling Platforms** (around line ~370)
```html
<!-- Update links here -->
```

**✏️ FOR EACH PROJECT:**
- Change `#` to your live demo URL (or use `javascript:void(0)` if no live demo)
- Replace GitHub links with your actual repository URLs
- Update project descriptions if needed

---

## Step 5: Add Your CV (2 minutes)

1. Save your CV as `cv.pdf`
2. Place it in the same folder as `index.html`
3. The download button will automatically work!

**✏️ If you don't have a PDF:**
- Export your CV as PDF from Word/Google Docs
- Rename it to `cv.pdf`
- Place it in the portfolio folder

---

## Step 6: Optional - Update Skills (if you want to add/remove)

Open `index.html` and find the Skills Section (around line ~160):

```html
<span class="skill-badge">Laravel</span>
<span class="skill-badge">PHP</span>
<span class="skill-badge">MySQL</span>
```

**✏️ TO CUSTOMIZE:**
Add or remove skills as needed. The layout will automatically adjust!

---

## Step 7: Optional - Update About Section

Find the About Section (around line ~115):

```html
<p>
    I'm a passionate Computer Science student with a strong focus on backend development and 
    artificial intelligence...
</p>
```

**✏️ TO CUSTOMIZE:**
Update with your personal story (2-3 paragraphs recommended)

---

## Step 8: Test Everything!

1. Open `index.html` in your browser
2. Check that all links work (hover over them)
3. Test the contact form (should show success message)
4. Check mobile view (make browser narrower)
5. Verify all your info appears correctly

---

## 🎨 OPTIONAL: Customize Colors

To change the accent color scheme, open `styles.css` and find the `:root` section (line ~7):

```css
:root {
    --primary-color: #00d4ff;      /* Cyan - change this */
    --secondary-color: #7c3aed;    /* Purple - or this */
    --background: #0a0e27;         /* Dark background */
    --text-primary: #e2e8f0;       /* Light text */
    --accent: #00d4ff;             /* Matches primary */
}
```

**Color ideas:**
- Modern: #00d4ff (current cyan)
- Professional: #6366f1 (indigo)
- Energetic: #ec4899 (pink)
- Natural: #10b981 (green)
- Warm: #f97316 (orange)

---

## 🚀 Final Checklist

Before deployment, verify:

- ✅ Name updated in all sections
- ✅ Email and phone updated
- ✅ GitHub and LinkedIn links working
- ✅ All project links updated
- ✅ Project descriptions accurate
- ✅ Skills match your abilities
- ✅ About section sounds like YOU
- ✅ CV file added (cv.pdf)
- ✅ Mobile view looks good
- ✅ All buttons clickable
- ✅ Contact form submits

---

## 📱 How to Test Mobile

1. Open portfolio on desktop
2. Press `F12` or right-click → "Inspect"
3. Click the phone/tablet icon at top-left of DevTools
4. Toggle between different devices
5. Check hamburger menu works

---

## 🆘 Help!

**Form not sending emails?**
→ See README.md for email setup instructions

**Links not working?**
→ Check you've replaced # with actual URLs
→ Make sure URLs start with https://

**Colors look weird?**
→ Clear browser cache (Ctrl+Shift+Delete)

**Mobile menu not showing?**
→ Open README.md troubleshooting section

---

## ✅ You're Done!

Your portfolio is now ready to impress! 🎉

**Next steps:**
1. Deploy to GitHub Pages or Netlify (see README.md)
2. Share with companies
3. Get that co-op/internship! 🚀

---

**Questions?** Check README.md for more details on any topic.
