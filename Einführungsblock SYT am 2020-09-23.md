# Einführungsblock SYT am 2020-09-23

---

## &copy; Anne Kreppenhofer 4AHIT

---

## Dokumentation

Wie wir alle wissen ist die Dokumentation der wichtigste Teil von einem Lernprozess, denn ich kann noch so viele Sachen zusammen suchen und mir durchlesen, aber wenn ich es nicht irgendwo niederschreibe werde ich es nicht dann verwenden können wenn ich es brauche.

### Markdown [1] [2] 

Mit Markdown kannst du Text gestalten der beispielsweise im Web angezeigt wird. Wichtig wird aber Markdown wenn man Sachen auf Github schreiben will wie:

- Gists
- Kommentare in Issues und Pull Requests 
- Dateien mit den Endungen **.md** oder **.mardown**
  Nun Folgen ein paar Dinge was man mit Markdown alles tun kann:

#### Headers

Mit **\#** kann man Überschriften erzeugen. Umso mehr \# man verwendet umso kleiner wir deine Überschrift. Wenn man eine Überschrift mit nur einer Raute(\#) markiert ist diese äquivalent zu einer Überschrift der Größe \<h1> in einem Html code. Somit ergibt sich:

| Markdown | Html tag |
| -------- | -------- |
| \#       | \<h1>    |
| \##      | \<h2>    |
| \###     | \<h3>    |
| \####    | \<h4>    |
| \#####   | \<h5>    |

#### Emphasis

Durch die Verwendung von \* und \_ kann man Schriftstücke sowohl **fett** als auch *kursiv* aussehen lassen. Dabei muss mach beachten, dass **fett gedruckte Schrift immer durch zweimalige Verwendung dieser Zeichen erzeugt wird also entweder \*\* oder \_\_ ** und *kursive Schrift immer nur ein Zeichen benötigt, also \* oder \_*. Man kann beide Arten nicht mit ein ander verbinden. Also der folgende Code funktioniert nicht:

```markdown
*Text_
**noch mehr Text__
```

Man sieht  schon dabei, dass das Kursive auf das fett Gedruckte übergeschwappt ist.
Weites kann man noch Text mit \~\~ ~~durchstreichen~~.

| Markdown      | Ergebnis |
| ------------- | -------- |
| \*Text\*      | *Text*   |
| \_Text\_      | _Text_   |
| \*\*Text\*\*  | **Text** |
| \_\_Text\_\_  | __Text__ |
| \~\~ Text\~\~ | ~~Text~~ |

Man kann auch die drei **Dinge *verbinden* und so *~~etwas~~* erzeugen**. Man sollte nur dabei immer auf die Form achten und die Bereiche richtig in einander verschachteln. Hin und wieder kann es auch vorkommen, dass diese Dinge nicht richtig angezeigt werden. 

**Bekannte Fehler hierbei sind:**

- Abstände zwischen dem Zeichen und dem Wort welches verändert werden sollen
- Zeichen zuvor nicht geschlossen 
- Das falsche Zeichen verwendet bzw. zu wenig

#### Listen

Weiters gibt es auch noch Möglichkeiten den Text in Listen darzustellen.
Diese können entweder geordnet oder ungeordnet sein.

##### geordnete Liste

1. Ich bin
2. eine
3. geordnete Liste

Geordnete Liste kann man erstellen indem man die erste Zahl der Liste mit einem Punkt dahinter aufschreibt (1.), dabei muss beachtet werden, dass die Zahl an der ersten Stelle in einer neuen Zeile steht. Danach kann man den Text hinschreiben. Wenn man einen Abstand davor einfügt bekommt es ein "schöneres Format" (es wird eingerückt).

##### ungeordnete Liste

* Ich 
* bin eine ungeordnete
* Liste
  * mit 
  * Unterpunkten
    * Juhu

