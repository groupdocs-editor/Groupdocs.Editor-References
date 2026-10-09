---
title: "JpegImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "JPEG Joint Photographic Experts Group formatında bir görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

JPEG (Joint Photographic Experts Group) formatında bir görüntüyü şu ile temsil eder
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | İçerikten yeni JpegImage örneği oluşturur, şu şekilde temsil edilen |
base64 kodlu dize ve belirtilen ad ile
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | İçerikten yeni JpegImage örneği oluşturur, bayt akışı olarak temsil edilen, |
ve belirtilen ad ile
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir JPEG görüntüsü olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir JPEG görüntüsü olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Jpeg döndürür |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


İçerikten yeni JpegImage örneği oluşturur, şu şekilde temsil edilen
base64 kodlu dize ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | JPEG görüntüsünün adı. Null, boş veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya sadece boşluk olamaz. JPEG içeriği değilse, istisna fırlatılacaktır. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


İçerikten yeni JpegImage örneği oluşturur, bayt akışı olarak temsil edilen,
ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | JPEG görüntüsünün adı. Null, boş veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir JPEG görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bayt akışı, muhtemelen bir JPEG görüntüsü içerir |
|

**Returns:**
boolean - Belirtilen akış geçerli bir JPEG görüntüsü içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir JPEG görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Muhtemel JPEG görüntüsünün içeriği, base64 kodlu bir dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir JPEG görüntüsü içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Jpeg döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
