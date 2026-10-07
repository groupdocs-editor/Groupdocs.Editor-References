---
title: "GifImage"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één afbeelding in GIF Graphics Interchange Format voor met zijn metadata en extra methoden"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

Stelt één afbeelding in GIF (Graphics Interchange Format) voor met zijn
metadata en extra methoden

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | Maakt een nieuwe GifImage‑instantie aan vanuit inhoud, weergegeven als base64‑gecodeerd |
tekenreeks, en met opgegeven naam
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | Maakt een nieuwe GifImage‑instantie aan vanuit inhoud, weergegeven als byte‑stroom, |
en met opgegeven naam
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Controleert of de opgegeven stroom een geldige GIF-afbeelding is |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Controleert of de opgegeven base64‑gecodeerde tekenreeks een geldige GIF-afbeelding is |
|
|  | [getType()](#getType--) | Retourneert ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | Retourneert de interne versie van deze GIF-afbeelding (versie wordt gehaald uit |
koptekst)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


Maakt een nieuwe GifImage‑instantie aan vanuit inhoud, weergegeven als base64‑gecodeerd
tekenreeks, en met opgegeven naam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | naam | java.lang.String | Naam van de GIF-afbeelding. Mag niet null, leeg of witruimtes zijn. |
|
|  | contentInBase64 | java.lang.String | Inhoud als base64-gecodeerde string. Mag niet null, leeg of witruimtes zijn. Als het geen GIF-inhoud is, wordt er een uitzondering gegooid. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
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

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Controleert of de opgegeven stroom een geldige GIF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte‑stroom, die vermoedelijk een GIF-afbeelding bevat |
|

**Returns:**
boolean - Waar als de opgegeven stroom een geldige GIF-afbeelding bevat, anders onwaar

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Controleert of de opgegeven base64‑gecodeerde tekenreeks een geldige GIF-afbeelding is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Inhoud van de vermoedelijke GIF-afbeelding in de vorm van een base64-gecodeerde string |
|

**Returns:**
boolean - Waar als de opgegeven string een geldige GIF-afbeelding bevat, anders onwaar

### getType() {#getType--}
```
public ImageType getType()
```


Retourneert ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Retourneert de interne versie van deze GIF-afbeelding (versie wordt gehaald uit
koptekst)


**Returns:**
java.lang.String
