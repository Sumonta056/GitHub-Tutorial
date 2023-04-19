
# Content

1. [Installing Git & GitHub Desktop](#installation)
2. [Setting up Git Environment](#setting-up-git-environment)
3. [Upload a folder in Github](#upload-a-filefolder-to-github)
4. [Readme.md Tutorial and Own Readme.md Profiles](#readmemd-tutorial)
5. [Github Desktop Tutorial](#github-desktop-tutorial)
6. [Git Branching](#gith-branching)
7. [Github Pull Request](#pull-request)
8. [Github with Vs Code](#github-with-vs-code)
9. [Github with Anroid Studio](#github-with-anroid-studio)
10. [Collaboration with Others](#collaboration-with-others)
11. [Complete Bangla Tutorial](#bangla-complete-github-course)

# Installation

* Git (**[Download](https://git-scm.com/downloads)**)
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

1. First **Create a repository** in Github : **([How To Create Repository](https://www.youtube.com/watch?v=u-_uGO95xco))**
2. Select the folder that you want to upload
3. Open Gitbash for that folder ( Right click on the folder and open git bash)
4. Now write the following Code in **Gitbash terminal**
     ```git init```
     ```git add .```
     ```git commit -m "Commits Names"```
     ```git branch -M main```
     ```git remote add origin " Git Repository Link"```
     ```git push -u origin main```
5. **Use this if the above code not works**
    ```git push origin master --force```  

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

# Bangla Complete Github Course

* **[Link](https://www.youtube.com/watch?v=8A4TsoXJOs8)**

# GitHub Server Connection Error
### Failed to connect to github.com port 443: Connection timed out" when pushing to remote repository
-  git config --global http.proxy
- git config --global --unset https.proxy
