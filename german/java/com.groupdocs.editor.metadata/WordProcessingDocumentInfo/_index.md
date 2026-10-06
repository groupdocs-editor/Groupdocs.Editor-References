---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Metadaten eines Textverarbeitungsdokuments dar."
type: docs
weight: 17
url: /de/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines Textverarbeitungsdokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt das Format dieses WordProcessing-Dokuments zurück |
|
|  | [getPageCount()](#getPageCount--) | Gibt die Anzahl der Seiten zurück |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses WordProcessing-Dokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Bestimmt, ob dieses bestimmte WordProcessing-Dokument verschlüsselt ist und |
ein Passwort zum Öffnen erfordert
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Erstellt und gibt eine Vorschau der ausgewählten Seite in Form eines SVG-Bildes zurück |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Bestimmt, ob diese Instanz gleich der angegebenen anderen ist |
WordProcessingDocumentInfo-Instanz
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Gibt das Format dieses WordProcessing-Dokuments zurück


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt die Anzahl der Seiten zurück


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes dieses WordProcessing-Dokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bestimmt, ob dieses bestimmte WordProcessing-Dokument verschlüsselt ist und
ein Passwort zum Öffnen erfordert


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Erstellt und gibt eine Vorschau der ausgewählten Seite in Form eines SVG-Bildes zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | pageIndex | int | 0-basierter Index der gewünschten Seite. Darf nicht kleiner als 0 sein und die Anzahl der Seiten in diesem WordProcessing-Dokument nicht überschreiten. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Bestimmt, ob diese Instanz gleich der angegebenen anderen ist
WordProcessingDocumentInfo-Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Andere WordProcessingDocumentInfo-Instanz, die auf Gleichheit mit dieser geprüft werden soll |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

