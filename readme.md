# Gym Git Exercise Solutions

This README file contains my solutions for most of the bundles of the Git exercises provided to us by our coaches, in person of Tresor Manzi and Souvede Inshuti from the gym.

## Table of Contents

- [Bundle 1](#bundle-1)
  - [Exercise 1](#exercise-1)
  - [Exercise 2](#exercise-2)

## Bundle 1

### Exercise 1

```bash
# Initialize repository
git init

# Check status
git status

# Add README.md file
touch README.md

# Rename branch to master
git branch -m master

# Check branches
git branch

# Add all files
git add .

# Make initial commit
git commit -m "Initial commit\n\n- Add initial README.md file with project description\n- Create table of contents for exercise solutions\n- Set up structure for Bundle 1 with placeholders for exercises\n- Include basic formatting and code blocks for command examples"

# Set up remote
git remote add origin https://github.com/mulbahoplanojames/gym-git-exercise-solutions.git

# Push to remote and set upstream
git push --set-upstream origin master

# Create and switch to dev branch
git checkout -b dev

# Create and switch to test branch
git checkout -b test

# Switch back to dev
git checkout dev

# Delete test branch
git branch -d test

# Push dev branch to remote
git push --set-upstream origin dev
```

### Exercise 2

```bash
# Create home.html and attempt to stash
touch home.html
git stash

# Check status
git status

# Add home.html
git add .
git status

# Stash home.html
git stash

# Create and add about.html
touch about.html
git add about.html

# Stash about.html
git stash

# Create and add team.html
touch team.html
git add team.html

# Stash team.html
git stash

# Apply stashed changes
git stash pop stash@{1}
git stash pop stash@{1}

# Add and commit home.html and about.html
git add .
git commit -m "Add and Setup home.html and about.html page"

# Apply remaining stash with team.html
git stash pop

# Reset to previous commit
git reset --hard
```
