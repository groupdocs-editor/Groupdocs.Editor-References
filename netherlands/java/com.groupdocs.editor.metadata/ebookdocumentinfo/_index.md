---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één E‑book‑document voor"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Stelt metadata van één E‑book‑document voor

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Retourneert een formaat van dit document |
|
|  | [getPageCount()](#getPageCount--) | Retourneert het aantal pagina's in het geval van MOBI of AZW3 of het aantal hoofdstukken in het geval van ePub. |
|
|  | [getSize()](#getSize--) | Retourneert de grootte in bytes van dit eBook-document |
|
|  | [isEncrypted()](#isEncrypted--) | Omdat eBook-documenten niet met een wachtwoord versleuteld kunnen worden, geeft deze eigenschap altijd 'false' terug |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Bepaalt of deze instantie gelijk is aan de andere opgegeven EbookDocumentInfo‑instantie |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Retourneert een formaat van dit document


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Retourneert het aantal pagina's in het geval van MOBI of AZW3 of het aantal hoofdstukken in het geval van ePub.

<br />

*** ** * ** ***

eBook-documenten hebben meestal geen vaste pagina's en dus geen paginatelling. In het geval van ePub is het mogelijk om een aantal hoofdstukken te berekenen. Echter, de MOBI- en AZW3-formaten hebben ook geen hoofdstukken, dus dit aantal wordt berekend op basis van de standaard paginagrootte ingesteld op A4 in staande oriëntatie.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Retourneert de grootte in bytes van dit eBook-document


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Omdat eBook-documenten niet met een wachtwoord versleuteld kunnen worden, geeft deze eigenschap altijd 'false' terug


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Bepaalt of deze instantie gelijk is aan de andere opgegeven EbookDocumentInfo‑instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Andere EbookDocumentInfo‑instantie, die op gelijkheid met deze moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

