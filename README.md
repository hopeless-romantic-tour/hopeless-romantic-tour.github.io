# Countdown Landing Page

A simple, elegant countdown timer landing page with a romantic color scheme.

## Colors
- Primary: `#282f4b`
- Secondary: `#f2f37c`, `#efdce2`

## Setup for GitHub Pages

### Domain Format
**IMPORTANT:** To get `username.github.io` as your URL (no path), you MUST name your repository exactly `username.github.io`
- ✅ Repository name: `hopeless-romantic-tour.github.io` → URL: `https://hopeless-romantic-tour.github.io`
- ❌ Repository name: `countdown` → URL: `https://hopeless-romantic-tour.github.io/countdown` (includes path!)

### Step-by-Step Instructions

#### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a new repository on GitHub**:
   - Go to [github.com](https://github.com) and sign in
   - Click the **+** icon (top right) → **New repository**
   - **Name it exactly: `hopeless-romantic-tour.github.io`** (to get the clean URL without a path)
     - ⚠️ If you use a different name, your URL will be `hopeless-romantic-tour.github.io/repository-name`
   - Make it **Public** (required for free GitHub Pages)
   - Don't initialize with README (we already have files)
   - Click **Create repository**

2. **Upload your files**:
   - On your new repository page, click **uploading an existing file**
   - Drag and drop all 4 files: `index.html`, `styles.css`, `script.js`, and `README.md`
   - Click **Commit changes** at the bottom

3. **Enable GitHub Pages**:
   - Click **Settings** (top menu of your repository)
   - In the left sidebar, click **Pages**
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** (or `master`) branch
   - Select `/ (root)` folder
   - Click **Save**
   - Wait a few minutes, then visit `https://hopeless-romantic-tour.github.io`

#### Option 2: Using Git Command Line

1. **Create repository on GitHub** (same as Option 1, step 1)

2. **In your project folder, run these commands**:
   ```bash
   git init
   git add index.html styles.css script.js README.md
   git commit -m "Initial commit: Countdown landing page"
   git branch -M main
   git remote add origin https://github.com/hopeless-romantic-tour/hopeless-romantic-tour.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages** (same as Option 1, step 3)

### Your Site URL
- ✅ Repository named `hopeless-romantic-tour.github.io`: `https://hopeless-romantic-tour.github.io`
- ❌ Any other repository name: `https://hopeless-romantic-tour.github.io/repository-name` (includes the path)

## Customization

- **Change the title**: Edit the `<h1 class="title">` in `index.html`
- **Change colors**: Edit the color values in `styles.css`
- **Change target date**: Edit `targetDate` in `script.js`

Enjoy your countdown page! ⏰
