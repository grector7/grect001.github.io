# Augustus — ePortfolio

A static ePortfolio site built for CYSE 201S at Old Dominion University.

## 📁 What's in this folder

```
eportfolio/
├── index.html           ← About Me (homepage)
├── cyse.html            ← CYSE 201S overview
├── reviews.html         ← Article Reviews subpage
├── career.html          ← Career Paper subpage
├── presentation.html    ← Presentation subpage
├── case-study.html      ← Case Study subpage
├── styles.css           ← Shared stylesheet
├── files/               ← (Create this folder for your PDFs)
└── README.md            ← This file
```

---

## 🚀 Deploy to GitHub Pages — Step by Step

### Step 1: Create a free GitHub account
Go to [github.com](https://github.com) and sign up if you don't already have an account. Use an email you check regularly.

### Step 2: Create a new repository
1. Click the green **New** button (or go to https://github.com/new)
2. Name your repository — for the cleanest URL, name it: **`yourusername.github.io`** (replace with your actual GitHub username)
   - Example: if your username is `augustus123`, name the repo `augustus123.github.io`
   - This gives you the URL `https://augustus123.github.io` — no extra path needed
3. Set it to **Public**
4. Check the box for **Add a README file** (you can replace this later)
5. Click **Create repository**

### Step 3: Upload your files
1. On the repository page, click **Add file** → **Upload files**
2. Drag ALL the files from this folder (`index.html`, `cyse.html`, `reviews.html`, `career.html`, `presentation.html`, `case-study.html`, `styles.css`) into the upload area
3. At the bottom, write a commit message like "Initial portfolio upload"
4. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. In your repository, click the **Settings** tab (top right of the repo page)
2. In the left sidebar, click **Pages**
3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** (or `master`)
   - Folder: **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes for the site to deploy

### Step 5: Get your link
After a minute or two, you'll see a green message at the top of the Pages settings:
> ✅ Your site is live at `https://yourusername.github.io`

That's the link to submit for your assignment.

---

## ✏️ Customizing Your Portfolio

### Add your photo
1. Save your photo as `photo.jpg` (or .png)
2. Upload it to the same folder as your HTML files on GitHub
3. Open `index.html` and find this section (around line 28):
   ```html
   <!-- TO ADD YOUR PHOTO: Replace the div below with: <img src="photo.jpg" alt="Augustus" /> -->
   <div class="image-placeholder">
     ...
   </div>
   ```
4. Replace the entire `<div class="image-placeholder">...</div>` with:
   ```html
   <img src="photo.jpg" alt="Augustus" />
   ```

### Add the 3 images on the CYSE 201S page
1. Save your images as `image1.jpg`, `image2.jpg`, `image3.jpg`
2. Upload them to the same folder
3. Open `cyse.html` and find each `<div class="visual-placeholder">...</div>` block
4. Replace each one with `<img src="image1.jpg" alt="..." />` (use the matching filename)

### Add your papers (PDFs)
1. Create a folder called `files` in your repository (click "Add file" → "Create new file" → type `files/.gitkeep` → commit)
2. Upload your PDFs into that folder: `article-review-1.pdf`, `article-review-2.pdf`, `career-paper.pdf`, `presentation.pdf`, `case-study.pdf`
3. In each subpage HTML file (e.g., `reviews.html`), find this block:
   ```html
   <div class="upload-box">
     <div class="upload-label">UPLOADED FILE</div>
     <div class="placeholder">
       ...
     </div>
   </div>
   ```
4. Replace the entire `<div class="placeholder">...</div>` with:
   ```html
   <a href="files/article-review-1.pdf" class="file-button" target="_blank">
     View Article Review #1 <span class="arrow">→</span>
   </a>
   ```

### Edit the bio text
Open `index.html` and find the three `<p class="bio-para">` blocks. Edit the text inside each one to match your actual story.

---

## 🔧 How to Edit Files on GitHub

1. On your repository, click the file you want to edit (e.g., `index.html`)
2. Click the pencil icon (✏️) in the top right of the file viewer
3. Make your changes
4. Scroll to the bottom and click **Commit changes**
5. GitHub Pages will auto-update your live site within 1–2 minutes

---

## 🌐 Custom Domain (Optional)

If you want a custom domain (like `augustus.com` instead of `username.github.io`), GitHub Pages supports that too. See [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for instructions.

---

## ❓ Troubleshooting

- **Site shows 404 after deploying:** Wait a few more minutes. First-time deployments can take up to 10 minutes. Also double-check that `index.html` is in the root of the repo, not inside a subfolder.
- **Styles look broken:** Make sure `styles.css` is in the same folder as the HTML files.
- **Images not showing:** Check that the filename in the HTML exactly matches the uploaded file (case-sensitive on GitHub Pages).

---

Built with care. Good luck with the submission.
