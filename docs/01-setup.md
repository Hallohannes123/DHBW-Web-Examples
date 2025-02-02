# Schnelles Projektsetup

_"Dann lass uns mal loslegen! Unsere Designer haben auf Figma ein paar Variablen definiert, die du 1:1 wiederverwenden solltest. Außerdem solltest du erstmal alles notwendige fürs Basic CSS bereitstellen."_

## Aufgabe 1 - CSS-Resets
Aus alten Zeiten bieten Web-Browser ein mindest-maß an Styles für verschiedene Elemente (z.B. Headlines 1-6, Paragraphs, etc). In modernen wollen wir alles so blank wie möglich halten. Hierfür gibt es sogenannte "CSS-Resets". Deine Erste Aufgabe ist einfach: Such dir im Internet ein existierendes CSS-Reset heraus und baue dieses in ein separates CSS-File mit dem Namen `reset.css` in einem css-ordner unter `assets` ein.

## Aufgabe 2 - CSS-Variablen vorbereiten
Wie bereits erwähnt, wurden im Figma File Variablen verwendet. Diese können wir direkt für uns in CSS-Variablen "gießen" und später bequem verwenden.  
Falls die Figma-Datei nicht mehr auffindbar ist, kommt nachfolgend eine Tabelle an verwendeten Farb-Werten:

|Name|Wert|
|----|----|
|bg| #14172F|
|fg| #F2F2f2|
|primary-100| #fff|
|primary-95| #effff2|
|primary-90| #deffe5|
|primary-80| #beffcb|
|primary-70| #9dffb0|
|primary-60| #7dff96|
|primary-50| #5cff7c|
|primary-40| #4acc64|
|primary-30| #37994a|
|primary-20| #256632|
|primary-10| #123319|
|primary-05| #09190c|
|primary-00| #000|
|mono-100| #fff|
|mono-95| #f2f2f2|
|mono-90| #e6e6e6|
|mono-80| #ccc|
|mono-60| #b3b3b3|
|mono-50| #808080|
|mono-40| #666|
|mono-30| #4d4d4d|
|mono-20| #333|
|mono-10| #1a1a1a|
|mono-05| #0d0d0d|
|mono-00| #000|

## Aufgabe 3: Fonts
Im `assets` Ordner wurden bereits die Font-Dateien bereit gestellt, die im Figma File auch verwendet wurden.
Beide Fonts sind "normal" gestyled (also keine Kursivschrift oder ähnliches) und haben eine Font-Weight von 400 (regular).  
Für unser Beispiel reicht es die normalen Unicode-Ranges einzubinden (`U+00-52F, U+1E00-1FFF, U+2200-22FF`).

Wenn du das geschafft hast, kannst du noch anhand der Figma Files auch ein paar "Font-Style-Klassen" definieren.
Diese sollten im gesamten Projekt wiederverwendet werden können. Falls auch hier die Figma-Datei nicht mehr erreichbar sein sollte, verwende folgende Werte:

|name  |family  |size (desktop)|size (mobile)|line-height|letter-spacing|
|------|--------|--------------|-------------|-----------|--------------|
|h1    |Orbitron|4rem          |2.5rem       |130%       |5%            |
|h2    |Orbitron|2.5rem        |2.5rem       |120%       |5%            |
|body-l|Oxanium |1.5rem        |1.5rem       |110%       |5%            |
|body-m|Oxanium |1rem          |1rem         |100%       |5%            |

Verwende als Mobiler <--> Desktop Breakpoint eine Mindestbreite von 712px!

## Setup geschafft!
Herzlichen Glückwunsch! Du hast nun ein Basis-Set von dem wir weiter machen können :)  
Falls du eine "Musterlösung" haben willst, von der du auch in den folgenden Aufgaben aufbauen willst, kannst du den Branch "junglesounds/css-setup" auschecken und von dort aus weiter machen!