Ungeordnete Listen kann man mit zwei verschieden Zeichen erzeugen entweder mit * , mit + oder mit - , dabei ist wieder zu beachten, dass diese an der ersten Stelle stehen müssen von einer neuen Zeile. Wenn man Unterpunkte erzuegen will muss man vor dem Zeichen zwei Abstände einfügen:

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

#### Bilder

![GitHub Logo][3]
Bilder kann man mit dem folgenden Code einfügen (der Code vom oberen Beispiel ohne Referenz):

````markdown
![GitHub Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Octicons-logo-github.svg/1200px-Octicons-logo-github.svg.png)
Format: ![Alt Text](url)
````

Dabei kann man wie auch bei Links Referenzen erstellen und diese dann an einem anderen Ort dann die Links verwenden. Mehr dazu unter Links.

#### Links

Wie kann man eine richtige Dokumentation erstellen ohne seine Links anzugeben? Gar nicht! Also folgen nun Links. Links kann man entweder einfach in den Code schreiben aller http://github.com  oder sie etwas "schöner" verlinken aller [GitHub](http://github.com ). Natürlich ist und bleibt die "schönste Variante " wenn man es noch mit einer Referenz ausstattet und dann als Quelle auszeichnet [GitHub][4].

````markdown
http://github.com
[GitHub](http://github.com)
[GitHub][4]
````

#### Blockzitate

Wenn man ganz lustig drauf ist kann mach auch gerne Blockzitate einfügen:

Als Yoda einmal sagte:

>Furcht führt zu Wut,
>Wut führt zu Hass,
>und Hass führt zu unsäglichem Leid

````markdown
>Furcht führt zu Wut,
>Wut führt zu Hass,
>und Hass führt zu unsäglichem Leid
````

Natürlich kann man hier auch eichfach die wichtigsten Dinge aus jedem Unterpunkt aufschreiben.


#### Inline Code

Und hier wohl noch eines der wichtigsten Abschnitte von Markdown: Code!
Um ein Code Feld zu öffnen muss man drei Mal dieses \` Zeichen eingeben. Danach kann optional noch die Sprache dazuschreiben und am Ende wieder mit diesen drei Zeichen schließen.

```markdown
​```html
<!DOCTYPE html>
<html>
<body>

<h1>The code element</h1>

<p>The HTML <code>button</code> tag defines a clickable button.</p>

<p>The CSS <code>background-color</code> property defines the background color of an element.</p>

</body>
</html>
​```
```

#### Escapen 

Natürlich kann man auch Zeichen Escapen also ausweichen indem man einfach einen \\ davor schreibt. 

#### Zusammenfassung 

Markdown ist eine einfache Art schnell technische Dinge zu dokumentieren und auch Code Teile einzubauen. Im oberen Teil habe ich ein paar wichtige Passagen erklärt wie man mit Markdown arbeiten kann, sonst kann ich nur noch auf die folgenden Seite verweisen wenn weitere Fragen aufkommen. [1] [2] [5] 

### Latex

Daher ich bereits letztes Jahr schon mit Latex gearbeitet habe werde ich mich hier etwas kürzer halten (und weil ich das Latex Template vom Herrn Markus Reichl und vom Herrn Prof. Michael Borko kenne und dieses wirklich sehr gut und sehr ausführlich ist. [6])

---

## Frameworks & Buildtools

### Gradle



---

## Quellen

[1]:https://guides.github.com/features/mastering-markdown/ "Mastering Markdown von Github Guides besucht am 23.09.2020"

[2]:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet vonAdam Pritchard besucht am 23.09.2020"

[3]:https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Octicons-logo-github.svg/1200px-Octicons-logo-github.svg.png "Github Logo von Wikipedia besucht am 23.09.2020"

[4]:http://github.com "Github besucht am 23.09.2020"

[5]:https://markdown.de/ "Markdown:Synatx von Lasar Liepins besuchat am 23.09.2020 "

[6]:https://github.com/TGM-HIT/latex-protocol "Git Repository von Michael Borko und Markus Reichel besucht am 23.09.2020"

