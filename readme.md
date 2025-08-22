# Gym Git Exercise Solutions

This README file contains my solutions for most of the bundles of the Git exercises provided to us by our coaches, in person of Tresor Manzi and Souvede Inshuti from the gym.

## Table of Contents

- [Bundle 1](#bundle-1)
  - [Exercise 1](#exercise-1)
  - [Exercise 2](#exercise-2)
- [Bundle 2](#bundle-2)
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

## Bundle 2

### Exercise 1

```bash
# Create and switch to new branch
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ >  git checkout -b ft/bundle-2

# Create new services.html file
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > touch services.html

# Add some content to services.html (example)
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > echo "
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Gym Git Exercise Solutions | Services</title>
  </head>
  <body>
    <h1>Gym Git Exercise Solutions</h1>
    <p>Services Page</p>
  </body>
</html>
" > services.html

# Stage all changes
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git add .

# Commit changes
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git commit -m "feat: add services page"

# Push to remote repository
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git push -u origin ft/bundle-2

# Create pull request
I created a pull request for the ft/bundle-2 branch on GitHub.
```

### Exercise 2

```bash

# Checkout main branch
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git checkout master

# Pull latest changes from remote repository
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git pull

# Create and switch to new branch
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git checkout -b ft/service-redesign

# Add some content to services.html (example)
I added some content to services.html in VSCode

# Add services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git add .

# Commit services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git commit -m  "feat: add comprehensive services page content
- Added list of gym services (Cardio, Strength Training, Yoga, etc.)
- Included operating hours for all days of the week
- Added location and contact information
- Structured content with appropriate headings"

# Push the new branch and set upstream
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git push --set-upstream origin ft/service-redesign

# Switch back to master and make conflicting changes
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git checkout master

# Add services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git add .

# Commit services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git commit -m "feat: add comprehensive services page content to the master branch"

# Push services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git push

# Switch back to ft/service-redesign branch to resolve conflicts
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git checkout ft/service-redesign

# Compare changes with main branch
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git diff master

# Merge main into ft/service-redesign and resolve conflicts
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git merge master

# Add resolved services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git add .

# Commit resolved services.html
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git commit -m "Merge main into ft/service-redesign and resolve conflicts"

# Push the resolved branch
Oplanos-MacBook-Pro:gym-first-git-exercise-main  oplanojamesmulbah$ > git push

```
