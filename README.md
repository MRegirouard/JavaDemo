# JavaDemo

Instructions on how to use GitHub with a java program.

### 1. Installing EGit - Git integration for Eclipse
1. Open Eclipse
2. Click on **Help > Install New Software...** in the top menu. A window should pop up.
3. Paste the following URL into the box that says "*type or select a site*": https://download.eclipse.org/egit/updates/
4. Check the box to install "*Git Integration for Eclipse*".
5. Click "*Next >*", and wait.
6. Click "*Next >*", then check the box "*I accept the terms of the license agreement*".
7. Click "*Finish*", then click "*Restart Now*" to restart Eclipse.

### 2. Downloading the Project
1. Open Eclipse
2. Click on **File > Import...** in the top menu. A window should pop up.
3. Drop down the folder "*Git*" and select "*Projects from Git*".
4. Click "*Next >*", and then select "*Clone URI*". Click "*Next >*" again.
5. Go to [GitHub](https://github.com) and find the respository you want to work on.
6. Click on the green "*Code*" button, and make sure "*HTTPS*" is selected.
7. Copy the URL manually or by pressing the clipboard icon.
8. Return to Eclipse, and paste the URL in the "*URI*" box.
9. The "*URI*" should look similar to this: https://github.com/MRegirouard/NationSimulation.git.
10. Enter your GitHub username and password in the appropriate fields, and check "Store in Secure Store*" to save them.
11. Press "*Next >*".
12. Ensure that "*main*" is selected, and click "*Next >*"
12. Beside the "*Directory*" field, click "*Browse*". Navigate to your Eclipse workspace folder, and press "*Save*".
13. Then press "*Next >*", and wait for the repository to download.
14. Ensure that "*Import existing Eclipse projects*" is selected, and then click "*Next >*".
15. Click "*Finish*". The repository should how be in your **Project Explorer** window.
16. You can now make changes to the code just like a normal Java Project.

### 3. Working on the Project
Now make your changes to the project. Try to edit only one file, and don't do too much before committing. Once you've made your change and the code runs, save your work, then see the section about committing below.


### 4. Committing Your Changes
1. Right-click on the project in the **Project Explorer** window. Then select **Team > Commit...** (Or just press *Ctrl-#*).
2. In the **Unstaged Changes** window, select the file you worked on, and click the single green plus at the top of **Unsaved Changes** window.
3. In the **Commit Message** box, write a very brief message about what you changed. Commit messages should be around 3 to 7 words.
4. Ensure that the "*Author:*" and "*Committer:*" fields have your name and email address.
5. Click "*Commit and Push*", then "*Close*".
