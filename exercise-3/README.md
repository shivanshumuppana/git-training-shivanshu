# Save your work

Learnt how to stash.

Used the following commands:
git stash
code bug.txt                <- fixed bug
git add bug.txt
git commit -m "Fixed bug"
git stash pop
code bug.txt                <- Added "Finally, finished it!"
git add .
git commit -m "Final"