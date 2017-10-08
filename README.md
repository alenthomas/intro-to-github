# intro-to-github
A repo to help people to get started with git and github

# How to Create a Pull Request


  - Click on the fork on the top to fork this repo.
  - Go to your repo where you fork the project.
  - Hit the clone button on your forked repo and copy the given link.
  - On your terminal / command prompt, type "git clone [put the link here]".
  - Change the index file in the folder.
  - Afterward, on your terminal / command prompt, type "git add index.html"; then 'git commit -m "[type a message]" '.
  - Push the commit. For example, type "git push origin master".
  - Go back to the original repo.
  - Hit "new pull request" and compare between forks.
  - Confirm the pull request and that's it!

  # There are some basic commands that are usually used, the command starts from the word "git":
  - git init : 
  	Initializes a git repository – creates the initial ‘.git’ directory in a new or in an existing project. Example: cd /home/user/my_new_git_folder/ git init
  - git status : 
	Shows you the status of files in the index versus the working directory. It will list out files that are untracked (only in your working directory), modified (tracked but not yet updated in your index), and staged (added to your index and ready for committing). Example: git status # On branch master # # Initial commit # # Untracked files: # (use "git add <file>..." to include in what will be committed) # # README nothing added to commit but untracked files present (use "git add" to track)
  - git push : 
	Pushes all the modified local objects to the remote repository and advances its branches. Example: git push origin master
  - git add : 
	Adds files changes in your working directory to your index. Example: git add 
  - git checkout : 
	Checks out a different branch – switches branches by updating the index, working tree, and HEAD to reflect the chosen branch. Example: git checkout newbranch
  - git diff : 
	Generates patch files or statistics of differences between paths or files in your git repository, or your index or your working directory. Example: git diff
  - git remote : 
	Shows all the remote versions of your repository. Example: git remote origin