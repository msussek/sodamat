# SodaMat - der freie DIY Getr�nkeautomat zum Bezug von Mischgetr�nken aus Wasser und Sodastream Sirup 

<img src="img/title.jpg" width="90%"/><br/>

SodaMat ist ein selbst gebauter Getr�kemischautomat, der sowohl aus 3D gedruckten Teilen als auch aus leicht verf�gbaren Komponenten besteht.

Ziel des Projektes ist es, eine Maschine zu bauen, die auf Knopfdruck die gew�nschte Menge eines im richtigen Verh�ltnis fertig gemischten Getr�nks aus aufgesprudeltem Wasser und Sirup zubereitet.

Wir stellen unser Design des Getr�nkeautomats unter Open Source und beschreiben hier den Aufbau, so dass ihn einjeder f�r nicht-kommerzieller Zwecke Lizenzkostenfrei nachbauen kann. 

## Videos

__Schaltung__

In diesem Video zeige ich kurz die Funktionsweise der Schaltung auf einem Breadboard.

https://youtu.be/glGSpBsMzlo


__Nach Einbau der Elektrischen Komponenten__

Dieses Video zeigt einen Zwischenstand beim Aufbau des Getr�nkeautomats, als die elektrischen Komponenten wie Pumpen, Taster und das Potentiometer bereits fertig in das Geh�use eingebaut wurden.

https://youtu.be/BnMTtF5-dhc

__Erster Funktionstest mit echtem Sirup__

Dieses Video zeigt den ersten Funktionstest des Automaten nach Einbau und Anschluss aller Komponenten.

https://youtu.be/NOZfXYWacTg

## Features

- Besitzt einen 4,2 Liter Vorratsbeh�lter f�r pures, aufgesprudeltes Wasser
- Bietet ausreichend Platz f�r den Anschluss von bis zu 6 verschiedenen Sodastream Sirup-Beh�ltern
- Mischverh�ltnis durch Drehzahlregelung der Sirup-Pumpen �ber Potentiometer variabel einstellbar
- Leicht nachzubauen, da ausschlie�lich 3D gedruckte Teile sowie leicht verf�gbare, kosteng�nstige Kaufteile verwendet wurden 
  - Ikea Samla Kiste als Geh�use
  - Ikea 365+ Beh�lter als Wasservorrat
  - Micro Luftpumpen als Sirup-Luftdruckpumpen
  - Aquariumpumpe als Wasserpumpe
  - Silikonschl�uche
- Gute Hygiene / Lebensmittelvertr�glichkeit
  - Alle Lebensmittelber�renden Teile sind zertifiziert Lebensmittelecht
  - Sirup kommt nicht mit der Pumpe in Kontakt, da Pumpe nur Druckluft erzeugt und dadurch den Sirup �ber ein Steigrohr aus dem Beh�lter heraus verdr�ngt
  - Leicht zu reinigen, Wasserbeh�lter entnehmbar, alle Lebensmittelber�renden Komponenten k�nnen mit Seifenwasser durchgesp�hlt werden
- Leicht zu transportieren, alle Komponenten finden in der Kiste Platz
- Erweiterbare und leicht modifizierbare Plattform
  - Modulares Design erlaubt Austausch einzelner Komponenten z. B. 
  - Ersatz der Luftdruckpumpen durch Peristaltikpumpen m�glich
  - Austausch der analogen Drehzahlregelung durch PMW �ber Microcontroller m�glich
  - W�gzellen / F�llstandssensoren / Durchflusssensoren k�nnen nachger�stet werden

## Ben�tigte Teile

- 1x Ikea Samla Box mit Deckel 22 Liter als Geh�use
  - https://www.ikea.com/de/de/p/samla-box-mit-deckel-transparent-s79850875/
- 1x Ikea 365+ Vorratsbeh�lter mit Deckel 4,2 Liter als Wasservorratsbeh�lter (Deckel ist optional, erleichtert jedoch den Transport)
  - https://www.ikea.com/de/de/p/ikea-365-vorratsbehaelter-mit-deckel-rechteckig-kunststoff-s59276822/
- 1x DC Netzteil 9 Volt oder 12 Volt mindestens 1500 mA
- 1x Aquarium Tauchpumpe als Wasserpumpe mit mindestens 240 L/h Durchfluss
  - https://www.amazon.de/gp/product/B07R8SLQS7
