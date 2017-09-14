
---

What ist git?
===============

* the most widely used modern version control system in the world today
* originally developed in 2005 by Linus Torvalds

* Distributed Version Control System (DVCS)


---

What is DVCS?
-------------

* Centralized version control systems (CVCS) focuses on synchronizing, tracking, and backing up files.
* Distributed version control systems (DVCS) focuses on sharing changes; every change has a guid or unique id.
* Recording/downloading and applying a change are separate steps (in a centralized system, they happen together).
* Distributed systems have no forced structure. You can create “centrally administered” locations or keep everyone as peers.
* DVCS new terminology
    * Pushes refer to sending a change to another repository (permissions may be required)
    * Pulls refer to grabbing a change from a repository

--- 

Advantages
----------------

* Everyone has their own local sandbox.
* git works offline.
* git is fast.
* Branching and merging is easy.


---

Disadvantages
--------------

* You still need a backup.
* You still want a machine to push changes.
* There’s not really a “latest version”
* There aren’t really revision numbers.

--- 

git Basics
===========

---

---

Work with remotes
===================

---

clone repository 
-----------------

```bash

$ git clone https://path/to/git-repository.git
$ ls
git-repository

```

---

add user-credentials 
--------------------

** either **

add ssh-key to repository (webinterace)

** or **

```
git config [--global] credential.helper "<helper> [<options>]"
```

---

add remote and push local repository 
--------------------------------------

```bash

$ git remote add origin https://path/to/git-repository.git
$ git push -u origin master 

```
---

get information about remotes 
--------------------------------

```bash
$ git remote 
origin
$ git config --get remote.origin.url
https://path/to/git-repository.git
$ git remote show origin
* Remote-Repository origin
  URL zum Abholen: https://path/to/git-repository.git
  URL zum Versenden: https://path/to/git-repository.git
  Hauptbranch: master
  Remote-Branch:
    master gefolgt
  Lokaler Branch konfiguriert für 'git pull':
    master führt mit Remote-Branch master zusammen
  Lokale Referenz konfiguriert für 'git push':
    master versendet nach master (aktuell)
```

---


