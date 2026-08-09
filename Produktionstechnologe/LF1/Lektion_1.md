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

# Lektion 1: Systemdenken & Anforderungsanalyse

Willkommen zur Lektion 1! In dieser Lektion erarbeiten wir uns die grundlegende Methodik, um technische Projekte systematisch zu analysieren, zu planen und umzusetzen.


## 1. Start: Problemstellung

**Impuls: Warum scheitern technische Projekte oft?**

![Produktkonfiguration](https://github.com/TobiKoz-git/Unterricht/blob/main/Produktionstechnologe/LF1/Gemini_Generated_Image_ugmf28ugmf28ugmf.png)
*Quelle: [Product Configuration](https://github.com/TobiKoz-git/Unterricht/blob/main/Produktionstechnologe/LF1/Gemini_Generated_Image_ugmf28ugmf28ugmf.png) *Chaotisches Konfigurations-Ergebnis in Werkshalle. Generiert mittels künstlicher Intelligenz (Google Gemini).*

Stell dir vor, ein Kunde bestellt bei einem Ingenieurbüro eine Anlage. Monate später wird geliefert – und der Kunde ist entsetzt. Die Maschine ist zu groß, zu laut und viel zu kompliziert zu bedienen. Der Ingenieur wehrt sich: *"Wir haben genau das gebaut, was technisch besprochen wurde!"*

> **Diskussion:** Woran liegt das? Oft scheitert es an Missverständnissen zwischen **Kundenwünschen** (Alltagssprache) und **technischer Umsetzung** (Fachsprache).

In den folgenden Schritten (Selbststudium) erarbeitest du dir das Rüstzeug, um solche Fehler zu vermeiden.

## 2. Infotext 1: Grundbegriffe der Systemtechnik

### Was ist ein technisches System?
Stell dir eine einfache Taschenlampe vor: Sie besteht aus einem Gehäuse, einem Schalter, einer Batterie und einer LED. Jedes dieser Teile für sich allein bringt dir im Dunkeln wenig. Erst wenn sie zusammenarbeiten, erfüllen sie eine gemeinsame Aufgabe: Licht erzeugen.

> **Definition:** Ein **technisches System** ist eine Ansammlung von Bauteilen, die miteinander verbunden sind und zusammenarbeiten, um eine bestimmte Aufgabe (Funktion) zu erfüllen.

### Die Systemgrenze – Wo fängt das System an, wo hört es auf?
Um ein technisches System zu verstehen oder zu planen, muss man genau festlegen, was zum System gehört und was außerhalb in der Umwelt liegt. Dafür zieht man eine Systemgrenze.

* **Innerhalb der Systemgrenze:** Alle Bauteile, die wir direkt betrachten, steuern oder bauen.
* **Außerhalb der Systemgrenze (Umwelt):** Alles, was das System umgibt (z. B. der Raum, der Benutzer, das Stromnetz oder das Wetter).

> **Definition:** Die **Systemgrenze** ist eine gedankliche (oder reale) Trennlinie. Sie grenzt das technische System eindeutig von seiner Umgebung ab. In Zeichnungen wird sie als gestrichelte Linie dargestellt.

### Ein- und Ausgangsgrößen – Was geht rein, was kommt raus?
Kein technisches System arbeitet völlig isoliert. Es steht immer im Austausch mit seiner Umwelt:

* **Eingangsgrößen (Input):** Alles, was von außen in das System hineingeht, damit es arbeiten kann (z. B. elektrische Spannung aus der Steckdose, Druck auf einen Start-Knopf, Kaffeebohnen).
* **Ausgangsgrößen (Output):** Alles, was das System an die Umwelt abgibt (z. B. eine Bewegung, Licht, fertiger Kaffee, Abwärme).
* **Störgrößen:** Unerwünschte Einflüsse aus der Umgebung, die das System beeinträchtigen (z. B. Kälte, Staub, Reibung).

```ascii
                     [ STÖRGRÖSSEN ]
               (z. B. Kälte, Staub, Reibung)
                          │
                          ▼
┌ - - - - - - - - - - - - - - - - - - - - - - - - - ┐
¦ SYSTEMGRENZE                                      ¦
¦                                                   ¦
¦   Eingangsgrößen ──►   TECHNISCHES   ──► Ausgangsgrößen
¦ (z. B. Strom, Taste)    SYSTEM        (z. B. Bewegung)
¦                       (z. B. Motor)               ¦
¦                                                   ¦
└ - - - - - - - - - - - - - - - - - - - - - - - - - ┘
```
---

## 3. Infotext 2: Lastenheft und Pflichtenheft

Das Grundproblem: Wünsche treffen auf Technik

Stell dir vor, ein Kunde sagt zum Entwickler: "Ich brauche ein Förderband, das extrem schnell und super stark ist!" Der Entwickler baut ein riesiges Band mit Industriemotor. Bei der Übergabe ist der Kunde schockiert: Die Bauteile fliegen vom Band und die Anlage war viel zu teuer.
Warum passiert das? Kunden sprechen die Sprache des Alltags (Wünsche, Ziele). Entwickler benötigen die Sprache der Technik (Zahlen, Maße, elektrische Spannungen). Um Fehler zu vermeiden, nutzt man in der Industrie zwei Dokumente.

Das Lastenheft (Kundensicht)

Das Lastenheft wird vom Auftraggeber (Kunden) geschrieben. Es beschreibt, was er haben möchte, ohne sich in technischen Details zu verlieren.
Definition: Das Lastenheft beschreibt, WAS das System leisten soll und WARUM es gebraucht wird. Beispiel: „Das Garagentor soll sich per Funk aus dem Auto öffnen lassen und niemanden einklemmen.“

Das Pflichtenheft (Entwicklersicht)

Das Pflichtenheft ist die technische Antwort des Entwicklers. Er übersetzt die Wünsche des Kunden in exakte technische Vorgaben.

Definition: Das Pflichtenheft beschreibt detailliert, WIE und WOMIT die Kundenwünsche technisch umgesetzt werden. Beispiel: „Funkfrequenz f = 868 MHz, Abschaltkraft bei Hindernis F ≤ 150 N, Auslösezeit t < 0,5 s.“


Übersicht & Vergleich

| Kriterium | Lastenheft (Kundensicht) | Pflichtenheft (Entwicklersicht) |
| -------- | :------: | -------: |
| Wer schreibt es?     |   Kunde / Auftraggeber   |     Entwickler / Projektteam |
| Kernfrage | WAS soll gemacht werden und WARUM? | WIE und WOMIT wird es umgesetzt? |
| Sprache     |   Umgangssprache, Wünsche, Ziele   |     Fachsprache, Maße, Parameter |

---

## 4. Formativer Wissenstest

Überprüfe dein Wissen aus den Infotexten, bevor wir in die Arbeitsphase starten.

1. Wer ist in erster Linie für das Verfassen des Lastenhefts verantwortlich?

[(X)] Der Kunde / Auftraggeber
[( )] Der Entwickler
[( )] Die Montageabteilung

2. Was wird durch die Systemgrenze abgetrennt?

[( )] Der mechanische vom elektrischen Teil der Anlage.
[(X)] Das technische System von seiner Umwelt.
[( )] Das Lastenheft vom Pflichtenheft.

3. Eine Taste wird gedrückt, um einen Motor zu starten. Was ist das Tastensignal in diesem System?

[(X)] Eine Eingangsgröße
[( )] Eine Störgröße
[( )] Eine Ausgangsgröße

4. Welches Dokument beantwortet die Frage "WIE und WOMIT wird etwas technisch umgesetzt?"

[( )] Das Lastenheft
[( )] Das Handbuch
[(X)] Das Pflichtenheft

5. Staub und Reibung sind klassische Beispiele für...

[( )] Ausgangsgrößen
[( )] Eingangsgrößen
[(X)] Störgrößen

---

## 5. Transferübung (Zuordnung)

Ordne die folgenden Aussagen korrekt dem Lastenheft (Kundensicht) oder dem Pflichtenheft (Entwicklersicht) zu.

"Die maximale Leistungsaufnahme darf 400 W bei 230 V AC nicht überschreiten."

[( )] Lastenheft
[(X)] Pflichtenheft

"Der Desinfektionsmittelspender muss kontaktlos funktionieren, um die Hygiene zu verbessern."

[(X)] Lastenheft
[( )] Pflichtenheft

"Der Schalldruckpegel der Anlage darf in 1 m Entfernung maximal 55 dB(A) betragen."

[( )] Lastenheft
[(X)] Pflichtenheft

"Die Schranke darf keine Autos einklemmen oder beschädigen."

[(X)] Lastenheft
[( )] Pflichtenheft

Team-Austausch: Setzt euch nun in euren 3–4er Teams zusammen (Peer-Review). Gleicht eure Ergebnisse ab und klärt eventuelle Begriffsfragen im Team, bevor ihr in den Lernraum wechselt.

---

## 6. LERNRAUM (Arbeitsblatt)
Thema: Vom Kundenwunsch zum technischen System

Hinweis: Wählt in eurem Team eines der drei folgenden Übungsbeispiele aus und bearbeitet alle Aufgaben exakt für dieses System. Nutzt dafür Papier oder ein digitales Board.



Beispiel-Pool zur Auswahl:

- Beispiel A: Automatisches Garagentor (Manuelles Öffnen bei Regen ist unbequem. Ein Motor soll das Tor per Funk öffnen/schließen. Ein Einklemmschutz ist Pflicht.)
- Beispiel B: Kontaktloser Desinfektionsmittelspender (Manueller Pumpdruck ist unhygienisch. Bei Annäherung der Hand soll automatisch eine Dosis abgegeben werden.)
- Beispiel C: Automatische Parkhausschranke (Schranke soll bei Ticketabgabe öffnen und nach Durchfahrt automatisch schließen, ohne Autos einzuklemmen.)

### Aufgabe 1: Ist-Analyse & Lastenheft (Kundensicht)
Beschreibt 2 Schwachstellen des bisherigen manuellen Zustands.
Formuliert aus Kundensicht 3 funktionale und 2 nicht-funktionale Anforderungen für das Lastenheft.

### Aufgabe 2: Pflichtenheft & Technische Parameter (Entwicklersicht)
Übersetzt die Kundenanforderungen aus Aufgabe 1 in konkrete, messbare technische Parameter für das Pflichtenheft. (Beispiel: Lastenheft = "Schnelles Öffnen" -> Pflichtenheft = "Öffnungszeit t ≤ 10 s")

### Aufgabe 3: Systemgrenze & Blockschaltbild
Zeichnet ein Blockschaltbild eures gewählten Systems:
Zeichnet eine gestrichelte Systemgrenze.
Tragt Eingangsgrößen, Ausgangsgrößen und mindestens 2 Störgrößen ein.
Transferübung: Methodencheck
Erklärt kurz in eigenen Worten: Warum reicht ein Lastenheft alleine nicht aus, um direkt mit dem Bau einer Anlage zu beginnen?

---

## 7. LERNRAUM: 🔍 Ausklappbare Hilfen & Musterlösungen zur Selbstkontrolle


<details>
<summary>📌 **Musterlösung für System A (Garagentor)** anzeigen</summary>

* **Systemgrenze:** Gehäuse der Steuerung, Elektromotor, Schneckengetriebe, Führungsschiene mit Laufkette, Lichtschrankensender/-empfänger, Funkempfänger-Platine.
* **Umwelt:** 230V-Netzspannung, Umgebungstemperatur/Regen, Garageneinfahrt, Handsender, Bediener.
* **Schnittstellen:**
  1. *Elektrisch:* Steckdose 230 V AC.
  2. *Informatorisch:* Funk-Signal (868 MHz) vom Handsender.
  3. *Mechanisch:* Befestigungswinkel an Garagendecke und Torblatt.
* **Komponenten:**
  * *Sensorik:* Lichtschranke (`-B1`), Hall-Sensor für Drehzahl (`-B2`).
  * *Verarbeitung:* Mikrocontroller-Steuerplatine (`-K1`).
  * *Aktorik:* 24V DC-Motor (`-M1`), Relais für Richtungswechsel (`-Q1`), Warn-LED (`-P1`).
* **Flussbeispiel:**  
  *Signalfluss:* Handsender $\rightarrow$ Funkempfänger $\rightarrow$ Mikrokontroller-Eingang $\rightarrow$ Relais-Ansteuerung.  
  *Energiefluss:* 230V AC Netz $\rightarrow$ Trafo/Netzteil (24V DC) $\rightarrow$ Motor $\rightarrow$ Getriebe $\rightarrow$ Kette $\rightarrow$ Bewegung Torblatt.
</details>

<details>
<summary>📌 **Musterlösung für System B (Desinfektionsspender)** anzeigen</summary>

* **Systemgrenze:** Kunststoffgehäuse, Infrarot-Sensorik, Steuerplatine, Batteriefach/Akku, Membranpumpe, Schlauchsystem, Auslassdüse.
* **Umwelt:** Hand des Nutzers, Raumlicht, Desinfektionsmittel-Nachfüllflasche.
* **Schnittstellen:**
  1. *Stofflich:* Einlassstutzen für Nachfüllflasche, Sprühdüse.
  2. *Informatorisch:* IR-Reflexionsstrahl zur Handerkennung.
  3. *Elektrisch:* USB-C Ladebuchse für Akku.
* **Komponenten:**
  * *Sensorik:* IR-Reflexionssensor (`-B1`), Füllstandssensor (`-B2`).
  * *Verarbeitung:* Low-Power Mikrocontroller (`-K1`).
  * *Aktorik:* 6V DC-Pumpenmotor (`-M1`), Status-LED (`-P1`).
</details>

<details>
<summary>📌 **Musterlösung für System C (Parkhausschranke)** anzeigen</summary>

* **Systemgrenze:** Schrankengehäuse, Frequenzumrichter, Drehstrommotor, Planetengehirre, Schrankenbaum, Induktionsschleifen-Auswertegerät.
* **Umwelt:** Pkw/Lkw, Fahrbahn, Regen/Frost, Kassenautomat/Parkhaus-Server.
* **Schnittstellen:**
  1. *Elektrisch:* 230V/400V Festanschluss.
  2. *Informatorisch:* Potentialfreier Kontakt vom Ticketleser / Kennzeichenscanner.
  3. *Mechanisch:* Fundamentverankerung im Boden.
* **Komponenten:**
  * *Sensorik:* Induktionsschleife im Boden (`-B1`), Endlagenschalter Oben/Unten (`-B2`, `-B3`).
  * *Verarbeitung:* Industrie-SPS (`-K1`).
  * *Aktorik:* 230V-Drehstrommotor (`-M1`), Frequenzumrichter (`-Q1`), Ampel Rot/Grün (`-P1`, `-P2`).
</details>

---


Hier findet ihr eine mögliche Lösung, falls ihr Beispiel A (Garagentor) gewählt habt. Gleicht eure Ergebnisse ab.

**Aufgabe 1: Ist-Analyse & Lastenheft**

Ist-Zustand:
1. Anheben erfordert Kraftaufwand.
2. Auto muss bei schlechtem Wetter verlassen werden.

Lastenheft (Funktional):
Öffnen/Schließen per Funkfernbedienung aus dem Auto heraus.
Automatischer Stopp und Auffahren bei einem Hindernis.
Manuelle Notentriegelung bei Stromausfall.

Lastenheft (Nicht-Funktional):
Betrieb an haushaltsüblicher 230 V-Steckdose.
Maximale Lautstärke im Betrieb darf nicht störend sein.

**Aufgabe 2: Pflichtenheft & Technische Parameter**

Anforderung aus Lastenheft
Technischer Systemparameter (Pflichtenheft)
Zielwert / Einheit
Funkfernbedienung
Trägerfrequenz f / Reichweite r
f = 868 MHz, r ≥ 20 m
Einklemmschutz
Abschaltkraft F_Abschalt bei Blockade
F_Abschalt ≤ 150 N (t < 0,5 s)
Notentriegelung
Mechanische Notentriegelung
Betätigungskraft F ≤ 50 N
Spannungsversorgung
Eingangsspannung U / Leistung P
U = 230 V AC, P_Max ≤ 400 W
Geräuschentwicklung
Schalldruckpegel L_p
L_p ≤ 55 dB(A) in 1 m

**Aufgabe 3: Systemgrenze & Blockschaltbild**
```ascii
                         [ Störgrößen ]
             • Windlast / Schneelast auf dem Tor
             • Hindernisse im Fahrweg
                          │
                          ▼
┌ - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - ┐
¦ SYSTEMGRENZE: GARAGENTOR-AUTOMATISIERUNG                      ¦
¦                                                               ¦
¦  [Eingangsgrößen]                               [Ausgangsgrößen]
¦  • El. Energie (230 V AC)  ──► ┌──────────┐ ───► • Mechanische
¦  • Funksignal (868 MHz)    ──► │ Steuerung│       Bewegung (Weg s)
¦  • Tastersignal (Innen)    ──► │   &      │ ───► • Optisches Signal
¦  • Lichtschrankensignal    ──► └──────────┘       (Warnleuchte)
¦                                                               ¦
└ - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - ┘
```

---

## 8. BEWERTUNGSRAUM: Arbeitsauftrag Frässtation
**Arbeitsauftrag für dein Projektteam:**
Übertragt die nun geübte Methodik auf eure reale Lernsituation (Vollautomatisierung der Frässtation) und legt die Ergebnisse strukturiert auf eurem Collaboard ab.

Eure Abgabe-Aufgaben im Collaboard:
1. Ist-Analyse & Lastenheft der Frässtation:
- Nennt 3 Schwachstellen des manuellen Bestückungsprozesses (siehe Handlungssituation: Unfälle, Ergonomie, Taktzeit).
- Formuliert 3 funktionale und 2 nicht-funktionale Anforderungen der Unternehmensleitung an die automatisierte Station.
2. Pflichtenheft-Parameter:
- Übersetzt die Anforderungen in exakte technische Parameter (z. B. geforderte Taktzeit t_Takt, Greifkraft F, Sicherheitskategorie/Lichtgitter).
3. Systemgrenze & Schnittstellen:
- Zeichnet das Blockschaltbild der automatisierten Station (Förderband + Handling + Fräsmaschine) inkl. Systemgrenze, Ein-/Ausgangsgrößen und Störgrößen (z. B. Späne, Bauteiltoleranzen).


---

## 9. Reflexion / Selbsttest

Überprüfe deinen eigenen Lernfortschritt am Ende dieser Lektion:

- [ ] Ich kenne den Unterschied zwischen einem Lastenheft (Kundensicht) und einem Pflichtenheft (Entwicklersicht).
- [ ] Ich kann vage Kundenwünsche in messbare, technische Parameter übersetzen.
- [ ] Ich weiß, was eine Systemgrenze ist und kann sie in einem Blockschaltbild anwenden.
- [ ] Ich kann Eingangsgrößen, Ausgangsgrößen und Störgrößen an einem technischen System identifizieren.
- [ ] Wir haben als Team unsere Ergebnisse zur Frässtation erfolgreich im Collaboard dokumentiert.
