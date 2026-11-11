# CPDJ-Webzine

# Website Collaboration Project

Welcome to our shared Neocities website project! This repository uses **GitHub Actions** to automatically publish updates directly to our Neocities site whenever changes are pushed or merged into the `main` branch.

## 🚀 How to Get Started

Follow these steps to set up the project on your computer and start editing:

### 1. Clone the Repository
Open your terminal (or use GitHub Desktop) and run:
```bash
git clone https://github.com
cd YOUR-REPO-NAME
```

### 2. Make Your Changes
1. Open the project folder in your favorite code editor (e.g., VS Code).
2. Edit or add your HTML, CSS, or JS files.
3. Test your changes locally by opening your `index.html` file in any web browser.

### 3. Save and Push Your Code
Once your edits look good, use Git to save and upload your progress:

```bash
# Check what files you changed
git status

# Stage all changes
git add .

# Commit your changes with a clear message
git commit -m "Fix: updated the navigation bar and layout"

# Push to GitHub
git push origin main
```

## ⚠️ Important

* **Always Pull First:** Before you start making edits, run `git pull origin main` to ensure you have the absolute latest code from everyone else. This prevents annoying code conflicts.
* **Neocities File Deletion:** The deployment workflow is set to clean up unused files. If you delete a file inside this GitHub repository, **it will also be deleted from the live Neocities site** on the next deploy.
* **Automatic Live Updates:** Do not manually upload files to the Neocities web dashboard. The GitHub Action will take care of deploying everything within 1 to 2 minutes of your push.