- 6x Mini Luftpumpen 6 Volt als Sirup Druckluftpumpen
  - https://www.amazon.de/gp/product/B07BY4LP22
  - https://de.aliexpress.com/item/32852470081.html
- 6x Taster / Push Buttons f�r das Bedienfeld
  - https://de.aliexpress.com/item/4000164264475.html
- 1 Meter Silikonschlauch 7 x 10 mm f�r Wasserpumpe 
  - https://www.amazon.de/gp/product/B06XW5NYZ1
- 5 Meter Silikonschlauch 3 x 5 mm als Luftdruckschlauch und als Steigleitung f�r Sirup
  - https://www.amazon.de/gp/product/B01N2GW7PX
- 1x N-Kanal Mosfet zum Beispiel Infineon IRF740PBF oder Infineon IRFP064N oder Infineon IRFP1405PBF
  - https://de.aliexpress.com/item/32907153234.html
- 1x Potentiometer 4,7 kOhm 
  - https://www.amazon.de/gp/product/B07M5MB2M5
- 6x Diode 1 Ampere zum Beispiel 1N4007
  - https://www.amazon.de/gp/product/B07JGRXJQ5
- 1x Lochrasterplatine
  - https://www.amazon.de/gp/product/B078HV79XX
- 16x Zylinderschrauben M3 x 10 mm und Muttern (optional dazu U-Scheiben)
- Optional Madenschraube M5 zum Festklemmen der Potentiometer-Kappe
- 4x Sekkopfschrauben M3 x 10 mm und Muttern (optional dazu U-Scheiben) f�r Bedienfeld mit Getr�nke-Labels
- Optional JST-Stecker + Crimpzange zum Herstellen von Steckanschl�ssen f�r die Pumpen
  - https://www.amazon.de/gp/product/B0716WZ6RW
- Optional 40 Pin IDE Header + IDE Flachbandkabel als Anschlusskabel aller elektrischen Bauteile an die Platine
  - https://www.amazon.de/gp/product/B007Q92OK2
  - https://www.amazon.de/gp/product/B00Z5AVRDY
  - So etwas l�sst sich aber auch wunderbar aus einem alten PC-Mainboard ausschlachten
- Optional Litzenkabel 0,5 mm� (falls man sich gegen das IDE Flachbandkabel entscheidet)
- 1x Rolle 3D Drucker Filament aus zertifiziert lebensmittelechtem Material, Empfehlung BASF Ultrafuse EPR InnoPET in Transparent
  - https://www.igo3d.com/innofil3d-epr-pet
- 6x Verschlusskappen von Sodastream Sirup-Flaschen
- Kleber zum Verkleben von Kunststoffteilen
- Schrumpfschlauch
- L�tzinn
- Hei�klebesticks
- Kabelbinder

## Werkzeuge

- 3D Drucker
- L�tkolben
- Hei�klebepistole
- Multimeter
- Optional Breadboard / Steckplatine + Anschlusskabel zum Testen der Schaltung bevor man sie fest verl�tet
- Cuttermesser
- Zangen (Abisolierzange, Schnabelzange)
- Optional Crimpzange f�r JST-Stecker
  - https://www.amazon.de/gp/product/B01N4L8QMW
- Pinzette
- Schraubenzieher / Schraubenschl�ssel
- Filzstift zum Markieren auf Kunststoff
- Zollstock
- Lochkreisbohrer mit 24 mm Durchmesser
- Bohrer 3,5 mm und 10 mm
- Hands�ge mit feiner Zahnung (f�r Kunststoff geeignet)
- Feilen / Schleifpapier


## Elektrische Schaltung

### Aufbau der Schaltung auf Steckplatine / Breadboard

<img src="img/breadboard.png" width="90%"/><br/>

### Schaltplan

<img src="img/schaltplan.png" width="90%"/><br/>

### St�ckliste

