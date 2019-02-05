# TY Intro to Git

Learning how to use Git. hello

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* [Git](https://git-scm.com/)
* A code editor (Visual Studio Code)

### Installing

Clone this project onto your machine:

```sh
git clone https://github.com/craicoverflow/transition-year-git-intro.git
```

Open the project in your favourite code editor.

## Git Commands

### Configure Git

Set your name in Git:

```sh
git config --global user.name "Your Name"
```

Set your email address in Git:

```sh
git config --global user.email "yourname@example.com"
```

### Creating Repositories

Create a new local repository:

```sh
git init .
```

Download a project:

```sh
git clone [url]
```

### Making Changes

List all new or modified files to be committed:

```sh
git status
```

Add file to a list of files ready to be committed:

```sh
git add [file]
```

Commit the list of files:

```sh
git commit -m "[descriptive commit message]"
```

### Branching

List all local branches:

```sh
git branch
```

Create a new branch:

```sh
git branch [branch-name]
```

Switch to a branch:

```sh
git checkout [branch-name]
```

Merge the changes made in a branch back into your current branch.

```sh
git merge [branch-name]
```

Delete a branch:

```sh
git branch -d [branch-name]
```

### Other Common Commands

Pull changes from GitHub:

```sh
git pull
```

Push your changes to GitHub:

```sh
git push
```

Shows a history of commits:

```sh
git log --oneline
```

Undo all unstaged changes:

```sh
git reset --hard
```