<!--

author:   	Tobias Kozlowski
email:    	tobias.kozlowski[a]bsz-tw-freiberg.lernsax.de

version:  	0.0.1

language: 	de
narrator: 	Deutsch Male

comment:  	Ausführliches interaktives Lernmodul zu Lektion 1 im Lernfeld 1 (Mechatronik & Produktionstechnologen).
tags:     	LF1, MECH,PT, Einführung, Lernsituation, Arbeitsplan, LOL


icon:  	 	  https://www.bsz-freiberg.de/templates/bszjw/img/logo.svg
logo:		    https://github.com/TobiKoz-git/Unterricht/blob/main/Elektrotechnik/Mechatroniker/Lernfeld_5/Grafiken/Nutzen_von_IT_Systemen__Tobias_Kozlowski_generated_with_Firefly.jpg?raw=true

mode:       Presentation


import: https://raw.githubusercontent.com/MINT-the-GAP/lia-board-mode/main/README.md
        https://raw.githubusercontent.com/LiaTemplates/lia-annotation/main/README.md
        


-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://github.com/TobiKoz-git/Unterricht/blob/main/Elektrotechnik/Produktionstechnologe/LF1/Lektion_1.md)


# ⚙️ Lektion 1: Mechatronische Systemanalyse & Strukturierung

Willkommen in **Lektion 1** des Lernfelds 1! In diesem Modul erarbeitest du dir das Fundament der Mechatronik: Wie zerlegt man ein komplexes Gesamtsystem in seine Bestandteile, wie zieht man Systemgrenzen und wie unterscheidet man die Informations- und Energieströme?
    
---

## 🎯 Lernziele dieser Lektion
Nach Bearbeitung dieser Lektion kannst du:
1. **Systemgrenzen und Schnittstellen** eines mechatronischen Systems definieren (Zielliste 1.1.1).
2. Komponenten exakt den drei Säulen **Sensorik, Informationsverarbeitung und Aktorik** zuordnen (Zielliste 1.1.1).
3. **Signal-, Stoff- und Energieflüsse** im System identifizieren und unterscheiden (Zielliste 1.3.1).
4. Den Unterschied zwischen **Lastenheft und Pflichtenheft** fachgerecht erklären (Zielliste 1.4.1).

---

## 📐 1. Theorie: Das mechatronische Grundsystem & Systemgrenzen

Ein mechatronisches System ist mehr als nur die Summe seiner Einzelteile. Es verbindet **Mechanik**, **Elektrotechnik/Elektronik** und **Informationstechnik**.
``` ascii
           ┌─────────────────────────────────────────┐
           │            UMWELT / UMGEBUNG            │
           │                                         │
           │     ┌─────────────────────────────┐     │
Energie  ──┼────>│      MECHATRONISCHES        │─────┼──> Nutzarbeit /
Signale  ──┼────>│          SYSTEM             │─────┼──> Status /
Stoffe   ──┼────>│ (Sensor - Steuerung - Aktor)│─────┼──> Stoffe
           │     └─────────────────────────────┘     │
           │                                         │
           └─────────────────────────────────────────┘
                                ▲
                            SYSTEMGRENZE
```
### 🔹 Systemgrenze und Umwelt
* **Innerhalb der Systemgrenze** befinden sich alle Bauteile, die direkt vom Konstrukteur beeinflusst und vom System gesteuert werden.
* **Außerhalb der Systemgrenze (Umwelt)** liegen Einflussgrößen wie Netzspannung, Umgebungstemperatur, der menschliche Bediener oder zu verarbeitende Werkstücke.

### 🔹 Schnittstellen zur Umwelt
Schnittstellen sind die Punkte, an denen das System Wechselwirkungen mit der Umwelt eingeht:
1. **Elektrische Schnittstellen:** z. B. 230 V Steckdose, Batterieklemmen, Steckverbinder.
2. **Informatorische Schnittstellen:** z. B. Taster, Touch-Displays, Funksignale, Bluetooth.
3. **Mechanische Schnittstellen:** z. B. Befestigungspunkte, Schienen, Wellenkupplungen.
4. **Material-/Stoffschnittstellen:** z. B. zu transportierende Bauteile, Desinfektionsflüssigkeit.

---

### ❓ Interaktiver Wissens-Check 1: Systemgrenzen & Schnittstellen

1. Was befindet sich **innerhalb** der Systemgrenze eines automatischen Garagentors? *(Wähle alle richtigen)*
   
   [[X]] Der DC-Antriebsmotor mit Schneckengetriebe
   [[X]] Die elektronische Steuerplatine mit Mikrocontroller
   [[ ]] Das 230V-Netz des Energieversorgers
   [[X]] Die Sicherheits-Lichtschranke an der Zarge
   [[ ]] Der Pkw, der in die Garage fährt

