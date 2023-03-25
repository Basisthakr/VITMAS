# VITMAS
Git Repository with all git commands listed the readme file with its Use and syntax

git init: Initializes a new Git repository.
Syntax: git init [repository name]

git add: Adds changes to the staging area.
Syntax: git add [file]

git commit: Records changes to the repository.
Syntax: git commit -m "commit message"

git push: Pushes changes to a remote repository.
Syntax: git push [remote] [branch]

git pull: Pulls changes from a remote repository.
Syntax: git pull [remote] [branch]

git clone: Clones a remote repository to a local directory.
Syntax: git clone [repository URL]

git branch: Lists, creates, or deletes branches.
Syntax: git branch [-a] [-v] [--merged | --no-merged] [<branchname>...]

git checkout: Switches to a different branch or commit.
Syntax: git checkout [-q] [-f] [-m] [<branch>] [--] <pathspec>...

git merge: Merges two or more branches.
Syntax: git merge [--no-ff] [-n] [--commit] [--squash] [--no-edit] [-s <strategy>] [-X <strategy-option>]... <commit>...

git status: Displays the current status of the repository.
Syntax: git status [-s] [-u[<mode>]] [--ignored] [--ignore-submodules[=<when>]] [--] [<pathspec>...]

git log: Displays the commit history of the repository.
Syntax: git log [--follow] [--grep=<pattern>] [--author=<pattern>] [--before=<date>] [--after=<date>] [--pretty[=<format>]] [--graph] [--oneline] [--decorate] [--abbrev-commit] [--reverse] [--] [<path>...]

git stash: Stashes changes for later use.
Syntax: git stash save [-p] [-k] [--] [<message>]

git remote: Lists, creates, or deletes remote repositories.
Syntax: git remote [-v | --verbose] add [-t <branch>] [-m <master>] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
git fetch: Fetches changes from a remote repository but doesn't merge them into the local branch.
Syntax: git fetch [remote]

git revert: Reverts a commit by creating a new commit that undoes the changes made by the original commit.
Syntax: git revert [commit]

git reset: Resets the current branch to a specific commit.
Syntax: git reset [commit]

git rebase: Applies changes from one branch onto another branch.
Syntax: git rebase [branch]

git tag: Creates a tag for a specific commit in the repository.
Syntax: git tag [-a] [-m <message>] [<tagname>] [<commit>]

git diff: Shows the differences between two commits or between the working directory and the repository.
Syntax: git diff [--options] [<commit>] [--] [<path>...]

git rm: Removes a file from the repository.
Syntax: git rm [--force] [--cached] <file>

git mv: Renames a file in the repository.
Syntax: git mv <source> <destination>

git submodule: Manages Git submodules, which are Git repositories embedded within a parent Git repository.
Syntax: git submodule [--quiet] add [-b <branch>] [--name <name>] [--reference <repository>] [--] <repository> [<path>]

git remote: Manages remote repositories that the local repository can track.
Syntax: git remote [-v | --verbose] add [-t <branch>] [-m <master>] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
git blame: Shows who last modified each line of a file.
Syntax: git blame [-L <range>] [--] <file>

git cherry-pick: Applies the changes of a specific commit onto the current branch.
Syntax: git cherry-pick [-n] [-e] [-s] [-x] [--ff] [-m parent-number] [-s] [-x] <commit>...

git bisect: Helps to find which commit introduced a bug by performing a binary search.
Syntax: git bisect <start> [<bad>] [<good>]

git show: Displays information about a specific commit.
Syntax: git show [<options>] [<object>]
