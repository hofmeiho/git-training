
Commands
==========

git config
-----------

set user credentials

either:
    add ssh-key to repository (webinterface)

or:

```
git config [--global] credential.helper "<helper> [<options>]"
```

helpers:
    * cached 
    * store
    * <platform-specific>

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

Update remotes 

```
git fetch [-all]
```

checkout, branching and merging  
--------------------------------

create new branch

```
git branch <branchname> [<start-point>]
```

checkout branch

```
git checkout <branch>
```

create and checkout new branch

```
git checkout -b <new_branch>
```

delete branch locally

```
git branch -d,--delete <branch>
```

delete branch remote 

```
$ git push origin -d,--delete <branch_name>
```

rename branch 

```
git branch -m,-M [<oldbranch>] <newbranch>
```

merge one branch into other

```
git merge <branch-to-merge>
```

tags
-----

list tags 

```
git tag -l,--list
```

create tag

```
```

delte tag
```

```

exploring history 
-----------------

