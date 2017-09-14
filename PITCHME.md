

--- 

clone repository 
-----------------

```bash

$ git clone https://path/to/git-repository.git
$ ls
git-training

```

add remote and push local repository 
--------------------------------------

```bash

$ git remote add origin https://path/to/git-repository.git
$ git push -u origin master 
$ git remote 
origin
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