# Wie richtet man CLA Assistant ein

## Vorbereitend

- Repo erstellen für das CLA verprobt werden soll
- Bei [CLA Assistant](https://cla-assistant.io/) mit GitHub Account einloggen

## Gist mit Lizenz einrichten

- Mithilfe von [Gist](https://gist.github.com/) soll eine Seite angelegt werden, welches die Contributor Lizenz enthält
- Inhalt soll aus der Datei CLA.md kopiert werden
- Dateiname kann CLA.md sein
- Sobald das Gist eingerichtet ist mit der Lizentdatei, soll im selben Gist eine weitere Datei mit dem namen "metadata" erstellt werden
- Der Inhalt kann aus der Datei mit dem selben Namen aus diesem Repository entnommen werden
- Diese Datei beinhaltet zusätzliche Informationen über den Contributor die ebenfalls gesammelt werden sollen

## CLA mit Repository verknüpfen

- Im CLA Assistant Hauptmenü Button mit `Configure CLA` anklicken
- Repository auswählen
- Gist auswählen
- `Share the Gist` auswählen, damit Benutzer nicht für jedes einzelne Repo die selbe Lizenz akzeptieren müssen
- Button mit dem Text `Link` anklicken

## CLA austesten

- Anderer Account soll einen Pull Request auf das Demo Repo erstellen
- Prüfen ob der Benutzer aufgefordert wird die CLA zu akzeptieren
- Prüfen ob die CLA als Prüfcheck im Pull Request auftaucht
- Prüfen ob Pull Request nicht mergebar ist, bis die CLA akzeptiert wurde

## Weiter Einstellungsmöglichkeiten für ein Repository

- Im Hauptmenü der CLA Assistant ist es möglich noch optionale Einstellungen für den Link zwischen Repository und CLA zu machen
- Zum einen kann eingestellt werden, dass die CLA erst ab einer bestimmten Anzahl von geänderten Zeilen / Datein notwendig wird
- Zusätzlich kann noch ein Link hinterlegt werden für eine Datenschutzerklärung für die persönlichen Daten, die durch die CLA erfragt werden
