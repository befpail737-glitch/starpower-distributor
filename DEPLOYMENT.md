# Deployment instructions for Cloudflare Pages

## Prerequisites
1. A Cloudflare account (free tier available)
2. The website files in this directory

## Steps to deploy

1. Go to https://dash.cloudflare.com/ and sign in to your account
2. If you don't have a Cloudflare account, create one for free
3. In the dashboard, select "Workers & Pages" from the left sidebar
4. Click "Create application"
5. Select "Pages" and then "Connect to Git"
6. Connect your Git provider (GitHub, GitLab, or Bitbucket)
7. Select the repository containing these website files
8. Configure the build settings:
   - Framework preset: None (or select a static site generator if you're using one)
   - Build command: Leave empty (static site)
   - Build output directory: Leave as default or specify if needed
9. Click "Save and Deploy"
10. Wait for the deployment to complete (usually takes 1-2 minutes)
11. Once deployed, you'll receive a unique *.pages.dev URL
12. To use a custom domain:
    - Go to the project settings
    - Select "Custom domains"
    - Add your domain and follow the instructions to update your DNS records

## Alternative deployment method (drag and drop)

1. Go to https://dash.cloudflare.com/
2. Select "Workers & Pages" from the left sidebar
3. Click "Create application"
4. Select "Pages" and then "Upload assets"
5. Drag and drop all files from this directory to the upload area
6. Click "Deploy"
7. Wait for deployment to complete
8. Your site will be available at a *.pages.dev URL

## Notes
- This website is a static site with no backend requirements
- All files are ready for deployment with no additional build steps
- The site is fully responsive and optimized for modern browsers
- SEO elements like meta tags, structured data, and sitemap are included