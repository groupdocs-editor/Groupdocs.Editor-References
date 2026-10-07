---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara Markdown-dokument."
type: docs
weight: 24
url: /sv/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Tillåter att ange anpassade alternativ för att generera och spara Markdown-dokument.

<br />

*** ** * ** ***

MarkdownSaveOptions-klassen måste tillämpas av användaren när det finns en instans av EditableDocument-klassen som innehåller redigerat dokumentinnehåll, och det krävs att detta innehåll sparas till det nya dokumentet i Markdown-format.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow specificerar hur innehåll i tabeller ska justeras vid export till Markdown-formatet. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow specificerar hur innehåll i tabeller ska justeras vid export till Markdown-formatet. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Anger den fysiska mappen där bilder sparas när ett dokument exporteras till |
Markdown-formatet.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Anger den fysiska mappen där bilder sparas när ett dokument exporteras till |
Markdown-formatet.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Anger om bilder sparas i Base64-format till utdatafilen. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Anger om bilder sparas i Base64-format till utdatafilen. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning.
Att ställa in detta alternativ till
true
kan avsevärt minska minnesförbrukningen vid generering av stora dokument på bekostnad av långsammare sparningstid.
Standard är
false
(minnesoptimering är inaktiverad för bättre prestanda).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Aktiverar minnesoptimeringsmekanismer under dokumentgenerering från HTML, vilket försämrar prestandan som en kostnad för minskat minnesanvändning.
Att ställa in detta alternativ till
true
kan avsevärt minska minnesförbrukningen vid generering av stora dokument på bekostnad av långsammare sparningstid.
Standard är
false
(minnesoptimering är inaktiverad för bättre prestanda).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow specificerar hur innehåll i tabeller ska justeras vid export till Markdown-formatet.
Standardvärdet är [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Värde: Tabellens innehållsjustering


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow specificerar hur innehåll i tabeller ska justeras vid export till Markdown-formatet.
Standardvärdet är [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Värde: Tabellens innehållsjustering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Anger den fysiska mappen där bilder sparas när ett dokument exporteras till
Markdown-formatet. Standard är null.

<br />

*** ** * ** ***

Om varken ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) eller ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) anges av användaren, kommer GroupDocs.Editor att försöka bestämma ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) själv och tillämpa det vid framgång.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Anger den fysiska mappen där bilder sparas när ett dokument exporteras till
Markdown-formatet. Standard är null.

<br />

*** ** * ** ***

Om varken ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) eller ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) anges av användaren, kommer GroupDocs.Editor att försöka bestämma ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) själv och tillämpa det vid framgång.

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Anger om bilder sparas i Base64-format till utdatafilen. Standard är
false
.

<br />

*** ** * ** ***

När denna egenskap är satt till true exporteras bilddata direkt till bildelementen ![](../) och separata filer skapas inte. Denna egenskap, om den är satt till true, har högre prioritet än egenskapen MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Anger om bilder sparas i Base64-format till utdatafilen. Standard är
false
.

<br />

*** ** * ** ***

När denna egenskap är satt till true exporteras bilddata direkt till bildelementen ![](../) och separata filer skapas inte. Denna egenskap, om den är satt till true, har högre prioritet än egenskapen MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

