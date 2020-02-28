# Basic Git commands to know and love

##### [This tutorial](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners) is simple and thoroughly explains each step. If you're working solo on your own projects and you just want to move things back and forth between your computer and your Github account, it will teach you everything you need to know.

## Common commands:
Initialize a new repository:

    git init

Staging a change:

    git add <yourfile>

Committing a change:

    git commit -m 'your concise message'

Pulling changes from Github:

    git pull

Pushing changes to Github:

    git push

Checking the status of your repo:

    git status

Seeing exactly what changes have been made:

    git diff <yourfile>

## Typical workflows:
1. Use Git without Github (i.e. if you don't care about sharing your projects, Git is still a great tool to use personally). See above tutorial, steps 1-4.
1. Create a local Git repository, push it to Github. See: [New repo](https://kbroman.org/github_tutorial/pages/init.html).
1. Fork an online repository, clone it to your local computer, work on it, push it back to Github, +/- revise the original. See: [Forking](https://kbroman.org/github_tutorial/pages/fork.html).
1. Create a repository, create a new branch, work on that branch, merge back to original. See: [Branching and Merging](https://kbroman.org/github_tutorial/pages/branching.html)
