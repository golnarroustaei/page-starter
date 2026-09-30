# page starter

Eine HTML-Seite. Kein Build, keine Bibliothek. Ziel: GitHub Pages.

Beispiel: [gsabau.github.io/page-starter/index.html](https://gsabau.github.io/page-starter/index.html)

Der Starter hat das Layout schon in Schwarz-Weiß: Kopf mit Menü, Liste, Text, drei Bildplätze, Fuß. Keine Galerie. Ein Menüpunkt. Der Text ist Lorem ipsum.

## Branches

Trunk-Based. Jeder der drei Punkte ist ein eigener Branch. Kurzer Branch. Pull Request nach `main`. Den nächsten Branch erst vom aktualisierten `main` starten.

1. `feature/pages`
2. `feature/content`
3. `feature/styling`

Danach die eigene Seite mit GitHub Pages veröffentlichen.

## Kommentare im Code

Die Stellen sind im Code markiert. Die Marker heißen `Seite:`, `Inhalt:` und `Styling:`.

Suchen im Editor nach genau diesen Wörtern.

| Marker | Datei | So sieht der Kommentar aus |
|---|---|---|
| `Seite:` | `index.html` | HTML-Kommentar `<!-- Seite: ... -->` |
| `Inhalt:` | `index.html` | HTML-Kommentar `<!-- Inhalt: ... -->` |
| `Styling:` | `index.html` und `style.css` | in HTML `<!-- Styling: ... -->`, in CSS `/* Styling: ... */` |

`Seite:` steht einmal, im Menü, direkt über dem einzigen Menüpunkt.

`Inhalt:` steht in `index.html` im `main`, jeweils direkt über dem Stück, das ersetzt wird: Überschrift, Absatz, Liste, zweite Überschrift, und jede der drei Spalten.

`Styling:` steht einmal in `index.html`, direkt über dem Link zu `style.css`. In `style.css` steht `/* Styling: ... */` über der Kopfzeile, dem Menü, der Textspalte, den drei Spalten und der Bildfläche.

## feature/pages

Zwei weitere Seiten, dasselbe Gerüst. Dasselbe Menü auf jeder Seite.

Eine neue Seite ist eine weitere HTML-Datei in diesem Ordner.

1. `index.html` kopieren, zum Beispiel nach `projekt.html`.
2. In **jeder** HTML-Datei im Menü einen Link ergänzen. Die Stelle ist der Kommentar `Seite:`:

```html
<a class="item" href="projekt.html">Projekt</a>
```

3. `style.css` bleibt eine Datei. Jede Seite verlinkt sie relativ mit `href="style.css"`.

## feature/content

Lorem ipsum durch eigene Sätze ersetzen. Die Kommentare `Inhalt:` in `index.html` markieren jedes Stück.

Ein Bild kommt als `img` in das Element mit der Klasse `imgWrap`. Der Kommentar in der Spalte sagt das.

## feature/styling

Das Schwarz-Weiß in `style.css` durch ein eigenes Aussehen ersetzen. Dieselbe Datei gilt für jede Seite.

Die Kommentare `Styling:` markieren die Regeln. In `index.html` zeigt der eine Kommentar nur auf die Datei. Die Änderungen stehen in `style.css`.

## Lokal öffnen

`index.html` im Browser öffnen.

## Lizenz

MIT. Siehe [LICENSE.md](LICENSE.md).
