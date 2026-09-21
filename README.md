# Aarya Sanjay Sawant — Motorsport & Mechanical Engineering Portfolio

> Official portfolio of **Aarya Sanjay Sawant** — Mechanical Engineer specializing in BAJA SAE Braking & Transmission, SolidWorks CAD, ANSYS FEA/CFD, and Precision Prototyping.

---

## 🚀 Deploy to Vercel

This project is configured and 100% ready for instant deployment on [Vercel](https://vercel.com).

### Option 1: Instant CLI Deployment (Recommended)

From this directory in PowerShell or Terminal, run:

```bash
npx vercel
```

- When prompted:
  - **Set up and deploy?** `Y`
  - **Which scope?** (Select your personal Vercel account)
  - **Link to existing project?** `N`
  - **Project name?** Press `Enter` (defaults to `aarya-sawant-portfolio`)
  - **Directory located?** Press `Enter` (defaults to `./`)
  - **Want to modify settings?** `N`

To deploy directly to production with a custom live URL:
```bash
npx vercel --prod
```

---

### Option 2: Connect via GitHub (Automatic Continuous Deployment)

1. Create a new GitHub repository (e.g. `aarya-sawant-portfolio`).
2. Push this repository:
   ```bash
   git remote add origin https://github.com/<your-username>/aarya-sawant-portfolio.git
   git branch -M main
   git push -u origin main
   ```
3. Go to [vercel.com/new](https://vercel.com/new).
4. Click **Import** next to your repository.
5. Framework Preset: **Other** (detected automatically).
6. Click **Deploy**. Any future `git push` will automatically trigger a new deployment.

---

## 🛠 Local Preview

To preview the portfolio locally:

```bash
npx serve .
```
Then open `http://localhost:3000` in your browser.

---

## 📁 Project Structure

```
├── index.html                            # Canonical root entrypoint for Vercel
├── Aarya_Resume.html                     # Synchronized portfolio file
├── vercel.json                           # Edge routing, clean URLs, security & caching headers
├── package.json                          # Project metadata & npm scripts
├── .gitignore                            # Excluded from git commits
├── .vercelignore                         # Excluded from Vercel deployments
├── f1-logo.svg                           # Favicon & branding asset
├── ferrari-logo.svg                      # Scuderia Ferrari logo asset
├── ferrari-f1-topview.svg                # F1 technical topview schematic
├── hero.mp4                              # Video background asset
├── Formula1-*.woff2                      # Official Formula 1 Web Fonts (Regular, Bold, Wide, Black)
└── *.png                                 # Engineering project schematics & FEA renders
```

---

## ⚙️ Vercel Optimizations Configured

- **Entrypoint**: `index.html` at root `/`
- **Clean URLs**: Clean URL resolution (`/resume`, `/Aarya_Resume`)
- **Font Caching**: 1-year immutable caching for `woff2` fonts
- **Media Caching**: Stale-while-revalidate caching for `mp4` and images
- **Security Headers**: `nosniff`, `SAMEORIGIN`, and strict referrer policy
- **Favicon & Social Previews**: Open Graph metadata configured for LinkedIn & Twitter previews
