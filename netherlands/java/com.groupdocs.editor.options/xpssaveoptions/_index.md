---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van XPS XML Paper Specifications-documenten"
type: docs
weight: 54
url: /nl/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Staat toe om aangepaste opties op te geven voor het genereren en opslaan van XPS (XML Paper Specifications) documenten

<br />

*** ** * ** ***

Een XPS-bestand vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Het is ontwikkeld als vervanging van het EMF-bestandsformaat en is vergelijkbaar met het PDF-bestandsformaat, maar gebruikt XML voor de lay-out, weergave en afdrukinformatie van een document.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Verantwoordelijk voor het insluiten van lettertypebronnen in het resulterende XPS-document, die worden gebruikt in het oorspronkelijke document. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Verantwoordelijk voor het insluiten van lettertypebronnen in het resulterende XPS-document, die worden gebruikt in het oorspronkelijke document.
Standaard worden er geen lettertypen ingesloten (NotEmbed).


**Returns:**
byte
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

