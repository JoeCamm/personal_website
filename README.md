# Joe Camm's Personal Website

A cozy corner of the internet showcasing ML engineering work, projects, and personality.

## 🚀 Quick Start

1. **Customize the content** in `index.html`:
   - Update your name, bio, and description
   - Add your actual email and social links in the Contact section
   - Replace placeholder projects with your real work
   - Update the footer year

2. **Personalize colors** in `styles.css`:
   - Change the CSS variables in the `:root` section (lines 12-22)
   - Try different color schemes while keeping the warm, cozy vibe

3. **Test locally**:
   - Open `index.html` in your browser
   - Check all sections and links work
   - Test on mobile (browser dev tools)

## 📦 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository
```bash
# In your project folder
git init
git add .
git commit -m "Initial commit: Personal website v1"

# Create a new repo on GitHub called "yourname.github.io"
# Then push your code:
git remote add origin https://github.com/yourusername/yourname.github.io.git
git branch -M main
git push -u origin main
```

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main branch**
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io` in a few minutes!

## 🎨 Customization Ideas

### Color Schemes
The current palette is warm and earthy. Here are alternative palettes:

**Cool & Modern:**
```css
--color-primary: #2563eb;
--color-accent: #6366f1;
--color-bg: #f8fafc;
```

**Forest Green:**
```css
--color-primary: #059669;
--color-accent: #10b981;
--color-bg: #f0fdf4;
```

### Adding a Frisbee Section
Add this between Projects and Writing:

```html
<section id="frisbee" class="frisbee">
    <div class="container">
        <h2 class="section-title">Ultimate Frisbee</h2>
        <p class="section-intro">Because life isn't all code and models.</p>
        <!-- Add videos, photos, tournament results, etc. -->
    </div>
</section>
```

### Adding a Blog
For a simple blog, you can:
1. Create a `blog/` folder
2. Add individual HTML files for each post
3. Link to them from the Writing section
4. Or use a static site generator like Jekyll (built into GitHub Pages!)

## 🛠️ Future Enhancements

Week 2+:
- [ ] Add actual project images
- [ ] Write first blog post
- [ ] Add frisbee photos/videos
- [ ] Implement project filtering by tags
- [ ] Add dark mode toggle
- [ ] Create individual project pages
- [ ] Set up custom domain (joecamm.dev)

## 📝 Content Checklist

Before going live, update these:
- [ ] Replace "your.email@example.com" with real email
- [ ] Update all GitHub/LinkedIn/Kaggle links
- [ ] Add real project descriptions
- [ ] Write actual about section (currently generic)
- [ ] Add your own skills tags
- [ ] Update footer copyright year
- [ ] Add a favicon (create a small JC logo)

## 🎯 Structure

```
your-site/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md           # This file
```

## 🌟 Design Philosophy

- **Cozy**: Warm colors, comfortable spacing, personal touches
- **Functional**: Easy to navigate, fast to load, works everywhere
- **Authentic**: Actually you, not a sterile portfolio
- **Iterative**: Build and improve over time

## 📸 Screenshots

(Add screenshots once you've customized it!)

## 🤝 Credits

Built from scratch with vanilla HTML, CSS, and JavaScript. No frameworks, just fundamentals.

---

**Pro tip**: Keep the site simple for now. Add complexity only when you need it. The best websites are the ones that actually get finished and published! 🚀
