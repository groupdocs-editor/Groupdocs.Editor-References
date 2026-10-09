---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara Presentation PowerPoint-kompatibla dokument"
type: docs
weight: 34
url: /sv/nodejs-java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara Presentation
(PowerPoint-kompatibla) dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Denna parameterlösa konstruktor skapar en ny instans av PresentationSaveOptions med PPTX-utdataformat (kan sedan modifieras genom |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) egenskap)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Skapar en ny instans av PresentationSaveOptions med angivet |
obligatoriskt Presentation-utdataformat, medan alla andra parametrar är
standard
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPassword()](#getPassword--) | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för |
kodar det resulterande Presentation-dokumentet.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Tillåter att ange, modifiera och hämta lösenordet, som kommer att användas för att koda det resulterande Presentation-dokumentet. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Tillåter att infoga redigerad bild i befintlig presentation istället för att skapa en ny enkelsidig presentation (standardbeteende). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Tillåter att infoga redigerad bild i befintlig presentation istället för att skapa en ny enkelsidig presentation (standardbeteende). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Boolesk flagga, som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) egenskap, eller så ska den injiceras mellan befintlig bild och föregående, utan att ersätta dess innehåll.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Boolesk flagga, som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) egenskap, eller så ska den injiceras mellan befintlig bild och föregående, utan att ersätta dess innehåll.
|
|  | [getOutputFormat()](#getOutputFormat--) | Tillåter att ange ett Presentation-format, som kommer att användas för att spara dokumentet |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Tillåter att ange ett Presentation-format, som kommer att användas för att spara dokumentet |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Tillåter att ange en array med 1-baserade bildnummer som ska tas bort från presentationen vid sparande, om den redigerade bilden infogas i en befintlig presentation. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Tillåter att ange en array med 1-baserade bildnummer som ska tas bort från presentationen vid sparande, om den redigerade bilden infogas i en befintlig presentation. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Denna parameterlösa konstruktor skapar en ny instans av PresentationSaveOptions med PPTX-utdataformat (kan sedan modifieras genom
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) egenskap)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Skapar en ny instans av PresentationSaveOptions med angivet
obligatoriskt Presentation-utdataformat, medan alla andra parametrar är
standard


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Obligatoriskt utdataformat, i vilket presentationsdokumentet ska sparas |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Tillåter att ange, ändra och hämta lösenordet som kommer att användas för
kodning av det resulterande presentationsdokumentet. Standardvärdet är NULL -
lösenordet kommer inte att sättas. Sätt till NULL eller en tom sträng för att ta bort
lösenordet, om det tidigare har satts.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Tillåter att ange, modifiera och hämta lösenordet, som kommer att användas för att koda det resulterande Presentation-dokumentet.
Standardvärdet är NULL - lösenordet kommer inte att sättas. Sätt till NULL eller en tom sträng för att ta bort lösenordet, om det tidigare har satts.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Tillåter att infoga redigerad bild i befintlig presentation istället för att skapa en ny enkelsidig presentation (standardbeteende).
Slide number är ett 1-baserat nummer på en bild i presentationen som har laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas en ny presentation med en enda redigerad bild. Om det är större eller mindre än noll, och det finns en giltig presentation som har laddats i Editor‑klassen, kommer den redigerade bilden, lagrad i den inmatade EditableDocument‑instansen, att infogas i denna presentation.

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


Tillåter att infoga redigerad bild i befintlig presentation istället för att skapa en ny enkelsidig presentation (standardbeteende).
Slide number är ett 1-baserat nummer på en bild i presentationen som har laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas en ny presentation med en enda redigerad bild. Om det är större eller mindre än noll, och det finns en giltig presentation som har laddats i Editor‑klassen, kommer den redigerade bilden, lagrad i den inmatade EditableDocument‑instansen, att infogas i denna presentation.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Boolesk flagga, som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) egenskap, eller så ska den injiceras mellan befintlig bild och föregående, utan att ersätta dess innehåll.
Standardvärdet är false \u2014 befintlig bild kommer att ersättas. Denna egenskap ignoreras om värdet av
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))‑egenskapen är satt till '0'.

