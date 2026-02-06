# Portfolio Website - Deployment Guide

## 🚀 Step-by-Step Guide to Deploy on GitHub Pages

### Prerequisites
- A GitHub account (create one at https://github.com if you don't have one)
- Your portfolio files (index.html)

---

## Method 1: Using GitHub Web Interface (Easiest - No Technical Skills Required)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process
4. Verify your email address

### Step 2: Create a New Repository
1. Once logged in, click the **"+"** icon in the top-right corner
2. Select **"New repository"**
3. **IMPORTANT:** Name your repository exactly: `yourusername.github.io`
   - Replace `yourusername` with YOUR actual GitHub username
   - Example: If your username is `thokozanie`, name it `thokozanie.github.io`
4. Set it to **Public**
5. Check **"Add a README file"** (optional)
6. Click **"Create repository"**

### Step 3: Upload Your Portfolio File
1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop your `index.html` file OR click "choose your files"
3. **IMPORTANT:** Make sure the file is named exactly `index.html` (lowercase)
4. Scroll down and click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. In your repository, click **"Settings"** (top menu)
2. Scroll down and click **"Pages"** in the left sidebar
3. Under "Source", select **"main"** branch
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 5: View Your Live Website! 🎉
Your portfolio will be live at: `https://yourusername.github.io`
- Example: `https://thokozanie.github.io`

---

## Method 2: Using Git (For Those Comfortable with Command Line)

### Step 1: Install Git
**Windows:**
- Download from: https://git-scm.com/download/win
- Run the installer with default settings

**Mac:**
- Open Terminal
- Type: `git --version` (this will prompt installation if not installed)

**Linux:**
```bash
sudo apt-get update
sudo apt-get install git
```

### Step 2: Configure Git
Open Terminal/Command Prompt and run:
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### Step 3: Create Repository on GitHub
1. Go to https://github.com
2. Click **"+"** → **"New repository"**
3. Name it: `yourusername.github.io`
4. Make it **Public**
5. **DO NOT** check "Add a README file"
6. Click **"Create repository"**

### Step 4: Upload Your Files via Git
Open Terminal/Command Prompt in the folder containing your `index.html` file:

```bash
# Initialize git in your folder
git init

# Add your files
git add index.html

# Commit your files
git commit -m "Initial portfolio upload"

# Add the GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Note:** Replace `yourusername` with your actual GitHub username

### Step 5: Your Site is Live!
Visit: `https://yourusername.github.io`

---

## 🎨 Customizing Your Portfolio

After deployment, you can update your portfolio anytime:

### Using Web Interface:
1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (✏️) to edit
4. Make your changes
5. Scroll down and click "Commit changes"
6. Changes will be live in 1-2 minutes

### Using Git:
```bash
# Make changes to index.html
# Then:
git add index.html
git commit -m "Updated portfolio content"
git push
```

---

## 📱 Adding a Custom Domain (Optional)

If you want to use your own domain (like `www.thokozani.dev`):

1. Buy a domain from a registrar (Namecheap, GoDaddy, etc.)
2. In your GitHub repository, go to **Settings** → **Pages**
3. Under "Custom domain", enter your domain
4. In your domain registrar's DNS settings, add:
   - Type: `A` Record
   - Name: `@`
   - Value: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   
5. For www subdomain:
   - Type: `CNAME`
   - Name: `www`
   - Value: `yourusername.github.io`

---

## 🔧 Troubleshooting

### Problem: "404 - Page Not Found"
**Solution:**
- Make sure your file is named exactly `index.html` (lowercase)
- Check that your repository name is exactly `yourusername.github.io`
- Wait 2-5 minutes after first deployment

### Problem: "Changes Not Showing"
**Solution:**
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)
- Wait 1-2 minutes for GitHub to rebuild the site
- Make sure you committed your changes

### Problem: "Repository Not Found"
**Solution:**
- Make sure the repository is set to **Public**, not Private
- Check spelling of your repository name

---

## 📞 Need Help?

If you encounter any issues:
1. Check GitHub Pages documentation: https://pages.github.com
2. GitHub Community Forum: https://github.community
3. Your repository → Issues → New Issue (describe your problem)

---

## ✨ Your Portfolio Features

Your portfolio includes:
- ✅ Responsive design (works on mobile, tablet, desktop)
- ✅ Smooth scrolling navigation
- ✅ Animated sections
- ✅ Professional developer theme
- ✅ Contact information
- ✅ Skills showcase
- ✅ Work experience timeline
- ✅ Fast loading speed

---

## 🎯 Next Steps After Deployment

1. **Share your portfolio:**
   - Add the link to your LinkedIn profile
   - Include it in your CV
   - Share it in job applications
   - Add it to your email signature

2. **Keep it updated:**
   - Add new projects as you complete them
   - Update your skills as you learn new technologies
   - Keep your contact information current

3. **Optimize for SEO:**
   - Add meta descriptions
   - Create a sitemap
   - Submit to Google Search Console

---

## 📊 Viewing Your Portfolio Statistics

GitHub provides basic analytics:
1. Go to your repository
2. Click **"Insights"** → **"Traffic"**
3. See visitor statistics (updated after 48 hours)

---

**Congratulations! Your professional portfolio is now live on the internet! 🎉**

Your URL: `https://yourusername.github.io`

Remember to replace `yourusername` with your actual GitHub username!