Nr.     | Anzahl | Bezeichnung  
------  | ------ | -------------
M1 - M6 | 6      | Mini Luftpumpen 6 Volt
S1 - S6 | 6      | Taster / Push Buttons
D1 - D6 | 6      | Diode 1 Ampere 1N4007
M7      | 1      | Aquarium Tauchpumpe mit mindestens 240 L/h Durchfluss
R1      | 1      | Potentiometer 4,7 kOhm
Q1      | 1      | N-Kanal Mosfet zum Beispiel Infineon IRF740PBF oder Infineon IRFP064N oder Infineon IRFP1405PBF
VCC1    | 1      | DC Netzteil 9 Volt oder 12 Volt mindestens 1500 mA

### Umsetzung

Optional kann die Schaltung zu Testzwecken zun�chst auf einem Breadboard aufgebaut werden (siehe Aufbauskizze oben). Zur Vereinfachung kann auch zum Beispiel mit nur zwei Siruppumpen getestet werden, hierzu einfach M3-6, S3-6 und D3-6 weglassen.

Anschlie�end sind alle Komponenten wie im Schaltplan dargestellt auf eine Lochrasterplatine zu l�ten. Die Platine wird sp�ter unten in der Geh�usemitte zwischen der Geh�usefront und dem Wasserbeh�lter platziert, bei den Kabell�ngen also bitte daran denken.

Optional k�nnen die freihstehenden Bauteile, die nicht direkt auf der Platine aufgel�tetet werden, �ber ein 40 Pin IDE-Header + Flachbandkabel steckbar an die Platine angebunden werden. Dies betrifft 

- die Pumpen M1 - M6 sowie M7
- die Taster S1 - S6
- das Potentiometer R1
- die Stromquelle / das Netzteil VCC1 

Hierzu ist einfach das 40 Pin IDE-Header auf die Platine anzul�ten und sich eine Belegung auszudenken und zu notieren. Ich habe die Pins in Hinblick auf einen strategisch klugen Kalebweg (ohne wilde �berkreuzungen) wie folgt gew�hlt:

- Pin 1 - 6 f�r die Pumpen M1 - M3 auf der linken Geh�useseite
- Pin 7 - 12 f�r die Taster S1 - S3 auf der linken Geh�useseite
- Pin 26 - 28 f�r das Potentiometer R1 auf der rechten Geh�useseite
- Pin 29 - 30 f�r die Stromquelle / das Netzteil VCC1
- Pin 31 - 32 f�r die Wasserpumpe M7 in der Mitte des Geh�uses
- Pin 29 - 34 f�r die Taster S4 - S6 auf der rechten Geh�useseite
- Pin 35 - 40 f�r die Pumpen M4 - M6 auf der rechten Geh�useseite

Ansonsten (falls man sich gegen die Verwendung eines IDE Headers entscheidet) sind die elektrischen Verbindungen �ber Litzenkabel auszuf�hren.

Alle L�tverbindungen an Kabel und Kontakte freistehender Bauteile sind mit Schrumpfschlauch vor Kurzschl�ssen zu isolieren.

Optional k�nnen auf Seite der Pumpen JST-Stcker und Buchsen an die Kabel gecrimpt werden, um eine Pumpe zum Beispiel bei einem Defekt schnell tauschen zu k�nnen.

Schlie�lich ist die Platine an ihrem Bestimmungsort (Geh�usemitte zwischen der Geh�usefront und dem Wasserbeh�lter) platzieren und lose Kabel mit Kabelbindern zu ordnen.

## 3D Druck

### Material

Da der Sirup mit einem gedruckten Teil in Kontakt kommt, sollte auf jeden Fall ein zertifiziert lebensmittelechtes Material f�r den 3D Druck verwendet werden.
Hierzu habe ich das Filament BASF Ultrafuse EPR InnoPET in Transparent verwendet, es ist lebensmittelecht, passt farblich gut zum transparenten Geh�use des Automats und erf�llt auch die ben�tigten Eigenschaften hinsichtlich Stabilit�t, Dehnungselastizit�t sowie Dichtigkeit.

### Druckteile

Die folgenden Teile sind in der jeweils angegebenen St�ckzahl zu drucken:

- [01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen](stl/01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen.stl)
  - Die zentrale D�se an der Front des Geh�uses, aus dem das Wasser und Sirup austritt und ins Glas f�llt
- [02_6x_Pumpenhalterung](stl/02_6x_Pumpenhalterung.stl)
  - Halterung zur Montage der Druckluftpumpen an die Seitenw�nde der Ikea Samla Kiste
