![Kodestarter](/kodu/kodestarter-logo-white.png)

<center>**Ablaufplanung Coding Camp**</center>

<center>Schwierigkeitsgrad: Anfänger </center>

#<center>Einstiegskurs mit KODU</center>

##Ziele
Den Schülern soll auf spielerische Art und Weise die Bedeutung von Bedingungen (`if then else`) nähergebracht werden, und wie aus mehreren solcher Regeln durchaus komplexe Programme entwickelt werden können. Dazu werden die Grundlagen der visuellen Programmiersprache KODU vermittelt.

Die Schüler lernen, wie sie mit Wenn-Dann Regeln und den entsprechenden grafischen Bausteinen die KODU-Welt nach ihren Vorstellungen verändern können. Als Abschluss-Projekt werden sie den Arkade-Klassiker *Pong* programmieren und in diesem Zusammenhang auch lernen, eine kleine Anforderungsanalyse mittels User Stories zu machen.

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
- Die Kodestarter Beispiel-Programme müssen in das Verzeichnis *<User-Verzeichnis>Saved Games* (Beispiel: C:\Users\john\Saved Games) der Teilnehmer-Rechner kopiert werden, damit diese später geladen werden können.

Optional:
- Whiteboard
- Beamer


#Ablauf
##Tag 1
###Motivation
Den Teilnehmern soll zunächst bewusst gemacht werden, warum es wichtig und sinnvoll ist, Programmier-Kenntnisse zu erlangen. Dazu kann der diesem Kurs beiliegende Foliensatz *Motivation.pptx* verwendet werden. Entsprechende Kommentare und Erklärungen der Folien sind direkt in dem Foliensatz eingebracht.

###Wie funktioniert ein KODU-Programm?
####Ziel
Ziel dieser Lerneinheit ist, dass die Teilnehmer die zugrunde liegenden zwei Wenn-Dann Regeln des Programms
[WennDann](/kodu/WennDann.Kodu2) durch Beobachtung entdecken bzw. selber in natürlicher Sprache formulieren. Ihnen wird dann gezeigt, wie die von ihnen gefundenen und formulierten Wenn-Dann Regeln in der Programmiersprache KODU abgebildet werden.

####Ablauf
1. Den Teilnehmern wird auf einem Beamer ein erstes kleines KODU-Programm in der Ausführung gezeigt([WennDann](/kodu/WennDann.Kodu2)). Steht kein Beamer zur Verfügung, so müssen die Teilnehmer dieses Programm auf ihren Rechnern öffnen und ausführen. Da sie bis dahin noch keinerlei Erfahrung mit KODU haben, muss ihnen eventuell dabei geholfen werden.
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
         Aktion - Objekt - qualifizierende Attribute
            wird kein Objekt angegeben, dann wird dafür implizit das Subjekt verwendet
            (für das die Regel definiert ist)

4. Die Teilnehmer sollen nun selber das Programm modifizieren und im Sinne von *Learning by doing* das KODU-Interface erforschen. Mögliche kleine Äderungen sind beispielsweise
  - Hinzufügen und Ändern von Objekten (Bäume, Farbe und Größe von Objekten ändern, etc.)
  - Hinzufügen oder ändern von Regeln (Wenn der Motorradfahrer einen blauen Baum sieht, dann soll er "WOW!" sagen, etc.)


###Das erste eigene KODU-Programm
####Ziel
Ziel dieser Lerneinheit ist, dass die Teilnehmer ein kleines Programm von Grund auf selber programmieren. Dabei sollen sie sowohl Objekte mit unterschiedlichen Regeln programmieren, als auch lernen, wie man die Welt selber ausgestalten kann (Berge, Flüsse, unterschiedliche Untergründe, etc.).

####Ablauf
Die Teilnehmer können in dieser Einheit ihrer eigenen Kreativität freien Lauf lassen. Erfahrungsgemäß ist dies der Teil des Coding Camps, der den Teilnehmern mit am meisten Spaß bereitet. Es hat sich allerdings bewährt, den Teilnehmern eine erste Aufgabe an die Hand zu geben, die als Startpunkt dient.

1. Die Teilnehmer sollen in das Hauptmenü wechseln und dort den Punkt **Neue leere Welt** auswählen.

2. In diese neue Welt sollen die Teilnehmer einen KODU setzen. Dieser soll nun so programmiert werden, dass er mit den Pfeiltasten bewegt werden kann.

3. Die Teilnehmer können nun die Welt nach ihren Vorstellungen verändern, neue Objekte hineinsetzen und diese programmieren. Du als Lehrer solltest die Teilnehmer natürlich an die Hand nehmen, ihnen bei Problemen helfen und bei Bedarf weitere Anregungen geben, was sie programmieren könnnten. Beispiele dafür wären:

  - Wenn man auf die Taste *R* drückt, soll eine Rakete abgeschossen werden
  - Wenn man die Taste *H* drückt soll das Objekt hochfliegen
  - Alle Objekte, die mich sehen, sollen vor mir weglaufen
  - etc.

4. Zum Abschluss sollen die Teilnehmer dann ihr Programm speichern.

