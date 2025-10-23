# Online Liquor Licensing Portal - CEO Presentation Website

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?logo=github)](https://chimenyadev.github.io/OnlineLiquorPortal/)

This repository contains a professional presentation website for the KZNERA Online Liquor Licensing Portal project update meeting scheduled for **October 24, 2025 at 09:00**.

## 🌐 Access the Presentation

### Option 1: GitHub Pages (Recommended)

Once deployed, the presentation will be available at:

**https://chimenyadev.github.io/OnlineLiquorPortal/**

### Option 2: Local Access

1. Clone the repository:
```bash
git clone https://github.com/ChimenyaDev/OnlineLiquorPortal.git
cd OnlineLiquorPortal
```

2. Open `index.html` in your web browser:
   - **Windows**: Double-click `index.html` or right-click → Open with → Your preferred browser
   - **Mac**: Double-click `index.html` or run `open index.html` in terminal
   - **Linux**: Run `xdg-open index.html` in terminal

### Option 3: Local Web Server

For the best experience, use a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open your browser and navigate to: `http://localhost:8000`

## 📋 Deploying to GitHub Pages

### Quick Deploy (Enable GitHub Pages)

1. Go to your repository: https://github.com/ChimenyaDev/OnlineLiquorPortal
2. Click on **Settings** (top right)
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**
6. Wait 1-2 minutes for deployment
7. Your site will be live at: `https://chimenyadev.github.io/OnlineLiquorPortal/`

### Alternative: Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ChimenyaDev/OnlineLiquorPortal)

1. Click the button above
2. Connect your GitHub account
3. Site will be deployed automatically

### Alternative: Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ChimenyaDev/OnlineLiquorPortal)

1. Click the button above
2. Connect your GitHub account
3. Site will be deployed automatically

## 🎯 Presentation Features

- **11 Professional Slides** covering:
  - Project Overview
  - Current System Landscape (eLMS)
  - Key Stakeholders (KZNERA, SAB, Joxicraft, IT Related)
  - Project Progress (65% completion)
  - Key Achievements
  - Critical Bottlenecks (API Development)
  - Impact Analysis
  - Proposed Solutions
  - Action Plan
  - Recommendations

- **Interactive Navigation**:
  - Use arrow buttons (bottom right)
  - Keyboard shortcuts: Arrow keys or Spacebar
  - Slide counter (top right)

- **Print Ready**: Use browser print function (Ctrl+P / Cmd+P) for PDF export

## 🎨 Customizing Brand Colors

To update the presentation with KZNERA's official brand colors:

1. Open `index.html`
2. Locate the `:root` section (around line 12):

```css
:root {
    /* KZNERA Brand Colors - UPDATE THESE */
    --primary-color: #003366;      /* Replace with KZNERA primary */
    --secondary-color: #0066CC;    /* Replace with KZNERA secondary */
    --accent-color: #FFB81C;       /* Replace with KZNERA accent */
}
```

3. Replace the hex color codes with your official brand colors
4. Save and reload the page

## 📱 Responsive Design

The presentation is fully responsive and works on:
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Tablets (iPad, Android tablets)
- Mobile devices (optimized for landscape viewing)

## 🖨️ Exporting to PDF

1. Open the presentation in your browser
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Select "Save as PDF" as the destination
4. Adjust settings:
   - Layout: Landscape
   - Margins: None
   - Background graphics: Enabled
5. Click Save

## 📊 Presentation Content Structure

1. **Title Slide** - Meeting details
2. **Project Overview** - Sponsor, beneficiary, objectives
3. **Current System Landscape** - eLMS background
4. **Key Stakeholders** - All project partners
5. **Project Progress** - Status indicators
6. **Key Achievements** - Completed milestones
7. **Challenges & Bottlenecks** - API development issues
8. **Impact Analysis** - Timeline and stakeholder effects
9. **Proposed Solutions** - Action items
10. **Action Plan** - Week-by-week timeline
11. **Recommendations** - Discussion points for CEO

## 🔧 Technical Stack

- **Pure HTML5** - No dependencies
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - Lightweight navigation
- **No Build Process** - Deploy as-is

## 📞 Support & Questions

For questions about the presentation or technical issues:
- **Project Lead**: KZNERA Project Management Team
- **Repository Owner**: @ChimenyaDev
- **Technical Support**: Create an issue in this repository

## 📄 Project Context

- **Project**: Online Liquor Licensing Portal (OnlineLiquorPortal)
- **Sponsor**: SAB (Full Funding)
- **Beneficiary**: KZNERA (Regulatory Authority)
- **Partners**: Joxicraft (Frontend), IT Related (API/eLMS)
- **Meeting Date**: October 24, 2025 @ 09:00

## 📜 License

This presentation is proprietary to KZNERA. All rights reserved.

---

**Last Updated**: October 23, 2025  
**Version**: 1.0  
**Status**: Ready for Deployment