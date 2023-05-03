
<h1> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40px" height="40px"> Learn Git and GitHub</h1>

<hr>

<h5><span style="color:#674747;font-weight:700;font-size:30px">
    👉 Click The Desire Content
</span></h5>

- **[💻 Installation ](#tips---1)**
- **[🧑‍💻 Setting up Git Environment ](#tips---2)**
- **[⬆️ Upload a file or folder to Github ](#tips---3)**
- **[🤡 Clone a Git repository](#tips---4)**
- **[👊 Push a file to remote repository](#tips---5)**
- **[👨‍🔧Track or Unstage a file in local repository](#tips---6)**
- **[🔀 Revert or Undo any commit](#tips---7)**
- **[🌳 Git Branching](#tips---8)**
- **[🥷 Git Pull - Fetch - Merge](#tips---9)**

  - **[🌿 Update a branch from main branch ](#tips---10)**
  - **[🏠 Update a main branch in local repository](#tips---11)**
  - **[🤞 Git Pull vs Fetch-Merge](#tips---12)**

- **[🌚 Create a Pull Request](#tips---13)**



<hr>

### Tips - 1

<h2><span style="color:green;font-weight:700;font-size:30px">
    💻 Installation
</span></h2>

- How to **Create GitHub Account** Step by Step (**[👉Tutorial Link](https://youtu.be/QUtk-Uuq9nE)**)
- Git (**[👉Download](https://git-scm.com/downloads)**)
- How to **install Git** Step by Step (**[👉Tutorial Link](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-1)**)
- GitHub Desktop (**[👉Download](https://desktop.github.com/)**)
- How to **install GitHub Desktop** Step by Step (**[👉Tutorial Link](https://www.youtube.com/watch?v=RPagOAUx2SQ)**)

<hr>

### Tips - 2

<h2><span style="color:#541690;font-weight:700;font-size:30px">
    🧑‍💻 Setting up Git Environment
</span></h2>

#### 🎥 Video Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=yDntCIs-IJM))**

1. Open Git Bash
2. Write The Following Commands

   - **Set Name** : `git config --global user.name "Gihub User Name"`
   - **Set Email** : `git config --global user.email "Github Email"`
   - **Check status** : `git config --list`

3. Setting Done Successfully

<hr>

### Tips - 3

<h2><span style="color:#EB455F;font-weight:700;font-size:30px">
    ⬆️ Upload a file/folder to Github
</span></h2>

##### 🎥 Video Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=eGaImwD8fPQ))**

##### ✍️ Blog Guide Step by Step : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-2))**

1. First **Create a repository** in Github : **([👉How To Create Repository : YouTube](https://www.youtube.com/watch?v=u-_uGO95xco))** **([👉Blog Link](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-5))**
2. Select the folder that you want to upload
3. Open Gitbash for that folder ( Right click on the folder and open git bash)
4. Now write the following Code in **Gitbash terminal**
5. Initialize it with git-specific functions : `git init`
6. Git isn't aware of these file, stage it : `git add .`
7. Take a snapshot of the staging area : `git commit -m "Commits Names"`
8. Select the master branch : `git branch -M main`
9. Provide the path for the repository you created on github : `git remote add origin " Git Repository Link"`
10. Push changes to github : `git push -u origin main`
11. **Use any of this if the above code not works**
    - `git push origin master --force`
    - `git push --set-upstream origin main`
<hr>

### Tips - 4

<h2><span style="color:#5D9C59;font-weight:700;font-size:30px">
    🤡 Clone a git repository and push a file to that repository
</span></h2>

#### ✍️ Blog Link Step By Step: **([👉Click Here](https://phoenixnap.com/kb/how-to-install-git-windows#ftoc-heading-13))**

1. Copy the url link of the git repository
2. Open Git Bash and run the following command
3. Clone the repository : `git clone "RepositoryLink"`
   - **Code - 1 :** `git clone https://github.com/link.git`
   - Want to clone into **Specific Path**
     - Code Format : `git clone "RepositoryLink" "Location Path"`
     - Example : `git clone https://github.com/link.git  ./Test`
     - Note : `git init` to that folder
     - Clone to current folder: `git clone https://github.com/example/example.git ./`
4. **Code - 2 :** `cd "Git Repository Name"`
5. **Code - 3 :** `git remote -v`
6. (Folder Location) **Code - 4 :** `pwd`
   - pwd = print working directory
7. Create a new file in that location(text.txt)


### Tips - 5

<h4><span style="color:#647E68;font-weight:700;font-size:30px">
    👊 Push any files to the remote working directory
</span></h4>

8. Now check the status of your untracked files
   - **Code - 5 :**`git status`
9. Add your new file to the local project
   - **Code - 6 :**`git add text.txt`
10. Commit the changes to the local project
    - **Code - 7 :**`git commit -m "Commit Name"`
11. Finally, push the changes to the remote GitHub repository
    - **Code - 8 :**`git push"`
    - Force Push:`git push -f"`

<hr>

### Tips - 6

<h4><span style="color:#F45050;font-weight:700;font-size:30px">
    👨‍🔧 Track an untracked file
</span></h4>

##### ✍️ Blog Link Step By Step: **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-6))**

1. Create a new file to in any local git repository
2. Check the new file is tracked or untracked
   - **Code - 1 :**`git status`
3. If untracked , then allow to track or stage the file
   - **Code - 2 :**`git add "file name"`
4. Now GitHub is tracking the file

<h4><span style="color:#89375F;font-weight:700;font-size:30px">
   ✈️ Unstage a tracked file
</span></h4>

1. Run git status to select which file you want to unstage
   - **Code - 1 :**`git status`
2. **Code - 2 :**`git reset -- "file name"`
3. Unstaging file successfully

<hr>

### Tips - 7

<h2><span style="color:#7149C6;font-weight:700;font-size:30px">
    🔀 Revert or Undo any Commit
</span></h2>

##### ✍️ Blog Link Step By Step: **([👉Click Here](https://phoenixnap.com/kb/git-revert-last-commit#ftoc-heading-1))**

1. Indetifying the commit
   - **Code - 1 :**`git log`
2. Now copy the hash code of the commit want to revert
3. Write the following code
   - **Code - 2 :**`git checkout "Hash Code"`

<hr>

### Tips - 8

<h2><span style="color:#5D9C59;font-weight:700;font-size:30px">
    🌳 Git Branching
</span></h2>

##### 🎥 Video Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=8x7QcF9LG7I))**

##### ✍️ Blog Guide Step by Step : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-10))**

##### 🆚 Branching Using VsCode : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-10))**

##### 💻 Branching Using GitHub Desktop : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-10))**

> ##### 🔛 Branching Using Git Bash👇

1. Check Current Branches
   - **Code - 1 :**`git branch`
2. **Create a new branch**
   - **Code - 2 :**`git branch New_Branch_Name`
3. **Switch to the new branch**
   - **Code - 3 :**`git checkout New_Branch_Name`
4. If you want to switch to a main branch
   - **Code - 4 :**`git checkout main`
5. Rename the branch you created
   - First Switch to the branch want to rename
   - **Code - 5 :**`git branch -m new-name`
6. **Delete a branch**
   - **Local Branch** : `git branch -d branch_name`
   - **Another Way** : `git push origin --delete branch_name`
   - **Remote Branch** : `git push origin --delete branch_name`
7. Check Branch Status
   - **Code - 6 :**`git branch`

<hr>

### Tips - 9

<h2><span style="color:#5D9C59;font-weight:700;font-size:30px">
    🥷 Git Pull - Fetch - Merge
</span></h2>

<hr>

#### Tips - 10

<h4><span style="color:#E96479;font-weight:700;font-size:30px">
    🌿 Update a branch from main branch
</span></h4>

##### ✍️ Blog Link Step By Step: **([👉Click Here](https://stackoverflow.com/questions/20101994/how-to-git-pull-from-master-into-the-development-branch))**

#### 1️⃣ Way - 1 (Fetch-Merge)

1. Check Branch
   - **Code - 1 :**`git branch`
2. Choose the brance you want to update from main branch
   - **Code - 2 :**`git checkout Branch_Name`
3. Fetch Orgin or Maser Branch
   - **Code - 3 :**`git fetch origin`
4. Merge Orgin or Maser Branch into current branch
   - **Code - 4 :**`git merge origin`

#### 2️⃣ Way - 2 (Pull)

1. Check Branch
   - **Code - 1 :**`git branch`
2. Choose the brance you want to update from main branch
   - **Code - 2 :**`git checkout Branch_Name`
3. Pull from master branch
   - **Code - 3 :**`git pull origin master`

<hr>

#### Tips - 11

<h4><span style="color:#6F1AB6;font-weight:700;font-size:30px">
    🏠 Update a main branch in local repository
</span></h4>

##### ✍️ Blog Link Step By Step: **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-18))**

#### 1️⃣ Way - 1 (Fetch-Merge)

1. Check Branch
   - **Code - 1 :**`git branch`
2. Choose the main brance
   - **Code - 2 :**`git checkout main`
3. Fetch Orgin or Maser Branch
   - **Code - 3 :**`git fetch `
4. Merge Orgin or Maser Branch
   - **Code - 4 :**`git merge`

#### 2️⃣ Way - 2 (Pull)

1. Check Branch
   - **Code - 1 :**`git branch`
2. Choose the brance main branch
   - **Code - 2 :**`git checkout Branch_Name`
3. Pull from master branch
   - **Code - 3 :**`git pull`
   - **Force Pull :**`git pull origin master`

<hr>

#### Tips - 12

<h4><span style="color:#DC3535;font-weight:700;font-size:30px">
    🤞 Git Pull vs Fetch-Merge
</span></h4>

##### 🎥 Video Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=KmagW60Li-o))**

<hr>

### Tips - 13

<h2><span style="color:green;font-weight:700;font-size:30px">
    ⚓ Create a Pull Request
</span></h2>

> #### ✍️ Blog Link Step By Step: **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-18))**

> #### 🎥 Video Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=jRLGobWwA3Y))**

1. Create a any file in  local repository
2. Switch to another or new brance from main branch
   - **Code - 1 :**`git checkout -b newbranch`
3. Check Branch
   - **Code - 2 :**`git branch`
4. Check files commit status
   - **Code - 3 :**`git status`
5. Stage untracked files
   - **Code - 4 :**`git add .`
6. Commit the untracked files
   - **Code - 5 :**`git commit -m "commit name"`
7. Push to remote repository with new branch
   - **Code - 6 :**`git push origin newbranch`
8. Now do the following Steps **[👉Click Here](https://www.youtube.com/watch?v=jRLGobWwA3Y)**


<hr>


