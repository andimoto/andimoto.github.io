---
layout: default
title:  "'Noiseless PC' Bau | [de]"
date:   2017-03-05
categories: tech
---

# 'Noiseless PC' Bau

![Noiseless-PC](/img/noiseless-pc/pc.jpg)
---

<br>
***Diesen Post habe ich bereits 2017 erstellt und nun mit ein paar Anpassungen hier "importiert".***

<br>

Ende 2016 habe ich mir nach langer Suche einen lüfterlosen PC zusammen gebaut. Das besondere ist, dass dieser PC sehr klein ist aber mit einer i7-6700 und 32GB RAM extrem viel Power aufweist. Die CPU besitzt dabei eine relativ performante Grafikeinheit, welche ohne Probleme 4K Videos abspielt oder beim Bearbeiten von RAW-Bilder mit Darktable ganze Arbeit leistet.

<br>

<h1>Die Idee</h1>
Als ich 2016 begann mich mit Fotografie zu beschäftigen, merkte ich nach und nach, dass sich die bearbeiteten Bilder von Kontrast und Farbe auf unterschiedlichen Endgeräten stark unterschieden. Das lag an meinem alten Monitor, welchen ich bis dahin nie für Bildbearbeitung verwendet habe. Da ich mich immer mehr mit Fotografie und Fotobearbeitung auseinander setzte, musste ein neuer Monitor her. Leider habe ich dabei nicht bedacht, dass mein Laptop mit HDMI nicht die vom Monitor mögliche maximale QHD Auflösung (2560 × 1440) des Dell U2715H bereitstellen kann. Das liegt unter anderem auch an den Spezifikation von HDMI. Diese Auflösung kann nur durch HDMI 2.0 oder DisplayPort 1.2 gefahren werden. Somit musste ein neuer Rechner her. Mein Laptop (IdeaPad Y570) ist zwar noch relativ flott aber besitzt die 2. Core i Generation in der mobilen Ausführung. Zudem reißen 8GB RAM keine Bäume mehr aus.

Da ich keinen großen lauten Rechner wollte, hatte ich meine Augen anfangs noch auf den kleinen Barebones Brix und NUCs. Nach und nach schieden viele davon aus. Es fehlten SD-Karten Slots und DisplayPorts. Zudem waren alle noch mit kleinen Lüftern ausgestattet und basierten auf den mobilen CPUs der Intel Core i Reihen. Zusätzlich musste Arbeitspeicher und Festplatte extra gekauft werden. Das mit dem SD-Karten Slot habe ich dann direkt aufgegeben und ein gutes externes Lesegerät angeschloßen.

Mit der Zeit kam dann wieder die Idee einen lüfterlosen Rechner aufzubauen. Das geisterte schon einige Jahre in meinem Kopf herum. Nach viel Recherche bin ich dann fündig geworden. Der Hersteller Wesena/Streacom (glaube das wird nun unter Streacom vertrieben) bietet ein passives Gehäuse FC8 Evo an, welches für bis zu 95W TDP ausgelegt ist. Nachdem ich einen Händler in Deutschland gefunden hatte und mit bestätigt wurde, dass das Case auch einen i7-6700 mit 65W locker weg steckt, habe ich das Gehäuse dann auch bestellt. An dieser Stelle empfehle ich zusätzlich eine (bzw. 2) Tuben mit einer guten Wärmeleitpaste (Arctic, etc) zu holen. Die mitgelieferte hätte bei mir nicht annähernd gereicht und besitzt auch eine schlechtere Wärmeleitfähigkeit. Da wollte ich dann lieber sicher gehen.

&nbsp;
<h1>Zusammenbau</h1>
Der Zusammenbau war etwas komplizierter als bei einem normalen PC, ist aber trotzdem recht gut zu meistern. Der schwere Teil liegt natürlich an den Heatpipes und der Wärmeleitpaste. Hierbei war es für mich auch relativ schwer zu bestimmen, wie viel Paste ich überhaupt auftragen soll. Dazu habe ich von den Plastikverpackungen etwas abgeschnitten und als Spachtel verwendet. Dabei habe ich versucht möglichst alle Kontaktflächen der Heatpipes zu CPU und Gehäuse lückenlos zu bedecken. Ich denke es reicht hierbei die Flächen so zu bedecken, dass die Schicht nicht zu dick ist, aber man die Oberfläche gerade nicht mehr sieht. Beim zusammenführen der Kontaktflächen ist auch sehr wenig Paste am Rand heraus gequellt. Das ist für mich allerdings eher ein subjektiver Eindruck und jeder sollte das selbst entscheiden. Ansonsten sollte der Zusammenbau nach Anleitung des Gehäuses, bzw. des Teils (RAM, CPU, usw) durchgeführt werden.

