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


# Übung 2 – Leistung, Arbeit, Reihen- und Parallelschaltung
Lösungsblatt zum Arbeitspaket MECH LF3 02

---

# Allgemeine Fachkompetenz

## Aufgabe 1: Zusammenhang zwischen Arbeit und Leistung
Welcher Zusammenhang besteht zwischen Arbeit und Leistung?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

Betrachten Sie die Grunddefinitionen der physikalischen Größen:
* Leistung $P$ ist die pro Zeiteinheit umgewandelte Arbeit $W$.
* Formelzusammenhang: $P = \frac{W}{t}$ bzw. $W = P \cdot t$.

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

Die elektrische Leistung $P$ ist der Quotient aus der verrichteten Arbeit $W$ und der dafür benötigten Zeit $t$ ($P = \frac{W}{t}$). Umgekehrt ist die Arbeit $W$ das Produkt aus Leistung $P$ und Zeit $t$ ($W = P \cdot t$).

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

Die elektrische Leistung $P$ gibt an, wie schnell oder wie effizient elektrische Energie (Arbeit) in eine andere Energieform (z. B. Wärme, Licht, mechanische Arbeit) umgewandelt wird:

$$P = \frac{W}{t}$$

Stellt man die Formel nach der elektrischen Arbeit (oder Energie) $W$ um, erhält man:

$$W = P \cdot t$$

* **Einheiten:** 
  * Leistung $P$ in Watt ($\text{W}$) bzw. Kilowatt ($\text{kW}$)
  * Arbeit $W$ in Wattsekunden ($\text{Ws} = \text{J}$) oder Kilowattstunden ($\text{kWh}$)
  * Zeit $t$ in Sekunden ($\text{s}$) oder Stunden ($\text{h}$)

</details>

---

## Aufgabe 2: Gesetzmäßigkeiten der Reihenschaltung
Welche Gesetzmäßigkeiten gelten in der Reihenschaltung von Widerständen?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

Betrachten Sie die Eigenschaften für:
1. Stromstärke $I$
2. Gesamtspannung $U$ und Teilspannungen $U_n$
3. Gesamtwiderstand $R_{\text{ges}}$
4. Spannungsteilerverhältnis

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

* **Strom:** $I = I_1 = I_2 = \dots = I_n$ (überall gleich)
* **Spannung:** $U_{\text{ges}} = U_1 + U_2 + \dots + U_n$ (Summe der Teilspannungen)
* **Widerstand:** $R_{\text{ges}} = R_1 + R_2 + \dots + R_n$ (Summe der Einzelwiderstände)
* **Verhältnis:** Die Teilspannungen verhalten sich wie die zugehörigen Widerstände ($\frac{U_1}{U_2} = \frac{R_1}{R_2}$).

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

In einer Reihenschaltung (Unverzweigter Stromkreis) gelten folgende vier Grundgesetze:

1. **Stromstärke:** Der Strom hat nur einen Pfad, ist also in jedem Bauteil gleich groß:
   $$I = I_1 = I_2 = \dots = I_n$$

2. **Gesamtspannung:** Die anliegende Quellspannung teilt sich auf die einzelnen Bauteile auf:
   $$U_{\text{ges}} = U_1 + U_2 + \dots + U_n$$

3. **Gesamtwiderstand:** Der Gesamtwiderstand ist stets größer als jeder Einzelwiderstand und entspricht der Summe aller Einzelwiderstände:
   $$R_{\text{ges}} = \sum_{i=1}^{n} R_i = R_1 + R_2 + \dots + R_n$$

4. **Spannungsteilung:** An größeren Widerständen fällt mehr Spannung ab als an kleineren:
   $$\frac{U_1}{U_2} = \frac{R_1}{R_2}$$

</details>

---

## Aufgabe 3: Ersatzlampen für eine Lichterkette
Was ist bei der Auswahl von Ersatzlampen für eine Lichterkette zu beachten?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* Bedenken Sie, dass Lichterketten meist eine **Reihenschaltung** bilden.
* Was passiert mit der Spannungsverteilung, wenn der Widerstand (bzw. die Nennleistung) einer Ersatzlampe von den übrigen Lampen abweicht?

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

