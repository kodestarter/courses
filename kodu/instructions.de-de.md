![Kodestarter](/kodu/kodestarter-logo-white.png)

<center>**Ablaufplanung Coding Camp**</center>

<center>Schwierigkeitsgrad: 1/3 </center>

#<center>Einstiegskurs mit KODU</center>

##Ziele
Den Schülern soll auf spielerische Art und Weise die Bedeutung von Bedingungen (`if then else`) nähergebracht werden, und wie aus mehreren solcher Regeln durchaus komplexe Programme entwickelt werden können. Dazu werden die Grundlagen der visuellen Programmiersprache KODU vermittelt.

Die Schüler lernen, wie sie mit Wenn-Dann Regeln und den entsprechenden grafischen Bausteinen die KODU-Welt nach ihren Vorstellungen verändern können. Als Abschluss-Projekt werden sie den Arkade-Klassiker *Pong* programmieren.

Es wird keinerlei Vorwissen der Teilnehmer vorausgesetzt.

##Zeitlicher Umfang
Das Coding Camp kann innerhalb von zwei Tagen á 3,5 Stunden durchgeführt werden.

##Voraussetzungen
Es werden Computer benötigt, die die folgenden Minimal-Voraussetzungen erfüllen:
- Microsoft Windows Betriebssystem ab XP (SP3)
- .NET Framework 3.5 oder höher
- XNA Framework 3.1 Redistributable
- Eine Grafikkarte mit DirectX 9.0c und Shader Model 2.0 Unterstützung

Folgende Software muss auf den Computern der Teilnehmer installiert sein:
- KODU (http://www.microsoft.com/en-us/download/details.aspx?id=10056)
- XNA Framework (http://www.microsoft.com/en-us/download/details.aspx?id=21)
- Die Kodestarter Beispiel-Programme müssen in das Verzeichnis TODO der Teilnehmer-Rechner kopiert werden, damit diese später geladen werden können.


#Ablauf
##Tag 1
###Motivation
Den Teilnehmern soll zunächst bewusst gemacht werden, warum es wichtig und sinnvoll ist, Programmier-Kenntnisse zu erlangen. Dazu kann der diesem Kurs beiliegende Foliensatz *Motivation.pptx* verwendet werden. Entsprechende Kommentare und Erklärungen der Folien sind direkt in dem Foliensatz eingebracht.

###Wie funktioniert ein KODU-Programm?
Ziel dieser Lerneinheit ist, dass die Teilnehmer die zugrunde liegenden zwei Wenn-Dann Regeln des Programms durch Beobachtung entdecken bzw. selber in natürlicher Sprache formulieren. Ihnen wird dann gezeigt, wie die von ihnen gefundenen und formulierten Wenn-Dann Regeln in der Programmiersprache KODU abgebildet werden.

1. Den Teilnehmern wird auf einem Beamer ein erstes kleines KODU-Programm in der Ausführung gezeigt(*Motorradfahren und Blinken.Kodu2*). Steht kein Beamer zur Verfügung, so müssen die Teilnehmer dieses Programm auf ihren Rechnern öffnen und ausführen. Da sie bis dahin noch keinerlei Erfahrung mit KODU haben, muss ihnen eventuell dabei geholfen werden.
Das Programm zeigt einen Motorradfahrer der im Kreis um einen KODU fährt.

2. Die Schüler sollen nun beschreiben, was sie sehen. Sie sollen die zugrunde liegende Gesetzmäßigkeit dieses Programms herausfinden und in natürlicher Sprache formulieren.
Das Programm besteht aus drei Regeln:

  - *Wenn der KODU den Motorradfahrer sieht, dann beginnt er zu glühen.*

  - *Wenn der KODU den Motorradfahrer nicht mehr sieht, dann hört er wieder auf zu glühen.*

  - *Der Motorradfahrer soll immer im Kreis fahren (egal was passiert).*

3. Den Teilnehmern wird nun gezeigt, wie die von ihnen entdeckten Gesetzmäßigkeiten bzw. Wenn-Dann Regeln in KODU abgebildet werden. Dabei soll den Teilnehmern die allgemeine Struktur eines KODU-Programms und die Syntax der Wenn-Dann Regeln bewusst gemacht werden:
  - Ein Programm besteht aus einer beliebigen Anzahl an Regeln (oder auch Anweisungen), die alle mehrmals pro Sekunde parallel von dem Computer überprüft werden. Ist der **Wenn-Teil** der Regel wahr, dann wird der **Tue-Teil** der Regel ausgeführt, ansonsten passiert nichts.

   - Soll der **Tue-Teil** einer Regel immer ausgeführt werden, unabhängig von irgendeiner Vorbedingung, dann wird der **Wenn-Teil** einfach leergelassen

   - Eine KODU-Regel folgt meist folgender Struktur:

    **Wenn-Teil**
         Subjekt - Aktion - Objekt - qualifizierende Attribute
            wobei das Subjekt implizit Teil der Regel ist, da die Regel ja für das Subjekt   definiert wird
    **Tue-Teil**
         Aktion - qualifizierende Attribute

4. Die Teilnehmer sollen nun selber das Programm modifizieren und im Sinne von *Learning by doing* das KODU-Interface erforschen. Mögliche kleine Äderungen sind beispielsweise
  - Hinzufügen und Ändern von Objekten (Bäume, Farbe und Größe von Objekten ändern, etc.)
  - Hinzufügen oder ändern von Regeln (Wenn der Motorradfahrer einen blauen Baum sieht, dann soll er "WOW!" sagen, etc.)


###Das erste eigene KODU-Programm
Ziel dieser Lerneinheit ist, dass die Teilnehmer ein kleines Programm von Grund auf selber programmieren. Dabei sollen sie sowohl Objekte mit unterschiedlichen Regeln programmieren, als auch lernen, wie man die Welt selber ausgestalten kann (Berge, Flüsse, unterschiedliche Untergründe, etc.).

Die Teilnehmer können in dieser Einheit ihrer eigenen Kreativität freien Lauf lassen. Erfahrungsgemäß ist dies der Teil des Coding Camps, der den Teilnehmern mit am meisten Spaß bereitet. Es hat sich allerdings bewährt, den Teilnehmern eine erste Aufgabe zu geben, die als Startpunkt dient.

1. Die Teilnehmer sollen in das Hauptmenü wechseln und dort den Punkt **Neue leere Welt** auswählen.

2. In diese neue Welt sollen die Teilnehmer einen KODU setzen. Dieser soll nun so programmiert werden, dass er mit den Pfeiltasten bewegt werden kann.

3. Die Teilnehmer können nun die Welt nach ihren Vorstellungen verändern, neue Objekte hineinsetzen und diese programmieren. Du als Lehrer solltest die Teilnehmer natürlich an die Hand nehmen, ihnen bei Problemen helfen und bei Bedarf weitere Anregungen geben, was sie programmieren könnnten. Beispiele dafür wären:

  - Wenn man auf die Taste *R* drückt, soll eine Rakete abgeschossen werden
  - Wenn man die Taste *H* drückt soll das Objekt hochfliegen
  - Alle Objekte, die mich sehen, sollen vor mir weglaufen
  - etc.

Dies ist dann nach unserer Erfahrung auch schon genug für den ersten Tag! Gut gemacht! :-)

##Tag 2
