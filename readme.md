
<h1> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40px" height="40px"> Learn Git and GitHub</h1>

<hr>

<h3><span style="color:#674747;font-weight:700;font-size:30px">
    👉 Click The Desire Content
</span></h3>

- **[💻 Installation ](#tips---1)**
- **[🧑‍💻 Setting up Git Environment ](#tips---2)**
- **[🔔 Git Commands List ](#tips---3)**
- **[⬆️ Upload a file or folder to Github ](#tips---4)**
- **[🤡 Clone a Git repository](#tips---5)**
- **[👊 Push a file to remote repository](#tips---6)**
- **[👨‍🔧Track or Unstage a file in local repository](#tips---7)**
- **[🔀 Revert or Undo any commit](#tips---8)**
- **[🌳 Git Branching](#tips---9)**
- **[🥷 Git Pull - Fetch - Merge](#tips---10)**
  - **[🌿 Update a branch from main branch ](#tips---11)**
  - **[🏠 Update a main branch in local repository](#tips---12)**
  - **[🤞 Git Pull vs Fetch-Merge](#tips---13)**
- **[🌚 Create a Pull Request](#tips---14)**
- **[🕸️ Hosting a website using GitHub Pages](#tips---15)**
- **[👑 How to write commit message like PRO](#tips---16)**
- **[✌️ Git Commit Message Type](#tips---17)**
- **[🥹 GitHub Related Problems and Solutions](#tips---18)**
   - **[⚠️ Git Server Connection Error : Fixed](#tips---18)**
   - **[⛑️ Restore a Deleted Depository](#tips---18)**
- **[🍕 How to make a Git Commit with a Past Date](#tips---19)**
- **[🤷‍♀️ What is Git-Ignore and How To Use It ! ](#tips---20)**



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

<h2><span style="color:#0B666A;font-weight:700;font-size:29px">
  🔔 Git Commands List
</span></h2>

| **Command** | **Description** |
| --- | --- |
| **👉 git init** | **✍️ Initialize a new repository** |
|              | `git init` |
| **👉 git clone** | **✍️ Clone a remote repository** |
|              | `git clone https://github.com/example/repo.git` |
| **👉 git add** | **✍️ Stage file changes** |
|              | `git add file.txt` |
|              | `git add .` |
| **👉 git commit** | **✍️ Commit changes with a descriptive message** |
|              | `git commit -m "Added new feature` |
| **👉 git status** | **✍️ Check repository status** |
|              | `git status` |
| **👉 git push** | **✍️ Push committed changes to a remote repository** |
|              | `git push origin main` |
| **👉 git pull** | **✍️ Fetch and merge changes from a remote repository** |
|              | `git pull origin main` |
| **👉 git branch** | **✍️ List of all branches** |
|              | `git branch` |
| **👉 git checkout** | **✍️ Switch to a different branch** |
|              | `git checkout new-feature` |
| **👉 git merge** | **✍️ Merge a branch into the current branch** |
|              | `git merge new-feature` |
| **👉 git log** | **✍️ View git commit history** |
|              | `git log` |
| **👉 git remote** | **✍️ Add remote repository** |
|              | `git remote add upstream https://github.com/upstream/repo.git` |
| **👉 git diff** | **✍️ Show differences between files** |
|              | `git diff file1.txt file2.txt` |
| **👉 git reset** | **✍️ Unstage a file** |
|              | `git reset file.txt` |

<hr>

### Tips - 4

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

### Tips - 5

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


### Tips - 6

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

### Tips - 7

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

### Tips - 8

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

### Tips - 9

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

### Tips - 10

<h2><span style="color:#5D9C59;font-weight:700;font-size:30px">
    🥷 Git Pull - Fetch - Merge
</span></h2>

<hr>

#### Tips - 11

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

#### Tips - 12

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

#### Tips - 13

<h4><span style="color:#DC3535;font-weight:700;font-size:30px">
    🤞 Git Pull vs Fetch-Merge
</span></h4>

##### 🎥 Video Tutorial : **([👉Click Here](https://www.youtube.com/watch?v=KmagW60Li-o))**

<hr>

### Tips - 14

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

### Tips - 15

<h2><span style="color:#576CBC;font-weight:700;font-size:30px">
  🕸️ Hosting a website using GitHub
</span></h2>

##### 1️⃣ What is github pages ? : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-18))**

##### 2️⃣ (Html - CSS - Javascript) Host a static website  : **([👉Click Here](https://www.youtube.com/watch?v=jRLGobWwA3Y))**


##### 3️⃣ (Only readme.md) Host a static website  : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-18))**


##### 4️⃣ (NPM Based) Host a react website  : **([👉Click Here](https://phoenixnap.com/kb/how-to-use-git#ftoc-heading-18))**
> 🍀 **Setup NPM & NodeJs** **([👉Click Here](https://www.youtube.com/watch?v=mIW_8dMQaUk))**


<hr>


### Tips - 16

<h2><span style="color:#F45050;font-weight:700;font-size:30px">
  👑 How to write commit message like PRO
</span></h2>

#### 🧐 Committing Ways

| **Basic Way** | **Advanced Way** |
| --- | --- |
| `git commit -m <message>` | `git commit -m <title> -m <description>` |

####  ✍️ 6 Steps to Write Better Commit Messages


##### 1️⃣ Capitalization & Punctuation
```Code
👉 Capitalize the first word and do not use in punctuation end
👉 Example :
    ❌❌ adding menu bar. 
    ✅✅ Adding menu bar  
```

##### 2️⃣ Show & Express Your Mood
```Code
👉 Use imperative mood in the subject line
👉 Example :
    ❌❌ dark mode toggle state 
    ✅✅ Add fix for dark mode toggle state  
```

##### 3️⃣ Specify The Type of Commit
```Code
👉 Use consistent set of words to describe your changes
👉 Example :
    ✅✅ Bugfix , Update , Refactor
```

##### 4️⃣ Think like a Journalist
```Code
👉 Be direct, try to eliminate filler words and phrases like (like : though, maybe, I think, kind of)
👉 Example :
    ❌❌ I added dark mode and maybe it has some issue 
    ✅✅ Add fix for dark mode toggle state  
```

##### 5️⃣ Add Emote Start of The Committ
```Code
👉 It creates a beautiful expression of the commit
👉 Example :
    ❌❌ Add fix for dark mode toggle state 
    ✅✅ ➕ Add fix for dark mode toggle state  
```

```Code
 ⚠️ NT : Since emojis use special ASCII codes (not commonly used and supported in the text-based interfaces like CLIs) and Unicode systems and most command-line interfaces need a third-party package or font to handle them, this convention might not look good to everyone. They might face some issues in terms of reading histories and checking the commit messages. (Like the emoji character in the message title might be rendered as its actual ASCII code or unknown question marks) 
```


##### 6️⃣ Convetional Keyword First
```Code
👉 Use a conventional Keyword first : Then explain the commit in detail
👉 Convetional Keywords like
    - feat , fix , chore
    - update , refactor , remove
    - docs , style 
    - test , build , revert
👉 Example :
    ❌❌ fixed bug on landing page 
    ✅✅ ➕ Fix: fix bug on landing page  
```

<hr>

### Tips - 17

<h2><span style="color:#A5402D;font-weight:700;font-size:27px">
  ✌️ Git Commit Message Type
</span></h2> 



#### 1️⃣ Introducing New Features : "feat"

```code 
    👉 Format : git commit -m "feat: message"
```
**✍️ When you add an existing new feature, use 'feat' commit type. It helps team members identify and track significant changes easily.**

<hr>

#### 2️⃣ Fixing Bugs: "fix"

```code 
    👉 Format : git commit -m "fix: message"
```
**✍️ Addressing a bug ? Utlize 'fix' commit type to highlight that the commit resolves an issue or a problem in the repository code base**

<hr>

#### 3️⃣ Miscellaneous Changes: "chore"

```code 
    👉 Format : git commit -m "chore: message"
```
**✍️ For non-feature/non-fix updates like updating dependencies or performing routine tasks, use 'chore' commit type**

<hr>

#### 4️⃣ Code Refactoring : "refactor"

```code 
    👉 Format : git commit -m "refactor: message"
```
**✍️ When you improve the structure or readability of the code without adding features or fixing bugs, use 'refactor' commit type**

<hr>

#### 5️⃣ Documentation Updates: "docs"

```code 
    👉 Format : git commit -m "docs: message"
```
**✍️ Updating project documentation? Whether it's the README or other relevant files , 'docs' commit type keeps the documentation up to date**

<hr>

#### 6️⃣ Code Formatting: "style"

```code 
    👉 Format : git commit -m "style: message"
```
**✍️ For changes that don't affect code behavior but enhance code style or formatting , use 'style' commit type**

<hr>

#### 7️⃣ Testing Updates: "test"

```code 
    👉 Format : git commit -m "test: message"
```
**✍️ When you add or modify tests to ensure code quality and reliability , use 'test' commit type to keep track testing effort**

<hr>

#### 8️⃣ Performance Improvements: "perf"

```code 
    👉 Format : git commit -m "perf: message"
```
**✍️ Did you optimize the code to boost performance? Use 'perf' commit type**

<hr>

#### 9️⃣ Continuous Integration: "ci"

```code 
    👉 Format : git commit -m "perf: message"
```
**✍️ Changes related to continuous integration, such as configuring pipelines or adjusting build process, should use the 'ci' commit type**

<hr>

#### 🔟 Build System Updates: "build"

```code 
    👉 Format : git commit -m "build: message"
```
**✍️ For changes impacting the build system or external dependencies such as package updates or build script modification , use 'build' commit type**

<hr>

#### 1️⃣1️⃣ Reverting Changes: "revert"

```code 
    👉 Format : git commit -m "revert: message"
```
**✍️ Mistakes happen! if you need to undo a previous commit , use 'revert commit type to roll back changes and restore the previous states**

<hr>

### Tips - 18

<h2><span style="color:#B8621B;font-weight:700;font-size:30px">
 🥹 GitHub Related Problems and Solutions 
</span></h2>

#####  1️⃣ Problem - 1 : Git Server Connection Error : Fixed
##### 🕵️ Description: *"Failed to connect to github.com port 443: Connection timed out"* when pushing to remote repository
* 👉 **Solution** :  Write the following command into GitBash
  - ```git config --global http.proxy```
  * ```git config --global --unset https.proxy```
<hr>

#####  2️⃣ Problem - 2 : Restore a Deleted Repository
##### 🕵️ Description: Mistakenly deleted an important repository
* 👉 **Solution** : Blog Link Step By Step **([👉Click Here](https://docs.github.com/en/repositories/creating-and-managing-repositories/restoring-a-deleted-repository))**

<hr>

### Tips - 19

<h2><span style="color:#4A55A2;font-weight:700;font-size:25px">
   🍕 How to make a Git Commit with a Past Date
</span></h2>

#### 🎥 Video Tutorial : **([👉Click Here](https://youtu.be/cSwgkUHk_Qo))**

##### 👇 Command Line 👇

1. Add all file from current repository
   - **Code - 1 :**`git add .`
2. Stage all files using commit command
   - **Code - 2 :**`git commit -m "Commit Message Type"`
3. **To commit with your desire date use the following command with Time**
   - **Code - 3 :**`git commit --amend --date="2023-07-07 20:12:20"`
4. Git Gui will take you to another page
5. Now juust **press Esc and type :wq** then press Enter
6. Now push the commit
   - **Code - 4** : `git push origin master`
7. **Successfully committed with a random date**

<hr>

### Tips - 20

<h2><span style="color:#DFA878;font-weight:700;font-size:25px">
   🤷‍♀️ What is Git-Ignore and How To Use It ! 
</span></h2>

#### ✍️ Blog Link Step By Step: **([👉Click Here](https://www.geeksforgeeks.org/what-is-git-ignore-and-how-to-use-it/?ref=lbp))**

#### 👇 What is git-ignore 👇
There are various types of files we might want the git to ignore before committing, for example, the files that are to do with our user settings or any utility setting, private files like passwords and API keys. These files are not of any use to anyone else and we do not want to clutter our git. We can do this with the help of “.gitignore”


.gitignore is an auto-generated file inside the project folder that ignores/prevents files to get committed to the local and remote repositories.
#### 👇 Command Line 👇

1. Create **.gitignore** File inside the project folder.
2. Assume I have files name
    - a.txt , b.txt , c.txt , text.txt
   
3. Write the name of the files you want to ignore in the .gitignore text file. Each file name should be written in a new line .
   - text.txt 
4. Initialize git in your terminal. Add these files to your git repository and commit all the changes with an appropriate message.
   - `git init`
   - `git add .`
   - `git commit - m "Testing Git Ignore"`
   - `git push`
5. Using **Git-Ignore** will not commit the file name text.txt further and commit the rest of files


#### 👇 Some common patterns and format for Git-Ignore 👇

- **Blank Line**: A blank line doesn’t refer to any file name, so we can use it to separate two file names for the ease of reading .

- **#**: A line beginning with the # symbol refers to a comment .However if # is used as a pattern then use backslash (“\”) before the # symbol so that it is not misunderstood as a comment.

- **/**: It is used as a directory separator i.e to include directories,  for example webdev/ .

- ***.extension_name**: For example *.txt and *.log can be used to match ALL the files that have .txt and .log as their extension respectively.

- ****/any_name**: It is used to match any file or directory with the name any_name.

- **any_name/****: It is used to match anything that is inside the directory of the name - any_name. for example webdev/** matches all the files inside webdev directory.

```code 

# Compiled class file                  // Comment
*.class                                // Ignore Extension Type

# Log file
*.log

# Mobile Tools for Java (J2ME)
.mtj.tmp/                              // Extension Directory Type      

# Package Files 
*.jar
```

<hr>