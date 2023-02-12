# Git CLI & remote
- CLI: comand line

### Was ist ein Repository?

Mit dem Begriff **Repository** bezeichnet eine zentrale Ablage für Daten, Dokumente, Programme, Metadaten und Datenmodelle bezeichnet:

## Ein lokales Repository erstellen

- In das Verzeichnis wechseln, das zu einer Repo werden soll
> cd Verzeichnis
- In die Konsole eingeben
> git init

Achtung: Keine Repos in andere Repos einfügen

## Die drei Zustände einer Datei

- **Modefied** bedeutet, dass eine Datei geändert, aber noch nicht in die lokale Datenbank eingecheckt wurde.
- **Staged** bedeutet, dass eine geänderte Datei in ihrem gegenwärtigen Zustand für den nächsten Commit vorgemerkt ist.
- **Commmited** bedeutet, dass die Daten sicher in der lokalen Datenbank gespeichert sind.

## Ein lokales Repository committen

- Alle geänderten Daten und deren Status auflisten
> git status

- Alle geänderten Daten in den Staging-Bereich hinzufügen
> git add .

- Ein Commit mit der zugehörigen Nachricht erstellen
> git commit -m "Commit-Nachricht"

## Lokales Repository mit remote Repository verknüpfen

- Ein neues Repository bei GitHub erstellen
- Dann die drei Komandozeilen kopieren
> git remote add origin git@github.com:GitHubUsername/repository-name.git  
> git branch -M main  
>git push -u origin main
- Und die Zeilen im Terminal einfügen

## Remote Repository klonen

> git clone url
  
 Auf SSH achten!
 
 ## Lokale und remote Repositorys synchronisieren
 
 > git push  

 Lokales Repository hochladen   

 > git pull  

 Remote-Repository runterladen
