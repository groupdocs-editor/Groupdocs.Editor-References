---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt Metadaten eines Dokuments mit festem Layoutformat wie PDF oder XPS dar"
type: docs
weight: 12
url: /de/nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Stellt Metadaten eines Dokuments mit festem Layoutformat wie PDF oder XPS dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt das Format dieses Fixed-Layout-Dokuments zurück |
|
|  | [getPageCount()](#getPageCount--) | Gibt die Anzahl der Seiten zurück |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses Fixed-Layout-Dokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Bestimmt, ob dieses spezifische Fixed-Layout-Dokument verschlüsselt ist und ein Passwort zum Öffnen benötigt |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Bestimmt, ob diese Instanz gleich der anderen angegebenen FixedLayoutDocumentInfo-Instanz ist |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Gibt das Format dieses Fixed-Layout-Dokuments zurück


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Gibt die Größe in Bytes dieses Fixed-Layout-Dokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bestimmt, ob dieses spezifische Fixed-Layout-Dokument verschlüsselt ist und ein Passwort zum Öffnen benötigt


**Returns:**
boolesch
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Bestimmt, ob diese Instanz gleich der anderen angegebenen FixedLayoutDocumentInfo-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Andere FixedLayoutDocumentInfo-Instanz, die auf Gleichheit mit dieser geprüft werden sollte |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

