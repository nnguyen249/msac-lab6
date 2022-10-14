# Exercise 7 - More than one changed file

1. Ensure you have a clean working directory

        git status

2. Edit one of your `fruits.txt`, add a few items

        blueberry
        strawberry
        etc.

3. Edit `appliances.txt` and add a few items

        dishwasher
        dryer
        etc.

4. Look at git status, paste the output here

        git status

5. Can you commit both of the changed files in a single commit?
Yes with adding both files or git add --all first then committing

6. After you do so, check that you have a clean working directory by running `git status`, and pasting the output here
$ git status
On branch main
Your branch is ahead of 'origin/main' by 8 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean


7. Create a new file `equipment/furniture.txt`. Add content to both `vegetables.txt` and `furniture.txt`

8. How can you commit just one of the changed files?
adding just the file you want to commit then comitting 

9. Check your `git status`

10. What does red text mean in the output of `git status`?
red text has not been added either unstaged or untracked files. These files will not commit when a commit command is given 

11. What does green text mean in the output of `git status`?
green text have been added and staged and will commit when commit command is given 
veg
12. How can you make a single file show in both red and green in the output of `git status`?
Modifying  a file after its been added will show green and red

