# How to contribute

## Getting Started

  1. Fork the repo to your GitHub account
  2. Clone the repo to your local machine
  3. Add the upstream repository to your forked version, so that you can pull down any changes made upstream
     - Tell Git where the upstream is located: `git remote add upstream https://github.com/Reddit-Web-Dev/Reddit-Web-Dev.github.io.git`
     - Tell Git to grab information about the upstream repo: `git fetch upstream`
  4. Switch to the branch that you would like to work on. There are two optoins:
      - If we wanted to switch to branch "mockup" and name our local copy the same: `git checkout -t origin/mockup`
      - We could also change the name of the local copy but have it push to the branch "mockup": `git checkout -t -b <new name> origin/mockup`
  5. Create a new branch off the one you are going to be working off of. This will allow us to keep commit hisotry more stream-lined
     - Enter the branch that you want to work off of if your not already in it: `git checkout <branch name>`
     - Create a new branch: `git checkout -b <New Feature branch with your changes>`
  6. Make your changes and commit them
     1. `git add -A`
     2. `git commit -m "A nice message describing what you changed"`
  7. Once your code is ready, pull down any changes that have happend in the upstream repo
     - `git pull upstream <Branch you want to contribute>`
  8. Merge your changes with the main branch:
      1. Switch back to the main branch: `git checkout <Branch you want to contribute>`
      2. Merge your change branch with the main one: `git merge <New Feature branch with your changes>`
  9. Push the changes to the main branch on your github: `git push origin <Branch you want to contribute>`
  10. Go to your GitHub account, select the branch you changed, in this case,
  `<Branch you want to contribute>`, and click open a new PR button.

## Updating your fork

  1. `git fetch upstream branch`
  2. `git checkout branch`
  3. `git pull upstream branch`