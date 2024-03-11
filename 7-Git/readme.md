# Cos'è git?
git sistema di versionamento del codice distribuito



# Config
git config --global user.name "Giuseppe Calia"
git config --global user.email "giuseppe.calia@aulab.it"


git config --global user.name
git config --global user.email

# keywords
- repository è una "sorta" di struttura dati (contenitore di dati) che tiene traccia dei cambienti apporti ai file del progetto
- branch una linea di sviluppo del progetto del tempo. Un branch è composto da commits
- commit è una istantanea del progetto



# comandi git
git init

# staging area
git status è una preview (anteprima di stampa) del prossimo commit
git add .

# commit
git log
git log --oneline
git commit -m "descrizione del commit"



# procedura x creare una repository locale
1) creo la cartella del progetto
2) inizializzo la repository con git init
3) inizio lo sviluppo (ad esempio creo il file index.html)

4) git add .
5) git commit -m "messaggino descrittivo"




# ssh keygen
- apro un terminale nella home
- eseguo il comando dando sempre invio:
    ssh-keygen -t rsa
- sarà creata una cartella .ssh contenente la coppia di chiavi
- cd .ssh
- cat id_rsa.pub



# procedura x creare una repository remote (avendo già creato una repo locale)
modifico il nome del branch di default master -> main:
    git branch -M main      
creare un collegamento tra la repo locale e la repo remota:
    git remote add origin urlDellaRepoRemota
faccio l'upload dei commit presenti all'interno del branch main della repo locale all'interno del branch main della repo remota:
    git push origin main