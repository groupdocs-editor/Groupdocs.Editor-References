---
title: "MetaImageBase"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Abstrakt basklass för WMF- och EMF-bildformat"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

Abstrakt basklass för WMF- och EMF-bildformat

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | Vanlig konstruktor, som förbereder skapandet av en WMF- eller EMF-instans från |
base64‑kodad sträng
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | Vanlig konstruktor, som förbereder skapandet av en WMF- eller EMF-instans från |
byte‑ström
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | Bestämmer om den angivna byte‑strömmen innehåller en giltig WMF‑bild |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | Bestämmer om den angivna strängen innehåller en giltig WMF‑bild, vilket är |
kodad med base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | Bestämmer om den angivna byte‑strömmen innehåller en giltig EMF‑bild |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | Bestämmer om den angivna strängen innehåller en giltig EMF‑bild, vilket är |
kodad med base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | I den implementerande typen bör den spara den aktuella vektor‑meta‑bilden till |
vektor‑SVG‑formatet i den angivna byte‑strömmen
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


Vanlig konstruktor, som förbereder skapandet av en WMF- eller EMF-instans från
base64‑kodad sträng


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Obligatoriskt namn |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64‑sträng. Får inte vara NULL eller tom. |
|
|  | isWmf | boolean | true för WMF, false för EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


Vanlig konstruktor, som förbereder skapandet av en WMF- eller EMF-instans från
byte‑ström


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Obligatoriskt namn |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte‑ström. Måste vara giltig. |
|
|  | isWmf | boolean | true för WMF, false för EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


Bestämmer om den angivna byte‑strömmen innehåller en giltig WMF‑bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Inmatnings‑byte‑ström. Måste vara giltig. |
|

**Returns:**
boolean – Returnerar 'true' om giltig och 'false' om ogiltig

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


Bestämmer om den angivna strängen innehåller en giltig WMF‑bild, vilket är
kodad med base64


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Sträng, som antas innehålla en base64‑kodad WMF‑bild |
|

**Returns:**
boolean – Returnerar 'true' om giltig och 'false' om ogiltig

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


Bestämmer om den angivna byte‑strömmen innehåller en giltig EMF‑bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Inmatnings‑byte‑ström. Måste vara giltig. |
|

**Returns:**
boolean – Returnerar 'true' om giltig och 'false' om ogiltig

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


Bestämmer om den angivna strängen innehåller en giltig EMF‑bild, vilket är
kodad med base64


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Sträng, som antas innehålla en base64‑kodad EMF‑bild |
|

**Returns:**
boolean – Returnerar 'true' om giltig och 'false' om ogiltig

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


I den implementerande typen bör den spara den aktuella vektor‑meta‑bilden till
vektor‑SVG‑formatet i den angivna byte‑strömmen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Byte‑ström, i vilken SVG‑versionen av denna vektor‑meta‑bild kommer att lagras. Den får inte vara NULL och bör stödja skrivning. |
|

