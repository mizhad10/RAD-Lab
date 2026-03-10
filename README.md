
# RAD-Lab Project
## GitHub for Rapid Application Development (RAD)

---

## Student Information

**Name:** Mizen Hadush  
**Student ID:** MIT/ur190598/16  
**University:** Mekelle University – MIT Campus  
**Course:** Rapid Application Development (RAD)

---

# Project Objective

The objective of this project is to learn and demonstrate the practical use of **version control systems** using **Git and GitHub** in a Rapid Application Development environment.

This lab helps students understand how modern developers manage software projects, collaborate with teams, track changes in code, and deploy web applications efficiently.

The project covers the following key skills:

- Creating and managing repositories
- Uploading and managing project files
- Tracking code changes using version control
- Creating branches for feature development
- Merging branches into the main project
- Resolving merge conflicts
- Simulating collaboration workflows
- Deploying a website using GitHub Pages

---

# Tools and Technologies Used

- Git (Version Control System)
- GitHub (Code Hosting Platform)
- Visual Studio Code (Code Editor)
- HTML (Web Structure)
- CSS (Basic Styling)
- JavaScript (Basic Script)

---

# Project Structure

```

RAD-Lab
│
├── index.html
├── about.html
│
├── css
│   └── style.css
│
├── js
│   └── script.js
│
├── images
│   └── sample.txt
│
└── pages
└── contact.html

````

This structure demonstrates proper **project organization and modular file management**.

---

# Step-by-Step Project Implementation

## 1. Repository Creation

A new repository called **RAD-Lab** was created on GitHub.

Local project directory was created using:

```bash
mkdir RAD-Lab
cd RAD-Lab
git init
````

This initializes a new **Git repository**.

---

# 2. Creating the Main Web Page

The main webpage **index.html** was created to serve as the homepage of the project.

Basic HTML structure was implemented including:

* Title
* Heading
* Description
* Navigation link to About page

---

# 3. First Commit

The first version of the project was saved using Git commit.

```
git add index.html
git commit -m "First commit"
```

Commit messages help track changes in the project history.

---

# 4. Connecting Local Project to GitHub

The local repository was connected to the remote GitHub repository.

```
git remote add origin https://github.com/USERNAME/RAD-Lab.git
git branch -M main
git push -u origin main
```

This uploads the project to GitHub.

---

# 5. Creating Additional Pages

An additional page **about.html** was created to describe the project.

Commands used:

```
touch about.html
git add about.html
git commit -m "Added about page"
git push
```

This demonstrates how new features are added incrementally.

---

# 6. Creating Project Folders

Folders were created to organize project resources.

```
mkdir css
mkdir js
```

Files created:

```
touch css/style.css
touch js/script.js
```

Commit command:

```
git add .
git commit -m "Added css and js folders"
git push
```

---

# 7. Expanding the Project Structure

Additional folders were created to simulate a real web project.

```
mkdir images
mkdir pages
```

Additional files were added including:

* images/sample.txt
* pages/contact.html

Commit:

```
git add .
git commit -m "Added images and pages folders"
git push
```

---

# 8. Branching for Feature Development

Branches allow developers to work on new features without affecting the main project.

A new branch was created:

```
git checkout -b feature-header
```

A header section was added to the homepage.

Changes committed:

```
git add .
git commit -m "Added header"
```

Merged into main branch:

```
git checkout main
git merge feature-header
```

---

# 9. Footer Feature Branch

Another branch was created to implement the footer.

```
git checkout -b feature-footer
```

Footer section added.

Commit:

```
git add .
git commit -m "Added footer"
```

Merged into main branch.

---

# 10. Merge Conflict Resolution

Merge conflicts occur when two branches modify the same line of code.

Conflict markers appear like this:

```
<<<<<<< HEAD
code from main branch
=======
code from feature branch
>>>>>>> branch-name
```

The conflict was manually resolved by editing the file and committing the corrected version.

```
git add index.html
git commit -m "Resolved merge conflict"
```

This demonstrates conflict resolution in collaborative development.

---

# 11. GitHub Pages Deployment

The project was deployed online using GitHub Pages.

Steps:

1. Open repository settings
2. Navigate to Pages
3. Select main branch
4. Save

Website link format:

```
https://username.github.io/RAD-Lab
```

This allows the project to be accessed publicly as a website.

---

# Essential Git Concepts Demonstrated

### Repository

A repository is a storage location where the project files and version history are maintained.

### Commit

A commit records changes made to the project files.

### Branch

A branch allows developers to work on features independently.

### Merge

Merge combines changes from one branch into another.

### Conflict

A conflict occurs when two branches modify the same part of a file.

### Pull Request

A pull request is used for reviewing and merging code changes in collaborative environments.

---

# Learning Outcomes

Through this lab project, the following skills were developed:

* Understanding Git workflow
* Managing project versions
* Organizing web project structures
* Using branching strategies
* Resolving merge conflicts
* Deploying web applications using GitHub

These skills are essential for modern software development and collaborative programming.

---

# Summary

This project successfully demonstrates the use of **Git and GitHub for Rapid Application Development**.

The lab covered the full development lifecycle including:

* Project initialization
* Version control
* Feature development using branches
* Conflict resolution
* Collaboration workflow
* Website deployment

By completing this lab, a solid foundation in professional software development practices was achieved.

---

# Author

**Mizen Hadush**
Mekelle University – MIT Campus
Information Technology Student

---