Bei meiner Konfiguration des Gehäuses mit Mainboard und M.2 SSD sind mir dann auch gewisse Schwachstellen aufgefallen. Ich habe das Betriebssystem auf die M.2 SDD installiert, welche unter dem Mainboard hängt. Sollte hier etwas ausfallen komme ich sehr schlecht an diese SDD heran. Dazu wäre es nötig die Heatpipes abzunehmen und das Mainboard auszubauen. Durch die Wärmeleitpaste kann das eine unangenehme Arbeit werden. Das sollte aber niemanden abschrecken. Das kommt natürlich auch darauf an ob man nun die M.2 SDD verbaut oder das Mainboard überhaupt einen Slot dafür besitzt. Wer nicht so viel Speicher benötigt dem reicht auch eine oder mehrere normale SDDs / HDDs. Hier würde noch eine SSD in den Schacht des CD Laufwerks passen wenn man einen passenden Adapter dafür verwendet.

Zu beachten ist auch, welches USB 3.0 Flachbandkabel man verwendet um die USB Anschlüße der Gehäusefront mit dem Mainboard zu verbinden. Zuerst hatte ich ein sehr starres und dickes Kabel dafür. Eine Seite ist am Stecker immer heraus gerutscht und machte ein Buchse nicht verwendbar. Das lag daran das im Gehäuse noch eine Brücke für die Laufwerke verbaut wird. Das drückt dann auf dieses starre Kabel. Dieses kann man auch nicht gut verbiegen. Besser ist da eines mit normalen einzelnen Leitungen die nicht zu einem Bündel zusammengeführt werden. Das gibt es auch direkt beim Anbieter des Gehäuses.

So ein lüfterloses Design benötigt zum Start noch einige Anpassungen. Das Problem sind hier die fehlenden Lüfter. Das BIOS erkennt natürlich keine und will erst einmal nichts machen. Da ich diesen Artikel 3 Monate nach dem Bau erstellt habe, kann ich nicht mehr genau sagen was ich umgestellt habe :). Das bekommt man aber irgendwie hin.

Noch etwas zum Arbeitsspeicher. Zu Beginn habe ich einen 16GB Riegel bestellt. Was ich da noch nicht wusste ist, dass die Leistung durch Dual-Channel stark erhöht werden kann. So habe ich mir den gleichen Arbeitspeicher nochmal bestellt. Das hat sich durch ein paar Tests bestätigt. Mit einem RAM-Riegel läuft die 4K Version von BigBugBunny nicht ganz flüssig. Sind beide Kanäle des Arbeitsspeichers bestückt, läuft das ganze ruckelfrei. Auch die maximal vorhandene Auflösung des Films.

***Ein paar schlechte Bilder vom Zusammenbau :)***
<br>
![Sorry for shitty picture :D](/img/noiseless-pc/001.jpg)
&nbsp;
![Build-up Noiseless-PC](/img/noiseless-pc/002.jpg)
&nbsp;
![Build-up Noiseless-PC](/img/noiseless-pc/003.jpg)
&nbsp;
![Build-up Noiseless-PC](/img/noiseless-pc/004.jpg)
&nbsp;
![Build-up Noiseless-PC](/img/noiseless-pc/009.jpg)
&nbsp;
![Build-up Noiseless-PC](/img/noiseless-pc/010.jpg)
<br>

&nbsp;
<h1>Eindrücke und Wärmeentwicklung</h1>
Der PC war nun fertig und bereit zur Installation des Betriebssystems. Das erste Einschalten war noch sehr ungewohnt. Das kennt man eventuell vom Raspberry Pi, der einfach ohne Brummen und Summen hochfährt. Es ist sehr angenehm und man wird nicht durch einen sich auf und ab regelnden Lüfter genervt. Die Schattenseite daran: hat man externe HDD Festplatten, hört man diese nun recht gut :). Das wurde sonst immer vom Lüfter des Laptops übertönt. Das Problem lag aber eher bei Linux Mint, welches die Festplatte nicht in den Standby versetzen wollte. Hierbei habe ich mir mit dem Tool ***hdparm*** Abhilfe verschafft.

