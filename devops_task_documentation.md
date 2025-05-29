
# DevOps Internship Task Documentation

## Project Setup and Version Control Workflow

### 1. Project Initialization
- Created a new local project directory for the internship task.
- Initialized a new Git repository using `git init`.

### 2. Connecting to GitHub
- Created a new repository on GitHub: [Vizzko/task-3](https://github.com/Vizzko/task-3).
- Linked local Git repo to GitHub using:
  ```sh
  git remote add origin https://github.com/Vizzko/task-3.git
  ```
- Fixed remote URL issues and ensured correct connection to the GitHub repository.

### 3. First Commit and Push
- Added a `README.md` file with a title and brief description.
- Staged and committed the file:
  ```sh
  git add README.md
  git commit -m "Add initial README"
  ```
- Pushed the commit to the remote repository:
  ```sh
  git push -u origin master
  ```
  *(Note: Your default branch is named `master`)*

### 4. Branching Workflow
- Created a new branch called `dev` for development:
  ```sh
  git checkout -b dev
  ```
- Made and committed changes on the `dev` branch (such as editing `README.md`).
- Pushed the new branch to GitHub:
  ```sh
  git push -u origin dev
  ```

### 5. .gitignore File
- Created a `.gitignore` file to exclude unnecessary files (such as log files or system files) from being tracked by Git.
  ```sh
  echo "node_modules/" >> .gitignore
  git add .gitignore
  git commit -m "Add .gitignore"
  git push
  ```

### 6. Pull Request Workflow
- Opened a pull request (PR) on GitHub to propose merging changes from the `dev` branch into the `master` branch.
- Added a clear title and description for the PR.
- Observed that the PR was able to merge automatically (no conflicts).
- (If merged) Merged the PR to update the `master` branch with latest changes.

### 7. Tagging (Milestone Marking)
- Tagged the latest commit as a version milestone (e.g., `v1.0`):
  ```sh
  git tag -a v1.0 -m "First release"
  git push origin v1.0
  ```

---

## Summary of Concepts Learned

- How to initialize a Git repository and connect it to GitHub.
- Creating, switching, and pushing branches to enable safe parallel development.
- Creating pull requests for code review and merging changes.
- Using a `.gitignore` file to exclude unnecessary files from version control.
- Tagging important versions in project history.
- Collaborative workflow even when working solo.

---

## Next Steps

- Continue to use branches for new features or bug fixes.
- Document all changes and features in the README or separate markdown files.
- Submit the GitHub repository link as per internship guidelines.

---

**Tip:** You can update this documentation as you add more features or steps!
