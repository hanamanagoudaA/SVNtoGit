The github enterprise URL for our team is   https://github.optum.com/OptumRx-MST-IVR.   You log in with your MSID credentials, for which you will need Secure access to the **github_users** group.   Here is a link on how to request Secure access to Github Enterprise:   https://hubconnect.uhg.com/docs/DOC-90949.   
 
You will want to install this Windows software from appstore:
* Git 2.11.0.3
* GitHub Desktop 1.0.8 

**VERY IMPORTANT:** After installing git and *before cloning any repositories,* open git bash and run this command. You only have to do this once. If you do not do this, when cloning the repository you will see lots of errors as git will try to modify the end-of-line markers on many files and create a very large mess for you to fix. Here is the command:<br/>
**git config --global core.autocrlf false**
 
Here are some Optum training materials:
* Github hubconnect: https://hubconnect.uhg.com/groups/github
* Training materials on hubconnect, mostly short videos:  https://hubconnect.uhg.com/docs/DOC-113608
* Training material on Learnsource:  There are 2-hour self-learning classes available on Beginner Git and Advanced Git.
* How to configure the Github Desktop app:   https://hubconnect.uhg.com/docs/DOC-120499
 
Here are some useful external links that explain the gitflow workflow which we will be using.  You can ignore discussion of installing git-flow extensions, because the extensions are already installed in the git software from the appstore.
* [Gitflow Workflow Tutorial from Atlassian](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
* [Gitflow blog from Axosoft](https://blog.axosoft.com/gitflow/)
