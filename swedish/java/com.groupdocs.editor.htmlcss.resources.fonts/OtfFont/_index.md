---
title: "OtfFont"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett teckensnitt i OTF Open Type Format-formatet"
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
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
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | Skapar en ny OtfFont-klass från innehåll, representerat som base64-kodat |
sträng, och med angivet namn
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | Skapar en ny OtfFont-klass från innehåll, representerat som byte‑ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | OTF‑huvudstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt OTF‑teckensnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64‑kodade strängen är ett giltigt OTF‑teckensnitt |
|
|  | [getType()](#getType--) | Returnerar |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


Skapar en ny OtfFont-klass från innehåll, representerat som base64-kodat
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på OTF‑teckensnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tomt eller bara blanksteg. Om det inte är OTF‑innehåll kastas ett undantag. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


Skapar en ny OtfFont-klass från innehåll, representerat som byte‑ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på OTF‑teckensnittet. Får inte vara null, tomt eller bara blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


OTF‑huvudstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt OTF‑teckensnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑ström som sannolikt innehåller en OTF‑resurs |
|

**Returns:**
boolean - True om den angivna strömmen innehåller ett giltigt OTF‑teckensnitt, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64‑kodade strängen är ett giltigt OTF‑teckensnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehåll för det sannolikt OTF‑teckensnittet i form av en base64‑kodad sträng |
|

**Returns:**
boolean - True om den angivna strängen innehåller ett giltigt OTF‑teckensnitt, annars false

### getType() {#getType--}
```
public FontType getType()
```


Returnerar
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
