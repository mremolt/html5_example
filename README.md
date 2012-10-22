# Vortrag über HTML5 ganz praktisch: Gliederung

## Allgemein

* http://html5boilerplate.com/ ist ein super Startpunkt!


## Grundlegende HTML5-Struktur

* Doctype
* IE-Klassen im html-Tag
* chromeframe/IE=edge
* meta-viewport


## Wichtige Bibliotheken

* modernizr: http://modernizr.com/
** HTML5-Tags für legacy Browser
** Feature-Detection
* normalize.css: http://necolas.github.com/normalize.css/


## Überblick über einige wichtige semantische HTML5-Tags 

* http://html5doctor.com/ als erste Anlaufstelle
* section
* header/footer
* aside
* nav
* article
* hgroup
* time


## Layout mit CSS3 

* wichtige Regel: w3c-Validator ignorieren!!!

* Es gibt viele gute Frameworks, die bei der Erstellung eines Layouts helfen
** Twitter Bootstrap
** Zurb Foundation
** framelessgrid.com
** viele weitere ...

* oder von Hand :)
** z.B. flexbox
** CSS3-Features wie border-radius oder gradient
** Alles ist gut ... wenn es nicht den IE/legacy Browser gäbe


## IE-Fallbacks 
* aktueller Status: ARGH!
* manchmal mit kleinen Tricks: dispay inline-block im IE7
* manchmal über alternative Layouts (flexbox -> float)
* manchmal über Polyfills: https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills
** z.B. CSS3 PIE: http://css3pie.com/


## Responsive Layouts 
* passen sich u.a. der Fenstergröße des Browsers an (oder portrait/landscape
  ...)
* funktioniert über sog. media queries:
** z.B. folgende Regeln gelten, falls die Fensterbreite maximal 800px beträgt
* für IE (falls man es braucht): https://github.com/scottjehl/Respond


