# LA1600
# Projekt-Dokumentation


Feigen Martullo Sivickas Suganthasri
| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|11.05.2023| 1.0.0   | Wir haben Kapitel 1 bis 4 abgeschlossen. |

## 1 Informieren

### 1.1 Ihr Projekt


Eine Website zu erstellen welche einem eine Auswahl an Spielen gibt welche man spielen kann.

Wir möchten eine Website erstellen, die den User Zugriff hat, diese Spiele zuspielen. Dabei werden wir mehr mit HTML und CSS arbeiten und somit auch kennenlernen, wie Darkmode, Pop-out und animationen gehen. 

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
|     |                 |      | Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️ |
|1| kann|Qualität| Als Spieler möchte ich, dass sich auf der Website Animationen befinden, damit die website noch einen spielerischen Touch bekommt.|
| 2 |muss |   Funktional   | Als ein Spieler möchte ich, dass es verschiedene Spiele gibt, damit es mehrere Wahlen habe zum Spielen.  |
| 3 | muss  | Qualität |Als ein Spieler möchte ich, dass es ein sinnvolles Layout hat, damit man sich gut auf der Seite zurecht findet |
| 4 | muss   | Funktional  | Als ein Spieler möchte ich, dass es ein Button gibt, damit das automatisch den gewünschten Spiel führt.|
| 5 | muss| Qualität  |Als ein Spieler möchte ich, dass es man auf Dark-Mode wechseln kann, damit ich meine Augen schonen kann |
|6| kann| Qualität|Als Spieler möchte ich, dass die Spiele in Kategorien unterteilt sind, damit ich mich besser zurecht finde|
|7|kann|Qualität|Als Spieler möchte ich, dass ich mir Beschreibungen zum Spiel anschauen kann, damit ich Zeit bei der Auswahl sparen kann|
|  |                 |      |                                    |
|  |                 |      |                                    |

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
|1.1	|Die Website wird geöffnet|	-	|Animationen sind auf der Website sichtbar|
|2.1	|Die Website wird geöffnet|	-	|Es werden verschiedene Spiele auf der Website angezeigt|
|3.1|	Die Website wird geöffnet|	-	|Das Layout der Website ist übersichtlich und benutzerfreundlich|
|4.1	|Ein Spiel wird ausgewählt	Button| "Spiel starten" wird geklickt	|Das ausgewählte Spiel wird automatisch gestartet|
|5.1	|Die Website wird geöffnet	|Button "Dark-Mode" wird aktiviert	|Das Design der Website wechselt in den Dark-Mode|
|6.1|	Die Spiele sind auf der Website sichtbar|	-	|Die Spiele sind in verschiedene Kategorien unterteilt|
|7.1	|Ein Spiel wird ausgewählt|	-	|Eine Beschreibung des Spiels wird angezeigt|

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 3 Anwendungsfällen ein; und eine Skizze davon, wie Ihre Netzseite aussehen sollte.
![Skizze](https://github.com/GM21GM/LA1600/assets/111046257/dee8f6dc-a94c-4cca-8c8c-7acacf3f2b2c)

![LA1600 Use-Case](https://github.com/GM21GM/LA1600/assets/111045891/9f09edb1-d623-471e-9af4-cbc3bc5d7e2e)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.  | 25.05.2023 | Sathana | Animation erstellen | 60 min |
| 2.  | 11.05.2023 | Benas | Grobe Website oder Test Website erstellen | 30 min |
| 2.A | 18.05.2023 | Benas | Games hinzufügen | 50 min |
| 3.  | 18.05.2023 | Alle | grobe Layout | 55 min |
| 3.A | 18.05.2023 | Sathana | Design Layout | 40 min  |
| 4.  | 18.05.2023 | Giuliano | Button Erstellen | 30 min |
| 4.A | 25.05.2023 | Alle | Code für automatische Führung |  45 min  |
| 5.  | 25.05.2023 | Giuliano | Dark Mode | 50 min |
| 6.  | 25.05.2023 | Benas | Unterteilung | 40 min |
| 7.  | 25.05.2023 | Sathana | Game pop-out | 45 min |
| 7.A | 25.05.2023 | Giuliano | Beschreibung für Games | 45 min |


Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.
Wir haben entschieden, dass wir eine Game Website mit HTML5 games und mit der <embed> funktion erstellen.
Wir haben auch entschieden, dass wir seperat einen Mobile und einen Desktop Layout erstellen, die beide sowohl light mode, als auch dark mode haben werden.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| 1.  | 11.05.2023 | Sathana | 60 min| noch nicht fertig |
| 2.  | 11.05.2023 | Benas | 30 min | 45 min |
| 3.  | 31.05.2023 | Alle | 55 min | 50 min |
| 7 | 31.05.2023   | Sathana | 45 min      |  50 min          |


✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
