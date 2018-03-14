<!-- Überschriften -->
<!-- HTML-Überschriften <h1> bis <h6> lassen sich einfach durch ein Voranstellen
der entsprechenden Anzahl an Hashes (#) auszeichnen -->
#Markdown Tutorial
##Überschriften
<br  />

# Das ist eine h1 Überschrift
## Das ist eine h2 Überschrift
### Das ist eine h3 Überschrift
#### Das ist eine h4 Überschrift
##### Das ist eine h5 Überschrift 
###### Das ist eine h6 Überschrift


<!-- Für die Elemente <h1> und <h2> gibt es in Markdown noch Sonderformen -->
Das ist eine h1 Überschrift
= 
Das ist eine h2 Überschrift
-
<h3> html tags :D </h3>

<br  />
<br  />
## Textstyling
<br  />
<!-- Einfaches Textstyling -->
<!-- Jeglicher Text lässt sich mit Markdown leicht als kursiv oder auch als fett auszeichnen -->


<!-- Kursiver Text -->
*Dieser Text ist kursiv.*
_Genau wie dieser._


<!-- Fetter Text --> 
**Dieser Text ist fett.**
__Genau wie dieser.__


<!-- Beides -->
***Dieser Text ist beides***
**_Dieser auch!_**
*__Und dieser genau so!__*
___Und was ist mit dem?___</br>

<br  />
<br  />
###GitHub Flavored Markdown
<br  />
<!-- In "GitHub Flavored Markdown", dem von GitHub verwendeten Dialekt / Parser,
gibt es auch noch durchgestrichenen Text: -->

~~Dieser Text wird in Github Flavored Markdown durchgestrichen dargestellt.~~



<!-- Absätze sind eine oder mehrere zusammenhängende Zeilen Text, und werden
durch eine oder mehrere Leerzeilen voneinander abgesetzt. -->

Das ist ein Absatz. Ich kann immer noch nicht glauben, wie viel Spaß das macht !?!

Jetzt bin ich schon bei Absatz 2.
Hier ist dann immer noch Absatz 2!

Jetzt ist das dann Nummer drei!



<!-- Sollte man jemals ein <br />-Tag einfügen wollen, kann man einen Absatz
mit zwei oder mehr Leerzeichen beenden, und danach einen neuen Absatz beginnen. -->

Ich höre mit zwei Leerzeichen auf (markiere mich, und du siehst es).  <br />


<br  />
<br  />
<!-- Zitate werden ganz einfach mit einem  > ausgezeichnet. -->
##Zitate
<br  />
> Das ist ein Zitat. Du kannst Zeilenumbrüche
> entweder manuell hinzufügen und ein `>` vor jeder Zeile einfügen, oder du kannst deine Zeilen einfach immer länger und länger und länger und länger und länger und länger und länger und länger und länger und länger und länger  werden lassen, die Umbrüche werden dann automatisch erzeugt.
> Solange sie mit einem `>` beginnen, macht das keinen Unterschied.
> Hier ist das Zitat dann schon zu Ende (in dieser Ebene).

> Auch möglich ist es, den Text
>> mehrstufig einzurücken.
>>>nicht schlecht, oder?

<br  />
<br  />
<!-- Listen -->
<!-- <ul>s können mit Sternen, Pluszeichen oder Minuszeichen erzeugt werden -->
##Listen
<br  />

* Punkt auf der Liste
* Punkt auf der Liste
* Anderer Punkt auf der Liste

oder

+ Punkt auf der Liste
+ Punkt auf der Liste
+ Noch ein Punkt auf der Liste

oder

- Punkt auf der Liste
- Punkt auf der Liste
- Ein letzter Punkt auf der Liste

<!-- <ol>s werden mit einer Zahl gefolgt von einem Punkt erzeugt -->

1. Punkt eins
2. Punkt zwei
3. Punkt drei

<!-- Auch wenn es keine gute Idee sein mag: du müsstest die einzelnen Punkte
nicht mal korrekt nummerieren -->

1. Punkt eins
1. Punkt zwei
1. Punkt drei
<!-- (Das sieht genau so aus wie das Beispiel eins weiter oben) -->

<!-- Man kann Listen auch verschachteln -->

1. Punkt eins
2. Punkt zwei
	1. test 
	2. test
3. Punkt drei
    * Unterpunkt
    * Unterpunkt
4. Punkt vier

<br  />
<br  />
##Codeblöcke
<br  />
<!-- Code-Blöcke -->
<!-- Blöcke von Programmcode (also ein <code>-Element) kannst du auszeichnen,
indem du eine Zeile mit vier Leerzeichen oder einem Tabulator einrückst -->

    Das ist Quellcode
    Das hier auch
	meehr Quellcode

<!-- Der Code kann natürlich auch wiederum eingerückt sein -->


	function fancyAlert(arg) {
		if(arg) {
			$.facebox({div:'#foo'})	
		}
	}


<!-- Innerhalb normalen Texts kannst du Code mit Backticks ` auszeichnen -->

Hermann hatte nicht die leiseste Ahnung, was dieses `go_to()` bedeuten könnte!
<br  />
<br  />
###Github Flavored Markdown 
<br  />

<!-- In "GitHub Flavored Markdown" gibt es für Code nocheinmal eine
besondere Syntax -->

```
def foobar
    puts "Hallo Welt!"
end
```


<!-- der obige Block muss nicht extra eingerückt werden, außerdem fügt GitHub
Syntax-Highlighting für die nach dem ``` angegebene Sprache hinzu -->

<br  />
<br  />
##Trenner
<br  />

<!-- Horizontale Linie (<hr />) -->
<!-- Trenner lassen sich einfach mit drei (oder mehr) Sternen oder Bindestrichen
erzeugen (egal ob mit oder ohne Leerzeichen dazwischen)-->

***
---
- - -
****************

<br  />
<br  />
##Hyperlinks aka. Links
<br  />
<!-- Hyperlinks -->
<!-- Eines der besten Features von Markdown ist das kinderleichte Erzeugen von
Hyperlinks: Einfach den Linktext in eckige Klammern [] setzen, gefolgt von
einer mit runden Klammern () umschlossenen URL. -->

[Klick mich!](http://wikipedia.org/)

<!-- Man kann dem Link auch noch ein title-Attribut geben -->

[Link zu Wikipedia](http://wikipedia.org/ "Link zu wikipedia.org")


[Zu meiner Bildersammlung](/Bilder/)

<br />
<br />
##Bilder
<br />
<!-- Bilder -->
<!-- Bilder funktionieren genau wie Links, nur dass man noch ein Ausrufezeichen
voranstellt! -->

![](https://cdn0.iconfinder.com/data/icons/octicons/1024/markdown-512.png "Cooles alt-Attribut")

<br />
<br />
##Bonus 
<br />
<!-- Bonusfeatures -->
<!-- Auto-Links -->
####Verschiedene Möglichkeiten für Links
<http://wikipedia.org/> ist das selbe wie
[http://wikipedia.org/](http://wikipedia.org/)


<!-- Automatische Links für E-Mail-Addressen -->
<br />
####Email an...
<alexanderwallner1999@gmail.com>
<br />
####Maskieren
<!-- Maskieren -->

Ich würde *diesen Teil gerne mit Sternen umschließen*, doch ohne dass er kursiv
wird. Also mache ich folgendes: \*Ich umschließe diesen Text mit Sternen\*!



