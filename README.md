[README.md](https://github.com/user-attachments/files/28113159/README.md)
# Jenny Riemer — Portfolio Website

Personal portfolio site for Jenny Riemer, digital marketer and AI automation strategist based in Colorado.

## Deploy to GitHub + Vercel

### Step 1 — Create a GitHub repo

1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it something like `jenny-riemer-portfolio`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the file

**Option A — drag and drop (easiest):**
1. On your new repo page, click **uploading an existing file**
2. Drag `index.html` into the window
3. Click **Commit changes**

**Option B — via Git CLI:**
```bash
git init
git add index.html
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/jenny-riemer-portfolio.git
git push -u origin main
```

### Step 3 — Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New Project**
3. Import your `jenny-riemer-portfolio` repo
4. Leave all settings as default — Vercel detects it as a static site automatically
5. Click **Deploy**

Your site will be live at `jenny-riemer-portfolio.vercel.app` in about 30 seconds.

### Step 4 — Custom domain (optional)

1. In Vercel, go to your project settings
2. Click **Domains**
3. Add your custom domain and follow the DNS instructions

## Making updates

Edit `index.html` locally, then push to GitHub. Vercel auto-deploys on every push.

## Tech stack

- Pure HTML + CSS — no frameworks, no build step needed
- Google Fonts: Bebas Neue + DM Sans
- Fully responsive — mobile hamburger menu, stacked layouts on small screens
