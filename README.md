# Vaughn Erik T. Dungo
#### This is my README.md file for my GitHub Introductory Repository

*I am currently at my second year college at [Mapua Malayan Colleges Laguna] taking BSIT.  

[Mapua Malayan Colleges Laguna]: (https://mcl.edu.ph/)

#### Other Details

- My Birthday (February 24, 2004, 19 years of age)
- I live in Santa Rosa Laguna

#### My Hobbies & Interests

- Cycling
- Playing Musical Instruments
- Driving
- Cooking
- Learning Programming
- I love listening to Classic OPM Music

#### 🌱 I’m currently learning:
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

#### Git Cheat Sheet

1. **Command: git blame**
   - *Description:* This command is used to find out who changed what in a file and at what revision.
   - *When to use:* When you want to track the authorship of each line in a file, helpful for understanding the history and context of changes.
   - *Parameters:*
     - -L: Specify a range of lines to examine.
     - <file>: The file you want to analyze.
   - *Example:*
     
     git blame -L 10,20 myfile.txt
     
     This command will show the changes made in lines 10 to 20 of myfile.txt along with the commit and author details.

2. **Command: git bisect**
   - *Description:* This command helps you find the commit that introduced a bug by performing a binary search through your commit history.
   - *When to use:* When you have a bug in your project, and you want to identify the specific commit that caused the issue.
   - *Parameters:*
     - start: Specify the starting point (a commit known to be good).
     - end: Specify the ending point (a commit known to be bad).
   - *Example:*
     
     git bisect start
     git bisect good 3a12bf2  # Specify a commit known to be good
     git bisect bad          # Specify the current commit as bad
     
     Git will perform a binary search, marking commits as good or bad until it identifies the one that introduced the bug.

3. **Command: git stash**
   - *Description:* Stash away changes in your working directory without committing them, allowing you to switch branches or perform other tasks.
   - *When to use:* When you need to temporarily save your changes without committing them to switch to another branch or perform a task.
   - *Parameters:*
     - save: Optional, include a message to describe the stash.
   - *Example:*
     
     git stash save "Work in progress, switching branches"
     
     This command will stash your changes with a message for reference, allowing you to switch branches without committing.

4. **Command: git cherry-pick**
   - *Description:* Apply changes introduced by some existing commits to your current branch.
   - *When to use:* When you want to selectively pick and apply specific commits from one branch to another.
   - *Parameters:*
     - <commit>: The commit you want to apply.
   - *Example:*
     
     git cherry-pick abc123
     
     This command will apply the changes from the commit with the hash abc123 to your current branch.

5. **Command: git rebase -i**
   - *Description:* Interactive rebase lets you modify commit history by combining, editing, or deleting commits interactively.
   - *When to use:* When you want to clean up or modify your commit history before pushing to a shared repository.
   - *Parameters:*
     - -i: Launch the interactive mode.
   - *Example:*
     
     git rebase -i HEAD~3
     
     This will open an interactive rebase window for the last 3 commits, allowing you to pick, edit, squash, or drop commits interactively.

<!--
*vaughnDungo/vaughnDungo* is a ✨ special ✨ repository because its README.md (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->