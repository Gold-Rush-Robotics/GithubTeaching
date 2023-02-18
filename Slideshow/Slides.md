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
by: Philip Smith & Samantha Crane

## <!--fit-->with Gold Rush Robotics
---

# Goals

By the end of this workshop you should be able to:

* Use Git and Github to manage your own projects
* Clone and collaborate on other projects
* Use a branch and create a Pull Request (PR)

---

<!---
## Agenda
<div class="columns"><div>

- What is git
- What is github
- Goals
- Create a GitHub account
- Downlod Github desktop
- Create a repo
- Add / Commit
- Push / Pull
</div><div>

- Clone This Repo
- Make a branch 
- Add a file
- Make a Commit
- Push
- Create a Pull Request
- Summary and additional tools
</div></div>

--->

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

1. Make a branch
2. Make changes 
3. git add
4. git commit
5. Repeat 2-5 until you finish the goal of the branch
6. git merge branch back into main

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
* Instead of merging locally, create a Pull Request (PR)
* Optional: add CI/CD workflows 

---
# <!--fit-->Lets Do IT
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
# Branch Managment

* Click on the branch menu 
* Click on the New Branch button
* Name it your name
* GitHub desktop automatically created it, and checked it out

![bg left width 100%](img/Screen%20Shot%202023-02-18%20at%205.03.05%20AM.png)


![bg left width 100%](img/Screen%20Shot%202023-02-18%20at%205.06.23%20AM.png)


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
    * wait... what wheres {name}.txt ????


---

# Oh right... Branches

![bg left width 100%](img/Screen%20Shot%202023-02-18%20at%205.26.44%20AM.png)

* To view the code on a branch, click the dropdown circled in yellow
* You should see that file now! 
* Thats all we need on that branch, Time for a PR (Pull Reqeuest)

---

# Pull Requests
* There should be a giant banner at the top with a button that says "Compare and Pull Request" (GitHub is smart...) Click it
* Since it says "Able to merge" up at the top, we can click the create pull request down at the bottom. 
![Alt text](img/Screen%20Shot%202023-02-18%20at%205.30.45%20AM.png)

* GitHub will quickly check that it can sucessfully merge the branches again then a Merge Pull Request button will show up --> "Confirm merge" button --> "Delete Branch" button

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

<!--
If you click back on code, you should see the file on the main branch! 
-->



![bg left height 50%](img/Screen%20Shot%202023-02-18%20at%205.00.22%20AM.png)
# Bonus Hint
## Repo Management

You can change which repo you have selected in the Top right corner of GitHub desktop

---
# Questions?

if you have any now or later feel free to shoot me an email (philip@randomsmiths.com or psmit145@uncc.edu)
