---
title: "EmfImage"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Gelişmiş metafile (EMF) formatında bir vektör görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

Gelişmiş metafile (EMF) formatında bir vektör görüntüyü
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | İçeriği base64 kodlu olarak temsil eden yeni EmfImage örneği oluşturur |
dize ve belirtilen ad
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni EmfImage örneği oluşturur, |
ve belirtilen ad ile
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | Belirtilen akışın geçerli bir EMF görüntüsü olup olmadığını denetler |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | Belirtilen base64 kodlu dizeyin geçerli bir EMF görüntüsü olup olmadığını denetler |
|
|  | [getType()](#getType--) | ImageType.Emf değerini döndürür |
|
|  | [getByteContent()](#getByteContent--) | Bu EMF görüntüsünün içeriğini ikili akış olarak döndürür |
|
|  | [getTextContent()](#getTextContent--) | Bu EMF görüntüsünün içeriğini düz metin olarak döndürür |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu EMF görüntüsünü dosyaya kaydeder |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Bu vektör EMF görüntüsünü raster PNG görüntüsüne kaydeder |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | Bu vektör EMF görüntüsünü vektör SVG görüntüsüne kaydeder |
|
|  | [dispose()](#dispose--) | Bu EMF görüntüsünü, içeriğini serbest bırakarak ve çoğunu |
metod ve özelliklerini çalışmaz hâle getirir
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


İçeriği base64 kodlu olarak temsil eden yeni EmfImage örneği oluşturur
dize ve belirtilen ad


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | EMF görüntüsünün adı. Boş, null veya yalnız boşluk olamaz. |
|
|  | contentInBase64 | java.lang.String | İçerik base64 kodlu dize olarak. Boş, null veya yalnız boşluk olamaz. EMF içeriği değilse, istisna fırlatılacaktır. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni EmfImage örneği oluşturur,
ve belirtilen ad ile


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | EMF görüntüsünün adı. Boş, null veya yalnız boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


Belirtilen akışın geçerli bir EMF görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Giriş bayt akışı. NULL olamaz, okuma ve konumlama (seeking) desteklemelidir. |
|

**Returns:**
boolean - Belirtilen akış geçerli bir EMF görüntüsü içeriyorsa true, aksi takdirde false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


Belirtilen base64 kodlu dizeyin geçerli bir EMF görüntüsü olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | EMF görüntüsünün içeriğinin base64 kodlamasıyla saklandığı girdi dizesi. NULL veya boş olamaz. |
|

**Returns:**
boolean - Belirtilen dize geçerli bir EMF görüntüsü içeriyorsa true, aksi takdirde false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Emf değerini döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Bu EMF görüntüsünün içeriğini ikili akış olarak döndürür


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Bu EMF görüntüsünün içeriğini düz metin olarak döndürür


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Bu EMF görüntüsünü dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Bu EMF görüntüsünün içeriğiyle oluşturulacak (var değilse) veya üzerine yazılacak (var ise) dosyanın tam yolu |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Bu vektör EMF görüntüsünü raster PNG görüntüsüne kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Çıktı akışı, PNG görüntüsünün içeriğinin yazılacağı yer. NULL olamaz ve yazılabilir olmalıdır. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


Bu vektör EMF görüntüsünü vektör SVG görüntüsüne kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | Çıktı akışı, SVG görüntüsünün içeriğinin yazılacağı yer. NULL olamaz ve yazılabilir olmalıdır. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Bu EMF görüntüsünü, içeriğini serbest bırakarak ve çoğunu
metod ve özelliklerini çalışmaz hâle getirir


