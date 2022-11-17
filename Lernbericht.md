Wir haben ein Anmeldesortierer für Workshops erstellt

## Was habe ich gelernt?

Wir haben gelernt, wie man eine Liste erstellt, verwendet und sortiert.

## Beschreibung
Von **allen** nützlichen Funktionen, die wir an der BBBaden in C# gelernt haben, sind **Listen** die nützlichsten.

Bis jetzt haben wir nur Arrays gebraucht, die eine grauenhafte Limitierung haben.

Arrays sind zwar sehr leicht zu erstellen, doch ihre limitierte Länge, die vorher definiert werden muss, beschränkt unsere Flexibilität, beliebig lange Textdateien einzulesen.

In der folgenden Darstellung sehen Sie die Limitierung von Arrays. Wir können in dieser Darstellung nicht mehr als 5 Wörter in der Textdatei haben, ohne dass wir einen Fehler erhalten.

![Hier ist eine Darstellung unserer Schmerzen](https://user-images.githubusercontent.com/111045604/202402305-82e71f6f-1091-4fad-a570-905596083988.png)

Nun kommen ***die Listen*** ins Spiel. Listen sind zwar ein bisschen schwieriger zu erstellen, doch es lohnt sich in vielen Fällen, so wie in diesem Fall.

Die Länge von Listen ist unbegrenzt, man kann in eine Liste beliebig viele Variablen hinzufügen, wenn diese Variabel vom gleichen Datentyp ist. Man kann auch wie im Array eine Liste in eine Liste einfügen!

So erstellt man eine Liste, die zum Beispiel emails beinhalten soll :

``` csharp
    List<string> emails = new List<string>();    //Ich erstelle hier eine neue Liste vom Datentyp 'string'
``` 

Man kann auch mit ```emails.Add()``` später Variabeln einfügen.

Damit haben wir jetzt gelernt, wie man eine Liste erstellt, doch wie verwendet man Listen?

Die Antwort : Genau gleich wie Arrays! Listen funktionieren, bis auf die Länge und Erstellung, komplett gleich wie Arrays!

Man ruft einfach die Elemente in unserem Fall so auf : ```emails[i]```

Hier sieht man, wie ich ein Element (A) in die List hinzufüge und auch dannach aufrufe ('beispiel' ist der Name des Arrays) :

![image](https://user-images.githubusercontent.com/111045604/202408873-f9fa6310-484e-42c1-8f8f-4bb4aeda3e4d.png)

Wie erwartet, druckt das Programm dann den Buchstaben A:

![image](https://user-images.githubusercontent.com/111045604/202409327-5375dec0-2a23-45cc-a10c-7eb24bcf148f.png)



***Wichtig!***
*Es hat aber auch kleine Unterschiede, wie das Zählen der Elemente in einer Liste. Bei Arrays nutzt man arrayname.Length, während man bei Listen listenname.Count nutzt.*

## Verifikation

Wir haben ober erklärt, was die Vorteile von Listen gegenüber Arrays sind. Wir haben auch oben mit den Bildern und Code-Fetzen gezeigt, wie man Listen erstellt und verwendet.

# Reflexion zum Arbeitsprozess

👍 Wir haben sehr konzentriert und zielgerichtet gearbeitet.

👎 Wir habe eine schlechte Planung gemacht und sind schliesslich mit dem Programm nicht fertiggeworden, wir haben auch nicht eine so gute Arbeitseinteilung gemacht, also es hat nicht jeder programmiert.

**VBV**: Wir sollten nächstes Mal besser und mehr miteinander kommunizieren und besser planen und organisieren, es sollten auch alle beim Programmieren mitmachen, damit sie auch etwas lernen.
