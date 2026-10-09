---
title: "GifImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "GIF Graphics Interchange Format formatında bir görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

GIF (Graphics Interchange Format) formatında bir görüntüyü, onun
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | İçeriğinden, base64 kodlu olarak temsil edilen yeni bir GifImage örneği oluşturur |
dize ve belirtilen ad
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | İçeriğinden, bayt akışı olarak temsil edilen yeni bir GifImage örneği oluşturur, |
ve belirtilen ad ile
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir GIF görüntüsü olup olmadığını kontrol eder |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir GIF görüntüsü olup olmadığını kontrol eder |
|
|  | [getType()](#getType--) | ImageType.Gif döndürür |
|
|  | [getVersion()](#getVersion--) | Bu GIF görüntüsünün dahili sürümünü döndürür (sürüm şu |
başlık) kaynaktan çıkarılır)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


İçeriğinden, base64 kodlu olarak temsil edilen yeni bir GifImage örneği oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | GIF görüntüsünün adı. Null, boş veya boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya boşluk olamaz. Eğer bir GIF içeriği değilse, istisna fırlatılacaktır. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
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

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir GIF görüntüsü olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bayt akışı, muhtemelen bir GIF görüntüsü içerir |
|

**Returns:**
boolean - Belirtilen akış geçerli bir GIF görüntüsü içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir GIF görüntüsü olup olmadığını kontrol eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Muhtemel GIF görüntüsünün içeriği, base64 kodlu bir dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir GIF görüntüsü içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Gif döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


Bu GIF görüntüsünün dahili sürümünü döndürür (sürüm şu
başlık) kaynaktan çıkarılır)


**Returns:**
java.lang.String
