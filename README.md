# LF-ZQ8a-Projekt
Verwendete Technologien:

```javascript
const Projects = {
  	code: ["HTML", "CSS", "Javascript"],
	technologies: {
	devTool: ["VS-Code"]
	}
}
```


## Quellen für dieses Projekt
<ul>
    <li><a href="https://www.w3.org/">W3C</a></li>
	<li><a href="https://fontawesome.com/">Font Awesome</a></li>
	<li><a href="https://cssloaders.github.io/">Loaders</a></li>
	<li><a href="https://www.impressum-generator.de/">Impressum-generator</a></li>
	<li><a href="https://www.mein-datenschutzbeauftragterdedatenschutzerklaerung-konfigurator">Datenschutzerklärung Muster</a></li>
</ul>

## Projektbeschreibung


## HTML:
Webseite für eine Pizzeria namens Muster Pizza.

Der Code enthält verschiedene Abschnitte, die den Inhalt der Webseite strukturieren. 
- Hier ist eine Zusammenfassung der Abschnitte:

- `head:` Dieser Abschnitt enthält Metadaten über die Webseite, die nicht direkt auf der Webseite angezeigt werden.
- `header:` Enthält den Kopfbereich der Webseite, einschließlich des Logos, der Navigation und der Social-Media-Links.
- `section:` Die Webseite enthält mehrere Abschnitte, z. B. für die Startseite (home), die Speisekarte (menü), Informationen über das Unternehmen (about) und Kontaktinformationen (contact).
- `footer:` Den Fußbereich der Webseite, einschließlich Copyright-Informationen und Links zu rechtlichen Dokumenten.

## JavaScript Funktionen:

## Navigationsmenü:

- Ein Element mit der ID "menu-toggler" steuert die Sichtbarkeit von Links.
- Beim Klicken auf dieses Element werden Event-Listener hinzugefügt oder entfernt, um die Links beim Klicken auszublenden.

## Karte:

- Nach dem Laden des DOMs (Document Object Model) wird eine Google Maps-Karte mit einer Verzögerung von 3 Sekunden in ein Element mit der ID "load-iframe-map" eingefügt.

## Kontaktformular:

- Die Funktion "validar" wird vermutlich beim Absenden des Formulars aufgerufen.
- Sie gibt eine Meldung in der Konsole aus und verhindert das Standardverhalten des Formulars (wahrscheinlich um eine eigene Verarbeitung durchzuführen).

## Wichtige Punkte:

- Der Code verwendet JavaScript, um dynamische Funktionen auf einer Webseite zu implementieren.
- Die Navigationsmenü-Funktionalität steuert die Sichtbarkeit von Links, um eine benutzerfreundlichere Navigation zu ermöglichen.
- Die Kartenfunktion lädt eine Google Maps-Karte, um den Nutzern standortbezogene Informationen bereitzustellen.
- Die Kontaktformularfunktion verarbeitet Formulardaten und verhindert wahrscheinlich das Standardverhalten des Formulars, um eine benutzerdefinierte Verarbeitung zu ermöglichen.

## CSS
Dieser Code definiert einen `CSS-Stil namens ".neon-Text"`, der verwendet wird, um Text mit einem neonartigen Effekt zu erstellen.

## Eigenschaften des Styles:

- `Positionierung:` Der Text wird absolut positioniert und mithilfe von `transform: translate(-50%, -50%)` in der Mitte des Bildschirms zentriert.
- `Textausrichtung:` Der Text wird durch `text-align: center` horizontal zentriert.
- `Textgröße und Umwandlung:` Die Textgröße wird auf 5rem festgelegt und mit `text-transform: uppercase` in Großbuchstaben umgewandelt.
- `Zeiger und Übergang:` Der Cursor wird beim Hovern über den Text zum Zeiger und es wird ein linearer Übergang mit einer Dauer von 0,3 Sekunden definiert.
- `Neon-Effekt:`
   -- Die Farbe des Textes ist transparent.
   -- Der Text verwendet einen Strich mit einer Stärke von 1,5 Pixeln in der Farbe `var(--color-green)`.
   -- Ein Hintergrundbild mit einem linearen Farbverlauf von Schwarz über Grün zu Schwarz und Dunkelgrau wird erstellt.
   -- Die Größe des Hintergrundbildes ist 200% (wodurch der Farbverlauf animiert wird).
- `-webkit-text-stroke` und `-webkit-background-clip: text` (vendorexifizierte Eigenschaften) wenden den Strich und den Farbverlauf nur auf den Text an.
- Die Keyframe-Animation `"move"` animiert die Bewegung des Farbverlaufs.

## Animation "move":

Die Animation "move" verschiebt die Position des Hintergrundbildes über 7 Sekunden linear von 0% auf 2000% der Textbreite. Dadurch entsteht die Illusion eines sich bewegenden Neonlichts.

## Hover-Effekt:

Beim Hovern über den Text ändert sich die Farbe zu var(--color-green) und ein grüner Schlagschatten mit zunehmender Unschärfe wird hinzugefügt.

## Gesamteffekt:

Dieser Code erzeugt einen Text mit einem neonartigen Leuchteffekt und Farbverlauf, der sich beim Hovern über den Text grün färbt.
