# finding-a-home
Point &amp; Click Adventure Prototype

## Finding a Home – Prototypentwicklung Point & Click
## Projektteam
Teammitglied	Matrikelnummer	Tätigkeitsbereich
Dana-Lucia H Design & Game Design
Mursal D Text & Sound
Soe Ö	Game Design & Text
Leander W	Development

## Gameplay-Video
http://youtube.com/watch?v=OtM3HaeACZM


## Kurzbeschreibung
Bei Finding a Home handelt es sich um ein Point & Click Adventure, das die Zukunfts-Geschichte eines Menschen erzählt, der aufgrund des unbewohnbaren Zustands der Erde ein neues Zuhause im Universum sucht und auf seiner Reise diverse Abenteuer erlebt.

## Inspiration & Referenzen
Imagia 1
Monkey Happy
Stardew Valley
Der kleine Prinz
(siehe auch Projektkonzept)

## Thema
Suche nach neuem Zuhause (was bedeutet Suche, was Zuhause)
altes Zuhause unbewohnbar, ungemütlich, einsam

## Mechaniken (Features, Regeln)
Point and Click, ohne Zeitlimit
Gegenstände sammeln, einsetzen, kombinieren, um neues Zuhause zu erschaffen

## Assets (Characters, Environments)
Maus-Cursor 
drei Planeten als Level (perspektivisch) in unterschiedlichem Look
diverse Planetenbewohner
Monologe, Dialoge

## Emotionen
Entspannung
Ehrgeiz
Neugierde

## Core Loop
Maus bewegen & klicken
Welt erkunden, Geheimnisse und Wege entdecken
(auf-)sammeln, einsetzen, richtig kombinieren

## Game Design Pillars
Exploration
Collection
Combination

## Inhalt & Story
Wir befinden uns im Jahr 2144.
Die Erde, dein Heimatplanet, wurde von den Menschen jahrhundertelang verbraucht, verwohnt, abgenutzt und vermüllt hinterlassen. Zu spät wurde erkannt, wie wichtig es ist, Umwelt und Lebewesen zu respektieren, Ressourcen zu schätzen, selbstlos statt egoistisch zu sein, für das Miteinander zu handeln.

Du, geboren in eine schon kaputte Welt ohne Artenvielfalt und Pflanzen, bist eine*r der letzten, die es irgendwie geschafft haben, zu überleben – doch es wird von Tag zu Tag schwieriger.

Um aus dem ermüdenden Überlebenskampf wieder ein begehrenswertes Leben zu machen, hast du dich dazu entschlossen, ein neues Zuhause auf einem der Nachbarplaneten zu suchen.

Während deiner Reise zu den Nachbarplaneten triffst du auf die unterschiedlichsten Bewohner*innen, die dich dabei unterstützen können alles Nötige für ein geeignetes Zuhause zu finden.

## Settings & Character
Das Spiel ist bezogen auf die Grundidee in mehrere Level bzw. Abschnitte aufgeteilt. Die spielende Person befindet sich dabei in einem Science-Fiction-geprägten Setting, wobei jeder Abschnitt der Geschichte von einem der im Laufe des Spiels bereisten Planeten repräsentiert wird.

Diese stellen jeweils eine sehr bunte Welt mit eigenen Regeln, Objekten und Bewohner*innen dar – kein Planet gleicht dem anderen.

Die spielende Person kann sich mit der von ihr steuerbaren Spielerfigur auf jedem dieser Abschnitte durch verschiedene Räume bewegen, welche jeweils eine eigene Szene darstellen, die auf dem ganzen Bildschirm vollständig dargestellt wird. So ist der gesamte Raum auf einen Blick zu sehen.

Umwelt, Objekte und Charaktere können bekannt aussehen und erdähnliche Eigenschaften mit sich bringen, gleichzeitig aber auch einer fantasiereichen Welt entstammen und neue oder mystische Aspekte mit sich bringen.

Die spielende Person wird sich zunächst auf einem der Planeten wiederfinden, den sie erkunden muss. Durch das Erforschen der Umgebung und Interagieren mit Objekten und Charakteren ergeben sich neue Handlungsstränge und Möglichkeiten. Durch Dialoge mit den Planetenbewohner*innen, die teilweise durch bestimmte Aktionen erst freigeschaltet werden können, erfährt die spielende Person immer mehr über deren Geschichte und Lebenswelt. Durch das Lösen von bestimmten Aufgaben sowie das Entdecken und Erhalten von Objekten werden immer mehr nützliche Erfahrungen und Objekte gesammelt, die einem für das neue Zuhause helfen.