Eine Ersatzlampe muss exakt dieselbe **Nennspannung** und dieselbe **Nennleistung** (bzw. denselben **Nennstrom**) wie die ursprünglichen Lampen besitzen.

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

Da in einer Lichterkette alle Lampen in Reihe geschaltet sind, fließt durch jede Lampe derselbe Strom.

* Wählt man eine Ersatzlampe mit **kleinerer Nennleistung** (höherer Widerstand), fällt an ihr eine zu hohe Teilspannung ab. Die Ersatzlampe überhitzt und brennt schnell durch.
* Wählt man eine Ersatzlampe mit **größerer Nennleistung** (kleinerer Widerstand), fällt an ihr nur eine sehr geringe Spannung ab. Sie leuchtet kaum, dafür wird an den restlichen Lampen der Lichterkette eine höhere Spannung abgefangen, was deren Lebensdauer verkürzt.
* **Fazit:** Nennspannung ($U_{\text{N}}$) und Nennstrom ($I_{\text{N}}$) bzw. Nennleistung ($P_{\text{N}}$) müssen exakt mit dem Original übereinstimmen.

</details>

---

## Aufgabe 4: Gesetzmäßigkeiten der Parallelschaltung
Welche Gesetzmäßigkeiten gelten in der Parallelschaltung von Widerständen?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

Betrachten Sie die Eigenschaften für:
1. Spannung $U$
2. Gesamtstrom $I$ und Teilströme $I_n$
3. Gesamtwiderstand $R_{\text{ges}}$ bzw. Gesamtleitwert $G_{\text{ges}}$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

