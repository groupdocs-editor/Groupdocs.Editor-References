---
title: "IconImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één afbeelding in ICON-formaat voor met zijn metadata en extra methoden."
type: docs
weight: 12
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

Stelt één afbeelding in ICON-formaat voor met zijn metadata en extra methoden.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | Maakt een nieuw IconImage-object aan vanuit inhoud, weergegeven als |
base64-gecodeerde string, en met opgegeven naam
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | Maakt een nieuw IconImage-object aan vanuit inhoud, weergegeven als byte-stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stream een geldige ICON-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64-gecodeerde string een geldige ICON-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Retourneert het aantal afbeeldingen dat aanwezig is in dit ICON-bestand |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


Maakt een nieuw IconImage-object aan vanuit inhoud, weergegeven als
base64-gecodeerde string, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de ICON-afbeelding. Mag niet null, leeg of witruimte zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of witruimte zijn. Als het geen ICON-inhoud is, wordt een uitzondering gegooid. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


Maakt een nieuw IconImage-object aan vanuit inhoud, weergegeven als byte-stroom,
en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de ICON-afbeelding. Mag niet null, leeg of witruimte zijn. |
|
|  | binaryContent | java.io.InputStream | Inhoud als byte‑stroom. Lezen begint vanaf de oorspronkelijke positie. Mag niet null zijn. Moet leesbaar en doorzoekbaar zijn. Als deze instantie wordt verwijderd, wordt deze stroom ook verwijderd. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stream een geldige ICON-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte-stroom, die vermoedelijk een ICON-afbeelding bevat |
|

**Returns:**
boolean - True als de opgegeven stream een geldige ICON-afbeelding bevat, false anders

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64-gecodeerde string een geldige ICON-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van de vermoedelijke ICON-afbeelding in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - True als de opgegeven string een geldige ICON-afbeelding bevat, false anders

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Retourneert het aantal afbeeldingen dat aanwezig is in dit ICON-bestand


**Returns:**
int
