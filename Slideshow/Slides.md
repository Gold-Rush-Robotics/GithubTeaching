---
marp: true
theme: dracula
html: true
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
---
![bg right width 100%](img/Logo_MainGreenBorder.png)
# Intro to Git/Github
by: Philip Smith & Sam Crane

## <!--fit-->with Gold Rush Robotics
---

# Goals

By the end of this workshop you should be able to:

* Use Git and Github to manage your own projects
* Clone and collaborate on other projects

---

# What is git?

* Version Control
    - Backup
    - Revert
    - Collaborate
    - Branch
* Local
* Often Associated with code, but can be used for anything that is a file (binaries loose the ability for merge 😔)
* **Industry standard**

---

# How Does it work?

* Commits
    * Change Snapshots
    * Commit message
* Branches
    * Protects main codebase
    * Allows you to test without breaking it


<!--
In order to do those things, Git splits your work into something called a "commit" you can think of a commit as a  snapshot of the changes you made since the last commit

you want your commits to be small, and you commit messages to be descriptive so you know when you did what (in case you need to revert)

git also has a concept called branches, you can visualize git commits like a tree, which is why they are called branches

Generally, all new code goes on a branch until it works and then it is merged in.
-->

---

# Workflow with git

1. Make changes 
2. git add
3. git commit

---

# What is GitHub?

* Free Online Repository Hosting
* Easy Sharing
* Home to **ALMOST ALL** open source projects
* CI/CD tools
* Team and Project Managment Tools
* Issue Tracker
* Free Cloud Computing
* **AND SO MUCH MORE**

---
# Adding GitHub to the git workflow
* Before working, make sure to fetch and then pull
* Do your standard git workflow
* Push your code
* Optional: add CI/CD workflows 

---
# <!--fit-->Lets Do It
---

# Creating a GitHub Account
##### Really one time

![bg left width 100%](img/Screen%20Shot%202023-02-18%20at%2012.13.57%20AM.png)

Go to [GitHub.com](https://github.com) and look for the box to type your email address, enter the email you wish to use and click Sign-up for GitHub.

Follow the prompts and create your account! 

---

# Downloading GitHub Desktop
##### Really one time

go to [desktop.github.com](https://desktop.github.com) and download it

Sign in, you will see something like this
![bg right width 100%](img/Screen%20Shot%202023-02-18%20at%201.10.53%20AM.png)

---

![bg](img/Screen%20Shot%202023-02-18%20at%201.10.53%20AM.png)

<!-- speaker notes: the tutorial repository is great whenever you need a refresher

Lets go ahead and Click Create a new Repository on your hard Drive
-->

---

![bg left height 100%](img/Screen%20Shot%202023-02-18%20at%204.30.40%20AM.png)

# Creating a Repo
##### Once per project
* Name: the name of the repo and the folder it will live in on your computer
* Description: helps populate the README
* Local Path: where the repo will live on your machine

---
![bg left height 100%](img/Screen%20Shot%202023-02-18%20at%204.30.40%20AM.png)

# <!--fit-->Creating a Repo (cont)

* Initializing with a README: this creates a README.md, which is how other people understand your repo
* Git Ignore: this is powerful tool to help not flood your git history or gitHub with compiled files
* License: this allows you to pick a license for your repo (standard is MIT)

---

![bg  width 100%](img/Screen%20Shot%202023-02-18%20at%204.44.04%20AM.png)

<!-- 
The defualt view of github desktop, go ahead and hit publish repo, or CMD/CTRL P
-->

---
# Add Content

* Click on view the files of your repository 
    - If you have an external editor installed click open in external editor instead
* Add a file at that location, name it yourname.txt
* open it up, and put your name in it
* save the file
* go back to github desktop

---
![bg left width 100%](img/Screen%20Shot%202023-02-18%20at%205.11.42%20AM.png)

# <!--fit--> Changes view

* In the changes view, you see all the files changed since the last commmit 
* You can see exactly what changed, Line by Line in each file
* Click the Checkbox next to the changes you want to save

---

# Making your first commit

* Once you add the file by clicking the checkbox, fill in the summary, or accept GitHub Desktops auto summary
* You can also add a description if you wish to add more info about the changes
* Then in the top menu, click publish branch (will become "push changes" if you had already worked on the branch)

---

![bg left height 100%](img/yay.gif)

# Success
* **You** now have something you wrote on GitHub (first time is the hardest)
* Lets go have a look...
    * [Open GitHub](https://github.com)
    * look on the sidebar for your repo
    * click on it


---
# Summary
* While it might take a bit to setup, Git and Github gives you power over your code and keeps you from being able to loose it. Cloud Backups FTW. 
* In addition to creating your own repos, You can clone other peoples public repos!
    * Try it out with this repo: https://github.com/Gold-Rush-Robotics/GithubTeaching
        * Just click on the code button
        * And then the Open in Github Desktop button
---

# Summary pt 2

* git and GitHub are powerful tools that we have **BARELY** scratched the surface of today
* If we have time, Philip will show how the workflow goes once it is all setup!

# Thanks For Comming!


---
# Questions?

if you have any now or later feel free to shoot me an email (philip@randomsmiths.com or psmit145@uncc.edu)
