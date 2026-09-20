<!--

author:     Tobias Kozlowski
email:      tobias.kozlowski[a]bsz-tw-freiberg.lernsax.de

version:    0.0.1

language:   de
narrator:   Deutsch Male

comment:  Lösungsblatt zu Übung 1: Grundlagen (Spannung, Strom, ohmsches Gesetz, Leistung)
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



# Übung 1 – Mathematische Fachkompetenzen
## Grundlagen: Spannung, Strom, ohmsches Gesetz, Leistung

---

### Aufgabe 1: Spannungseinheiten umwandeln
Wandeln Sie folgende Spannungsangaben um in die Grundeinheit Volt:
`2kV, 80mV, 0,23kV, 700µV, 380kV, 0,75MV`

- [[Stufe 1: Nur Ergebnis]]
  * $2\,\text{kV} = 2000\,\text{V}$
  * $80\,\text{mV} = 0{,}08\,\text{V}$
  * $0{,}23\,\text{kV} = 230\,\text{V}$
  * $700\,\mu\text{V} = 0{,}0007\,\text{V}$
  * $380\,\text{kV} = 380000\,\text{V}$
  * $0{,}75\,\text{MV} = 750000\,\text{V}$

- [[Stufe 2: Lösungshinweise]]
  * Nutzen Sie die Zehnerpotenzen der Einheitsvorsätze:
    * Mega ($\text{M}$) = $10^6$
    * Kilo ($\text{k}$) = $10^3$
    * Milli ($\text{m}$) = $10^{-3}$
    * Mikro ($\mu$) = $10^{-6}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  * $2\,\text{kV} = 2 \cdot 10^3\,\text{V} = 2000\,\text{V}$
  * $80\,\text{mV} = 80 \cdot 10^{-3}\,\text{V} = 0{,}08\,\text{V}$
  * $0{,}23\,\text{kV} = 0{,}23 \cdot 10^3\,\text{V} = 230\,\text{V}$
  * $700\,\mu\text{V} = 700 \cdot 10^{-6}\,\text{V} = 0{,}0007\,\text{V}$
  * $380\,\text{kV} = 380 \cdot 10^3\,\text{V} = 380000\,\text{V}$
  * $0{,}75\,\text{MV} = 0{,}75 \cdot 10^6\,\text{V} = 750000\,\text{V}$

---

### Aufgabe 2: Stromeinheiten umwandeln
Wandeln Sie folgende Stromangaben um in eine Angabe mit sinnvollem Maßeinheitsvorsatz:
`2500A, 0,003A, 80000µA, 1550mA, 0,000040A`

- [[Stufe 1: Nur Ergebnis]]
  * $2500\,\text{A} = 2{,}5\,\text{kA}$
  * $0{,}003\,\text{A} = 3\,\text{mA}$
  * $80000\,\mu\text{A} = 80\,\text{mA}$
  * $1550\,\text{mA} = 1{,}55\,\text{A}$
  * $0{,}000040\,\text{A} = 40\,\mu\text{A}$

- [[Stufe 2: Lösungshinweise]]
  * Wählen Sie den Präfix so, dass der Zahlenwert vorzugsweise zwischen $1$ und $1000$ liegt.
  * Verschieben Sie das Komma in Dreierschritten ($10^3, 10^{-3}, 10^{-6}$).

- [[Stufe 3: Vollständiger Lösungsweg]]
  * $2500\,\text{A} = \frac{2500}{1000}\,\text{kA} = 2{,}5\,\text{kA}$
  * $0{,}003\,\text{A} = 0{,}003 \cdot 1000\,\text{mA} = 3\,\text{mA}$
  * $80000\,\mu\text{A} = \frac{80000}{1000}\,\text{mA} = 80\,\text{mA}$
  * $1550\,\text{mA} = \frac{1550}{1000}\,\text{A} = 1{,}55\,\text{A}$
  * $0{,}000040\,\text{A} = 0{,}000040 \cdot 10^6\,\mu\text{A} = 40\,\mu\text{A}$

---

### Aufgabe 3: Erzeugte Spannung im Generator
Eine Ladungsmenge von $500\,\text{C}$ wird in einem Generator durch Zufuhr einer mechanischen Arbeit von $3000\,\text{Nm}$ getrennt. Wie hoch ist die erzeugte Spannung?

- [[Stufe 1: Nur Ergebnis]]
  $$U = 6\,\text{V}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $Q = 500\,\text{C}$, $W = 3000\,\text{Nm} = 3000\,\text{J}$
  * **Gesucht:** Spannung $U$
  * **Formel:** $U = \frac{W}{Q}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$U = \frac{W}{Q} = \frac{3000\,\text{J}}{500\,\text{C}} = 6\,\text{V}$$

