---
title: "SvgImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één vectorafbeelding in SVG Scalable Vector Graphics‑formaat voor met zijn metadata en extra methoden"
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

Stelt één vectorafbeelding in SVG (Scalable Vector Graphics)-formaat voor met zijn
metadata en extra methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | Maakt een nieuw SvgImage‑object aan vanuit inhoud, weergegeven als gewone tekenreeks, |
en met opgegeven naam
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw SvgImage‑object aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Voert een oppervlaktetest uit om te bepalen of de opgegeven tekstuele XML‑conforme inhoud |
vertegenwoordigt een SVG-afbeelding
|
|  | [getType()](#getType--) | Retourneert ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | Retourneert de inhoud van deze SVG-afbeelding als een binaire stream |
|
|  | [getTextContent()](#getTextContent--) | Retourneert de inhoud van deze SVG-afbeelding als platte tekst (in XML-indeling) |
|
|  | [getXmlContent()](#getXmlContent--) | Retourneert de inhoud van deze SVG-afbeelding in zijn oorspronkelijke XML-conforme formaat |
tekstuele vorm
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Slaat deze SVG-afbeelding op in het bestand |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Slaat deze vector‑SVG-afbeelding op als raster‑PNG-afbeelding |
|
|  | [dispose()](#dispose--) | Verwijdert deze rasterafbeelding, waarbij de inhoud wordt verwijderd en de meeste methoden |
en eigenschappen niet-werkend
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


Maakt een nieuw SvgImage‑object aan vanuit inhoud, weergegeven als gewone tekenreeks,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de SVG-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | inhoud | java.lang.String | Inhoud als een gewone tekenreeks, die een geldige XML‑conforme inhoud van een SVG-afbeelding bevat. Mag niet null, leeg of alleen witruimte zijn. Als het geen SVG‑inhoud is, wordt er een uitzondering gegooid. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


Maakt een nieuw SvgImage‑object aan vanuit inhoud, weergegeven als byte‑stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de SVG-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Voert een oppervlaktetest uit om te bepalen of de opgegeven tekstuele XML‑conforme inhoud
vertegenwoordigt een SVG-afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | inhoud | java.lang.String | XML‑inhoud van een SVG-afbeelding als eenvoudige tekst, niet als base64‑gecodeerde inhoud |
|

**Returns:**
boolean - True als de opgegeven tekenreeks bij eerste blik als geldige SVG kan worden beschouwd, false als het zeker geen SVG is

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Retourneert de inhoud van deze SVG-afbeelding als een binaire stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Retourneert de inhoud van deze SVG-afbeelding als platte tekst (in XML-indeling)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Retourneert de inhoud van deze SVG-afbeelding in zijn oorspronkelijke XML-conforme formaat
tekstuele vorm


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Slaat deze SVG-afbeelding op in het bestand


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Volledig pad naar het bestand, dat zal worden aangemaakt (als het niet bestaat) of overschreven (als het bestaat) met de inhoud van deze SVG-afbeelding |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Slaat deze vector‑SVG-afbeelding op als raster‑PNG-afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Uitvoerstroom, waarin de inhoud van de PNG-afbeelding zal worden geschreven. Mag niet NULL zijn en moet schrijfbaar zijn. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Verwijdert deze rasterafbeelding, waarbij de inhoud wordt verwijderd en de meeste methoden
en eigenschappen niet-werkend


