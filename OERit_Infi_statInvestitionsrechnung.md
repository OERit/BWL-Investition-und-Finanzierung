# Statische Investitionsrechnung
###### tags: `InFi`

[toc]

## Grundlagen

In der statischen Investitionsrechnung wird immer nur **ein Zeitabschnitt** berücksichtigt. Dazu wird entweder eine besonders **repräsentative Periode** oder eine **hypothetische Durchschnittsperiode** ausgewählt.

Innerhalb der statischen Investitionsrechnung erfolgt eine Differenzierung von Verfahren hinsichtlich unterschiedlicher Zielgrößen.


**DIESE TABELLE BASIERT AUF PAPE 2018; S.332. SIE KANN SO VERMUTLICH NICHT IN DER FINALEN OER-VERSION EINGESETZT WERDEN!**


| Verfahren | Vorgehensweise | Zielsetzung |
| -------- | -------- | -------- |
| Kostenvergleichsrechnung | Ermittlung der durchschnittlichen Kosten pro Jahr | Minimierung der Kosten |
| Gewinnvergleichsrechnung | Ermittlung des durchschnittlichen Gewinns pro Jahr | Maximierung des Gewinns |
| Rentabilitätsrechnung | Ermittlung der durchschnittlichen Rentabilität pro Jahr | Maximierung der Rentabilität|
| Amortisationsrechnung | Ermittlung der durchschnittlichen Amortisationszeit | Minimierung der Amortisationszeit |


## Kostenvergleichsrechnung

### Grundlagen

In der Kostenvergleichsrechnung werden die durchschnittlichen **Kosten jeder Investitonsalternative ermittelt**. Dabei wird angenommen, dass die **Erlöse** der Investitionsalternativen **identisch** sind und der **Gesamtgewinn maximiert** werden soll.

Typischerweise werden dabei folgende Kostenarten untersucht:
- Personalkosten (Löhne, Gehälter, Sozialkosten, etc.)
- Materialkosten
- Abschreibungen
- Zinsen
- Steuern, Gebühren, Beiträge
- Kosten für Fremdleistungen

Die Kostenvergleichsrechnung basiert auf zwei Vorteilhaftigkeitsregeln:
- Ein Investitionsobjekt ist **absolut** vorteilhaft, falls seine Kosten geringer sind als die Kosten der Unterlassungsalternative.
- Ein Investitionsobjekt ist **relativ** vorteilhaft, falls seine Kosten geringer sind als die jedes anderen zur Wahl stehenden Objekts.

Es wird zwischen **variablen** und **fixen Kosten** unterschieden:
- Variable Kosten sind abhängig von der Produktionsmenge. Sie entstehen nur, wenn auch produziert wird.
- Fixe Kosten sind unabhängig von der Proudktionsmenge. Sie fallen immer in gleicher Höhe an, selbst wenn nichts produziert wird.

### Übung: Variable Kosten und fixe Kosten
<iframe src="https://h5p.org/h5p/embed/1280883" width="630" height="600" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Variable und fixe Kosten"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

### Vorgehen in der Kostenvergleichsrechnung

1. Ermittlung der Fixkosten
2. Ermittlung der variablen Kosten
3. Aufstellen der Kostenfunktion und Berechnung der Kosten für verschiedene Mengen



### Einfache Übung: Konstenfunktion aufstellen
<iframe src="https://h5p.org/h5p/embed/1286988" width="800" height="1740" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Kostenvergleichsrechnung (komplettes einfaches Beispiel)"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

### Komplexe Übung: Kostenfunktion aufstellen
<iframe src="https://h5p.org/h5p/embed/1286991" width="800" height="1480" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Kostenvergleichsrechung (komplexes Beispiel V1)"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

### Ermittlung der kritischen Menge
Als kritische Menge bezeichnet man den Punkt, an dem die Kosten zweier Alternativen gleich hoch sind. Zur Berechnung der kritischen Menge werden die Kostenfunktionen beider Alternativen gleichgesetzt.

Beispiel mit den Kostenfunktionen aus den vorherigen Abschnitten:

$$ \begin{array}{lllll}
& K(A) &= K(B) \\
\iff & 113.000 + 11,5 * x &= 78.000 + 15 * x  &|-78.000 \\
\iff & 35.000 + 11,5 * x &= 15 * x &|-11,5 \\
\iff & 35.000 &= 3,5 * x &|:3,5 \\
\iff & 10.000 &= x \\
\end{array} $$

Das bedeutet, dass bei einer Produktionsmenge von 10.000 Einheiten pro Jahr beide Maschinen die gleichen Kosten verursachen.

