---
title: "TtfFont"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett typsnitt i TTF TrueType Font-formatet"
type: docs
weight: 15
url: /sv/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

Representerar ett teckensnitt i TTF‑formatet (TrueType Font).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | Skapar en ny TtfFont-klass från innehåll, representerat som base64-kodat |
sträng, och med angivet namn
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | Skapar en ny TtfFont-klass från innehåll, representerat som byte-ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTF-headerstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt TTF-typsnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är ett giltigt TTF-typsnitt |
|
|  | [getType()](#getType--) | Returnerar FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


Skapar en ny TtfFont-klass från innehåll, representerat som base64-kodat
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på TTF‑teckensnittet. Får inte vara null, tomt eller bestå av mellanslag. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tomt eller bestå av mellanslag. Om det inte är TTF‑innehåll kommer ett undantag att kastas. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


Skapar en ny TtfFont-klass från innehåll, representerat som byte-ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på TTF‑teckensnittet. Får inte vara null, tomt eller bestå av mellanslag. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTF-headerstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt TTF-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑ström som sannolikt innehåller en TTF‑resurs |
|

**Returns:**
boolesk – True om den angivna strömmen innehåller ett giltigt TTF‑teckensnitt, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är ett giltigt TTF-typsnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet av det sannolikt TTF‑teckensnittet i form av en base64‑kodad sträng |
|

**Returns:**
boolesk – True om den angivna strängen innehåller ett giltigt TTF‑teckensnitt, annars false

### getType() {#getType--}
```
public FontType getType()
```


Returnerar FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
