# 🌾 Krushi Mitra - Legal & Privacy Policy Repository

Official Privacy Policy and Terms & Conditions website for **Krushi Mitra** ("KishanBhai"), modern smart farming assistance app for Indian farmers (`com.mstar.krushi_mitra`).

This repository contains fully styled, mobile-responsive HTML pages ready to be deployed instantly on **GitHub Pages**, as well as Markdown versions viewable directly on GitHub.

---

## 📂 Repository Contents

| File | Description | Purpose |
| :--- | :--- | :--- |
| `index.html` | Portal landing page with cards linking to policies | Main website hub |
| `privacy-policy.html` | Complete Privacy Policy (Google Play & DPDP Act 2023 compliant) | **Google Play Console Privacy Policy URL** |
| `terms-and-conditions.html` | Complete Terms & Conditions with agricultural advisory disclaimer | In-app legal & terms redirect |
| `style.css` | Clean, responsive stylesheet with agricultural green theme | Mobile & desktop styling |
| `PRIVACY_POLICY.md` | Markdown format of the Privacy Policy | Direct GitHub viewing |
| `TERMS_AND_CONDITIONS.md`| Markdown format of the Terms & Conditions | Direct GitHub viewing |
| `404.html` | Fallback error page | Graceful navigation |

---

## 🚀 How to Publish on GitHub & Enable GitHub Pages

Follow these simple steps to make your Privacy Policy and Terms live on the web:

### Step 1: Create a New GitHub Repository
1. Go to [https://github.com/new](https://github.com/new).
2. Set Repository Name to: **`krushi-mitra-legal`** (or `khedutmitra-policies`).
3. Set Visibility to: **Public** *(required for free GitHub Pages)*.
4. Leave "Add a README file", ".gitignore", and "license" **unchecked** (we already have them).
5. Click **Create repository**.

### Step 2: Push This Repository to GitHub
Open your terminal in this directory (`d:\flutter_apps\krushi-mitra-legal`) and run:

```bash
git remote add origin https://github.com/MStar35/krushi-mitra-legal.git
git branch -M main
git push -u origin main
```

*(Replace `MStar35` if using a different GitHub account).*

### Step 3: Enable GitHub Pages in 1 Click
1. In your GitHub repository, click on **Settings** (gear icon at the top).
2. In the left sidebar, click **Pages** (under the "Code and automation" section).
3. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
4. Under **Branch**, select **`main`** and folder **`/(root)`**.
5. Click **Save**.
6. Wait 1-2 minutes. GitHub will show a green banner:  
   `"Your site is live at https://mstar35.github.io/krushi-mitra-legal/"`.

---

## 🌐 Your Live URLs

Once published, your URLs will be:

| Page | Live URL |
| :--- | :--- |
| **Privacy Policy (Google Play URL)** | `https://mstar35.github.io/krushi-mitra-legal/privacy-policy.html` |
| **Terms & Conditions** | `https://mstar35.github.io/krushi-mitra-legal/terms-and-conditions.html` |
| **Legal Hub** | `https://mstar35.github.io/krushi-mitra-legal/` |

---

## 📱 Google Play Console Submission

When submitting to Google Play Console:
1. Open [Google Play Console](https://play.google.com/console).
2. Go to your app > **Policy and programs** > **App content**.
3. Under **Privacy Policy**, paste your live Privacy Policy link:  
   `https://mstar35.github.io/krushi-mitra-legal/privacy-policy.html`
4. Click **Save**.

---

## 💡 Alternative: Hosting via Existing `khedutmitra` Repo

If you prefer not to create a separate repository, the identical files are also placed in the `/docs` folder of your existing `khedutmitra` repository:
1. In `https://github.com/MStar35/khedutmitra` > **Settings** > **Pages**.
2. Select **Branch: `main`**, and Folder: **`/docs`**.
3. Your live URLs will be:  
   - `https://mstar35.github.io/khedutmitra/privacy-policy.html`  
   - `https://mstar35.github.io/khedutmitra/terms-and-conditions.html`
