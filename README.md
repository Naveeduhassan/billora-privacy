# Billora — Privacy Policy Webpage

This repository hosts the official, public Privacy Policy website for **Billora — Simple Invoice Maker** (`com.billora.app`), developed by **NH TechLabs**.

It is formatted as a single, self-contained, mobile-friendly HTML document (`index.html`) designed for zero-maintenance hosting on **GitHub Pages**.

---

## 📁 Repository Contents

* **`index.html`**: Complete, self-contained Privacy Policy webpage featuring:
  * Executive Precision design system styling (Navy `#172554`, Emerald `#059669`, Light background `#F8FAFC`).
  * Fast, responsive layout for mobile and desktop screens.
  * Zero external CSS frameworks, zero JavaScript dependencies, and zero tracking scripts.
  * Complete coverage of all 12 privacy sections matching `docs/privacy-policy-draft.md`.
  * Clearly marked contact and date placeholders ready for developer finalization.

---

## 🚀 Step-by-Step GitHub Pages Deployment Guide

Follow these simple steps to publish this privacy policy online for free using GitHub Pages:

### Step 1: Create a New Public Repository on GitHub
1. Log in to your GitHub account ([github.com](https://github.com)).
2. In the top-right corner, click **+** and select **New repository**.
3. Set the **Repository name** to: `billora-privacy`
4. Make sure the repository visibility is set to **Public** (required for free GitHub Pages).
5. Leave "Add a README file" unchecked (we will upload our own).
6. Click **Create repository**.

### Step 2: Upload Files to the Repository
You can upload either using Git command line or directly through GitHub's web interface:

#### Option A: Using the GitHub Web Interface (Easiest)
1. On the new repository page, click **uploading an existing file**.
2. Drag and drop `index.html` (and `README.md`) from the `billora-privacy` folder.
3. In the commit message box, enter: `feat: initial privacy policy webpage`
4. Select **Commit directly to the main branch**.
5. Click **Commit changes**.

#### Option B: Using Git Command Line
Run the following commands from your computer:
```bash
cd "E:\Web Development\App\Billora\billora-privacy"
git init
git branch -M main
git add index.html README.md
git commit -m "feat: initial privacy policy webpage"
git remote add origin https://github.com/<your-github-username>/billora-privacy.git
git push -u origin main
```
*(Replace `<your-github-username>` with your actual GitHub username).*

### Step 3: Enable GitHub Pages
1. In your GitHub repository, click on the **Settings** tab (the gear icon near the top right).
2. In the left-hand navigation sidebar, scroll down to the **Code and automation** section and click **Pages**.
3. Under **Build and deployment**:
   * **Source:** Select **Deploy from a branch**.
   * **Branch:** Select **`main`** from the dropdown menu.
   * **Folder:** Leave as **`/ (root)`**.
4. Click **Save**.

### Step 4: Verify the Live Webpage
1. Wait approximately 1 to 2 minutes for GitHub's automated build runner to deploy the site.
2. Refresh the **Settings > Pages** screen.
3. You will see a banner at the top:
   > **Your site is live at `https://<your-github-username>.github.io/billora-privacy/`**
4. Click the link to open your live Privacy Policy.

### Step 5: Test on Mobile
* Open the live URL on your Android or iOS smartphone to verify responsive layout, clear readability, and touch navigation.

---

## 🔗 Expected Live URL Format

Once deployed, your live privacy policy URL will be:

```text
https://<your-github-username>.github.io/billora-privacy/
```

For example, if your GitHub username is `naveed048`, the live URL will be:
```text
https://naveed048.github.io/billora-privacy/
```

---

## 📝 Remaining Placeholders Checklist

Before submitting this URL to Google Play Console:
- [ ] Open `index.html` and replace `[Effective Date, e.g., November 21, 2026]` with the confirmed date.
- [ ] Replace `[Developer/Contact Name, e.g., Naveed Ul Hassan]` with the official developer contact name.
- [ ] Replace `[Contact Email, e.g., support@nhtechlabs.com]` with the verified support email.
- [ ] Replace `[Official Website URL, e.g., https://nhtechlabs.com]` with your website or GitHub developer profile.
- [ ] Replace `[Physical / Mailing Address, City, Country]` with the developer mailing address.
- [ ] Commit and push the updated `index.html` to update the live site.
