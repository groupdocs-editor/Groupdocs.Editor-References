---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar metadata för ett e‑postdokument i vilket som helst stödd e‑postformat."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett e‑postdokument i vilket som helst stödd e‑postformat.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta e-postdokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar alltid 1, eftersom e-postdokument inte har paginerad vy |
|
|  | [getSize()](#getSize--) | Returnerar storlek i byte för detta e-postdokument |
|
|  | [isEncrypted()](#isEncrypted--) | Eftersom e-postdokument inte kan krypteras med lösenord, returnerar denna egenskap alltid 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Bestämmer om denna instans är lika med den andra angivna EmailDocumentInfo-instansen |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Returnerar ett format för detta e-postdokument


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar alltid 1, eftersom e-postdokument inte har paginerad vy


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storlek i byte för detta e-postdokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Eftersom e-postdokument inte kan krypteras med lösenord, returnerar denna egenskap alltid 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Bestämmer om denna instans är lika med den andra angivna EmailDocumentInfo-instansen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Annan EmailDocumentInfo-instans som bör kontrolleras för likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

