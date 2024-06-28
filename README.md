<h2> 1-) About The Project</h2>
The repository is created to learn GitHub commands.

<h2> 2-) Mostly Used  Github Commands</h2>
Here is added my most commonly used GitHub commands.
<br>

| Git Commands                                               |  Explanations                                                                                                                                                |
| ---------------------------------------------------------- |:------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| git branch Feature1                                        | creates a new branch named "Feature1".                                                                                                                       |
| git switch Feature1                                        | switches the current branch to "Feature1". (Feature1 branch must be created to use this command.)                                                            |
| git checkout -b Feature2                                   | creates a new branch named "Feature2" and switches the current branch to "Feature2".                                                                         |
| git checkout Feature2                                      | switches the current branch to "Feature2". (Feature2 branch must be created to use this command.)                                                            |
| git merge  Feature3                                        | merges "Feature3" branch into the current branch. if there are any conflicts, they need to be resolved.                                                      |
| git add file1                                              | adds the "file1" to staging area.                                                                                                                            |
| git add .                                                  | moves all files to the staging area from the unstaging area.                                                                                                 |
| git reset                                                  | moves all staging files back to the unstaged area, referencing them to the last commit.                                                                      |
| git reset --hard                                           | discards all staged and unstaged changes, reverting everything back to the last commit.                                                                      |
| git commit -m "My Message"                                  | commits all staged files to the local repository with the message "My Message".                                                                             |
| git commit --amend  -m "New Message"                       | updates last commit. If there are new staged files, they will also be added to the local repository. The commit message will be updated to "New Message".    |
| git remote add origin <github_repository_http_address>     | adds remote area to push the project.                                                                                                                        |
| git push origin feature                                    | pushes the local repository's "feature" branch to the remote GitHub repository.                                                                              |
