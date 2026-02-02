# Step-by-Step: Getting Your Bet the Bracket Tool Online

## What You're Doing
You're putting your interactive bracket tool on the internet so anyone on your team can access it with a link.

---

## STEP 1: Download the Files

1. Download the `bet-the-bracket-github.zip` file I just created
2. Unzip it (double-click on Mac, right-click → Extract on Windows)
3. You should see a folder with these files:
   - index.html
   - README.md
   - SETUP.md
   - .gitignore

---

## STEP 2: Create a GitHub Account (If You Don't Have One)

1. Go to https://github.com
2. Click "Sign up"
3. Follow the prompts (it's free!)

---

## STEP 3: Create a New Repository

You're already on the right screen! Here's what to fill in:

### Repository name:
```
bet-the-bracket-demo
```

### Description:
```
Interactive pricing model for Bet the Bracket - March Madness prediction markets
```

### Visibility:
- Choose **Private** (this is internal modeling - don't make it public)

### Initialize repository:
- Leave everything OFF (no README, no .gitignore, no license)

### Click "Create repository"

---

## STEP 4: Upload Your Files

After creating the repo, GitHub will show you a page with instructions. **Ignore the complicated stuff!**

Instead, look for a link that says **"uploading an existing file"** (it's in small text in the middle of the page)

Click that link, then:

1. Drag all 4 files from your unzipped folder into the upload box:
   - index.html
   - README.md  
   - SETUP.md
   - .gitignore

2. At the bottom, in the "Commit changes" box, type:
   ```
   Initial commit: Bet the Bracket pricing tool
   ```

3. Click **"Commit changes"** (green button)

---

## STEP 5: Turn on GitHub Pages (Make It Live!)

1. In your repo, click **"Settings"** (top tab, far right)

2. On the left sidebar, click **"Pages"**

3. Under "Source", select:
   - Branch: **main**
   - Folder: **/ (root)**

4. Click **"Save"**

5. Wait ~30 seconds, then refresh the page

6. You'll see a box at the top that says:
   ```
   Your site is live at https://YOUR-USERNAME.github.io/bet-the-bracket-demo/
   ```

---

## STEP 6: Share with Your Team!

Copy that URL and share it with:
- Dustin
- Sam Baker
- Cameron Dean
- SIG team
- Anyone who needs to see the pricing model

They just click the link - no installation, no downloads, works on any device!

---

## If You Get Stuck

**Can't find "uploading an existing file"?**
- Look in the "Quick setup" section on the page after creating repo
- It's a small link in the middle of instructions

**Files won't upload?**
- Make sure you're dragging all 4 files at once
- Make sure they're unzipped (not still in the .zip)

**Don't see the Settings tab?**
- Make sure you're logged into GitHub
- Make sure you're viewing YOUR repository

**Pages not showing up?**
- Wait 1-2 minutes after clicking Save
- Refresh the Pages settings page
- Sometimes takes a minute to build

---

## Alternative: Super Fast Method (Netlify)

If GitHub seems confusing, try this instead:

1. Go to: https://app.netlify.com/drop
2. Drag JUST the `index.html` file into the browser
3. Get instant link in 10 seconds
4. Share with team

This is even easier but the link is random (like `festive-unicorn-123.netlify.app`)

---

Need help? Just ask me and I'll walk you through any step!