- [03_6x_Sirupschlauchadapter](stl/03_6x_Sirupschlauchadapter.stl)
  - Adapter mit 2 Schlauchanschl�ssen, die an die Deckel der Sodastream Sirup-Flaschen geklebt werden, bitte spezielle Druckhinweise weiter unten beachten
- [04_2x_Tastergeh�use_Frontplatte](stl/04_2x_Tastergeh�use_Frontplatte.stl)
  - Frontabdeckung des Bedienfeldes f�r 3 Taster, klemmt das Getr�nkelabel fest
- [05_2x_Tastergeh�use_Montagerahmen](stl/05_2x_Tastergeh�use_Montagerahmen.stl)
  - Hinterteil des Bedienfeldes f�r 3 Taster, hier wird das Getr�nkelabel eingelegt und die Frontabdeckung wird drauf geclipst
- [06_Potentiometergeh�use_Frontplatte](stl/06_Potentiometergeh�use_Frontplatte.stl)
  - Frontabdeckung des Bedienfeldes des Potentiometers, klemmt das Label mit der Skala f�r die Mischverh�ltnis-Einstellung fest
- [07_Potentiometergeh�use_Montagerahmen](stl/07_Potentiometergeh�use_Montagerahmen.stl)
  - Hinterteil des Bedienfeldes des Potentiometers, hier wird das Label mit der Skala f�r die Mischverh�ltnis-Einstellung eingelegt und die Frontabdeckung wird drauf geclipst
- [08_Potentiometer_Drehknopf](stl/08_Potentiometer_Drehknopf.stl)
  - Drehkappe f�r die Achse des Potentiometers, wird mit einer Madenschraube klemmend fixiert
- [09_Ikea_365+_Unterstellrahmen](stl/09_Ikea_365+_Unterstellrahmen.stl)
  - Optional: Rahmen f�r den Ikea 365+ Wasservorratsbeh�lter, kann am Boden der Ikea Samla Kiste festgeklebt werden und markiert so eine fixe Position zum Einsetzen des Beh�lters 
- [10_Soda_Mat_Label](stl/10_Soda_Mat_Label.stl)
  - Optional: SodaMat Label zur Versch�nerung / zum Branding der Ikea Samla Kiste von au�en, kann auf den freien Streifen �ber das Bedienfeld geklebt werden
- [11_Soda_Mat_Schablone](stl/11_Soda_Mat_Schablone.stl)
  - Optional: Schablone zum einfacheren Einkleben und Platzieren der Buchstaben des SodaMat Labels

## Spezielle Druckhinweise f�r die Sirupschlauchadapter

Die Sirupschlauchadapter sind etwas schwierig zu drucken, daher hier einige Tips:

Die Adapter m�ssen am Ende des Drucks m�glichst Luftdicht sein um den Luftdruck, der durch die Pumpen erzeugt wird, aufrecht erhalten zu k�nnen. Hinzu kommt noch die Herausforderung, dass das Dach des Deckels als �berhang gedruckt werden muss.

Um Leckagen zu vermeiden und um den �berhang sauber gedruckt zu bekommen sind m�glichst folgende Druckeinstellungen zu w�hlen: 

- Bauteil so platzieren, dass die runde Mantelfl�che des Deckels sowie der innere Schlauchanschlussflansch auf der Druckplatte aufliegt
- ein hoher Fluss zum Beispiel 110 % (muss vorher getestet werden, dass nicht zu viel Overextrusion entsteht)
- breite Linien zum Beispiel 0.6 mm bei einer 0.4 mm Nozzle (je breiter die Linien, desto weniger Zwischenr�ume entstehen)
- Ideale Temperatur beim BASF Ultrafuse EPR InnoPET war bei mir 220 Grad / 70 Grad Heizbett
- M�glichst viel Cooling verwenden, um ein Bridging am �berhang hin zu bekommen
- Keine St�tzstrukturen / Support verwenden, andernfalls wird es fast unm�glich, am Ende den Support zerst�rungsfrei vom Bauteil zu trennen, da der innere Schlauchanschlussflansch sehr nah am Support w�re
- Unbedingt die Br�cken- / Bridging-Einstellungen aktivieren, damit die ersten beiden Br�ckenw�nde mit reduziertem Fluss und h�herem Linienabstand gedruckt werden (siehe folgendes Bild)

