# Warner Classic Aero Website - Easy Update Guide

Welcome! This guide will help you update your website easily, even if you're new to GitHub.

## 🎯 Quick Start: How to Edit Your Website

### The Basics
Your website automatically updates when you make changes to files in this GitHub repository. Any change you make will appear on your live site in about 1 minute!

---

## 📝 Editing Text on Any Page

1. **Go to:** https://github.com/Marsdirt/warnerclassic-website
2. **Click on the file** you want to edit:
   - `index.html` - Homepage
   - `about.html` - About page
   - `contact.html` - Contact page
   - `projects.html` - Projects page
3. **Click the pencil icon** (✏️) in the top right that says "Edit this file"
4. **Make your changes** to the text
5. **Scroll to the bottom** and click the green "Commit changes" button
6. **Wait about 1 minute** - your website will update automatically!

---

## 📸 Adding Aircraft Photos to Projects Page

### Step 1: Upload Your Photos

1. Go to https://github.com/Marsdirt/warnerclassic-website
2. Click "Add file" → "Upload files"
3. Drag your aircraft photos into the box
4. Give them simple names like: `aircraft1.jpg`, `cessna-restoration.jpg`, etc.
5. Click "Commit changes"

### Step 2: Add the Project to Your Page

1. Click on `projects.html`
2. Click the pencil icon to edit
3. Find this section:

```html
<div class="project-item">
    <h3>Project Coming Soon</h3>
    <p>Check back soon to see our latest restoration projects.</p>
</div>
```

4. **Replace it with** (use your own photo name and details):

```html
<div class="project-item">
    <img src="aircraft1.jpg" alt="1946 Cessna 120 Restoration">
    <h3>1946 Cessna 120</h3>
    <p>Complete restoration including new fabric, engine overhaul, and authentic period-correct paint scheme.</p>
</div>
```

5. To add MORE projects, copy the entire `<div class="project-item">...</div>` section and paste it below
6. Click "Commit changes" at the bottom

---

## 🎨 Changing Colors

If you want to adjust the vintage look:

1. Click on `styles.css`
2. Click the pencil icon
3. Look for these lines near the top:

```css
background-color: #f4e8d0;  /* Page background - cream color */
color: #3a2f2a;              /* Text color - dark brown */
```

4. Change the color codes (Google "color picker" to find codes you like)
5. Commit changes

---

## ✉️ Updating Contact Information

1. Click on `contact.html`
2. Click the pencil icon
3. Find these lines and replace with your real info:

```html
<p><strong>Email:</strong> info@warnerclassicaero.com</p>
<p><strong>Phone:</strong> (555) 123-4567</p>
<p><strong>Location:</strong> Your Location Here</p>
```

4. Commit changes

---

## 🏠 Editing Homepage Content

1. Click on `index.html`
2. Click the pencil icon
3. Find the welcome section and update the text:

```html
<section class="welcome">
    <h2>Welcome to Warner Classic Aero</h2>
    <p>We specialize in... [YOUR TEXT HERE]</p>
</section>
```

4. Commit changes

---

## 📋 Adding a New Page

If you want to add a completely new page (like "Services" or "Gallery"):

1. Click "Add file" → "Create new file"
2. Name it something like `services.html`
3. Copy the content from `about.html` as a template
4. Edit the content to match your new page
5. Add a link to it in the navigation of all other pages

---

## ❓ Need Help?

- **Your website URL:** https://whimsical-biscotti-c9fcd6.netlify.app (will change to warnerclassicaero.com soon!)
- **Your GitHub repository:** https://github.com/Marsdirt/warnerclassic-website
- **Netlify dashboard:** https://app.netlify.com

---

## 🚀 Remember:
- Changes take about 1 minute to appear on your live site
- You can't break anything - GitHub keeps all previous versions
- If you make a mistake, you can always undo it by looking at the file history

Happy updating! ✈️