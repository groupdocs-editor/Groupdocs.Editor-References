---
title: "IHtmlResource"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één instantie van de onbekende HTML-resource raster of vector afbeelding stylesheet lettertype tekstresource CSS XML enz. voor"
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.resources/ihtmlresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public interface IHtmlResource extends IAuxDisposable
```

Stelt één instantie van de onbekende HTML-resource (raster of vector afbeelding,
stylesheet, lettertype, tekstresource (CSS, XML) enz.)

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getName()](#getName--) | Naam van de HTML-resource |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Correcte bestandsnaam van de opgegeven resource met passend bestand |
extensie
|
|  | [getType()](#getType--) | Type van de HTML-resource |
|
|  | [getByteContent()](#getByteContent--) | Inhoud van de HTML-resource in de vorm van een byte‑stroom |
|
|  | [getTextContent()](#getTextContent--) | Inhoud van de HTML-resource in de vorm van een base64‑gecodeerde tekststring |
voor binaire resources of een eenvoudige tekst voor tekstuele resources
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat de huidige resource op in het opgegeven bestand |
|
### getName() {#getName--}
```
public abstract String getName()
```


Naam van de HTML-resource


**Returns:**
java.lang.String -
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public abstract String getFilenameWithExtension()
```


Correcte bestandsnaam van de opgegeven resource met passend bestand
extensie


**Returns:**
java.lang.String -
### getType() {#getType--}
```
public abstract IResourceType getType()
```


Type van de HTML-resource


**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - 
### getByteContent() {#getByteContent--}
```
public abstract InputStream getByteContent()
```


Inhoud van de HTML-resource in de vorm van een byte‑stroom


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Inhoud van de HTML-resource in de vorm van een base64‑gecodeerde tekststring
voor binaire resources of een eenvoudige tekst voor tekstuele resources


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Slaat de huidige resource op in het opgegeven bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat wordt aangemaakt of herschreven met de inhoud van een huidige resource |
|

