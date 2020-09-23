# Einführungsblock SYT am 2020-09-23
---
## Dokumentation
Wie wir alle wissen ist die Dokumentation der wichtigste Teil von einem Lernprozess, denn ich kann noch so viele Sachen zusammen suchen und mir durchlesen, aber wenn ich es nicht irgendwo niederschreibe werde ich es nicht dann verwenden können wenn ich es brauche.
### Markdown [1] [2] 
Mit Markdown kannst du Text gestalten der beispielsweise im Web angezeigt wird. Wichtig iwr aber Markdown wenn du Sachen auf Github schreiben willst wie:
- Gists
- Kommentare in Issues und Pull Requests 
- Dateien mit den Endungen **.md** oder **.mardown**
Nun Folgen ein paar Dinge was man mit Markdown alles tun kann:
#### Headers
Mit **\#** kann man Überschriften erzeugen. Umso mehr \# man verwendet umso kleiner wir deine Überschrift. Wenn man eine Überschrift mit nur einer Raute(\#) markiert ist diese äquivalent zu einer Überschrift der Größe \<h1> in einem Html code. Somit ergibt sich:

Markdown | Html tag
------------ | -------------
\# | \<h1>
\## | \<h2>
\### | \<h3>
\#### | \<h4>
\##### | \<h5>

#### Emphasis
Durch die Verwendung von \* und \_ kann man Schriftstücke sowohl **fett** als auch *krusiv* aussehen lassen. Dabei muss mach beachten, dass **fett gedruckte Schrift immer durch zweimalige Verwendug dieser Zeichen erzeugt wird also entweder \*\* oder \_\_ ** und *kursive Schrift immer nur ein Zeichen benötigt, also \* oder \_*. Man kann beide Arten nicht mit ein ander verbinden. Also der folgende Code funktioniert nicht:
```Markdown
*Text_
**noch mehr Text__
```
Man sieht  schon dabei, dass das Kursive auf das fett Gedruckte übergeschwappt ist.
Weites kann man noch Text mit \~\~ ~~durchstreichen~~.

Markdown | Ergebnis
------------ | -------------
\*Text\* |*Text*
\_Text\_ | _Text_
\*\*Text\*\* | **Text**
\_\_Text\_\_ | __Text__
\~\~ Text\~\~ | ~~Text~~
Man kann auch die drei **Dinge *verbinden* und so *~~ etwas~~* erzeugen**. Man sollte nur dabei immer auf die Form achten und die Bereiche richtig in einander verschachteln.

### Latex
---
## Frameworks & Buildtools
### Gradle
---
## Quellen
[1]:https://guides.github.com/features/mastering-markdown/ "Mastering Markdown von Github Guides besucht am 23.09.2020"
[2]:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet vonAdam Pritchard besucht am 23.09.2020"