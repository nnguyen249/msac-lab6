# Exercise 6 - Committing a change (full cycle)

1. Look at git status and ensure you have a clean working directory

        git status

2. Open your `fruits.txt` file  in VS Code, your favorite code editor

3. Add some lines to the file

        apple
        banana
        tomato

4. Save and exit the editor

5. Look at git status

        git status

6. Add the file to the index

        git add fruits.txt

7. Check status

        git status

8. Commit the changes (short commit message included on command line)

        git commit -m "Added more fruit to the list"

9. Check status

        git status

10. Which of the steps could be omitted?
-m  and add

11. Why might it be a bad idea to omit them?
commits should always have a message so you know what you editted 
add should always be added so that the commit is intentional and not just automatically staged

12. Repeat the above steps to add a new file with the name `vegetables.txt`

13. Create a subdirectory named `equipment` and a new file named `appliances.txt` in that subdirectory

14. Repeat the above steps to commit the new file and directory

15. Repeat the above steps 1-9, adding data to each of your files a few lines at a time, until you can easily do the steps without referring to the steps. You may want to add vegetables to the vegetables file, and appliances to the appliances - or vice versa