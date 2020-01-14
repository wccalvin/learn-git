# Command Reference

## First time Git Setup

- Setup user name and email in the ~/.gitconfig

  `git config --global user.name "wccalvin"`

  `git config --global user.email clayton.calvin@gmail.com`

- If a default text editor should be setup when Git needs you to type in a message

  `git config --global core.editor emacs` [default: vim]

## To pull an existing repository to update modified changes

- Create an empty git repository or reinitialize an existing one

  `git init`

- Fetch from and integrate with another repository

  `git pull https://github.com/user.name/repo.git`

- Make required changes to the files.

- Add file contents to the index.

  `git add <file name>`

- Record changes to the repository

  `git commit -m "message"`

- Manage set of tracked repositories

  `git remote show origin`

  `git remote add origin https://github.com/user.name/repo.git`

- Update remote refs along with associated objects

  `git push origin master`
