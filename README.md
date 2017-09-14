
Commands
==========



remotes
--------

Clone a repository into a new directory

```
git clone <repository> [<directory>]
```

Add remote to local repository

```
$ git remote add origin https://path/to/git-repository.git
```

List remotes 

```
git remote 

```

Get informations about remote 

```
git config --get remote.<remote>.url
git remote show <remote>
```

Push local to remote
```
git push [-u,--set-upsteam <remote> <branch>]
```

