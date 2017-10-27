# GitHub Tutorial

_by Jakeline Hernandez_

---
## Git vs. GitHub
 **GitHub:** is usually used to store code that you are pushing up to the cloud. In github you are allowed to fork and clone and collaborate on others projects.Using github does require you to use git.
 
 **Git:** Git is used to store any snapshots of code that you want to use. Git does not require you to use github. You can also create a directory/file, what this does is it creates a repository where you can add any files.
 
   

---
## Initial Setup
**_Making a github account:_** To start making a github account you have to go to...
                  
1. [_Github.com_](https://github.com/) and press on the sign up button you will enter your information and  create a new profile
2. After you have created your profile you'll go to the top right corner and click on your profile picture and then click on settings, After go into the SSH and GPG KEYS tab on the left side and make sure that you are on SSH. you'll press on **_new SSH key_** and place "title" as **cloud9**

[![Screen_Shot_2017-10-25_at_9.14.03_AM.png](https://s1.postimg.org/2fzea8t2r3/Screen_Shot_2017-10-25_at_9.14.03_AM.png)](https://postimg.org/image/4pietqdt7v/)     [![Screen_Shot_2017-10-25_at_9.14.16_AM.png](https://s1.postimg.org/1witkmt2nj/Screen_Shot_2017-10-25_at_9.14.16_AM.png)](https://postimg.org/image/9hgqotzvsb/)
3. Once you are done with creating a tile you will go to your cloud9 acccount and click on the setting in the top right corner and go to **SSH Keys** and you will copy the _2nd keys(private git repository)_ and paste it in _keys_ in your github (i blurred my SSH key out but when you do yours you will have alot of code in it.) 
4. [![Screen_Shot_2017-10-25_at_9.27.42_AM.png](https://s1.postimg.org/1qvx7ospov/Screen_Shot_2017-10-25_at_9.27.42_AM.png)](https://postimg.org/image/1g93ejdhjf/) [![Screen_Shot_2017-10-25_at_9.31.38_AM.png](https://s1.postimg.org/6hqoyg1mxb/Screen_Shot_2017-10-25_at_9.31.38_AM.png)](https://postimg.org/image/3qhmqdfivf/)
Add your ssh that you copied from cloud9 onto your github account and paste it in your _Key_ and press submit.
[![Screen_Shot_2017-10-25_at_9.36.20_AM.png](https://s1.postimg.org/2len0a0mnz/Screen_Shot_2017-10-25_at_9.36.20_AM.png)](https://postimg.org/image/1bbptyincr/)

4. Press **Add SSH key** and you have created the ssh keys.

* **Overview**
  
---
## Repository Setup
To start a repository you have to log into c9 and create a new file.
 * you have to click on file and click(create file) and name it.
 * then go to you workspace below and on the command line start by opening the file by typing (mkdir your file name)
 * then you have to CD into the file so you can make any edits (When you CD into a file you are opening up the file)
 * after you have created a file you have to write anything you want inside of the file and then you have to add, commit, and push 

    *_ add --all_
    *git commit -m "insert message"
    *git push
now your file would be in your github account by going to your _Profile_ and then to your repositories and the file will be there.
    

---
## Workflow & Commands
**_Git Status:_** in order to check where you are and where your code is you have to type_git status_ this will help you know what you have already done(like any chnages) but _git status_ will not tell you if you have a mistake or if you did something wrong it will also not coreect anything that you did incorrectly so in order to check you would have to revise and check your code again.

**_Add:_** when you are adding in cloud9 you arre adding any file that may go into a folder. _Git add file_ will add the files to the stage to be comitted(git commit) and _Git add_ will add all the current directory that has changes in them. **_Git add --all:_** by using this line of code you will include all changes and deleted files.

**Git add remote origin:** This will allow you to set a connection with your current repository and your external one (that lives on github) _Origin_ is the nickname for the remote repository. There are multiple remotes

**(Git Commit-m") :** by using this line of code you will take a snapshot of the file on the stage, the message will let you know what is going on in the code, it should also be present tense so that you know if you made anychanges recently to your code.

**_Git Push:_** In Git Push you are sending your commits from your local repository to your remote repository which means to upstream it tells git to remember which remote to push our changes when we type git push to our master.   

**git pull** bring any chances from your remote repository to your local repository
[![Screen_Shot_2017-10-25_at_11.11.19_AM.png](https://s1.postimg.org/57rq6yfvb3/Screen_Shot_2017-10-25_at_11.11.19_AM.png)](https://postimg.org/image/5wkzqz3ebf/)

---
## Rolling Back Changes

**Undo Edit** in order to go back up one level you have to type _cd .._  
**Git Checkout -- file** this line of code is to discard lines of code 
[![Screen_Shot_2017-10-25_at_11.14.02_AM.png](https://s1.postimg.org/51s2fv72xb/Screen_Shot_2017-10-25_at_11.14.02_AM.png)](https://postimg.org/image/10g31h2zkb/)
 
   