### Kostenvergleich
Mit Hilfe von Kostenfunktionen können verschiedene Alternativen miteinander verglichen werden. Die kritische Menge ist hier der Schnittpunkt der beiden Geraden.

Eine graphische Umsetzung des Kostenvergleichs mit Hilfe der in den vorherigen Abschnitten aufgestellten Kostenfunktionen findet sich im unten stehenden Diagramm.

Es zeigt sich, dass Maschine B im Bereich bis 10.000 Einheiten pro Jahr weniger Kosten verursacht als Maschine A, sodass der Kauf und Einsatz von Maschine B hier zu bevorzugen wäre. Maschine B ist also realtiv vorteilhaft.

Die kritische Menge ist in diesem Beispiel bei 10.000 Einheiten erreicht, beide Maschinen verursachen hier Kosten in gleicher Höhe.

Ab einer Produktionsmenge von mehr als 10.000 Einheiten ist der Kauf und Einsatz von Maschine A zu bevorzugen. Maschine A ist also relativ vorteilhaft.

![](https://i.imgur.com/mzcNl4h.png)

## Gewinnvergleichsrechnung

### Grundlagen
In der Gewinnvergleichsrechnung wird der durchschnittliche Gewinn pro Jahr errechnet. Ziel ist dabei die Maximierung des Gewinns. Der Gewinn ist definiert als $$ Gewinn = Erlös - Kosten. $$

Die Gewinnvergleichsrechnung basiert auf zwei Vorteilhaftigkeitsregeln:
- Ein Investitionsobjekt ist **absolut** vorteilhaft, falls sein Gewinn größer als Null ist.
- Ein Investitionsobjekt ist **relativ** vorteilhaft, falls sein Gewinn größer ist als der Gewinn jedes anderen zur Wahl stehenden Objektes.

### Übungen

## Rentabilitätsvergleichsrechnung
### Grundlagen
In der Rentabilitätsvergleichsrechnung wird die durchschnittliche Rentabilität pro Jahr errechnet. Ziel ist dabei die Maximierung der Rentabilität. Die Rentabilität ist definiert als 

$$ Rentabilität = \frac{ durchschnittlicher \ Gewinn }{ durchschnittliche \ Kapitalbindung. } $$

\

Weiterhin wird zwischen **Bruttorentabilität** und **Nettorentabilität** unterschieden.

$$Bruttorentabilität = \frac{ Gewinn \ vor \ Abzug \ von \ kalk. \ Zinsen}{ durchschnittliche \ Kapitalbindung }$$

$$Nettorentabilität = \frac{ Gewinn \ nach \ Abzug \ von \ kalk. \ Zinsen}{ durchschnittliche \ Kapitalbindung }$$

\

Die Rentabilitätsvergleichsrechnung basiert auf zwei Vorteilhaftigkeitsregeln:
- Ein Investitionsobjekt ist **absolut** vorteilhaft, falls seine Rentabilität höher ist als ein vorzugebender Grenzwert.
- Ein Investitionsobjekt ist **relativ** vorteilhaft, falls seine Rentabilität höher ist als die Rentabilität jedes anderen zur Wahl stehenden Objektes.

### Übungen

## Statische Amortisationsrechnung

### Grundlagen
Der **Zeitraum**, in dem das **eingesetzte Kapital** aus den Rückflüssen oder Einzahlungsüberschüssen des Objekts **wiedergewonnen** wird, wird als Armortisationszeit bezeichnet.
In der statischen Amortisationsrechnung wird dabei mit **Durchschnittswerten** gerechnet.
Man betrachtet dabei die durchschnittlichen Rückflüsse:

$$ Durchschnittliche \ Rückflüsse = durchschnittlicher \ Gewinn + Abschreibungen $$

Mit Hilfe der durchschnittlichen Rückflüsse lässt sich dann die Armortisationszeit berechnen.

$$ Amortisationszeit = \frac {eingesetztes \ Kapital }{durchschnittliche \ Rückflüsse} $$

Die statische Armortisationsrechnung basiert auf zwei Vorteilhaftigkeitsregeln:
- Ein Investitionsobjekt ist **absolut vorteilhaft**, falls seine Amortisationszeit geringer ist als ein vorzugebender Grenzwert
- Ein Investitionsobjekt ist **relativ vorteilhaft**, falls seine Amortisationszeit geringer ist als die jedes anderen zur Wahl stehenden Objektes.

### Übung
<iframe src="https://h5p.org/h5p/embed/1285855" width="800" height="670" frameborder="0" allowfullscreen="allowfullscreen" allow="geolocation *; microphone *; camera *; midi *; encrypted-media *" title="Statische Amortisationsrechnung"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>