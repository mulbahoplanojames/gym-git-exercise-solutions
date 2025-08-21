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

```
