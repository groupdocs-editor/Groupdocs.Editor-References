---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van Presentation PowerPoint‑compatibele documenten"
type: docs
weight: 34
url: /nl/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van Presentation
(PowerPoint‑compatibele) documenten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Deze parameterloze constructor maakt een nieuw exemplaar van PresentationSaveOptions met PPTX‑uitvoerformaat (kan vervolgens worden aangepast via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) eigenschap)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Maakt een nieuw exemplaar van PresentationSaveOptions met opgegeven |
verplicht Presentation‑uitvoerformaat, terwijl alle andere parameters
standaard
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor |
het coderen van het resulterende Presentation‑document.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Staat toe het wachtwoord op te geven, te wijzigen en op te halen, dat zal worden gebruikt voor het coderen van het resulterende Presentation‑document. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Staat toe een bewerkte dia in te voegen in een bestaande presentatie in plaats van een nieuwe één‑dia‑presentatie te maken (standaardgedrag). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Staat toe een bewerkte dia in te voegen in een bestaande presentatie in plaats van een nieuwe één‑dia‑presentatie te maken (standaardgedrag). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Booleaanse vlag die aangeeft of de bewerkte dia de bestaande dia in de oorspronkelijke presentatie moet vervangen op de positie, gespecificeerd door de |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) eigenschap, of moet deze worden ingevoegd tussen de bestaande dia en de vorige, zonder de inhoud te vervangen.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Booleaanse vlag die aangeeft of de bewerkte dia de bestaande dia in de oorspronkelijke presentatie moet vervangen op de positie, gespecificeerd door de |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) eigenschap, of moet deze worden ingevoegd tussen de bestaande dia en de vorige, zonder de inhoud te vervangen.
|
|  | [getOutputFormat()](#getOutputFormat--) | Staat toe een Presentation‑formaat op te geven, dat zal worden gebruikt voor het opslaan van het document |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Staat toe een Presentation‑formaat op te geven, dat zal worden gebruikt voor het opslaan van het document |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Staat toe een array met 1‑gebaseerde nummers van dia's op te geven die tijdens het opslaan uit de presentatie moeten worden verwijderd, voor het geval de bewerkte dia wordt ingevoegd in een bestaande presentatie. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Staat toe een array met 1‑gebaseerde nummers van dia's op te geven die tijdens het opslaan uit de presentatie moeten worden verwijderd, voor het geval de bewerkte dia wordt ingevoegd in een bestaande presentatie. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Deze parameterloze constructor maakt een nieuw exemplaar van PresentationSaveOptions met PPTX‑uitvoerformaat (kan vervolgens worden aangepast via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) eigenschap)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Maakt een nieuw exemplaar van PresentationSaveOptions met opgegeven
verplicht Presentation‑uitvoerformaat, terwijl alle andere parameters
standaard


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Verplicht uitvoerformaat waarin het Presentation‑document moet worden opgeslagen |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Staat toe het wachtwoord op te geven, te wijzigen en te verkrijgen, dat zal worden gebruikt voor
het coderen van het resulterende Presentation‑document. Standaard is NULL -
wachtwoord wordt niet ingesteld. Stel in op NULL of een lege tekenreeks om te verwijderen
het wachtwoord, indien het eerder was ingesteld.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Staat toe het wachtwoord op te geven, te wijzigen en op te halen, dat zal worden gebruikt voor het coderen van het resulterende Presentation‑document.
Standaard is NULL - wachtwoord wordt niet ingesteld. Stel in op NULL of een lege tekenreeks om het wachtwoord te verwijderen, indien het eerder was ingesteld.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Staat toe een bewerkte dia in te voegen in een bestaande presentatie in plaats van een nieuwe één‑dia‑presentatie te maken (standaardgedrag).
Slide number is een op 1 gebaseerd nummer van een dia in de presentatie, geladen in de Editor class. Als het 0 is (standaardwaarde), wordt de nieuwe presentatie aangemaakt met één bewerkte dia. Als het groter of kleiner is dan nul, en er een geldige presentatie is geladen in de Editor class, wordt de bewerkte dia, opgeslagen in de invoer EditableDocument instantie, ingevoegd in deze presentatie.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Staat toe een bewerkte dia in te voegen in een bestaande presentatie in plaats van een nieuwe één‑dia‑presentatie te maken (standaardgedrag).
Slide number is een op 1 gebaseerd nummer van een dia in de presentatie, geladen in de Editor class. Als het 0 is (standaardwaarde), wordt de nieuwe presentatie aangemaakt met één bewerkte dia. Als het groter of kleiner is dan nul, en er een geldige presentatie is geladen in de Editor class, wordt de bewerkte dia, opgeslagen in de invoer EditableDocument instantie, ingevoegd in deze presentatie.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Booleaanse vlag die aangeeft of de bewerkte dia de bestaande dia in de oorspronkelijke presentatie moet vervangen op de positie, gespecificeerd door de
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) eigenschap, of moet deze worden ingevoegd tussen de bestaande dia en de vorige, zonder de inhoud te vervangen.
Standaard is false \\u2014 bestaande dia zal worden vervangen. Deze eigenschap wordt genegeerd, als waarde van
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) eigenschap is ingesteld op '0'.

