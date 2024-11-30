# Learning Git and GitHub

This repository is a personal project aimed at learning and practicing Git and GitHub. It contains a collection of exercises, commands, and resources to help understand version control and collaborate on software development using Git and GitHub.

## Table of Contents

- [Introduction](#introduction)
- [Setup and Installation](#setup-and-installation)
- [Git Basics](#git-basics)
  - [Cloning a Repository](#cloning-a-repository)
  - [Creating and Switching Branches](#creating-and-switching-branches)
  - [Committing Changes](#committing-changes)
  - [Pushing and Pulling](#pushing-and-pulling)
- [GitHub Basics](#github-basics)
  - [Creating a Repository on GitHub](#creating-a-repository-on-github)
  - [Forking and Pull Requests](#forking-and-pull-requests)
- [Resources](#resources)

## Introduction

Git is a powerful version control system that helps developers track and manage code changes. GitHub is a cloud-based platform that provides Git repository hosting and collaboration features. This repository is intended to serve as a learning resource for Git and GitHub concepts, and to practice using version control in real-world scenarios.

## Setup and Installation

### Prerequisites:

- [Git](https://git-scm.com/downloads) installed on your machine.
- A [GitHub](https://github.com/) account.

### Clone this Repository:

To get started with the exercises and learn Git commands, clone this repository to your local machine:

```bash
git clone https://github.com/your-username/learning-git-and-github.git
```

Replace `your-username` with your GitHub username.

### Navigate into the Project Directory:

```bash
cd learning-git-and-github
```

## Git Basics

### Cloning a Repository

To clone a Git repository, use the `git clone` command:

```bash
git clone <repository-url>
```

This copies the repository to your local machine and sets up a connection to the remote GitHub repository.

### Creating and Switching Branches

Git allows you to work on different features or fixes simultaneously using branches.

- **Create a new branch**:

  ```bash
  git checkout -b <branch-name>
  ```

- **Switch to an existing branch**:
  ```bash
  git checkout <branch-name>
  ```

### Committing Changes

After making changes to your files, you need to commit them to your local repository.

1. **Stage your changes**:

   ```bash
   git add <file-name>
   ```

   Or to stage all changes:

   ```bash
   git add .
   ```

2. **Commit your changes**:
   ```bash
   git commit -m "A brief description of what you changed"
   ```

### Pushing and Pulling

- **Push your changes to GitHub**:

  ```bash
  git push origin <branch-name>
  ```

- **Pull the latest changes from the remote repository**:
  ```bash
  git pull origin <branch-name>
  ```

## GitHub Basics

### Creating a Repository on GitHub

To create a new repository on GitHub:

1. Go to [GitHub](https://github.com).
2. Click on the "New" button to create a new repository.
3. Follow the prompts to name your repository and set up its settings (visibility, description, etc.).
4. After creation, you can clone it locally and start working on it.

### Forking and Pull Requests

- **Forking a repository**: Forking is creating a copy of someone else's repository to your own GitHub account. This allows you to make changes to the code without affecting the original project.
  - Click the "Fork" button on the top right of a repository's page.
- **Pull Request**: After making changes to your forked repository, you can submit a **Pull Request** (PR) to propose those changes to the original repository.
  - Push your changes to your fork.
  - Go to the original repository and click "New Pull Request".
  - Review your changes and submit the PR.

## Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/en/github)
- [Pro Git Book (free online)](https://git-scm.com/book/en/v2)
