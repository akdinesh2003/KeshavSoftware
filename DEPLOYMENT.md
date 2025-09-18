# KeshavSoftware - Deployment Guide

## 🚀 GitHub Pages Deployment Instructions

Follow these steps to deploy your KeshavSoftware website to GitHub Pages:

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com) and sign in to your account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository (e.g., `keshavsoftware-website`)
4. Make sure the repository is **Public** (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license (we already have these)
6. Click "Create repository"

### Step 2: Connect Local Repository to GitHub
```bash
# Add the remote origin (replace with your GitHub username and repository name)
git remote add origin https://github.com/YOUR_USERNAME/keshavsoftware-website.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on the "Settings" tab
3. Scroll down to the "Pages" section in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Live Website
After 5-10 minutes, your website will be available at:
```
https://YOUR_USERNAME.github.io/keshavsoftware-website/
```

## 🔗 Important Links to Update

Once deployed, update the following in your README.md:
- **GitHub Repository**: `https://github.com/YOUR_USERNAME/keshavsoftware-website`
- **Live Website**: `https://YOUR_USERNAME.github.io/keshavsoftware-website/`

## 📱 Alternative Deployment - Netlify

### Quick Netlify Deployment
1. Go to [Netlify.com](https://netlify.com) and sign up/login
2. Click "New site from Git"
3. Connect to GitHub and select your repository
4. Leave build settings empty (static site)
5. Click "Deploy site"
6. Your site will be available at a random Netlify URL (you can customize this)

## 🔧 Troubleshooting

### Common Issues:
1. **404 Error**: Make sure your repository is public and files are in the root directory
2. **CSS not loading**: Check that file paths are relative (no leading slashes)
3. **Changes not showing**: Wait 5-10 minutes for GitHub Pages to rebuild

### File Structure Verification:
Your repository should have this structure:
```
keshavsoftware-website/
├── index.html
├── about.html
├── contact.html
├── styles.css
├── README.md
├── DEPLOYMENT.md
└── .gitignore
```

## ✅ Final Checklist

- [ ] Repository created on GitHub
- [ ] Code pushed to main branch  
- [ ] GitHub Pages enabled
- [ ] Website accessible via GitHub Pages URL
- [ ] All pages load correctly
- [ ] Navigation works between pages
- [ ] Responsive design tested
- [ ] Contact form validation works
- [ ] README.md updated with live links

## 🎉 Submission

For your internship submission, provide:
1. **GitHub Repository URL**: `https://github.com/YOUR_USERNAME/repository-name`
2. **Live Website URL**: `https://YOUR_USERNAME.github.io/repository-name/`
3. **Project Reflection**: Already included in README.md

---

**Note**: Replace `YOUR_USERNAME` and `repository-name` with your actual GitHub username and repository name.