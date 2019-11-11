# Phone company site
Projekt für Test im UI Modul

- Schreib das HTML und CSS für die abgebildete Seite
- Die Seite soll responsive sein und sich auf unterschiedlichen Bildschirmbreiten entsprechend der Abbildungen verhalten.

## Anforderungen HTML
- Die Seite soll auf dem Handy bzw. im DevTools-Simulator nicht kleiner skaliert/kleiner gezoomt werden.
- Einrückung der Kinder-Elemente im Code
- Korrekte Dateipfade
- Beschreibende Klassen- oder ID-Namen für Elemente vergeben
## Anforderungen CSS
- Selektoren so speizifisch schreiben, dass unabsichtliche Auswirkungen auf andere Teile der Seite vermieden werden.
- Kein float zum Anordnen von Block-Elementen
- Style-Werte, die sowieso standardmäßig vom Browser gesetzt werden, nicht im CSS deklarieren.

![](drafts/mobile.JPG)
![](drafts/tablet.JPG)
![](drafts/desktop.JPG)
![](drafts/desktop-button-hover.JPG)

###   25/60 Punkten
#### Punktabzüge für:
- [x] (10) Elemente passen sich nicht an Fensterbreite an
```diff
- Ab einer mittleren Fensterbreite verschwindet das Formular aus dem viewport
- Die Navigation springt bei viel zu großer Fensterbreite auf die mobile Version um
```
- [x] (10) Tags nicht geschlossen oder falsch verschachtelt
```diff
- h1 und h2 nicht in cols verschachtelt, so kann nicht kontrolliert werden, ob sie neben dem Formular stehen oder drunter
```
- [_] (5) Block-Tag in Inline-Tag
- [_] (5) Kinder-Tags im Code nicht eingerückt
- [_] (10) Zweckfremde Tags verwendet
- [_] (10) Fehlende essetielle Tags (z.B. Meta-Tags)
- [_] (5) Falsche Datei-Pfade
- [x] (10) CSS-Selektoren, die bei Änderungen im HTML sehr leicht fehlschlagen können
```diff
- Es wird unnötigerweise !important verwendet um Bootstrap anzupassen
- flexbox und grid verwendet, trotz Bootstrap
```
- [x] (5) Fehlende essentielle Tag-Attribute
```diff
- Im label für das email-Feld wird eine ID verwendet, die es beim Feld nicht gibt
```
