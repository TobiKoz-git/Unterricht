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



# Modul: Systembeschreibung & Funktionseinheiten (Akkubohrmaschine)

> **Lernziel:** Du verstehst den mechatronischen Aufbau einer Akkubohrmaschine, kannst das Gesamtsystem in Teilsysteme und Teilfunktionen zerlegen und die Bauteile den sechs zentralen Funktionseinheiten zuordnen.

---

## 1. Systembeschreibung und Hierarchie

Eine Akkubohrmaschine (Akkuschrauber) ist ein hochintegriertes mechatronisches System. Sie verknüpft moderne Akkutechnologie und Leistungselektronik mit kompakter Feinmechanik (Planetengetriebe) und Ergonomie.

Wir gliedern das Gesamtsystem systematisch in seine Ebenen:


``` ascii
                            [ Gesamtsystem: Akkubohrmaschine ]
                                           │
              ┌────────────────────────────┼────────────────────────────┐
              ▼                            ▼                            ▼
[ Teilsystem: Energiesystem ]  [ Teilsystem: Antrieb/Getriebe ] [ Teilsystem: Werkzeugaufnahme ]
                │                            │                            │
                ▼                            ▼                            ▼
        • Li-Ion-Akkupack            • BLDC-Motor                 • Schnellspannbohrfutter
        • Schnittstelle/Kontakte     • 2-Gang-Planetengetriebe    • Werkzeug (Bit / Bohrer)
```



### Die Hierarchie-Ebenen der Akkubohrmaschine:

1. **Gesamtsystem:** Akkubohrmaschine.
2. **Teilsysteme:** 
   * *Energiesystem* (Li-Ion-Akku, BMS-Schutzelektronik, Kontakte)
   * *Antriebs- und Steuerungssystem* (Bürstenloser Motor, Drückschalter, Elektronik, Rechts-/Linkslauf-Umschalter)
   * *Übertragungssystem* (Getriebe, Drehmomentkupplung, Spindel)
   * *Werkzeugaufnahmesystem* (Bohrfutter, Bithalter)
   * *Gehäusesystem* (Gehäuse, Handgriff, Gürtelclip)
3. **Funktionen:**
   * **Hauptfunktion:** Ortunabhängiges Fügen (Schrauben) und Bohren.
   * **Teilfunktionen:** Chemische Energie speichern und bereitstellen, elektrische Energie in Rotation wandeln, Drehmoment und Drehzahl anpassen, Drehmoment begrenzen.

---

### Quiz: Systemhierarchie der Akkubohrmaschine


1. Was beschreibt die *Hauptfunktion* einer Akkubohrmaschine?

  [(x)] Mobiles, netzunabhängiges Eindrehen von Schrauben und Bohren von Löchern
  [( )] Das Umwandeln von 230V Wechselspannung in Druckluft
  [( )] Das automatische Abmessen von Bauteildicken

2. Welche Komponenten gehören zum Teilsystem *Energiesystem*?

  [[x]] Lithium-Ionen-Akkupack
  [[x]] Steckkontakte zur Leistungsübertragung
  [[ ]] Schnellspannbohrfutter
  [[ ]] Planetengetriebe

3. Welche Teilfunktion übernimmt das *mehrstufige getriebe* im Akkuschrauber?

  [( )] Es schützt den Akku vor Tiefentladung.
  [(x)] Es wandelt die hohe Motordrehzahl in ein größeres Drehmoment um und ermöglicht die Gangumschaltung.
  [( )] Es hält die Bohrmaschine am Gürtel des Benutzers.

---

## 2. Die sechs Funktionseinheiten der Akkubohrmaschine

Auch der kompakte Akkuschrauber lässt sich nach **DIN EN 61346** in die sechs Funktionseinheiten unterteilen:

### 1. Antriebseinheit
* **Funktion:** Wandelt elektrische Energie aus dem Akku in mechanische Rotationsenergie um.
* **Bauteile an der Akkubohrmaschine:** Elektromotor (z. B. Bürstenloser Gleichstrommotor (BLDC-Motor)) und Getriebe.

### 2. Energieübertragungseinheit
* **Funktion:** Passt Drehzahl und Drehmoment an und überträgt die Bewegung auf die Spindel.
* **Bauteile an der Akkubohrmaschine:** Mehrstufiges Getriebe, Gangwahlschalter (1. Gang / 2. Gang), Bohrspindel.

### 3. Stütz- und Trageinheit
* **Funktion:** Nimmt Reaktionskräfte (Drehmoment) auf, schützt die Innenbauteile und ermöglicht die Handhabung.
* **Bauteile an der Akkubohrmaschine:** Ergonomisches Kunststoffgehäuse mit Softgrip, Getriebegehäuse, Kugellager der Spindel.

### 4. Arbeitseinheit
* **Funktion:** Hält das Werkzeug und führt die eigentliche Bearbeitung/Fügeoperation aus.
* **Bauteile an der Akkubohrmaschine:** Schnellspannbohrfutter, eingesetzter Spiralbohrer oder Schrauberbit.

### 5. Steuerungs- und Regelungseinheit
* **Funktion:** Dosiert die Leistung, bestimmt die Drehrichtung und begrenzt das Drehmoment zum Schutz der Schraube.
* **Bauteile an der Akkubohrmaschine:** Drückerschalter (Elektronikschalter für stufenlose Drehzahl), Rechts-/Linkslauf-Umschalter, Einstellring für die Drehmomentkupplung, Motorsteuerungselektronik.

### 6. Ver- und Entsorgungseinheit
* **Funktion:** Speichert die benötigte Energie und versorgt die Elektronik und den Motor.
* **Bauteile an der Akkubohrmaschine:** Wechselbarer Li-Ion-Akkupack, Akkukontakte und internes Batteriemanagementsystem (BMS).

---

## 3. Vertiefungs-Quiz: Funktionseinheiten zuordnen

* Ordne die Bauteile der Akkubohrmaschine den richtigen Einheiten zu:

1. Der **wechselbare Li-Ion-Akkupack** gehört zu welcher Funktionseinheit?
   
[( )] Antriebseinheit
[( )] Steuerungs- und Regelungseinheit
[(x)] Ver- und Entsorgungseinheit

2. Welches Bauteil stellt die **Steuerungs- und Regelungseinheit** dar?

[[x]] Der Stufenlos-Drückerschalter zur Drehzahlsteuerung
[[x]] Der Einstellring für das maximale Drehmoment
[[ ]] Das Gehäuse
[[ ]] Der Motor

3. Wie ist das **Schnellspannbohrfutter mit eingesetztem Bit** einzuordnen?

[( )] Energieübertragungseinheit
[(x)] Arbeitseinheit
[( )] Stütz- und Trageinheit

4. Das **2-Gang-Planetengetriebe** ist eine...

[(x)] ...Energieübertragungseinheit, da es die Drehbewegung des Motors übersetzt.
[( )] ...Arbeitseinheit, weil es direkt in das Holz bohrt.
[( )] ...Ver- und Entsorgungseinheit, da es den Motor kühlt.

---

## 4. Zusammenfassung & Check-Out

> **Merke:** 
> Durch die Zuordnung zu den sechs Funktionseinheiten wird verständlich, wie Mechanik, Elektrik und Elektronik auf engstem Raum zusammenarbeiten. Fällt bei einem Akkuschrauber beispielsweise das Drehmoment unter Last ab, obwohl der Motor voll dreht, liegt der Fehler in der **Energieübertragungseinheit** (z. B. durchrutschende Drehmomentkupplung oder defektes Planetengetriebe).




