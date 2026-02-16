# YOLO – Pothole Detection Assignment Repository

Welcome, students! 👋

This repository is designed for you to submit your assignments. Below you will find step-by-step instructions on how to set up your local environment and push your code using the required Git workflow.

---

## 📌 Getting Started

To complete your assignments, you will follow a **standard Git workflow**, which includes:

* Cloning the repository
* Creating a dedicated branch for your work
* Committing your changes
* Pushing your branch to GitHub
* Opening a Pull Request (PR)

---

## 🔄 Workflow Overview

1. Clone the repository to your local machine
2. Create a new branch using the required naming convention
3. Write your code and commit your changes
4. Push your branch to GitHub
5. Open a Pull Request (PR) to merge your work into the main branch

---

## 🛠 Step-by-Step Instructions

Follow the commands below in your **Terminal** or **Git Bash**.

---

### 1️⃣ Clone the Repository

Navigate to the directory where you want to store the project, then run:

```bash
git clone [REPOSITORY_URL]
```

After cloning, move into the project directory:

```bash
cd repository-name
```

---

### 2️⃣ Create and Switch to a New Branch

Create a new branch for your assignment using the required naming convention:

```bash
git checkout -b your-name/feature-description
```

✅ Example:

```bash
git checkout -b john/pothole-detection-model
```

This keeps your work isolated from the main codebase.

---

### 3️⃣ Make Changes and Commit

Work on your assignment files.

#### Stage your changes:

To stage all changes:

```bash
git add .
```

Or stage a specific file:

```bash
git add filename.py
```

#### Commit your changes:

```bash
git commit -m "Brief description of your changes"
```

✅ Example:

```bash
git commit -m "Added YOLO pothole detection training script"
```

---

### 4️⃣ Push Your Branch to GitHub

Push your branch to the remote repository:

```bash
git push -u origin your-name/feature-description
```

📌 The `-u` flag is only required the first time you push a new branch to set the upstream branch.

After the first push, you can simply use:

```bash
git push
```

---

### 5️⃣ Open a Pull Request (PR)

After pushing your branch:

1. Go to the repository on **GitHub** in your web browser.
2. You should see a yellow banner that says **Compare & pull request**.
3. Click **Compare & pull request**.
4. Make sure:

   * The **base branch** is `main` (or the default branch).
   * The **compare branch** is your feature branch.
5. Add a clear **title** and **description** explaining your changes.
6. Click **Create pull request**.

Your assignment will then be submitted for review.

---

## ✅ Important Notes

* Always use the correct branch naming format:
  `your-name/feature-description`
* Write meaningful commit messages.
* Do **not** push directly to the `main` branch.
* Ensure your code runs correctly before submitting your PR.

---

## 🚀 Good Luck!

Follow the workflow carefully, and feel free to ask questions if anything is unclear.

Happy Coding! 💻