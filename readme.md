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
1. [Full length article on gitgnore](https://www.linkedin.com/pulse/much-ado-gitignore-satya-komatineni/)
2. [An article on Linked In:Curious experiment with \*, \*/, /\*, /\*/, and /\*\* in .gitignore](https://www.linkedin.com/pulse/curious-experiment-gitignore-satya-komatineni/)
2. [A running journal on .gitignore](http://satyakomatineni.com/item/5394)
3. [Reference on gitignore at git](https://git-scm.com/docs/gitignore)
4. [An Atlassian article](https://www.atlassian.com/git/tutorials/saving-changes/gitignore#git-ignore-patterns)
5. [A Pluralinsight article](https://www.pluralsight.com/guides/how-to-use-gitignore-file)
6. [An SOF discussion](https://stackoverflow.com/questions/41761128/are-leading-asterisks-redundant-in-gitignore-path-matching-syntax)
7. [A repo for gitignore samples](https://github.com/github/gitignore)