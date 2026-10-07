---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Sabit ad, boyutlar, en-boy oranı, tip, boyut ve içerik ile desteklenen herhangi bir raster görüntünün temel sınıfı."
type: docs
weight: 15
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

Sabit ad, boyutlar, en-boy oranı ile desteklenen herhangi bir raster görüntünün temel sınıfı
oran, tip, boyut ve içerik.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Disposed](#Disposed) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Bu raster görüntünün adını döndürür. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu raster görüntünün doğru dosya adını döndürür, ad ve |
uzantı.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Bu raster görüntünün lineer boyutlarını (genişlik ve yükseklik) döndürür. |
|
|  | [getAspectRatio()](#getAspectRatio--) | Bu görüntünün en-boy oranını genişlik-yükseklik ilişkisi olarak döndürür. |
|
|  | [getLength()](#getLength--) | Bu raster görüntü dosyasının uzunluğunu bayt cinsinden döndürür. |
|
|  | [getByteContent()](#getByteContent--) | Bu raster görüntünün içeriğini bayt akışı olarak döndürür. |
|
|  | [getTextContent()](#getTextContent--) | Bu raster görüntünün içeriğini base64 kodlu dize olarak döndürür. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Bu raster görüntüyü belirtilen dosyaya kaydeder. |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
|
|  | [dispose()](#dispose--) | Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntemi |
ve özellikleri çalışmaz hâle getirir
|
|  | [isDisposed()](#isDisposed--) | Bu raster görüntünün serbest bırakılıp bırakılmadığını belirler |
|
|  | [getType()](#getType--) | Uygulamada tür, raster tipine ilişkin bilgiyi döndürmelidir |
görüntü
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Bu raster görüntünün adını döndürür. Genellikle dosya adı içermez
uzantı ve teorik olarak dosya adından farklı olabilir.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Bu raster görüntünün doğru dosya adını döndürür, ad ve
uzantı. Teorik olarak isimden farklı olabilir.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Bu raster görüntünün lineer boyutlarını (genişlik ve yükseklik) döndürür.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Bu görüntünün en-boy oranını genişlik-yükseklik ilişkisi olarak döndürür.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


Bu raster görüntü dosyasının uzunluğunu bayt cinsinden döndürür.


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


Bu raster görüntünün içeriğini bayt akışı olarak döndürür.


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


Bu raster görüntünün içeriğini base64 kodlu dize olarak döndürür.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


Bu raster görüntüyü belirtilen dosyaya kaydeder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | Oluşturulacak veya yeniden yazılacak dosyanın tam yolu |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Bu örneği belirtilen referans eşitliğiyle kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Diğer IHtmlResource türevi |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

### dispose() {#dispose--}
```
public final void dispose()
```


Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntemi
ve özellikleri çalışmaz hâle getirir


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


Bu raster görüntünün serbest bırakılıp bırakılmadığını belirler


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


Uygulamada tür, raster tipine ilişkin bilgiyi döndürmelidir
görüntü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
