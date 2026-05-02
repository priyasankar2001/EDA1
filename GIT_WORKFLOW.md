# 🚀 GitHub Upload Workflow

## Complete Step-by-Step Guide to Upload Your Insurance EDA Project

---

## ⚠️ BEFORE YOU START

**Important:** You'll need to update these placeholders in README.md:
- `YOUR_USERNAME` → your actual GitHub username
- `Your Name` → your real name
- Your LinkedIn URL (or remove if not applicable)

---

## 📋 STEP 1: Prepare Your Local Folder Structure

Create this exact folder structure on your computer:

```
insurance-eda/
├── data/
│   └── insurance_synthetic_data.csv    ← YOUR DATASET GOES HERE
├── .gitignore
├── insurance_eda.ipynb
├── requirements.txt
└── README.md
```

**Action:** 
1. Create a new folder called `insurance-eda`
2. Create a subfolder called `data` inside it
3. Copy your **dataset** into the `data/` folder
4. Copy all the files I created for you into the main `insurance-eda/` folder

---

## 📋 STEP 2: Create GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **"+"** icon (top right) → **"New repository"**
3. Fill in:
   - **Repository name:** `insurance-eda`
   - **Description:** `Exploratory Data Analysis of insurance premium data using Python and Seaborn`
   - **Visibility:** ✅ Public (for portfolio)
   - **DO NOT** initialize with README, .gitignore, or license (we already have these)
4. Click **"Create repository"**

---

## 📋 STEP 3: Initialize Git in Your Local Folder

Open your terminal/command prompt and navigate to your project folder:

```bash
cd path/to/insurance-eda
```

Then run these commands **one by one**:

```bash
# Initialize git repository
git init

# Add all files to staging
git add .

# Create your first commit
git commit -m "Initial commit: Insurance EDA project with 30 analytical questions"

# Rename default branch to main (if needed)
git branch -M main
```

---

## 📋 STEP 4: Connect to GitHub and Push

**Replace `YOUR_USERNAME` with your actual GitHub username:**

```bash
# Add GitHub as remote repository
git remote add origin https://github.com/YOUR_USERNAME/insurance-eda.git

# Push your code to GitHub
git push -u origin main
```

**If you have 2FA enabled on GitHub**, you'll need to use a Personal Access Token instead of your password:
1. Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Generate new token (classic)
3. Select scopes: `repo` (full control)
4. Copy the token and use it as your password when prompted

---

## 📋 STEP 5: Verify Upload

1. Go to `https://github.com/YOUR_USERNAME/insurance-eda`
2. You should see:
   - ✅ README.md displayed beautifully
   - ✅ All your files listed
   - ✅ Folder structure visible

---

## 🎯 BONUS: Add Topics for Discoverability

On your GitHub repo page:
1. Click ⚙️ (Settings icon) next to "About"
2. Add topics:
   - `data-analysis`
   - `exploratory-data-analysis`
   - `python`
   - `seaborn`
   - `pandas`
   - `data-science`
   - `insurance`
   - `visualization`

This helps recruiters/employers find your project!

---

## 🔄 Making Future Updates

After making changes to your project:

```bash
# Check what changed
git status

# Add changed files
git add .

# Commit with a descriptive message
git commit -m "Description of what you changed"

# Push to GitHub
git push
```

---

## 🆘 Troubleshooting

### "Permission denied" error?
→ You need to set up SSH keys or use a Personal Access Token (see Step 4)

### "Repository not found" error?
→ Double-check your username in the remote URL:
```bash
git remote -v    # Check current remote
git remote remove origin    # Remove if wrong
git remote add origin https://github.com/CORRECT_USERNAME/insurance-eda.git
```

### Want to start over?
```bash
rm -rf .git    # Remove git tracking (careful!)
# Then start from Step 3 again
```

---

## ✅ Final Checklist

Before you share this repo on LinkedIn/resume:

- [ ] README.md has your actual name and GitHub username (not placeholders)
- [ ] All code runs without errors
- [ ] Dataset is in the `data/` folder
- [ ] .gitignore is preventing unnecessary files from being tracked
- [ ] Repository is set to **Public**
- [ ] Topics/tags are added for discoverability
- [ ] You've tested cloning the repo in a fresh folder to verify it works

---

**🎉 You're done! Your portfolio piece is now live on GitHub!**
