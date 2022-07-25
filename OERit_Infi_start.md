<!--

author:   Rico Meiner, ...
email:    rico.meiner@jade-hs.de

repository: ...

comment:  Lerneinheit Investition und Finanzierung. Diese Seite ist lizenziert unter der [Lizenz CC-BY (4.0)](https://creativecommons.org/licenses/by/4.0/legalcode).
(ggf.  CC0 am Start)

language: de

mode:     Textbook

version:  0.0.1

date:     26/05/2022

icon:     // Icon svg einfügen

logo:     // Logo png einfügen

link:     https://cdn.jsdelivr.net/gh/twillo-lehre-teilen/BestPractice_Sortieralgorithmen/custom.css

import:   https://github.com/LiaTemplates/Pyodide/blob/0.1.4/README.md
          https://github.com/LiaScript/CodeRunner/blob/master/README.md
-->

# Investitionsrechnung und Finanzierung

###### tags: `InFi`

Einstieg Infi als OER

## Investitionsrechnung

### Grundlagen Investition

* Begriffsdefinition
* Vorteilhaftigkeit
    * absolut
    * relativ
* Investitionsziele
    * Minimalprinzip
    * Maximalprinzip
* Investitionsarten
    * Neuinvestition
    * Ersatzinvestition
    * ...
* Sicherheit
* Unsicherheit
* Endwert
* Barwert
* Entscheidungen
    * Auswahlentscheidung
    * Ersatzentscheidung
* eine Zielgröße -> statische/dynamische Verfahren
* mehrere Zielgrößen -> Entscheidungsverfahren

### Statische Investitionsverfahren

* Kostenvergleichsrechnung
* Gewinnvergleichsrechnung
* Rentabilitätsvergleichsrechnung
* Statische Amortisationsrechnung

### Dynamische Verfahren

* Kapitalwertmethode
* Annuitätenmethode
* Methode des Internen Zinssatzes
* Dynamische Amortistationsrechnung
* Vermögensendwertmethode
* Vollständiger Finanzplan (VoFi)

### Entscheidungsverfahren

Unter Sicherheit
* Nutzwertanalyse
* Analytischer Hierarchie Prozess

Unter Unsicherheit
* Sensitivitätsanalyse
* Risikoanalyse
* Entscheidungsbaumverfahren

## Nutzungsdauer und Ersatzzeitpunkt bestimmen

* Kapitalwertmodell als Grundlage
* optimale Nutzungsdauer
* optimale Nutzungsdauer mit einem Nachfolgeobjekt
* optimale Nutzungsdauer mit vielen Nachfolgeobjekt

# Finanzierung
* Begriffsdefinition
* Liquidität
* Maßnahmen der Finanzierung
    * Kapitalbeschaffung
    * Kapitalumschichtung
    * Kapitalsicherung
    * Kapitalreduzierung
* Finanzmärkte
* Leverage-Effekt 
*  Finanzierungsarten
    *  Innenfinanzierung
    *  Außenfinanzierung
    *  Selbstfinanzierung
    *  Fremdfinanzierung
![](https://i.imgur.com/5NEw3Oh.png)
vlt. so wie im Bild differenzieren (Becker, Peppmeier: Investition und Finanzierung S. 153)
## Modelle Investition und Finanzierung

* Modell von Dean

### Programmentscheidungen bei Sicherheit

* Optimales Investitionsprogramm
* Simultane Investitions- und Finanzierungsplanung
* Simultane Investitions- und Produktionsplanung

### Programmentscheidungen bei Unsicherheit

* Portfolio-Selection
* Flexible Planung

---

# Formeln

einfache Formel auf dem Weg zum Kapitalwert:
> $$ 
> \sum _{ t=0 } ^{ T } { 
>   \left( 
>     e_{ t } - a_{ t } 
>   \right) 
>   \cdot q^{ t } 
> } 
> $$
>
> Parameter
> - $t$ >Zeitindex
> - $T$ >letzter Zeitpunkt
> - $e_{> t }$ Einzahlung für Zeitpunkt $t$
> - $a_{> t }$ Auszahlung für Zeitpunkt $t$
> - $q^{> t }$ Abzinsungsfaktor für Zeitpunkt $t$
 

Quelle:[^1] 
[^1]: Götze, U.: Investitionsrechnung, S. 79  Auflage 7


# Regeln
## OER mit Markdown - Empfehlungen

- Überschriften h1 bis h4 

  - '#' bis '####' 

- Listen

  - 1 Stern \* (danach Leerzeichen!)

- Formatierung nur **fett**

  - 2 Sterne \*\*

- Trennlinie

  - 3 Sterne \*\*\* (allein in Zeile)

- Links mit [Text] und (Link)
- Bilder mit ![Text] und (Link)
- Videos, H5P, ... nur mit [iframe einbinden](https://hackmd.io/s/features?both=1#Embed-a-Note)

**Formeln**

* Formeln nur mit Latex einfügen
  * $ für Formeln im Text 
  * $$ für größere Formeln (Beispiel siehe [a Kapitalwert](## Kapitalwert))
  * [Formeleditor](https://www.zahlen-kern.de/editor/) - ggf. Anpassungen notwendig 
  * HackMd nutzt die JS-Bibliothek [MathJax](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)
  * Liascript nutzt die JS-Bibliothek [KaTex](https://katex.org/docs/supported.html)

**Tabellen**

* Tabellen möglichst nicht mit Markdown erstellen
* ggf. [CSV-Formatierung ](https://hackmd.io/s/features#Render-CSV-as-table) nutzen

**Kompatibilität zu LiaScript**

* Elemente von HackMd/Hedgedoc nicht nutzen
* Besser HTML pur nutzen und Inhalte eher einbinden

# Links zu Projektressourcen
## Github
Für die allgemeine Projektdokumentation und Projektarchivierung wird Github benutzt.
Repository: https://github.com/OERit/InFi

Projektplan: https://github.com/orgs/OERit/projects/1

## Hackmd
In Hackmd werden die schriftlichen Inhalte für das Projekt erstellt.
https://hackmd.io/team/JadeOER-IT?nav=overview

## Nextcloud
Alle Einzelelemente (Bilder, Excel, H5P, ...)
https://ccs.jade-hs.de/f/235373619


