# Taste Rider Shopify Theme

This is a Shopify theme for Taste Rider.

## Directory Structure

- `assets/`: Theme assets such as CSS, JavaScript, and images
- `config/`: Theme configuration files
- `layout/`: Theme layout templates
- `locales/`: Translation files
- `sections/`: Theme sections
- `snippets/`: Reusable template snippets
- `templates/`: Page templates

## Connecting to Shopify via GitHub

1. Push this repository to GitHub:
   ```
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/taste-rider-shopify.git
   git push -u origin main
   ```

2. In your Shopify admin:
   - Go to Online Store > Themes
   - Click "Add theme" > "Connect from GitHub"
   - Connect your GitHub account if not already connected
   - Select this repository
   - Select the branch you want to use (usually main)

3. Shopify will now sync with your GitHub repository. Any changes pushed to GitHub will be automatically deployed to your theme.