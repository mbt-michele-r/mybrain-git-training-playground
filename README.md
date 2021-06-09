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

`git commit -a -m "change Readme update"`

`git push origin branch-name`
