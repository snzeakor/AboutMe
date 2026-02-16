

### SYLVIA NZEAKOR
Open `index.html` and search for these sections to customize:

**Line 183-185** - Update your name and contact info:
```html
<div class="eyebrow">SYLVIA NZEAKOR</div>
<h1>MUSIC BUSINESS DEVELOPMENT EXECUTIVE</h1>
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
