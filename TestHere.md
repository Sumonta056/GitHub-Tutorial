

### Tips - 24

<h2><span style="color:#97FFF4;font-weight:700;font-size:25px">
   ⚔️ How To Edit Pushed Git Commit Message?
</span></h2>

#### 🎥 Tutorial How To Edit Pushed Git Commit Message: **([👉Click Here](https://youtu.be/BNF4le5X1Ms?si=B4OqcrJ3Ojj5al_J))**

<hr>

#### ❤️‍🩹 Edit The ⭐ Last ⭐ Pushed Git Commit Message **([👉Tutorial](https://youtu.be/BNF4le5X1Ms?si=B4OqcrJ3Ojj5al_J) )**

1. **✍️ Open Git Terminal of Your Project**

```bash
git commit --amend
```

2. **✍️ New Window will open where in top you see the last commit message**

3. **✍️ Write the following commands**

```bash
Press ESC
```

4. **✍️ To Edit the Message** 

```bash
 Press I
```

5. **✍️ Now you can edit the Last Pushed Git Commit Message. After edit do this :**
```bash
Press ESC
```
```bash
Press SHIFT + Z + Z
```

6. **✍️ Now Push the Git Updated Commit Message**

```bash
git push -f
```

7. **🥳 Successfully Updated the Last Commit Message**

<hr>



#### 🍂 Edit The ⭐ Any ⭐ Pushed Git Commit Message **([👉Tutorial](https://youtu.be/BNF4le5X1Ms?si=B4OqcrJ3Ojj5al_J) )**

1. **✍️ Open Git Terminal of Your Project**

```bash
git rebase -i HEAD~5  
```
[Here 5 = How Many last commit you want to see]


2. **✍️ New Window will open where in top you see the all last commit message upto 5**

3. **✍️ Choose the desire commit Then**

```bash
Press ESC
```

4. **✍️ You will see "PICK" key word before your desire commit mesaage**
```bash
Press I
```

5. **✍️ Modify the "PICK" keyword to "Edit". After modifying do this :**
```bash
Press ESC
```
```bash
Press SHIFT + Z + Z
```

6. **✍️ Now write the following command**
```bash
git commit --amend
```
7. **✍️ To Edit The Last Selected Message** 

```bash
 Press I
```

8. **✍️ Now you can edit the selected Pushed Git Commit Message. After edit do this :**
```bash
Press ESC
```
```bash
Press SHIFT + Z + Z
```

9. **✍️ Now Push the Git Updated Commit Message**

```bash
git push -f
```

10. **✍️ Now write the following command**

```bash
git push origin HEAD:main 

git branch -M main
```
```bash
git rebase --continue
```

11. **✍️ Now do a final push**

```bash
git push -f
```

12. **🥳 Successfully Updated the Selected Commit Message**

[![E](Images/footer.png 'E')](#content-list)

