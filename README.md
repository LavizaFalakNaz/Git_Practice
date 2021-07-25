# LEARNING GIT

This is a git practice repository i've created to practice Git and help juniors follow a very simple pathway towards professional software development.

# INSTALLING GIT

goto https://git-scm.com/download/win and download the setup

run the setup and choose all the default options (TRUST ME, THEY'RE THE BEST ONES FOR BEGINNERS AND PROFESSIONALS TOO!)

once installed, search for "GIT GUI" on windows search option. you should see a repository

now you need to link this VCS (Version Control System) with an application like GitHub! (And Whoosh, by default you alread prepared it to link to a github account!)

# LINKING TO A GITHUB ACCOUNT

open powershell and run the following commands
Create a new test directory (folder) by entering the following:
```
mkdir git_test
```
Change your location to the newly created directory:
```
cd git_test
```
Configure GitHub Credentials
```
git config ––global user.name “github_username”
git config ––global user.email “email_address”
```
Clone a GitHub Repository
```
git clone <em>repository_url</em>
```
List Remote Repositories
```
cd git_project
```
list the remote repositories:
```
git remote –v
```
Pushing Local Files to the Remote Repository

1. For example, create a new text file by entering the following into your PowerShell window:
```
new-item text.txt
```
2. Confirmation that the new file is created.

Create new text file in Windows PowerShell.

3. Now check the status of your new Git branch and untracked files:
```
git status
```
4. Add your new file to the local project:
```
git add text.txt
```
5. Run git status again to make sure the text.txt file has been added. Next, commit the changes to the local project:
```
git commit –m “Sample 1”
```
6. Finally, push the changes to the remote GitHub repository:
```
git push
```
You may need to enter your username and password for GitHub.
