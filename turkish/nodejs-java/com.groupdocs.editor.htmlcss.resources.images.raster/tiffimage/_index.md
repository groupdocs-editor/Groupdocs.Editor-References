---
title: "TiffImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "TIFF Tagged Image File Format formatında bir görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

TIFF (Tagged Image File Format) formatında bir görüntüyü, onun
meta verileri ve ek yöntemleri


*** ** * ** ***

Ayrıntılar için https://en.wikipedia.org/wiki/TIFF adresine bakın. Çok nadir durumlarda TIFF, WordProcessing belgelerinde bulunur.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | İçeriğinden yeni TiffImage örneği oluşturur, şu şekilde temsil edilir |
base64 kodlu dize ve belirtilen ad ile
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | İçeriğinden, bayt akışı olarak temsil edilen yeni bir GifImage örneği oluşturur, |
ve belirtilen ad ile
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir TIFF görüntüsü olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir TIFF görüntüsü olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Tiff döndürür |
|
|  | [getFramesCount()](#getFramesCount--) | Bu TIFF görüntüsü içindeki çerçeve (görüntü) sayısını döndürür. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


İçeriğinden yeni TiffImage örneği oluşturur, şu şekilde temsil edilir
base64 kodlu dize ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | TIFF görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. TIFF içeriği değilse, istisna fırlatılacaktır. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


İçeriğinden, bayt akışı olarak temsil edilen yeni bir GifImage örneği oluşturur,
ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | GIF görüntüsünün adı. Null, boş veya boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir TIFF görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Muhtemelen bir TIFF görüntüsü içeren bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir TIFF görüntüsü içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir TIFF görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Muhtemel TIFF görüntüsünün içeriği, base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir TIFF görüntüsü içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Tiff döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


Bu TIFF görüntüsü içindeki çerçeve (görüntü) sayısını döndürür. Olamaz
1'den küçük.


**Returns:**
int -