---

### Aufgabe 4: Feldstärke einer Oszilloskopröhre
Die Beschleunigungsspannung einer Elektronenstrahlröhre eines Oszilloskops beträgt $2\,\text{kV}$. Der Abstand zwischen Katode und Anode beträgt $32\,\text{cm}$. Wie hoch ist die Feldstärke?

- [[Stufe 1: Nur Ergebnis]]
  $$E = 6250\,\frac{\text{V}}{\text{m}} = 6{,}25\,\frac{\text{kV}}{\text{m}}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $U = 2\,\text{kV} = 2000\,\text{V}$, $d = 32\,\text{cm} = 0{,}32\,\text{m}$
  * **Gesucht:** Feldstärke $E$
  * **Formel:** Homogenes Feld $E = \frac{U}{d}$ (Einheiten in Volt und Meter umrechnen).

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$E = \frac{U}{d} = \frac{2000\,\text{V}}{0{,}32\,\text{m}} = 6250\,\frac{\text{V}}{\text{m}} = 6{,}25\,\frac{\text{kV}}{\text{m}}$$

---

### Aufgabe 5: Maximale Spannung am Folienkondensator
Bei einem Kunststoff-Folienkondensator mit einer Folienstärke von $0{,}3\,\mu\text{m}$ beträgt die zulässige Feldstärke $E_d = 80\,\text{kV/mm}$. Bis zu wie viel Volt Gleichspannung kann der Kondensator verwendet werden?

- [[Stufe 1: Nur Ergebnis]]
  $$U_{\max} = 24\,\text{V}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $d = 0{,}3\,\mu\text{m} = 0{,}0003\,\text{mm}$, $E_d = 80\,\text{kV/mm} = 80000\,\text{V/mm}$
  * **Formel:** $U = E_d \cdot d$
  * **Tipp:** Wandeln Sie die Dicke $d$ in Millimeter um, damit die Einheiten zu $E_d$ passen.

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$d = 0{,}3 \cdot 10^{-3}\,\text{mm} = 0{,}0003\,\text{mm}$$
  $$U_{\max} = E_d \cdot d = 80000\,\frac{\text{V}}{\text{mm}} \cdot 0{,}0003\,\text{mm} = 24\,\text{V}$$

---

### Aufgabe 6: Ladung & Elektronenzahl beim Akku-Laden
Ein Bleiakkumulator wird $10\,\text{Minuten}$ lang mit $3{,}2\,\text{A}$ geladen. Berechnen Sie
a) die Ladung,
b) die Elektronenzahl der Ladung.

- [[Stufe 1: Nur Ergebnis]]
  a) $Q = 1920\,\text{C} = 1920\,\text{As} = 0{,}533\,\text{Ah}$
  b) $N \approx 1{,}20 \cdot 10^{22} \text{ Elektronen}$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $t = 10\,\text{min} = 600\,\text{s}$, $I = 3{,}2\,\text{A}$
  * **Elementarladung:** $e \approx 1{,}602 \cdot 10^{-19}\,\text{C}$
  * **Formeln:**
    * a) $Q = I \cdot t$
    * b) $N = \frac{Q}{e}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  **a) Ladung $Q$:**
  $$t = 10 \cdot 60\,\text{s} = 600\,\text{s}$$
  $$Q = I \cdot t = 3{,}2\,\text{A} \cdot 600\,\text{s} = 1920\,\text{C} \quad (1920\,\text{As} = 0{,}533\,\text{Ah})$$

  **b) Elektronenzahl $N$:**
  $$N = \frac{Q}{e} = \frac{1920\,\text{C}}{1{,}602 \cdot 10^{-19}\,\text{C}} \approx 1{,}1985 \cdot 10^{22} \approx 1{,}20 \cdot 10^{22}$$

---

### Aufgabe 7: Mittlerer Entladestrom des Blitzgeräts
Der Kondensator eines Elektronenblitzgeräts hat eine Ladung von $450\,\text{mAs}$. Er wird durch eine Blitzlampe in einer tausendstel Sekunde entladen. Berechnen Sie den mittleren Entladestrom.

- [[Stufe 1: Nur Ergebnis]]
  $$I = 450\,\text{A}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $Q = 450\,\text{mAs} = 0{,}45\,\text{As}$, $t = \frac{1}{1000}\,\text{s} = 0{,}001\,\text{s}$
  * **Formel:** $I = \frac{Q}{t}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$I = \frac{Q}{t} = \frac{0{,}45\,\text{As}}{0{,}001\,\text{s}} = 450\,\text{A}$$

