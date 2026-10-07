---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één document met een vaste lay-out indeling voor, zoals PDF of XPS"
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Stelt metadata van één document met een vaste lay-out indeling voor, zoals PDF of XPS

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Geeft een formaat van dit fixed-layout‑formaatdocument terug |
|
|  | [getPageCount()](#getPageCount--) | Geeft het aantal pagina's terug |
|
|  | [getSize()](#getSize--) | Geeft de grootte in bytes van dit fixed-layout‑formaatdocument terug |
|
|  | [isEncrypted()](#isEncrypted--) | Bepaalt of dit specifieke fixed-layout‑formaatdocument versleuteld is en een wachtwoord vereist om te openen |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Bepaalt of deze instantie gelijk is aan de andere opgegeven FixedLayoutDocumentInfo‑instantie |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Geeft een formaat van dit fixed-layout‑formaatdocument terug


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Geeft het aantal pagina's terug


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Geeft de grootte in bytes van dit fixed-layout‑formaatdocument terug


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bepaalt of dit specifieke fixed-layout‑formaatdocument versleuteld is en een wachtwoord vereist om te openen


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Bepaalt of deze instantie gelijk is aan de andere opgegeven FixedLayoutDocumentInfo‑instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Andere FixedLayoutDocumentInfo‑instantie, die op gelijkheid met deze moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

