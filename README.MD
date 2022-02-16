To set up GitHub you'll first need to set up an account at https://github.com/join. If you want to create a repository, you can do so at https://github.com/new. You can also make branches of your repository, which can let you make different versions of your repository without committing the changes to your main project. To make a branch, click the code tab of your repository, then click the dropdown at the top of the file list that says main. Type a branch name into the text box, and then click create branch: "branch name" from 'main'. Committing is when you save a change to your file, and each commit has a commit message which explains the change. 


Git is an open source version control system  for github, which you can ue for github related activities locally on your machine. To set it up you download and install the latest version of Git from https://git-scm.com/downloads. After that you will set your username using $ git config --global user.name "your username" and replace your username with whatever you will use as your username. You will also need to set your email with the following format $ git config --global user.email "your@email.com", replacing your@email.com with your email. 

After setting up Git you will need to authenticate with github, which you can do through https or SSH. If you choose https you can use the url with git clone, fit fetch, git pull, or git push. It will then ask you for your github username and password, but you will need to enter your personal access token instead of your actual github password.


Webstorm is an IDE that has integration with github, and lets you manage your projects from there. To download webstorm you can get it from the jetbrains website at https://www.jetbrains.com/webstorm/. To link your github account you open Ctrl+Alt+S to open the IDE settings and select Version Control|Github. After this you click +, then enter your github server URL. You then need to enter a token for your github account with the repo, gist, and read:org scopes enabled in your account permissions. 

If you don't already have a token with the necessary permissions you will need to verify your email address on github, and then go to your account settings by clicking on your profile in the top right. From your account settings you will need to click developer settings then personal acess tokens on the left sidebar. Then you will click generate new token, give it a name, and give it the required scopes. Then you click generate and give it to webstorm.

Glossary

**Branch**

A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.

**Clone**

A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.

**Commit**

A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.

**Fetch**

When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.

**GIT**

Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.


**Github**

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

**Merge**

Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.

**Merge Conflict**

A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.


**Push**

To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.

**Pull**

Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.

**Remote**

This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.

**Repository**

A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.


https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token

https://www.jetbrains.com/help/webstorm/github.html#register-account
https://docs.github.com/en/get-started/quickstart/set-up-git

https://docs.github.com/en/get-started/quickstart/github-glossary

