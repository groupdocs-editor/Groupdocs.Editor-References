---
title: "EotFont"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett typsnitt i EOT Embedded OpenType-formatet"
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

Representerar ett teckensnitt i EOT‑formatet (Embedded OpenType).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Skapar ny EotFont-klass från innehåll, representerat som base64-kodad |
sträng, och med angivet namn
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Skapar ny EotFont-klass från innehåll, representerat som byte-ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | EOT-huvudstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt EOT-typsnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är ett giltigt EOT-typsnitt |
|
|  | [getType()](#getType--) | Returnerar FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Skapar ny EotFont-klass från innehåll, representerat som base64-kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på EOT-typsnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tomt eller bara blanksteg. Om det inte är EOT-innehåll kastas ett undantag. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Skapar ny EotFont-klass från innehåll, representerat som byte-ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på EOT-typsnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte stream. Läsning börjar från originalposition. Får inte vara null. Bör vara läsbar och sökbar. Om denna instans avslutas, avslutas även detta stream. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


EOT-huvudstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt EOT-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-ström som sannolikt innehåller en EOT-resurs |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller ett giltigt EOT-typsnitt, annars falskt

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är ett giltigt EOT-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehåll för det sannolikt EOT-typsnittet i form av en base64-kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller ett giltigt EOT-typsnitt, annars falskt

### getType() {#getType--}
```
public FontType getType()
```


Returnerar FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
