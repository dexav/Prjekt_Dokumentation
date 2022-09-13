# Projekt-Dokumentation


Xavier Nursiwat

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 23/08/2022    | 0.0.1   | Ich habe heute gelernt was User-Stories sind.   |
|  30/08/2022     |   0.0.2   | Ich habe heute das Spiel so gut wie fertig gemacht. Dazu habe ich noch die Farbe der SChrift geändert.    |
| 06/09/2022      | 0.0.3   | Heute habe Ich das Programm fertig gestellt. Es funktioniert alles sehr gut. Am Ende des Programms habe ich einen Code geschrieben wo auswählen kann ob man das Spiel nochmals spielen will oder nicht.       |
|13/09/2022|1.0.0| Projektabgabe|

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


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Das Programm ist gestartet       |     Der User soll eine Zahl zwischen 1-100 eingeben    |   Das Programm soll sagen ob eingegebene Zahl zu klein oder zu hoch ist.         |
| 2.1  | Das Programm ist gestartet     | Das Programm soll eine Zahl zwischen 1-100 zufällig auswählen        |       Es soll die ausgewählte Zahl speichern und nicht anzeigen.            |
|3.1| Das Programm ist gestartet |  Der User gibt eine Zahl ein  | Es soll alles untereinander geschrieben sein|
|4.1|Das Programm ist gestartet|Der User hat die richtige Zahl erraten| Das Program soll den User fragen ob er nochmals spielen will.|


### 1.4 Diagramme


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |     Xavier Nursiwat    |   Während des Spiels wird gezeigt ob die eingegeben Zahl zu gross oder zu klein ist.      |    50  min         |
| 2.A  |       |    Xavier Nursiwat       |    Das Program soll eine zufällige Zahl ziwschen 1-100 auswählen. Ich werde also einen Random Number Generator schreiben         |     60 min          |
|3.A||Xavier Nursiwat| Ich werde das so prgrammieren das es in der Ausgabe alles schön untereinander steht.|10 min|
|4.A||Xavier Nursiwat|Am Ende des Programs werde ich noch schreiben ob man das Spiel nochmals spielen will.|40 min|

Total: 
160 min

## 3 Entscheiden



## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |   30/08/2022    |  Xavier Nursiwat        |     50 min     |     90 min              |
| 2.A  | 30/08/2022      | Xavier Nursiwat          |   60 min            |       70 min            |
|3.A|06/09/2022| Xavier Nursiwat| 10 min | 15 min |
|4.A| 06/09/2022| Xavier Nursiwat| 40 min | 50 min|



## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |    13/09/2022   |  Das Program sagt ob die eingegebene Zahl zu gross oder zu klein ist.     |  Xavier Nursiwat      |
|2.1  |13/09/2022       | Das Program wählt nach jedem Spiel eine andere Zahl aus.  |Xavier Nursiwat        |
|3.1| 13/09/2022| Das Program zeigt alles untereinander an.| Xavier Nursiwat|
|4.1|13/09/2022| Nach dem der User fertig gespielt hat, wird gefragt ob man nochmal spielen will| Xavier Nursiwat|
 


### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    | das Programm fragt die Zahl ab.             |croissant         | es teilt mit das die Eingbabe falsch ist.                  |Es teilt mit das die Eingabe falsch ist.                      |
|II   | das Programm fragt die Zahl ab.             |120         |Das Programm teilt mit das die Zahl zu gross wahr                   |Es teilt mit das die Eingabe falsch ist.                      |



## 6 Auswerten

