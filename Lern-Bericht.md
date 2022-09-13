# Lern-Bericht
Xavier Nursiwat

## Einleitung

Im Lernatalier habe ich einen Auftrag bekommen, einen Zahlenratespiel in C# zu programmieren.

## Was habe ich gelernt?

Während dem Programmiern habe ich folgendes gelernt: Ich habe gelernt dass man die Farbe von der Schrift und vom Hintergrund ändern kann. 

## Beschreibung

Während dem Programmieren hat alles mehr oder weniger gut geklappt, aber in der Ausgabe sah alles so langweilig aus. Also habe ich die Codes von meinen Mitschülerns angeschaut und habe bei einem gesehen dass seine Schrift eine andere Farbe hat. Also habe ich im Internet rechechiert wie man das macht und habe es selber in meinem Code asuprobiert. Es ist recht simpel und man kann jede Zeile individuell entscheiden welche Farbe die haben soll. Ich habe noch versucht den Hintergrund zu ändern aber es sah dann nicht so toll aus. Am Ende entschied ich mich, wenn man die falsche Zahl eingegeben hat wird die Schrift rot und wenn man es richtig erraten hat wird die Schrift grün. 
![ezgif com-gif-maker](https://user-images.githubusercontent.com/110892637/189845970-8c21d873-3151-459a-a725-112a25e1a540.gif)

```C#
  else if (Guess > RNumber)
                        {
                            Console.ForegroundColor = ConsoleColor.Red;
                            Console.WriteLine("Deine Nummer ist zu gross. Versuchs nochmal:");

                        }
                        else if (Guess == RNumber)
                        {


                            Console.ForegroundColor = ConsoleColor.Green;
                            Console.WriteLine("Glückwunsch, du hast es richtig erraten!");
                            Console.ReadLine();
                            Console.WriteLine("Willst du nochmals spielen? [y/n]");
                            nochmal = Console.ReadLine();

```

Mit Console.ForegroundColor kann ich bestimmen welche Farbe die Schrift haben soll.


## Verifikation

Text: Es zeigt wie ich es gelernt habe und wie ich es angewendet habe.

Gif: Es zeigt die Ausgabe von meinem Programm und die verschiedenen Schriftfarben.

Code: Es zeigt wie ich die Fuktion im Code benutzt habe.

# Reflektion zum Arbeitsprozess

Was gut lief: Ich konnte sehr schnell und konzentriert arbeiten. Vorallem als ich zu Hause gearbeitet habe hatte ich meine Ruhe und konnte sogar viel besser arbeiten als im Schulzimmer.
Es hat mir beim programmieren viel Spass gemacht.


Was nicht so gut lief: Ich hatte nich so eine gute Planung. Ich habe teilweise wichtige Sachen vergessen zu machen und habe es spät gemerkt. 

**VBV**: Nächstes Mal eine richtige Planung machen damit nichts vergessen geht.


