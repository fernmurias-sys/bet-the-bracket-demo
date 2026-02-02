# Quick Start: Deploy to GitHub

## Option 1: GitHub Pages (Recommended)

1. **Create a new GitHub repository:**
   ```bash
   # On GitHub.com, click "New Repository"
   # Name it: bet-the-bracket-demo
   # Make it private (contains internal modeling)
   # Don't initialize with README
   ```

2. **Push this code:**
   ```bash
   cd /path/to/this/folder
   git init
   git add .
   git commit -m "Initial commit: Bet the Bracket pricing model"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/bet-the-bracket-demo.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo Settings → Pages
   - Source: Deploy from branch "main"
   - Folder: / (root)
   - Save
   - Your site will be live at: `https://YOUR-USERNAME.github.io/bet-the-bracket-demo/`

## Option 2: Share HTML File Directly

Just share `index.html` (or `bracket-full-interactive.html`) directly with your team. They can open it in any browser - no server needed!

## Option 3: Netlify (Fastest)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag `index.html` into the browser
3. Get instant live URL (no account needed)
4. Share with team immediately

## Files Included

- `index.html` - Main application (same as bracket-full-interactive.html)
- `bracket-full-interactive.html` - Backup copy
- `README.md` - Project documentation
- `SETUP.md` - This file

## Sharing with Team

Once deployed, your team can:
- View the live site (no installation needed)
- Use on any device (desktop/mobile/tablet)
- Bookmark for presentations
- Share link with stakeholders

## Updating the Tool

After making changes:
```bash
git add .
git commit -m "Update: description of changes"
git push
```

GitHub Pages will auto-deploy in ~1 minute.