Die durch Umwelt und Bewohner*innen gestellten Aufgaben müssen dabei korrekt gelöst werden, um in der Geschichte und im Gameplay voranzuschreiten.

## Aesthetics
Die Spielwelt beinhaltet eine Weltall-Atmosphäre, vor allem aber eine bunte und fantasievolle Welt auf den unterschiedlichen Planeten. Sie ist geprägt durch erdähnliche Objekte, die sich in Farbgebung und Aussehen letztlich jedoch vom Bekannten unterscheiden. So ist die Spielwelt nie völlig fremd, aber immer neu und eindrucksvoll.

Das Spiel lehnt sich dabei an einen Look von früheren Sierra oder Lucas Arts Point & Click Adventures an, wobei die Spielwelt eher zweidimensional bleibt und eher wenig mit („spielbarer“) Tiefe arbeitet.

Die einzelnen Szenen werden seitlich betrachtet, die Figuren können sich entsprechend vor allem nach links und rechts bewegen (u.U. auch mal nach unten und oben), aber nicht deutlich in einen Raum hinein.

Der Art Style bedient sich dabei an Pixel Art Elementen bei einer (für frühere Verhältnisse) klassischen Auflösung von 320 x 200 px. So sind Charaktere und Spielerfigur ebenso wie die Umwelt aus wenigen Pixeln in recht satten Farben gestaltet. Der Sound hingegen nutzt keine 8-Bit-Sounds oder vergleichbares sondern bedient sich an hochauflösenden Loop-Kompositionen und Sound-Effekten, die abgestimmt sind auf ein futuristisches Erlebnis im Weltraum.

Die Umgebung der einzelnen Räume/Szenen ist weitestgehend statisch, teilweise werden vereinzelte Elemente animiert (Wolken, Glühwürmchen, Sterne o. Ä.).

Die Charaktere werden teilweise mit wenigen Frames animiert, um sie weniger statisch wirken zu lassen. Die Spielfigur erhält neben einer Idle-Animation logischerweise auch eine Walk-Animation, da sich der Character durch die Level bewegen muss.

Neben dem Cursor zum Navigieren, Entdecken, Steuern und Klicken gibt es ein Spielmenü zum Speichern, eines zum Laden, eines zum Beenden, eines zum Beenden oder Neustarten (am Ende des Spiels) sowie das für den Spielverlauf elementare Inventar. Dieses stellt sämtliche Items dar, die im Laufe des Gameplays aufgesammelt oder erhalten werden können.

Ursprüngliche Moodboards und Style-Skizzen können dem Projektkonzept entnommen werden. 

## Technologie & Mechanik
Das Spiel wird umgesetzt für PC (Windows) und mit Adventure Game Studio (v3.5.0) realisiert, einer quelloffenen Spiele-Engine und Entwicklungsumgebung, dessen Programmiersprache an C angelehnt ist.

Gesteuert wird eine Spielfigur mit der Maus, wobei die linke Maustaste zum Laufen und Interagieren dient, die rechte Maustaste zum genaueren „Betrachten“ eines Objekts. Das gesamte Spiel kann mit der Maus gespielt werden, zusätzlich dienen die Tasten F5 zum Aufrufen des Speichern-Dialogs, F7 zum Aufrufen des Laden-Dialogs und ESC zum beenden des Spiels.



Ein Linksklick auf einen leeren Bereich (ein Bereich ohne Character, Objekt oder sonstigem „Hotspot“) führt dazu, dass die Spielfigur zum nächstgelegenen Punkt des begehbaren Bereichs läuft.

Interagiert werden kann, in dem auf einen Character, ein Objekt oder einen Hotspot geklickt wird, alternativ ein Item durch Auswahl und anschließendem Klick auf einen entsprechenden Bereich auf diesen angewendet wird.

Die Mechanik des Spiels folgt also einer klassischen Point-and-Click-Mechanik ohne Zeitlimit, bei der es darauf ankommt Gegenstände zu sammeln, einzusetzen, zu kombinieren und entsprechende Rätsel mithilfe der Hinweise in Form von Dialogen zu lösen.

Im Kern (Core-Loop) geht es darum, dass die spielende Person mit der Maus neue Bereiche erforscht, Gegenstände und Character anklickt, um mehr zu erfahren, Objekte einsammelt oder erhält und diese schließlich einsetzt, um wiederum neue Aktionen und Orte freizuschalten.

Die Hauptpfeiler (Game-Design-Pillars), auf denen das Spiel steht, bestehen also aus dem Entdecken (Exploration), dem Sammeln (Collection) und dem richtigen Kombinieren (Combination).
