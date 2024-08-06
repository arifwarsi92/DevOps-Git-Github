##### What is Git:-
Git is a Distributed Version Control System. Git is a Tool That Helps Multiple People Can Work on Same Project on Same time.They Can Track and Manage Changes in the Files.

##### What is VCS(Version Control System):-
VCS is a tool that keep record the changes we are doing in the files like adding a line of code, removing code. Editing a documents, In that case VCS will keep record of  all the changes and the person who is changing .
In the VCS we can revert back to our old version if we face any issue in our current version.
##### Benifits:-
1.Back-Up & Recovery:- Files are safe from accidental loss.<br>
2-Collaboration:-Multiple people can work on same project.<br>
3.Tracking Changes:- You can check specific changes and by whom.
##### Installation:-
1. Go to the official website 'https://git-scm.com/'.<br>
2. Click on "Downloads" and select "Windows" to download the Git installer.<br>
3. Click on the Installer and double click<br>
4. Follow the Set-up Wizard.<br>
   .Click "Next" on the initial screen.<br>
   .Choose the installation directory or leave the default path.<br>
   .Select components to install (the default settings are usually fine).<br>
   .Choose the default editor used by Git (e.g., Vim, Nano, or Visual Studio Code).<br>
5.To check if git is installed type git --version in your terminal.It will show you the current version of git.<br>
6.I downloaded the VS code editer.<br>
#### Git Configuration:-
Git uses your name and your email-id to identify who make changes.So first Configure your username and email id.<br>
###### Open your Visual Studio Code and Create a folder named Git Repo or xyz and then click create and once you open it will ask permission click yes. #####
##### In this step you simply do right click on the folder you created and select "open in intigrated terminal". ##### 
###### Configure User name & user email. ######
1.To Initialize a Repository.<br>
   ###### git init #######
2.To set your user name.Type this command.<br>
   git config --global user.name "xyz".<br>
3. To set your email.Type this command.<br>
   git config --global user.email "xyz@gmail.com"
#### Git Commands:- ####
1.Git add- Git add file_name (This command adds a file to the staging area) <br>
2.Git Commit- Git commit command record all the changes made into repository. Creating permanent record in repository 
  history (git commit -m "type msg") <br>
3.Git log- Shows the commit history of the current branch and it will show the person who did that commit and time a well 
  (git log) <br>
4.Git diff- This command is used to see differences between two files once we committed. Before and after comparison (git 
   diff) <br>
5.Git show- This command is used to see previous file or some specific file (git show id:file_name) <br>
6.Git Checkout- This command basically check some old specific file (git checkout id:file_name) <br>
7.Git restore-This command use to restore the previous file which has already been committed(git restore --staged file_name) <br>
8.Git reset- This command is use to go on step back or we can say it will get the previous file (git reset --hard HEAD^) <br>
9.Git log -p -2- This command will check last two commit.<br>
10.Git log --state - Summary of changes. <br>
11.Git log --pretty=oneline -This command will show the log in one line<br>
12.Git log --pretty=format:"%h - %an , %ar:%s". <br>
13.Git Pull-This command fetches and merges changes on the remote server to your working directory (git pull link).<br>
14.Git Push-This command sends the committed changes of master branch to your remote repository (git push variable_name).<br>
15. Git Clone-This command is use to clone current repository from a remote repo to your local machine. <br>
### Git Branching & Merging ###
1.Creates a new branch with the specified name.<br>
git branch branch_name <br>
2.Switches to the specified branch.<br>
git checkout branch_name<br>
3.Creates a new branch and switches to it.<br>
git checkout -b branch_name<br>
4.Merges the specified branch into the current branch.<br>
git merge branch-name<br>
5.Deletes the specified local branch.<br>
git branch -d branch-name<br>
6.Deletes a remote branch.<br>
git push origin --delete branch-name




















 
