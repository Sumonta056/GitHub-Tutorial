### Tips - 2

<h2><span style="color:#B8621B;font-weight:700;font-size:30px">
 🥲 GitHub Related Problems and Solutions
</span></h2>

####  1️⃣ Problem - 1 : Git Server Connection Error : Fixed
##### 🕵️ Description: *"Failed to connect to github.com port 443: Connection timed out"* when pushing to remote repository
* **Solution** :  Write the following command into GitBash
  * ```git config --global http.proxy```
  * ```git config --global --unset https.proxy```

<hr>