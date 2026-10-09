---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar metadata för ett dokument med fast layoutformat som PDF eller XPS."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Representerar metadata för ett dokument med fast layoutformat som PDF eller XPS.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta fastlayout-dokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar antal sidor |
|
|  | [getSize()](#getSize--) | Returnerar storlek i byte för detta fastlayout-dokument |
|
|  | [isEncrypted()](#isEncrypted--) | Bestämmer om detta specifika fastlayout-dokument är krypterat och kräver lösenord för att öppnas |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Bestämmer om denna instans är lika med den andra angivna FixedLayoutDocumentInfo-instansen |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Returnerar ett format för detta fastlayout-dokument


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antal sidor


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storlek i byte för detta fastlayout-dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bestämmer om detta specifika fastlayout-dokument är krypterat och kräver lösenord för att öppnas


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Bestämmer om denna instans är lika med den andra angivna FixedLayoutDocumentInfo-instansen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Annan FixedLayoutDocumentInfo-instans som bör kontrolleras för likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

