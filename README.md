# TY Intro to Git

Learning how to use Git.
Updating readme.

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

## Pushing to GitHub

### Initialise your project

```sh
git init
```

### Create the project on GitHub

1. Login to your [GitHub](https://github.com/) account.

2. At the top right of any Github page, you should see a '+' icon. Click that, then select 'New Repository'.

3. Give your repository a name--ideally the same name as your local project. If I'm building a travel application, its folder will be called 'travel-app' on my computer, and 'travel-app' will be the Github repository name as well.

4. Click 'Create Repository'. The next screen you see will be important, so don't close it.

### Connect your local project folder to your empty folder/repository on GitHub

The screen you should be seeing now on Github is titled **'Quick setup — if you’ve done this kind of thing before'**.

Copy the link in the input right beneath the title, it should look something like this:
`https://github.com/mindplace/test-repo.git`
This is the web address that your local folder will use to push its contents to the remote folder on GitHub.

1. Go back to your project in the terminal/command line.

2. In your terminal/command line (Git Bash), type `git remote add origin [copied web address]`
    
    Example: `git remote add origin https://github.com/mindplace/test-repo.git`

3. Push your branch to Github: `git push origin master`

4. Go back to the folder/repository screen on Github that you just left, and refresh it. The title **'Quick setup — if you’ve done this kind of thing before'** should disappear, and you should see your files there.