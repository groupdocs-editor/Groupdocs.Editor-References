---
title: "EmfImage"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en vektorbild i Enhanced Metafile-format (EMF) med dess metadata och ytterligare metoder"
type: docs
weight: 10
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Representerar en vektorbild i Enhanced Metafile-format (EMF) med dess
metadata och ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | Skapar en ny EmfImage-instans från innehåll, representerat som base64-kodat |
sträng, och med angivet namn
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | Skapar en ny EmfImage-instans från innehåll, representerat som byte-ström, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Kontrollerar om den angivna strömmen är en giltig EMF-bild |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Kontrollerar om den angivna base64-kodade strängen är en giltig EMF-bild |
|
|  | [getType()](#getType--) | Returns ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | Returnerar innehållet i denna EMF-bild som en binär ström |
|
|  | [getTextContent()](#getTextContent--) | Returnerar innehållet i denna EMF-bild som vanlig text |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar denna EMF-bild till filen |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Sparar denna vektor-EMF-bild som raster-PNG-bild |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Sparar denna vektor-EMF-bild som vektor-SVG-bild |
|
|  | [dispose()](#dispose--) | Avslutar denna EMF-bild genom att frigöra dess innehåll och göra de flesta av dess |
metoder och egenskaper icke-fungerande
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


Skapar en ny EmfImage-instans från innehåll, representerat som base64-kodat
sträng, och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på EMF-bilden. Får inte vara null, tom eller bara whitespace. |
|
|  | contentInBase64 | java.lang.String | Innehåll som base64-kodad sträng. Får inte vara null, tom eller bara whitespace. Om det inte är EMF-innehåll kommer ett undantag att kastas. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


Skapar en ny EmfImage-instans från innehåll, representerat som byte-ström,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namn på EMF-bilden. Får inte vara null, tom eller bara whitespace. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Kontrollerar om den angivna strömmen är en giltig EMF-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Inmatnings-byte-ström. Får inte vara NULL, bör stödja läsning och sökning. |
|

**Returns:**
boolean - True om den angivna strömmen innehåller en giltig EMF-bild, annars false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Kontrollerar om den angivna base64-kodade strängen är en giltig EMF-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Indatasträng, där innehållet i EMF-bilden lagras i base64-kodning. Får inte vara NULL eller tom. |
|

**Returns:**
boolean - Sant om den angivna strängen innehåller en giltig EMF-bild, falskt annars

### getType() {#getType--}
```
public ImageType getType()
```


Returns ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returnerar innehållet i denna EMF-bild som en binär ström


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Returnerar innehållet i denna EMF-bild som vanlig text


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Sparar denna EMF-bild till filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen, som kommer att skapas (om den inte finns) eller skrivas över (om den finns) med innehållet i denna EMF-bild |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Sparar denna vektor-EMF-bild som raster-PNG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Utdatastream, där innehållet i PNG-bilden kommer att skrivas. Får inte vara NULL och bör vara skrivbar. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Sparar denna vektor-EMF-bild som vektor-SVG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Utdatastream, där innehållet i SVG-bilden kommer att skrivas. Får inte vara NULL och bör vara skrivbar. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Avslutar denna EMF-bild genom att frigöra dess innehåll och göra de flesta av dess
metoder och egenskaper icke-fungerande


