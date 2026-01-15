# LearningGithubActions
This document contains my **Day 1 learning notes** for GitHub Actions.  
It explains **what GitHub Actions is**, **how to create a workflow**, and **important core terms** in a simple and clear way.

---
## 📌 What is GitHub Actions?

GitHub Actions is a **CI/CD automation tool** provided by GitHub.  
It allows you to automate tasks like:

- Running tests
- Building applications
- Running scripts
- Deploying code

These tasks are executed automatically when certain **events** happen in a repository.

---

## 🧭 Steps to Create a GitHub Actions Workflow

### 1️⃣ Sign up or Login to GitHub
Go to:  
👉 https://github.com  
Sign up or log in to your account.

---

### 2️⃣ Create a New Repository
- Click on **New Repository**
- Enter repository name
- Choose **Public** or **Private**
- Click **Create repository**

---

### 3️⃣ Create Workflow Directory
Inside the repository, create the following directory structure:
```
.github/workflows
```
> ⚠️ This folder name is mandatory for GitHub Actions.

---

### 4️⃣ Create a YAML Workflow File
Inside `.github/workflows`, create a file with `.yml` extension.

---

### 6️⃣ Commit and Push Changes
- Save the file
- Commit the changes
- Push the code to GitHub

---

### 7️⃣ Open the Actions Tab
- Go to the repository main page
- Click on the Actions tab

---

### 8️⃣ Check Workflow Execution

---

## 📚 GitHub Actions Terminology

### 🔹 Workflow
A workflow is a collection of jobs defined in a YAML (`.yml`) file that automates tasks in a GitHub repository.

---

### 🔹 name
Specifies the name of the workflow as displayed in the **Actions** tab of the repository.

---

### 🔹 Events
Events are activities that occur in a repository and trigger the execution of a workflow.

---

### 🔹 on
Defines when a workflow should run by specifying the triggering event.

---

### 🔹 Jobs
A job is a collection of steps that execute together on the same runner.

---

### 🔹 runs-on
Specifies the type of operating system environment on which a job runs.