Die Installation von Linux Mint 18 lief extrem schnell durch, was man den schnellen SSDs zuschreiben muss. Auch ein Start bzw. Neustart benötigte Anfangs noch etwa 10 Sekunden bis zum Login-Screen. Das legte sich nachdem einige Services des Betriebssystems installiert und aktiviert wurden und auch gestartet werden müssen. Nach dem Login erscheint der Desktop nun auch fast augenblicklich. Das ist beim Laptop ganz anders. Der benötigt ein paar Sekunden Bedenkzeit. Die Ladezeiten der einzelnen Programme ist sehr kurz. Die meisten Programme starten sofort als würde man diese aus der Taskleiste wiederherstellen.

Die Wärmeentwicklung stellt überhaupt kein Problem dar. Im BIOS wurden mir immer um 40°C angezeigt. Das Betriebssystem zeigt mir nun im "Leerlauf" ca. 35°C an. "Leerlauf" ist hier - die üblichen Hintergrundprozesse, Firefox, Thunderbird, Terminal und Dateimanager. Wenn ich meine Bilder mit Darktable bearbeite, werden mir ca. 50°C bis 55°C angezeigt. Sobald ich einige Bilder dann konvertiere steigt die Wärme auf ca 70°C an und erhöht sich stetig je nach Dauer der Belastung. Dabei muss ich erwähnen, dass Darktable alle Kerne beansprucht. Das ist z.B. bei Videos nicht der Fall. Dabei hatte ich noch nie Probleme mit der Wärme. Die Kühlrippen werden nach so einer Belastung sehr Warm aber man kann sie noch anfassen. Sorgen mache ich mir hierbei eher weniger. Die CPU hat interne Mechanismen, welche bei Übertemperatur ab regeln oder ausschalten.


&nbsp;
<h4>Die Daten auf einen Blick:</h4>

| Typ | Hardware | Preis (Dez.2016) |
|-------|--------|---------|
| Case | Wesena FC8 Evo V2 Mini-ITX + 150W Netzteil @ PicoPSU | ca. 200€ |
| Mainboard | ASUS H170I-PRO ITX So. 1151 (Skylake CPUs) | ca. 120€ |
| CPU | Intel Core i7-6700 | ca. 310€ |
| RAM | 2x Crucial CT16G4DFD8213 DDR4-2133 | ca. 2x 80€ |
| SSD (OS) | Samsung 850 Evo M.2 2280 500GB | ca. 180€ |
| SSD (Data) | Samsung 750 Evo 2.5" SATA 500 GB | ca. 135€ |
|            |                                  |          |
| Grafikkarte | Asus GeForce GT 1030 | ca. 90€ Juni 2020 |

<h1>Auswahl</h1>
<h4>Case</h4>
Da ich kein großes Gehäuse wollte aber auch kein Lüfter, war das FC8 perfekt. Es ist klein (ca. 25x25cm) und passt auf den Schreibtisch. Naja, so gesehen wäre ein NUC natürlich besser aber diesen Kompromiss gehe ich gerne ein. Zudem ist es eines der ganz wenigen Gehäuse die auch eine leistungsstarke CPU ohne Probleme kühlt.
<h4>Mainboard</h4>
Für mich, das einzige Mainboard welches meine Anforderungen erfüllt hat. Schneller Chipsatz, Display Port und einige USB Buchsen. Praktischer Weise besitzt es noch alle Anschlüssarten für Monitore. Heißt: VGA, DVI, HDMI und DP. WLan, Bluetooth & 2 Ethernet-Buchsen sind auch vorhanden. Auf was man dringend achten muss ist, dass das Gehäuse mit der Anordnung der Heatpipes zum Mainboard passt. Der Hersteller des Gehäuses listet das eigentlich auf.
<h4>CPU</h4>
Wenn schon, denn schon! Bei diesem Thema habe ich viel überlegt und recherchiert, welche CPU & Grafikeinheit am besten ist. Vergleichen kann ich das natürlich schlecht. Aber für meinen Anwendungsfall benötigte ich eine Grafikeinheit die gut mit OpenCL klar kommt. Das verwendet Darktable als Grafikbibliothek. Natürlich wäre so gesehen eine dedizierte Grafikkarte besser, allerdings habe ich einen gewissen Platzmangel im Gehäuse und müsste eine spezielle Grafikkarte einbauen. Zudem haben die meisten Grafikkarten Lüfter. Passt nicht so ganz zu einem lüfterlosen PC.
<h4>Arbeitsspeicher</h4>
Hierfür gab es keine besonderen Gründe. Das Mainboard bzw. die CPU sollte den Arbeitsspeicher natürlich optimal Auslasten können. Außerdem kann man zusätzlich noch relativ viel Leistung herausholen, indem man den RAM im DualChannel Betrieb installiert. Das habe ich dann sofort gemerkt.
<h4>SSDs</h4>
Passend zur Leistung der Hardware sollten auch schnelle SSDs eingebaut werden. Da die RAW Dateien der Kamera relativ groß sind, muss auch genug Speicher vorhanden sein. Die Aufteilung für das Betriebssystem und die Daten habe ich extra so gewählt. Das hält meine Daten vom Betriebssystem getrennt und somit wäre es auch relativ einfach ein neues oder anderes Betriebssystem zu installieren ohne die Daten hin und her zuschieben.