* **Spannung:** $U = U_1 = U_2 = \dots = U_n$ (überall gleich)
* **Strom:** $I_{\text{ges}} = I_1 + I_2 + \dots + I_n$ (Summe der Teilströme)
* **Leitwert / Widerstand:** $G_{\text{ges}} = G_1 + G_2 + \dots + G_n$ bzw. $\frac{1}{R_{\text{ges}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n}$
* Der Gesamtwiderstand $R_{\text{ges}}$ ist immer kleiner als der kleinste Einzelwiderstand.

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

In einer Parallelschaltung (Verzweigter Stromkreis) gelten folgende Gesetzmäßigkeiten:

1. **Spannung:** An allen parallelen Zweigen liegt exakt dieselbe Spannung an:
   $$U = U_1 = U_2 = \dots = U_n$$

2. **Gesamtstrom:** Der von der Quelle gelieferte Gesamtstrom teilt sich an den Knotenkunkten auf die einzelnen Zweige auf:
   $$I_{\text{ges}} = I_1 + I_2 + \dots + I_n$$

3. **Gesamtwiderstand / Gesamtleitwert:** Die Leitwerte addieren sich. Für den Gesamtwiderstand gilt:
   $$\frac{1}{R_{\text{ges}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n}$$
   Für genau zwei parallele Widerstände vereinfacht sich die Formel zu:
   $$R_{\text{ges}} = \frac{R_1 \cdot R_2}{R_1 + R_2}$$

4. **Stromteiler:** Die Teilströme verhalten sich umgekehrt proportional zu den Widerständen ($\frac{I_1}{I_2} = \frac{R_2}{R_1}$).

</details>

---

## Aufgabe 5: Parallelschaltung in Installationsschaltungen
Warum werden in Installationsschaltungen Lampen und Geräte an Steckdosenstromkreisen parallel angeschlossen?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

Überlegen Sie:
* Welche Spannung benötigen Haushaltsgeräte zum Betrieb?
* Was würde passieren, wenn Sie ein Gerät ausschalten oder es defekt ist, wenn alle Geräte in Reihe geschaltet wären?

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

1. Damit an jedem Verbraucher unabhängig von den anderen Geräten stets die volle Netzspannung ($230\,\text{V}$) anliegt.
2. Damit Geräte unabhängig voneinander ein- und ausgeschaltet werden können (beim Ausschalten eines Geräts bleiben alle anderen in Funktion).

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

* **Unabhängiger Betrieb:** Bei der Parallelschaltung bilden die einzelnen Verbraucher eigene Stromkreise. Wird ein Verbraucher ausgeschaltet oder fällt durch einen Defekt aus, bleiben die anderen Strompfade geschlossen und die übrigen Geräte funktionieren ungestört weiter.
* **Konstante Nennspannung:** Elektrische Geräte sind für eine Bemessungsspannung von $230\,\text{V}$ konstruiert. Nur bei der Parallelschaltung erhalten alle Steckdosen und Leuchten diese konstante Spannung. Bei einer Reihenschaltung würde sich die Spannung aufteilen und Geräte würden nicht richtig oder gar nicht funktionieren.

</details>

---

# Mathematische Fachkompetenz

## Aufgabe 1: Unbeabsichtigte Flurbeleuchtung
Eine Flurbeleuchtung nimmt bei $230\,\text{V}$ einen Strom von $174\,\text{mA}$ auf. Sie ist versehentlich während der Nacht $7\,\text{Stunden}$ lang eingeschaltet. Wie groß ist die elektrische Leistung und der Verbrauch an elektrischer Energie? Welche Kosten entstehen bei einem Preis von $0{,}25\,\text{€/kWh}$?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $U = 230\,\text{V}$, $I = 174\,\text{mA} = 0{,}174\,\text{A}$, $t = 7\,\text{h}$, $\text{Preis} = 0{,}25\,\text{€/kWh}$
* **Gesucht:** Leistung $P$, Energie $W$, Kosten
* **Formeln:**
  * $P = U \cdot I$
  * $W = P \cdot t$
  * $\text{Kosten} = W \cdot \text{Preis}$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

* Elektrische Leistung: $P \approx 40{,}02\,\text{W} \approx 0{,}040\,\text{kW}$
* Elektrische Energie: $W \approx 0{,}280\,\text{kWh}$
* Entstehende Kosten: $\approx 0{,}07\,\text{€}$ ($7\,\text{Cent}$)

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**1. Elektrische Leistung $P$:**
$$P = U \cdot I = 230\,\text{V} \cdot 0{,}174\,\text{A} = 40{,}02\,\text{W} = 0{,}04002\,\text{kW}$$

**2. Verbrauchte elektrische Energie $W$:**
$$W = P \cdot t = 0{,}04002\,\text{kW} \cdot 7\,\text{h} = 0{,}28014\,\text{kWh} \approx 0{,}280\,\text{kWh}$$

**3. Kosten:**
$$\text{Kosten} = W \cdot \text{Preis} = 0{,}28014\,\text{kWh} \cdot 0{,}25\,\frac{\text{€}}{\text{kWh}} \approx 0{,}070035\,\text{€} \approx 0{,}07\,\text{€}$$

</details>

---

## Aufgabe 2: Eingeschaltete Autobeleuchtung
Durch Unachtsamkeit wurde ein Personenauto $70\,\text{Minuten}$ mit eingeschalteter Beleuchtung geparkt. Folgende Lampen waren eingeschaltet:
* Abblendlicht: 2 Halogenlampen H4 ($12\,\text{V} / 55\,\text{W}$)
* Standlicht: 2 Lampen ($12\,\text{V} / 5\,\text{W}$)
* Schlussleuchte: 2 Lampen ($12\,\text{V} / 5\,\text{W}$)
* Kennzeichenbeleuchtung: 2 Lampen ($12\,\text{V} / 5\,\text{W}$)
* Instrumentenbeleuchtung: 5 Lampen ($12\,\text{V} / 5\,\text{W}$)

Berechnen Sie:
a) die Leistungsaufnahme der eingeschalteten Beleuchtung,
b) die aus der Batterie während des Parkens entnommene elektrische Energie,
c) die Stromaufnahme der Beleuchtung,
d) die Entladedauer des vollen Akkumulators mit einer Kapazität von $44\,\text{Ah}$.

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $U = 12\,\text{V}$, $t = 70\,\text{min} = \frac{70}{60}\,\text{h}$, $Q_{\text{nenn}} = 44\,\text{Ah}$
* Summen der einzelnen Lampenleistungen bilden.
* Formeln: $W = P_{\text{ges}} \cdot t$, $I = \frac{P_{\text{ges}}}{U}$, $t_{\text{entlade}} = \frac{Q_{\text{nenn}}}{I}$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

