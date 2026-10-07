---
title: "JpegImage"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "JPEG Joint Photographic Experts Group formatında bir resmi, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

JPEG (Joint Photographic Experts Group) formatında bir resmi, ile
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | İçeriği, ... olarak temsil eden yeni JpegImage örneğini oluşturur |
base64 kodlu dize ve belirtilen ad ile
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni JpegImage örneğini oluşturur, |
ve belirtilen adla
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir JPEG görüntüsü olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir JPEG görüntüsü olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | ImageType.Jpeg döndürür |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


İçeriği, ... olarak temsil eden yeni JpegImage örneğini oluşturur
base64 kodlu dize ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | JPEG görüntünün adı. Null, boş veya yalnız boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya yalnız boşluk olamaz. JPEG içeriği değilse, istisna fırlatılacaktır. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni JpegImage örneğini oluşturur,
ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | JPEG görüntünün adı. Null, boş veya yalnız boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma, orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir JPEG görüntüsü olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | JPEG görüntüsü içeriyor gibi görünen bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli JPEG görüntüsü içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir JPEG görüntüsü olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | JPEG görüntüsü içeriyor gibi görünen içeriğin base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli JPEG görüntüsü içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Jpeg döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
