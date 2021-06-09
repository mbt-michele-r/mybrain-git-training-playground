# mybrain-git-training-playground
Training playground to test Git basic workflow for a small team use case.

The first step is to clone a repository. To clone a repository go to the Github page, look for the green button and copy
the link (HTTP or SSH).
Then go in the folder in which you want to clone the project, open Git Bash (or the terminal app of your preference) and 
run the following command:

`git clone git@github.com:mbt-michele-r/mybrain-git-training-playground.git`

This will create a folder with the project name. If you are using a standard Unix shell this command will move your
cursor inside the folder:

`cd my-project-folder`

`git status`

`git add file-name`

`git commit -a -m "this is just a sample message"`

Before pushing your changes, check that you are up-to-date with the repository using one of the following commands:

- `git pull` : pulls all the changes from the remote repository and automatically tries to merge them in the local repository
- `git fetch` : fetches all the changes from the remote repository, but will not try to merge them in the local repository

If you use `git fetch` then you are supposed to manually merge the remote changes with your local repository by launching:

`git merge origin/branch-name` (in our case branch-name is 'main')

`git push origin branch-name`


`gitk --all`