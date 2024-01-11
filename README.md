# Task-2
## Explain version control.

Version control, also known as source control or revision control, is a system that manages changes to a project's codebase or any set of files over time.
It enables multiple contributors to work collaboratively on a project while keeping track of the changes made to the files. 

It is used to track changes on a project keep a record of every change made to the files, including who made the change, when it was made, and what exactly was 
changed. This historical record allows you to review and revert to previous states of the project.


It is used for collaboration among multiple developers providing centralized repository where everyone can contribute changes. Also it helps for conflict resolution
among developers who modify same files simultaneously

It acts as a backup mechanism. If something goes wrong or if a mistake is made, you can easily revert to a known good state of the project.

Version control provides an audit trail, making it possible to trace the evolution of the project over time. This is valuable for understanding the development 
history, identifying the source of bugs, and ensuring compliance with project requirements.


## Explain difference between git and github
Git is the version control system itself, while GitHub is a platform that uses Git for version control and adds collaborative features. Developers use Git to manage 
changes locally, and platforms like GitHub enable remote collaboration and provide additional tools to enhance the development process. 

Git is a command-line tool that operates locally on a developer's machine.
GitHub is an online platform that hosts Git repositories, providing collaboration 

Git is typically installed and used locally on a developer's machine.
GitHub is a cloud-based platform accessible through a web interface.

Git allows for local collaboration on a developer's machine.
GitHub facilitates remote collaboration, allowing multiple developers to work together on a project hosted in the cloud.

Git allows for local collaboration on a developer's machine.
GitHub facilitates remote collaboration, allowing multiple developers to work together on a project hosted in the cloud.

Git is primarily used through the command line, though there are graphical user interfaces available.
GitHub provides a user-friendly web interface for managing repositories, issues, and other collaboration features.


After fetching, you can inspect the changes and decide when to merge them into your working branch.

## List 3 other github alternatives

Gitlab

Bitbucket

Luanchpad


## Explain the difference between git fetch and git pull

git fetch and git pull are both Git commands used to update local repository with changes from a remote repository, they have undelining key differences:

## Git Fetch:


Fetching is the operation where you retrieve the latest changes from a remote repository without merging them into your working branch.

After fetching, a developer can inspect the changes and decide when to merge them into your working branch.

Developers prefer using git fetch and git merge separately to have more control over the process and to review changes before merging them into their local branches.

git fetch is used when you want to see what changes are available on the remote repository but don't want to merge them immediately.

It doesn't automatically update your working directory or merge any changes into your local branches.


## Git pull:

Pulling is a combination of fetching and merging. It fetches changes from a remote repository and automatically merges them into your current working branch.

It is more like a shortcut or an easier way of handling both git fetch and merge command

It's a more convenient way to update your local repository and working directory if you're ready to incorporate the changes immediately.


## Explain in simple terms git rebase and the command for it

git rebase is a way to incorporate changes from one branch into another while maintaining a cleaner and more linear project history.
it moves all your feature commit and places it untop of your master commit.  

Git Command

git rebase <branch-name>

## Explain in simple terms git cherry-pick and the command for it 

git cherry-pick is a Git command that allows you to take a specific commit from one branch and apply it onto another branch. It's like picking a commit from one branch
and placing it onto another.

git cherry-pick copies the changes introduced by a specific commit and creates a new commit with those changes in your current branch. If there are conflicts between 
the changes in the cherry-picked commit and the changes in your current branch, Git will notify you, and you'll need to resolve the conflicts manually.
