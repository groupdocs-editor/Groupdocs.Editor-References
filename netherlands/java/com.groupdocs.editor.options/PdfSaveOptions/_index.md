---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het genereren en opslaan van PDF Portable Document Format-documenten"
type: docs
weight: 31
url: /nl/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Staat toe om aangepaste opties op te geven voor het genereren en opslaan van PDF (Portable
Document Format) documenten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Wachtwoord, dat wordt toegepast op het gegenereerde PDF‑document als gebruikerswachtwoord, vereist voor openen. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Wachtwoord, dat wordt toegepast op het gegenereerde PDF‑document als gebruikerswachtwoord, vereist voor openen. |
|
|  | [getCompliance()](#getCompliance--) | Specificeert het PDF‑standaarden‑conformiteitsniveau voor uitvoerdocumenten. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Specificeert het PDF‑standaarden‑conformiteitsniveau voor uitvoerdocumenten. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwoordelijk voor het insluiten van lettertype‑bronnen in het resulterende PDF‑document, die worden gebruikt in het oorspronkelijke document. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Verantwoordelijk voor het insluiten van lettertype‑bronnen in het resulterende PDF‑document, die worden gebruikt in het oorspronkelijke document. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Wachtwoord, dat wordt toegepast op het gegenereerde PDF‑document als gebruikerswachtwoord, vereist voor openen.
Als NULL of leeg, wordt er geen wachtwoord op het document toegepast. Anders wordt het document versleuteld met RC4 (sleutellengte van 128 bit).
Standaard is NULL \u2014 wachtwoord wordt niet toegepast.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Wachtwoord, dat wordt toegepast op het gegenereerde PDF‑document als gebruikerswachtwoord, vereist voor openen.
Als NULL of leeg, wordt er geen wachtwoord op het document toegepast. Anders wordt het document versleuteld met RC4 (sleutellengte van 128 bit).
Standaard is NULL \u2014 wachtwoord wordt niet toegepast.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Specificeert het PDF‑standaarden‑conformiteitsniveau voor uitvoerdocumenten. Standaard is PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Specificeert het PDF‑standaarden‑conformiteitsniveau voor uitvoerdocumenten. Standaard is PdfCompliance.Pdf17.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Verantwoordelijk voor het insluiten van lettertype‑bronnen in het resulterende PDF‑document, die worden gebruikt in het oorspronkelijke document. Standaard worden er geen lettertypen ingesloten (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Verantwoordelijk voor het insluiten van lettertype‑bronnen in het resulterende PDF‑document, die worden gebruikt in het oorspronkelijke document. Standaard worden er geen lettertypen ingesloten (NotEmbed).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik.
Het instellen van deze optie op true kan het geheugenverbruik aanzienlijk verminderen bij het genereren van grote documenten, ten koste van een tragere opslagtijd.
Standaard is false (geheugenoptimalisatie is uitgeschakeld ten gunste van betere prestaties).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik.
Het instellen van deze optie op true kan het geheugenverbruik aanzienlijk verminderen bij het genereren van grote documenten, ten koste van een tragere opslagtijd.
Standaard is false (geheugenoptimalisatie is uitgeschakeld ten gunste van betere prestaties).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

