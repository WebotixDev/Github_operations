# Git and GitHub Version Control Setup Guide

## Step 1: Install Git

1. Download Git from the official website:  
   [https://git-scm.com/downloads/win](https://git-scm.com/downloads/win)

2. Run the installer and complete the installation with default settings.

---

## Step 2: Install GitHub Desktop

1. Download GitHub Desktop:  
   [https://desktop.github.com/](https://desktop.github.com/)

2. Install and launch GitHub Desktop.

3. **Login with your GitHub account**:  
   - If you have an account, log in.  
   - If not, create one at [https://github.com](https://github.com) and then log in.

4. **Share your GitHub username** with the admin to receive repository access.

---

## Step 3: Clone Repository

1. After being added to a repository:
   - Accept the repository invitation from your GitHub account.

2. In GitHub Desktop:
   - Go to `File` > `Clone Repository`
   - Select the repo and choose a local path
   - Click `Clone`

---

## Step 4: Pull Latest Code

Before making any changes, **pull the latest code** to your local machine:

- In GitHub Desktop, click `Fetch origin` to sync with the remote repository.

---

## Step 5: Make Changes and Commit

1. Make code or file changes in your local repo using any editor (e.g., VSCode).

2. After changes:
   - Open GitHub Desktop.
   - You will see changed files listed.
   - Enter a commit message describing your changes.
   - Click `Commit to main` (or your working branch).

---

## Step 6: Push Changes to GitHub

- After committing, click `Push origin` in GitHub Desktop to upload your changes to the GitHub server.

---

## Step 7: Git Configuration (If Git Already Connected to Another Account)

### Unset Existing Global Git Credentials

```bash
git config --global --unset user.name
git config --global --unset user.email

```
### Set Your Personal Git Credentials

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

### Tips
- Always pull before making changes to avoid conflicts.
- Use meaningful commit messages.
- Use branches if working on features separately.
