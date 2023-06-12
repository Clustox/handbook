# **Introduction to GIT and Basic Commands**

**Objective:**
The objective of this task is to familiarize the fresh graduate with the fundamentals of Git version control system, including basic commands and the benefits of using Git in software development.

**Instructions:**

1. **Set up Git:**
    - Install Git on your local machine if it is not already installed. You can download Git from the **[official website](https://git-scm.com/)**.
    - Configure your Git username and email using the following commands:
        
        ```
        git config --global user.name "Your Name"
        git config --global user.email "your.email@example.com"
        
        ```
        
2. **Create a Git repository:**
    - Create a new empty directory on your local machine for this task.
    - Initialize a new Git repository in that directory using the command:
        
        ```ruby
        git init
        
        ```
        
3. **Learn basic Git commands:**
Familiarize yourself with the following basic Git commands and their purposes:
    - **`git add`**: Add file changes to the staging area.
    - **`git commit`**: Commit staged changes to the local repository.
    - **`git status`**: View the current status of your working directory and staged changes.
    - **`git log`**: View the commit history.
    - **`git branch`**: List, create, or delete branches.
    - **`git checkout`**: Switch branches or restore files from a specific commit.
    - **`git push`**: Push your local commits to a remote repository.
    - **`git pull`**: Fetch and merge changes from a remote repository to your local repository.
4. **Understand the benefits of using Git:**
Research and write a brief report (around 1 page) explaining the benefits of using Git as a version control system in software development. Include the following points:
    - Collaboration and team workflow facilitation.
    - Version control and history tracking.
    - Branching and merging capabilities.
    - Remote repository management.
    - Conflict resolution and code review process.
5. **Practice Git workflow:**
    - Create a new branch named "feature-branch" using the command:
        
        ```
        git branch feature-branch
        ```
        
    - Switch to the newly created branch using the command:
        
        ```
        git checkout feature-branch
        ```
        
    - Create a new text file named "sample.txt" and add some text content to it.
    - Add the "sample.txt" file to the staging area using the command:
        
        ```
        git add sample.txt
        ```
        
    - Commit the changes to the local repository with an appropriate commit message using the command:
        
        ```
        git commit -m "Add sample.txt file"
        ```
        
    - Switch back to the main/master branch using the command:
        
        ```
        git checkout main/master
        ```
        
    - Merge the changes from the "feature-branch" to the main/master branch using the command:
        
        ```
        git merge feature-branch
        ```
        
    - Push the changes to the remote repository (with appropriate permissions) using the command:
        
        ```
        git push origin main/master
        ```
        
6. **Submission:**
Submit the following items to your mentor upon completion:
    - A document containing the brief report on the benefits of using Git.
    - A screenshot of the Git log showing the commit history.
    - A description of the steps followed during the Git workflow practice.

**Note:** Throughout the task, feel free to seek guidance and clarification from your team lead or mentor. Remember to follow the rules mentioned at the beginning of the task. Happy learning!
