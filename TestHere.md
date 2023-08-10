

### Tips - 21

<h2><span style="color:#7A316F;font-weight:700;font-size:25px">
   How To Add Video, Audio and GIFs Files directly in README.md File

</span></h2>

#### 🎥 Add Videos on README.md File: **([👉Click Here](https://www.geeksforgeeks.org/how-to-add-videos-on-readme-md-file-in-a-github-repository/?ref=lbp))**

#### 🎶 Add Audio on README.md File: **([👉Click Here](https://www.geeksforgeeks.org/how-to-add-audio-files-on-readme-md-file-in-a-github-repository-from-the-local-system/))**


#### 📸 Add Images on README.md File: **([👉Click Here](https://www.geeksforgeeks.org/how-to-add-images-on-readme-md-file-in-a-github-repository-from-the-local-system/))**


#### 💃 Add GIFs  on README.md File: **([👉Click Here](https://www.geeksforgeeks.org/how-to-add-gifs-on-readme-md-file-in-a-github-repository/))**
=======
### Tips - 19

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





<hr>