<br />

*** ** * ** ***

Som standard ersätts bilden. Det innebär att om den givna presentationen har 5 bilder, och SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, så kommer den fjärde bilden att ersättas med den nya redigerade bilden, medan det totala antalet bilder i presentationen (5) förblir oförändrat. Om värdet på denna egenskap däremot sätts till  *true* , kommer den nya redigerade bilden att infogas som den fjärde bilden, och alla efterföljande bilder kommer att flyttas åt slutet: den \"old\" fjärde bilden blir femte, och den femte blir sjätte, och det totala antalet bilder i presentationen ökas med ett och blir 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Boolesk flagga, som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) egenskap, eller så ska den injiceras mellan befintlig bild och föregående, utan att ersätta dess innehåll.
Standardvärdet är false \u2014 befintlig bild kommer att ersättas. Denna egenskap ignoreras om värdet av
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))‑egenskapen är satt till '0'.

<br />

*** ** * ** ***

Som standard ersätts bilden. Det innebär att om den givna presentationen har 5 bilder, och SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, så kommer den fjärde bilden att ersättas med den nya redigerade bilden, medan det totala antalet bilder i presentationen (5) förblir oförändrat. Om värdet på denna egenskap däremot sätts till  *true* , kommer den nya redigerade bilden att infogas som den fjärde bilden, och alla efterföljande bilder kommer att flyttas åt slutet: den \"old\" fjärde bilden blir femte, och den femte blir sjätte, och det totala antalet bilder i presentationen ökas med ett och blir 6.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Tillåter att ange ett Presentation-format, som kommer att användas för att spara dokumentet

<br />

*** ** * ** ***

Utdataformatet sätts vanligtvis i konstruktorn för denna klass, eftersom det är obligatoriskt. Denna egenskap möjliggör att hämta eller ändra utdataformatet senare, när en instans av klassen [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) redan har skapats.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Tillåter att ange ett Presentation-format, som kommer att användas för att spara dokumentet

<br />

*** ** * ** ***

Utdataformatet sätts vanligtvis i konstruktorn för denna klass, eftersom det är obligatoriskt. Denna egenskap möjliggör att hämta eller ändra utdataformatet senare, när en instans av klassen [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) redan har skapats.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Tillåter att ange en array med 1‑baserade bildnummer som ska tas bort från presentationen vid sparande, om den redigerade bilden infogas i en befintlig presentation. När den redigerade bilden sparas inte som en ny enkelsidig presentation (standardbeteende), utan istället sparas i en befintlig presentation (med #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), är det också möjligt att ta bort vissa specifika bilder från denna presentation genom att ange deras nummer i denna array. Standardvärdet för arrayen är  null  \u2014 inga bilder kommer att tas bort. Men när arrayen är icke‑null och inte tom, och den innehåller minst ett giltigt bildnummer, kommer efter att presentationsdokumentet har genererats med innehållet från den redigerade bilden, bilderna med angivna nummer att tas bort från presentationen precis innan dess innehåll skrivs till utströmmen eller filen. Bildnummer i denna array är 1‑baserade, inte 0‑baserade. Ogiltiga nummer (mindre än 1 eller större än det totala antalet bilder) ignoreras.


**Returns:**
int[] – Array med 1‑baserade bildnummer att ta bort, eller  null  om inget ska tas bort.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Tillåter att ange en array med 1‑baserade bildnummer som ska tas bort från presentationen vid sparande, om den redigerade bilden infogas i en befintlig presentation. Bildnumren i denna array är 1‑baserade. Ogiltiga nummer ignoreras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Array med 1‑baserade bildnummer att ta bort (kan vara  null  eller tom). |
|

