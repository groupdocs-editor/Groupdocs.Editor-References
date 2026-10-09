---
title: "BmpImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "BMP BitMap Picture formatında bir görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

BMP (BitMap Picture) formatında bir görüntüyü meta verileri ve
ek yöntemler

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | İçerikten yeni BmpImage örneği oluşturur, base64 kodlu olarak temsil edilen |
dize ve belirtilen ad
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | İçerikten yeni BmpImage örneği oluşturur, bayt akışı olarak temsil edilen, |
ve belirtilen ad ile
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir BMP görüntüsü olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizgenin geçerli bir BMP görüntüsü olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Bmp değerini döndürür |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


İçerikten yeni BmpImage örneği oluşturur, base64 kodlu olarak temsil edilen
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | BMP görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. BMP içeriği değilse, bir istisna fırlatılacaktır. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


İçerikten yeni BmpImage örneği oluşturur, bayt akışı olarak temsil edilen,
ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | BMP görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir BMP görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | BMP görüntüsü içerdiği varsayılan bayt akışı |
|

**Returns:**
boolean - Doğru ise belirtilen akış geçerli BMP görüntüsü içeriyorsa, aksi takdirde yanlış

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizgenin geçerli bir BMP görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Varsayılan BMP görüntüsünün içeriği base64 kodlu dize biçiminde |
|

**Returns:**
boolean - Doğru ise belirtilen dize geçerli BMP görüntüsü içeriyorsa, aksi takdirde yanlış

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Bmp değerini döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