&nbsp;
<h2>Alternative Hardware</h2>
Drückt man die Ansprüche an die Leistung & Kapazität der Hardware weiter runter, wäre es möglich so einen lüfter- und lärmlosen PC für weniger €uros zu bekommen. Abstriche kann man zum Beispiel bei Mainboard und CPU machen. Für ein relativ angenehmes Arbeiten reichen schon 8GB RAM. Die Kapazität kann man locker auf 100-250GB runter schrauben. Das reicht normalerweise aus. Alternativ könnte man normale 2,5" HDDs verwenden. Aber das lärmt dann wieder etwas :). Ausgerechnet habe ich mal einen Gesamtpreis von 400-450€. Die Hardwareauswahl dieser Alternative habe ich am HP ProLiant angelehnt. Auf dem lasse ich ein OpenMediaVault NAS System laufen und eine Linux VM ist auch kein Problem. Ausgewählt habe ich zum Beispiel eine Celeron G1840 CPU (Sockel 1151) für ca. 40-50€. Ein ASRock H81M-ITX Mainboard für ca 60€, 2x4GB RAM für insgesamt ca. 60€ und eine SSD mit 120GB für rund 50€. Hinzu kommen noch ca. 200€ für Case und Netzteil. Durch eine geringere Leistung des Netzteil kann man noch etwas sparen. Ein guter Preis wenn man bedenkt was halbwegs brauchbare Barebones und Laptops kosten.

&nbsp;

***Update 2019:***
<br>
Es gibt 12cm PC Lüfter welche über USB versorgt werden und mit einem Schalter ein- und ausgeschaltet werden können. So einen habe ich neben die Kühlrippen gestellt. Die Hitze an den Kühlrippen wurde mir, vor allem beim Konvertieren sehr vieler Bilder, etwas zu heiß. Der Lüfter schafft hier eine gute Abhilfe. Für die mittlerweile wenigen male, die ich den Lüfter einschalten muss ist das ein guter Kompromiss bzw. Workaround gegenüber einem dauerhaft eingebauten Lüfter.

<br>
![graka001](/img/noiseless-pc/g000.jpg)
&nbsp;

***Update 2020:***
<br>
Ich habe das coolste Spiel entdeckt! Kerbal Space Programm. Ich habe es anfangs auf meinem Laptop gespielt. Dieser hat mit einem Core i5-8265U eine neuere CPU, welche einen besseren Grafikchip besitzt. Damit läuft das Spiel relativ gut. Die Framerate liegt zwischen 13 bis 20 Frames. Natürlich nicht viel, aber noch gut spielbar. Auf meinem Noiseless PC ging das nicht mehr. Der Grafikchip des i7-6700 hat einfach keine Power (der Grafikchip wird mit 350MHz getacktet). Die Framrate lag unter der des Laptops und ich konnte das Spiel nur in einem Fenster halbwegs akzeptabel spielen. Das wollte ich nicht so lassen.

