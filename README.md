# LearningGitHub

Welcome to the **LearningGitHub** repository! This repository is designed to help you understand and practice the fundamentals of GitHub, including forking, cloning, branching, and making pull requests. By the end of this lab, you should be comfortable collaborating on GitHub projects. This repo was made for lab 4 of CS326: Web Programming at UMass Amherst.

## Objectives

By participating in this lab, you will learn to:
- Fork a repository
- Clone a repository to your local machine
- Create and switch branches
- Stage, commit, and push changes
- Submit pull requests (PRs)
- Participate in code reviews

## Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
- [Git](https://git-scm.com/downloads)
- [GitHub account](https://github.com/join)
- A text editor or IDE (such as [VS Code](https://code.visualstudio.com/))

### Step-by-Step Instructions

1. **Fork this Repository**
   - At the top-right corner of this page, click the "Fork" button. This will create a copy of this repository under your GitHub account.

2. **Clone Your Fork Locally**
   - On your forked repository page, click the green "Code" button and copy the HTTPS URL.
   - Open your terminal (or command line) and clone the repository by running:
     ```
     git clone https://github.com/YOUR_USERNAME/LearningGitHub.git
     ```
   - Replace `YOUR_USERNAME` with your GitHub username.

3. **Create a Branch**
   - Navigate to the repository directory on your local machine:
     ```
     cd LearningGitHub
     ```
   - Create a new branch to work on:
     ```
     git checkout -b my-branch-name
     ```
   - Replace `my-branch-name` with a descriptive branch name (e.g., `add-my-name`).

4. **Make Changes**
   - Open the repository in your text editor.
   - Add a .txt file with your name to the `student-edits` folder and write the following inside it:
     ```
     I was here!
     ```

5. **Stage and Commit Changes**
   - Stage the changes:
     ```
     git add .
     ```
   - Commit your changes:
     ```
     git commit -m "Added my name to the student-edits folder!"
     ```
   - As always, try to keep informative commit messages, so you know what you did in each commit!
     - ![commit xkcd](https://imgs.xkcd.com/comics/git_commit_2x.png) (https://xkcd.com/1296/)

6. **Push Your Changes**
   - Push the branch to your forked repository on GitHub:
     ```
     git push origin my-branch-name
     ```

7. **Create a Pull Request (PR)**
   - On your GitHub fork, you should now see a notification asking if you'd like to create a pull request for the changes you just pushed. 
   - Click "Compare & pull request."
   - Add a meaningful description, then submit the PR.

8. **Code Review and Merge**
   - Your instructor will review the pull request. You may be asked to make additional changes before it can be merged.
   - Once approved, your changes will be merged into the main repository.

## Helpful Git Commands

Here are some useful Git commands you might need:

- `git status`: Check the status of your working directory and staging area.
- `git branch`: List all branches in your local repository.
- `git checkout branch-name`: Switch to a different branch.
- `git pull origin main`: Update your local repository with the latest changes from the main repository.
- `git log`: View commit history.

## Resources
- [Class Cheat Sheet](https://docs.google.com/document/d/1JdusFWUcK-ikh_tf0qPjc08eYCMTcU96n8E2toFvIto/edit?usp=sharing)
- [Pro Git Book](https://git-scm.com/book/en/v2)
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Guides](https://guides.github.com/)

