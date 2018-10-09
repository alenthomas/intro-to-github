# intro-to-github
A repo to help people to get started with git and github

# Install  GIT

This is the link you to download git according to your operating system.
https://git-scm.com/downloads

Then you can use git bash/git gui or git desktop to configure git.

# Configure GIT

- Right click on desktop and then click 'git bash here'
- Then type these commands one by one to configure

  1) git config --global user.name "github username"
  2) git config --global user.emal "github email address"
  
  ** Username and Email must be inside double quotes
  
# Create Repositories

- These are the commands to make a new repository.If you are not in the mood to type commands,you can use the git gui to make repositor   simply by a click.

  1) git init <project-name>
  2) git clone <url>
  
  ** url - The URL of the project of you want to work in.This can be copied from the github project
  
# Making Changes

- After modifying the project files you need to right click inside the project folder and then click git bash here.
- Then type this command.
  1) git status  
  
- Next following command will show what are the changes happened after the last pull request
  2) git diff
  
- Then type this command to add the file you need to be pull
  3)git add <file name> or git add .
  ** "." will add all the changed files

- Next enter a commit message using following command
  4)git commit -m "Commit Message"
  ** commit message must be inside double quotes
  
- Finally use git push to make changes to your repository on GitHub

  5) git push

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
  
  
