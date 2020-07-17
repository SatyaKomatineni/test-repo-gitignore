# About
This repo is created to test various settings in .gitignore file

# How to use this repo
You cannot really test the effects of .gitignore on a commited repo. So you have to do the following

1. Clone the repo
2. Give it a proper name. 
3. You won't be staging files or commiting or pushing the test repo back to a server
2. Remove the .git sub folder to make it non-git
3. Do a git init at the root to make it a fresh non committed repo
4. Now all files are new
5. Now you can uncomment what each option in .gitignore to see which files git consideres as candidates for "staging"