2. Welche Art von Schnittstelle stellt der Handsender einer Garagentor-Fernbedienung primär dar?
   
   [( )] Mechanische Schnittstelle
   [(X)] Informatorische Schnittstelle (Elektromagnetische Wellen / Funk)
   [( )] Stoffliche Schnittstelle
   [( )] rein thermische Schnittstelle

---

## 🏗️ 2. Theorie: Komponentenklassifizierung (Die 3 Grundpfeiler)

Jede Komponente in einem mechatronischen System lässt sich einer von drei Hauptfunktionsgruppen zuordnen:

| Funktionsgruppe | Aufgabe im System | Beispiele |
| :--- | :--- | :--- |
| **1. Sensorik** *(Informationserfassung)* | Erfasst physikalische Größen aus dem System/der Umwelt und wandelt sie in elektrische Signale um. | Lichtschranke, Induktionsschleife, Taster, Temperaturfühler, Drucksensor. |
| **2. Informationsverarbeitung** *(Steuerung/Regelung)* | Verarbeitet Eingangssignale nach einer programmierten Logik und erzeugt Steuersignale für Aktoren. | Mikrocontroller (ESP32, Arduino), SPS (Speicherprogrammierbare Steuerung), PC. |
| **3. Aktorik** *(Wirkung & Bewegung)* | Wandelt elektrische Steuersignale/Energie in mechanische Arbeit, Bewegung, Licht oder Wärme um. | Elektromotor, Pneumatikzylinder, Magnetventil, Signal-LED, Heizwendel. |

---

### ❓ Interaktiver Wissens-Check 2: Komponentenklassifizierung

Ordne die Bauteile der richtigen Funktionsgruppe zu:

- [(Sensorik (Erfassung)) (Verarbeitung (Steuerung)) (Aktorik (Wirkung))]
- [    (X)                      ( )                        ( )       ] Optische Einweg-Lichtschranke
- [    ( )                      (X)                        ( )       ] Speicherprogrammierbare Steuerung (SPS)
- [    ( )                      ( )                        (X)       ] 24V-DC-Schneckengetriebemotor
- [    (X)                      ( )                        ( )       ] Kapazitiver Füllstandssensor
- [    ( )                      ( )                        (X)       ] Magnetventil für Pneumatikzylinder
- [    ( )                      (X)                        ( )       ] ESP32-Mikrocontroller-Board

---

## 🌊 3. Theorie: Signal-, Stoff- und Energiefluss

In einem mechatronischen System fließen gleichzeitig drei Arten von Größen:

1. **Signalfluss (Information):** 
   * Transportiert Daten und Zustände (z. B. "Tor ist offen", "Taste gedrückt", "Temperatur = 22°C").
   * *Signalformen:* Analoge Spannungen (0–10 V), Ströme (4–20 mA), digitale Pulse, BUS-Protokolle.
   * *Leistung:* Vernachlässigbar gering ($P < 1\text{ W}$).

2. **Energiefluss (Leistung):** 
   * Transportiert die Energie zur Verrichtung von Arbeit.
   * *Wandlungskette:* Elektrische Energie $\rightarrow$ Leistungselektronik $\rightarrow$ Elektromotor $\rightarrow$ Mechanische Rotationsenergie $\rightarrow$ Getriebe $\rightarrow$ Mechanische Translation.
   * *Verluste:* Bei jeder Wandlung entsteht Verlustleistung (überwiegend Wärme).

3. **Stofffluss (Materie):** 
   * Transport von festen, flüssigen oder gasförmigen Stoffen.
   * *Beispiele:* Werkstücke auf einem Förderband, Desinfektionsmittel durch eine Pumpe, Druckluft in Schläuchen.

---

### ❓ Interaktiver Wissens-Check 3: Flussanalyse

- [(Signalfluss) (Energiefluss) (Stofffluss)]
- [    (X)             ( )             ( )     ] 5V-Schaltsignal vom Not-Halt-Taster an die SPS
- [    ( )             (X)             ( )     ] 230V-Netzeinspeisung zum Transformationsnetzteil
- [    ( )             ( )             (X)     ] Förderung von $2\text{ ml}$ Desinfektionsgel durch den Schlauch
- [    (X)             ( )             ( )     ] CAN-Bus-Datenpaket zwischen zwei Steuergeräten
- [    ( )             (X)             ( )     ] Rotationsenergie an der Motorwelle

---