Ich hatte 2 zwei Möglichkeiten:
1. Das Case und das Motherboard haben einen freien PCI Slot. Hier passt eine Grafikkarte rein.
2. Ein neuer Rechner, welchen ich nur zum Spielen verwende.

Das Thema Linux und Nvidea Grafikkarten bereitete mir etwas Sorgen, da ich bisher keine guten Erfahrungen damit hatte. Im nachhinein war der Grund dafür unbedeutend. Zum einen hatte ein Rechner (auf welchen ich vor Jahren mal Linux Mint installierte) eine alte GeForce, welche von den Treibern nicht unterstützt wurde. Zum anderen hat mein alter Laptop eine dieser Hybrid-Grafikkarten (Intel & NVidea). Hier läuft das mit den Treibern komplett anders. Ich musste die günstigere Variante mit der Grafikkarte mindesten Versuchen.

Nach etwas Suche entschied ich mich für eine Asus GeForce GT 1030. Lediglich der Kühler würde nicht richtig passen. Aber eine Grafikkarte mit passivem Kühler und als 1 Slot Ausführung gab es nicht. Die Installation lief (zu meiner Überraschung) ohne Probleme über die Bühne. Die Grafikkarte eingebaut und den PC gestartet. Den Monitor habe ich am DisplayPort des Mainboards angeschoßen gelassen. Nach dem Start von Linux mit 19.3 meldete sich direkt die Treiberverwaltung, welche die neue Grafikkarte erkannt hat. Man bekommt hier direkt mögliche Treiber angezeigt. Ich habe direkt den aktuellsten nvidia-driver(-440) installiert. Nach einem Neustart war alles eingerichtet. Die Grafikkarte wurde bereits verwendet. Den Monitor konnte ich am DisplayPort hängen lassen.

Kerbal Space Program läuft nun auf voller Auflösung (3840 x 2160) und etwas herunter geschraubten Spiele-Details. Die Temperatur hält sich in Grnezen. Im Leerlauf liegt die Temperatur der Grafikkarte bei ca. 30°C. Während des Spiels werden es 70-75°C. Mehr habe ich bisher nicht erlebt.

Leider ist das ganze noch nicht perfekt. Der Kühler der Grafikkarte schaut über den Rand des Gehäuses raus. Ich kann also das Gehäuse nicht zu machen. Der Kühler muss kleiner werden. Dazu habe ich den Kühler abfrässen lassen. Das ging durch die relativ dünnen Kühlrippen nur sehr schwer, wie man auf einem der Bilder sieht. Die Kühlrippen sind teilweise stark verbogen oder sind ganz abgebrochen. Um die verkürzten Kühlrippen auszugleichen, habe ich auf die Innenseite des Gehäusedeckels ein paar Wärmeleitpads angebracht. Ich habe die Höhe des Kühlkörpers so berechnet, dass dieser direkt über die Wärmeleitpads am Gehäuse anliegt. Die Wärmeleitpads kleben nicht am Gehäuse, sondern haften nur relativ schwach daran.

Nachdem schließen des Gehäusedeckels habe ich den PC gleich gestartet. Die Temperatur des Grafikchips pendelt sich nach dem Start im Leerlauf bei ca. 30°C ein. Nach einigen Minuten Kerbal Space Program stieg die Temperatur langsam in Richtung 70°C und höher. Das Gehäuse hat die Wärme abgeführt. Es wird sehr warm an der Seite. Aber der verkürzte Kühlkörper hat natürlich einen recht großen Einfluß auf die nun höhere Temperatur.

Hätte ich mich dazu entscheiden keine Grafikkarte in meinen PC zu bauen, würde ich auf einen Ryzen mit Vega Grafikchip zurück greifen. Ein ca. 2 Jahre alter Ryzen 3 2200 ermöglicht schon eine anständige Framerate von weit mehr als 30 Frames. Das wäre eine sehr gute Alternative für mich.

Hier noch ein paar Bilder:

<br>
![graka001](/img/noiseless-pc/g001.jpg)
&nbsp;
![graka001](/img/noiseless-pc/g002.jpg)
&nbsp;
![graka001](/img/noiseless-pc/g003.jpg)
&nbsp;
![graka001](/img/noiseless-pc/g004.jpg)
&nbsp;
![graka001](/img/noiseless-pc/g005.jpg)
&nbsp;
![Thermal Pads](/img/noiseless-pc/g006.jpg)
