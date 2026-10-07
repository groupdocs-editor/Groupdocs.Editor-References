---
title: "TiffImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één afbeelding voor in het TIFF Tagged Image File Format-formaat met zijn metadata en extra methoden"
type: docs
weight: 16
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

Stelt één afbeelding voor in TIFF (Tagged Image File Format)-formaat met zijn
metadata en extra methoden


*** ** * ** ***

Zie https://en.wikipedia.org/wiki/TIFF voor details. In zeer zeldzame gevallen komt TIFF voor in WordProcessing-documenten.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | Maakt een nieuw TiffImage‑object aan vanuit de inhoud, weergegeven als |
base64-gecodeerde string, en met opgegeven naam
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | Maakt een nieuwe GifImage‑instantie aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stream een geldige TIFF-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde string een geldige TIFF-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | Retourneert een aantal frames (afbeeldingen) in deze TIFF-afbeelding. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


Maakt een nieuw TiffImage‑object aan vanuit de inhoud, weergegeven als
base64-gecodeerde string, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de TIFF-afbeelding. Mag niet null, leeg of alleen witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64‑gecodeerde string. Mag niet null, leeg of alleen witruimte zijn. Als het geen TIFF-inhoud is, wordt er een uitzondering gegooid. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


Maakt een nieuwe GifImage‑instantie aan vanuit inhoud, weergegeven als byte‑stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de GIF-afbeelding. Mag niet null, leeg of witruimtes zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stream een geldige TIFF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stream die vermoedelijk een TIFF-afbeelding bevat |
|

**Returns:**
boolean - True als de opgegeven stream een geldige TIFF-afbeelding bevat, anders false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde string een geldige TIFF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van de vermoedelijke TIFF-afbeelding in de vorm van een base64‑gecodeerde string |
|

**Returns:**
boolean - True als de opgegeven string een geldige TIFF-afbeelding bevat, anders false

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Retourneert een aantal frames (afbeeldingen) in deze TIFF-afbeelding. Mag niet
kleiner dan 1.


**Returns:**
int -
