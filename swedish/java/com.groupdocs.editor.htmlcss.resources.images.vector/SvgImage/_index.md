---
title: "SvgImage"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en vektorbild i SVG Scalable Vector Graphics-format med dess metadata och ytterligare metoder"
type: docs
weight: 12
url: /sv/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Representerar en vektorbild i SVG (Scalable Vector Graphics)-format med dess
metadata och ytterligare metoder

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Skapar en ny SvgImage-instans från innehåll, representerat som vanlig sträng, |
och med angivet namn
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Skapar en ny SvgImage-instans från innehåll, representerat som byte-ström, |
och med angivet namn
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Utför en ytlig kontroll om angivet textbaserat XML-kompatibelt innehåll |
representerar en SVG-bild
|
|  | [getType()](#getType--) | Returnerar ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Returnerar innehållet i denna SVG-bild som en binär ström |
|
|  | [getTextContent()](#getTextContent--) | Returnerar innehållet i denna SVG-bild som vanlig text (i XML-format) |
|
|  | [getXmlContent()](#getXmlContent--) | Returnerar innehållet i denna SVG-bild i dess ursprungliga XML-kompatibla format |
textuell form
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Sparar denna SVG-bild till filen |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Sparar denna vektor‑SVG-bild till en raster‑PNG-bild |
|
|  | [dispose()](#dispose--) | Avslutar denna rasterbild, frigör dess innehåll och gör de flesta metoder otillgängliga. |
och egenskaper fungerar inte
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Skapar en ny SvgImage-instans från innehåll, representerat som vanlig sträng,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på SVG-bilden. Får inte vara null, tom eller bestå av bara mellanslag. |
|
|  | innehåll | java.lang.String | Innehåll som en vanlig sträng, som innehåller ett giltigt XML‑kompatibelt innehåll för SVG-bilden. Får inte vara null, tom eller bestå av bara mellanslag. Om det inte är SVG‑innehåll kommer ett undantag att kastas. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Skapar en ny SvgImage-instans från innehåll, representerat som byte-ström,
och med angivet namn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | namn | java.lang.String | Namnet på SVG-bilden. Får inte vara null, tom eller bestå av bara mellanslag. |
|
|  | binaryContent | java.io.InputStream | Innehåll som byte-ström. Läsning börjar från ursprunglig position. Får inte vara null. Ska vara läsbar och sökbar. Om detta objekt frigörs, frigörs även denna ström. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Utför en ytlig kontroll om angivet textbaserat XML-kompatibelt innehåll
representerar en SVG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | innehåll | java.lang.String | XML‑innehåll för en SVG-bild som enkel text, inte som base64‑kodad data |
|

**Returns:**
boolesk – True om den angivna strängen kan betraktas som giltig SVG vid första anblicken, false om den säkert inte är SVG

### getType() {#getType--}
```
public ImageType getType()
```


Returnerar ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Returnerar innehållet i denna SVG-bild som en binär ström


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Returnerar innehållet i denna SVG-bild som vanlig text (i XML-format)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Returnerar innehållet i denna SVG-bild i dess ursprungliga XML-kompatibla format
textuell form


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Sparar denna SVG-bild till filen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Fullständig sökväg till filen, som kommer att skapas (om den inte finns) eller skrivas över (om den finns) med innehållet i denna SVG-bild |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Sparar denna vektor‑SVG-bild till en raster‑PNG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Utdatastream, där innehållet i PNG-bilden kommer att skrivas. Får inte vara NULL och bör vara skrivbar. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Avslutar denna rasterbild, frigör dess innehåll och gör de flesta metoder otillgängliga.
och egenskaper fungerar inte


