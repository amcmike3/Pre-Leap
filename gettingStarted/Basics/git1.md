## Version Control With Git

### What is `git`?

`git` is _Version Control_ software which keeps track of the changes you make to files.

Imagine you're working on a big puzzle with your friends, and everyone has their own piece to add. Now, you want to make sure that everyone can work on their pieces without messing up each other's work. This is where Git comes in!

Git is like a magical puzzle manager for coders. It helps you and your friends work on the same code project without getting your pieces mixed up. Every time you or your friends want to make a change to the code, Git takes a picture of how the code looks right now. This is called a _snapshot_ or a "commit."

Let's say you and your friends are all working on a game. Each time someone adds a new feature or fixes a bug, Git takes a snapshot of the code. If something goes wrong and the code gets messed up, you can ask Git to go back to a previous snapshot, just like turning back time on the puzzle.

Git also lets you work on your own version of the code without affecting your friends' pieces. You can create your own "branch," which is like a separate copy of the puzzle. This way, you can try out new ideas without worrying about breaking the main puzzle that your friends are working on.

When you and your friends are ready to put all the pieces together, Git helps you "merge" your changes. It carefully combines all the snapshots from different branches and makes sure everything fits perfectly.

But remember, since Git is like magic, it's important to learn a few spells (or commands) to tell it what you want to do. For example, you can use commands like "commit" to take a snapshot, "branch" to create a separate copy, and "merge" to put everything together.

So, Git is like a puzzle manager that helps coders work together on projects without getting their pieces mixed up. It keeps track of changes, lets you try out new ideas, and ensures that everything fits together nicely in the end. And just like learning magic spells, practicing with Git will make you a master at managing code puzzles!

Lets walk you through creating your first version controlled project with Git!

<hr>

### 1. Create a Repository

**Getting Started with Git: Creating a Repository and Making a Commit**

Welcome to the world of Git! Git is a powerful tool that helps you manage and track changes in your code. In this tutorial, we'll walk you through the process of creating a new repository (repo) and making your first commit.

**Step 1: Install Git**
Before you start, make sure Git is installed on your computer. It should have been downloaded with git bash but if it didn't get installed for some reason, You can download it from the official website: https://git-scm.com/downloads

* verify it is installed by enter `git -v` in git bash or the cmd line

**Step 2: Setting Up Your Identity**
Open git bash and run the following commands to set your name and email. This is important because every commit you make will include this information.

```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

**Step 3: Create a New Repository**
1. Create a new folder on your computer where you want to keep your project.
```bash
cd ~/Documents
mkdir myFirstGit
```
2. Open your terminal and navigate to the newly created folder using the `cd` command.
```bash
cd ~/Documents/myFirstGit
```

**Step 4: Initialize Your Repository**
Run the following command to initialize a new Git repository in the folder:

```bash
git init
```

**Step 5: Create and edit a New File**
Create a new text file in the repository folder and make some changes to it.

```bash
touch file.txt
code file.txt
```
* this should open up visual studio code. Lets type `Hello World` and save file.txt.

**Step 6: Add and Commit**
Run the following command to see the status of your repository:

```bash
git status
```

This will show you the untracked file you created.

lets Add the file to the staging area using the following command:

```bash
git add file.txt
```
  * Alternatively if you want to add everything inside the repo run: 
```bash
git add .
```
* The period `.` simply means the entire folder I am currently in.

4. Run `git status` again to see that the file is staged.
     * `git status` tells you a number of things:

      * `On branch master` - You are using the 'master' (or main) source of your code.

      * `Initial commit` - You haven't created a _commit_ yet.

      * `nothing to commit` - No files have changed (actually none exist) in this _repository_, and there is nothing to save (_commit_)

5. Now, let's make your first commit! Run the following command:

```bash
git commit -m "Initial commit"
```

The `-m` flag allows you to write a short message explaining what this commit is about.

**Step 7: Check Your Commit**
Congratulations! You've just made your first commit. You can run the following command to see the commit history:

```bash
git log
```

This will show you the commit messages, authors, dates, and unique commit IDs.


Later we will start connecting local repositories to their remote counterparts. Platforms like GitHub, GitLab, and Bitbucket offer free hosting for Git repositories. We will be using GitHub.


That's it! You've successfully created a Git repository, added a file, and made your first commit. This is just the beginning of your journey with Git, but you've taken the first steps toward efficient code management and collaboration.

Next we will `push` this repo into the cloud and onto github. 


<hr>


[Prev](git.md) | [Up](README.md) | [Next](remoteRepo.md)
