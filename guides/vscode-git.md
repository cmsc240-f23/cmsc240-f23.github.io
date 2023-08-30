---
layout: default
permalink: /guides/vscode-git
title: Setting up VS Code
---

# Using VSCode with Git and SSH to Complete/Submit a programming Assignment

> Before starting, you should have completed the [VScode Setup Guide with SSH](vscode-ssh). This guide assume you have VScode and SSH capabilities installed, as well as the VSCode extension Remote Development Extension. 


1. Accept the GitHub classroom assignment and follow the link to the repository. For example, if you are working on Lab 1, after accepting the assignment, you'll have a new repository named `lab-1-username` where `username` is your GitHub username. 

2. Copy the repository link by clicking the `Code` label

   ![Github Repo Link](/images/module1-git.png)

   You should have setup an ssh key, use ssh.
   
   To setup an ssh key, see this [guide](vscode-ssh.md)

3. In a VSCode window where you have connected remotely to a Linux machine, cs01-cs06 (refer to this [guide](vscode-ssh.md)). Click the `Source Control` icon on the left hand side. Then click the explorer and then `Clone Repository`

   ![VScode New Window, Explore, Clone Repository](/images/Clone-Repo.png) 


   
4. Enter the repo link in the command pallet. 

   ![Enter repo link](/images/Clone-Repo2.png)


5. Choose a folder where you want to clone the repository.
   ![Confirm Location](/images/Clone-Repo3.png)
   


6. You will be prompted where to save the repo. Save it wherever you want, but I like to create a folder called `repos` or `cs240` to save my projects. 

7. Go ahead and open the repo in this window by selecting `Open`

   ![Open in this window](/images/Clone-Repo-Open.png)

8. Click Yes, I trust the authors to continue.

   ![Init Complete](/images/Clone-Repo-Trust-Authors.png)


9. Once complete, you'll have your workspace ready to go.

   ![Init Complete](/images/Clone-Repo-Working.png)

10.  Do your work. **Save your changes.** And once done, you need to commit your work. Start by clicking on the repo symbol.

   ![Repo symbol](/images/VSCodeGitRepoSymbol.png)

11.  Add the modified files (or new files) to be staged for commit by pressing the `+` next to the files you want to add.

   ![add files to the commit](/images/VSCodeGitChanges.png)

   The files are now staged.

   ![add files to the commit](/images/VSCodeGitStagedChanges.png)

12. Type a message in the text area above the `Commit` button. Click the &#10003;`Commit` button to perform the commit.

   ![add files to the commit](/images/VSCodeGitCommitMessage.png)


13. Finally, push your changes to github by clicking the `Sync` button.

   ![Push changes](/images/VSCodeGitSync.png)

14. Finally, finally, you should go back to GitHub as a final check to make sure you pushed all your changes.

   ![Push changes](/images/VSCodeGitGitHub.png)

## Using the git command line in the integrated terminal

You can also use the command line to do the git commands. 


```
git add file.txt        #add a file to the commit
git commit -m "message" #perform the commit with the commit message
git push                #push the commit to github 
```

If you want to add all the files that have been modified and commit all at once, use the following

```
git commit -a -m "message" 
```


## Asking you to set up your git profile?

If you're getting a error saying you need to setup your name and email, then open the integrated terminal and type these two commands


   ```
   git config --global user.name "JohnDoe"
   git config --global user.email johndoe@example.com
   ```
   
Where `JohnDoe` is replaced with your name and `johndoe@example.com` is replaced with the email address you used to sign up to github
