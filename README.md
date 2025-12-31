# Raw for the Future Website

Simple static website for rawforthefuture.com hosted on GitHub Pages.

## Setup Instructions

### 1. Add Your Logo
- Place your white logo image in the root directory
- Name it `logo.png` (or update the reference in `index.html` if using a different name)

### 2. Update Shop URLs
Edit `index.html` and replace the placeholder URLs:
- Replace `YOUR_GRAB_SHOP_URL` with your actual Grab shop URL
- Replace `YOUR_LINEMAN_SHOP_URL` with your actual Lineman shop URL

### 3. Deploy to GitHub Pages

#### Option A: Using GitHub Web Interface
1. Go to GitHub and create a new repository named `rawforthefuture`
2. Upload all files (index.html, styles.css, logo.png)
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click Save
7. Your site will be live at `https://yourusername.github.io/rawforthefuture/`

#### Option B: Using Git Command Line
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/rawforthefuture.git
git push -u origin main
```

Then follow steps 3-7 from Option A.

### 4. Custom Domain (Optional)
To use rawforthefuture.com:
1. In GitHub Settings → Pages, add your custom domain
2. Update your domain's DNS settings to point to GitHub Pages:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Or add A records pointing to GitHub's IP addresses

## File Structure
```
rawforthefuture/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
├── logo.png        # Your logo (you need to add this)
└── README.md       # This file
```

## Features
- Black background
- Centered white logo
- Two styled buttons with rounded corners
- Responsive design for mobile devices
- Links open in new tabs
