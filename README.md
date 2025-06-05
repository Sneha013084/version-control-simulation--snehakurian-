## Project Reflection ##
#### Steps for create and manage branches: ####
 Log into GitHub and create a new repository. Clone the repository to your local computer using the git clone command to set up a workspace where you can easily manage and track your changes. To keep your work organized, create separate branches for each feature, like master, feature/header, and feature/footer, using the command *git checkout -b <branch-name>*. Check which branch you’re on by running *git branch* to ensure you’re working on the right one. After making changes, stage the files with *git add*, *git commit* them with a message, and push the changes to GitHub by using *git push*.
#### Handling of Merge conflict: ####
While working on the project, push both your master and feature branches to GitHub. When you create a pull request to merge your feature branch into master, you may face a merge conflict. Use *git status* to find the conflicting files, open them, and manually combine the correct parts from both branches. After resolving the conflict, stage the fixed files and commit the changes to keep your code clean.
#### The pull request process helps ensure code quality and collaboration: ####
Using pull requests helps maintain code quality and encourages teamwork. Submitting a pull request allows you and your teammates to review the changes before merging them into the main branch, making it easier to find mistakes and improve the code. Take advantage of the discussion and commenting features to communicate better and collaborate smoothly. Pull requests also make it simple to track all changes and test them before finalizing.

By using branches, fixing merge conflicts, and following the pull request process, you can improve your collaborative software development skills. These steps help keep your project organized and make it easier to work with others.

