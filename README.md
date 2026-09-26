# sorry01 - Celestial Maintenance Page

A modern, responsive, and animated server maintenance page with a live downtime clock and high-quality artwork integration.

## 🚀 GitHub Pages Setup Guide

To host this project on GitHub Pages for the repository `sorry01`:

1. **Create Repository on GitHub**:
   - Create a new public repository named `sorry01` on GitHub.

2. **Push Code to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for sorry01 maintenance page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/sorry01.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub: `https://github.com/YOUR_USERNAME/sorry01`.
   - Click on **Settings** -> **Pages** (under Code and automation).
   - Under **Build and deployment**:
     - **Source**: Select `Deploy from a branch`.
     - **Branch**: Select `main` / `/ (root)`.
   - Click **Save**.

4. **Access Your Live Maintenance Page**:
   - Your page will be published live at:
     `https://YOUR_USERNAME.github.io/sorry01/`

---

## ⚙️ Configuration

### Changing the Downtime Clock Start Time
In `index.html`, locate the constant at the top of the `<script>` tag:

```javascript
const STARTING_DOWNTIME = "2026-09-26T12:00:00+06:00";
```

Replace the string with any starting timestamp in ISO 8601 format (including your timezone offset). The downtime clock will automatically calculate elapsed time and animate in real-time.
