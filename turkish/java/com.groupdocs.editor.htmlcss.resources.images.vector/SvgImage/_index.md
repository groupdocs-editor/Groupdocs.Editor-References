---
title: "SvgImage"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "SVG Scalable Vector Graphics formatında bir vektör görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 12
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

SVG (Scalable Vector Graphics) formatında bir vektör görüntüyü, onunla birlikte temsil eder
meta verileri ve ek yöntemleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | İçeriği normal dize olarak temsil eden yeni bir SvgImage örneği oluşturur, |
ve belirtilen adla
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | İçeriği bayt akışı olarak temsil eden yeni bir SvgImage örneği oluşturur, |
ve belirtilen adla
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | Belirtilen metinsel XML uyumlu içeriğin yüzey kontrolünü gerçekleştirir |
bir SVG görüntüsünü temsil eder
|
|  | [getType()](#getType--) | ImageType.Svg değerini döndürür |
|
|  | [getByteContent()](#getByteContent--) | Bu SVG görüntüsünün içeriğini ikili akış olarak döndürür |
|
|  | [getTextContent()](#getTextContent--) | Bu SVG görüntüsünün içeriğini düz metin (XML formatında) olarak döndürür |
|
|  | [getXmlContent()](#getXmlContent--) | Bu SVG görüntüsünün içeriğini orijinal XML uyumlu biçiminde döndürür |
metinsel biçim
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu SVG görüntüsünü dosyaya kaydeder |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Bu vektör SVG görüntüsünü raster PNG görüntüsüne kaydeder |
|
|  | [dispose()](#dispose--) | Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntemi |
ve özellikleri çalışmaz hâle getirir
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


İçeriği normal dize olarak temsil eden yeni bir SvgImage örneği oluşturur,
ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | SVG görüntüsünün adı. Boş, null veya yalnızca boşluk olamaz. |
|
|  | içerik | java.lang.String | SVG görüntüsünün geçerli XML uyumlu içeriğini içeren normal bir dize olarak içerik. Boş, null veya yalnızca boşluk olamaz. SVG içeriği değilse, istisna fırlatılacaktır. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


İçeriği bayt akışı olarak temsil eden yeni bir SvgImage örneği oluşturur,
ve belirtilen adla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | SVG görüntüsünün adı. Boş, null veya yalnızca boşluk olamaz. |
|
|  | binaryContent | java.io.InputStream | İçerik bayt akışı olarak. Okuma, orijinal konumdan başlar. Null olamaz. Okunabilir ve aranabilir olmalıdır. Bu örnek serbest bırakılırsa, bu akış da serbest bırakılacaktır. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


Belirtilen metinsel XML uyumlu içeriğin yüzey kontrolünü gerçekleştirir
bir SVG görüntüsünü temsil eder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | içerik | java.lang.String | SVG görüntüsünün XML içeriği basit metin olarak, base64 kodlu içerik değildir |
|

**Returns:**
boolean - Belirtilen dize ilk bakışta geçerli bir SVG olarak kabul edilebiliyorsa True, kesinlikle SVG değilse false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Svg değerini döndürür


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Bu SVG görüntüsünün içeriğini ikili akış olarak döndürür


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


Bu SVG görüntüsünün içeriğini düz metin (XML formatında) olarak döndürür


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


Bu SVG görüntüsünün içeriğini orijinal XML uyumlu biçiminde döndürür
metinsel biçim


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


Bu SVG görüntüsünü dosyaya kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Bu SVG görüntüsünün içeriğiyle oluşturulacak (var değilse) veya üzerine yazılacak (var ise) dosyanın tam yolu |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


Bu vektör SVG görüntüsünü raster PNG görüntüsüne kaydeder


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Çıktı akışı, PNG görüntüsünün içeriğinin yazılacağı yer. NULL olamaz ve yazılabilir olmalıdır. |
|

### dispose() {#dispose--}
```
public void dispose()
```


Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntemi
ve özellikleri çalışmaz hâle getirir


