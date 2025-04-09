1.## 🌐 Steps to Deploy

### 1. Push Your Project to GitHub

If you haven't already, initialize git and push your project:


git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main


2.Sign in to Vercel
# Go to https://vercel.com

# Sign in using GitHub

# Click on "Add New Project"


3. Import Your GitHub Repository
# Select your project repo from the list
# Click "Import"

4. Configure Project (if needed)
Framework Preset: Vercel usually auto-detects it (e.g., React, Vite, etc.)

Root Directory: (optional) Set this if your project is in a subfolder

Build Command:

Static Site → leave it blank

React → npm run build

Output Directory:

Static Site → e.g., Level_0 or dist

React → build

5. Click “Deploy” 🚀
That’s it! Your site will be deployed and you’ll get a live link like:
"https://your-project-name.vercel.app"

