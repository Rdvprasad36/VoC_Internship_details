# How to Push Files to GitHub Repository

This guide explains how to push your local files to a GitHub repository.

## Prerequisites

- Git installed on your system
- A GitHub account
- A repository created on GitHub (e.g., https://github.com/Rdvprasad36/VoC_Internship_details)

## Steps to Push Files

1. **Open your terminal or command prompt** and navigate to your project directory. For example:

   ```bash
   cd path/to/your/project
   ```

2. **Initialize a Git repository** (if not already initialized):

   ```bash
   git init
   ```

3. **Add the remote repository URL**:

   ```bash
   git remote add origin https://github.com/Rdvprasad36/VoC_Internship_details.git
   ```

4. **Add files to the staging area**:

   ```bash
   git add .
   ```

5. **Commit the changes** with a message:

   ```bash
   git commit -m "Initial commit"
   ```

6. **Push the changes to the remote repository**:

   ```bash
   git push -u origin master
   ```

   > Note: If your default branch is `main` instead of `master`, replace `master` with `main`.

## Verification

- Go to your GitHub repository URL and refresh the page to see your files uploaded.

## Additional Tips

- To check the status of your repository:

  ```bash
  git status
  ```

- To see the commit history:

  ```bash
  git log
  ```

- To pull changes from the remote repository:

  ```bash
  git pull origin master
  ```

Replace `master` with your branch name if different.

---

This README provides a simple step-by-step guide to push your local files to a GitHub repository.
