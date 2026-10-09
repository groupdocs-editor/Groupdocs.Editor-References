---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade Presentation PowerPoint-kompatibla format"
type: docs
weight: 32
url: /sv/nodejs-java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade
Presentation (PowerPoint-kompatibla) format

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | Tillåter att ange bildnumren som ska öppnas för redigering |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Tillåter att ange bildnumren som ska öppnas för redigering |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | Anger om dolda bilder ska inkluderas eller inte. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Anger om dolda bilder ska inkluderas eller inte. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Tillåter att ange bildnumren som ska öppnas för redigering


*** ** * ** ***

Bildnummer är ett nollbaserat index för en bild som gör det möjligt att ange och välja en specifik bild från en presentation för redigering. Om värdet är mindre än 0 väljs den första bilden (samma som SlideNumber = 0). Om värdet är större än antalet bilder i presentationen väljs den sista bilden. Om den inmatade presentationen bara innehåller en enda bild kommer detta alternativ att ignoreras och den enda bilden kommer att redigeras. Om man försöker öppna en dold bild för redigering medan ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) är satt till 'false', kommer ett undantag att kastas.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Tillåter att ange bildnumren som ska öppnas för redigering


*** ** * ** ***

Bildnummer är ett nollbaserat index för en bild som gör det möjligt att ange och välja en specifik bild från en presentation för redigering. Om värdet är mindre än 0 väljs den första bilden (samma som SlideNumber = 0). Om värdet är större än antalet bilder i presentationen väljs den sista bilden. Om den inmatade presentationen bara innehåller en enda bild kommer detta alternativ att ignoreras och den enda bilden kommer att redigeras. Om man försöker öppna en dold bild för redigering medan ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) är satt till 'false', kommer ett undantag att kastas.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Anger om dolda bilder ska inkluderas eller inte. Standard är
false - dolda bilder visas inte och ett undantag kommer att kastas medan
man försöker redigera dem.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Anger om dolda bilder ska inkluderas eller inte. Standard är
false - dolda bilder visas inte och ett undantag kommer att kastas medan
man försöker redigera dem.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

