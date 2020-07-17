# About
This repo is created to test various settings in .gitignore file

# How to use this repo
You cannot really test the effects of .gitignore on a commited repo. So you have to copy this repo
and reinitialize it as a separate repo.

# Reinitializing it as a new repo
1. Clone the repo
2. Give it a proper name. 
3. You won't be staging files or commiting or pushing the test repo back to a server
2. Remove the .git sub folder to make it non-git
3. Do a git init at the root to make it a fresh non committed repo

# Now you can test the effects of changing .gitignore
1. Now all files are new
2. Now you can uncomment what each option in .gitignore to see which files git consideres as candidates for "staging"

# Few useful URLs
1. [An article on Linked In: https://www.linkedin.com/pulse/curious-experiment-gitignore-satya-komatineni/](https://www.linkedin.com/pulse/curious-experiment-gitignore-satya-komatineni/)
2. [A running journal on .gitignore](http://satyakomatineni.com/5394)