a) $P_{\text{ges}} = 165\,\text{W}$  
b) $W = 192{,}5\,\text{Wh} = 0{,}1925\,\text{kWh}$  
c) $I = 13{,}75\,\text{A}$  
d) $t_{\text{entlade}} = 3{,}2\,\text{h} = 3\,\text{Std. } 12\,\text{Min.}$

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**a) Gesamtleistungsaufnahme $P_{\text{ges}}$:**
$$P_{\text{Abblend}} = 2 \cdot 55\,\text{W} = 110\,\text{W}$$
$$P_{\text{Stand}} = 2 \cdot 5\,\text{W} = 10\,\text{W}$$
$$P_{\text{Schluss}} = 2 \cdot 5\,\text{W} = 10\,\text{W}$$
$$P_{\text{Kennzeichen}} = 2 \cdot 5\,\text{W} = 10\,\text{W}$$
$$P_{\text{Instrumente}} = 5 \cdot 5\,\text{W} = 25\,\text{W}$$
$$P_{\text{ges}} = 110\,\text{W} + 10\,\text{W} + 10\,\text{W} + 10\,\text{W} + 25\,\text{W} = 165\,\text{W}$$

**b) Entnommene elektrische Energie $W$:**
$$t = 70\,\text{min} = \frac{70}{60}\,\text{h} \approx 1{,}1667\,\text{h}$$
$$W = P_{\text{ges}} \cdot t = 165\,\text{W} \cdot \frac{70}{60}\,\text{h} = 192{,}5\,\text{Wh} = 0{,}1925\,\text{kWh}$$

**c) Stromaufnahme $I$:**
$$I = \frac{P_{\text{ges}}}{U} = \frac{165\,\text{W}}{12\,\text{V}} = 13{,}75\,\text{A}$$

**d) Entladedauer des vollen Akkumulators ($44\,\text{Ah}$):**
$$t_{\text{entlade}} = \frac{Q_{\text{nenn}}}{I} = \frac{44\,\text{Ah}}{13{,}75\,\text{A}} = 3{,}2\,\text{h} = 3\,\text{Std. } 12\,\text{Min.}$$

</details>

---

## Aufgabe 3: Höchstzulässige Kennwerte von Widerständen
Berechnen Sie die höchstzulässige Spannung und Stromstärke für die Widerstände $330\,\Omega$, $680\,\Omega$ und $1{,}5\,\text{k}\Omega$ bei einer Nennbelastbarkeit von jeweils $2\,\text{W}$.

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $P_{\max} = 2\,\text{W}$
* **Formeln:**
  * Spannung: $P = \frac{U^2}{R} \quad \Rightarrow \quad U_{\max} = \sqrt{P \cdot R}$
  * Stromstärke: $P = I^2 \cdot R \quad \Rightarrow \quad I_{\max} = \sqrt{\frac{P}{R}}$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

* **Für $330\,\Omega$:** $U_{\max} \approx 25{,}69\,\text{V}$, $I_{\max} \approx 77{,}85\,\text{mA}$
* **Für $680\,\Omega$:** $U_{\max} \approx 36{,}88\,\text{V}$, $I_{\max} \approx 54{,}23\,\text{mA}$
* **Für $1{,}5\,\text{k}\Omega$:** $U_{\max} \approx 54{,}77\,\text{V}$, $I_{\max} \approx 36{,}51\,\text{mA}$

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**1. Widerstand $R_1 = 330\,\Omega$:**
$$U_{\max} = \sqrt{P \cdot R_1} = \sqrt{2\,\text{W} \cdot 330\,\Omega} = \sqrt{660}\,\text{V} \approx 25{,}69\,\text{V}$$
$$I_{\max} = \sqrt{\frac{P}{R_1}} = \sqrt{\frac{2\,\text{W}}{330\,\Omega}} \approx 0{,}07785\,\text{A} \approx 77{,}85\,\text{mA}$$

