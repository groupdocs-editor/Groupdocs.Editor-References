---
title: "EotFont"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett teckensnitt i EOT Embedded OpenType-formatet"
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
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
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | Skapar en ny EotFont‑klass från innehåll, representerat som base64‑kodad |
sträng, och med angivet namn
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | Skapar en ny EotFont‑klass från innehåll, representerat som byte‑ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | EOT‑huvudstorlek (i byte), som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är ett giltigt EOT‑font |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64‑kodade strängen är ett giltigt EOT‑font |
|
|  | [getType()](#getType--) | Returnerar FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


Skapar en ny EotFont‑klass från innehåll, representerat som base64‑kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på EOT‑fonten. Får inte vara null, tom eller bestå av enbart blanksteg. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tom eller bestå av enbart blanksteg. Om det inte är ett EOT‑innehåll kommer ett undantag att kastas. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


Skapar en ny EotFont‑klass från innehåll, representerat som byte‑ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på EOT‑fonten. Får inte vara null, tom eller bestå av enbart blanksteg. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


EOT‑huvudstorlek (i byte), som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är ett giltigt EOT‑font


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑ström som förmodligen innehåller en EOT‑resurs |
|

**Returns:**
boolean – True om den angivna strömmen innehåller ett giltigt EOT‑font, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64‑kodade strängen är ett giltigt EOT‑font


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet av det förmodade EOT‑fonten i form av en base64‑kodad sträng |
|

**Returns:**
boolean – True om den angivna strängen innehåller ett giltigt EOT‑font, annars false

### getType() {#getType--}
```
public FontType getType()
```


Returnerar FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
