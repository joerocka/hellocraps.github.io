# Hello Craps Landing Page

🎲 Casino craps game - available free on Google Play

## Deploy to Cloudflare Pages (Free)

1. Go to https://pages.cloudflare.com
2. Sign in with your Cloudflare account
3. Click "Create a project" → "Upload assets"
4. Drag and drop the `index.html` folder
5. Your site will be live at `*.pages.dev`

Or with CLI:
```bash
npx wrangler pages deploy .
```

## Deploy to GitHub Pages

1. Create a new repo on GitHub
2. Push this code:
```bash
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/hellocraps.git
git push -u origin master
```

3. Go to Repo Settings → Pages
4. Set Source to "master branch"
5. Your site will be live at `YOUR_USERNAME.github.io/hellocraps`

## Custom Domain

Both Cloudflare and GitHub support custom domains (hellocraps.com) for free.