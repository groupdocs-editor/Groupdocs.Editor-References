---
title: "WmfImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "WMF Windows MetaFile formatında bir vektör görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

WMF (Windows MetaFile) formatında bir vektör görüntüyü ile
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | İçeriğinden, base64 kodlu olarak temsil edilen yeni bir WmfImage örneği oluşturur |
dize ve belirtilen ad
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | İçeriğinden, bayt akışı olarak temsil edilen yeni bir WmfImage örneği oluşturur, |
ve belirtilen ad ile
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir WMF görüntüsü olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizeyin geçerli bir WMF görüntüsü olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Wmf değerini döndürür |
|
|  | [getByteContent()](#getByteContent--) | Bu WMF görüntüsünün içeriğini ikili akış olarak döndürür |
|
|  | [getTextContent()](#getTextContent--) | Bu WMF görüntüsünün içeriğini düz metin olarak döndürür |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu WMF görüntüsünü dosyaya kaydeder |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Bu vektör WMF görüntüsünü raster PNG görüntüsü olarak kaydeder |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Bu vektör WMF görüntüsünü vektör SVG görüntüsü olarak kaydeder |
|
|  | [dispose()](#dispose--) | Bu WMF görüntüsünü içeriğini serbest bırakarak ve çoğu özelliğini |
metod ve özelliklerini çalışmaz hâle getirir
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


İçeriğinden, base64 kodlu olarak temsil edilen yeni bir WmfImage örneği oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WMF görüntüsünün adı. Null, boş veya sadece boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Null, boş veya sadece boşluk olamaz. WMF içeriği değilse, bir istisna fırlatılacaktır. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


İçeriğinden, bayt akışı olarak temsil edilen yeni bir WmfImage örneği oluşturur,
ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | WMF görüntüsünün adı. Null, boş veya sadece boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir WMF görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Giriş bayt akışı. NULL olamaz, okuma ve konumlama (seeking) desteklemelidir. |
|

**Returns:**
boolean - Belirtilen akış geçerli bir WMF görüntüsü içeriyorsa True, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizeyin geçerli bir WMF görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | Giriş dizesi, WMF görüntüsünün içeriğinin base64 kodlamasıyla saklandığı yer. NULL veya boş olamaz. |
|

**Returns:**
boolean - Belirtilen dize geçerli bir WMF görüntüsü içeriyorsa True, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Wmf değerini döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Bu WMF görüntüsünün içeriğini ikili akış olarak döndürür


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Bu WMF görüntüsünün içeriğini düz metin olarak döndürür


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Bu WMF görüntüsünü dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Bu WMF görüntüsünün içeriğiyle oluşturulacak (var değilse) veya üzerine yazılacak (var ise) dosyanın tam yolu |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Bu vektör WMF görüntüsünü raster PNG görüntüsü olarak kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Çıktı akışı, PNG görüntüsünün içeriğinin yazılacağı yer. NULL olamaz ve yazılabilir olmalıdır. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Bu vektör WMF görüntüsünü vektör SVG görüntüsü olarak kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Çıktı akışı, SVG görüntüsünün içeriğinin yazılacağı yer. NULL olamaz ve yazılabilir olmalıdır. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Bu WMF görüntüsünü içeriğini serbest bırakarak ve çoğu özelliğini
metod ve özelliklerini çalışmaz hâle getirir


