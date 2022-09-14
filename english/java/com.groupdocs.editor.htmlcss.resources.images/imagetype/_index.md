---
title: ImageType
second_title: GroupDocs.Editor for Java API Reference
description: Represents one supportable image type format supports both raster and vector formats
type: docs
weight: 11
url: /java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Represents one supportable image type (format), supports both raster and vector formats
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getUndefined()](#getUndefined--) | Undefined image type - special value, which should not normally occur |
| [getJpeg()](#getJpeg--) | JPEG image type |
| [getPng()](#getPng--) | PNG image type |
| [getBmp()](#getBmp--) | BMP image type |
| [getGif()](#getGif--) | GIF image type |
| [getIcon()](#getIcon--) | ICON image type |
| [getSvg()](#getSvg--) | SVG vector image type |
| [getWmf()](#getWmf--) | WMF (Windows MetaFile) vector image type |
| [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) vector image type |
| [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) raster image type |
| [getFormalName()](#getFormalName--) | Returns a formal name of this image format. |
| [isVector()](#isVector--) | Indicates whether this particular format is vector (true) or raster (false) |
| [getFileExtension()](#getFileExtension--) | File extension (without leading dot character) of a particular image type in lower case. |
| [toString()](#toString--) | Returns a FormalName property |
| [getMimeCode()](#getMimeCode--) | MIME code of a particular image type as a string. |
| [getFormat()](#getFormat--) |  |
| [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Determines whether this instance is equal with specified "ImageType" instance |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal with specified uncasted object, which presumably is another "ImageType" instance |
| [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Defines whether two specific ImageType instances are equal |
| [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Defines whether two specific ImageType instances are not equal |
| [hashCode()](#hashCode--) | Returns a hash-code, which is an immutable number for this specific instance |
| [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returns ImageType value, which is equivalent of filename extension, which is extracted from specified filename |
| [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Returns ImageType value, which is equivalent of specified MIME code |
| [CloneTo(ImageType that)](#CloneTo-com.groupdocs.editor.htmlcss.resources.images.ImageType-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(ImageType obj1, ImageType obj2)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) |  |
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Undefined image type - special value, which should not normally occur

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG vector image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) vector image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) vector image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) raster image type

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Returns a formal name of this image format. Never reurns NULL. If instance is not corrupted, never throws an exception.

**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Indicates whether this particular format is vector (true) or raster (false)

**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


File extension (without leading dot character) of a particular image type in lower case. For the Undefined type returns a string 'unsefined'.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a FormalName property

**Returns:**
java.lang.String - 
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME code of a particular image type as a string. For the Undefined type returns a string 'unsefined'.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final System.Drawing.Imaging.ImageFormat getFormat()
```




**Returns:**
com.aspose.ms.System.Drawing.Imaging.ImageFormat
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Determines whether this instance is equal with specified "ImageType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Other ImageType instance to check on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal with specified uncasted object, which presumably is another "ImageType" instance

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Other System.Object instance, that is presumably of ImageType type, to check on equality with this |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


Defines whether two specific ImageType instances are equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | First ImageType instance to check |
| second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Second ImageType instance to check |

**Returns:**
boolean - True if are equal, false if are unequal
### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


Defines whether two specific ImageType instances are not equal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | First ImageType instance to check |
| second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Second ImageType instance to check |

**Returns:**
boolean - True if are unequal, false if are equal
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash-code, which is an immutable number for this specific instance

**Returns:**
int - Signed 4-byte integer
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Returns ImageType value, which is equivalent of filename extension, which is extracted from specified filename

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | Arbitrary filename, can be a relative or full path |

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.
### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Returns ImageType value, which is equivalent of specified MIME code

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mimeCode | java.lang.String | Arbitrary MIME-code |

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.
### CloneTo(ImageType that) {#CloneTo-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public void CloneTo(ImageType that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) |  |

### Clone() {#Clone--}
```
public ImageType Clone()
```




**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(ImageType obj1, ImageType obj2) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean equals(ImageType obj1, ImageType obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) |  |
| obj2 | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) |  |

**Returns:**
boolean
