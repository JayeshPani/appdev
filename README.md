# 📘 Git Basics & Commands Guide

---

## 🔹 What is Git?

Git is a **version control system**.

- It is used to preserve older and newer versions of code  
- All developers upload their code into the version controlling system  
- Helps in tracking and managing code changes  

---

## 🔹 Git Working Areas

Git works with 3 main sections:

### 1️⃣ Working Directory
- Folder where developer creates or stores code  
- Files here are called **untracked files**

---

### 2️⃣ Staging Area
- Intermediate buffer zone  
- Files moved here are called **staged files**

---

### 3️⃣ Local Repository
- Actual location where Git performs version control  
- Files here are called **committed files**

---

## 📂 Basic Commands

---

### 📁 Move into directory
```bash
cd C:
```
Create a directory
```bash
mkdir directoryname
```
Create a file
```bash
Method 1:
cat > filename
```
Method 2:
```bash
touch filename
```
Show list of files
```bash
ls
ls -lrt
```
### Git Commands
Send file from Working Directory to Staging Area
```bash
git add filename
```
Send multiple files to Staging Area
```bash
git add filename1 filename2 filename3
```
Check status
```bash
git status
```
Remove file from Staging Area
```bash
git reset filename
```
Send files from Staging Area to Local Repository
```bash
git commit -m "comments"
```
Check status again
```bash
git status
```
View Commit History
📜 View all commits
```bash
git log
```
View commits in one line
```bash
git log --oneline
```
