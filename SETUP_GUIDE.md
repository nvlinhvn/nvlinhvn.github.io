# 🚀 How to Launch Your Blog on GitHub Pages

## Step 1 — Fill in your contact details
Open `index.html` and find the 3 lines marked `✏️`:
- Replace `your.email@example.com` with your real email
- Replace `linkedin.com/in/your-profile` with your LinkedIn URL
- Replace `github.com/your-username` with your GitHub username

---

## Step 2 — Create a GitHub repository

1. Go to **github.com** → click **New repository**
2. Name it exactly: `YOUR-USERNAME.github.io`  
   _(e.g. if your GitHub username is `linhvnguyen`, name it `linhvnguyen.github.io`)_
3. Set it to **Public**
4. Click **Create repository**

---

## Step 3 — Upload your file

### Option A — Drag & drop (easiest)
1. Open your new repo on GitHub
2. Click **Add file → Upload files**
3. Drag `index.html` into the upload area
4. Click **Commit changes**

### Option B — Via Git (if you have Git installed)
```bash
git init
git add index.html
git commit -m "Launch personal blog site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```

---

## Step 4 — Enable GitHub Pages

1. In your repo, go to **Settings → Pages**
2. Under **Source**, select `Deploy from a branch`
3. Choose `main` branch and `/ (root)`
4. Click **Save**

✅ Your site will be live at `https://YOUR-USERNAME.github.io` within ~2 minutes!

---

## Step 5 (Optional) — Connect a custom domain

1. Buy a domain from Namecheap, Google Domains, Cloudflare, etc.
2. In your domain registrar's DNS settings, add a **CNAME record**:
   - Name: `www`
   - Value: `YOUR-USERNAME.github.io`
3. In GitHub Pages settings, enter your domain under **Custom domain**
4. Check **Enforce HTTPS**

---

## Updating your site later

Just edit `index.html` and re-upload (or `git push`). Changes go live in ~1 minute.

---

*Site built with vanilla HTML/CSS — no frameworks, no build steps. Fast, free, forever.*
