# Connect this folder to your GitHub

Follow these steps to connect **my-new-project** to your GitHub account (jashhhhhhhh).

## 1. Set your Git identity (one-time, if not already set)

In PowerShell or Terminal, run (use your real name and GitHub email):

```powershell
git config --global user.name "jashhhhhhhh"
git config --global user.email "your-email@example.com"
```

Use the same email as your GitHub account.

## 2. Create a new repository on GitHub

1. Open: **https://github.com/new**
2. Sign in as **jashhhhhhhh** if needed.
3. **Repository name:** e.g. `my-new-project` (or any name you like).
4. Choose **Public** (or Private).
5. **Do not** check "Add a README" (this folder already has one).
6. Click **Create repository**.

## 3. Connect this folder and push

In PowerShell, from this folder (`c:\Users\mjkum\projects\my-new-project`):

```powershell
cd c:\Users\mjkum\projects\my-new-project

# Add your new GitHub repo as remote (replace REPO_NAME with the name you used in step 2)
git remote add origin https://github.com/jashhhhhhhh/REPO_NAME.git

# First commit (after setting user.name and user.email in step 1)
git add .
git commit -m "Initial commit"

# Push to GitHub (main branch)
git branch -M main
git push -u origin main
```

Replace `REPO_NAME` with the repository name you created (e.g. `my-new-project`).

## 4. Using SSH instead of HTTPS

If you use SSH keys with GitHub:

```powershell
git remote add origin git@github.com:jashhhhhhhh/REPO_NAME.git
```

Then `git push -u origin main` as above.

---

After this, your project will be at:  
**https://github.com/jashhhhhhhh/REPO_NAME**
