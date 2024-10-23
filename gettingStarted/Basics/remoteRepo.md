**Getting Started with GitHub: Signing Up and Pushing a Repository**

GitHub is a popular platform for hosting and collaborating on Git repositories. In this tutorial, we'll guide you through the process of signing up for GitHub, creating a new repository, and pushing an existing repository to GitHub. You should have already signed up and verified your email. if that is the case skip steps 1 and 2.

**Step 1: Sign Up for GitHub**
1. Open your web browser and go to https://github.com
2. Click on the "Sign up" button in the top right corner.
3. Follow the prompts.

**Step 2: Verify Your Email**
1. Check your email inbox for a verification email from GitHub.
2. Open the email and click the "Verify email address" button.
3. Ensure you are signed in.

**Step 3: Create a New Repository on GitHub**
1. Once you're signed in, click the "+" icon in the top right corner and select "New repository."
2. Enter ```myFirstGit``` as the name for your repository. When creating repositories in the future this name can be anything you like.
3. Choose the visibility of your repository. You can keep it public (visible to everyone) or private (visible only to you or collaborators). For now Lets keep it public.
4. Check the "Initialize this repository with a README" option.
5. Click the "Create repository" button.

**Step 4: Clone the Repository to Your Computer**
1. After creating the repository, you'll be taken to its main page. Click the "Code" button.
2. Copy the URL provided (usually in HTTPS format).
3. Open git bash on your computer using `The windows button ⊞` and typing _GitBash_ to search until `GitBash` appears in the list..
4. Navigate to the directory where you want to clone the repository using the `cd` command. ```cd ~/Documents/myFirstGit```
5. Run the command below, replacing `repository_url` with the URL you copied:

```bash
git clone repository_url
```

**Step 5: Pushing Your Existing Repository to GitHub**

1. Make sure you have a `.git` folder in the repository directory using ```ls```. The ```-a``` option with ```ls``` shows hidden files that you wouldn't be able to see in the file explorer. 

```bash
ls -a
```
* If we did everthing right on the previous page we should see a `.git` folder. If not got back to the [Previous page](git1.md) and follow those steps.

2. Assuming we did everything correct initializing the repo, we can now link your local repository to the GitHub repository:
(don't foget to replace `repository_url` with the URL you copied:)

```bash
git remote add origin repository_url
```
* this step is telling our local git that our remote counterpart can be located at the `repository_url`

6. Push your code to GitHub:

```bash
git push -u origin master
```
* this step is updating our remote version so that it matches our local version.
  
**Step 6: Check Your GitHub Repository**
1. Refresh your GitHub repository page. You should see your code files and the README you initialized.
2. Congratulations! You've successfully pushed your existing repository to GitHub.

That's it! You've now signed up for GitHub, created a new repository, and pushed your existing code to GitHub. You're ready to collaborate and share your code. Happy coding!

[Prev](git1.md) | [Up](README.md) | [Next](gitExtras.md)