Dies ist dann nach unserer Erfahrung auch schon genug für den ersten Tag! Gut gemacht! :-)

##Tag 2
###Wiederholung
Der 2.Tag startet mit einer Wiederholung des am Vortag Gelernten. Es bietet sich an, dass ein oder mehrere Teilnehmer ihr eigenes Programm vom Vortag der gesamten Gruppe präsentieren. Dabei sollen sie erklären, was in dem Programm so alles passiert, und wie sie diese Regeln umgesetzt haben.

###Abschluss-Projekt: Pong
Das Abschluss-Projekt hat drei Ziele:
- Die Teilnehmer sollen ihre bisher erlernten Kenntnisse in einem komplexeren Projekt anwenden und vertiefen
- Die Teilnehmer sollen anhand einer fertigen Demo des Spiels selber die funktionalen Anforderungen (in Prosa) formulieren und so das anfangs sehr komplex erscheinende Programm in leichter zu bewältigende Teil-Aufgaben unterteilen
- In dem abschließenden Turnier sollen die Jugendlichen einfach Spaß haben und für ihren tollen Einsatz belohnt werden (z.B. kleine Sachpreise)  

####Ablauf
1. Zunächst soll den Teilnehmern eine bereits fertige Demo des Spiels gezeigt werden ([PingPong-Spiel](/kodu/PingPong-Spiel.Kodu2)). Anhand der Demo sollen die funktionalen Anforderungen definiert und aufgeschrieben werden (auf einem Whiteboard oder Beamer). Eine fertige Ausarbeitung dazu findest Du in der Datei *TODO*

2. Nun sollen die Teilnehmer dieses Spiel nachprogrammieren. Als Ausgangspunkt soll die Datei [PingPong-Template](/kodu/PingPong-Template.Kodu2) dienen, die schon eine fertig erstellte Welt bietet, aber natürlich ohne Regeln. Je nachdem wie gut die einzelnen Teilnehmer in den vorherigen Projekten waren, haben sich zwei verschiedene Vorgehensweisen bewährt:

  - Sehr gute Teilnehmer sollen selbstständig versuchen, das Spiel gemäß den funktionalen Anforderungen umzusetzen. Dabei sollen sie jeweils mit der Anforderung beginnen, die für sie am einfachsten zu bewältigen und nachzuvollziehen ist. Deine Aufgabe ist es, diesen Teilnehmern regelmäßig über die Schulter zu schauen, ob alles in die richtige Richtung geht und bei Fragen zu helfen.

  - Teilnehmer, die etwas mehr Unterstützung brauchen, sollten bei der Auswahl und Reihenfolge der umzusetzenden Anforderungen an die Hand genommen werden. Dabei ist es nicht zwingend notwendig, dass alle Anforderungen vollständig umgesetzt werden. Dies ist manchmal aus Zeitgründen oder aufgrund sehr unterschiedlicher Leistungsniveaus der Teilnehmer nicht realistisch. Folgende Reihenfolge schlagen wir vor:

    1. Der Puck soll sich immer geradeaus bewegen
    2. Wenn die Pfeiltasten (hoch, runter) gedrückt werden, dann soll sich der rote Schläger ausschließlich nach oben oder unten bewegen
    3. Wenn die Tasten WASD gedrückt werden, dann soll sich der blaue Schläger ausschließlich nach oben oder unten bewegen
    4. Wenn der Schläger mit dem Puck zusammenstößt, dann soll er den Puck wegtreten
    5. Wenn der rote Schläger 5 rote Punkte hat, dann gewinnt rot
    6. Wenn der blaue Schläger 5 blaue Punkte hat, dann gewinnt blau
    7. Wenn der Puck auf dem roten Land ist, dann soll einmal 1 blauer Punkt addiert werden
    8. Wenn der Puck auf dem blauen Land ist, dann soll einmal 1 roter Punkt addiert werden

3. Diejenigen Teilnehmer, die das Spiel schon fertig umgesetzt haben, dürfen bei Bedarf gerne die anderen Teilnehmer bei der Umsetzung unterstützen.

4. Wenn alle Teilnehmer zufrieden mit ihrer Arbeit sind, dann steht dem Abschluss-Turnier nichts mehr im Wege. Die Spiele werden am basten via Beamer übertragen, ansonsten an einem Computer vor dem für alle Zuschauer Platz ist. Das Turnier folgt einem einfachen KO-System. Die Spielpaarungen können ausgelost werden.

Es sollte klar sein, dass alle Teilnehmer Gewinner sind. Bei der Auswahl der Preise sollte also darauf geachtet werden, dass diese nicht stark voneinander im Wert abweichen. Die Platzierung ist absolut zweitrangig, es geht hier vor allem um den Spaß, sein selbstprogrammiertes Spiel selber mit anderen zu spielen.

Wir von Kodestarter e.V. hoffen, dass Dir dieser Guide hilft, Coding Camps für Kinder und Jugendliche durchzuführen und in ihnen die Begeisterung für IT und Informatik weckst! Wir freuen uns, wenn du uns von deinem Coding Camp erzählst! Berichte und Fotos einfach an [info@kodestarter.org](mailto:info@kodestarter.org) schicken, wir freuen uns!
