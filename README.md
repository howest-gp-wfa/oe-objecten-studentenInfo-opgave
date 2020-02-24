oe-objecten-studentenInfo-start

Houd de gegevens van een student bij in een JS-object
# Objecten: info over een studentbeheren
## Opstarten
- Koppel de DOM-elementen
- Koppel *WijzigObject()* toe aan **btnVoegToe**
- Maak een object **student** aan met een naam, een voornaam en een leeftijd
- Roep de methode *ToonObject()* aan die de info over de student toont
## Info over student wijzigen
- In function *WijzigObject( )*
  - Lees je de info uit GUI
  - Pas de informatie van de student op basis hiervan aan
  - Roep je de methode *ToonObject()* aan
## VoegKeyValueDivToe
Wijzig *ToonObject()* zodat de verschillende key-value paren in aparte div-elementen getoond worden via calls naar *VoegKeyValueDivToe()*
- Maak een div-element aan
- Plaats in het div-element de info van de key- en value
- Geef het de klasse studentenKenmerk
- Geef het div-element de tooltip: 'Klik om het kenmerk [key-naam] te wijzigen'
- Zorg ervoor dat bij een klik de info uit het key-value paar getoond wordt in de textboxen
- Voeg het divElement toe aan **divFeedback**