**2. Widerstand $R_2 = 680\,\Omega$:**
$$U_{\max} = \sqrt{P \cdot R_2} = \sqrt{2\,\text{W} \cdot 680\,\Omega} = \sqrt{1360}\,\text{V} \approx 36{,}88\,\text{V}$$
$$I_{\max} = \sqrt{\frac{P}{R_2}} = \sqrt{\frac{2\,\text{W}}{680\,\Omega}} \approx 0{,}05423\,\text{A} \approx 54{,}23\,\text{mA}$$

**3. Widerstand $R_3 = 1{,}5\,\text{k}\Omega = 1500\,\Omega$:**
$$U_{\max} = \sqrt{P \cdot R_3} = \sqrt{2\,\text{W} \cdot 1500\,\Omega} = \sqrt{3000}\,\text{V} \approx 54{,}77\,\text{V}$$
$$I_{\max} = \sqrt{\frac{P}{R_3}} = \sqrt{\frac{2\,\text{W}}{1500\,\Omega}} \approx 0{,}03651\,\text{A} \approx 36{,}51\,\text{mA}$$

</details>

---

## Aufgabe 4: Reihenschaltung von zwei Widerständen
Die Widerstände $R_1 = 250\,\Omega$ und $R_2 = 500\,\Omega$ liegen in Reihe an $230\,\text{V}$. Berechnen Sie:
a) den Gesamtwiderstand,
b) den Strom,
c) die Teilspannungen.

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $R_1 = 250\,\Omega$, $R_2 = 500\,\Omega$, $U = 230\,\text{V}$
* **Formeln:**
  * $R_{\text{ges}} = R_1 + R_2$
  * $I = \frac{U}{R_{\text{ges}}}$
  * $U_1 = I \cdot R_1$, $U_2 = I \cdot R_2$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

a) $R_{\text{ges}} = 750\,\Omega$  
b) $I \approx 0{,}3067\,\text{A} = 306{,}7\,\text{mA}$  
c) $U_1 \approx 76{,}67\,\text{V}$, $U_2 \approx 153{,}33\,\text{V}$

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**a) Gesamtwiderstand $R_{\text{ges}}$:**
$$R_{\text{ges}} = R_1 + R_2 = 250\,\Omega + 500\,\Omega = 750\,\Omega$$

**b) Gesamtstrom $I$:**
$$I = \frac{U}{R_{\text{ges}}} = \frac{230\,\text{V}}{750\,\Omega} \approx 0{,}30667\,\text{A} \approx 306{,}7\,\text{mA}$$

**c) Teilspannungen $U_1$ und $U_2$:**
$$U_1 = I \cdot R_1 = 0{,}30667\,\text{A} \cdot 250\,\Omega = 76{,}67\,\text{V}$$
$$U_2 = I \cdot R_2 = 0{,}30667\,\text{A} \cdot 500\,\Omega = 153{,}33\,\text{V}$$
*(Kontrolle: $U_1 + U_2 = 76{,}67\,\text{V} + 153{,}33\,\text{V} = 230\,\text{V}$)*

</details>

---

## Aufgabe 5: Falscher Ersatz einer Glühlampe in Reihenschaltung
Zwei Glühlampen $6\,\text{V} / 15\,\text{W}$ sind in Reihe an $12\,\text{V}$ angeschlossen. Eine der beiden Lampen ist durchgebrannt und wird durch eine Glühlampe $6\,\text{V} / 25\,\text{W}$ ersetzt.
a) Welche Folge hat diese Maßnahme?
b) Begründen Sie Ihre Meinung durch Rechnung.
c) Durch welche Maßnahmen können die Glühlampen auf ihre Nennleistungen gebracht werden?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* Berechnen Sie die Warmwiderstände beider Glühlampen mit $R = \frac{U^2}{P}$.
* Berechnen Sie den Gesamtwiderstand, den Strom und die sich neu einstellenden Teilspannungen an beiden Lampen.

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

