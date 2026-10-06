---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Metadaten eines Markdown‑Dokuments dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines Markdown‑Dokuments dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt ein Format dieses Markdown-Dokuments zurück \\u2014 ist immer |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Gibt die Anzahl der Seiten zurück. |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses Markdown-Dokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Da Markdown-Dokumente nicht mit einem Passwort verschlüsselt werden können, ist dies |
Eigenschaft gibt immer 'false' zurück
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Bestimmt, ob diese Instanz gleich der angegebenen anderen ist |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Gibt ein Format dieses Markdown-Dokuments zurück \\u2014 ist immer
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt die Anzahl der Seiten zurück. Markdown-Dokumente haben normalerweise keine festen Seiten
und damit die Seitenzahl, sodass diese Zahl aus der Standardseitengröße berechnet wird
auf A4 im Hochformat eingestellt.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes dieses Markdown-Dokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Da Markdown-Dokumente nicht mit einem Passwort verschlüsselt werden können, ist dies
Eigenschaft gibt immer 'false' zurück


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Bestimmt, ob diese Instanz gleich der angegebenen anderen ist
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Andere [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo)-Instanz, die auf Gleichheit mit dieser geprüft werden soll |
|

**Returns:**
boolesch - Wahr, wenn gleich, falsch, wenn ungleich