<br />

*** ** * ** ***

Standaard wordt dia vervangen. Dit betekent dat als de gegeven presentatie 5 dia's heeft, en SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, dan wordt de 4e dia vervangen door de nieuwe bewerkte dia, terwijl het totale aantal dia's in de presentatie (5) ongewijzigd blijft. Echter, als de waarde van deze eigenschap is ingesteld op *true*, wordt de nieuwe bewerkte dia ingevoegd als 4e dia, en alle daaropvolgende dia's worden verschoven naar het einde: "old" 4e dia wordt 5e, en 5e wordt 6e, en het totale aantal dia's in de presentatie wordt met één verhoogd tot 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Booleaanse vlag die aangeeft of de bewerkte dia de bestaande dia in de oorspronkelijke presentatie moet vervangen op de positie, gespecificeerd door de
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) eigenschap, of moet deze worden ingevoegd tussen de bestaande dia en de vorige, zonder de inhoud te vervangen.
Standaard is false \\u2014 bestaande dia zal worden vervangen. Deze eigenschap wordt genegeerd, als waarde van
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) eigenschap is ingesteld op '0'.

<br />

*** ** * ** ***

Standaard wordt dia vervangen. Dit betekent dat als de gegeven presentatie 5 dia's heeft, en SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, dan wordt de 4e dia vervangen door de nieuwe bewerkte dia, terwijl het totale aantal dia's in de presentatie (5) ongewijzigd blijft. Echter, als de waarde van deze eigenschap is ingesteld op *true*, wordt de nieuwe bewerkte dia ingevoegd als 4e dia, en alle daaropvolgende dia's worden verschoven naar het einde: "old" 4e dia wordt 5e, en 5e wordt 6e, en het totale aantal dia's in de presentatie wordt met één verhoogd tot 6.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Staat toe een Presentation‑formaat op te geven, dat zal worden gebruikt voor het opslaan van het document

<br />

*** ** * ** ***

Het uitvoerformaat wordt meestal ingesteld in de constructor van deze class, omdat het verplicht is. Deze eigenschap maakt het mogelijk om later het uitvoerformaat op te halen of te wijzigen, wanneer een instantie van de class [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) al is aangemaakt.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Staat toe een Presentation‑formaat op te geven, dat zal worden gebruikt voor het opslaan van het document

<br />

*** ** * ** ***

Het uitvoerformaat wordt meestal ingesteld in de constructor van deze class, omdat het verplicht is. Deze eigenschap maakt het mogelijk om later het uitvoerformaat op te halen of te wijzigen, wanneer een instantie van de class [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) al is aangemaakt.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Staat toe een array op te geven met op 1 gebaseerde nummers van dia's die tijdens het opslaan uit de presentatie moeten worden verwijderd, voor het geval de bewerkte dia wordt ingevoegd in een bestaande presentatie. Wanneer de bewerkte dia niet wordt opgeslagen als een nieuwe één-dias-presentatie (standaardgedrag), maar in plaats daarvan wordt opgeslagen in een bestaande presentatie (met behulp van #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), is het ook mogelijk om bepaalde dia's uit deze presentatie te verwijderen door hun nummers in deze array op te geven. Standaard is deze array  null  \\u2014 er worden geen dia's verwijderd. Echter, wanneer deze array niet-null en niet-leeg is, en ten minste één geldig dia-nummer bevat, worden na het genereren van het uitvoer-Presentation-document met de inhoud van de bewerkte dia, de dia's met de opgegeven nummers verwijderd uit de presentatie vlak voor het schrijven van de inhoud naar de uitvoer-stream of het bestand. Dia-nummers in deze array zijn 1-gebaseerd, niet 0-gebaseerd. Ongeldige nummers (kleiner dan 1 of groter dan het totale aantal dia's) worden genegeerd.


**Returns:**
int[] - Array van op 1 gebaseerde dia-nummers om te verwijderen, of  null  als er niets moet worden verwijderd.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Staat toe een array op te geven met op 1 gebaseerde nummers van dia's die tijdens het opslaan uit de presentatie moeten worden verwijderd, wanneer de bewerkte dia wordt ingevoegd in een bestaande presentatie. Dia-nummers in deze array zijn 1-gebaseerd. Ongeldige nummers worden genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | Array van op 1 gebaseerde dia-nummers om te verwijderen (kan  null  of leeg zijn). |
|

