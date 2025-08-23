# Gym Git Exercise Solutions

This README file contains my solutions for most of the bundles of the Git exercises provided to us by our coaches, in person of Tresor Manzi and Souvede Inshuti from the gym.

## Table of Contents

- [Bundle 1](#bundle-1)
  - [Exercise 1](#bundle-1-exercise-1)
  - [Exercise 2](#bundle-1-exercise-2)
- [Bundle 2](#bundle-2)
  - [Exercise 1](#bundle-2-exercise-1)
  - [Exercise 2](#bundle-2-exercise-2)
- [Bundle 3](#bundle-3)
  - [Exercise 1](#bundle-3-exercise-1)
  - [Exercise 2](#bundle-3-exercise-2)
- [Bundle 4](#bundle-4)
  - [Exercise 1](#bundle-4-exercise-1)
  - [Exercise 2](#bundle-4-exercise-2)
- [Bundle 5](#bundle-5)
  - [Exercise 1](#bundle-5-exercise-1)
  - [Exercise 2](#bundle-5-exercise-2)
- [Bundle 6](#bundle-6)
  - [Exercise 1](#bundle-6-exercise-1)
  - [Exercise 2](#bundle-6-exercise-2)
  - [Exercise 3](#bundle-6-exercise-3)
  - [Exercise 4](#bundle-6-exercise-4)

## Bundle 1

### Bundle 1 Exercise 1

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

### Bundle 1 Exercise 2

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

### Bundle 2 Exercise 1

```bash
# Create and switch to new branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git checkout -b ft/bundle-2

# Create new services.html file
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch services.html

# Add some content to services.html (example)
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > echo "
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
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

# Commit changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add services page"

# Push to remote repository
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push -u origin ft/bundle-2

# Create pull request
I created a pull request for the ft/bundle-2 branch on GitHub.
```

### Bundle 2 Exercise 2

```bash

# Checkout main branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout master

# Pull latest changes from remote repository
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git pull

# Create and switch to new branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b ft/service-redesign

# Add some content to services.html (example)
I added some content to services.html in VSCode

# Add services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

# Commit services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m  "feat: add comprehensive services page content
- Added list of gym services (Cardio, Strength Training, Yoga, etc.)
- Included operating hours for all days of the week
- Added location and contact information
- Structured content with appropriate headings"

# Push the new branch and set upstream
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin ft/service-redesign

# Switch back to master and make conflicting changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout master

# Add services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

# Commit services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add comprehensive services page content to the master branch"

# Push services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push

# Switch back to ft/service-redesign branch to resolve conflicts
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/service-redesign

# Compare changes with main branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git diff master

# Merge main into ft/service-redesign and resolve conflicts
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git merge master

# Add resolved services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

# Commit resolved services.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "Merge main into ft/service-redesign and resolve conflicts"

# Push the resolved branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push

```

## Bundle 3

### Bundle 3 Exercise 1

```bash
# Create and switch to ft/team-page branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b ft/team-page

# Create team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch team.html

# Add team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add team.html

# Commit team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add team page with initial content"

# Push team.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin ft/team-page

# Create PR
I created a pull request for the ft/team-page branch on GitHub.

# Switch to master
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout master

# Create and switch to ft/contact-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b ft/contact-page

# Switch back to ft/team-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/team-page

# Get last commit hash from ft/team-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > COMMIT_HASH=$(git log -1 --pretty=format:"%H")

# Switch back to ft/contact-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/contact-page

# Cherry-pick changes from ft/team-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git cherry-pick $COMMIT_HASH

# Switch back to ft/contact-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/contact-page

# Add contact page content
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch contact.html

# Add contact.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add contact.html

# Commit contact.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add contact page"

# Push contact.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin ft/contact-page

# Create PR for contact page
I created a pull request for the ft/contact-page branch on GitHub.

# Create ft/faq-page from ft/contact-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b ft/faq-page

# Create faq.html with content
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > touch faq.html

# Add faq.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add faq.html

# Commit faq.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add FAQ page"

# Push faq.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin ft/faq-page

# Revert last commit in ft/team-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/team-page

# Revert last commit in ft/team-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git revert $COMMIT_HASH

# Push the reverted branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push

# Switch back to ft/faq-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/faq-page

# Add faq.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add faq.html

# Commit faq.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add FAQ page"

# Push faq.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push

# Create PR for faq page
I created a pull request for the ft/faq-page branch on GitHub.
```

### Bundle 3 Exercise 2

```bash
# Switch to ft/faq-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git checkout ft/faq-page

# Create and switch to ft/home-page-redesign from ft/faq-page
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git checkout -b ft/home-page-redesign

# Switch back to main branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git checkout master

# Make changes to home.html
I updated the home.html file in VSCode

# Add home.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add home.html

# Commit home.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "chore: update home page content on main branch"

# Push to remote repository
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push

# Switch back to ft/home-page-redesign branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout ft/home-page-redesign

# Rebase ft/home-page-redesign onto master
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git rebase master

# Make changes to home page in ft/home-page-redesign
I updated the home.html file in VSCode

# Add home.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add home.html

# Commit home.html
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: redesign home page with modern layout"

# Push to remote repository
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push --set-upstream origin ft/home-page-redesign

# Create PR for ft/home-page-redesign
I created a pull request for the ft/home-page-redesign branch on GitHub.

```

## Bundle 4

### Bundle 4 Exercise 1

```bash
# Switch to main branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git checkout master

# Create a new repository on GitHub
I created a new repository on GitHub.

# Then add it as a remote
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git remote add git-copy https://github.com/mulbahoplanojames/gym-git-exercise-copy.git

# Make changes to home page
I updated the home.html file in VSCode

# Stage the changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .

# Commit the changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "chore: update home page content"

# Push to origin (original remote)
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push origin master

# Push to git-copy (new remote)
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push git-copy master

```

### Bundle 4 Exercise 2

```bash
# Create and switch to new footer branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ >  git checkout -b ft/footer

# Make first set of changes to footer
# (edit files as needed)
I updated the footer.html file in VSCode

# Stage and commit first set of changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: add basic footer structure"

# Make second set of changes to footer
# (edit files as needed)
I updated the footer.html, contact.html, and home.html files in VSCode

# Stage and commit second set of changes
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git add .
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git commit -m "feat: enhance footer with social links and styling"

# Push to remote and create PR
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push -u origin ft/footer

# Create PR in GitHub
I created a pull request for the ft/footer branch on GitHub.

# Switch back to main
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout master

# Create and switch to new squashing branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git checkout -b ft/squashing

# Merge and squash the footer branch
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git merge --squash ft/footer

# Create a single commit with squashed changes
git commit -m "feat: complete footer implementation with styling and social links with footer changes squashing"

# Push to remote
Oplanos-MacBook-Pro:gym-git-exercise-solutions oplanojamesmulbah$ > git push -u origin ft/squashing

# Create PR in GitHub
I created a pull request for the ft/squashing branch on GitHub.
```

## Bundle 5

### Bundle 5 Exercise 1

```bash
# I enable the github page for the gym-git-exercise-solutions repository on GitHub.

# I check the github page and it is available to everyone.
```

### Bundle 5 Exercise 2

```bash
#  Fork the repository
I forked the repository on GitHub.


# Clone the forked repository
I cloned the repository from my forked repository on GitHub to my local machine.

Oplanos-MacBook-Pro:oplanojamesmulbah$ > git clone git@github.com:mulbahoplanojames/git-cafe-exercise.git

# cd into the repository
Oplanos-MacBook-Pro:oplanojamesmulbah$ > cd git-cafe-exercise

# Edit index.html to change the welcome text
I updated the index.html file in VSCode

# Check the changes
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ >git diff

# Add index.html
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ >git add index.html

# Commit index.html
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ >git commit -m "chore: update welcome message to 'Welcome to our restaurant'"

# Push the changes to my fork
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ >git push origin main

# Create a Pull Request
I created a pull request for the index.html file on GitHub.
```

## Bundle 6

### Bundle 6 Exercise 1

```bash
# cd into the repository
Oplanos-MacBook-Pro:oplanojamesmulbah$ > cd git-cafe-exercise

# Create and switch to a new feature branch
git checkout -b feature/add-menu-page

# Create a new menu.html file
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > touch menu.html

# Add menu.html
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git add menu.html

# Commit menu.html
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git commit -m "feat: add menu page"

# Push the changes to my fork
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git push origin feature/add-menu-page

# Create a Pull Request
I created a pull request for the feature/add-menu-page branch on GitHub.

```

### Bundle 6 Exercise 2

```bash
# Create and switch to a new bugfix branch
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git checkout -b bugfix/update-contact-title

# Rename index-4.html to contact.html
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git mv index-4.html contact.html

# Stage the changes
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git add contact.html

# Commit the changes
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git commit -m "fix: rename index-4.html to contact.html"

# Push the branch to remote
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git push -u origin bugfix/update-contact-title

# Create a Pull Request
I created a pull request for the bugfix/update-contact-title branch on GitHub.
```

### Bundle 6 Exercise 3

```bash
# Create and switch to a new hotfix branch
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git checkout -b hotfix-contact

# Edit the phone number in index-4.html in VSCode
# (Update the number from +1 800 603 6035 to +1 800 659 6035)

# Stage the changes
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git add index-4.html

# Commit the changes
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git commit -m "fix: update contact phone number to +1 800 659 6035"

# Push the branch to remote
Oplanos-MacBook-Pro:git-cafe-exercise oplanojamesmulbah$ > git push -u origin hotfix-contact

# Create a Pull Request
I created a pull request for the hotfix-contact branch on GitHub.
```

### Bundle 6 Exercise 4

```bash
# Create and review pull requests from your peers on GitHub.
I reviewed the pull requests from my peers on GitHub and merged the pull requests that were approved.
```
