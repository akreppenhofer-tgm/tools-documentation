# Einführungsblock SYT am 2020-09-23
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

Markdown | Html tag
------------ | -------------
\# | \<h1>
\## | \<h2>
\### | \<h3>
\#### | \<h4>
\##### | \<h5>

#### Emphasis
Durch die Verwendung von \* und \_ kann man Schriftstücke sowohl **fett** als auch *kursiv* aussehen lassen. Dabei muss mach beachten, dass **fett gedruckte Schrift immer durch zweimalige Verwendung dieser Zeichen erzeugt wird also entweder \*\* oder \_\_ ** und *kursive Schrift immer nur ein Zeichen benötigt, also \* oder \_*. Man kann beide Arten nicht mit ein ander verbinden. Also der folgende Code funktioniert nicht:

```markdown
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

Ungeordnete Listen kann man mit zwei verschieden Zeichen erzeugen entweder mit * oder mit - , dabei ist wieder zu beachten, dass diese an der ersten Stelle stehen müssen von einer neuen Zeile. Wenn man Unterpunkte erzuegen will muss man vor dem Zeichen zwei Abstände einfügen:

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

#### Bilder

![image-20200923095235245](C:\Users\annek\AppData\Roaming\Typora\typora-user-images\image-20200923095235245.png)

Bilder kann man mit einem 


### Latex
---
## Frameworks & Buildtools
### Gradle
---
## Quellen
[1]:https://guides.github.com/features/mastering-markdown/ "Mastering Markdown von Github Guides besucht am 23.09.2020" Mastering Markdown von Github Guides besucht am 23.09.2020

[2]:https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheatsheet vonAdam Pritchard besucht am 23.09.2020"
