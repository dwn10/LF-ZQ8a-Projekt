# LF-ZQ8a-Projekt

Verwendete Technologien:

```javascript
const Projects = {
  code: ["HTML", "CSS", "Javascript"],
  technologies: {
    devTool: ["VS-Code"],
  },
};
```

## Quellen für dieses Projekt

<ul>
    <li><a href="https://www.w3.org/">W3C</a></li>
	<li><a href="https://fontawesome.com/">Font Awesome</a></li>
	<li><a href="https://cssloaders.github.io/">Loaders</a></li>
	<li><a href="https://www.impressum-generator.de/">Impressum-generator</a></li>
	<li><a href="https://www.mein-datenschutzbeauftragterdedatenschutzerklaerung-konfigurator">Datenschutzerklärung Muster</a></li>
</ul>

## Projektbeschreibung Thema : Pizzeria

Skizze: Navigation als Navigationsleist an der Seite oben mit folgenden Seiten:

- Frontpage
- Speisenkarte
- Über uns
- Impressum
- Anfahrt
- Responsiv, Hamburger Btn
- Optional: Gutscheine, Kochworkshop
- Veranstaltungen (Raum, Servic, Beamer, Flipchart)

Datenschutz (nicht in der Navigation, sondern auf jeder Seite rechts unten)

## HTML:

Webseite für eine Pizzeria namens Muster Pizza.

Der Code enthält verschiedene Abschnitte, die den Inhalt der Webseite strukturieren.

- Hier ist eine Zusammenfassung der Abschnitte:

- `head:` Dieser Abschnitt enthält Metadaten über die Webseite, die nicht direkt auf der Webseite angezeigt werden.
- `header:` Enthält den Kopfbereich der Webseite, einschließlich des Logos, der Navigation und der Social-Media-Links.
- `section:` Die Webseite enthält mehrere Abschnitte, z. B. für die Startseite (home), die Speisekarte (menü), Informationen über das Unternehmen (about) und Kontaktinformationen (contact).
- `footer:` Den Fußbereich der Webseite, einschließlich Copyright-Informationen und Links zu rechtlichen Dokumenten.

## JavaScript Funktionen

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

## CSS:

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

## Animation move:

Die Animation "move" verschiebt die Position des Hintergrundbildes über 7 Sekunden linear von 0% auf 2000% der Textbreite. Dadurch entsteht die Illusion eines sich bewegenden Neonlichts.

## Hover-Effekt:

Beim Hovern über den Text ändert sich die Farbe zu var(--color-green) und ein grüner Schlagschatten mit zunehmender Unschärfe wird hinzugefügt.

## Gesamteffekt:

Dieser Code erzeugt einen Text mit einem neonartigen Leuchteffekt und Farbverlauf, der sich beim Hovern über den Text grün färbt.

##
## Loader:

Definiert die Stile für eine Ladeanimation (.loader). Die Animation erzeugt einen rotierenden Kreis mit zwei farbigen Schatten.

##
## Projekt-Screenshots

<a href="https://media.discordapp.net/attachments/1214730549969813504/1220142619858829412/web-home.JPG?ex=660ddd5d&is=65fb685d&hm=d156c79fcfdcc2aeba6a7d94ccab6b333e0d9059f6aa88623d76aa301169d352&=&format=webp&width=904&height=579"><img src="https://media.discordapp.net/attachments/1214730549969813504/1220142619858829412/web-home.JPG?ex=660ddd5d&is=65fb685d&hm=d156c79fcfdcc2aeba6a7d94ccab6b333e0d9059f6aa88623d76aa301169d352&=&format=webp&width=904&height=579" style="height: 80%; width:80%;"/></a>
<a href="https://media.discordapp.net/attachments/1214730549969813504/1220142620228059216/web-menu.JPG?ex=660ddd5d&is=65fb685d&hm=a771200c1b18600239273e02119828318c797c3f080e9ef170bda6066cf1e9a9&=&format=webp&width=864&height=579"><img src="https://media.discordapp.net/attachments/1214730549969813504/1220142620228059216/web-menu.JPG?ex=660ddd5d&is=65fb685d&hm=a771200c1b18600239273e02119828318c797c3f080e9ef170bda6066cf1e9a9&=&format=webp&width=864&height=579" style="height: 80%; width:80%;"/></a>
<a href="https://media.discordapp.net/attachments/1214730549969813504/1220142620693631039/web-contact.JPG?ex=660ddd5d&is=65fb685d&hm=d4be069b08e75adabc812e39dc2af8cf43f35b8caea9dcd879e3821efaee4041&=&format=webp&width=842&height=579"><img src="https://media.discordapp.net/attachments/1214730549969813504/1220142620693631039/web-contact.JPG?ex=660ddd5d&is=65fb685d&hm=d4be069b08e75adabc812e39dc2af8cf43f35b8caea9dcd879e3821efaee4041&=&format=webp&width=842&height=579" style="height: 80%; width:80%;"/></a>
<a href="https://media.discordapp.net/attachments/1214730549969813504/1220142620949348443/web-responsive.JPG?ex=660ddd5d&is=65fb685d&hm=c017605133c4f1791a038f641e30c279d366d95f0f92a93cf2451d41bc2c889f&=&format=webp&width=320&height=579"><img src="https://media.discordapp.net/attachments/1214730549969813504/1220142620949348443/web-responsive.JPG?ex=660ddd5d&is=65fb685d&hm=c017605133c4f1791a038f641e30c279d366d95f0f92a93cf2451d41bc2c889f&=&format=webp&width=320&height=579" style="height: 50%; width:50%;"/></a>

## Credits:

**Author:**

```bash
  Darwin Paz
```

**Unter der Leitung von:**

```bash
  Norbert Maier
```

```http
  Abgabetermin:
```

| Stadt:      | Datum:            | Bis:          |
| :---------- | :---------------- | :------------ |
| `Darmstadt` | `Fr - 22.03.2024` | **10:30 Uhr** |
