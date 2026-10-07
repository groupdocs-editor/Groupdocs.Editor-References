---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van Markdown‑documenten."
type: docs
weight: 24
url: /nl/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van Markdown‑documenten.

<br />

*** ** * ** ***

De MarkdownSaveOptions‑klasse moet door de gebruiker worden toegepast wanneer er een instantie van de EditableDocument‑klasse bestaat, die bewerkte documentinhoud bevat, en het vereist is om deze inhoud op te slaan in een nieuw document in Markdown‑formaat.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow specificeert hoe inhoud in tabellen moet worden uitgelijnd bij het exporteren naar het Markdown‑formaat. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow specificeert hoe inhoud in tabellen moet worden uitgelijnd bij het exporteren naar het Markdown‑formaat. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Specificeert de fysieke map waar afbeeldingen worden opgeslagen bij het exporteren van een document naar |
het Markdown‑formaat.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Specificeert de fysieke map waar afbeeldingen worden opgeslagen bij het exporteren van een document naar |
het Markdown‑formaat.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Specificeert of afbeeldingen worden opgeslagen in Base64‑formaat naar het uitvoerbestand. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Specificeert of afbeeldingen worden opgeslagen in Base64‑formaat naar het uitvoerbestand. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik.
Instellen van deze optie op
true
kan het geheugenverbruik aanzienlijk verminderen tijdens het genereren van grote documenten, ten koste van een tragere opslagtijd.
Standaard is
false
(geheugenoptimalisatie is uitgeschakeld ten behoeve van betere prestaties).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Schakelt geheugenoptimalisatiemechanismen in tijdens het genereren van documenten vanuit HTML, wat de prestaties vermindert als prijs voor het verminderen van het geheugenverbruik.
Instellen van deze optie op
true
kan het geheugenverbruik aanzienlijk verminderen tijdens het genereren van grote documenten, ten koste van een tragere opslagtijd.
Standaard is
false
(geheugenoptimalisatie is uitgeschakeld ten behoeve van betere prestaties).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow specificeert hoe inhoud in tabellen moet worden uitgelijnd bij het exporteren naar het Markdown‑formaat.
De standaardwaarde is [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Waarde: De uitlijning van de tabelinhoud


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow specificeert hoe inhoud in tabellen moet worden uitgelijnd bij het exporteren naar het Markdown‑formaat.
De standaardwaarde is [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Waarde: De uitlijning van de tabelinhoud


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Specificeert de fysieke map waar afbeeldingen worden opgeslagen bij het exporteren van een document naar
het Markdown‑formaat. Standaard is null.

<br />

*** ** * ** ***

Als noch de ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) noch ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) door de gebruiker zijn gespecificeerd, zal de GroupDocs.Editor proberen de ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) zelf te bepalen en deze bij succes toepassen.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Specificeert de fysieke map waar afbeeldingen worden opgeslagen bij het exporteren van een document naar
het Markdown‑formaat. Standaard is null.

<br />

*** ** * ** ***

Als noch de ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) noch ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) door de gebruiker zijn gespecificeerd, zal de GroupDocs.Editor proberen de ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) zelf te bepalen en deze bij succes toepassen.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Geeft aan of afbeeldingen in Base64-indeling naar het uitvoerbestand worden opgeslagen. Standaard is
false
.

<br />

*** ** * ** ***

Wanneer deze eigenschap is ingesteld op true, worden afbeeldingsgegevens direct geëxporteerd naar de afbeeldingselementen ![](../) en worden er geen afzonderlijke bestanden aangemaakt. Deze eigenschap, indien ingesteld op true, heeft een hogere prioriteit dan de MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) eigenschap.

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Geeft aan of afbeeldingen in Base64-indeling naar het uitvoerbestand worden opgeslagen. Standaard is
false
.

<br />

*** ** * ** ***

Wanneer deze eigenschap is ingesteld op true, worden afbeeldingsgegevens direct geëxporteerd naar de afbeeldingselementen ![](../) en worden er geen afzonderlijke bestanden aangemaakt. Deze eigenschap, indien ingesteld op true, heeft een hogere prioriteit dan de MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) eigenschap.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

