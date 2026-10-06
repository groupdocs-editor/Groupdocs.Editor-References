---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Metadaten eines E‑Book‑Dokuments dar"
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines E‑Book‑Dokuments dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt ein Format dieses Dokuments zurück |
|
|  | [getPageCount()](#getPageCount--) | Gibt die Anzahl der Seiten im Fall von MOBI oder AZW3 oder die Anzahl der Kapitel im Fall von ePub zurück. |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses eBook-Dokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Da eBook-Dokumente nicht mit einem Passwort verschlüsselt werden können, gibt diese Eigenschaft immer 'false' zurück |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Bestimmt, ob diese Instanz gleich der anderen angegebenen EbookDocumentInfo-Instanz ist |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Gibt ein Format dieses Dokuments zurück


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt die Anzahl der Seiten im Fall von MOBI oder AZW3 oder die Anzahl der Kapitel im Fall von ePub zurück.

<br />

*** ** * ** ***

eBook-Dokumente haben normalerweise keine festen Seiten und damit keine Seitenzahl. Im Fall von ePub ist es möglich, die Anzahl der Kapitel zu berechnen. Die Formate MOBI und AZW3 haben jedoch ebenfalls keine Kapitel, sodass diese Zahl aus der Standardseitengröße A4 im Hochformat berechnet wird.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes dieses eBook-Dokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Da eBook-Dokumente nicht mit einem Passwort verschlüsselt werden können, gibt diese Eigenschaft immer 'false' zurück


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Bestimmt, ob diese Instanz gleich der anderen angegebenen EbookDocumentInfo-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Andere EbookDocumentInfo-Instanz, die auf Gleichheit mit dieser geprüft werden soll |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

