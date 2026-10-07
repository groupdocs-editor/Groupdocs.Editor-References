---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att specificera och justera anpassade alternativ för redigering av e-bokdokument i alla stödda format ePub, MOBI och AZW3."
type: docs
weight: 12
url: /sv/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Tillåter att ange och justera anpassade alternativ för redigering av e-bokdokument i alla stödda format: ePub, MOBI och AZW3.

<br />

*** ** * ** ***

Stödda e-bokformat:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronisk publikation)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle-format 8t)

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Initierar en ny instans av klassen [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), där alla alternativ är satta till sina standardvärden |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Initierar en ny instans av klassen [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) med angivet pagineringsläge |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Anger om språkinformation exporteras till HTML-markupen i form av 'lang'-HTML-attribut. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Anger om språkinformation exporteras till HTML-markupen i form av 'lang'-HTML-attribut. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Initierar en ny instans av klassen [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), där alla alternativ är satta till sina standardvärden


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Initierar en ny instans av klassen [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) med angivet pagineringsläge


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | enablePagination | boolean | Aktiverar ( true ) eller inaktiverar ( false ) paginering av e-bokens innehåll i det resulterande HTML-dokumentet. Som standard är den inaktiverad ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. Som standard är den inaktiverad (
false
).

<br />

*** ** * ** ***

I sin kärna är de flesta e-bokformat internt ett flödesformat som Office Open XML, där innehållet är en helhet och delas upp i kapitel men inte i sidor. Det innehåller dock viss sid-specifik information som sidnummer, fotnoter, sidhuvuden/sidfötter osv. Vissa e-boksläsare delar upp e-bokens innehåll på sidor, medan andra (särskilt mobila) \\u2014 inte. Detta alternativ låter dig kontrollera hur e-bokens innehåll ska representeras i HTML/CSS under redigering \\u2014 i flytande ( false ) eller paginerad ( true ) vy.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. Som standard är den inaktiverad (
false
).

<br />

*** ** * ** ***

I sin kärna är de flesta e-bokformat internt ett flödesformat som Office Open XML, där innehållet är en helhet och delas upp i kapitel men inte i sidor. Det innehåller dock viss sid-specifik information som sidnummer, fotnoter, sidhuvuden/sidfötter osv. Vissa e-boksläsare delar upp e-bokens innehåll på sidor, medan andra (särskilt mobila) \\u2014 inte. Detta alternativ låter dig kontrollera hur e-bokens innehåll ska representeras i HTML/CSS under redigering \\u2014 i flytande ( false ) eller paginerad ( true ) vy.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Anger om språkinformation exporteras till HTML-markupen i form av 'lang'-HTML-attribut.
Detta alternativ kan vara användbart för rundresa-konvertering av flerspråkiga dokument. Som standard är det inaktiverat (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Anger om språkinformation exporteras till HTML-markupen i form av 'lang'-HTML-attribut.
Detta alternativ kan vara användbart för rundresa-konvertering av flerspråkiga dokument. Som standard är det inaktiverat (
false
).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

