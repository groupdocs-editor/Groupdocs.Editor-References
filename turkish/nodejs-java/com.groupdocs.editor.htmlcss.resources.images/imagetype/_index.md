---
title: "ImageType"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Hem raster hem vektör formatlarını destekleyen tek bir desteklenebilir görüntü türü biçimini temsil eder"
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

Desteklenebilir bir görüntü türünü (formatını) temsil eder, raster ve vektör formatlarını destekler.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Tanımsız görüntü türü - normalde ortaya çıkmaması gereken özel bir değer |
|
|  | [getJpeg()](#getJpeg--) | JPEG görüntü türü |
|
|  | [getPng()](#getPng--) | PNG görüntü türü |
|
|  | [getBmp()](#getBmp--) | BMP görüntü türü |
|
|  | [getGif()](#getGif--) | GIF görüntü türü |
|
|  | [getIcon()](#getIcon--) | ICON görüntü türü |
|
|  | [getSvg()](#getSvg--) | SVG vektör görüntü türü |
|
|  | [getWmf()](#getWmf--) | WMF (Windows MetaFile) vektör görüntü türü |
|
|  | [getEmf()](#getEmf--) | EMF (Enhanced MetaFile) vektör görüntü türü |
|
|  | [getTiff()](#getTiff--) | TIFF (Tagged Image File Format) raster görüntü türü |
|
|  | [getFormalName()](#getFormalName--) | Bu görüntü formatının resmi adını döndürür. |
|
|  | [isVector()](#isVector--) | Bu belirli formatın vektör (true) mı yoksa raster mı olduğunu gösterir |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | Belirli bir görüntü türünün dosya uzantısı (başındaki nokta karakteri olmadan) |
küçük harflerle.
|
|  | [toString()](#toString--) | FormalName özelliğini döndürür |
|
|  | [getMimeCode()](#getMimeCode--) | Belirli bir görüntü türünün MIME kodunu dize olarak döndürür. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | Bu örneğin belirtilen "ImageType" ile eşit olup olmadığını belirler |
örnek
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler, |
muhtemelen başka bir "ImageType" örneği olduğunu varsayar
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | İki belirli ImageType örneğinin eşit olup olmadığını tanımlar |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | İki belirli ImageType örneğinin eşit olmama durumunu tanımlar |
|
|  | [hashCode()](#hashCode--) | Bu belirli nesne için değişmez bir sayı olan hash kodunu döndürür |
örnek
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Dosya uzantısına eşdeğer olan ImageType değerini döndürür, bu |
belirtilen dosya adından çıkarılır
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Belirtilen MIME koduna eşdeğer olan ImageType değerini döndürür |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


Tanımsız görüntü türü - normalde ortaya çıkmaması gereken özel bir değer


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


JPEG görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


PNG görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


BMP görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


GIF görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


ICON görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


SVG vektör görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


WMF (Windows MetaFile) vektör görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


EMF (Enhanced MetaFile) vektör görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


TIFF (Tagged Image File Format) raster görüntü türü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Bu görüntü formatının resmi adını döndürür. Asla NULL döndürmez. Eğer
örnek bozulmamışsa, asla bir istisna fırlatmaz.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


Bu belirli formatın vektör (true) mı yoksa raster mı olduğunu gösterir
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Belirli bir görüntü türünün dosya uzantısı (başındaki nokta karakteri olmadan)
küçük harflerle. Undefined türü için 'unsefined' dizesini döndürür.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


FormalName özelliğini döndürür


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Belirli bir görüntü türünün MIME kodunu dize olarak döndürür. Undefined türü için
'unsefined' dizesini döndürür.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


Bu örneğin belirtilen "ImageType" ile eşit olup olmadığını belirler
örnek


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Bu ile eşitliği kontrol etmek için diğer ImageType örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler,
muhtemelen başka bir "ImageType" örneği olduğunu varsayar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Bu nesneyle eşitliği kontrol etmek için muhtemelen ImageType türünde olan başka bir System.Object örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


İki belirli ImageType örneğinin eşit olup olmadığını tanımlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Kontrol edilecek ilk ImageType örneği |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Kontrol edilecek ikinci ImageType örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


İki belirli ImageType örneğinin eşit olmama durumunu tanımlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Kontrol edilecek ilk ImageType örneği |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | Kontrol edilecek ikinci ImageType örneği |
|

**Returns:**
boolean - Eşit değilse True, eşit ise false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu belirli nesne için değişmez bir sayı olan hash kodunu döndürür
örnek


**Returns:**
int - İşaretli 4 bayt tamsayı

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


Dosya uzantısına eşdeğer olan ImageType değerini döndürür, bu
belirtilen dosya adından çıkarılır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya adı | java.lang.String | İsteğe bağlı dosya adı, göreli ya da tam yol olabilir |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


Belirtilen MIME koduna eşdeğer olan ImageType değerini döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mimeCode | java.lang.String | İsteğe bağlı MIME kodu |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

