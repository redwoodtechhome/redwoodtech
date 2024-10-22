# Setup GIT Repositories in Your LAN

## In Remote Node

1.  `ssh <remote_host>`
2.  `mkdir gitrepos`
3.  `cd gitrepos`
4.  `mkdir notes`
5.  `cd notes`
6.  `git init --bare`
7.  `git config --global init.defaultBranch main`
8.  `pwd`

## In Local Node

1.  `mkdir local`
2.  `cd local`
3.  `mkdir notes`
4.  `cd notes`
5.  `git config --global user.name "Chris Jones"`
6.  `git config --global user.email chrisjones@example.com`
7.  `git config --global core.editor nano`
8.  `git init`
9.  `git config --global init.defaultBranch main`
10. `git remote add origin ssh://<user>@<remote_host>/<remote_repository_path>`
11. `nano note1.txt` (Type any text then use, Ctrl+O, Ctrl+X)
12. `git add .`
13. `git commit -a -m 'Initial commit.'`
14. `git push origin main`
15. `git log`
