---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar metadata för ett EBook-dokument"
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett EBook-dokument

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta dokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar antalet sidor för MOBI eller AZW3 eller antalet kapitel för ePub. |
|
|  | [getSize()](#getSize--) | Returnerar storleken i byte för detta eBook-dokument |
|
|  | [isEncrypted()](#isEncrypted--) | Eftersom eBook-dokument inte kan krypteras med lösenord returnerar den här egenskapen alltid 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Bestämmer om den här instansen är lika med den andra angivna EbookDocumentInfo-instansen |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Returnerar ett format för detta dokument


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antalet sidor för MOBI eller AZW3 eller antalet kapitel för ePub.

<br />

*** ** * ** ***

eBook-dokument har vanligtvis inga fasta sidor och därmed ingen sidräkning. För ePub är det möjligt att beräkna ett antal kapitel. Däremot har MOBI- och AZW3-formaten inga kapitel heller, så detta tal beräknas från standard sidstorlek inställd på A4 i stående orientering.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storleken i byte för detta eBook-dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Eftersom eBook-dokument inte kan krypteras med lösenord returnerar den här egenskapen alltid 'false'


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Bestämmer om den här instansen är lika med den andra angivna EbookDocumentInfo-instansen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Annan EbookDocumentInfo-instans som ska kontrolleras för likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

