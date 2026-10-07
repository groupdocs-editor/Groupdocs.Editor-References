---
title: "PngImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één afbeelding in PNG Portable Network Graphics-formaat voor met zijn metadata en extra methoden"
type: docs
weight: 14
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

Stelt één afbeelding in PNG (Portable Network Graphics)-formaat voor met zijn
metadata en extra methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | Maakt een nieuw PngImage‑instance aan vanuit inhoud, weergegeven als base64-gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw PngImage‑instance aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldige PNG-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64-gecodeerde string een geldige PNG-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


Maakt een nieuw PngImage‑instance aan vanuit inhoud, weergegeven als base64-gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de PNG-afbeelding. Mag niet null, leeg of witruimtes zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of witruimtes zijn. Als het geen PNG-inhoud is, wordt er een uitzondering gegooid. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


Maakt een nieuw PngImage‑instance aan vanuit inhoud, weergegeven als byte‑stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de PNG-afbeelding. Mag niet null, leeg of witruimtes zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldige PNG-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom, die vermoedelijk een PNG-afbeelding bevat |
|

**Returns:**
boolean - Waar als de opgegeven stroom een geldige PNG-afbeelding bevat, anders onwaar

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64-gecodeerde string een geldige PNG-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van de vermoedelijke PNG-afbeelding in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - Waar als de opgegeven string een geldige PNG-afbeelding bevat, anders onwaar

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
