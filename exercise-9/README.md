# Fix typo in old commit

Used how to use interactive rebase.

Used the following commands:
```
-git rebase -i HEAD~2
-#Added break after the commit with a typo
-code file.txt
-git add file.txt
-git commit --amend
-git rebase --continue
-code file.txt
-#fixed merge errors
-git add file.txt
-git commit --no-edit
-git rebase --continue
```