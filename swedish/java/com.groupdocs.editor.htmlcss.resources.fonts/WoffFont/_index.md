---
title: "WoffFont"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar ett teckensnitt i WOFF Web Open Font Format-formatet"
type: docs
weight: 17
url: /sv/java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
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
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | Skapar en ny WoffFont‑klass från innehåll, representerat som base64‑kodad |
sträng, och med angivet namn
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | Skapar en ny WoffFont‑klass från innehåll, representerat som byte‑ström, och |
med angivet namn
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | WOFF‑huvudstorlek (i byte) som krävs för dess validering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om angiven ström är ett giltigt WOFF‑teckensnitt |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om angiven base64‑kodad sträng är ett giltigt WOFF‑teckensnitt |
|
|  | [getType()](#getType--) | Returnerar FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


Skapar en ny WoffFont‑klass från innehåll, representerat som base64‑kodad
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på WOFF‑teckensnittet. Får inte vara null, tomt eller bestå av mellanslag. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑kodad sträng. Får inte vara null, tomt eller bestå av mellanslag. Om det inte är WOFF‑innehåll kommer ett undantag att kastas. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


Skapar en ny WoffFont‑klass från innehåll, representerat som byte‑ström, och
med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på WOFF‑teckensnittet. Får inte vara null, tomt eller bestå av mellanslag. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Bör vara läsbar och sökbar. Om detta objekt kommer att tas bort, kommer även denna ström att tas bort. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


WOFF‑huvudstorlek (i byte) som krävs för dess validering


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om angiven ström är ett giltigt WOFF‑teckensnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑ström som sannolikt innehåller en WOFF‑resurs |
|

**Returns:**
boolesk – True om den angivna strömmen innehåller ett giltigt WOFF‑teckensnitt, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om angiven base64‑kodad sträng är ett giltigt WOFF‑teckensnitt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Innehållet av det sannolikt WOFF‑teckensnittet i form av en base64‑kodad sträng |
|

**Returns:**
boolesk – True om den angivna strängen innehåller ett giltigt WOFF‑teckensnitt, annars false

### getType() {#getType--}
```
public FontType getType()
```


Returnerar FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
