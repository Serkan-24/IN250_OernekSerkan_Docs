# Git Basics

## Schritt 1
GitHub geöffnet und ein neues Repository erstellt.

## Schritt 2
Repository benannt: IN250_OrnekSerkan_Docs.

## Schritt 3
Datei git_basics.md erstellt.

# Aufgabe 2: Repository klonen

# Aufgabe 3: Markdown Cheatsheet hinzufügen

# Aufgabe 5: Beobachtung
Beim git pull origin main wurden alle Dateien aus dem Remote-Repository in das neue lokale Repository heruntergeladen.
Neuer Branch main wurde erstellt und mit origin/main verknüpft.
Wenn die Änderungen im alten Ordner vorher gepusht wurden, dann werden sie beim git pull in das neue Repository übernommen. Beide Ordner sind dadurch synchron.

# Aufgabe 6: Nutzen von Git + Commit/Push vor der Flucht
### Warum sollte Git in der Softwareentwicklung genutzt werden?
Git hilft dabei, Änderungen an Code sauber nachzuverfolgen, ältere Versionen wiederherzustellen und gemeinsam im Team am gleichen Projekt zu arbeiten, ohne dass etwas verloren geht oder überschrieben wird.  

### Warum bei einem „Feuer“ zuerst Commit → Push → Flucht?
Wenn ein Computer beschädigt wird oder ausfällt, sind die lokalen Änderungen verloren.
Durch Commit und Push werden die Änderungen zuerst gespeichert und dann ins Remote-Repository übertragen. Dadurch ist der Code sicher und kann später wiederhergestellt werden.


## Schritt 2
Änderungen committed mit der Nachricht "Initial commit".

## Schritt 3
Über den Browser überprüft, ob die Datei im Repository sichtbar ist.


```bash
git add .
git commit -m "Initial commit"


## Schritt 1
Markdown-Cheatsheet in das lokale Repository-Verzeichnis kopiert


## Schritt 4
Repository lokal geklont.

```bash
git clone git@github.com:Serkan-24/IN250_OernekSerkan_Docs.git
```

## Schritt 5
Datei `git_basics.md` lokal bearbeitet und gespeichert.

## Schritt 6
Änderungen gestaged und committed.

``` bash
git add git_basics.md
git commit -m "add documentation steps"

## Schritt 7
Änderungen auf GitHub gepusht.

```bash
git push

## Schritt 8
Über den Browser überprüft, ob die Änderungen erfolgreich auf GitHub sichtbar sind.

