
# Undoing Changes


Run `git checkout -- <filename>` to discard the changes made to a single file.


#### Unstaging files
---
Run `git reset HEAD <filename>` to unstage a file, ie. set it back to its state at HEAD.


<br>


#### Reverting a file to its state in an older commit.

Run `git checkout <SHA1> -- <filename>`



#### Removing unstaged files
---

Run `git clean -f`.