---

### Aufgabe 8: Kfz-Akkumulator Lade- und Entladevorgang
Ein leerer Kfz-Akkumulator mit der Aufschrift $12\,\text{V} / 44\,\text{Ah}$ wird mit einer konstanten Stromstärke von $2\,\text{A}$ geladen.
a) Welche Ladezeit wird benötigt?
b) Welche Ladung hat er nach 8 Stunden?
c) In welcher Zeit ist der volle Akkumulator bei einer konstanten Belastung mit $0{,}5\,\text{A}$ entladen?

- [[Stufe 1: Nur Ergebnis]]
  a) $t = 22\,\text{h}$
  b) $Q = 16\,\text{Ah} = 57600\,\text{C}$
  c) $t = 88\,\text{h}$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $Q_{\text{nenn}} = 44\,\text{Ah}$, $I_{\text{lade}} = 2\,\text{A}$, $I_{\text{entlade}} = 0{,}5\,\text{A}$
  * **Formeln:**
    * Lade-/Entladezeit: $t = \frac{Q}{I}$
    * Geladene Menge: $Q = I \cdot t$

- [[Stufe 3: Vollständiger Lösungsweg]]
  **a) Ladezeit:**
  $$t = \frac{Q_{\text{nenn}}}{I_{\text{lade}}} = \frac{44\,\text{Ah}}{2\,\text{A}} = 22\,\text{h}$$

  **b) Ladung nach 8 Stunden:**
  $$Q = I \cdot t = 2\,\text{A} \cdot 8\,\text{h} = 16\,\text{Ah} = 16 \cdot 3600\,\text{As} = 57600\,\text{C}$$

  **c) Entladezeit:**
  $$t = \frac{Q_{\text{nenn}}}{I_{\text{entlade}}} = \frac{44\,\text{Ah}}{0{,}5\,\text{A}} = 88\,\text{h}$$

---

### Aufgabe 9: Erforderliche Querschnitte am Transformator
Ein Steuertransformator $230\,\text{V} / 24\,\text{V}$ nimmt $0{,}77\,\text{A}$ auf und gibt $6{,}2\,\text{A}$ ab. Die Stromdichte in der Eingangswicklung soll $2{,}3\,\text{A/mm}^2$, in der Ausgangswicklung $2{,}7\,\text{A/mm}^2$ nicht überschreiten. Berechnen Sie die erforderlichen Querschnitte.

- [[Stufe 1: Nur Ergebnis]]
  * Eingangswicklung: $A_1 \approx 0{,}335\,\text{mm}^2$
  * Ausgangswicklung: $A_2 \approx 2{,}30\,\text{mm}^2$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $I_1 = 0{,}77\,\text{A}$, $J_1 = 2{,}3\,\text{A/mm}^2$, $I_2 = 6{,}2\,\text{A}$, $J_2 = 2{,}7\,\text{A/mm}^2$
  * **Formel:** Stromdichte $J = \frac{I}{A} \quad \Rightarrow \quad A = \frac{I}{J}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  **Eingangswicklung ($A_1$):**
  $$A_1 = \frac{I_1}{J_1} = \frac{0{,}77\,\text{A}}{2{,}3\,\text{A/mm}^2} \approx 0{,}3348\,\text{mm}^2 \approx 0{,}335\,\text{mm}^2$$

  **Ausgangswicklung ($A_2$):**
  $$A_2 = \frac{I_2}{J_2} = \frac{6{,}2\,\text{A}}{2{,}7\,\text{A/mm}^2} \approx 2{,}296\,\text{mm}^2 \approx 2{,}30\,\text{mm}^2$$

---

### Aufgabe 10: Stromdichte einer Unterputzleitung
Eine PVC-isolierte Kupferleitung vom Querschnitt $2{,}5\,\text{mm}^2$ darf bei Verlegung im Putz mit $24\,\text{A}$ belastet werden. Wie hoch ist die zulässige Stromdichte?

- [[Stufe 1: Nur Ergebnis]]
  $$J = 9{,}6\,\frac{\text{A}}{\text{mm}^2}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $A = 2{,}5\,\text{mm}^2$, $I = 24\,\text{A}$
  * **Formel:** $J = \frac{I}{A}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$J = \frac{I}{A} = \frac{24\,\text{A}}{2{,}5\,\text{mm}^2} = 9{,}6\,\frac{\text{A}}{\text{mm}^2}$$

