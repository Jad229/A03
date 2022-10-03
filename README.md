# How To Use Webstorm with Git and GitHub

    Before we learn how to interconnect these resources lets 
    first lay our foundation and environment.

#### Links
- [Webstorm Download](https://www.jetbrains.com/webstorm/promo/?source=google&medium=cpc&campaign=9641686290&term=webstorm&gclid=Cj0KCQjwkOqZBhDNARIsAACsbfJxUjVZIarlu73fO6oCyRQu8rADOV3G-Fr02rnLRr_T9_mEnOHU1nkaAv_LEALw_wcB)
- [Git Download](https://git-scm.com/downloads)
- [Github](https://github.com/)

# Directions on Using Webstorm

###### Step 1. Download Webstorm and Git from the above links
###### Step 2. Head over to Github and create an account.
###### Step 3. Create a repository on Github name it something simple I'll call it Demo for now
###### Step 4. When you open Webstorm click on the "Customize" tab and then click "All settings" and follow these steps:
    - In the settings window go to "Version Control"
    - Sign in to your github account in the "Github" tab
    - In the "Git" tab, if not already in there, paste the path to your git.exe download
    - Test the path for your git.exe, if it is correct the appropriate version will appear.
###### Step 5. Head back to the main page. Here you can do one of two things, start a fresh new project or in our case we will click "Get from VCS"
###### Step 6. In the new window you will look for the repository you created, in my case it was "Demo" and clone it to your local system.
###### Step 7. Now you have successfully cloned your Github repo onto your system. Lets add a new txt file and in it write "Hello World".
###### Step 8. You've made a change to your local repo! Webstorm will automatically add it to your staging area, so lets commit the change by pressing "Ctrl + K"
###### Step 9. In the commit window you will select your txt file to commit, and add a meaningful but short message as to what changes you made.
###### Step 10. Once you feel satisfied with your changes and message you can push these changes onto your remote repo on Github. Click Commit and Push, or you can Commit and Push later.
###### Step 11. CONGRATULATIONS! You've successfully used Webstorm and Git to work on your project head over to Github to see your changes live!

# Why Git and Github?
###### Git is a version control system that allows you to better your workflow.  What it provides is the ability to rewind to previously saved versions of your project. So you can test new features and functions without fully commiting a change to a previously function project.
###### Github on the other hand provides a remote place to hold your repos. This allows your project to be collaborated on and cloned on any system with access to Git/Github. If you want to work on your project on another system all you have to do is clone it from your Github Repo.
 

## Glossary

| Word           | Definition                                                                                                 |
|----------------|------------------------------------------------------------------------------------------------------------|
| Webstorm       | IDE used for developing web applications.                                                                  |
| Git            | Version control system.                                                                                    |
| Github         | Remote host for your online repositories, a<br/> form of version control using Git.                        |
| Branch         | To branch in Git means to branch off from <br/>the main trunk of development.                              |
| Clone          | To clone means to make a copy of an existing <br/>repository and add it to your computer.                  |
| Commit         | To commit means to create a save of your project in your repository.                                       |
| Fetch          | To fetch means to "fetch" any new changes done to a repository, but it will not alter your own work.       |
| Merge          | To merge means to join branches of development into one                                                    |
| Merge Conflict | A merge conflict means that Git cannot successfully join code together                                     |
| Push           | To push means to upload your "save", or commit, to a remote repository.                                    |
| Pull           | To pull means to "Fetch" any new changes done to a repository and actually integrate it with your project. |
| Remote         | A remote in git means where your repositories are being held on the internet, such as Github.              |
| Repository     | In simple terms, is a folder/directory that can track changes in your project.                             |






