# Distributed version control systems #

Key points:

- Every clone of a `git` repository had the complete history of the project
- Multiple users can work on the project simultaneously
- The version control system reconciles different users' edits


## Quick intro to version control with git ##


### Prerequisites

- install git ([http://git-scm.com/](http://git-scm.com/))
- get an account from  [github.com](github.com), a free hosting service for `git` repositories


Optional : configure your preferred text editor[^tweakOSX]. 

[^tweakOSX]: Here's a one-liner you can add to a `.profile` to [use TextEdit as your default editor on OS X](https://gist.github.com/neelsmith/6511857)

[editor]: https://gist.github.com/neelsmith/6511857

### One-time setup

*Clone* (make a copy) a shared  repository:


    git clone REPOSITORYURL


### Routine work pattern


Get any new material others have added to the repository:

    git pull


Edit your files, then save your changes in the local copy of the repository

    git add FILENAME
    git commit

Every time you *commit* one or more files, you will be prompted to describe your changes in a brief message.

At this stage, your changes are saved in your local copy.  When you are ready to share your committed changes with the rest of your team, you can *push* them back to the shared repository:

    git push


At any time, you can check the status of your local files to see whether any files have been changed:

    git status


