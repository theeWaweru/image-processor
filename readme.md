# GitHub Pages Setup Guide

This guide will walk you through setting up your Image Processor as a web application hosted on GitHub Pages.

## 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account
2. Click on the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., "image-processor")
4. Add a description (optional)
5. Choose "Public" visibility
6. Check "Add a README file"
7. Click "Create repository"

## 2. Upload the Files

### Option A: Using GitHub Web Interface

1. In your new repository, click the "Add file" button and select "Upload files"
2. Drag and drop or select the HTML file from your computer
3. Add a commit message (e.g., "Add image processor app")
4. Click "Commit changes"

### Option B: Using Git Command Line

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/image-processor.git
   ```
2. Copy your HTML file to the cloned repository folder
3. Add, commit, and push the changes:
   ```
   git add .
   git commit -m "Add image processor app"
   git push origin main
   ```

## 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (tab at the top)
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait a few minutes for GitHub to build your site

## 4. Access Your Web App

1. After GitHub Pages is enabled, you'll see a message with your site's URL
2. The URL will be in this format: `https://your-username.github.io/image-processor/`
3. Click on the link to open your web app

## 5. Update Your App (If Needed)

To make changes to your app:

1. Edit the HTML file
2. Upload the updated file to your repository
3. GitHub Pages will automatically update your site (may take a few minutes)

## 6. Custom Domain (Optional)

If you want to use a custom domain:

1. Purchase a domain from a domain registrar (e.g., Namecheap, GoDaddy)
2. In your repository settings, under "GitHub Pages", enter your custom domain
3. Configure your domain's DNS settings as per GitHub's instructions
4. Wait for DNS changes to propagate (can take up to 48 hours)

## 7. Limitations and Tips

- GitHub Pages has a soft limit of 1GB for repository size
- The site is public, so don't include sensitive information
- Consider adding a license file to your repository
- You can use Git version control to track changes
- For more complex apps, consider organizing your code into separate files

## 8. Troubleshooting

If your site doesn't appear:
- Make sure your HTML file is named `index.html`
- Check that GitHub Pages is properly enabled
- Verify that your repository is public
- Wait a few minutes for changes to propagate

## 9. Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Custom Domain Setup](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [GitHub Pages Limits](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#usage-limits)