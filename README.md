# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Team 

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23/08/2022    | 0.0.1   | Ich habe heute gelernt was User-Stories sind.   |
|  30/08/2022     |   0.0.2   | Ich habe heute das Spiel so gut wie fertig gemacht. Dazu habe ich noch die Farbe der SChrift geändert.    |
| 06/09/2022      | 0.0.3   | Heute habe Ich das Programm fertig gestellt. Es funktioniert alles sehr gut. Am Ende des Programms habe ich einen Code geschrieben wo auswählen kann ob man das Spiel nochmals spielen will oder nicht.       |

## 1 Informieren

### 1.1 Ihr Projekt

Ich werde ein "Zahlguesser" Spiel programmieren.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |   muss  | Funktionale Anforderungen     | Als User möchte ich eine Zahl eingeben, damit das Programm sagt ob meine Zahl zu hoch oder zu niedrig ist, damit ich sehe was für eine Zahl ich eingeben muss  |
| 2 |   muss    | Funktionale Anfroderungen     |  Als User möchte ich dass das Programm die eine Zahl von 1-100 auswählt, damit es nicht immer das gleiche ist.|
|3| kann| qualitätsanforderung | Als User möchte ich dass das Programm leicht zu verstehen ist, damit der User keine Probleme hat. |
|4|kann|funktionale Anforderungen| Als User möchte ich am Ende gefragt werden, ob ich das Spiel nochmals spielen will, damit ich es nicht immer ganz neustarten muss.|

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Das Programm ist gestartet       |     Der User soll eine Zahl zwischen 1-100 eingeben    |   Das Programm soll sagen ob eingegebene Zahl zu klein oder zu hoch ist.         |
| 2.1  | Das Programm ist gestartet     | Das Programm soll eine Zahl zwischen 1-100 zufällig auswählen        |       Es soll die ausgewählte Zahl speichern und nicht anzeigen.            |
|3.1| Das Programm ist gestartet |  Der User gibt eine Zahl ein  | Es soll alles untereinander geschrieben sein|
|4.1|Das Programm ist gestartet|Der User hat die richtige Zahl erraten| Das Program soll den User fragen ob er nochmals spielen will.|

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |     Xavier Nursiwat    |   Während des Spiels wird gezeigt ob die eingegeben Zahl zu gross oder zu klein ist.      |    50  min         |
| 2.A  |       |    Xavier Nursiwat       |    Das Program soll eine zufällige Zahl ziwschen 1-100 auswählen. Ich werde also einen Random Number Generator schreiben         |     60 min          |
|3.A||Xavier Nursiwat| Ich werde das so prgrammieren das es in der Ausgabe alles schön untereinander steht.|10 min|
|4.A||Xavier Nursiwat|Am Ende des Programs werde ich noch schreiben ob man das Spiel nochmals spielen will.|40 min|

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   30/08/2022    |  Xavier Nursiwat        |     50 min     |     90 min              |
| 2.A  | 30/08/2022      | Xavier Nursiwat          |   60 min            |       70 min            |
|3.A|06/09/2022| Xavier Nursiwat| 10 min | 15 min |
|4.A| 06/09/2022| Xavier Nursiwat| 40 min | 50 min|

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |    13/09/2022   |  Das Program sagt ob die eingegebene Zahl zu gross oder zu klein ist.     |  Xavier Nursiwat      |
|2.1  |13/09/2022       | Das Program wählt nach jedem Spiel eine andere Zahl aus.  |Xavier Nursiwat        |
|3.1| 13/09/2022| Das Program zeigt alles untereinander an.| Xavier Nursiwat|
|4.1|13/09/2022| Nach dem der User fertig gespielt hat, wird gefragt ob man nochmal spielen will| Xavier Nursiwat|
 
✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    | das Programm fragt die Zahl ab.             |croissant         | es teilt mit das die Eingbabe falsch ist.                  |Es teilt mit das die Eingabe falsch ist.                      |
|II   | das Programm fragt die Zahl ab.             |120         |Das Programm teilt mit das die Zahl zu gross wahr                   |Es teilt mit das die Eingabe falsch ist.                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
