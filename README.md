# Git Assignment - <SidraOB>
What is an issue?

Github issue is the powerfull way to keeb track of different features or changings in code, For example its project management system for software developers.

What is a pull request?

It is a feature of github which allows developers to propose changes to code. When creating a pull request we are asking the repository maintainers to review and merge changes into the main branch.

Describe the steps to open a pull request?

- click on the pull request tab
-click on New pull request button
-Ensure that the base repository is the original repository and base branch is main 
-compare repository should be the forked repository and compare branch should be that we just pushed
-Fill out the details about why we did the changes and add relevant information
-we can also request reviewers and finally press "create pull request" button

Describe the steps to add a collaborator to a repository (share write permissions)

-Open the repository where you want to add a collaborator
-Click on the "Settings" tab
-click on the Collaborators under access menu
-To invite the people, click on "add people" under manage access
-type the github usename or email of the person you want to add as collaborator
-set the permission to "write" and send the invitation

What is the difference between git and GitHub?

Git is a distributed version control system that tracks changes in source code during software development. Git manages and tracks changes to files in a repository, allowing you to commit, branch, and merge changes locally.
GitHub is a platform that leverages Git to offer a collaborative environment for developers to work on projects together, with added features and tools for managing and sharing repositories online.

What does git diff do?

It shows changes between the working directory and the staging area. This is useful for viewing modifications you made but have not yet staged for commit.

What is the main branch?

Main branch is the default branch of a repository. The code in main branch remains stable. We create another branch if we want to do any changing in code and then merge into main branch after reviewing. 

Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

While directly pussing to main branh is possible but we should use branching strategy. It promotes better practices in terms of code stability, collaboration, testing, and tracking changes.
