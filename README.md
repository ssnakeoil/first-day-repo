# hElLo WoRlD

My first repository on GitHub

 I love 📚 and ☕.

# Notes on initial creation:
- advised to set .gitignore template to Node (not done with this repository)
- also advised to create readme file; skipped due to misunderstanding/needless preventative measures against duplicate readme files. This was easily added later.
- make sure default is set to Main, not Master with 

What is a repository?
A repository is a tool built on Git (source code management tool) to store not only code but tracks and saves history of all changes made to a project.

# Steps to create repository were as follows (truncated):
Part 1 (GitHub)
 1. Navigate to repositories page and click "create repository"
 2. Name repository (no spaces or capital letters, this will add a step when accessing from terminal)
 3. Add readme file (this will give other contributors an idea about what your project is about - this can be edited after creation)
 4. Add .gitignore; select .ignore template: Node
 5. "Create repository"
 6. On your repository's page there will be a green "Code" button containing a down arrow. Click the arrow to reveal links for cloning.
 7. Copy appropriate address for next part. 
Part 2 (Local-On your machine, thru bash or IDE; example is from Visual Studio Code with Bash terminal)
 8. Open terminal and navigate to folder on computer where you would like to clone repository (you can do this by clicking around in the IDE or by using cd command ie "cd desired-location" or a series of cd and ls commands to navigate through folders in your computer. ls command will display contents of a folder)
 9. "git clone <pasted url>" and hit enter.
 10. Repository is cloned. Check status with "git status"
 
# Committing files to your repository:
 If you make a change to your local repository, this change will not be reflected in the github repository without a few extra steps.
 1. Enter "git status" this should show you new or newly edited files. Red means that these files are not ready to be committed to the cloud repository.
 2. Make these files ready by "staging" them. Do this by entering "git add -A" (for the current directory & higher) or "git add ." (for the current directory only). See note (1) for an example.
 3. Now, when running "git status" the files should be green, meaning they are ready to be committed to the repository.
 4. Run "git commit -m "message"". This message should be a short informative blurb written in the imperitive of what changes were made. (i.e. fix bug). This step commits the files to the repository.
 5. "git push origin main" will then push the files to the repository.
 
 # In order to update your repository run the following:
 1. "git pull origin main"
 
 # Notes:
 (1) If file "text.html" is located in "Folder" and user is in "Subfolder" directory when running commands (i.e. ./Folder/Subfolder/), "git add ." will not stage "text.html" as it is in a higher directory than the current. However, running "git add -A" will stage ALL files in the subfolder AS WELL as the folder containing it.
 
 
