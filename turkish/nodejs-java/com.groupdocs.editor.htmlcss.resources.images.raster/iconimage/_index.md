---
title: "IconImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "ICON formatında bir resmi, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

ICON formatında bir resmi, meta verileri ve ek yöntemleriyle temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | İçeriği temsil eden yeni bir IconImage örneği oluşturur, |
base64 kodlu dize ve belirtilen ad ile
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni bir IconImage örneği oluşturur, |
ve belirtilen ad ile
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir ICON görüntüsü olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizenin geçerli bir ICON görüntüsü olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Icon değerini döndürür |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | Bu ICON dosyasında bulunan görüntü sayısını döndürür |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


İçeriği temsil eden yeni bir IconImage örneği oluşturur,
base64 kodlu dize ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | ICON görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya sadece boşluk olamaz. ICON içeriği değilse, bir istisna fırlatılacaktır. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni bir IconImage örneği oluşturur,
ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | ICON görüntüsünün adı. Boş, null veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir ICON görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Bayt akışı, muhtemelen bir ICON görüntüsü içerir |
|

**Returns:**
boolean - Belirtilen akış geçerli bir ICON görüntüsü içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizenin geçerli bir ICON görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Muhtemel ICON görüntüsünün içeriği, base64 kodlu bir dize biçiminde |
|

**Returns:**
boolean - Belirtilen dize geçerli bir ICON görüntüsü içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Icon değerini döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


Bu ICON dosyasında bulunan görüntü sayısını döndürür


**Returns:**
int
