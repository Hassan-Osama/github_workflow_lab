# GitHub Workflow Practice Lab

This lab is designed to help you practice the basic development workflow using Git and GitHub.  
You will clone the repository, create your own branch, implement a simple function, commit your work, push it to GitHub, and open a Pull Request.

---

# Objectives

By completing this lab, you will practice:

- Cloning a repository
- Creating and switching branches
- Making commits
- Pushing changes to a remote repository
- Creating a Pull Request (PR)

---

# Instructions

## 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone <repository-url>
cd <repository-name>
```

---

## 2. Create your branch

Create a new branch using the following format:

```bash
name_id
```

Example:

```bash
hassan_12345
```

Command:
```bash
git checkout -b name_id
```

---

## 3. Navigate to the correct lab folder

Each lab has its own folder in the repository.

Example:

```bash
lab1/
lab2/
lab3/
lab4/
lab5/
lab6/
```
Go to the folder of the lab you are working on.

---

## 4. Create Your File

Inside the lab folder, create a new file using the following format:
name_id.<extension>

Example:
hassan_12345.js

---

## 5. Implement the Required Function

Write a simple function inside your file.

Example (Python):

```js
function greet(){
    console.log("YOUR NAME HERE");
}
```

---

## 6. Stage Your Changes

Add your file to the staging area:

```bash
git add .
```

---

## 7. Commit Your Changes

Commit with a meaningful message:

```bash
git commit -m "Add solution for lab1 - name_id"
```

---

## 8. Push Your Branch

Push your branch to GitHub:

```bash
git push origin name_id
```

---

## 9. Create a Pull Request

1. Go to the repository on GitHub  
2. Click **Compare & Pull Request**  
3. Create a PR from your branch to `main`

**PR title format:**
```bash
LabX - name_id
```

**Example:**
```bash
Lab1 - hassan_12345
```