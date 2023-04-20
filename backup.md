
# Content

1. [Installing and Creating Git & GitHub Account](#installation)
2. [Setting up Git Environment](#setting-up-git-environment)
3. [Upload a folder in Github](#upload-a-filefolder-to-github)

# Installation

* How to **Create GitHub Account** Step by Step (**[Tutorial Link](https://youtu.be/QUtk-Uuq9nE)**)
* Git (**[Download](https://git-scm.com/downloads)**)
* How to **install Git** Step by Step (**[Tutorial Link](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-1)**)
* GitHub Desktop (**[Download](https://desktop.github.com/)**)

# Setting up Git Environment

Vedio Tutorial : **([Click Here](https://www.youtube.com/watch?v=yDntCIs-IJM))**

1. Open Git Bash
2. Write The Following Commands

    * **Set Name** :  ``` git config --global user.name "Gihub User Name" ```
    * **Set Email** : ``` git config --global user.email "Github Email" ```
    * **Check status** :  ``` git config --list ```
3. Setting Done Successfully

# Upload a file/folder to Github

Vedio Tutorial : **([Click Here](https://www.youtube.com/watch?v=eGaImwD8fPQ))**
Blog Guide Step by Step : **([Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-2))**

1. First **Create a repository** in Github : **([How To Create Repository](https://www.youtube.com/watch?v=u-_uGO95xco))**
2. Select the folder that you want to upload
3. Open Gitbash for that folder ( Right click on the folder and open git bash)
4. Now write the following Code in **Gitbash terminal**
    * ```git init```
    * ```git add .```
    * ```git commit -m "Commits Names"```
    * ```git branch -M main```
    * ```git remote add origin " Git Repository Link"```
    * ```git push -u origin main```
5. **Use this if the above code not works**
    * ```git push origin master --force```  

# Readme.md Tutorial

* Create readme.md file  
  * git add README.md
* (.md file) Learning tutorial ([Link](https://agea.github.io/tutorial.md/))
* (.md file) Easy Tutorial ([Link](https://www.markdownguide.org/basic-syntax/))
* Learn with practice test ([Link](https://www.markdowntutorial.com/))
* Rules of .md files ([Link](https://github.com/markdownlint/markdownlint/blob/master/docs/RULES.md))
* Create own profile README.md file
  * [Tutorial Link](https://www.youtube.com/watch?v=KhGWbt1dAKQ)
  * [Samples Readme Profiles](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
  * [Profile Generator 1](https://arturssmirnovs.github.io/github-profile-readme-generator/)
  * [Profile Generator 2](https://rahuldkjain.github.io/gh-profile-readme-generator/)
  * [Profile Generator 3](https://profile-readme-generator.com/)
  * [Profile Generator 4](https://gprm.itsvg.in/)

# Github Desktop Tutorial

* **Youtube Links**
  * [Basics , Create repositories and Branching](https://www.youtube.com/watch?v=RPagOAUx2SQ&list=PLcL8q_TiioW0JLk03hM3cu_Nb5DRwBHa1&index=2&t=107s)
  * [Draging , Clone and Advance](https://www.youtube.com/watch?v=GOY9wMyr7pU&list=PLcL8q_TiioW0JLk03hM3cu_Nb5DRwBHa1&index=2)

# Gith Branching

* **Youtube Links**
  * [What is Branching and How works](https://youtu.be/BcFoLD6acOM?t=114)
  * [Basic Branching](https://www.youtube.com/watch?v=QV0kVNvkMxc)
  * [Using VSCode Terminal](https://youtu.be/Lf3DYRvCPFo?t=79)
  * [Using Github Desktop](https://www.youtube.com/watch?v=FegJzEFXdk8&list=PLcL8q_TiioW0JLk03hM3cu_Nb5DRwBHa1&index=17)

# Github with VS Code

* [Youtube Link](https://www.youtube.com/watch?v=rmuAKOlWMjA&list=PLcL8q_TiioW0JLk03hM3cu_Nb5DRwBHa1&index=11)

# Github with Anroid studio

* [Upload a project](https://www.youtube.com/watch?v=GhfJTOu3_SE)
* [Everything tutorial](https://youtube.com/playlist?list=PLQkwcJG4YTCQTEk4J4btiOJBV0PhKjJVS)
  * How to upload
  * How to branch
  * How to clone or merge
  * Advance tips

# Pull request

* First Learn Branching ([Link](#gith-branching))
* What is pull request ([Link](https://www.youtube.com/watch?v=For9VtrQx58))
* How to pull request on another person repositories
  * [Using forking and pull request](https://www.youtube.com/watch?v=a_FLqX3vGR4)
  * [Branching and pull request](https://www.youtube.com/watch?v=inPYMFPdzRA)
* [Pull request on Own Branch](https://www.youtube.com/watch?v=inPYMFPdzRA)
* [Pull request on Open Source Projects](https://www.youtube.com/watch?v=8A4TsoXJOs8)

# Collaboration with Others

* [How to give permissions to other in your repository](https://www.youtube.com/watch?v=nS9QbJt4KaQ)

# Git Server Connection Error : Fixed

* Problem : **"Failed to connect to github.com port 443: Connection timed out"** when pushing to remote repository
* **Solution** :  Write the following command into GitBash
  * ```git config --global http.proxy```
  * ```git config --global --unset https.proxy```

# Clone a git repository and push a file to that repository

Blog Link Step By Step:  **([Click Here](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-13))**

1. Copy the url link of the git repository
2. Open Git Bash and run the following command
3. Clone the repository : `git clone "RepositoryLink"`
    * **Code - 1 :** `git clone https://github.com/link.git`
    * Want to clone into **Specific Path**
        * Code Format : `git clone "RepositoryLink" "Location Path"`
        * Example : `git clone https://github.com/link.git  ./Test`
        * Note : `git init` to that folder
        * Clone to current folder: `git clone https://github.com/example/example.git ./`
4. **Code - 2 :** `cd "Git Repository Name"`
5. **Code - 3 :** ```git remote -v```
6. (Folder Location) **Code - 4 :** ```pwd```
     * pwd = print working directory
7. Create a new file in that location(text.txt)
8. Now check the status of your untracked files
    * **Code - 5 :**`git status`
9. Add your new file to the local project
     * **Code - 6 :**`git add text.txt`
10. Commit the changes to the local project
    * **Code - 7 :**`git commit -m "Commit Name"`
11. Finally, push the changes to the remote GitHub repository
    * **Code - 8 :**`git push"`
