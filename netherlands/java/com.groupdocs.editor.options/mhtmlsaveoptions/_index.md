---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het genereren en opslaan van de MHTML MIME-encapsulatie van samengestelde HTML-documenten"
type: docs
weight: 26
url: /nl/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van de MHTML (MIME‑encapsulatie van samengestelde HTML‑documenten) documenten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | Specificeert of CID (Content-ID) URL's moeten worden gebruikt om bronnen (afbeeldingen, lettertypen, CSS) die in MHTML-documenten zijn opgenomen, te refereren. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | Specificeert of CID (Content-ID) URL's moeten worden gebruikt om bronnen (afbeeldingen, lettertypen, CSS) die in MHTML-documenten zijn opgenomen, te refereren. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Specificeert of ingebouwde en aangepaste documenteigenschappen naar MHTML moeten worden geëxporteerd. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Specificeert of ingebouwde en aangepaste documenteigenschappen naar MHTML moeten worden geëxporteerd. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Specificeert of taalinformatie naar MHTML wordt geëxporteerd. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Specificeert of taalinformatie naar MHTML wordt geëxporteerd. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


Specificeert of CID (Content-ID) URL's moeten worden gebruikt om bronnen (afbeeldingen, lettertypen, CSS) die in MHTML-documenten zijn opgenomen, te refereren. Standaardwaarde is
false
.

<br />

*** ** * ** ***


Standaard worden bronnen in MHTML-documenten gerefereerd aan de hand van bestandsnaam (bijvoorbeeld \"image.png\"), die wordt vergeleken met de \"Content-Location\"-headers van MIME-onderdelen. Deze optie schakelt een alternatieve methode in, waarbij verwijzingen naar bronbestanden worden geschreven als CID (Content-ID) URL's (bijvoorbeeld \"cid:image.png\") en worden vergeleken met de \"Content-ID\"-headers.


In theorie zou er geen verschil moeten zijn tussen de twee referentiemethoden en zou elk van beide prima moeten werken in elke browser of e-mailclient. In de praktijk falen sommige clients echter bij het ophalen van bronnen via bestandsnaam. Als uw browser of e-mailclient weigert bronnen die in een MTHML-document zijn opgenomen te laden (geen afbeeldingen weergeeft of geen CSS‑stijlen laadt), probeer dan het document te exporteren met CID‑URL's.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


Specificeert of CID (Content-ID) URL's moeten worden gebruikt om bronnen (afbeeldingen, lettertypen, CSS) die in MHTML-documenten zijn opgenomen, te refereren. Standaardwaarde is
false
.

<br />

*** ** * ** ***


Standaard worden bronnen in MHTML-documenten gerefereerd aan de hand van bestandsnaam (bijvoorbeeld \"image.png\"), die wordt vergeleken met de \"Content-Location\"-headers van MIME-onderdelen. Deze optie schakelt een alternatieve methode in, waarbij verwijzingen naar bronbestanden worden geschreven als CID (Content-ID) URL's (bijvoorbeeld \"cid:image.png\") en worden vergeleken met de \"Content-ID\"-headers.


In theorie zou er geen verschil moeten zijn tussen de twee referentiemethoden en zou elk van beide prima moeten werken in elke browser of e-mailclient. In de praktijk falen sommige clients echter bij het ophalen van bronnen via bestandsnaam. Als uw browser of e-mailclient weigert bronnen die in een MTHML-document zijn opgenomen te laden (geen afbeeldingen weergeeft of geen CSS‑stijlen laadt), probeer dan het document te exporteren met CID‑URL's.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Specificeert of ingebouwde en aangepaste documenteigenschappen naar MHTML moeten worden geëxporteerd. Standaardwaarde is
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Specificeert of ingebouwde en aangepaste documenteigenschappen naar MHTML moeten worden geëxporteerd. Standaardwaarde is
false
.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Specificeert of taalinformatie naar MHTML wordt geëxporteerd. Standaardwaarde is
false
.

<br />

*** ** * ** ***

Wanneer deze eigenschap is ingesteld op  true , geeft de GroupDocs.Editor het  lang  HTML-attribuut weer op de documentelementen die de taal specificeren. Dit kan nodig zijn om taalkundige semantiek te behouden.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Specificeert of taalinformatie naar MHTML wordt geëxporteerd. Standaardwaarde is
false
.

<br />

*** ** * ** ***

Wanneer deze eigenschap is ingesteld op  true , geeft de GroupDocs.Editor het  lang  HTML-attribuut weer op de documentelementen die de taal specificeren. Dit kan nodig zijn om taalkundige semantiek te behouden.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

