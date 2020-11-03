# Test
### Hallo
- ich bin
# Inhaltsverzeichnis
## Einleitung
## Syntax
### Überschriften
- Überschriften leitet man immer mit einem # ein.
- Je nachdem wie viele # man nutzt wird die Überschrift etwas dicker oder dünner
z.B.
# Test
## Test
### Test
#### Test
- Alternativ dazu kann man darunter auch ----- oder ======

z.B.

Headline 1
=====

Headline 2
-------

### Zeichenumbüche
- dafür nutzt man hinter dem Satz 2 Leerzeichen. Dann Zeigt er es auf der nächsten Zeile an.

### Hervorhebungen
- Fett: mit **Text**  
            oder __Text__
            innerhalb des Textes
            Love**is**blind
- kursiv: mit _Text_
              oder *Text*
              innerhalb des Textes
              A*cat*meow
- Fett und Kursiv: mit ***Text***
                       oder
                       ___Text___
                       innerhalb des Textes:
                       This text is __*really important*__.

### Block Zitate
- beginnen mit einem > vor dem Paragrafen
z.B.
> Dorothy followed her through many of the beautiful rooms in her castle.

- verschachtelte Zitate
>Dorothy followed her through many of the beautiful rooms in her castle.
>> The Witch bade her clean the pots and kettles an sweep the floor and keep the fire fed with wood.

- Blockzitate mit anderen Elementen
  wenn man noch mit Aufzählungsliste machen möchte

> ### The quarterly results look great
>
> - Revenue was off the chart.
> - Profits were higher than ever
>
> *Everything* is going according to **plan**

### Listen
- man kann diese mit 1,2,3 oder auch 1,1,1, jeweils mit einem Leerzeichen.
Die Reihenfolge spielt dabei keine Rolle
1.
2.
3.

oder

1.
1.
1.

- ungeordnete Listen erfolgen mit -, *  oder +. Man muss sich allerdings für eines von den Sachen entscheiden und nicht durcheinander bringen.
* Test 1
* Test 1
- Test 2
- Test 2
+ Test 3
+ Test 3
- Test 4
  - Test 4

### Hinzufügen von Elementen in einer Liste.
###### Paragrafen: Entweder mit 4 Leerzeichen oder mit 4 Taps. Hier mit 4 Tabs.
* This ist the first list item
* Here's the second list item

        I need to add another paragraph below the second list item
* Here's the third list item

###### Blockzitate

* This ist the first list item
* Here's the second list item

        > I need to add another paragraph below the second list item

* Here's the third list item

###### Code Blöcke
mit dem .
1. Open the file.
1. Find the following code block in line 21
`test`

### Horizontale Linien
- dafür kann man 3 oder mehr Sternchen (*), Minuszeichen (-) oder Unterstrich(_)

***
___
---


### Links
- um einen Lin zu setzen muss man den Text in eckigen Klammern schreiben.

     My favorite search enging is [Duck Duck Go](https://duckduckgo.com)

- Man kann auch einen Titel zum Link Hinzufügen.

     My favorite search enging is [Duck Duck Go](https://duckduckgo.com)"The best search enging for privacy"

- URL und E-Mail Adresse
    dafür muss man die Dreiecke nehmen <>
    <https://www.markdownguide.org>
    <fake@example.com>

- Formatierung von Links
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org.de)*.
See the section on[`code`](#code).

- Referenzen
- [hobbit-hol][1]

- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit Lifestyles"
- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle `Hobbit Lifestyles`
- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit Lifestyles)
- [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit Lifestyles"
- [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> `Hobbit Lifestyles`
- [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit Lifestyles)

Beispiel:
In a hole in the ground there lived a hobbit. Not a nasy, dirty, wet hole, filled with the ends of worms an an oozy smell, nor yet a dry, bare, sandy hole with noting in it to sit down on or to eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles") and that means comfort.

oder

In a hole in the ground there lived a hobbit. Not a nasy, dirty, wet hole, filled with the ends of worms an an oozy smell, nor yet a dry, bare, sandy hole with noting in it to sit down on or to eat: it was a [hobbit-hole][1] and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

### Bilder
- vor dem Bild muss ein Ausrufezeichen stehen !, gefolgt vom ALternativtext und dem URL oder Pfad in Klammern.

![Kleid 13](/C:\Users\Kati\Desktop\Kleid\Stoff.PNG)
[![Logo Dataport]](https://de.wikipedia.org/wiki/Dataport#/media/Datei:Dataport_Logo.svg)

### Ausbleden
\* without the backslash, this would be a bullet in an unordered list
