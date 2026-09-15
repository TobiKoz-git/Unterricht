<!--

author:     Tobias Kozlowski
email:      tobias.kozlowski[a]bsz-tw-freiberg.lernsax.de

version:    0.0.1

language:   de
narrator:   Deutsch Male

comment: Ausführliches interaktives Lernmodul zu Lektion 1 im Lernfeld 1 (Mechatronik & Produktionstechnologen).
tags: LF1, MECH,PT, Einführung, Lernsituation, Arbeitsplan, LOL


icon: https://www.bsz-freiberg.de/templates/bszjw/img/logo.svg
logo: https://github.com/TobiKoz-git/Unterricht/blob/main/Elektrotechnik/Mechatroniker/Lernfeld_5/Grafiken/Nutzen_von_IT_Systemen__Tobias_Kozlowski_generated_with_Firefly.jpg?raw=true

mode: Presentation

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-DynFlex/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-timer/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-board-mode/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-marker/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-annotation/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-canvas-ocr/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-orthography/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-Mathe/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-kachel/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-navigation/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-mathpath/refs/heads/master/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-llm/refs/heads/main/README.md

import: https://raw.githubusercontent.com/liaTemplates/algebrite/master/README.md
import: https://raw.githubusercontent.com/liaTemplates/JSXGraph/main/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-resetter/main/README.md

import: https://raw.githubusercontent.com/MINT-the-GAP/lia-coordinate/refs/heads/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/lia-freeze-v2/main/README.md
import: https://raw.githubusercontent.com/MINT-the-GAP/Aufgabensammlung/main/imports/RedirecterREADME.md


import: https://raw.githubusercontent.com/MINT-the-GAP/lia-pentominos/main/README.md


import: https://raw.githubusercontent.com/liaTemplates/ABCjs/main/README.md

import: https://raw.githubusercontent.com/liaTemplates/Speech-Recognition-Quiz/refs/heads/main/README.md

-->

# Das Technische System & Die Systemgrenze

Stell dir eine einfache Taschenlampe vor: Sie besteht aus einem Gehäuse, einem Schalter, einer Batterie und einer LED. Jedes dieser Teile für sich allein bringt dir im Dunkeln wenig. Erst wenn sie zusammenarbeiten, erfüllen sie eine gemeinsame Aufgabe: Licht erzeugen.

> 📌 **Portfolio-Übernahme**
> **Definition:**
> Ein **technisches System** ist eine Ansammlung von Bauteilen, die miteinander verbunden sind und zusammenarbeiten, um eine bestimmte Aufgabe (Funktion) zu erfüllen.

Ein mechatronisches System wandelt Energie, Stoffe und Informationen um, um eine spezifische Gesamtfunktion zu erfüllen. In der Praxis stehen Techniker oft vor extrem komplexen Anlagen. Um diese beherrschbar zu machen, zu analysieren oder Fehler zu diagnostizieren, wird das System gedanklich von seiner Umgebung isoliert.

---

## Was ist die Systemgrenze?

Die Systemgrenze ist die Schnittstelle, die ein betrachtetes System von seiner Umgebung trennt. An den Systemgrenzen erfolgt eine Übertragung der Hauptumsatzgrößen, innerhalb des Systems erfolgt deren Umwandlung (EVA-Prinzip), Transport oder Speicherung. Für den Konstrukteur stellt die Systemgrenze häufig eine Schnittstelle dar, die gewissen Vorgaben entsprechen muss.

Die Beschaffenheit dieser Schnittstellen kann sehr unterschiedlich sein:

 - mechanische Schnittstellen (Maße, Toleranzen, Kupplungen, Befestigungen...)
 - elektrische Schnittstellen (Spannungspegel, Potential, Verbindungstechnik...)
 - pneumatische und hydraulische Schnittstellen (Druck, Anschluss...)
 - Datenschnittstellen (Übertragungsprotokoll, Übertragungsmedium, Anschluss...)

* **Innerhalb der Systemgrenze:** Alle Bauteile, die wir direkt betrachten, steuern oder bauen.
* **Außerhalb der Systemgrenze (Umwelt):** Alles, was das System umgibt (z. B. der Raum, der Benutzer, das Stromnetz).

Welche der folgenden drei Aussagen beschreibt den Begriff **Systemgrenze** in der technischen Systemanalyse am exaktesten?

 - [( )] A Eine mechanische Schutzverkleidung oder Trenngitter, das den Bediener vor Verletzungen durch laufende Maschinenteile schützt.
 - [(X)] B Eine gedankliche oder reale Trennlinie, die das betrachtete System von seiner Umwelt abgrenzt und alle relevanten Ein- und Ausgangsgrößen an den Schnittstellen definiert.
 - [( )] C Die maximale thermische und mechanische Belastungsgrenze einer Komponente, bei deren Überschreitung das System ausfällt.



---

> 📌 **Portfolio-Übernahme**
> **Definition: Systemgrenze**
> Die Systemgrenze ist die gedankliche oder physikalische Abgrenzung eines technischen Systems gegenüber seiner Umwelt. Sie definiert eindeutig, welche Bauteile zum betrachteten System gehören und welche Eingangs- und Ausgangsgrößen (Stoff, Energie, Information) die Grenze an den Schnittstellen überschreiten.

---

## Offene, geschlossene und abgeschlossene Systeme

Als offen ist ein System definiert, das sowohl Energie als auch Stoffe mit seiner Umgebung austauschen kann. Ein Beispiel für ein offenes System ist eine eisgekühlte, offene Cola-Flasche, die sowohl Wärmeenergie aus der Umgebungsluft aufnimmt wie auch Materie in Form Kohlendioxid an die Umgebungsluft abgibt.

Ein geschlossenes System ist materieundurchlässig, lässt aber einen Energiefluss zu. Bleiben wir bei besagter Cola-Flasche und lassen sie geschlossen. Die Temperatur steigt aber der Inhalt bleibt gleich.

Ein abgeschlossenen System lässt sich nur näherungsweise in die Praxis umsetzen, da - per Definition - sowohl Stofffluss wie auch Energiefluss unterbunden sein müssen. Daher nur näherungsweise ein Beispiel: die eiskalte Cola in einer verschlossenen Thermoskanne.


---

## Das Prinzip der Black Box

Vor der Detailanalyse wird das System innerhalb der Systemgrenze als **Black Box** ("schwarzer Kasten") modelliert. Der innere Aufbau, die Verschaltung und die einzelnen Teilfunktionen bleiben zunächst bewusst unberücksichtigt.

Der Fokus liegt ausschließlich auf den Schnittstellen zur Umwelt:

* **Was geht in das System hinein?** (Eingangsgrößen)
* **Was kommt aus dem System heraus?** (Ausgangsgrößen & Verlustgrößen)

```text        
                
                       Verarbeitung                 
E              +---------------------------+           A
I              |                           |           U
N      ========|=>       BLACK BOX         |==========>S
G  Information |                           |           G   | Information
Ä    Energie   |     (Innerer Aufbau       |           Ä   | Energie
N    Stoffe    |      vorerst verborgen)   |           N   | Stoffe
G      ========|=>                         |==========>G    (inkl. Verluste)
E              +---------------------------+           E
              
    

```