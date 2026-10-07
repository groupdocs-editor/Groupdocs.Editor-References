---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Basabstrakt klass för alternativen för alla dokument med fast layout, såsom PDF och XPS."
type: docs
weight: 16
url: /sv/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Basabstrakt klass för alternativen för alla dokument med fast layout, såsom PDF och XPS.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Hämtar eller anger flaggan som indikerar om bilder ska hoppas över vid konvertering av inmatningsdokument med fast layout till den resulterande HTML. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Hämtar eller anger flaggan som indikerar om bilder ska hoppas över vid konvertering av inmatningsdokument med fast layout till den resulterande HTML. |
|
|  | [getPages()](#getPages--) | Tillåter att ange ett sidintervall att bearbeta. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Tillåter att ange ett sidintervall att bearbeta. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Tillåter att aktivera (true) eller inaktivera (false) paginering i det resulterande HTML-dokumentet. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Tillåter att aktivera (true) eller inaktivera (false) paginering i det resulterande HTML-dokumentet. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Hämtar eller anger flaggan som indikerar om bilder ska hoppas över vid konvertering av inmatningsdokument med fast layout till den resulterande HTML. Standard är false - bilder bevaras.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Hämtar eller anger flaggan som indikerar om bilder ska hoppas över vid konvertering av inmatningsdokument med fast layout till den resulterande HTML. Standard är false - bilder bevaras.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Tillåter att ange ett sidintervall att bearbeta. Som standard bearbetas alla sidor i ett dokument med fast layout.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Tillåter att ange ett sidintervall att bearbeta. Som standard bearbetas alla sidor i ett dokument med fast layout.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Tillåter att aktivera (true) eller inaktivera (false) paginering i det resulterande HTML-dokumentet. Som standard är den inaktiverad (false).

<br />

*** ** * ** ***

Dokument i fast-layout-format (PDF och XPS i synnerhet) är i sin essens strikt paginerade, deras innehåll har en fast layout och är uppdelat på sidor. Men den resulterande redigerbara HTML:n kan representeras antingen i en sidlös eller paginerad vy.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Tillåter att aktivera (true) eller inaktivera (false) paginering i det resulterande HTML-dokumentet. Som standard är den inaktiverad (false).

<br />

*** ** * ** ***

Dokument i fast-layout-format (PDF och XPS i synnerhet) är i sin essens strikt paginerade, deras innehåll har en fast layout och är uppdelat på sidor. Men den resulterande redigerbara HTML:n kan representeras antingen i en sidlös eller paginerad vy.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

