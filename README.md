# Music Business Development Portfolio

A dynamic, visually striking portfolio website showcasing 12+ years of experience in music licensing, business development, and creative project management.

## 🎵 Live Demo

Once deployed, your portfolio will be live at: `https://yourusername.github.io/portfolio`

## ✨ Features

- **Bold Visual Design** - Music industry aesthetic with distinctive typography and animations
- **Compelling Storytelling** - Origin story highlighting early work with Burna Boy, Tems, and Omah Lay
- **Measurable Impact** - Timeline showcasing 50% partnership growth, 40% sync fee increases, and more
- **Project Showcase** - Notable placements including Coming 2 America, Grand Theft Auto, I May Destroy You
- **Fully Responsive** - Works beautifully on desktop, tablet, and mobile
- **Fast & Lightweight** - Pure HTML/CSS/JS with no dependencies

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create a GitHub Account
If you don't have one, sign up at [github.com](https://github.com)

### Step 2: Create a New Repository
1. Click the **+** icon in the top right and select **New repository**
2. Name it `portfolio` (or any name you prefer)
3. Make it **Public**
4. Do NOT initialize with README (we already have one)
5. Click **Create repository**

### Step 3: Upload Your Files
**Option A: Using GitHub Web Interface (Easiest)**
1. On your new repository page, click **uploading an existing file**
2. Drag and drop both `index.html` and `README.md` into the upload area
3. Scroll down and click **Commit changes**

**Option B: Using Git Command Line**
```bash
# Navigate to your portfolio folder
cd path/to/portfolio-site

# Initialize git
git init

# Add files
git add .

# Commit
git commit -m "Initial portfolio launch"

# Add remote (replace YOUR_USERNAME and YOUR_REPO)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Click **Pages** in the left sidebar
4. Under **Source**, select **main** branch
5. Click **Save**
6. Wait 1-2 minutes, then visit `https://YOUR_USERNAME.github.io/YOUR_REPO`

## 🎨 Customization Guide

### Update Your Personal Information
Open `index.html` and search for these sections to customize:

**Line 183-185** - Update your name and contact info:
```html
<div class="eyebrow">MUSIC BUSINESS DEVELOPMENT EXECUTIVE</div>
<h1>Building Bridges Between<br>Artists & Opportunity</h1>
```

**Line 186** - Update your bio:
```html
<p class="hero-subtitle">From Lagos studios to Grammy stages—I've spent 12+ years...</p>
```

**Line 667-669** - Update contact information:
```html
<a href="mailto:your.email@example.com" class="btn btn-primary">Get In Touch</a>
<a href="https://linkedin.com/in/yourprofile" class="btn btn-secondary">View LinkedIn</a>
```

**Header Section (top)** - Update page title:
```html
<title>Your Name - Music Business Development Executive</title>
```

### Change Colors
Update the CSS color variables at the top of the file (around line 12):
```css
:root {
    --primary: #E63946;    /* Main accent color */
    --secondary: #F4A261;  /* Secondary accent */
    --dark: #1D3557;       /* Dark backgrounds */
    --light: #F1FAEE;      /* Light backgrounds */
    --accent: #A8DADC;     /* Additional accent */
}
```

### Add Photos/Images
To add profile photos or project images:
1. Create an `images` folder in your repository
2. Upload images to that folder
3. Reference them in the HTML:
```html
<img src="images/profile.jpg" alt="Your Name">
```

### Modify Content Sections
- **Origin Story** (line 216-235): Update your personal story
- **Artists Section** (line 244-267): Add/remove artist cards
- **Skills Section** (line 280-351): Customize your expertise areas
- **Projects Section** (line 425-512): Update project details

## 📱 Custom Domain (Optional)

Want to use your own domain like `yourname.com`?

1. Buy a domain from Namecheap, GoDaddy, or Google Domains
2. In your repository, create a file named `CNAME`
3. Add your domain to that file: `yourname.com`
4. In your domain registrar settings, add these DNS records:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   
   Type: A
   Host: @
   Value: 185.199.109.153
   
   Type: A
   Host: @
   Value: 185.199.110.153
   
   Type: A
   Host: @
   Value: 185.199.111.153
   ```
5. Wait 24-48 hours for DNS to propagate

## 🔧 Local Development

To test changes locally before pushing to GitHub:

1. Open `index.html` directly in your browser
2. Make edits in a text editor (VS Code, Sublime, etc.)
3. Refresh the browser to see changes
4. Once happy, commit and push to GitHub

## 💡 Pro Tips

- **Update regularly** - Keep your achievements and projects current
- **Add analytics** - Insert Google Analytics to track visitors
- **SEO optimization** - Add meta descriptions and Open Graph tags
- **A/B test** - Try different headlines or layouts to see what resonates
- **Share widely** - Include the link in your email signature, LinkedIn, resume

## 🎯 Next Steps

After launching:
1. ✅ Update all placeholder text with your actual information
2. ✅ Add your professional headshot (optional but recommended)
3. ✅ Include resume download link
4. ✅ Add case studies or expanded project details
5. ✅ Set up Google Analytics
6. ✅ Share on LinkedIn, Twitter, and professional networks

## 📄 License

This portfolio template is free to use and customize for your personal use.

## 🤝 Questions?

If you need help customizing or have questions, feel free to reach out!

---

**Built with** ❤️ **for music industry professionals who want to stand out**
