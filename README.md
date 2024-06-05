# Q&A Website

## Overview

This project is a Q&A website designed for users to engage with general knowledge questions and answers

## Technologies Used

-**Frontend:** HTML, CSS, JavaScript

## Advanced Git and GitHub Assignment

**Name:** Leah Sherley  
**Forked Repository:** [Quiz-Website](https://github.com/RandikiOduor/Quiz-Website.git)  
**Open Source Project Link:** [Quiz-Website](https://github.com/RandikiOduor/Quiz-Website.git)

### Task 1: Cloning and Forking

1. **Cloned the repo:**
    ```bash
    leah-sherley@hp:~/Desktop$ git clone https://github.com/LeahSherley/Quiz-Website.git
    ```

2. **Created a new branch and switched to it:**
    ```bash
    leah-sherley@hp:~/Desktop/Quiz-Website$ git checkout -b feature-update
    Switched to a new branch 'feature-update'
    ```

### Task 2: Managing Branches

3. **Added new styling to the website and staged the changes:**
    ```bash
    leah-sherley@hp:~/Desktop/Quiz-Website$ git add .
    ```

4. **Committed the changes:**
    ```bash
    leah-sherley@hp:~/Desktop/Quiz-Website$ git commit -m "styled the questions correctly to occupy the intended space"
    [feature-update 723b8a3] styled the questions correctly to occupy the intended space
    1 file changed, 18 insertions(+), 14 deletions(-)
    ```

5. **Switched to the main branch:**
    ```bash
    leah-sherley@hp:~/Desktop/Quiz-Website$ git checkout main
    Switched to branch 'main'
    Your branch is up to date with 'origin/main'.
    ```

6. **Merged the branches:**
    ```bash
    leah-sherley@hp:~/Desktop/Quiz-Website$ git merge feature-update
    Updating c90992e..723b8a3
    Fast-forward
    quiz.css | 32 ++++++++++++++++++--------------
    1 file changed, 18 insertions(+), 14 deletions(-)
    ```

7. **Pushed the changes to the remote repository:**
    ```bash
    leah-sherley@hp:~/Desktop/Quiz-Website$ git push
    Enumerating objects: 5, done.
    Counting objects: 100% (5/5), done.
    Delta compression using up to 2 threads
    Compressing objects: 100% (3/3), done.
    Writing objects: 100% (3/3), 580 bytes | 580.00 KiB/s, done.
    Total 3 (delta 2), reused 0 (delta 0)
    remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
    To https://github.com/LeahSherley/Quiz-Website.git
    c90992e..723b8a3  main -> main
    ```

### Task 3: Handling Conflicts

8. **Creating Conflicts:**
    - made changes to this file and committed them.
    

9. **Resolving Conflicts:**
    - Created a new branch to resolve the conflict.
    - Resolve the conflict manually in the file.
    - Committed the changes and merged the branch back into `main`.

### Task 4: GitHub Pages

10. **Enabling GitHub Pages:**
    - Enabled GitHub Pages for the repository and set the source branch to `main`.

11. **Accessing the Published Page:**
    - Visited the GitHub Pages URL for your repository and verify that the HTML file is accessible online.

### Task 5: Open Source Exploration

12. **Exploring Open Source Projects:**
    - used the same project for open source exploration.

13. **Opening an Issue:**
    - Opened a new issuefor style improvements.

### Submission

- Pushed all changes to your forked repository on GitHub.
