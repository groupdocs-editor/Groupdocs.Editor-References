---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één Markdown‑document voor"
type: docs
weight: 13
url: /nl/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Stelt metadata van één Markdown‑document voor

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Retourneert een formaat van dit Markdown-document \u2014 is altijd |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Retourneert aantal pagina's. |
|
|  | [getSize()](#getSize--) | Retourneert de grootte in bytes van dit Markdown-document |
|
|  | [isEncrypted()](#isEncrypted--) | Omdat Markdown-documenten niet met een wachtwoord versleuteld kunnen worden, dit |
eigenschap retourneert altijd 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Bepaalt of deze instantie gelijk is aan de opgegeven andere |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Retourneert een formaat van dit Markdown-document \u2014 is altijd
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Retourneert aantal pagina's. Markdown-documenten hebben meestal geen vaste pagina's
en dus de paginatelling, dus dit getal wordt berekend op basis van de standaard paginagrootte
ingesteld op A4 in staande oriëntatie.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Retourneert de grootte in bytes van dit Markdown-document


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Omdat Markdown-documenten niet met een wachtwoord versleuteld kunnen worden, dit
eigenschap retourneert altijd 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven andere
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Andere [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instantie, die op gelijkheid met deze moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

