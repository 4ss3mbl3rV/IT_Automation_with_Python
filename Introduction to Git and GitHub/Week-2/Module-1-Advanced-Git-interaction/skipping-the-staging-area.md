# Skipping the Staging Area

we can use `git commit -a` to skip the staging step and commit the changes to the tracked file.
__Note__ `git commit -a` only commits the files that has been tracked before. This mean that a new file that createsafter the lastest commit wouldn't be committed.

TL;DR. `git commit -a` is a shortcut to stage any changes to tracked files and commit them in one step.

## HEAD in Git

Git uses the `HEAD` alias to represent the current checked-out snapshot of your project.
