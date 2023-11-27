# Übersicht HTML und CSS Befehle

Hier findet ihr eine fortlaufende Übersicht über unsere bislang kennengelernten Elemente in HTML und die CSS Eigenschaften. Die Übersicht wird in den nächsten Tagen immer um die neuen Werte ergänzt.
<br><br>

## Übersicht
1. [HTML-Elemente](#html-elemente)
   - [Block Elemente](#block-elemente)
   - [Inline Elemente](#inline-elemente)
2. [CSS-Eigenschaften](#css-eigenschaften)
   - [Textformatierung](#textformatierung)
   - [Größen](#größen)
   - [Abstände und Rahmen](#abstände-und-rahmen)
   - [Hintergrund](#hintergrund)


<br><br><br>

## HTML-Elemente

1. Block Elemente (nehmen gesamte Breite des Elternelements)

    | HTML-Element  | Beschreibung                               | Beispiel                             |
    |:-------------:|:------------------------------------------:|:------------------------------------:|
    | `<h1>`...`<h6>` | Überschriften                            | `<h1>Überschrift</h1>`               |
    | `<p>`          | Textabsatz                                | `<p>Textabsatz</p>`                  |
    | `<ul>`         | Ungeordnete Liste                         | `<ul><li>Element</li></ul>`          |
    | `<ol>`         | Geordnete Liste                           | `<ol><li>Erstes Element</li></ol>`   |
    | `<li>`         | Listenelement                             | `<li>Listeneintrag</li>`             |


   
2. Inline Elemente (nehmen nur die Breite ihres Inhalts)

    | HTML-Element | Beschreibung                    | Beispiel                              |
    |:------------:|:-------------------------------:|:-------------------------------------:|
    | `<a>`        | Hyperlink (intern, extern)      | `<a href="url">Linktext</a>`          |
    | `<br>`       | Spezielles leeres Element für Zeilenumbrüche  | `Dies ist ein Text<br>neue Zeile`         |
    | `<img>`      | Bild einfügen                                 | `<img src="url" alt="Bildbeschreibung">`  |

<br><br><br>
## CSS-Eigenschaften

### Textformatierung
| Eigenschaft       | Beschreibung                                   | Beispiel                        |
|-------------------|------------------------------------------------|---------------------------------|
| `color`           | Setzt die Textfarbe.                           | `color: blue;`                  |
| `font-size`       | Bestimmt die Schriftgröße.                     | `font-size: 16px;`              |
| `text-decoration` | Fügt Dekorationen wie Unterstreichungen hinzu. | `text-decoration: underline;`   |
| `font-weight`     | Definiert die Dicke der Schrift.               | `font-weight: bold;`            |
| `font-family`     | Bestimmt die Schriftart.                       | `font-family: Arial, sans-serif;`|
| `font-style`      | Legt den Stil der Schrift fest (z.B. kursiv).  | `font-style: italic;`           |



## Nützliche Tastenkombinationen (Windows)

Es ist hilfreich einige Tastenkombinationen für häufige Handlungen zu lernen. Mit der Tastatur könnt ihr schneller arbeiten und es entstehen weniger Fehler als bei der Benutzung mit der Maus (Touchpad). Vielleicht seit ihr am Anfang etwas langsamer, aber auf lange Sicht lohnt sich das Lernen.


### Allgemeine Tastenkombinationen

Tastenkombinationen, die in **VS Code** und anderen Programmen funktionieren:

- Fenster wechseln --> `Alt` + `Tab`
- Kopieren        --> `STRG` + `c`
- Ausschneiden    --> `STRG` + `x`
- Einfügen        --> `STRG` + `v`
- Suchen          --> `STRG` + `f`
- Speichern       --> `STRG` + `s`
- alles markieren --> `STRG` + `a`


### VS-Code

Diese praktischen Kombinationen funktionieren nur in VS Code:
- `Alt` + `Pfeiltaste`  --> Zeilen verschieben, hoch/runter
- `Alt` + `z`           --> Zeilenumbruch anschalten/ausschalten
- `STRG`+ `#`           --> erzeugt einen Kommentar 
- `STRG`+ `l`           --> Zeile markieren


#### Emmet Abkürzungen in VS Code

Emmet sind Kurzformen, die VS Code zu Code umschreibt, hier einige kurze Beispiele für ***HTML***:
- `!`               --> erzeugt in einen Boilerplate-Code (Grundstruktur)
- `lorem50`         --> erzeugt einen Lorem-Text mit 50 Worten
- `div.box`         --> erzeugt eine `<div class="box">`
- `ul>li*3`         --> erzeugt eine `<ul>` mit 3 `<li>`Elementen
- `a{weiterlesen}`  --> erzeugt ein `<a href="">weiterlesen</a>`
- `section>img+p+a` --> erzeugt eine Sektion und darin ein `<img>`, `<p>`und ein `<a>`

Ihr könnt diese Elemente miteinander kombinieren und damit sehr umfangreiche Codeblöcke bauen. Benutzt diese aber erst, wenn ihr euch mit eurem html sicher seid. Je länger eure Kombinationen sind, desto leichter könnt ihr Fehler produzieren und den Überblick verlieren. Es gibt diese Emmet Abkürzungen auch für CSS. Einen (sehr) umfangreichen Überblick über die verschiedenen Möglichkeiten findet ihr hier:
***[Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)***