<img src="img/bridging.png" width="50%"/><br/>

## Montage

### Montage des Teils __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__

- An der Front kurz unter dem oberen Falz die Geh�usemitte mit dem Stift markieren
- Am Mittelpunkt auf der Au�enseite des Geh�uses das Teil __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__ anhalten, so dass die die Oberkante b�ndig mit dem oberen Falz des Geh�uses ist
- Auf der Innenseite des Geh�uses die Mitte der 6 Schlauchdurchf�hrungs-L�cher markieren
- Die 4 seitlichen L�cher zur Schraubenbefestigung ebenfalls markieren 
- Am markierten zentralen Punkt mit dem 24 mm Lochkreisbohrer durch das Geh�use bohren f�r zur Durchf�hrung der 6 Schl�uche
- An den markierten 4 seitlichen Punkten mit dem 3,5 mm Bohrer durch das Geh�use bohren
- 6 etwa 40 cm lange St�cke vom Silikonschlauch 3 x 5 mm abschneiden
- Das Schlauchende der 6 Silikonschl�uche 3 x 5 mm sowie des Silikonschlauchs 7 x 10 mm muss zun�chst durch eines der hinteren und dann durch das entsprechende untere Loch des Teils __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__ gef�delt werden, hierzu ist eine spitze Schnabelzange oder Pinzette hilfreich
- Alle Schlauchenden so ausrichten, dass sie bis kurz unter die unteren L�cher ragen
- Schlauchenden mit Hei�kleber fixieren, damit sie nicht mehr leicht heraus rutschen k�nnen
- Hinteren Teil der Schl�uche von au�en durch das gebohrte 24 mm Loch der Samla Kiste schieben
- __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__ ans Geh�use andr�cken und mit 4 M3 x 10 mm Zylinderschrauben + Muttern montieren

<img src="img/d�se_unten.jpg" width="50%"/><br/>
<img src="img/d�se_hinten.jpg" width="50%"/><br/>

### Montage der Teile __02_6x_Pumpenhalterung__

- Eine Pumpe in eine __02_6x_Pumpenhalterung__ einlegen, hierzu ein wenig Mosgummi zur Ger�uschentkopplung und zum besseren Verklemmen an den Kunststoffteil der Pumpe kleben (Hei�kleber)
- Die __02_6x_Pumpenhalterung__ von innen an einer der Seitenw�nde der Ikea Samla Kiste anhalten und messen, dass sie vertikal mittig platziert ist, der Abstand von oben sollte so gew�hlt werden, dass noch der Deckel der Samla Kiste geschlossen werden kann, ohne an die Pumpe anzuschlagen
- Laschen der Halterung fest an das Geh�use dr�cken und Bohrl�cher mit dem Stift markieren
- Einen festen Abstand der vorderen und hinteren Pumpe zum Mittelpunkt festlegen und messen, hierzu analog zur vorherigen Beschreibung die Bohrl�cher durch Anhalten der Halterung + Pumpe markieren
- An den markierten Punkten mit dem 3,5 mm Bohrer durch das Geh�use bohren
- Analog an der anderen Geh�useseite vorgehen
- __02_6x_Pumpenhalterung__ mit den eingesetzten Pumpen und jeweils 2 M3 x 10 mm Zylinderschrauben von innen an den Geh�useseiten montieren

<img src="img/pumpenhalterungen.jpg" width="50%"/><br/>

### Montage der Teile __03_6x_Sirupschlauchadapter__

- 6 etwa 15 cm lange (L�nge der H�he der Sodastream Sirup-Flaschen entsprechend) St�cke vom Silikonschlauch 3 x 5 mm abschneiden
- Die einen Schlauchenden auf die inneren Schlauchanschlussflansche der Teile __03_6x_Sirupschlauchadapter__ aufstecken
- Die Verschlusskappen der Sodastream Sirup-Flaschen reinigen und die oberen Fl�che / D�cher abs�gen und mit der Feile oder Schleifpapier entgraten
- Reichlich Kunststoffkleber auf die Innenseiten der Flanken der Teile __03_6x_Sirupschlauchadapter__ auftragen und diese auf die abges�gten Verschlusskappen setzen, damit die Teile luftdicht mit den Verschlusskappen verkleben
- Nach dem Trocknen des Klebers die 6 Schlauchenden des Teils __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__ an denjenigen Schlauchanschlussflnasch stecken, unter dem sich auch der innere Schlauchanschlussflansch befindet (Sirup-Steigleitung)
- 6 etwa 20 cm lange St�cke vom Silikonschlauch 3 x 5 mm abschneiden
- Das eine Ende des Schlauchs auf den Auslass (oben) der zugeh�rigen Luftpumpe stecken, das andere Ende auf den verbleibenden Schlauchanschlussflnasch der Teile __03_6x_Sirupschlauchadapter__

