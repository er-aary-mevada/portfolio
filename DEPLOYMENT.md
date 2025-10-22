# GitHub Pages Deployment Guide

## Quick Setup for Automatic Deployment

### Step 1: Repository Setup
1. Create a new repository on GitHub (or use existing one)
2. Push your portfolio files to the `main` branch

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **GitHub Actions**

### Step 3: Deploy!
```bash
# Add all files
git add .

# Commit changes
git commit -m "Deploy portfolio with GitHub Actions"

# Push to main branch
git push origin main
```

### That's it! 🎉

- Your site will be automatically deployed
- Every future commit to `main` branch will trigger automatic deployment
- Your portfolio will be available at: `https://your-username.github.io/portfolio`

## Troubleshooting

### If deployment fails:
1. Check the **Actions** tab in your repository
2. Look for any error messages in the workflow logs
3. Ensure all files are committed and pushed

### If site doesn't load:
1. Wait 5-10 minutes for propagation
2. Check that GitHub Pages is enabled in Settings
3. Verify the source is set to "GitHub Actions"

### To check deployment status:
- Go to **Actions** tab in your repository
- Look for green checkmarks ✅ (successful) or red X ❌ (failed)

## Benefits of GitHub Actions Deployment

✅ **Automatic**: Deploy on every push to main  
✅ **Fast**: Usually deploys in 1-2 minutes  
✅ **Reliable**: GitHub's infrastructure  
✅ **Free**: No cost for public repositories  
✅ **Version Control**: Track all changes  

Happy coding! 🚀