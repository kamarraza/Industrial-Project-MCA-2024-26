# Industrial Project MCA 2024-26

## Overview
This repository contains the industrial project for the Master of Computer Applications (MCA) program for the academic year 2024-26.

# Step-by-Step Instructions for Students to Upload Files to Git Repository

## Prerequisites

Before starting, install Git on your computer.

Download Git from:
[Git Official Website](https://git-scm.com/downloads?utm_source=chatgpt.com)

After installation, restart your computer if required.

---

# Repository Details

Repository Name: **Industrial Project 2024-26**

Inside the repository there are two folders:

1. **Industrial Project**
2. **Training**

Students must upload:

* Their **Industrial Project** files inside the **Industrial Project** folder
* Their **Training** files inside the **Training** folder

---

# Step 1: Open Git Bash

* In Windows:

  * Right-click on Desktop or inside any folder
  * Click **Git Bash Here**

---

# Step 2: Clone the Repository

Use the repository link provided by the teacher.

Run the following command:

```bash
git clone <REPOSITORY_LINK>
```

Example:

```bash
git clone https://github.com/username/Industrial-Project-2024-26.git
```

---

# Step 3: Move into Repository Folder

```bash
cd "Industrial Project 2024-26"
```

---

# Step 4: Copy Your Files

## For Industrial Project Submission

* Open the folder:

```bash
Industrial Project
```

* Paste your complete project files/folders inside it.

---

## For Training Submission

* Open the folder:

```bash
Training
```

* Paste your training files/folders inside it.

---

# Step 5: Check Files Added

Run:

```bash
git status
```

This will show newly added files.

---

# Step 6: Add Files to Git

To add all files:

```bash
git add .
```

---

# Step 7: Commit Your Changes

Write your name and submission type.

Example:

```bash
git commit -m "Submitted Industrial Project and Training files - Your Name"
```

Example:

```bash
git commit -m "Submitted files - Rahul Sharma"
```

---

# Step 8: Upload Files to GitHub

Run:

```bash
git push origin main
```

If the branch name is `master`, then use:

```bash
git push origin master
```

---

# Step 9: Login if Asked

If GitHub asks for authentication:

* Enter your GitHub Username
* Enter Personal Access Token (PAT) instead of password

---

# Complete Command List

```bash
git clone <REPOSITORY_LINK>

cd "Industrial Project 2024-26"

git status

git add .

git commit -m "Submitted files - Your Name"

git push origin main
```

---

# Important Instructions

* Do NOT delete other students’ files.
* Upload files only inside the correct folder:

  * Industrial Project → Industrial Project Folder
  * Training → Training Folder
* Always run `git pull` before starting work.

```bash
git pull origin main
```

---

# Recommended Folder Structure

```text
Industrial Project 2024-26
│
├── Industrial Project
│   └── Student_Name
│       └── Project Files
│
└── Training
    └── Student_Name
        └── Training Files
```

---

# Example Submission

```text
Industrial Project/
    Rahul_Sharma/
        project_report.pdf
        source_code/
        ppt/

Training/
    Rahul_Sharma/
        training_report.pdf
        certificates/
```     ppt/
