
# Content

- [Content](#content)
- [Installation](#installation)
- [Setting up Git Environment](#setting-up-git-environment)
- [Upload a file or folder to Github](#upload-a-filefolder-to-github)
- [Clone a Git repository](#clone-a-git-repository-and-push-a-file-to-that-repository)
- [Push a file to remote repository from cloned repository](#clone-a-git-repository-and-push-a-file-to-that-repository)

<hr>

# Installation

* How to **Create GitHub Account** Step by Step (**[Tutorial Link](https://youtu.be/QUtk-Uuq9nE)**)
* Git (**[Download](https://git-scm.com/downloads)**)
* How to **install Git** Step by Step (**[Tutorial Link](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-1)**)
* GitHub Desktop (**[Download](https://desktop.github.com/)**)

<hr>

# Setting up Git Environment

#### Vedio Tutorial : **([Click Here](https://www.youtube.com/watch?v=yDntCIs-IJM))**

1. Open Git Bash
2. Write The Following Commands

    * **Set Name** :  ``` git config --global user.name "Gihub User Name" ```
    * **Set Email** : ``` git config --global user.email "Github Email" ```
    * **Check status** :  ``` git config --list ```
3. Setting Done Successfully

<hr>

# Upload a file/folder to Github

##### Vedio Tutorial : **([Click Here](https://www.youtube.com/watch?v=eGaImwD8fPQ))**
##### Blog Guide Step by Step : **([Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-2))**

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

<hr>

# Clone a git repository and push a file to that repository

#### Blog Link Step By Step:  **([Click Here](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-13))**

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

<hr>
