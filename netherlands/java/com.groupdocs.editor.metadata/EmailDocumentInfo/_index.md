---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één e‑mail‑document voor van elk ondersteund e‑mailformaat"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Stelt metadata van één e‑mail‑document voor van elk ondersteund e‑mailformaat

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Geeft een formaat van dit e‑maildocument terug |
|
|  | [getPageCount()](#getPageCount--) | Geeft altijd 1 terug, omdat e‑maildocumenten geen paginavoorstelling hebben |
|
|  | [getSize()](#getSize--) | Geeft de grootte in bytes van dit e‑maildocument terug |
|
|  | [isEncrypted()](#isEncrypted--) | Omdat e-maildocumenten niet met een wachtwoord versleuteld kunnen worden, geeft deze eigenschap altijd 'false' terug |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Bepaalt of deze instantie gelijk is aan de andere opgegeven EmailDocumentInfo instantie |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Geeft een formaat van dit e‑maildocument terug


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Geeft altijd 1 terug, omdat e‑maildocumenten geen paginavoorstelling hebben


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Geeft de grootte in bytes van dit e‑maildocument terug


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Omdat e-maildocumenten niet met een wachtwoord versleuteld kunnen worden, geeft deze eigenschap altijd 'false' terug


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Bepaalt of deze instantie gelijk is aan de andere opgegeven EmailDocumentInfo instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Andere EmailDocumentInfo instantie, die op gelijkheid met deze moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

