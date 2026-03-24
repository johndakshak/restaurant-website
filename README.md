## 👤 Contributor Guide (For Newbies)

Follow these steps every time you work on the project.

---

### Step 1 — Accept the Invite
Check your email or GitHub notifications and accept the collaborator invite.

---

### Step 2 — Clone the Repo
This downloads the project to your computer. Open your terminal and run:
```bash
HTTPS:
git clone https://github.com/johndakshak/restaurant-website.git

SSH:
git clone git@github.com:johndakshak/restaurant-website.git
```
Then move into the project folder:
```bash
cd restaurant-website
```

---

### Step 3 — Open the Project
Open the folder in VS Code or any code editor. 

Every time before coding:

```bash
git pull origin main
```

This ensures:
✅ You have the latest version
✅ You avoid conflicts

---

### Step 4 — Create Your Own Branch
Before touching any file, create your own branch that is applicable to your task:
```bash
git checkout -b feat/your-task
```
Example of branch depending on your section/task:
```bash
git checkout -b feat/menu-page

git checkout -b feat/contact-page

git checkout -b feat/about-page

```

---

### Step 5 — Make Your Changes
Create your file

Example:

menu.html
contact.html
about.html

Edit whichever file you were assigned. Save your work.

---

### Step 6 — Stage and Commit
```bash
git add .
git commit -m "describe what you changed here"
```
Example:
```bash
git commit -m "Update food cards on menu page"
```

---

### Step 7 — Push Your Branch

NOTE: Kindly pull before you push

```bash
git pull origin main
```

```bash
git push origin your-name/your-task
```

---

### Step 8 — Open a Pull Request
1. Go to the repo on GitHub
2. Click **"Compare & pull request"**
3. Write a short description of what you did
4. Click **"Create Pull Request"**

---

### Step 9 — Wait for Review
A teammate will review and merge your changes. You're done!

---

### Step 10 — Stay Updated
Whenever someone else's work gets merged, run this to keep your copy current:
```bash
git checkout main
git pull origin main
```
Then create a new branch for your next task and repeat from Step 4.

---

> Every task follows the same cycle: **pull → branch → edit → commit → push → pull request**