* **a) Folge:** Die verbleibende $15\,\text{W}$-Lampe brennt übermäßig hell (Gefahr des Durchbrennens), während die neu eingesetzte $25\,\text{W}$-Lampe nur schwach glimmt.
* **b) Rechnerisch:** $U_{15\text{W}} = 7{,}5\,\text{V}$ (überlastet), $U_{25\text{W}} = 4{,}5\,\text{V}$ (unterversorgt).
* **c) Maßnahmen:** Wieder eine passende $6\,\text{V}/15\,\text{W}$-Lampe einbauen ODER beide Lampen parallel an einer $6\,\text{V}$-Spannungsquelle betreiben.

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**a) Folge:**
Die verbleibende $15\,\text{W}$-Lampe wird durch überschüssige Spannung überlastet und wird sehr hell leuchten bzw. schnell durchbrennen. Die $25\,\text{W}$-Lampe erhält zu wenig Spannung und glimmt nur schwach.

**b) Rechnerischer Nachweis:**
* Widerstand der $15\,\text{W}$-Lampe ($R_1$):
  $$R_1 = \frac{U_{\text{N}}^2}{P_1} = \frac{(6\,\text{V})^2}{15\,\text{W}} = \frac{36}{15}\,\Omega = 2{,}4\,\Omega$$

* Widerstand der $25\,\text{W}$-Lampe ($R_2$):
  $$R_2 = \frac{U_{\text{N}}^2}{P_2} = \frac{(6\,\text{V})^2}{25\,\text{W}} = \frac{36}{25}\,\Omega = 1{,}44\,\Omega$$

* Gesamtwiderstand in Reihe:
  $$R_{\text{ges}} = R_1 + R_2 = 2{,}4\,\Omega + 1{,}44\,\Omega = 3{,}84\,\Omega$$

* Reihenstrom $I$:
  $$I = \frac{U_{\text{ges}}}{R_{\text{ges}}} = \frac{12\,\text{V}}{3{,}84\,\Omega} = 3{,}125\,\text{A}$$

* Teilspannung an der $15\,\text{W}$-Lampe ($U_1$):
  $$U_1 = I \cdot R_1 = 3{,}125\,\text{A} \cdot 2{,}4\,\Omega = 7{,}5\,\text{V} \quad (> 6\,\text{V} \rightarrow \text{Überlastung!})$$

* Teilspannung an der $25\,\text{W}$-Lampe ($U_2$):
  $$U_2 = I \cdot R_2 = 3{,}125\,\text{A} \cdot 1{,}44\,\Omega = 4{,}5\,\text{V} \quad (< 6\,\text{V} \rightarrow \text{Unterversorgung!})$$

**c) Abhilfemaßnahmen:**
1. Die defekte Lampe wieder durch eine identische $6\,\text{V} / 15\,\text{W}$-Lampe ersetzen (dann fallen an beiden genau $6\,\text{V}$ ab).
2. Die Schaltung von Reihenschaltung auf Parallelschaltung an einer $6\,\text{V}$-Spannungsquelle umstellen.

</details>

---

## Aufgabe 6: Bestimmung eines unbekannten Parallelwiderstandes
Die Parallelschaltung von zwei Widerständen hat einen Ersatzwiderstand von $40\,\Omega$. Einer der Widerstände hat $60\,\Omega$. Wie groß ist der andere Widerstand?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $R_{\text{ges}} = 40\,\Omega$, $R_1 = 60\,\Omega$
* **Formel umstellen:**
  $$\frac{1}{R_{\text{ges}}} = \frac{1}{R_1} + \frac{1}{R_2} \quad \Rightarrow \quad R_2 = \frac{R_{\text{ges}} \cdot R_1}{R_1 - R_{\text{ges}}}$$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

$$R_2 = 120\,\Omega$$

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

$$\frac{1}{R_{\text{ges}}} = \frac{1}{R_1} + \frac{1}{R_2}$$

$$\frac{1}{R_2} = \frac{1}{R_{\text{ges}}} - \frac{1}{R_1} = \frac{1}{40\,\Omega} - \frac{1}{60\,\Omega} = \frac{3 - 2}{120\,\Omega} = \frac{1}{120\,\Omega}$$

$$R_2 = 120\,\Omega$$

Alternative Formel:
$$R_2 = \frac{R_{\text{ges}} \cdot R_1}{R_1 - R_{\text{ges}}} = \frac{40\,\Omega \cdot 60\,\Omega}{60\,\Omega - 40\,\Omega} = \frac{2400\,\Omega^2}{20\,\Omega} = 120\,\Omega$$

