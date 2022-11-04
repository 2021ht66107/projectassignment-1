# Git Basics
> assignment 1


```bash
## create director on local system
mkdir projectassignment-1
cd projectassignment-1
```

```bash
## create repo on github and follow th instructions on local system
echo "# projectassignment-1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/2021ht66107/projectassignment-1.git
git push -u origin main
```

```bash
## Create a branch(development/production/feature)
git checkout -b development
git push -u origin development

git checkout -b production
git push -u origin production

git checkout -b feature
git push -u origin feature
```

```bash
## Edit files or create new files followed by commit
This file is created and committed
```

Clone the repo and Create pull-request

While collaborating your work, showcase how conflicts are resolved

Create tag such as open issue, or feature-added

Do a force push/commit and then later reset the changes

Stage “development branch to production branch”

Showcase how features are released in versions (merging production to master branch)

Also, state importance of Readme and gitignore files and their usage while working in a distributed environment.
