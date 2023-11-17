# GIT COMMANDS
repo to practice git pull

<!-- Adding GIT commands. -->
Repository Setup:

    git init: Initializes a new Git repository.
    git clone [repository]: Clones a remote repository to your local machine.
    git config: Configures Git settings.

Staging and Committing:

    git add [file]: Adds a file to the staging area.
    git rm [file]: Removes a file from the repository.
    git mv [source] [destination]: Moves or renames a file.
    git commit -m "[message]": Commits the changes in the staging area with a descriptive message.
    git commit --amend: Modifies the most recent commit.

Branching and Merging:

    git branch: Manages branches in Git.
    git checkout [branch]: Switches to a different branch or restores files from a specific commit.
    git merge [branch]: Combines changes from different branches.
    git rebase [branch]: Applies commits from one branch onto another branch.
    git cherry-pick [commit]: Applies the changes of a specific commit onto the current branch.

Remote Repository Interaction:

    git remote add [name] [url]: Adds a remote repository.
    git remote remove [name]: Removes a remote repository.
    git fetch [remote]: Fetches the latest changes from a remote repository.
    git pull [remote] [branch]: Fetches and merges changes from a remote repository.
    git push [remote] [branch]: Uploads local branch commits to a remote repository.

Viewing and Managing History:

    git log: Displays the commit history of the repository.
    git show [commit]: Shows the details of a specific commit.
    git diff: Shows the differences between commits, branches, or files.
    git blame [file]: Displays who last modified each line of a file.
    git stash: Temporarily saves changes that are not ready to be committed.

Tagging:

    git tag [name]: Creates a tag for a specific commit.
    git tag -l: Lists all available tags.
    git tag -a [name] -m "[message]": Creates an annotated tag with a message.

Collaboration:

    git branch -r: Lists remote branches.
    git branch -a: Lists both local and remote branches.
    git push [remote] --delete [branch]: Deletes a remote branch.
    git fetch --prune: Prunes deleted remote branches.
    git checkout -b [branch] [remote]/[branch]: Creates a new local branch based on a remote branch.

Miscellaneous:

    git status: Shows the current status of the repository.
    git config -l: Lists all Git configuration settings.
    git clean: Removes untracked files from the working directory.
    git reset: Resets the current branch to a specific commit.
