---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara MHTML MIME-inkapslingen av samlade HTML-dokument"
type: docs
weight: 26
url: /sv/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara MHTML (MIME-inkapsling av sammansatta HTML-dokument) dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Anger om CID (Content-ID)-URL:er ska användas för att referera resurser (bilder, typsnitt, CSS) som ingår i MHTML-dokument. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Anger om CID (Content-ID)-URL:er ska användas för att referera resurser (bilder, typsnitt, CSS) som ingår i MHTML-dokument. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Anger om inbyggda och anpassade dokumentegenskaper ska exporteras till MHTML. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Anger om inbyggda och anpassade dokumentegenskaper ska exporteras till MHTML. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Anger om språkinformation ska exporteras till MHTML. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Anger om språkinformation ska exporteras till MHTML. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Anger om CID (Content-ID)-URL:er ska användas för att referera resurser (bilder, typsnitt, CSS) som ingår i MHTML-dokument. Standardvärdet är
false
.

<br />

*** ** * ** ***


Som standard refereras resurser i MHTML-dokument med filnamn (till exempel "image.png"), som matchas mot "Content-Location"-rubriker i MIME-delar. Detta alternativ möjliggör en alternativ metod där referenser till resursfiler skrivs som CID (Content-ID)-URL:er (till exempel "cid:image.png") och matchas mot "Content-ID"-rubriker.


I teorin bör det inte finnas någon skillnad mellan de två referensmetoderna och båda bör fungera bra i vilken webbläsare eller e-postklient som helst. I praktiken misslyckas dock vissa klienter med att hämta resurser via filnamn. Om din webbläsare eller e-postklient vägrar att ladda resurser som ingår i ett MTHML-dokument (visar inte bilder eller laddar inte CSS-stilar), försök exportera dokumentet med CID-URL:er.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Anger om CID (Content-ID)-URL:er ska användas för att referera resurser (bilder, typsnitt, CSS) som ingår i MHTML-dokument. Standardvärdet är
false
.

<br />

*** ** * ** ***


Som standard refereras resurser i MHTML-dokument med filnamn (till exempel "image.png"), som matchas mot "Content-Location"-rubriker i MIME-delar. Detta alternativ möjliggör en alternativ metod där referenser till resursfiler skrivs som CID (Content-ID)-URL:er (till exempel "cid:image.png") och matchas mot "Content-ID"-rubriker.


I teorin bör det inte finnas någon skillnad mellan de två referensmetoderna och båda bör fungera bra i vilken webbläsare eller e-postklient som helst. I praktiken misslyckas dock vissa klienter med att hämta resurser via filnamn. Om din webbläsare eller e-postklient vägrar att ladda resurser som ingår i ett MTHML-dokument (visar inte bilder eller laddar inte CSS-stilar), försök exportera dokumentet med CID-URL:er.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Anger om inbyggda och anpassade dokumentegenskaper ska exporteras till MHTML. Standardvärdet är
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Anger om inbyggda och anpassade dokumentegenskaper ska exporteras till MHTML. Standardvärdet är
false
.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Anger om språkinformation ska exporteras till MHTML. Standardvärdet är
false
.

<br />

*** ** * ** ***

När den här egenskapen är satt till  true , avger GroupDocs.Editor  lang  HTML-attributet på dokumentelementen som specificerar språk. Detta kan behövas för att bevara språkrelaterad semantik.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Anger om språkinformation ska exporteras till MHTML. Standardvärdet är
false
.

<br />

*** ** * ** ***

När den här egenskapen är satt till  true , avger GroupDocs.Editor  lang  HTML-attributet på dokumentelementen som specificerar språk. Detta kan behövas för att bevara språkrelaterad semantik.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