</details>

---

## Aufgabe 7: Kochplatte mit 4-Takt-Schalter
In einer Kochplatte ($230\,\text{V} / 2\,\text{kW}$) sind zwei Heizspiralen mit je $52{,}9\,\Omega$ eingebaut. Durch einen 4-Takt-Schalter werden folgende Schaltzustände erreicht:
* **Stellung 1:** beide Spiralen in Reihe.
* **Stellung 2:** eine Spirale allein.
* **Stellung 3:** beide Spiralen parallel.

Wie groß sind Widerstand, Stromaufnahme und Leistung in jeder Stufe?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $U = 230\,\text{V}$, $R_1 = R_2 = 52{,}9\,\Omega$
* **Stellung 1:** $R_{\text{St1}} = R_1 + R_2$
* **Stellung 2:** $R_{\text{St2}} = R_1$
* **Stellung 3:** $R_{\text{St3}} = \frac{R_1}{2}$
* Formeln für jede Stufe: $I = \frac{U}{R}$, $P = U \cdot I$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

| Stufe | Schaltung | Widerstand $R$ | Strom $I$ | Leistung $P$ |
| :--- | :--- | :--- | :--- | :--- |
| **Stellung 1** | Reihe | $105{,}8\,\Omega$ | $2{,}174\,\text{A}$ | $500\,\text{W} \quad (0{,}5\,\text{kW})$ |
| **Stellung 2** | Einzeln | $52{,}9\,\Omega$ | $4{,}348\,\text{A}$ | $1000\,\text{W} \quad (1{,}0\,\text{kW})$ |
| **Stellung 3** | Parallel | $26{,}45\,\Omega$ | $8{,}696\,\text{A}$ | $2000\,\text{W} \quad (2{,}0\,\text{kW})$ |

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**Stellung 1 (Reihenschaltung - "Stufe 1 / Leise"):**
* $R_{\text{St1}} = 52{,}9\,\Omega + 52{,}9\,\Omega = 105{,}8\,\Omega$
* $I_{\text{St1}} = \frac{230\,\text{V}}{105{,}8\,\Omega} \approx 2{,}1739\,\text{A} \approx 2{,}174\,\text{A}$
* $P_{\text{St1}} = 230\,\text{V} \cdot 2{,}1739\,\text{A} \approx 500\,\text{W} = 0{,}5\,\text{kW}$

**Stellung 2 (Einzeleinbau - "Stufe 2 / Mittel"):**
* $R_{\text{St2}} = 52{,}9\,\Omega$
* $I_{\text{St2}} = \frac{230\,\text{V}}{52{,}9\,\Omega} \approx 4{,}3478\,\text{A} \approx 4{,}348\,\text{A}$
* $P_{\text{St2}} = 230\,\text{V} \cdot 4{,}3478\,\text{A} \approx 1000\,\text{W} = 1{,}0\,\text{kW}$

**Stellung 3 (Parallelschaltung - "Stufe 3 / Stark"):**
* $R_{\text{St3}} = \frac{52{,}9\,\Omega}{2} = 26{,}45\,\Omega$
* $I_{\text{St3}} = \frac{230\,\text{V}}{26{,}45\,\Omega} \approx 8{,}6957\,\text{A} \approx 8{,}696\,\text{A}$
* $P_{\text{St3}} = 230\,\text{V} \cdot 8{,}6957\,\text{A} \approx 2000\,\text{W} = 2{,}0\,\text{kW}$

</details>

---

