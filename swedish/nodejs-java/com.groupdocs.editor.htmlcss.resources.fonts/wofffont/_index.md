---
title: "WoffFont"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett typsnitt i WOFF Web Open Font Format-formatet"
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

Representerar ett teckensnitt i WOFF‑formatet (Web Open Font Format).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Skapar en ny WoffFont-klass från innehåll, representerat som base64-kodat |
sträng, och med angivet namn
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Skapar en ny WoffFont-klass från innehåll, representerat som byte-ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF-huvudstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt WOFF-typsnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är ett giltigt WOFF-typsnitt |
|
|  | [getType()](#getType--) | Returnerar FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Skapar en ny WoffFont-klass från innehåll, representerat som base64-kodat
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på WOFF-typsnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tomt eller bara blanksteg. Om det inte är WOFF-innehåll kastas ett undantag. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Skapar en ny WoffFont-klass från innehåll, representerat som byte-ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på WOFF-typsnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om detta objekt kommer att disponeras, kommer även denna ström att disponeras. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF-huvudstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt WOFF-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-ström som antagligen innehåller en WOFF-resurs |
|

**Returns:**
boolean - Sant om den angivna strömmen innehåller ett giltigt WOFF-typsnitt, falskt annars

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är ett giltigt WOFF-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehåll för det antagna WOFF-typsnittet i form av en base64-kodad sträng |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller ett giltigt WOFF-typsnitt, falskt annars

### getType() {#getType--}
```
public FontType getType()
```


Returnerar FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
