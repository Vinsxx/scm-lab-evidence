Q1. Why is a commit history useful when maintaining software? Give one concrete maintenance situation (for example finding when a bug appeared) and refer to your own commits.

A commit history is useful because it allows developers to see the changes made to a project over time. For example, if a bug appears, developers can check previous commits to find when the problem started. In my exercise, I created a commit called "Add Session 1 notes". This helps me keep track of my changes and understand what I have done.

Q2. Explain the difference between Git and GitHub, using your two repositories (the exercise repository and scm-lab-evidence) as examples.

Git is a tool used to track changes and manage versions of a project on my computer. GitHub is an online platform where I can store and share my Git repositories. My exercise repository and scm-lab-evidence are examples of repositories that I can manage using Git. I can also upload them to GitHub to access them online.

Q3. In the GitHub Skills exercise you worked on a branch and used a pull request instead of changing main directly. What risk does this reduce?

Working on a separate branch reduces the risk of making mistakes directly in the main branch. It allows developers to test and review their changes before adding them to the main project. A pull request also allows other team members to check the changes. This helps prevent problems from affecting the main project.

Q4. State which of your commands changed only your computer and which changed GitHub.

Commands such as git init, git switch, mkdir, git add, git commit, and git restore only changed files or Git data on my computer. The git status and git log commands only displayed information without changing anything. Commands such as git push send my commits to GitHub. Therefore, Git commands do not automatically update GitHub unless I use a command that communicates with it.


Part 1:

Repository: A Git repository (repo) is a place where all project files and their changes are stored and managed.

Working Tree (Working Directory): The working tree contains the project files where changes can be made. It shows the current state of the project.

Staging Area (Index): The staging area is where changes are prepared before committing. It allows specific files to be selected instead of adding all changes at once.

Commit: A commit is a saved record of changes made to a project. It helps keep track of the project's progress.

Branch: A branch allows developers to work on new features or fix problems without directly changing the main branch.

Merge: Merge combines changes from one branch into another branch, such as adding completed work into the main branch.

Remote: A remote is a version of a repository stored on another server, such as GitHub. It allows developers to share and access their projects online.

Push / Pull / Clone: Push sends local commits to a remote repository. Pull downloads and combines changes from a remote repository into the local repository. Clone creates a local copy of a remote repository on a computer.