# A03
<details>
<summary></summary>
This repository is for IS117 002.
Abdullah Mumin
UCID: aam286 

</details>

## Github Tutorial

#### Create  an account
Github is a web-based Git repository hosting service. It offers all of the distributed revision control and source code management functionally.
A step-by-step instruction provided below:
<br>
* Go to [GitHub](http://github.com) and create and account.
* Create a repository from the upper right corner of the navigation bar, give it a proper name. Remember, you will need the name included in the url later on. You can make it public for others to see or private just for you.
* After done creating the repo, click on it to open. Click on the green **code** button right upper corner. Select https and from the url field, copy the address.
* Open local terminal. Go to the local disk location you want to make your local repository using `cd` command. Type `git remote add origin yourRepoURLhere`, then enter. You will need to provide you admin and github username and password. Your local clone repository has created.
* Open *README.md* file from the repo, type something meaningful. Click commit changes, type a short meaningful sentence related to the changes, click ok. 
* It will ask you if you want to push the commit from the main branch or if you want a new branch. It is a good practice to use a new branch and then merge them.
* Have a look at your repository. You should see the file and recent commit added. 




## Git Tutorial

#### Download and install Git
  Download and install the latest version of Github. It will automatically install the Git. If you want to do manually, follow the instructions:
* For Mac users, install homebrew by running the command in the terminal `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
* Then type `$ brew install git` in the terminal and run.
**Git is installed**.
* Open **Git Shell** application.
* Enter these lines (use your own name and email):
  * `git config --global user.name "Abdullah Mumin"`
  * `git config --global user.email aam286@njit.edu`
  * You only need to do this once.
* With `git init` command, you will initialize or create a new repository. 
* `git commit` will save your most recent edit. Use it often. Its a good practice.








## Webstorm Tutorial

**Webstorm is code editor. See the instruction below on how to download and use it.**

* System Requirement to run Webstorm:
  * Minimum 2 gb of RAM, 8 gb recommended.
  * Any moder multi-core CPU.
  * Minimum 2.5 gb disk space. SSD with 5 gb space is recommended.
  * 64 bit version of Operating System.

**Installation**
* Download the latest version from [Jetbrains](https://jetbrains.com/webstorm/download/#section=mac) website.
* Create an account. You will have the option to buy a premium or 30-days free trial.
* You can also install it using the terminal. Just type and run `sudo snap install webstorm --classic`.
* Open the application after the installation done. 
* From the main window, you create a new project or open an existing one.
* You can also change the appearance from the *customize* section.
* Install necessary plugins by clicking on *plugins*.
* Using the *Remote Development* option, you can connect to your remote server and work on your project remotely.









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

