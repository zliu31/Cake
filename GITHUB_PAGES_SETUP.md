# 🌐 Setting Up GitHub Pages for Make a Cake!

Follow these steps to make your "Make a Cake!" website publicly accessible via GitHub Pages.

## Quick Setup (Recommended)

### Step 1: Merge to Main Branch

1. Go to your GitHub repository: https://github.com/zliu31/Cake
2. You should see the branch `claude/test-repository-connection-011CUqiL4LrqpnHx5F51oJYF`
3. Click on "Pull requests" → "New pull request"
4. Set the base branch to `main` (or create it if it doesn't exist)
5. Set the compare branch to `claude/test-repository-connection-011CUqiL4LrqpnHx5F51oJYF`
6. Click "Create pull request"
7. Add a title like "Add Make a Cake! interactive website"
8. Click "Merge pull request" → "Confirm merge"

### Step 2: Enable GitHub Pages

1. In your repository, click on "Settings" (top right)
2. Scroll down to "Pages" in the left sidebar (under "Code and automation")
3. Under "Source", select:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
4. Click "Save"
5. Wait 1-2 minutes for deployment

### Step 3: Access Your Website

Your website will be available at:

**https://zliu31.github.io/Cake/**

The exact URL will be shown in the GitHub Pages settings once deployment is complete.

## Alternative: Direct Branch Deployment

If you want to deploy the feature branch directly:

1. Go to Settings → Pages
2. Under "Source", select:
   - **Branch**: `claude/test-repository-connection-011CUqiL4LrqpnHx5F51oJYF`
   - **Folder**: `/ (root)`
3. Click "Save"

Your site will be live at: https://zliu31.github.io/Cake/

## Troubleshooting

### Repository Not Public?

If the repository is private, you need to make it public first:
1. Go to Settings → General
2. Scroll to "Danger Zone"
3. Click "Change visibility" → "Make public"
4. Confirm the action

### 404 Error?

- Wait a few minutes - GitHub Pages can take 1-10 minutes to deploy
- Check that `index.html` is in the root directory
- Verify the branch and folder settings in GitHub Pages

### Custom Domain (Optional)

To use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update GitHub Pages settings to use your custom domain

## Files in This Repository

- `index.html` - Main website file
- `README.md` - Project documentation
- `test-connection.txt` - Repository connection test file
- `GITHUB_PAGES_SETUP.md` - This file

## After Setup

Once live, share your cake builder with:
- Friends and family
- Social media
- Portfolio or resume

Enjoy! 🎂✨
