# I file di template #
Queste istruzioni sono relative alla macchina "desktop" del laboratorio virtuale.

Per svolgere l'attività di laboratorio digitare, in una console della macchina virtuale, i seguenti comandi:

```
#!bash

$ cd
$ . Flask/bin/activate
$ git clone git@bitbucket.org:augusto_ciuffoletti/lab_flask_3.git
$ cd lab_flask_3
$ export FLASK_APP=login.py
$ flask run --host=0.0.0.0
```

Dal computer host, quello reale, aprite il browser e digitate la url:

```
http://192.168.5.2:5000
```

(o sostituite 192.168.5.2 con l'IP della macchina virtuale *desktop*).

## Esercizio ##

Create una nuova route che risponde al GET restituendo un documento html contenuto in un template