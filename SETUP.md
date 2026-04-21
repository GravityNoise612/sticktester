# Setup Instructions for GitHub Pages

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Enter repository name: `joystick-tester`
3. Set to **Public**
4. Click **Create repository**

## Step 2: Upload Files

### Option A: GitHub Web UI (Easiest)

1. Click **Add file → Upload files**
2. Drag these files into the upload area:
   - `index.html`
   - `README.md`
3. Click **Commit changes**

### Option B: Git Command Line

```bash
git clone https://github.com/YOUR-USERNAME/joystick-tester.git
cd joystick-tester
# Copy index.html and README.md here
git add .
git commit -m "Initial commit"
git push origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository **Settings**
2. Click **Pages** (in the left sidebar)
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

## Step 4: Access Your Site

After 1-2 minutes, your site will be live at:

```
https://YOUR-USERNAME.github.io/joystick-tester/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

---

## That's it!

Your joystick tester is now live on the web. Share the URL with anyone who needs to test their controllers!
