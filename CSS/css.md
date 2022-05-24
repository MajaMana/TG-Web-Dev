# Theorie

In dit document zal ik de CSS vragen beantwoorden.

# CSS vragen hoofdstuk 1
### **Opdracht 1**

Je kunt op 3 verschillende manieren CSS in je HTML inladen. Op welke 3 manieren kun je dat doen? Leg ook voor elke wijze uit wat het precies inhoud.

*De verschillende manieren om CSS in je HTML in te laden zijn:*
1. Internal

*Internal staat voor het typen van de CSS elementen binnen het HTML document.*

2. External

*External staat voor extern een CSS document aanmaken waarin de CSS elementen geschreven worden. Binnen het HTML document wordt dan gelinkt naar het CSS document.*

3. Inline

*Inline staat voor het toepassen van CSS binnen 1 specifiek element van het HTML document. Denk aan de stijl aanpassen van < h1 >.*

<br>

### **Opdracht 2**

CSS pas je toe met een bepaalde syntax. Hoe ziet zo'n syntax eruit? Kun je ook uitleggen wat elk element uit de syntax betekent?

*Een CSS syntax start altijd met de elementen die de CSS waarde moeten krijgen. Daarna geef je een property en die property krijgt een value. Een voorbeeld hiervan is: < h1 > {color:red; font-size:10px;}*

*Dit betekent dus dat het < h1 > element een bepaalde stijl gaat krijgen. De stijl die hier wordt toegepast is 'color' met als value 'red' en de 'font-size' die als value '10px' heeft. Het < h1 > element zal dus een rode tekst hebben met een tekstgrootte van 10px.*

<br>

### **Opdracht 3**

Er zijn verschillende selectors, bijvoorbeeld;

* type selectors
* class selectors
* ID selectors
* descendant selectors

Maak van de bovengenoemde selectors voorbeelden. Geef in je antwoord ook aan wat de voordelen zijn van elke selector.

1. *De type selectors staan voor het gebruiken van 1 element waarbij alle elementen met die naam op de pagina dezelfde aanpassingen zullen krijgen. Denk aan:*

p {

    color:red

}

*Dit betekent dat alle 'p' elementen op de pagina de kleur rood zullen zijn. Dit is handig als iemand de stijl wil aanpassen van alle elementen met dezelfde naam op 1 pagina.*

<br>

2. *De class selectors staan voor het gebruiken van aanpassingen die voor alle elementen van 1 class zullen gelden. Denk aan:*

.navbar {

    color:red

}

*Dit betekent dat alle elementen met de class naam 'navbar' de kleur rood zullen zijn. Dit is handig als iemand de stijl wil aanpassen van alle elementen met dezelfde class attribuut. Je kan ook aangeven dat je alleen specifieke elementen met de class 'navbar' wilt stylen. Denk aan:*

p.navbar {

    color:red

}

*Nu zullen alleen de < p > elementen met de class 'navbar' de kleur rood krijgen. Het is ook mogelijk om de aanpassingen voor meerdere classes te laten gelden.*

<br>

3. *De id selectors staan voor het gebruiken van aanpassingen die alleen voor het id attribuut gelden van een specifiek element. Het id attribuut is zeldzaam op 1 pagina, dus gebruik maken van deze selector betekent dat maar 1 element wordt aangepast. Denk aan:*

#firstid {

    color: red

}

*Dit betekent dat het HTML element met de id 'firstid' de kleur rood zal krijgen. Dit is handig als 1 specifiek element aangepast moet worden, die een eigen id heeft. Zo zal het niet voorkomen dat ineens alle < p > elementen worden aangepast, maar alleen het element met de genoteerde id.*

<br>

4. *Descendant selectors staan voor aanpassingen die voor alle elementen gelden die afstammen van een specifiek element. Denk aan:*

div p {

    color: red

}

*Dit betekent dat alle < p > elementen binnen alle < div > elementen de kleur rood zullen krijgen. Dit is bijvoorbeeld handig als je snel de afstammeling elementen wilt aanpassen. Zo hoef je niet 10 keer een css code te schrijven, maar kan het in 1 keer.*

