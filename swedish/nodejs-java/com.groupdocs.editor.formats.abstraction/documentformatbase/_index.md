---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar basklassen för dokumentformat som tillhandahåller gemensam funktionalitet för formatinstanser."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Representerar basklassen för dokumentformat, och tillhandahåller gemensam funktionalitet för formatinstanser.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMime()](#getMime--) | Hämtar MIME-typen för dokumentformatet. |
|
|  | [getExtension()](#getExtension--) | Hämtar filändelsen för dokumentformatet. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Hämtar formatfamiljen som dokumentformatet tillhör. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Hämtar en instans av den angivna typen |
T
som har den angivna MIME-typen.
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för det aktuella objektet. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Bestämmer om den här instansen är lika med den angivna [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instansen. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den här instansen är lika med den angivna [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instansen. |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Konverterar en [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instans till en sträng implicit. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Hämtar MIME-typen för dokumentformatet.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Hämtar filändelsen för dokumentformatet.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Hämtar formatfamiljen som dokumentformatet tillhör.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Hämtar en instans av den angivna typen
T
som har den angivna MIME-typen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | MIME-typen för dokumentformatet. |


T
: Typen av dokumentformat.
|

**Returns:**
T - En instans av den angivna typen  T  med den angivna MIME-typen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för det aktuella objektet.


**Returns:**
int - En hashkod för det aktuella objektet, som kombinerar hashkoderna för basobjektet, MIME-typen, filändelsen och formatfamiljen.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Bestämmer om den här instansen är lika med den angivna [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instansen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Den [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) instansen att jämföra med den aktuella instansen. |
|

**Returns:**
boolean -  true  om den angivna [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) är lika med den aktuella instansen; annars,  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om den här instansen är lika med den angivna [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instansen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Den [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instansen att jämföra med den aktuella instansen. |
|

**Returns:**
boolean -  true  om den angivna [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) är lika med den aktuella instansen; annars,  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Konverterar en [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instans till en sträng implicit.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Den [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instansen att konvertera. |
|

**Returns:**
java.lang.String - Filändelsen för [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) instansen.