## Aufgabe 8: Stand-by-Verbrauch im Haushalt
In einer Wohnung dreht sich infolge des Stand-by-Betriebes einiger Geräte die Zählerscheibe in $10\,\text{min}$ um eine Umdrehung. Die Zählerkonstante beträgt $300\,\text{U/kWh}$. Wie groß ist die Anschlussleistung? Welche Energie wird über ein Jahr verbraucht? Welche Kosten entstehen über ein Jahr bei einem Preis von $0{,}25\,\text{€/kWh}$?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $n = 1\,\text{Umdrehung}$, $t = 10\,\text{min} = \frac{1}{6}\,\text{h}$, $C = 300\,\text{U/kWh}$, $\text{Preis} = 0{,}25\,\text{€/kWh}$
* **Formeln:**
  * Energie pro Umdrehung: $W_1 = \frac{n}{C}$
  * Leistung: $P = \frac{W_1}{t}$
  * Jahresenergie: $W_{\text{Jahr}} = P \cdot 8760\,\text{h}$ ($1\,\text{Jahr} = 365 \cdot 24\,\text{h} = 8760\,\text{h}$)
  * Jahreskosten: $\text{Kosten} = W_{\text{Jahr}} \cdot \text{Preis}$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

* Anschlussleistung: $P = 20\,\text{W} = 0{,}02\,\text{kW}$
* Jahresenergieverbrauch: $W_{\text{Jahr}} = 175{,}2\,\text{kWh}$
* Entstehende Jahreshosten: $43{,}80\,\text{€}$

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**1. Anschlussleistung $P$:**
$$W_1 = \frac{1\,\text{U}}{300\,\text{U/kWh}} = \frac{1}{300}\,\text{kWh}$$
$$t = 10\,\text{min} = \frac{10}{60}\,\text{h} = \frac{1}{6}\,\text{h}$$
$$P = \frac{W_1}{t} = \frac{\frac{1}{300}\,\text{kWh}}{\frac{1}{6}\,\text{h}} = \frac{6}{300}\,\text{kW} = 0{,}02\,\text{kW} = 20\,\text{W}$$

**2. Verbrauchte Energie im Jahr $W_{\text{Jahr}}$:**
$$t_{\text{Jahr}} = 365 \cdot 24\,\text{h} = 8760\,\text{h}$$
$$W_{\text{Jahr}} = P \cdot t_{\text{Jahr}} = 0{,}02\,\text{kW} \cdot 8760\,\text{h} = 175{,}2\,\text{kWh}$$

**3. Kosten pro Jahr:**
$$\text{Kosten} = 175{,}2\,\text{kWh} \cdot 0{,}25\,\frac{\text{€}}{\text{kWh}} = 43{,}80\,\text{€}$$

</details>

---

## Aufgabe 9: Leistungsmessung eines Heizlüfters
Zur Bestimmung der Leistung eines Heizlüfters wird dieser als einziger Verbraucher an einen Zähler mit der Zählerkonstanten $1200\,\text{U/kWh}$ angeschlossen. In einer halben Minute werden $20\,\text{Umdrehungen}$ der Scheibe gezählt. Wie groß ist die Leistungsaufnahme des Lüfters?

<details>
<summary><b>Stufe 1: Lösungshinweise</b></summary>

* **Gegeben:** $C = 1200\,\text{U/kWh}$, $n = 20\,\text{Umdrehungen}$, $t = 0{,}5\,\text{min} = 30\,\text{s} = \frac{1}{120}\,\text{h}$
* **Formel:**
  * Umgewandelte Arbeit: $W = \frac{n}{C}$
  * Leistung: $P = \frac{W}{t}$

</details>

<details>
<summary><b>Stufe 2: Nur Ergebnis</b></summary>

$$P = 2000\,\text{W} = 2\,\text{kW}$$

</details>

<details>
<summary><b>Stufe 3: Vollständiger Lösungsweg</b></summary>

**1. Verbrauchte Arbeit $W$ in $30\,\text{Sekunden}$:**
$$W = \frac{n}{C} = \frac{20\,\text{U}}{1200\,\text{U/kWh}} = \frac{1}{60}\,\text{kWh}$$

**2. Messzeit $t$ in Stunden:**
$$t = 0{,}5\,\text{min} = \frac{0{,}5}{60}\,\text{h} = \frac{1}{120}\,\text{h}$$

**3. Leistungsaufnahme $P$:**
$$P = \frac{W}{t} = \frac{\frac{1}{60}\,\text{kWh}}{\frac{1}{120}\,\text{h}} = \frac{120}{60}\,\text{kW} = 2\,\text{kW} = 2000\,\text{W}$$

</details>