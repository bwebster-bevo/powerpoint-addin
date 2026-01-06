# Files to Upload to GitHub

Upload these 6 files to your GitHub repository:

## Required Files:
1. **consulting-tools.html** - The main add-in interface
2. **manifest-github.xml** - Configuration file (⚠️ MUST EDIT - see below)
3. **icon-16.png** - Small icon
4. **icon-32.png** - Medium icon
5. **icon-64.png** - Large icon
6. **icon-80.png** - Extra large icon

## ⚠️ IMPORTANT: Before Uploading

You MUST edit **manifest-github.xml** and replace `YOUR-USERNAME` with your actual GitHub username.

### How to Edit:

1. Open `manifest-github.xml` in Notepad
2. Press Ctrl+H (Find and Replace)
3. Find: `YOUR-USERNAME`
4. Replace with: (your actual GitHub username)
5. Click "Replace All"
6. Save the file

For example, if your GitHub username is `john-smith`, change:
- FROM: `https://YOUR-USERNAME.github.io/powerpoint-addin/`
- TO: `https://john-smith.github.io/powerpoint-addin/`

## Upload Steps:

1. Go to your GitHub repository: `github.com/YOUR-USERNAME/powerpoint-addin`
2. Click "Add file" > "Upload files"
3. Drag and drop ALL 6 files into the upload area
4. Scroll down and click "Commit changes"
5. Wait 2-3 minutes for GitHub Pages to build
6. Your add-in will be available at: `https://YOUR-USERNAME.github.io/powerpoint-addin/consulting-tools.html`

## Test Your Deployment:

After uploading, open this URL in your browser:
```
https://YOUR-USERNAME.github.io/powerpoint-addin/consulting-tools.html
```
(Replace YOUR-USERNAME with your actual username)

If you see the Consulting PowerTools interface, it's working! ✅

## Load in PowerPoint Online:

1. Go to https://office.com
2. Open PowerPoint Online
3. Click **Insert** > **Add-ins** > **Upload My Add-in**
4. Upload the **manifest-github.xml** file (the edited one!)
5. The add-in should load immediately!

---

**Troubleshooting:**

If the add-in doesn't load:
- Make sure you replaced `YOUR-USERNAME` in the manifest
- Verify the files are public (not in a private repository)
- Check that GitHub Pages is enabled (Settings > Pages)
- Wait a few more minutes - GitHub Pages can take 5-10 minutes to deploy
