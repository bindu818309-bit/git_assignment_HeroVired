
git assignment for hero
# Git Assignment – HeroVired

## Repository Name
**git_assignment_HeroVired**

This repository contains the complete implementation of the Git & GitHub assignment provided by HeroVired.  
All tasks were completed using proper Git workflows, branching strategies, pull requests, code reviews, Git LFS, and Git stash.



## 📌 Assignment Overview

The assignment consists of **three mandatory questions**:

1. **CalculatorPlus Application**
2. **Git LFS Integration**
3. **Geometry Calculator using Git Stash**

Each task was completed in separate branches following best Git practices.

---

# ✅ Q1: CalculatorPlus Application

### Objective
Enhance a Python calculator application by adding a square root feature, fixing a critical bug, and managing releases using Git.

---

## 🔹 Steps Performed

### 1. Repository Creation
- Created GitHub repository named **git_assignment_HeroVired**
- Initialized with `main` branch

---

### 2. Development Branch
```bash
git checkout -b dev
3. Version 1 Release

Merged dev → main

Created Release v1.0.0 using GitHub Releases

4. Collaborators

Added classmates as collaborators via GitHub repository settings

Assisted at least one classmate by reviewing their code and providing feedback

5. Feature Branch – Square Root
git checkout -b feature/sqrt


Implemented square_root() function using math.sqrt()

6. Critical Bug Fix

Bug reported in divide() function (division by zero)

Fixed in dev branch:

def divide(self, a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero.")
    return a / b


Merged bug fix into feature/sqrt to keep it up to date

7. Pull Request & Code Review

Created PR from feature/sqrt → dev

Requested code review from collaborator

Implemented feedback changes

8. Version 2 Release

Merged dev → main

Created Release v2.0.0

🚀 Calculator Features

Addition

Subtraction

Multiplication

Division (with zero-division handling)

Square Root

✅ Q2: Git LFS (Large File Storage)
Objective

Efficiently handle large binary files using Git LFS.

🔹 Steps Performed
1. Git LFS Installation
git lfs install

2. LFS Branch Creation
git checkout -b lfs

3. Track Large Files
git lfs track "*.txt"


.gitattributes file committed

4. Large File Upload

Created a text file larger than 200MB

File tracked and committed using Git LFS

git add .gitattributes large_text_file.txt
git commit -m "Add large file using Git LFS"
git push origin lfs

5. Verification on Another Machine
git clone <repo-url>
git checkout lfs
git lfs pull


Verified the file was downloaded correctly

✅ Q3: Geometry Calculator (Git Stash)
Objective

Use Git stash to manage multiple incomplete features.

🔹 Branch Structure

geometry-calculator

feature/circle-area

feature/rectangle-area

🔹 Workflow Steps
1. Geometry Base Branch
git checkout -b geometry-calculator

2. Circle Area Feature
git checkout -b feature/circle-area


Started implementation

Stashed incomplete work:

git stash 

3. Rectangle Area Feature
git checkout -b feature/rectangle-area


Started implementation

Stashed incomplete work:

git stash 

4. Complete Features

Restored stashes using git stash pop

Completed both features

Committed and pushed each branch

5. Pull Requests

Created PRs to dev branch

Got code review approval

Merged both features into dev

Final merge into main

🧪 Geometry Calculator Features

Area of Circle

Area of Rectangle

📄 Submission File

A text file containing the GitHub repository link was created and uploaded to VLearn as required.

✅ Conclusion

This repository demonstrates:

Proper Git branching strategy

Feature development workflow

Pull requests & code reviews

Git stash usage

Git LFS integration

Release management

Author: Bindu
Course: DevOps / Git Assignment – HeroVired


---



GitHub Repository Link:

https://github.com/<your-username>/git_assignment_HeroVired

Repository Name: git_assignment_HeroVired
Repository Visibility: Private (will be made public after due date as instructed)