<br>

### **Opdracht 8**

Styling die je toepast wordt toegepast in een bepaalde volgorde. Het kan voorkomen dat je styling toepast en vervolgens niet het gewenste resultaat ziet. **_Cascade_** en **_Inheritance_** zijn belangrijke concepten om te begrijpen hoe styling werkt. Lees hier in de officiële documentatie meer over [cascade en inheritance](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance).

Zoek ook andere referenties om het concept te begrijpen.

Leg in eigen woorden uit wat met cascade en inheritance wordt bedoeld. Maak voorbeelden om je antwoord uit te leggen.

*CSS staat voor cascading style sheet. Door middel van cascade, worden conflicten binnen CSS opgelost. Als meerdere CSS regels gelden voor 1 HTML element, dan is cascade het algoritme wat bepaalt welke regels worden toegepast. Op deze manier worden de conflicten vermeden.*

Voorbeeld:

button {
    
    color: red

}

button {
    
    color: blue

}

*Het is niet mogelijk voor een element om 2 kleuren tegelijk te zijn. Dit is dus een conflict. Deze button zal de kleur blauw worden, omdat die regel onderaan staat. In het cascade algoritme staat dat de laatst toegevoegde regel toegepast zal worden. Zo wordt het conflict opgelost.*

<br>

*Met inheritance wordt bedoeld dat een element een CSS stijl zal krijgen van een 'voorouder' element als er niet specifiek een andere stijl aan wordt gegeven. Het gaat hier dus om stijlen die aan een eerder element zijn gegeven. Als de kleur van een < body > element blauw wordt gemaakt, zullen alle elementen binnen de body ook blauw worden als er niet specifiek een andere kleur aan de andere elementen wordt gegeven. Het voorbeeld staat in het document opdracht1.8.html.*

<br>

# CSS vragen hoofdstuk 2

### **Opdracht 1**

Wat zijn de eigenschappen van block boxes en inline boxes?

<br>

### **Opdracht 2**

Maak wat hieronder staat met paragraph en span tags.


<br>

### **Opdracht 3**

Wat gebeurt er als je een width en een height toevoegt aan de span tag ( &lt;span> ) van vorige opdracht?

<br>

### **Opdracht 4**

Leg uit wat de volgende termen betekenen: content, padding, margin en border.

<br>

### **Opdracht 5**

Als je ruimte wilt maken tussen de border en content, welke css property gebruik je dan? Maak een voorbeeld in je antwoord. 

<br>

### **Opdracht 6**

Als je ruimte wilt maken tussen de border en buiten de box, welke css property gebruik je dan? Maak een voorbeeld in je antwoord.

<br>

### **Opdracht 7**

Maak nu een blok met width: 100px, height: 100px, margin: 5px, padding 5px en border-width: 5px. Zie hieronder:

1. Hoe breed is de box?

2. Hoe hoog is de box?

3. Wat merk je op met width en height?

<br>

### **Opdracht 8**

Welke CSS property kun je gebruiken om ervoor te zorgen dat de waarde van width en height de totale breedte en hoogte is van het blok van de voorgaande opdracht?

<br>

# CSS vragen hoofdstuk 3

### **Opdracht 1**

De belangrijkste waardes van “position” zijn static, relative, absolute, fixed & sticky. Leg voor elke uit wat ze doen.

<br>

# CSS vragen hoofdstuk 4

### **Opdracht 1**

Er zijn 14 verschillende pseudo-elementen. Beschrijf ze alle 14 kort en maak voor elk een voorbeeld

<br>

# CSS vragen hoofdstuk 6

### **Opdracht 1**

Bij CSS Grid wordt vaak gebruikgemaakt van een speciale lengte-eenheid: “**fr**”. Onderzoek wat deze doet en beschrijf het in je eigen woorden.

<br>

# CSS vragen hoofdstuk 7

### **Opdracht 1**

Zoek uit wat transitions zijn en beschrijf met eigen woorden wat het betekent.

<br>

