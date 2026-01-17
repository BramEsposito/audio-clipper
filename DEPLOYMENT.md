# Deploying to GitHub Pages

This guide will walk you through deploying the Audio Clipper application to GitHub Pages.

## Steps to Deploy

### 1. Access Repository Settings

1. Navigate to your repository: https://github.com/BramEsposito/audio-clipper
2. Click the **Settings** tab (you need admin/write access to the repository)

### 2. Configure GitHub Pages

1. In the left sidebar, scroll down and click **Pages** under the "Code and automation" section
2. Under **Build and deployment**:
   - **Source**: Select "Deploy from a branch"
   - **Branch**: Select `claude/audio-trim-wavesurfer-Q6mCg` from the dropdown
   - **Folder**: Select `/ (root)`
3. Click **Save**

### 3. Wait for Deployment

1. GitHub will start building your site automatically
2. This usually takes 1-3 minutes
3. You'll see a notification at the top of the Pages settings once it's ready
4. The page will show: "Your site is live at https://bramesposito.github.io/audio-clipper/"

### 4. Access Your Live Site

Once deployed, your Audio Clipper will be available at:
**https://bramesposito.github.io/audio-clipper/**

## Troubleshooting

### Branch Not Showing in Dropdown

If you don't see the `claude/audio-trim-wavesurfer-Q6mCg` branch:
- Make sure the branch has been pushed to GitHub
- Try refreshing the settings page
- Check that you have the correct permissions

### Site Not Loading

If the site doesn't load after deployment:
- Wait a few more minutes (initial deployment can take up to 10 minutes)
- Check the Actions tab to see if the deployment workflow completed
- Make sure the branch contains the `index.html` file

### 404 Error

If you see a 404 error:
- Verify the repository name is correct in the URL
- Check that GitHub Pages is enabled in settings
- Ensure the source branch and folder are set correctly

## Updating the Site

To update your deployed site:
1. Make changes to your files locally
2. Commit the changes: `git add . && git commit -m "Your message"`
3. Push to the branch: `git push origin claude/audio-trim-wavesurfer-Q6mCg`
4. GitHub Pages will automatically rebuild and deploy (takes 1-3 minutes)

## Custom Domain (Optional)

To use a custom domain:
1. In the Pages settings, enter your custom domain
2. Configure your DNS provider to point to GitHub Pages
3. Follow GitHub's documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Need Help?

Visit the GitHub Pages documentation: https://docs.github.com/en/pages
