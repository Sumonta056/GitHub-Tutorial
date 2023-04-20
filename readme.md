
# Content

- [💻 Installation ](#💻-installation)
- [🧑‍💻 Setting up Git Environment ](#🧑‍💻-setting-up-git-environment)
- [⬆️ Upload a file or folder to Github ](#⬆️-upload-a-filefolder-to-github)
- [🤡 Clone a Git repository](#🤡-clone-a-git-repository-and-push-a-file-to-that-repository)
- [👊 Push a file to remote repository](#👊-push-any-files-to-the-remote-working-directory)
- [👨‍🔧Track or Unstage a file in local repository](#👨‍🔧-track-an-untracked-file)
- [🔀 Revert or Undo any commit](#🔀-revert-or-undo-any-commit)
- [🌳 Git Branching](#🌳-git-branching)

<hr>

# 💻 Installation 

* How to **Create GitHub Account** Step by Step (**[👉Tutorial Link](https://youtu.be/QUtk-Uuq9nE)**)
* Git (**[👉Download](https://git-scm.com/downloads)**)
* How to **install Git** Step by Step (**[👉Tutorial Link](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-1)**)
* GitHub Desktop (**[👉Download](https://desktop.github.com/)**)
* How to **install GitHub Desktop** Step by Step (**[👉Tutorial Link](https://www.youtube.com/watch?v=RPagOAUx2SQ)**)

<hr>

# 🧑‍💻 Setting up Git Environment

#### 🎥 Vedio Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=yDntCIs-IJM))**

1. Open Git Bash
2. Write The Following Commands

    * **Set Name** :  ``` git config --global user.name "Gihub User Name" ```
    * **Set Email** : ``` git config --global user.email "Github Email" ```
    * **Check status** :  ``` git config --list ```
3. Setting Done Successfully

<hr>

# ⬆️ Upload a file/folder to Github

##### 🎥 Vedio Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=eGaImwD8fPQ))**
##### ✍️ Blog Guide Step by Step : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-2))**

1. First **Create a repository** in Github : **([👉How To Create Repository : YouTube](https://www.youtube.com/watch?v=u-_uGO95xco))** **([👉Blog Link](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-5))**
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

# 🤡 Clone a git repository and push a file to that repository

####  ✍️ Blog Link Step By Step:  **([👉Click Here](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-13))**

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
#### 👊 Push any files to the remote working directory
8. Now check the status of your untracked files
    * **Code - 5 :**`git status`
9. Add your new file to the local project
     * **Code - 6 :**`git add text.txt`
10. Commit the changes to the local project
    * **Code - 7 :**`git commit -m "Commit Name"`
11. Finally, push the changes to the remote GitHub repository
    * **Code - 8 :**`git push"`
    * Force Push:`git push -f"`


<hr>

## 👨‍🔧 Track an untracked file
##### ✍️ Blog Link Step By Step:  **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-6))**

1. Create a new file to in any local git repository
2. Check the new file is tracked or untracked
    * **Code - 1 :**`git status`
3. If untracked , then allow to track or stage the file
    * **Code - 2 :**`git add "file name"`
4. Now GitHub is tracking the file

## ✈️ Unstage a tracked file

1. Run git status to select which file you want to unstage
    * **Code - 1 :**`git status`
2. **Code - 2 :**`git reset -- "file name"`
3. Unstaging file successfully

<hr>

# 🔀 Revert or Undo any Commit
##### ✍️ Blog Link Step By Step:  **([👉Click Here](https://phoenixnap.com/kb/git-revert-last-commit#ftoc-heading-1))**

1. Indetifying the  commit
     * **Code - 1 :**`git log`
2. Now copy the hash code of the commit want to revert
3. Write the following code
    * **Code - 2 :**`git checkout "Hash Code"`

<hr>

# 🌳 Git Branching

##### 🎥 Vedio Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=8x7QcF9LG7I))**
##### ✍️ Blog Guide Step by Step : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-10))**

##### 🆚 Branching Using VsCode : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-10))**

##### 💻 Branching Using GitHub Desktop : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-10))**

##### 🔛  Branching Using Git Bash👇

1. Check Current Branches
    * **Code - 1 :**`git branch`
2. **Create a new branch**
    * **Code - 2 :**`git branch New_Branch_Name`
3. **Switch to the new branch**
    * **Code - 3 :**`git checkout New_Branch_Name`
4. If you want to switch to a main branch
    * **Code - 4 :**`git checkout main`
5. Rename the branch you created 
    * First Switch to the branch want to rename
    * **Code - 5 :**`git branch -m new-name`
6. **Delete a branch**
    * **Local Branch** : `git branch -d branch_name`
    * **Another Way** : `git push origin --delete branch_name`
    * **Remote Branch** : `git push origin --delete branch_name`
7. Check Branch Status
    * **Code - 6 :**`git branch`

<hr>







