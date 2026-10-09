---
title: "OtfFont"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett typsnitt i OTF Open Type Format-formatet"
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

Representerar ett teckensnitt i OTF‑formatet (Open Type Format).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Skapar ny OtfFont-klass från innehåll, representerat som base64-kodad |
sträng, och med angivet namn
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Skapar ny OtfFont-klass från innehåll, representerat som byte-ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | OTF-huvudstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt OTF-typsnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är ett giltigt OTF-typsnitt |
|
|  | [getType()](#getType--) | Returnerar |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Skapar ny OtfFont-klass från innehåll, representerat som base64-kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på OTF-typsnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tomt eller bara blanksteg. Om det inte är OTF-innehåll kastas ett undantag. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Skapar ny OtfFont-klass från innehåll, representerat som byte-ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på OTF-typsnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte stream. Läsning börjar från originalposition. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även detta stream. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


OTF-huvudstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt OTF-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-ström som sannolikt innehåller en OTF-resurs |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller ett giltigt OTF-typsnitt, falskt annars

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är ett giltigt OTF-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehåll för det antagna OTF-typsnittet i form av en base64-kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller ett giltigt OTF-typsnitt, falskt annars

### getType() {#getType--}
```
public FontType getType()
```


Returnerar
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
