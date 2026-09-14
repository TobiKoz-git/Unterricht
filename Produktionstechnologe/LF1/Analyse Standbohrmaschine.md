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



# Modul: Systembeschreibung & Funktionseinheiten

> **Lernziel:** Du verstehst den Aufbau komplexer mechatronischer Systeme, kannst die Hierarchie von Gesamtsystemen über Teilsysteme bis zu den Bauelementen aufschlüsseln und kennst die sechs zentralen Funktionseinheiten.

---

## 1. Systembeschreibung und Hierarchie

Mechatronische Systeme setzen sich aus mechanischen, elektrischen, pneumatischen und hydraulischen Komponenten sowie integrierter Software zusammen. Das geordnete Zusammenwirken aller Teile ergibt die Funktionsweise des Gesamtsystems.

Um komplexe Anlagen zu verstehen, führen wir die Analyse gemeinsam am Beispiel einer Standbohrmaschine durch.

Eine Standbohrmaschine ist ein klassisches mechatronisches System. Sie kombiniert elektrische Komponenten (Motor, Schalter), mechanische Bauteile (Riemengetriebe, Spindel, Hebel) und moderne Sicherheitstechnik.


### Die Hierarchie-Ebenen der Bohrmaschine:

1. **Gesamtsystem:** Standbohrmaschine.
2. **Teilsysteme:** 
   * *Antriebssystem* (Elektromotor, Kondensator, Ansteuerung)
   * *Übertragungssystem* (Keilriementrieb, Riemenscheiben)
   * *Arbeits- und Vorschubeinheit* (Bohrspindel, Pinole, Bohrfutter, Handkreuz)
   * *Tragstruktur* (Maschinenfuß, Säule, Führung, Bohrtisch)
3. **Funktionen:**
   * **Hauptfunktion:** Spanende Formgebung durch Bohren (Erzeugen von kreiszylindrischen Senkungen oder Bohrungen in Werkstücken).
   * **Teilfunktionen:** Elektrische Energie in Rotation wandeln, Drehzahl/Drehmoment anpassen, Schnittbewegung auf das Werkzeug übertragen, Vorschubbewegung ausführen, Werkstück halten und stützen.

```ASCII

                [ Gesamtsystem: Standbohrmaschine ]
                               │
  ┌────────────────────────────┼────────────────────────────┐
  ▼                            ▼                            ▼
[ Teilsystem: Antrieb ]   [ Teilsystem: Getriebe ]   [ Teilsystem: Gestell & Tisch ]
│                            │                            │
▼                            ▼                            ▼
• Elektromotor             • Keilriemen / Scheiben      • Maschinenfuß & Säule
• Schaltelektronik         • Bohrspindel                • Bohrtisch & Führung

```

---

### Quiz: Systemhierarchie der Standbohrmaschine

* Prüfe dein Verständnis zur Zerlegung der Bohrmaschine:

1. Was beschreibt die *Hauptfunktion* einer Standbohrmaschine?

[(x)] Erzeugen von kreisförmigen Bohrungen im Werkstück
[( )] Das Wandeln von Wechselstrom in Gleichstrom
[( )] Das automatische Transportieren von Werkstücken zur nächsten Station

2. Welche Komponenten gehören direkt zum Teilsystem *Übertragungssystem*?

[[x]] Getriebe
[[x]] Keilriemen
[[ ]] Maschinenfuß
[[ ]] Not-Aus-Schalter

3. Welche Teilfunktion übernimmt die *Bohrspindel mit der Pinole*?

[( )] Sie wandelt Netzspannung in Magnetismus um.
[(x)] Sie überträgt die Drehbewegung auf das Bohrfutter und ermöglicht die vertikale Vorschubbewegung.
[( )] Sie entsorgt die Späne automatisch aus dem Arbeitsraum.


---

## 2. Die sechs Funktionseinheiten der Bohrmaschine

Nach **DIN EN 61346** teilen wir die Bauteile der Bohrmaschine in sechs genormte Funktionseinheiten ein:

### 1. Antriebseinheit
* **Funktion:** Stellt die notwendige mechanische Energie bereit.
* **Bauteile an der Bohrmaschine:** Elektromotor.

### 2. Energieübertragungseinheit
* **Funktion:** Leitet die Bewegung weiter, passt die Drehzahl an oder wandelt Bewegung Formen um.
* **Bauteile an der Bohrmaschine:** Keilriemen, Riemenscheiben, Bohrspindel, Verzahnung der Pinole für den Vorschub.

### 3. Stütz- und Trageinheit
* **Funktion:** Nimmt Gewichtskräfte sowie Schnitt- und Vorschubkräfte auf und führt bewegliche Teile.
* **Bauteile an der Bohrmaschine:** Schwerer Maschinenfuß, vertikale Säule, höhenverstellbarer Bohrtisch, Motorgehäuse.

### 4. Arbeitseinheit
* **Funktion:** Führt die eigentliche technologische Aufgabe (das Bohren) am Werkstück aus.
* **Bauteile an der Bohrmaschine:** Bohrfutter (Spannzeug), Spiralbohrer (Werkzeug), Maschinenschraubstock (Werkstückspannung).

### 5. Steuerungs- und Regelungseinheit
* **Funktion:** Verarbeitet Befehle/Signale zur Überwachung und Beeinflussung des Prozesses.
* **Bauteile an der Bohrmaschine:** EIN/AUS-Schalter, Not-Aus-Taster, Mikroschalter an der Riemenabdeckung (Sicherheitsschaltung), Handkreuz für den manuellen Vorschub.

### 6. Ver- und Entsorgungseinheit
* **Funktion:** Versorgt die Maschine mit Energie oder Betriebsstoffen und leitet Abfälle ab.
* **Bauteile an der Bohrmaschine:** Netzanschlusskabel mit Schukostecker, Klemmenkasten am Motor, ggf. Kühlmitteleinrichtung und Spänewanne.

---

## 3. Quiz: Funktionseinheiten zuordnen

* Ordne die Bauteile der Standbohrmaschine den richtigen Einheiten zu:

1. Der **Maschinenfuß und die Stahlsäule** gehören zu welcher Funktionseinheit?
   [( )] Antriebseinheit
   [(x)] Stütz- und Trageinheit
   [( )] Ver- und Entsorgungseinheit

2. Welches Bauteil bildet die **Arbeitseinheit** der Bohrmaschine?
   [[x]] Der eingespannte Spiralbohrer
   [[x]] Das Bohrfutter
   [[ ]] Das Netzkabel
   [[ ]] Der Keilriemen

3. Wie ist der **EIN/AUS-Schalter mit Not-Aus-Funktion** einzuordnen?
   [( )] Energieübertragungseinheit
   [( )] Arbeitseinheit
   [(x)] Steuerungs- und Regelungseinheit

4. Das **Keilriemengetriebe** ist eine...
   [(x)] ...Energieübertragungseinheit, da es Drehzahl und Drehmoment vom Motor auf die Spindel übersetzt.
   [( )] ...Ver- und Entsorgungseinheit, da es den Motor mit Strom versorgt.
   [( )] ...Arbeitseinheit, da es direkt die Späne vom Werkstück abhebt.

---

## 4. Zusammenfassung & Check-Out

> **Merke:** 
> Auch eine eigenständige Werkzeugmaschine wie die Standbohrmaschine lässt sich lückenlos in die sechs Funktionseinheiten zerlegen. Dieses Schema hilft dir später bei der Fehlersuche: Wenn die Bohrspindel steht, obwohl der Motor läuft, liegt der Fehler in der **Energieübertragungseinheit** (z. B. Keilriemen gerissen).