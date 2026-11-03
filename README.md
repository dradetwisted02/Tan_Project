# Vanguard Business Portfolio & 4P Marketing Engine

A premier, high-converting digital business portfolio website and commercial strategy framework built for enterprise consulting, technical engineering, and business solutions.

---

## 🌟 What's Included

1. **Production-Ready Business Portfolio Website (`index.html`, `styles.css`, `script.js`):**
   - **Hero Section:** High-impact value proposition, dynamic client metric stats bar ($45M+ revenue, 99.2% delivery, 120+ deployments).
   - **About Section:** Operating philosophy, 4-step execution framework (Discovery, Strategy, Sprint Engineering, Scale).
   - **Core Capabilities:** 4 core strategic pillars (Custom Web & Platform Engineering, Performance & 4P Marketing, AI Automation, Brand Architecture).
   - **Interactive Portfolio Showcase:** Filterable case study cards (All, Engineering, Marketing, Automation) with quantified ROI metrics.
   - **Interactive 4P Marketing Matrix:** Interactive tabs detailing Product, Price, Place, and Promotion directly on the site.
   - **Transparent Pricing Tiers:** 3 flexible engagement models (Sprint Launchpad, Growth Engine, Enterprise Bespoke).
   - **Client Testimonials & Endorsements:** Social proof and verified founder quotes.
   - **Interactive Project Brief Form:** Custom intake form with immediate feedback modal.
   - **Responsive Design:** Polished glassmorphism theme, fluid typography, mobile drawer navigation, zero runtime dependencies.

2. **Complete 4P Marketing Blueprint (`MARKETING_4P_STRATEGY.md`):**
   - In-depth strategic documentation covering Product, Price, Place, Promotion, unfair advantages, unit economics, risk reversal, and a commercial KPI telemetry matrix.

3. **Built-in Node.js Preview Server (`server.js`):**
   - Zero-dependency local development server.

---

## 🚀 How to Run & Preview Locally

### Option 1: Direct File Open (Instant)
Simply double-click `index.html` or open it in any web browser (Chrome, Edge, Safari, Firefox):
```text
C:\Users\Brendan\.gemini\antigravity\scratch\business-portfolio\index.html
```

### Option 2: Local HTTP Server (Node.js)
Open PowerShell or Terminal and run:
```powershell
cd C:\Users\Brendan\.gemini\antigravity\scratch\business-portfolio
node server.js
```
Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🌐 Publishing Options (100% Free & Ready)

Because this website uses clean, modern HTML5, CSS3, and ES6 JavaScript with zero build compilation needed, it can be published instantly to any modern hosting platform:

### Method A: Deploy to GitHub Pages (Recommended)
1. Initialize a git repository in this folder:
   ```powershell
   cd C:\Users\Brendan\.gemini\antigravity\scratch\business-portfolio
   git init
   git add .
   git commit -m "Initial commit of Vanguard Business Portfolio"
   ```
2. Create a new public repository on [GitHub](https://github.com/new) (e.g. `business-portfolio`).
3. Push your repository:
   ```powershell
   git remote add origin https://github.com/<YOUR-USERNAME>/business-portfolio.git
   git branch -M main
   git push -u origin main
   ```
4. On GitHub, go to **Settings > Pages > Source**, select `Deploy from a branch` (`main` / root), and click **Save**.
5. Your website will be live at `https://<YOUR-USERNAME>.github.io/business-portfolio/` in ~60 seconds!

---

### Method B: Deploy to Vercel (1-Click or CLI)
- **Via Vercel Web:** Log into [vercel.com](https://vercel.com), click **Add New Project**, import your GitHub repo (or drag the `business-portfolio` folder), and click **Deploy**.
- **Via Vercel CLI:**
  ```powershell
  npx vercel
  ```
  Follow the simple prompts and your site will be live on an SSL `*.vercel.app` domain immediately.

---

### Method C: Deploy to Netlify (Drag and Drop in 30 Seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop the `business-portfolio` directory directly into the browser window.
3. Netlify will instantly generate a live URL with free global CDN and HTTPS!

---

### Method D: Cloudflare Pages
1. Go to the [Cloudflare Dashboard](https://dash.cloudflare.com/) > **Workers & Pages**.
2. Select **Upload Assets**, drag the `business-portfolio` folder, and click **Deploy Site**.

---

## 📁 File Structure

```
business-portfolio/
├── index.html               # Main website markup & semantic structure
├── styles.css               # Modern glassmorphism CSS & responsive design
├── script.js                # Dynamic filtering, interactive tabs, mobile menu & form handling
├── server.js                # Zero-dependency local Node.js preview server
├── vercel.json              # Vercel deployment & security headers config
├── MARKETING_4P_STRATEGY.md # Comprehensive 4P Marketing Documentation
└── README.md                # Project documentation & deployment guide
```

---

## 💼 Customization Tips
- **Branding & Name:** Search and replace `Vanguard` with your preferred company or brand name in `index.html`.
- **Contact Details:** Update `brendan.inquiries@vanguardportfolio.io` in `index.html` to your actual business email.
- **Projects & Metrics:** Add your custom client logos and case study metrics in the `#portfolio` section.
