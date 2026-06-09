# Railway Preservation Society of Queensland Website

A static website for the Railway Preservation Society of Queensland, designed to be hosted on Cloudflare Pages.

## Setup

Before deploying, you need to add your image files to the project directory:

1. **Logo Image**: Save your logo image as `logo.png` in this directory
2. **Steam Train Image**: Save your steam train background image as `steam-train.jpg` in this directory

The website expects these exact filenames:
- `logo.png` - The circular Railway Preservation Society of Queensland logo
- `steam-train.jpg` - The steam train photograph for the header background

## Local Testing

To test the website locally:
1. Open `index.html` in your web browser, or
2. Use a local server like Live Server in VS Code

## Deploying to Cloudflare Pages

### Option 1: Direct Upload

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Click "Create a project"
3. Select "Upload assets"
4. Upload all files from this directory (index.html, style.css, logo.png, steam-train.jpg)
5. Click "Deploy site"

### Option 2: Git Integration

1. Push this directory to a GitHub/GitLab repository
2. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
3. Click "Create a project"
4. Connect your Git account
5. Select your repository
6. Cloudflare will automatically deploy when you push changes

### Option 3: Wrangler CLI

1. Install Wrangler: `npm install -g wrangler`
2. Login: `wrangler login`
3. Deploy: `wrangler pages deploy . --project-name=railway-society`

## Customization

- Edit `index.html` to change content
- Edit `style.css` to modify colors, fonts, and layout
- The header uses the steam train image as a background
- The logo is displayed in a circular container with a red border matching the society's branding

## Features

- Responsive design that works on mobile and desktop
- Hero header with steam train background image
- Prominent logo display
- About section
- Mission cards with hover effects
- Contact call-to-action
- Memorial footer text
