This document defines the workflow we would like to follow for the duration of this project. This will allow us to keep everything structured and organised along with ensuring the code that we develop is up to standard. All of the specific repositories and directories in this document are examples only.

Whenever you start a new ticket, please follow this format:

Open your ticket and create a branch in the relevant GitHub repository from the development branch. It will take you to a separate screen to do this after pressing Create branch in GitHub.


If you have not cloned your repository yet, please do so in the terminal (change the URL):


cd ~/Documents/GitHub/Enterprise-Pro
git clone https://github.com/Enterprise-Pro/Front-End.git
Now go into your repo directory and do a git pull to ensure you have the latest files/branches:


cd Front-End
git pull
As you are completing your task, make sure to commit your changes after a milestone has been reached. This is basically a checkpoint of your code. To do this, you need to add files to your staging area (this is files ready to be committed). You can do this by typing any of the following in your terminal:


git add * //This is to add all files that have changed/been edited
git add FILE //This is to add a specific file to the staging area, where FILE is the file
Once you have added your modified files to the staging area, you can commit these changes:


git commit -m "EP-<ticket-number>  This is a short comment about this commit"
//Make sure that your message starts with "EP-" and then your ticket number, e.g EP-15
After a commit, it is good practice to push the changes from your local repo to the remote repo (GitHub). You can do this by doing the following:


git push
Once you are happy with your task and have completed it, you can create a pull request on GitHub. Please add a comment to your Jira ticket about your progress of the task. You can assign a specific person to look at this pull request if you would like. Please do not merge the branch as this should be done by another member of the team for peer review.

Whenever a pull request is created, everyone should receive an email from Jira to notify about it. Any updates to the repositories will also be in the discord #github-updates channel. This is to allow us to review the pull request and either test functionality and/or code. Anybody can do this, but it is to ensure that we are pushing correct, working code to our development branch. 
