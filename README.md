# HowToPutCodesInGithub
How to put codes, commit to github

[Adding an existing project to GitHub using the command line] 

"https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/"

Step 1. Create a new repository on GitHub

Step 2. Open Git Bash : locates in the project folder, right click and open git gash menu from menu list

Step 3. Initialize the local directory as a Git repository
```
$git init
```
Step 4. Add the files in your new local repository
```
$git add .
```
Step 5. Commit the files that you've staged in your local repository
```
$git commit -m "First commit"
```
Step 6.In the Command prompt, add the URL for the remote repository where your local repository will be pushed
```
$git remote add origin remote repository URL
```
Step 7. Push the changes in your local repository to GitHub
```
$git push origin master
```
