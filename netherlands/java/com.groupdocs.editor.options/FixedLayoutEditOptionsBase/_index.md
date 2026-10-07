---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Basis abstracte klasse voor de opties voor alle documenten van vaste‑indelingsformaten zoals PDF en XPS."
type: docs
weight: 16
url: /nl/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Basis abstracte klasse voor de opties voor alle documenten van vaste‑indelingsformaten zoals PDF en XPS.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Haalt de vlag op of stelt deze in die aangeeft of afbeeldingen moeten worden overgeslagen bij het converteren van het invoer‑fixed‑layout‑document naar de resulterende HTML. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Haalt de vlag op of stelt deze in die aangeeft of afbeeldingen moeten worden overgeslagen bij het converteren van het invoer‑fixed‑layout‑document naar de resulterende HTML. |
|
|  | [getPages()](#getPages--) | Staat toe een paginabereik in te stellen om te verwerken. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Staat toe een paginabereik in te stellen om te verwerken. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Staat toe paginering in het resulterende HTML‑document in te schakelen (true) of uit te schakelen (false). |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Staat toe paginering in het resulterende HTML‑document in te schakelen (true) of uit te schakelen (false). |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Haalt de vlag op of stelt deze in die aangeeft of afbeeldingen moeten worden overgeslagen bij het converteren van het invoer‑fixed‑layout‑document naar de resulterende HTML. Standaard is false – afbeeldingen worden behouden.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Haalt de vlag op of stelt deze in die aangeeft of afbeeldingen moeten worden overgeslagen bij het converteren van het invoer‑fixed‑layout‑document naar de resulterende HTML. Standaard is false – afbeeldingen worden behouden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Staat toe een paginabereik in te stellen om te verwerken. Standaard worden alle pagina's van een fixed‑layout‑document verwerkt.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Staat toe een paginabereik in te stellen om te verwerken. Standaard worden alle pagina's van een fixed‑layout‑document verwerkt.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Staat toe paginering in het resulterende HTML‑document in te schakelen (true) of uit te schakelen (false). Standaard is uitgeschakeld (false).

<br />

*** ** * ** ***

Fixed‑layout‑formaatdocumenten (met name PDF en XPS) zijn in wezen strikt paginaged, hun inhoud heeft een vaste lay-out en is verdeeld over pagina's. Maar de resulterende bewerkbare HTML kan worden weergegeven in een paginavrije of paginale weergave.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Staat toe paginering in het resulterende HTML‑document in te schakelen (true) of uit te schakelen (false). Standaard is uitgeschakeld (false).

<br />

*** ** * ** ***

Fixed‑layout‑formaatdocumenten (met name PDF en XPS) zijn in wezen strikt paginaged, hun inhoud heeft een vaste lay-out en is verdeeld over pagina's. Maar de resulterende bewerkbare HTML kan worden weergegeven in een paginavrije of paginale weergave.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

