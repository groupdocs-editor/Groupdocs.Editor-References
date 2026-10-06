---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Metadaten eines Tabellenkalkulationsdokuments dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines Tabellenkalkulationsdokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt ein Format dieses Spreadsheet-Dokuments zurück |
|
|  | [getPageCount()](#getPageCount--) | Gibt die Anzahl der Registerkarten zurück |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses Spreadsheet-Dokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Gibt an, ob dieses spezielle Spreadsheet-Dokument verschlüsselt ist und |
ein Passwort zum Öffnen erfordert
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Erzeugt und gibt eine Vorschau des ausgewählten Arbeitsblatts in Form eines SVG-Bildes zurück |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Bestimmt, ob diese Instanz gleich der angegebenen anderen ist |
SpreadsheetDocumentInfo-Instanz
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Gibt ein Format dieses Spreadsheet-Dokuments zurück


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt die Anzahl der Registerkarten zurück


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes dieses Spreadsheet-Dokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gibt an, ob dieses spezielle Spreadsheet-Dokument verschlüsselt ist und
ein Passwort zum Öffnen erfordert


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Erzeugt und gibt eine Vorschau des ausgewählten Arbeitsblatts in Form eines SVG-Bildes zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | worksheetIndex | int | 0-basierter Index des gewünschten Arbeitsblatts. Darf nicht kleiner als 0 sein und die Anzahl der Arbeitsblätter in dieser Tabelle nicht überschreiten. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Bestimmt, ob diese Instanz gleich der angegebenen anderen ist
SpreadsheetDocumentInfo-Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Andere SpreadsheetDocumentInfo-Instanz, die auf Gleichheit mit dieser geprüft werden sollte |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

