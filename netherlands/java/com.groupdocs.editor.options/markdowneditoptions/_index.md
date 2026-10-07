---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het bewerken van documenten in Markdown‑formaat."
type: docs
weight: 21
url: /nl/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Staat toe aangepaste opties op te geven voor het bewerken van documenten in Markdown‑formaat.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Maakt een nieuwe instantie van de MarkdownEditOptions-klasse aan en retourneert deze, |
waar alle opties zijn ingesteld op hun standaardwaarden
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Staat toe te bepalen hoe afbeeldingen worden opgeslagen bij het converteren van een Markdown-document |
naar HTML.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Staat toe te bepalen hoe afbeeldingen worden opgeslagen bij het converteren van een Markdown-document |
naar HTML.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Maakt een nieuwe instantie van de MarkdownEditOptions-klasse aan en retourneert deze,
waar alle opties zijn ingesteld op hun standaardwaarden


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Staat toe te bepalen hoe afbeeldingen worden opgeslagen bij het converteren van een Markdown-document
naar HTML.
Waarde: De callback voor het opslaan van afbeeldingen.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Staat toe te bepalen hoe afbeeldingen worden opgeslagen bij het converteren van een Markdown-document
naar HTML.
Waarde: De callback voor het opslaan van afbeeldingen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

