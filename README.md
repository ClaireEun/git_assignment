# Git Assignment - ClaireEun
=======================
a. What is an issue?
An issue is a way to track tasks, enhancements, bugs, and other types of work in a repository on platforms like GitHub. It acts as a discussion thread where developers 

b. What is a pull request?
A pull request (PR) is a request to merge changes from one branch (typically a feature branch) into another branch (often the main or master branch) in a Git repository. A pull request allows team members to review the changes, discuss potential improvements, and approve the merge before it is finalized.

c. Describe the steps to open a pull request?
1. Fork or Clone the repository 
2. Create a New Branch
3. Make change
4. Push changes to Github

d. Describe the steps to add a collaborator to a repository (share write permissions)
Navigate to repository on GitHub.
Open the Settings Tab: Click on the "Settings" tab.
Manage Access: In the sidebar, click on "Collaborators and Teams" or "Manage access."
Invite a Collaborator:
Click on "Invite a collaborator."
Enter the GitHub username or email of the person you want to add.
Click "Add <username>" to send the invitation.
Accept Invitation: The collaborator will receive an invitation, which they must accept to gain write access to the repository.

e. What is the difference between git and GitHub?
Git: Git is a distributed version control system that allows developers to track changes in their code, manage revisions, and collaborate with others. Git runs locally on your computer and doesn't require an internet connection.

GitHub: GitHub is a web-based platform built on top of Git. It provides a centralized place for hosting Git repositories, along with additional features like issue tracking, pull requests, and collaboration tools. GitHub facilitates sharing code and collaborating on projects with others.

f. What does git diff do?
git diff shows the differences between the working directory and the staging area or between different commits. It displays the changes that have been made to the files, including lines that have been added, modified, or deleted.

g. What is the main branch?
The main branch (formerly often called master) is the primary branch of a Git repository. It typically contains the stable, production-ready code. All other branches typically branch off from the main branch and are eventually merged back into it after the changes are reviewed and approved.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
Generally, no, you should not push changes directly to the main branch. Instead, it is good practice to:

Create a new branch for your feature or fix.
Make your changes and commit them to this branch.
Push the branch to the remote repository.
Open a pull request to merge the changes into the main branch.
This workflow ensures that your changes are reviewed and tested before they are merged into the main branch, reducing the risk of introducing bugs or breaking the production code.