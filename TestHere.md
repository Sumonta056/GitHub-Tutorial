
### Tips - 25

<h2><span style="color:#EB455F;font-weight:700;font-size:30px">
    ⬆️ How to Roll Back ( Git Reset vs Revert ) a Git Repository to a Particular Commit 
</span></h2>


#### ✍️ Blog Guide Step by Step Git Reset: **([👉Click Here](https://linuxhint.com/roll-back-reset-git-repository-to-particular-commit/) )**

#### 🎥 Video Tutorial Git Revert vs Reset: **([👉Click Here](https://www.youtube.com/watch?v=IWR24Z1yp80) )**


<hr>

#### ⛑️ Git reset and git revert are not the same.

Git reset will undo changes up to the state of the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the second commit.
Ggit revert will undo changes up to the state before the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the commit that comes before the second commit – the first commit.

The explanations above may seem confusing. The best way to understand it is to try it out yourself.

#### 🎡 When to Use git reset and git revert

You should use git reset when working on a local repository with changes yet to be pushed remotely. This is because running this command after pulling changes from the remote repo will alter the commit history of the project, leading to merge conflicts for everyone working on the project.

Git reset is a good option when you realize that the changes being made to a particular local branch should be somewhere else. You can reset and move to the desired branch without losing your file changes.

**Git revert is a good option for reverting changes pushed to a remote repository. Since this command creates a new commit, you can safely get rid of your mistakes without rearranging the commit history for everyone else.**

<hr>

### ⚠️ Reset Only Works for Local Commits

#### 🫁 How to Reset a Git Repository to a Specific Commit **([👉Tutorial](https://youtu.be/IWR24Z1yp80?t=213) )**

###### 👉 Step - 1 : View and Check Git Commit History

```bash
git log --oneline
```

###### 👉 Step - 2 : Choose a particular commit and its copy SHA-hash
![Alt text](image.png)

**We have selected the “Files added” commit, whose hash value is “9bd11a3”**

###### 👉 Step - 3 : Reset to Particular Commit : Run the “git reset –hard <commit-id>” command

```bash
git reset --hard 9bd11a3
```

###### 👉 Step - 4 : Next Do the following command things

```bash
git add .
git commit -m "Your Message"
git push origin main
```

###### 🍭 Step - 5 : Successfully Reset to Particular Commit


<hr>

### ⚠️ Revert Only Works for Public/Remote Commits
#### 😮‍💨 How to Revert a Git Repository to a Specific Commit **([👉Tutorial](https://youtu.be/IWR24Z1yp80?t=492) )**

###### 👉 Step - 1 : View and Check Git Commit History

```bash
git log --oneline
```

###### 👉 Step - 2 : Choose a particular commit and its copy SHA-hash
![Alt text](image.png)

**We have selected the “Files added” commit, whose hash value is “9bd11a3”**

###### 👉 Step - 3 : Revert to Particular Commit 

```bash
git revert 9bd11a3
```

###### 👉 Step - 4 : New Screen will come then type any of below code

```bash
Type "Esc"
Type "SHIFT + Z + Z"
```

```bash
Type ":wq"
```

###### 🍭 Step - 5 : Successfully Revert to Particular Commit


[![E](Images/footer.png 'E')](#content-list)
