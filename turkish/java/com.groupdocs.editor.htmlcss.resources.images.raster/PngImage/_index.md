---
title: "PngImage"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "PNG Portable Network Graphics formatında bir görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 14
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

PNG (Portable Network Graphics) formatında bir görüntüyü, kendi
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | İçerikten, base64 kodlu olarak temsil edilen yeni bir PngImage örneği oluşturur |
dize ve belirtilen adla
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | İçerikten, bayt akışı olarak temsil edilen yeni bir PngImage örneği oluşturur, |
ve belirtilen adla
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir PNG görüntüsü olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir PNG görüntüsü olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | ImageType.Png döndürür |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


İçerikten, base64 kodlu olarak temsil edilen yeni bir PngImage örneği oluşturur
dize ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | PNG görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. Eğer PNG içeriği değilse, bir istisna fırlatılacaktır. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


İçerikten, bayt akışı olarak temsil edilen yeni bir PngImage örneği oluşturur,
ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | PNG görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma, orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir PNG görüntüsü olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bir PNG görüntüsü içerdiği varsayılan bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir PNG görüntüsü içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir PNG görüntüsü olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Varsayılan PNG görüntüsünün içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir PNG görüntüsü içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Png döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
