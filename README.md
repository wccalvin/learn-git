# Git

## Git vs GitHub vs GitLab

Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories.

Both [GitHub and GitLab](https://about.gitlab.com/devops-tools/github-vs-gitlab.html) are cloud-based hosting service for your git repositories.

## Terminology

### commit
Git thinks of its data like a set of snapshots of a mini filesystem. Every time you commit (save the state of your project in Git), it basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. So a commit is the fundamental unit in Git

![basic workflow](img/repo.png)

### repo

A repository is a directory which contains your project work which are used to communicate with Git. Repositories can exist either locally on your computer or as a remote copy on another computer.

### Working directory

The Working Directory is the files that you see in your computer's file system.

### checkout

A checkout is when content in the repository has been copied to the Working Directory.

### Staging Area / Staging Index / Staging / Index

A file in the Git directory that stores information about what will go into your next commit.

### SHA

"SHA" is shorthand for "Secure Hash Algorithm". It is a 40-character string composed of characters (0–9 and a–f) and calculated based on the contents of a file or directory structure in Git.

### Branch

A branch is when a new line of development is created that diverges from the main line of development. This alternative line of development can continue without altering the main line.
