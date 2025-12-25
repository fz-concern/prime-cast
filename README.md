# Prime Cast Landing Page

A beautiful, modern landing page for the Prime Cast app - Stream every TV channel from around the world!

## Features

✨ **Modern Design**
- Purple to blue gradient theme
- Responsive mobile-first design
- Smooth animations and transitions
- Beautiful UI components

🎯 **Key Sections**
- Hero section with app description
- Features showcase with 6 key features
- Download section with prominent CTA button
- Smooth navigation and scrolling

📱 **Fully Responsive**
- Works perfectly on desktop, tablet, and mobile devices
- Touch-friendly download button
- Optimized performance

## Setup & Deployment

### Option 1: GitHub Pages (Recommended)

1. **Enable GitHub Pages:**
   - Go to your repository settings
   - Scroll to "GitHub Pages" section
   - Select `main` branch as the source
   - Save

2. **Access your site:**
   - Your landing page will be available at:  `https://fz-concern.github.io/prime-cast-landing`

### Option 2: Custom Domain

1. Add a `CNAME` file to your repository root with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. Enable HTTPS in repository settings

## Uploading Your APK

1. **Upload the APK file:**
   - In your GitHub repository, click "Add file" → "Upload files"
   - Upload your `app.apk` file (or place it in an `assets` folder)
   - Commit the changes

2. **Update the download link in `script.js`:**
   ```javascript
   // If APK is in root: 
   const apkUrl = 'https://github.com/fz-concern/prime-cast-landing/raw/main/app. apk';
   
   // If APK is in assets folder: 
   const apkUrl = 'https://github.com/fz-concern/prime-cast-landing/raw/main/assets/app.apk';