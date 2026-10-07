---
title: "ImageType"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt één ondersteund afbeeldingstype voor dat zowel raster- als vectorformaten ondersteunt"
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Stelt één ondersteund afbeeldings type (formaat) voor, ondersteunt zowel raster- als vectorformaten.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Ongedefinieerd afbeeldingstype - speciale waarde, die normaal niet zou moeten voorkomen |
|
|  | [getJpeg()](#getJpeg--) | JPEG-afbeeldingstype |
|
|  | [getPng()](#getPng--) | PNG-afbeeldingstype |
|
|  | [getBmp()](#getBmp--) | BMP-afbeeldingstype |
|
|  | [getGif()](#getGif--) | GIF-afbeeldingstype |
|
|  | [getIcon()](#getIcon--) | ICON-afbeeldingstype |
|
|  | [getSvg()](#getSvg--) | SVG-vectorafbeeldingstype |
|
|  | [getWmf()](#getWmf--) | WMF (Windows MetaFile) vectorafbeeldingstype |
|
|  | [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) vectorafbeeldingstype |
|
|  | [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) rasterafbeeldingstype |
|
|  | [getFormalName()](#getFormalName--) | Retourneert een formele naam van dit afbeeldingsformaat. |
|
|  | [isVector()](#isVector--) | Geeft aan of dit specifieke formaat vector (true) of raster is |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Bestandsextensie (zonder voorafgaande punt) van een specifiek afbeeldingstype |
in kleine letters.
|
|  | [toString()](#toString--) | Retourneert de FormalName-eigenschap |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-code van een specifiek afbeeldingstype als een string. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Bepaalt of deze instantie gelijk is aan de opgegeven "ImageType" |
instantie
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object, |
wat vermoedelijk een andere "ImageType"-instantie is
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definieert of twee specifieke ImageType-instanties gelijk zijn |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definieert of twee specifieke ImageType-instanties niet gelijk zijn |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode, die een onveranderlijk getal is voor dit specifieke |
instantie
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Retourneert de ImageType-waarde, die gelijk is aan de bestandsextensie, die |
wordt gehaald uit de opgegeven bestandsnaam
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Retourneert de ImageType-waarde, die gelijk is aan de opgegeven MIME-code |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Ongedefinieerd afbeeldingstype - speciale waarde, die normaal niet zou moeten voorkomen


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG-afbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG-afbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP-afbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF-afbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON-afbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG-vectorafbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) vectorafbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) vectorafbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) rasterafbeeldingstype


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Retourneert een formele naam van dit afbeeldingsformaat. Retourneert nooit NULL. Als
de instantie niet corrupt is, nooit een uitzondering werpt.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Geeft aan of dit specifieke formaat vector (true) of raster is
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bestandsextensie (zonder voorafgaande punt) van een specifiek afbeeldingstype
in kleine letters. Voor het Undefined-type retourneert een string 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Retourneert de FormalName-eigenschap


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-code van een specifiek afbeeldingstype als een string. Voor het Undefined-type
retourneert een string 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven "ImageType"
instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Andere ImageType-instantie om op gelijkheid met deze te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan het opgegeven niet-gecastte object,
wat vermoedelijk een andere "ImageType"-instantie is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere System.Object-instantie, die vermoedelijk van het type ImageType is, om op gelijkheid met deze te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Definieert of twee specifieke ImageType-instanties gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Eerste ImageType-instantie om te controleren |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Tweede ImageType-instantie om te controleren |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Definieert of twee specifieke ImageType-instanties niet gelijk zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Eerste ImageType-instantie om te controleren |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Tweede ImageType-instantie om te controleren |
|

**Returns:**
boolean - True als ze ongelijk zijn, false als ze gelijk zijn

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode, die een onveranderlijk getal is voor dit specifieke
instantie


**Returns:**
int - Ondertekende 4-byte integer

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Retourneert de ImageType-waarde, die gelijk is aan de bestandsextensie, die
wordt gehaald uit de opgegeven bestandsnaam


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bestandsnaam | java.lang.String | Willekeurige bestandsnaam, kan een relatief of volledig pad zijn |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Retourneert de ImageType-waarde, die gelijk is aan de opgegeven MIME-code


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Willekeurige MIME-code |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

