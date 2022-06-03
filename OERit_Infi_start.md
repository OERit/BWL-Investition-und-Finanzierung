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

## OER mit Markdown > Regeln

**Erlaubte Elemente im Dokument**
* Überschriften h1 bis h3 
    * '#' bis '####' 
* Listen 
    * 1 Stern * (danach Leerzeichen!)
* Formatierung nur **fett**
    * 2 Sterne **
* Trennlinie
    * 3 Sterne *** (allein in Zeile)
* Links mit [Text] und (Link)
* Bilder mit ![Text] und (Link)
* Videos, H5P, ... nur mit [iframe einbinden](https://hackmd.io/s/features?both=1#Embed-a-Note)

***

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

# Investitionsrechnung

## Grundlagen Investition

![test](https://de.wikipedia.org/wiki/Investitionsrechnung#/media/Datei:Abzinsung.svg)

## statische Investitionsverfahren

### Kostenvergleichsrechnung

### Gewinnvergleichsrechnung

### Amortisationsrechnung

## dynamische Verfahren

Es werden mehrere Perioden berücksichtigt

### Kapitalwertmethode

einfache Formel auf dem Weg zum Kapitalwert:
$$ 
\sum _{ t=0 } ^{ T } { 
    \left( 
        e_{ t } - a_{ t } 
    \right) 
    \cdot q^{ t } 
} 
$$

Parameter
* $t$ Zeitindex
* $T$ letzter Zeitpunkt
* $e_{ t }$ Einzahlung für Zeitpunkt $t$
* $a_{ t }$ Auszahlung für Zeitpunkt $t$
* $q^{ t }$ Abzinsungsfaktor für Zeitpunkt $t$


Quelle:[^1] 
[^1]: Götze, U.: Investitionsrechnung, S. 79  Auflage 7

### dynamische Amortistationsrechnung

### Vollständiger Finanzplan (VoFi)

# Nutzungsdauer- und Ersatzzeitpunktentscheidungen


# Entscheidungsverfahren

## Nutzwertanalyse

## Entscheidungsbaumverfahren

## Sensitivitätsanalyse


# Finanzierung

## Innenfinanzierung

## Außenfinanzierung

## Selbstfinanzierung

## Fremdfinanzierung
