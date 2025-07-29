# 🚀 Deploy to Vercel - Step by Step Guide

## Prerequisites
- Node.js installed on your computer
- Vercel CLI installed (`npm install -g vercel`)

## Step 1: Login to Vercel
```bash
vercel login
```
Choose your preferred login method:
- **GitHub** (Recommended)
- **Google**
- **GitLab**
- **Bitbucket**
- **Email**

## Step 2: Deploy Your Website
```bash
vercel --yes
```

## Step 3: Follow the Prompts
When prompted, answer the following:

1. **Set up and deploy?** → `Y`
2. **Which scope?** → Select your account
3. **Link to existing project?** → `N`
4. **What's your project's name?** → `bharmal-sanitary-center`
5. **In which directory is your code located?** → `./` (current directory)
6. **Want to override the settings?** → `N`

## Step 4: Get Your Live URL
After deployment, Vercel will provide you with:
- **Production URL**: `https://your-project-name.vercel.app`
- **Preview URL**: For testing changes

## Step 5: Share Your Website
Share the production URL with anyone you want to show your project to!

## 🔄 Updating Your Website
To update your website after making changes:
```bash
vercel --prod
```

## 📁 Project Structure for Vercel
```
├── index.html                    # Main entry point
├── bharmal-sanitary-center.html  # Your website
├── uploads/                      # Product images
├── vercel.json                   # Vercel configuration
├── README.md                     # Project documentation
└── DEPLOYMENT.md                 # This file
```

## 🌟 Benefits of Vercel Deployment
- **Free hosting** for personal projects
- **Automatic HTTPS** security
- **Global CDN** for fast loading
- **Custom domains** support
- **Automatic deployments** from Git
- **Analytics** and performance insights

## 🔗 Alternative Deployment Options

### Option 1: Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Drag your project folder to the deploy area
3. Get instant live URL

### Option 2: GitHub Pages
1. Create GitHub repository
2. Upload your files
3. Enable GitHub Pages in settings
4. Get `https://username.github.io/repository-name`

### Option 3: Surge.sh
```bash
npm install -g surge
surge
```

## 📞 Support
If you encounter any issues:
- Check Vercel documentation: https://vercel.com/docs
- Visit Vercel community: https://github.com/vercel/vercel/discussions

---

**Your Bharmal Sanitary Center website will be live and shareable! 🎉** 