<img src="img/sirupschlauchadapter1.jpg" width="50%"/><br/>
<img src="img/sirupschlauchadapter2.jpg" width="50%"/><br/>

### Montage der Teile __04_2x_Tastergeh�use_Frontplatte__ und __05_2x_Tastergeh�use_Montagerahmen__

- Die beiden Teile zusammen clipsen und so an die Front des Geh�uses (Ikea Samla Kiste) anhalten, dass die Oberseite b�ndig mit dem oberen Falz des Geh�uses  und die Innenseite b�ndig mit dem Teil __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__ ist
- Die 2 L�cher zur Schraubenbefestigung sowie die 3 L�cher der Taster auf dem Geh�use markieren
- An den 2 markierten Schraubenbefestigungspunkten mit dem 3,5 mm Bohrer durch das Geh�use bohren
- An den 3 markierten Punkten der Taster mit dem 10 mm Bohrer durch das Geh�use bohren
- 3 Taster durch die L�cher in __05_2x_Tastergeh�use_Montagerahmen__ und durch die gebohrten L�cher des Geh�uses f�hren und mit der �berwurfmutter auf der Innenseite des Geh�uses fest ziehen
- __05_2x_Tastergeh�use_Montagerahmen__ mit 2 M3 x 10 mm Zylinderschrauben an der Geh�usefront fertig montieren
- Getr�nkelabels ausdrucken, passend zuschneiden und in __05_2x_Tastergeh�use_Montagerahmen__ einlegen
- __04_2x_Tastergeh�use_Frontplatte__ aufclipsen
- Analog mit dem Tasterbedienfeld an der anderen Geh�useseite vorgehen

<img src="img/tastergeh�use1.jpg" width="50%"/><br/>
<img src="img/tastergeh�use2.jpg" width="50%"/><br/>

### Montage der Teile __06_Potentiometergeh�use_Frontplatte__ und __07_Potentiometergeh�use_Montagerahmen__

- Bei der Montage dieser Teile ist analog zur Montage von __04_2x_Tastergeh�use_Frontplatte__ und __05_2x_Tastergeh�use_Montagerahmen__ vorzugehen
- Die Platzierung sollte rechts neben dem rechten diagonalen Falz der Ikea Samla Kiste erfolgen, Oberkante sollte b�ndig zu den restlichen Bedienfeldern sein horizontaler Abstand kann frei gew�hlt werden

### Montage des Teils __09_Ikea_365+_Unterstellrahmen__

- Das Teil ohne Kleber lose auf dem Boden platzieren, darauf den Ikea 365+ Beh�lter stellen und diesen so in der Samla Box ausrichten, dass er horizontal in der Mitte steht und vertikal am hinteren Geh�userand anschl�gt
- Vorsichtig den Ikea 365+ Beh�lter heraus nehmen und ohne Verrutschen die Position des Teils am Boden der Kiste markieren
- Kleber auf die Unterseite des Teils auftragen und das Teil an der markierten Position auf der Innenseite des Bodens der Kiste befestigen

<img src="img/unterstellrahmen1.jpg" width="50%"/><br/>
<img src="img/unterstellrahmen2.jpg" width="50%"/><br/>

### Montage der Wasserpumpe

- Da es sich um eine Tauchpumpe handelt, wird diese zum Betrieb einfach tauchend in den Ikea 365+ Wasserbeh�lter gelegt
- Zur Montage muss lediglich das verbleibende Schlauchende des Teils __01_Getr�nked�se_mit_6_Schlauchdurchf�hrungen__ auf den Auslass der Pumpe gesteckt werden

<img src="img/wasserpumpe.jpg" width="50%"/><br/>