---

### Aufgabe 11: Kennwerte einer Glühlampe
An einer Glühlampe wurde eine Spannung von $12\,\text{V}$ und eine Stromstärke von $417\,\text{mA}$ gemessen. Wie groß ist der Widerstand und der Leitwert? Welche Leistung besitzt die Glühlampe?

- [[Stufe 1: Nur Ergebnis]]
  * Widerstand: $R \approx 28{,}78\,\Omega$
  * Leitwert: $G \approx 0{,}0348\,\text{S} = 34{,}8\,\text{mS}$
  * Leistung: $P \approx 5{,}00\,\text{W}$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $U = 12\,\text{V}$, $I = 417\,\text{mA} = 0{,}417\,\text{A}$
  * **Formeln:**
    * Widerstand: $R = \frac{U}{I}$
    * Leitwert: $G = \frac{1}{R} = \frac{I}{U}$
    * Leistung: $P = U \cdot I$

- [[Stufe 3: Vollständiger Lösungsweg]]
  **Widerstand $R$:**
  $$R = \frac{U}{I} = \frac{12\,\text{V}}{0{,}417\,\text{A}} \approx 28{,}777\,\Omega \approx 28{,}78\,\Omega$$

  **Leitwert $G$:**
  $$G = \frac{1}{R} = \frac{0{,}417\,\text{A}}{12\,\text{V}} \approx 0{,}03475\,\text{S} \approx 34{,}8\,\text{mS}$$

  **Leistung $P$:**
  $$P = U \cdot I = 12\,\text{V} \cdot 0{,}417\,\text{A} = 5{,}004\,\text{W} \approx 5{,}00\,\text{W}$$

---

### Aufgabe 12: Stromaufnahme von Glühlampen ($230\,\text{V}$)
Handelsübliche Glühlampen für die Nennspannung $230\,\text{V}$ haben folgende Leistungen:
Berechnen Sie jeweils die Stromaufnahme für:
a) $25\,\text{W}$, b) $40\,\text{W}$, c) $60\,\text{W}$, d) $75\,\text{W}$, e) $100\,\text{W}$, f) $150\,\text{W}$

- [[Stufe 1: Nur Ergebnis]]
  | Aufgabe | Leistung $P$ | Stromaufnahme $I$ |
  | :--- | :--- | :--- |
  | **a** | $25\,\text{W}$ | $0{,}109\,\text{A} \quad (108{,}7\,\text{mA})$ |
  | **b** | $40\,\text{W}$ | $0{,}174\,\text{A} \quad (173{,}9\,\text{mA})$ |
  | **c** | $60\,\text{W}$ | $0{,}261\,\text{A} \quad (260{,}9\,\text{mA})$ |
  | **d** | $75\,\text{W}$ | $0{,}326\,\text{A} \quad (326{,}1\,\text{mA})$ |
  | **e** | $100\,\text{W}$ | $0{,}435\,\text{A} \quad (434{,}8\,\text{mA})$ |
  | **f** | $150\,\text{W}$ | $0{,}652\,\text{A} \quad (652{,}2\,\text{mA})$ |

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $U = 230\,\text{V}$ (konstant)
  * **Formel:** $I = \frac{P}{U}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  * **a)** $I = \frac{25\,\text{W}}{230\,\text{V}} \approx 0{,}1087\,\text{A} \approx 108{,}7\,\text{mA}$
  * **b)** $I = \frac{40\,\text{W}}{230\,\text{V}} \approx 0{,}1739\,\text{A} \approx 173{,}9\,\text{mA}$
  * **c)** $I = \frac{60\,\text{W}}{230\,\text{V}} \approx 0{,}2609\,\text{A} \approx 260{,}9\,\text{mA}$
  * **d)** $I = \frac{75\,\text{W}}{230\,\text{V}} \approx 0{,}3261\,\text{A} \approx 326{,}1\,\text{mA}$
  * **e)** $I = \frac{100\,\text{W}}{230\,\text{V}} \approx 0{,}4348\,\text{A} \approx 434{,}8\,\text{mA}$
  * **f)** $I = \frac{150\,\text{W}}{230\,\text{V}} \approx 0{,}6522\,\text{A} \approx 652{,}2\,\text{mA}$

---

### Aufgabe 13: Schnellkochplatte des Elektroherdes
Bestimmen Sie für die Schnellkochplatte eines Elektroherdes $230\,\text{V} / 2\,\text{kW}$ die Stromaufnahme und den Widerstand.

