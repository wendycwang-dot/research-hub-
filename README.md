# Research Hub PWA

Your Research Hub is now a Progressive Web App! Here's how to deploy it.

## Quick Start (GitHub Pages - Free)

1. **Create a GitHub repository**
   - Go to github.com and create a new repository (e.g., "research-hub")
   - Make it public (required for free GitHub Pages)

2. **Upload these files**
   Upload all files from this folder:
   - `index.html` (the main app)
   - `manifest.json` (PWA configuration)
   - `sw.js` (service worker for offline support)
   - `icon-192.png` (app icon)
   - `icon-512.png` (app icon)

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main, folder: / (root)
   - Click Save

4. **Access your app**
   - Your app will be live at: `https://YOUR-USERNAME.github.io/research-hub/`
   - It may take a few minutes to deploy

## Installing on Your Phone

### iPhone/iPad (Safari)
1. Open your GitHub Pages URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"

### Android (Chrome)
1. Open your GitHub Pages URL in Chrome
2. You should see an "Install" banner at the bottom
3. Tap "Install" (or tap ⋮ menu → "Install app")

## Features

- ✅ Works offline (after first load)
- ✅ Installs to home screen like a native app
- ✅ Full-screen mode (no browser UI)
- ✅ Auto-updates when you push changes
- ✅ Mobile-optimized with collapsible sidebar

## Alternative Hosting Options

### Netlify (Free, easier)
1. Go to netlify.com and sign up
2. Drag and drop this entire folder
3. Get instant URL

### Vercel (Free)
1. Go to vercel.com
2. Import from GitHub or drag and drop
3. Automatic deployments on push

### Your own server
Just upload all files to any web server with HTTPS enabled.

## Updating the App

1. Make changes to `index.html`
2. Push to GitHub (or re-upload to your host)
3. Users will see an "Update available" notification

## Troubleshooting

**App not installing?**
- Make sure you're using HTTPS (required for PWAs)
- Try clearing browser cache
- Check browser console for errors

**Offline not working?**
- The service worker needs HTTPS
- First visit must be online to cache files

**Icons not showing?**
- Replace the placeholder PNGs with real 192x192 and 512x512 icons
- Use a tool like realfavicongenerator.net

## File Structure

```
research-hub/
├── index.html      # Main application
├── manifest.json   # PWA manifest
├── sw.js          # Service worker
├── icon-192.png   # Small icon
├── icon-512.png   # Large icon
└── README.md      # This file
```

Enjoy your Research Hub app! 📊
