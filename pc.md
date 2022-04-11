## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

1. Git is software for tracking changes in any set of files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
2. Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.
3. We create a branch to isolate development work without affecting other branches in the repository.
4. Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
5. git checkout
6. git fetch - only downloads latest changes into the local repository. It downloads fresh changes that other developers have pushed to the remote repository since the latst fetch and allows you to review and merge manually at a later time using git merge. git merge - Merging is Git's way of putting a forked history back together again. git pull - downloads latest changes into the local repository and it also automatically merges change in your working directory. It doesn't give you a chance to review the changes before merging and as a consequence, 'merge conflicts' can and do occur.
7. A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits.
8. The most dirct way to resolve a merge conflict is to edit the conflicted file. Git also has commands to solve merge conflicts