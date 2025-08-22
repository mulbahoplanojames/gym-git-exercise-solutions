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
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git init

# Check status
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git status

# Add README.md file
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch README.md

# Rename branch to master
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git branch -m master

# Check branches
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git branch

# Add all files
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

# Make initial commit
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "Initial commit\n\n- Add initial README.md file with project description\n- Create table of contents for exercise solutions\n- Set up structure for Bundle 1 with placeholders for exercises\n- Include basic formatting and code blocks for command examples"

# Set up remote
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git remote add origin https://github.com/mulbahoplanojames/gym-git-exercise-solutions.git

# Push to remote and set upstream
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin master

# Create and switch to dev branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b dev

# Create and switch to test branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b test

# Switch back to dev
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout dev

# Delete test branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git branch -d test

# Push dev branch to remote
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin dev
```

### Exercise 2

```bash
# Create home.html and attempt to stash
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch home.html

Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash

# Check status
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git status

# Add home.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git status

# Stash home.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash

# Create and add about.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch about.html

Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add about.html

# Stash about.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash

# Create and add team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch team.html

Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add team.html

# Stash team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash

# Apply stashed changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash pop stash@{1}
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash pop stash@{1}

# Add and commit home.html and about.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "Add and Setup home.html and about.html page"

# Apply remaining stash with team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git stash pop

# Reset to previous commit
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git reset --hard
```
