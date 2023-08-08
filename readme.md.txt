# Learn Git - Instructions

This repository contains a step-by-step guide to learn Git version control.

## Prerequisites

Before you begin, ensure that you have Git installed on your machine. You can download and install Git from the official website [here](https://git-scm.com/).

## Getting Started

1. Create a folder called `learn_git`.

2. Change your current working directory to `learn_git` using the `cd` command:
cd learn_git

3. Create a file called `third.txt` inside the `learn_git` folder.

4. Initialize an empty Git repository using the following command:
git init

5. Add `third.txt` to the staging area:
git add third.txt

6. Commit the changes with the message "adding third.txt":
git commit -m "adding third.txt"

7. Check your commit history using `git log`:
git log


8. Create another file called `fourth.txt` inside the `learn_git` folder.

9. Add `fourth.txt` to the staging area:
git add fourth.txt


10. Commit the changes with the message "adding fourth.txt":
 ```
 git commit -m "adding fourth.txt"
 ```

11. Remove the `third.txt` file from the repository:
 ```
 git rm third.txt
 ```

12. Add the removal change to the staging area using the command:
 ```
 git add .
 ```

13. Commit the changes with the message "removing third.txt":
 ```
 git commit -m "removing third.txt"
 ```

14. Check your commit history using `git log`:
 ```
 git log
 ```

15. Change your global settings to use `cat` as the pager:
 ```
 git config --global core.pager "cat"
 ```

16. To list all the global configurations for Git on your machine, use:
 ```
 git config --global --list
 ```

## Additional Resources

To further enhance your understanding of Git, you can refer to the following resources:
- [Official Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)

Happy learning and happy coding!