# LeadForge Website

## File Structure
```
leadforge/
├── index.html              ← Main homepage
├── vercel.json             ← Vercel deployment config
├── css/
│   └── style.css           ← Shared styles (all pages)
├── js/
│   └── main.js             ← Shared JS (calculator, booking, tabs)
└── pages/
    ├── tradies.html         ← Tradies vertical (plumbers, electricians, painters)
    ├── healthcare.html      ← Healthcare vertical (dentists, physios, cosmetic)
    └── professional.html    ← Professional services (lawyers, accountants)
```

## Deploy to Vercel (Free — takes 5 minutes)

### Option A: Drag & Drop (Easiest — no account needed)
1. Go to https://vercel.com
2. Sign up free with Google or GitHub
3. Click "Add New" → "Project"
4. Drag the entire `leadforge` folder into the upload area
5. Click Deploy — you'll get a URL like `leadforge-abc123.vercel.app`

### Option B: GitHub + Vercel (Best for ongoing edits)
1. Go to https://github.com and create a free account
2. Create a new repository called `leadforge`
3. Upload all files (drag & drop works in GitHub too)
4. Go to https://vercel.com → "Add New" → "Import Git Repository"
5. Connect GitHub, select `leadforge` repo, click Deploy
6. Every time you update a file on GitHub, it auto-redeploys

### Option C: Vercel CLI
```bash
npm install -g vercel
cd leadforge
vercel
```
Follow the prompts — deployed in 60 seconds.

## Custom Domain (Optional)
Once on Vercel: Settings → Domains → Add your domain
Cost: Vercel is free. Domain costs ~$15/yr on Namecheap or GoDaddy.

## Pages
- `/` → Homepage with all verticals
- `/pages/tradies.html` → Tradies (plumbers, electricians, painters)
- `/pages/healthcare.html` → Healthcare clinics
- `/pages/professional.html` → Lawyers & accountants

## To Edit
All content is plain HTML — open any `.html` file in a text editor.
Prices, copy, testimonials are all easy to find and update.
The calculator data is in `js/main.js` under `TRADE_DATA`.
