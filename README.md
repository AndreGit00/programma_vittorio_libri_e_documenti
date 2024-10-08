# Libreria
Il programma consente un'immediata fruizione e ricerca della documentazione del signor Vittorio.

## Integrazione del progetto Github con NetBeans
L'ambiente di sviluppo NetBeans consente di interagire facilmente con Github per lo scaricamento e la modifica di progetti presenti. Per scaricare un progetto Github in locale, provvedere alla sua modifica e infine confermare la modifica seguire la seguente guida.

### Clonazione di repository
In primo luogo, scaricare in locale il progetto presente utilizzando il menù: TEAM --> GIT --> CLONE.
Nella prima schermata il link da cui prendere il progetto: https://github.com/AndreGit00/Libreria. Confermare le schermate successive.

### Salvataggio locale tramite COMMIT
Al termine delle modifiche, per confermarle eseguire la procedura di COMMIT tramite il menù TEAM --> COMMIT.

### Configurazione di Github e NetBeans
Ora le modifiche sono state salvate in locale. Prima di caricarle su Github, se è la prima volta che si effettua il caricamento, seguire i seguenti due passaggi:
1) Andare sul sito di Github, accedere al proprio profilo e andare sotto il seguente menù: Settings --> Developer settings --> Personal access tokens --> Tokens (classic) --> Generate new token (classic). Nella schermata che compare, in note scrivere "NetBeans" e selezionare tutte le voci presenti nei menù a spunta. Dare al token una scadenza infinita. Una volta generato, salvarlo in un documento poiché non risulterà più reperibile. Su NetBeans, nelle schermate dove richiesti, inserire come di seguito nome utente e password.

```
    User: indirizzo mail.
   
    Password: token di accesso.
```
   
2) Andare, su NetBeans, nel seguente menù: TEAM --> REPOSITORY --> OPEN CONFIGURATION.
Impostare, nelle due voci finali, il nome utente utilizzato su Github e la mail ASSOCIATA, nel seguente modo:

```
    [user]

        name = AndreGit00 (nome utente di Github) 

        email = andre.j5samsung2016@gmail.com (mail di profilo).
```

### Salvataggio delle modifiche su Github tramite PUSH
Ora è possibile eseguire la procedura di PUSH, per riportare in Github tutte le modifiche effettuate in locale, utilizzando il menù TEAM --> REMOTE --> PUSH.

### Aggiornamento programma locale tramite PULL
Un'altra procedura utile è quella di PULL, che consente di aggiornare la versione locale del programma, sulla base delle modifiche caricate da altri utenti su Github, tramite il menù TEAM --> REMOTE --> PULL.
