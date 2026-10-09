---
title: "ImageType"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt ein unterstützbares Bildtyp-Format dar, das sowohl Raster- als auch Vektorformate unterstützt"
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Stellt einen unterstützbaren Bildtyp (Format) dar, unterstützt sowohl Raster- als auch Vektorformate.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Undefinierter Bildtyp – Spezialwert, der normalerweise nicht auftreten sollte |
|
|  | [getJpeg()](#getJpeg--) | JPEG-Bildtyp |
|
|  | [getPng()](#getPng--) | PNG-Bildtyp |
|
|  | [getBmp()](#getBmp--) | BMP-Bildtyp |
|
|  | [getGif()](#getGif--) | GIF-Bildtyp |
|
|  | [getIcon()](#getIcon--) | ICON-Bildtyp |
|
|  | [getSvg()](#getSvg--) | SVG-Vektor-Bildtyp |
|
|  | [getWmf()](#getWmf--) | WMF (Windows MetaFile) Vektor-Bildtyp |
|
|  | [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) Vektor-Bildtyp |
|
|  | [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) Raster-Bildtyp |
|
|  | [getFormalName()](#getFormalName--) | Gibt einen formalen Namen dieses Bildformats zurück. |
|
|  | [isVector()](#isVector--) | Gibt an, ob dieses spezielle Format Vektor (true) oder Raster ist |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Dateierweiterung (ohne führenden Punkt) eines bestimmten Bildtyps |
in Kleinbuchstaben.
|
|  | [toString()](#toString--) | Gibt die Eigenschaft FormalName zurück |
|
|  | [getMimeCode()](#getMimeCode--) | MIME-Code eines bestimmten Bildtyps als Zeichenkette. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Bestimmt, ob diese Instanz mit dem angegebenen "ImageType" gleich ist |
Instanz
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist, |
die vermutlich eine andere "ImageType"-Instanz ist
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definiert, ob zwei bestimmte ImageType-Instanzen gleich sind |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Definiert, ob zwei bestimmte ImageType-Instanzen ungleich sind |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hash-Code zurück, der eine unveränderliche Zahl für dieses spezifische Objekt ist |
Instanz
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Gibt den ImageType-Wert zurück, der dem Dateierweiterungswert entspricht, der |
wird aus dem angegebenen Dateinamen extrahiert
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Gibt den ImageType-Wert zurück, der dem angegebenen MIME-Code entspricht |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Undefinierter Bildtyp – Spezialwert, der normalerweise nicht auftreten sollte


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG-Vektor-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) Vektor-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) Vektor-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) Raster-Bildtyp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Gibt einen formellen Namen dieses Bildformats zurück. Gibt niemals NULL zurück. Wenn
Ist die Instanz nicht beschädigt, wird niemals eine Ausnahme ausgelöst.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Gibt an, ob dieses spezielle Format Vektor (true) oder Raster ist
(false)


**Returns:**
boolesch
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Dateierweiterung (ohne führenden Punkt) eines bestimmten Bildtyps
in Kleinbuchstaben. Für den Typ Undefined wird die Zeichenkette 'unsefined' zurückgegeben.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Gibt die Eigenschaft FormalName zurück


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-Code eines bestimmten Bildtyps als Zeichenkette. Für den Typ Undefined
gibt die Zeichenkette 'unsefined' zurück.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Bestimmt, ob diese Instanz mit dem angegebenen "ImageType" gleich ist
Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Andere ImageType-Instanz zum Vergleich auf Gleichheit mit dieser |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz mit dem angegebenen nicht gecasteten Objekt gleich ist,
die vermutlich eine andere "ImageType"-Instanz ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere System.Object-Instanz, die vermutlich vom Typ ImageType ist, zum Vergleich auf Gleichheit mit dieser |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Definiert, ob zwei bestimmte ImageType-Instanzen gleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Erste ImageType-Instanz zum Vergleich |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Zweite ImageType-Instanz zum Vergleich |
|

**Returns:**
boolesch – Wahr, wenn gleich, sonst falsch

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Definiert, ob zwei bestimmte ImageType-Instanzen ungleich sind


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Erste ImageType-Instanz zum Vergleich |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Zweite ImageType-Instanz zum Vergleich |
|

**Returns:**
boolescher Wert – True, wenn ungleich, false, wenn gleich

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hash-Code zurück, der eine unveränderliche Zahl für dieses spezifische Objekt ist
Instanz


**Returns:**
int – Vorzeichenbehaftete 4-Byte-Ganzzahl

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Gibt den ImageType-Wert zurück, der dem Dateierweiterungswert entspricht, der
wird aus dem angegebenen Dateinamen extrahiert


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dateiname | java.lang.String | Beliebiger Dateiname, kann ein relativer oder voller Pfad sein |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Gibt den ImageType-Wert zurück, der dem angegebenen MIME-Code entspricht


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | mimeCode | java.lang.String | Beliebiger MIME-Code |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

