# Academic CV, Research Portfolio & Blog (Google Drive Integrated)

A fast, zero-dependency academic portfolio, CV, and research blog designed to showcase research files stored on **Google Drive** and host for free on **GitHub Pages**.

---

## 🚀 Quick Start (Preview Locally in 5 Seconds)

1. Open your File Explorer and navigate to this folder:  
   `C:\Users\Lenovo\.gemini\antigravity\scratch\research-portfolio`
2. **Double-click `index.html`**.  
   It will open immediately in your web browser (Chrome, Edge, Firefox). No software installation or command line required!

---

## 📁 How to Connect Your Google Drive Files

To display and embed your CV and research papers directly on your website:

### Step 1: Make your file viewable on Google Drive
1. Go to [Google Drive](https://drive.google.com).
2. Right-click your PDF file (your CV, research paper, or presentation slides).
3. Click **Share** &rarr; **Share**.
4. Under *General access*, change **Restricted** to **"Anyone with the link"** (Role: *Viewer*).
5. Click **Copy link**.

### Step 2: Extract the File ID
Your link will look like this:
```
https://drive.google.com/file/d/1A2b3C4d5E6F7g8H9iJkLmNoP/view?usp=sharing
                                ^^^^^^^^^^^^^^^^^^^^^^^^^
                                    This is your File ID!
```

### Step 3: Put your File ID into `index.html` or `blog-post.html`
- In `index.html`, search for `YOUR_GOOGLE_DRIVE_CV_FILE_ID` and replace it with your copied ID:
  ```javascript
  openDriveModal('1A2b3C4d5E6F7g8H9iJkLmNoP', 'Curriculum Vitae (PDF)')
  ```
- Visitors can now click the **"View CV"** or **"Preview Paper"** button to read the PDF directly in a clean modal popup!

---

## 🌐 How to Publish to GitHub Pages for Free (No Git Required)

1. Open [GitHub.com](https://github.com) and log into your account.
2. Click the **+** (plus icon) in the top right &rarr; **New repository**.
3. Name your repository:
   - **Option A (Main website):** `<your-username>.github.io`
   - **Option B (Subproject):** `research-portfolio`
4. Make sure it is set to **Public**, and check **Add a README file**. Click **Create repository**.
5. In your new repository on GitHub:
   - Click **Add file** &rarr; **Upload files**.
   - Drag and drop `index.html`, `blog-post.html`, `profile.png`, `cv.pdf`, `creature.png`, `sorry-creature.png`, and `README.md` into the browser window.
   - Click **Commit changes**.
6. Go to **Settings** (tab at the top of your repository) &rarr; **Pages** (on the left sidebar):
   - Under *Build and deployment* &rarr; *Branch*, select `main` (or `master`) and folder `/ (root)`.
   - Click **Save**.
7. In about 1 minute, your website will be live at:
   `https://<your-username>.github.io`
