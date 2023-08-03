
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