## 📄 4. Theorie: Lastenheft vs. Pflichtenheft

Vor der Entwicklung eines technischen Systems stehen klare Absprachen zwischen Kunde und Entwickler.
``` ascii
┌──────────────────────────────────────┐
|             K U N D E                │
|  Formuliert Wünsche & Anforderungen  │
└──────────────────┬───────────────────┘
                   │erstellt
                   ▼
                  📄 L A S T E N H E F T  ( WAS soll entwickelt werden? )
                   │
                   │  Übergabe an Entwickler
                   ▼
                  📄 P F L I C H T E N H E F T  ( WIE wird es konkret umgesetzt? )
                   ▲
                   │  erstellt
┌──────────────────┴────────────────────┐
│     FIRMA / ENTWICKLER                │
│     Plant die technische Realisierung │
└───────────────────────────────────────┘
```

| Merkmal | Lastenheft | Pflichtenheft |
| :--- | :--- | :--- |
| **Wer erstellt es?** | **Auftraggeber / Kunde** | **Auftragnehmer / Entwickler** |
| **Kernfrage** | *„Was und wozu?“* | *„Wie und womit?“* |
| **Inhalt** | Zielsetzung, Anforderungsprofil, Rahmenbedingungen, Budget. | Technische Detaillierung, Schaltpläne, Bauteilauswahl, Zeitplan. |
| **Verbindlichkeit** | Grundlage für das Angebot. | Vertagliche Grundlage für die Abnahme der Anlage. |

---

### ❓ Interaktiver Wissens-Check 4: Lastenheft oder Pflichtenheft?

1. "Das Garagentor muss innerhalb von max. 12 Sekunden vollständig öffnen."
   [(X)] Aussage gehört ins **Lastenheft** (Kundenanforderung)
   [( )] Aussage gehört ins **Pflichtenheft** (Technische Detaillösung)

2. "Einsatz eines DC-Motors Typ GR 63x55 mit einem Schneckengetriebe SG 80 (Übersetzung i=20:1)."
   [( )] Aussage gehört ins **Lastenheft**
   [(X)] Aussage gehört ins **Pflichtenheft**

---

## 🛠️ Arbeitsauftrag: Portfolio-Baustein 1

> **Bearbeitungszeit:** ca. 30–45 Minuten  
> **Ziel:** Erstelle die vollständige Systemanalyse für **dein gewähltes Referenzsystem** in deinem Portfolio.

### **Schritt 1: Systemwahl**
Wähle **eines** der folgenden Systeme aus:
* **System A:** Automatischer Garagentorantrieb mit Funkfernbedienung und Lichtschranke
* **System B:** Kontaktloser Desinfektionsmittelspender (Akkubetrieb)
* **System C:** Automatische Parkhausschranke mit Induktionsschleife

### **Schritt 2: Aufgaben im Portfolio bearbeiten**
1. **Systemgrenze & Umwelt:** Zeichne oder beschreibe die Systemgrenze deines Systems. Nenne 3 Umweltfaktoren und 3 konkrete Schnittstellen.
2. **Komponenten-Tabelle:** Erstelle eine Tabelle und ordne mindestens **6 Bauteile** deines Systems den Kategorien *Sensorik*, *Verarbeitung* und *Aktorik* zu.
3. **Fluss-Beschreibung:** Beschreibe den Ablauf der Auslösung von **Signalfluss** (von der Eingabe bis zur Steuerung) und **Energiefluss** (von der Einspeisung bis zur Bewegung).
4. **Anforderungsspezifikation:** Formuliere 2 typische Sätze aus dem **Lastenheft** und 2 dazu passende technische Lösungen für das **Pflichtenheft**.

---

### 🔍 Ausklappbare Hilfen & Musterlösungen zur Selbstkontrolle

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

## 📊 Kann-Liste Check: Lektion 1

Überprüfe abschließend deinen Lernfortschritt für Lektion 1:

- [(1 - Noch unsicher) (2 - Mit Hilfe) (3 - Selbstständig sicher) (4 - Kann ich erklären)]
- [    ( )                ( )              ( )                     ( )         ] Ich kann Systemgrenzen ziehen und Schnittstellen zur Umwelt benennen.
- [    ( )                ( )              ( )                     ( )         ] Ich kann Komponenten in Sensorik, Verarbeitung und Aktorik einteilen.
- [    ( )                ( )              ( )                     ( )         ] Ich kann Signal-, Stoff- und Energiefluss im System beschreiben.
- [    ( )                ( )              ( )                     ( )         ] Ich kann Lasten- und Pflichtenheft voneinander abgrenzen.


