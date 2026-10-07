---
title: "BmpImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één afbeelding in BMP BitMap Picture-formaat voor met zijn metadata en extra methoden"
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

Stelt één afbeelding in BMP (BitMap Picture)-formaat voor met zijn metadata en
aanvullende methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | Maakt een nieuw BmpImage‑object aan vanuit inhoud, weergegeven als base64‑gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw BmpImage‑object aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldige BMP-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde tekenreeks een geldige BMP-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


Maakt een nieuw BmpImage‑object aan vanuit inhoud, weergegeven als base64‑gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de BMP-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64‑gecodeerde tekenreeks. Mag niet null, leeg of alleen witruimte zijn. Als het geen BMP‑inhoud is, wordt een uitzondering gegooid. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


Maakt een nieuw BmpImage‑object aan vanuit inhoud, weergegeven als byte‑stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de BMP-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldige BMP-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom die vermoedelijk een BMP-afbeelding bevat |
|

**Returns:**
boolean - Waar als de opgegeven stroom een geldige BMP-afbeelding bevat, anders onwaar

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde tekenreeks een geldige BMP-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van de vermoedelijke BMP-afbeelding in de vorm van een base64‑gecodeerde tekenreeks |
|

**Returns:**
boolean - Waar als de opgegeven tekenreeks een geldige BMP-afbeelding bevat, anders onwaar

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
