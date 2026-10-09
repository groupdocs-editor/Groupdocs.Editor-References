---
title: "ImageType"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar ett stödjande bildformat som stödjer både raster- och vektorformat"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Representerar en stödbar bildtyp (format), stöder både raster- och vektorformat.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Odefinierad bildtyp - specialvärde som normalt inte bör förekomma |
|
|  | [getJpeg()](#getJpeg--) | JPEG-bildtyp |
|
|  | [getPng()](#getPng--) | PNG-bildtyp |
|
|  | [getBmp()](#getBmp--) | BMP-bildtyp |
|
|  | [getGif()](#getGif--) | GIF-bildtyp |
|
|  | [getIcon()](#getIcon--) | ICON-bildtyp |
|
|  | [getSvg()](#getSvg--) | SVG-vektorbildtyp |
|
|  | [getWmf()](#getWmf--) | WMF (Windows MetaFile) vektorbildtyp |
|
|  | [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) vektorbildtyp |
|
|  | [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) rasterbildtyp |
|
|  | [getFormalName()](#getFormalName--) | Returnerar ett formellt namn för detta bildformat. |
|
|  | [isVector()](#isVector--) | Anger om detta specifika format är vektor (true) eller raster |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Filändelse (utan inledande punkt) för en specifik bildtyp |
i gemener.
|
|  | [toString()](#toString--) | Returnerar en FormalName-egenskap |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-kod för en specifik bildtyp som en sträng. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Bestämmer om detta objekt är lika med den angivna "ImageType" |
instans
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med angivet okastat objekt, |
vilket förmodligen är en annan "ImageType"-instans
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definierar om två specifika ImageType-instansers är lika |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definierar om två specifika ImageType-instansers inte är lika |
|
|  | [hashCode()](#hashCode--) | Returnerar en hash-kod, som är ett oföränderligt tal för detta specifika |
instans
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returnerar ImageType-värde, som motsvarar filnamnstillägget, som |
extraheras från angivet filnamn
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Returnerar ImageType-värde, som motsvarar angiven MIME-kod |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Odefinierad bildtyp - specialvärde som normalt inte bör förekomma


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG-bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG-bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP-bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF-bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON-bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG-vektorbildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) vektorbildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) vektorbildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) rasterbildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Returnerar ett formellt namn för detta bildformat. Returnerar aldrig NULL. Om
instansen inte är korrupt, kastar aldrig ett undantag.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Anger om detta specifika format är vektor (true) eller raster
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Filändelse (utan inledande punkt) för en specifik bildtyp
i gemener. För den odefinierade typen returneras en sträng 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returnerar en FormalName-egenskap


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME‑kod för en viss bildtyp som en sträng. För den odefinierade typen
returnerar en sträng 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Bestämmer om detta objekt är lika med den angivna "ImageType"
instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Annat ImageType‑instans att kontrollera likhet med detta |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt är lika med angivet okastat objekt,
vilket förmodligen är en annan "ImageType"-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annat System.Object‑instans, som förmodligen är av ImageType‑typ, för att kontrollera likhet med detta |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Definierar om två specifika ImageType-instansers är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Första ImageType‑instans att kontrollera |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Andra ImageType‑instans att kontrollera |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Definierar om två specifika ImageType-instansers inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Första ImageType‑instans att kontrollera |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Andra ImageType‑instans att kontrollera |
|

**Returns:**
boolesk – True om de är olika, false om de är lika

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hash-kod, som är ett oföränderligt tal för detta specifika
instans


**Returns:**
int – Signerat 4‑byte heltal

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Returnerar ImageType-värde, som motsvarar filnamnstillägget, som
extraheras från angivet filnamn


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filnamn | java.lang.String | Godtyckligt filnamn, kan vara en relativ eller fullständig sökväg |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Returnerar ImageType-värde, som motsvarar angiven MIME-kod


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Godtycklig MIME‑kod |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

