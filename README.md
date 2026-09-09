# CFB Scores

Dark-mode college football scoreboard (FBS) for laptop / iPad.

Live data from ESPN. Auto-refreshes every 15 seconds.

## Deploy to GitHub Pages

### 1. Create a new repo on GitHub
1. Go to [github.com/new](https://github.com/new)
2. Name it something like `cfb-scores` (public is fine)
3. **Do not** check “Add a README” if you plan to upload these files as the first commit
4. Create the repository

### 2. Upload this site
**Option A — GitHub website (easiest)**  
1. Open your new repo  
2. Click **Add file → Upload files**  
3. Upload `index.html` (this folder’s main page)  
4. Commit

**Option B — Git command line**
```bash
git clone https://github.com/YOUR_USERNAME/cfb-scores.git
cd cfb-scores
cp /path/to/index.html .
git add index.html
git commit -m "Add CFB scores board"
git push origin main
```

### 3. Turn on GitHub Pages
1. Repo → **Settings → Pages**
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`)
   - Folder: **/ (root)**
3. Save

After a minute or two, your site will be at:

`https://YOUR_USERNAME.github.io/cfb-scores/`

### 4. iPad
1. Open that URL in Safari  
2. Share → **Add to Home Screen**  
3. Leave it on your table like a scoreboard app  

## Local use
Open `index.html` or `cfb-scores.html` in a desktop browser. For iPad, use the hosted GitHub Pages URL above.