- [[Stufe 1: Nur Ergebnis]]
  * Stromaufnahme: $I \approx 8{,}70\,\text{A}$
  * Widerstand: $R = 26{,}45\,\Omega$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $U = 230\,\text{V}$, $P = 2\,\text{kW} = 2000\,\text{W}$
  * **Formeln:**
    * $I = \frac{P}{U}$
    * $R = \frac{U}{I}$ oder $R = \frac{U^2}{P}$

- [[Stufe 3: Vollständiger Lösungsweg]]
  **Stromaufnahme $I$:**
  $$I = \frac{P}{U} = \frac{2000\,\text{W}}{230\,\text{V}} \approx 8{,}6957\,\text{A} \approx 8{,}70\,\text{A}$$

  **Widerstand $R$:**
  $$R = \frac{U^2}{P} = \frac{(230\,\text{V})^2}{2000\,\text{W}} = \frac{52900\,\text{V}^2}{2000\,\text{W}} = 26{,}45\,\Omega$$

---

### Aufgabe 14: Widerstand Belastung & Spannung
Ein Widerstand trägt die Aufschrift $3{,}3\,\text{k}\Omega / 5\,\text{W}$. In der Zuleitung wird ein Strom von $30{,}2\,\text{mA}$ gemessen. Berechnen Sie die Spannung am Widerstand.

- [[Stufe 1: Nur Ergebnis]]
  $$U = 99{,}66\,\text{V}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $R = 3{,}3\,\text{k}\Omega = 3300\,\Omega$, $I = 30{,}2\,\text{mA} = 0{,}0302\,\text{A}$
  * **Formel:** Ohmsches Gesetz $U = R \cdot I$
  * *(Kontrolle: $P_{\text{ist}} = U \cdot I \approx 3{,}01\,\text{W} \le 5\,\text{W}$ max. Belastbarkeit)*

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$U = R \cdot I = 3300\,\Omega \cdot 0{,}0302\,\text{A} = 99{,}66\,\text{V}$$

---

### Aufgabe 15: Anschlussleistung Schutzkontaktsteckdose
Eine Schutzkontaktsteckdose $230\,\text{V}$ wird mit einem Leitungsschutzschalter von $16\,\text{A}$ vor Überlastung geschützt. Wie groß ist die maximale Anschlussleistung?

- [[Stufe 1: Nur Ergebnis]]
  $$P_{\max} = 3680\,\text{W} = 3{,}68\,\text{kW}$$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $U = 230\,\text{V}$, $I = 16\,\text{A}$
  * **Formel:** Elektrische Leistung $P = U \cdot I$

- [[Stufe 3: Vollständiger Lösungsweg]]
  $$P = U \cdot I = 230\,\text{V} \cdot 16\,\text{A} = 3680\,\text{W} = 3{,}68\,\text{kW}$$

---

### Aufgabe 16: Verlust an mangelhafter Kontaktstelle
In einem Stockwerk-Abzweigkasten tritt an einer Kontaktstelle wegen mangelhafter Verschraubung ein Übergangswiderstand von $0{,}15\,\Omega$ auf. In der Abzweigleitung fließen $30\,\text{A}$. Berechnen Sie den Leistungs- und Spannungsverlust an der Kontaktstelle.

- [[Stufe 1: Nur Ergebnis]]
  * Spannungsverlust: $U_{\text{verlust}} = 4{,}5\,\text{V}$
  * Leistungsverlust: $P_{\text{verlust}} = 135\,\text{W}$

- [[Stufe 2: Lösungshinweise]]
  * **Gegeben:** $R_{\text{ü}} = 0{,}15\,\Omega$, $I = 30\,\text{A}$
  * **Formeln:**
    * Spannungsverlust: $U_{\text{verlust}} = I \cdot R_{\text{ü}}$
    * Leistungsverlust: $P_{\text{verlust}} = I^2 \cdot R_{\text{ü}} = U_{\text{verlust}} \cdot I$

- [[Stufe 3: Vollständiger Lösungsweg]]
  **Spannungsverlust ($U_{\text{verlust}}$):**
  $$U_{\text{verlust}} = I \cdot R_{\text{ü}} = 30\,\text{A} \cdot 0{,}15\,\Omega = 4{,}5\,\text{V}$$

  **Leistungsverlust ($P_{\text{verlust}}$):**
  $$P_{\text{verlust}} = I^2 \cdot R_{\text{ü}} = (30\,\text{A})^2 \cdot 0{,}15\,\Omega = 900\,\text{A}^2 \cdot 0{,}15\,\Omega = 135\,\text{W}$$