# Douglas Chingosho - Portfolio Website

Professional portfolio website showcasing data analytics and financial technology projects.

## 🌐 Live Website
Visit: `https://yourusername.github.io`

## 📁 Files Included

### Core Pages:
- `index.html` - Homepage with hero section, stats, and featured projects
- `about.html` - Detailed biography, journey, values, and expertise
- `projects.html` - Complete project portfolio with detailed descriptions
- `resume.html` - Interactive resume/CV
- `contact.html` - Contact information and availability

### Styling:
- `style.css` - Complete stylesheet for all pages

## 🚀 How to Set Up Your GitHub Website

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com)
2. Click "+" → "New repository"
3. **Repository name:** `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
4. Set to **Public**
5. ✅ Check "Add a README file"
6. Click "Create repository"

### Step 2: Upload Files
1. In your repository, click "Add file" → "Upload files"
2. Drag and drop ALL the files:
   - index.html
   - about.html
   - projects.html
   - resume.html
   - contact.html
   - style.css
3. Commit message: "Initial website setup"
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to **Settings** (in your repository)
2. Click **Pages** (left sidebar)
3. Under "Source", select **"Deploy from a branch"**
4. Under "Branch", select **"main"** and **"/ (root)"**
5. Click **"Save"**

### Step 4: Visit Your Website! 🎉
Wait 1-2 minutes, then visit:
```
https://yourusername.github.io
```

## ✏️ Customization Guide

### Update Your Information:

#### 1. Personal Details
Search and replace throughout ALL files:
- `Douglas Tawanda Chingosho` → Your name
- `your.email@wustl.edu` → Your email
- `yourprofile` → Your LinkedIn username
- `yourusername` → Your GitHub username

#### 2. Projects Section
In `projects.html`, update:
- Project titles
- Project descriptions
- Technologies used
- GitHub links
- Live demo links

#### 3. About Page
In `about.html`, customize:
- Your personal story
- Timeline events
- Skills and expertise
- Certifications
- Interests

#### 4. Resume
In `resume.html`, update:
- Education details
- Work experience
- Projects
- Skills
- Add PDF resume link

### Add Your Resume PDF:
1. Create/upload `Douglas_Chingosho_Resume.pdf` to your repository
2. The download button in `resume.html` will automatically link to it

## 🎨 Color Customization

In `style.css`, find these color variables:

```css
/* Primary Blue: #3498db */
/* Dark Blue: #2c3e50 */
/* Light Gray: #ecf0f1 */
/* Green (success): #27ae60 */
```

To change colors, search for these hex codes and replace them.

## 📱 Features

✅ **Responsive Design** - Works on mobile, tablet, and desktop  
✅ **Clean Navigation** - Easy-to-use menu  
✅ **Project Showcase** - Detailed project descriptions with code samples  
✅ **Interactive Elements** - Hover effects and smooth transitions  
✅ **Professional Styling** - Modern, clean design  
✅ **SEO Friendly** - Proper meta tags and semantic HTML  

## 🔧 Advanced Customizations

### Add Google Analytics:
Add this before `</head>` in each HTML file:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

### Add Custom Domain:
1. Buy domain from Namecheap or Google Domains
2. Create file `CNAME` with your domain: `www.yourdomain.com`
3. Update DNS records in domain registrar

## 📞 Support

Questions? Issues?
- Email: your.email@wustl.edu
- Open an issue on GitHub

## 📄 License

This website template is open source. Feel free to use and modify!

---

**Built with:** HTML5, CSS3, and lots of ☕

**Last Updated:** February 2026
