# Git Task Report

This document outlines the tasks performed in a Git repository and provides explanations along with the commands used.

## 1. Repository Initialization
**Task:** Initialize a new Git repository and provide a clear README file.

**Explanation:**
I initialized a new Git repository to start tracking changes in the project files. A `README.md` file was created to provide essential information about the project.

**Commands:**
```bash
$ git init
$ echo "# Git Task Report" > README.md
$ git add README.md
$ git commit -m "Initial commit with README file"
```

---

## 2. Branch Management
**Task:** Create and switch between multiple branches.

**Explanation:**
I created and managed multiple branches, each representing different features or fixes in the project.

**Commands:**
```bash
$ git branch feature1
$ git branch feature2
$ git branch fix-bug
$ git checkout feature1
```
To list branches:
```bash
$ git branch
```

---

## 3. Committing Changes
**Task:** Make changes to files, commit those changes with meaningful commit messages, and view the commit history.

**Explanation:**
I made changes in different branches and committed them with appropriate messages for clarity.

**Commands:**
```bash
$ git add .
$ git commit -m "Enhance feature1 functionality"
$ git log --oneline
```
To view the commit graph visually (using VSCode):
- Open the Git pane.

---

## 4. Merging and Resolving Conflicts
**Task:** Merge branches and resolve any merge conflicts that arise.

**Explanation:**
I merged branches back into the `master` branch and resolved conflicts when they occurred.

**Commands:**
```bash
$ git checkout master
$ git merge feature1
```
For resolving conflicts manually, I edited the conflicting files and committed the changes:
```bash
$ git add .
$ git commit -m "Resolve merge conflict between feature1 and master"
```

---

## 5. Tagging and Releases
**Task:** Tag specific commits and create a release.

**Explanation:**
I tagged important commits to mark version milestones and created release references for better project tracking.

**Commands:**
```bash
$ git tag v1.0 -m "Initial release"
$ git tag v1.1 -m "Enhanced feature2 functionality"
```
To push tags to the remote repository:
```bash
$ git push origin --tags
```

---

## Conclusion
All tasks were successfully completed, demonstrating proficiency in Git repository initialization, branch management, commit handling, conflict resolution, and tagging.
