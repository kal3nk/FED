# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Auteur:
  Seth Verhaart

  #### Je startniveau:
  De blauwe piste, maar ik zal ook de rode piste proberen te maken.

  #### Je focus:
  hier je focus (kies uit responsive óf surface plane)
  Mijn focus wordt de surface plane.
 
</details>





## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Je opdracht:
  Goodreads
  https://www.goodreads.com

  #### Screenshot(s) van de eerste pagina (small screen): 
  Goodreads | Meet your next favorite book
  https://www.goodreads.com
  
  <img src="readme-images/Goodreads-Meet-your-next-favorite-book.png" width="375px" alt="Dit is een screenshot van de homepagina van de website Goodreads.">

  #### Screenshot(s) van de tweede pagina (small screen):
  1984 by George Orwell | Goodreads 
  https://www.goodreads.com/book/show/61439040-1984
  
  <img src="readme-images/1984-by-George-Orwell-Goodreads.png" width="375px" alt="Dit is een screenshot van de boekpagina voor het boek 1984 van George Orwell.">
 
</details>



## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 2<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen:

  Ik zal eerst een lijst samenstellen van wat Goodreads wel goed doet, met commentaar. De  lijst er onder noem ik dingen die heel erg missen van de website.
  
  ### Content
  - Use left-aligned text for left-to-right (LTR) languages, and right-aligned text for right-to-left (RTL) languages. (In het Engels is het LTR en in het Japans is het RTL.)

  ### Global Code
  - Provide a unique title for each page or view. (Er zijn unieke titles voor iedere pagina.)
  - Ensure that viewport zoom is not disabled. (Het is enabled.)
  - Use landmark elements to indicate important content regions. 
  - Ensure a linear content flow. (Wordt tabindex gebruikt met alleen maar 0 en -1 als waardes.)
  - Avoid using the autofocus attribute. (Er is geen autofocuse attribute.)

  ### Lists
  - Use list elements (ol, ul, and dl elements) for list content. (Worden ol's en ul's gebruikt.)

  ### Controls
  - Use the a element for links. (Worden a href= elements gebruikt.)
  - Ensure that links are recognizable as links. (Het wordt onderlijnd of er is een animatie zichtbaar.)
  - Use the button element for buttons. (Buttons worden gebruikt.)
  - Identify links that open in a new tab or window. (Alleen maar links die leiden naar andere websites openen in een nieuwe tab, en deze zijn makkelijk te onderscheiden van andere links.)

  ### Media
  - Make sure that media does not autoplay. (Heb een aantal video's gecheckt en om ze te kunnen bekijken moet ik op een playbutton klikken.)
  - Check to see all media can be paused. (Heb een aantal video's afgespeeld en gepauzeerd.)

  ### Appearance
  - Check your content in specialized browsing modes. (Zowel high contrast als inverted colors geprobeerd, de content is leesbaar, maar sommige boekcovers zijn amper te begrijpen.)
  - Increase text size to 200%. (Het kan.)
  - Make sure color isn't the only way information is conveyed. (Het wordt aangegeven met onderlijningen of met buttons.)


  ### Animation
  - Ensure animations are subtle and do not flash too much. (Animaties zijn erg beperkt, maar de gene die er zijn, zijn heel erg minimaal. Alleen maar hover animaties, met veranderde kleuren.)

  ### Color contrast
  - Check the contrast for all normal-sized text. (Erg duidelijk contrast, vooral donker groen en zwart op beige/gebroken wit.)
  - Check the contrast for all large-sized text (Hetzelfde geldt voor dit als het gene wat hierboven vermeldt word.)
  - Check the contrast of borders for input elements (text input, radio buttons, checkboxes, etc.). (Dit is erg grootschalig goed verwerkt. Het enige wat tegenvalt is de "login with apple" button, maar dit is een template die ze gebruiken, niet van de webdevelopers zelf.)
  - Check text that overlaps images or video. (Dit is zowel promotie materiaal als andere images goed gedaan, behalve bij sommige bookcovers, maar dit is niet de keuze van de developers, maar het gene wat ze hebben ontvangen van de uitgevers.)

  ### Mobile and touch
  - Check that the site can be rotated to any orientation. (Ja dit kan.)
  - Ensure that button and link icons can be activated with ease. (Hier had ik zelf geen enkele moeite mee.)
  - Ensure sufficient space between interactive items in order to provide scroll area. (Er zijn genoeg sufficient scorlling areas, ik had er zelf in ieder geval geen last van, maar misschien is het wel voor iemand anders moeilijk met een bepaalde beperking.)

  ### Niet aangehouden richtlijnen die mij erg opvallen
  - Validate your HTML. (Er zijn echt ontzettend veel errors in deze HTML.
  - Use a lang attribute on the html element. (Er is geen aangegeven taal en die is ook nergens te vinden.)
  - Make sure that all img elements have an alt attribute. (Geen enkel img element heeft een alt attribute, en op bepaalde pagina's zijn er zo enorm veel bookcovers en andere images, dat ik me echt afvraag hoe iemand ooit deze website met een screenreader zou kunnen gebruiken.)
  - Headings. (Er is in allebei mijn pagina's geen enkele heading te bekennen, dus dit hele onderwerp kan ik eigenlijk niks mee.)
  - Provide a skip link and make sure that it is visible when focused. (Er zijn geen skiplinks available.)
  - Confirm the presence of captions. (Er zijn geen captions bij video's.)
  - Confirm that transcripts are available. (Er zijn geen transcripts beschikbaar.)

    
</details>



## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 3<sup>e</sup> werkgroep</summary>

  ### de hele pagina: 
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van de hele pagina">

  ### dynamisch deel (bijv menu): 
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van een dynamisch deel">

  ### wellicht nog een dynamisch deel (bijv filter): 
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van nog een dynamisch deel">

</details>





## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
- ...

</details>





## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 9<sup>e</sup> werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):

</details>





## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3<sup>e</sup> voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

  ### Je uitkomst - karakteristiek screenshots:
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="uitomst opdracht 1">


  ### Dit ging goed/Heb ik geleerd: 
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="top">


  ### Dit was lastig/Is niet gelukt:
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="bummer">
</details>





## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

  Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg). 
  Nb. ChatGpT en andere AI horen er ook bij.
  Nb. Vermeld de bronnen ook in je code.

  1. bron 1
  2. bron 2
  3. ...

</details>
