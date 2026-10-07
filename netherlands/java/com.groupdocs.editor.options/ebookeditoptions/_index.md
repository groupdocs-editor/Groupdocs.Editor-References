---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties te specificeren en aan te passen voor het bewerken van E-boekdocumenten in alle ondersteunde formaten ePub, MOBI en AZW3."
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Staat toe aangepaste opties op te geven en aan te passen voor het bewerken van E‑book‑documenten in alle ondersteunde formaten: ePub, MOBI en AZW3.

<br />

*** ** * ** ***

Ondersteunde e‑book‑formaten:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronische publicatie)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle‑formaat 8t)

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Initialiseert een nieuw exemplaar van de [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Initialiseert een nieuw exemplaar van de [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) klasse met de opgegeven paginatiemodus |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Staat toe om paginering in het resulterende HTML-document in of uit te schakelen. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in de vorm van 'lang' HTML-attributen. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in de vorm van 'lang' HTML-attributen. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Initialiseert een nieuw exemplaar van de [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) klasse, waarbij alle opties zijn ingesteld op hun standaardwaarden


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Initialiseert een nieuw exemplaar van de [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) klasse met de opgegeven paginatiemodus


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | enablePagination | boolean | Schakelt ( true ) of schakelt ( false ) paginering van de e-boekinhoud in het resulterende HTML-document in. Standaard is uitgeschakeld ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Staat toe paginering in het resulterende HTML-document in of uit te schakelen. Standaard is uitgeschakeld (
false
, ).

<br />

*** ** * ** ***

In zijn essentie is de meeste e-boekformaten intern een doorlopend formaat zoals Office Open XML, waarbij de inhoud een geheel is en wordt verdeeld over hoofdstukken maar niet over pagina's. Het bevat echter enkele paginaspecifieke informatie zoals paginanummers, voetnoten, kop- en voetteksten, enzovoort. Sommige e-boeklezers splitsen de e-boekinhoud op in pagina's, terwijl andere (vooral mobiel) \\u2014 niet. Deze optie maakt het mogelijk te bepalen hoe de e-boekinhoud moet worden weergegeven in HTML/CSS tijdens het bewerken \\u2014 in de zwevende ( false ) of gepagineerde ( true ) weergave.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Staat toe paginering in het resulterende HTML-document in of uit te schakelen. Standaard is uitgeschakeld (
false
, ).

<br />

*** ** * ** ***

In zijn essentie is de meeste e-boekformaten intern een doorlopend formaat zoals Office Open XML, waarbij de inhoud een geheel is en wordt verdeeld over hoofdstukken maar niet over pagina's. Het bevat echter enkele paginaspecifieke informatie zoals paginanummers, voetnoten, kop- en voetteksten, enzovoort. Sommige e-boeklezers splitsen de e-boekinhoud op in pagina's, terwijl andere (vooral mobiel) \\u2014 niet. Deze optie maakt het mogelijk te bepalen hoe de e-boekinhoud moet worden weergegeven in HTML/CSS tijdens het bewerken \\u2014 in de zwevende ( false ) of gepagineerde ( true ) weergave.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in de vorm van 'lang' HTML-attributen.
Deze optie kan nuttig zijn voor roundtrip-conversie van meertalige documenten. Standaard is deze uitgeschakeld (
false
, ).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Specificeert of taalinformatie wordt geëxporteerd naar de HTML-markup in de vorm van 'lang' HTML-attributen.
Deze optie kan nuttig zijn voor roundtrip-conversie van meertalige documenten. Standaard is deze uitgeschakeld (
false
, ).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

