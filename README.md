# What is Git ?
Git is a open source version control system. The management of change of documents, computer program, large web page etc.

# Terms To Know
1. Directory --- Folder
2. Terminal or Command Line -> Interface for Text Commands
3. CLI-> Command Line Interface
4. cd -> Change Directory
5. Code Editor -> Word Processor for Writing Code
6. Repository -> Project, or the folder/place where your project is kept
7. Github -> A website to host your repositories online

# Command(all command are in lower case)
1.  git clone url -> Bring a repository that is hosted somewhere like Github into a folder on your local machine (Copy url from github )
2.  cd <name of the folder> -> To change the directory of the folder
3.  cd..  -> To comeback the directory
4.  ls -la ->command mean list all . To see if you are in git repository (look for hidden .git folder) type the command in git bash if not work on vs code terminal
5.  git status -> Show all the file which are updated, Created or Deleted
6.  git add file_name  -> Track your files and changes in Git
7.  git add . -> To take all the file (.)period is use
8.  git commit -m "Add Message" -m "Add desciption" -> Save your files in Git
9.  git config --global user.name "Username"
    git config --global user.email "Email"    -> run this command before Pushing the remote repo to github so that it would config. globel is used for all the remote repo
10. git push -> Upload Git commits to a remote repo, like Github
11. git push origin master -> push to master branch
12. git init -> To create and Initialized git repository
    To push the local repo to remote repo 1. create a empty repo of same name  2. copy https ssh 3. run command git remote add origin http_link
13. git remote -v  -> to see any remote repo connected to local repo
14. git pull -> Download changes from remote repo to your local machine, the opposite of push
15. git reset file_name or git reset -> To uncommit the file
16. git reset HEAD~1 -> uncommit the last commit one further
17. git log -> to see all your commit  
      Every commit have a id to directly undo that commit use 
18. git reset commit_ID
19. git reset --hard commit_ID -> to completly remove the commit


# Branching command  
Use Git Bash for Branching
1. git branch  -> To check number of branch 
2. git checkout branch_name -> To switch between branches
3. git checkout -b brench_name -> to create new branch 
4. git merge branch_name -> to merge two branch
5. git diff branch_name -> to see the different in two branches code
