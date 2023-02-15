# A03
This repository is for the class IS117. Projects will be added here.
Abdullah Mumin
UCID: aam286 

## Github Tutorial

#### Create  an account
Github is a web-based Git repository hosting service. It offers all of the distributed revision control and source code management functionally.
A step-by-step instruction provided below:
<br>
* Go to [GitHub](github.com) and create and acount.
* Create a repository, give it a proper name. Remember, you will need the name included in the url later on.
* 




## Git Tutorial








## Webstorm Tutorial









## Part 2: Definition

* **Branch**: A separate repository that allows user to commit changes the code without changing anything to the main branch. User can merger the branch with main/master branch anytime later.
* **Clone**: User can get a local copy of the remote repository using `git clone` command. "`git clone repositoryURLhere`
* **Commit**: This command can save any changes to the document later which will be pushed to the repository. Using `git commit`, the editor will take a snapshot of the most recent edition of the document.
* **Fetch**: To make sure the user is working on the same state of the project, locally and remotely, it is a good practice to fetch the data. Using the command `git fetch` will make sure the user is working from the most recent changes.
* **GIT**: GIT is a version control system. It allows user or multiple users to work on a same project, save it as multiple versions, and edit any of them when needed. 
* **Github**: Github is the website that hosts git repositories. It allows users to pull files, review, edit, push files. It has a bunch of extensions that make editing convenient for the developer.
* **Merge**: User can join multiple branches together using `git merge` command. 
* **Merge Conflict**: Sometimes merge conflicted with each other because of two or multiple commits. It is when the version does not know which one is the latest commit and gives the user the conflicted message. It can be solved manually.
* **Push**: With `git commit`, browser save a screenshot of the latest changes. But to upload the file to the repository of the remote server, user must use the `git push` command.
* **Pull**: `git pull` command get the files from remote server and updates the local repository.
* **Remote**: A server that is global and accessible by multiple users from different places via internet.
* **Repository**: A server folder that holds all the files of a project, its edit history, and recent changes.


### Step 1-Make Account
Go to [GitHub](github.com) and create an account for **GitHub**.
![Account Creation](https://www.w3schools.com/git/img_githup_sign_up.png)
### Step 2-Make Repository
Click plus button dropdown in the upper righthand corner of the site on the navigation bar. Click the button that says `New repository`.
![Repo Creation](https://www.w3schools.com/git/img_github_new_repo.png)
Fill in the info for your repository. This one is for a W3 Schools [tutorial](https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github). We will be following that tutorial for the rest of this.
![Repo Info](https://www.w3schools.com/git/img_github_new_repo_create.png)
### Step 3-It's time to Push
Now the first time is going to be tough but we are going to **push** that repo we created in the GIT tutorial to your new GitHub account. Now breathe with me as we take our GitHub username and the GitHub repo name and combine into a URL like the one below.
> https://github.com/cc756/A03.git
Now we take this URL and breathe out as we head back to our command line.
```
git remote add origin https://github.com/cc756/A03.git
```
`git remote add origin URL` specifies that you are adding a **remote** repository, with the specified `URL`, as an `origin` to your local Git repo.
Okay it's time for that big push! I'll hold your hand if you need it as if this is your first time you will get a notification to authenticate.

**3**

**2**

**1**

**PUSH!**