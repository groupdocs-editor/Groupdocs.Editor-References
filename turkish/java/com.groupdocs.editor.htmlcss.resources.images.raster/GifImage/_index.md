---
title: "GifImage"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "GIF Graphics Interchange Format formatındaki bir resmi, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

GIF (Graphics Interchange Format) formatındaki bir resmi, onun
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni bir GifImage örneği oluşturur |
dize ve belirtilen adla
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni bir GifImage örneği oluşturur, |
ve belirtilen adla
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir GIF resmi olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir GIF resmi olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Gif döndürür |
|
|  | [getVersion()](#getVersion--) | Bu GIF resminin dahili sürümünü döndürür (sürüm şu kaynaktan çıkarılır |
header)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni bir GifImage örneği oluşturur
dize ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | GIF görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. Eğer GIF içeriği değilse, bir istisna fırlatılacaktır. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni bir GifImage örneği oluşturur,
ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | GIF görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma, orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir GIF resmi olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bir GIF görüntüsü içerdiği varsayılan bayt akışı |
|

**Returns:**
boolean - Belirtilen akış geçerli bir GIF görüntüsü içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir GIF resmi olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Varsayılan GIF görüntüsünün içeriği base64 kodlu dize biçiminde |
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


Bu GIF resminin dahili sürümünü döndürür (sürüm şu kaynaktan çıkarılır
header)


**Returns:**
java.lang.String
