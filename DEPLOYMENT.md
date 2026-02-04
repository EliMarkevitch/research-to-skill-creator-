# Deployment Guide

This guide will walk you through deploying your Research to Skill Creator app to GitHub and Vercel.

## 📋 Prerequisites

- A GitHub account ([Sign up here](https://github.com/join))
- A Vercel account ([Sign up here](https://vercel.com/signup)) - you can sign in with GitHub

## 🚀 Step 1: Push to GitHub

### Option A: Using GitHub Desktop (Easiest)

1. **Download GitHub Desktop** (if you haven't already)
   - Visit [desktop.github.com](https://desktop.github.com)
   - Download and install

2. **Add your repository**
   - Open GitHub Desktop
   - Click "File" → "Add Local Repository"
   - Browse to: `Desktop/CLAUDE4ELI/Created with Claude/research-to-skill-creator`
   - Click "Add Repository"

3. **Create GitHub repository**
   - Click "Publish repository" in the top bar
   - Repository name: `research-to-skill-creator`
   - Description: "Transform research into Claude skills with brand identity"
   - Uncheck "Keep this code private" (if you want it public)
   - Click "Publish Repository"

### Option B: Using Command Line

1. **Create a new repository on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Repository name: `research-to-skill-creator`
   - Description: "Transform research into Claude skills with brand identity"
   - Choose Public or Private
   - **Do NOT** initialize with README (we already have one)
   - Click "Create repository"

2. **Push your local repository**
   ```bash
   cd ~/Desktop/CLAUDE4ELI/Created\ with\ Claude/research-to-skill-creator
   git remote add origin https://github.com/YOUR_USERNAME/research-to-skill-creator.git
   git push -u origin main
   ```

   Replace `YOUR_USERNAME` with your GitHub username.

## 🌐 Step 2: Deploy to Vercel

### Method 1: Quick Deploy (Recommended)

1. **Go to Vercel**
   - Visit [vercel.com](https://vercel.com)
   - Click "Sign Up" and choose "Continue with GitHub"
   - Authorize Vercel to access your GitHub repositories

2. **Import your project**
   - Click "Add New..." → "Project"
   - Find `research-to-skill-creator` in the list
   - Click "Import"

3. **Configure the project**
   - Project Name: `research-to-skill-creator` (or customize)
   - Framework Preset: Leave as "Other"
   - Root Directory: `./`
   - Build Settings: Leave default (no build needed)
   - Click "Deploy"

4. **Wait for deployment** ⏳
   - Vercel will deploy your app (takes ~30 seconds)
   - You'll get a live URL like: `research-to-skill-creator.vercel.app`

5. **Done! 🎉**
   - Click the generated URL to view your live app
   - Share it with anyone!

### Method 2: Using Vercel CLI

```bash
# Install Vercel CLI (one time)
npm i -g vercel

# Navigate to your project
cd ~/Desktop/CLAUDE4ELI/Created\ with\ Claude/research-to-skill-creator

# Deploy
vercel

# Follow the prompts:
# - Set up and deploy? Yes
# - Which scope? Your account
# - Link to existing project? No
# - Project name: research-to-skill-creator
# - Directory: ./
# - Override settings? No

# For production deployment
vercel --prod
```

## 🎨 Step 3: Customize Your Domain (Optional)

1. **Go to your Vercel project dashboard**
2. Click "Settings" → "Domains"
3. Add your custom domain or use the free `.vercel.app` domain
4. Follow Vercel's instructions to configure DNS

## 🔄 Future Updates

Once deployed, any time you push changes to GitHub:

```bash
cd ~/Desktop/CLAUDE4ELI/Created\ with\ Claude/research-to-skill-creator
git add .
git commit -m "Your update message"
git push
```

Vercel will **automatically deploy** your changes! 🚀

## 📊 Your Live App

After deployment, you'll have:

- **GitHub Repository**: `https://github.com/YOUR_USERNAME/research-to-skill-creator`
- **Live App**: `https://research-to-skill-creator.vercel.app` (or your custom domain)
- **Automatic Updates**: Push to GitHub → Auto-deploy to Vercel

## 🆘 Troubleshooting

### "Repository not found" error
- Make sure you've pushed your code to GitHub first
- Check that Vercel has permission to access your repositories

### Deployment failed
- Check the Vercel deployment logs
- Ensure `index.html` exists in the root directory
- Verify `vercel.json` is properly formatted

### Changes not showing up
- Wait 30-60 seconds after pushing
- Check the Vercel deployment status
- Try a hard refresh in your browser (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows)

## 🎯 What's Next?

- Share your live URL with others
- Customize the app for your brand
- Add more features as needed
- Create more skills with your app!

---

Need help? Check out:
- [Vercel Documentation](https://vercel.com/docs)
- [GitHub Guides](https://guides.github.com)
