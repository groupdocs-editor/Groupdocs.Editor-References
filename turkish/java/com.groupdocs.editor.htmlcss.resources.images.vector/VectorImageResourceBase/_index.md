---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Desteklenen herhangi bir vektör görüntü için temel sınıf"
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Desteklenen herhangi bir vektör görüntü için temel sınıf

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Disposed](#Disposed) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getName()](#getName--) | Bu vektör görüntüsünün adını döndürür. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu vektör görüntüsünün doğru dosya adını döndürür, bu ad isim ve |
uzantı.
|
|  | [getAspectRatio()](#getAspectRatio--) | Bu vektör görüntüsünün en-boy oranını döndürür |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Bu vektör görüntüsünün doğrusal boyutlarını (genişlik ve yükseklik) döndürür |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
|
|  | [isDisposed()](#isDisposed--) | Bu raster görüntünün serbest bırakılıp bırakılmadığını belirler |
|
|  | [getType()](#getType--) | Uygulayan tür, vektörün türü hakkında bilgi döndürmelidir |
görüntü
|
|  | [getByteContent()](#getByteContent--) | Uygulayan tür, bu vektör görüntüsünün içeriğini bayt olarak döndürmelidir |
stream
|
|  | [getTextContent()](#getTextContent--) | Uygulayan tür, bu vektör görüntüsünün içeriğini metin olarak döndürmelidir |
form: görüntü türüyle ilgili XML'in base64 kodlu hali
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Uygulayan tür, bu görüntüyü belirtilen yola disk üzerinde kaydetmelidir |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Uygulayan tür, mevcut vektör görüntüsünü raster PNG'ye kaydetmelidir |
belirtilen bayt akışına formatla
|
|  | [dispose()](#dispose--) | Uygulayan tür, bu örneği serbest bırakmalıdır |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


Bu vektör görüntüsünün adını döndürür. Genellikle dosya adı içermez
uzantı ve teorik olarak dosya adından farklı olabilir.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Bu vektör görüntüsünün doğru dosya adını döndürür, bu ad isim ve
uzantı. Teorik olarak isimden farklı olabilir.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Bu vektör görüntüsünün en-boy oranını döndürür


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Bu vektör görüntüsünün doğrusal boyutlarını (genişlik ve yükseklik) döndürür


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Bu örneği belirtilen referans eşitliğiyle kontrol eder.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Diğer vektör görüntüsü örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false.

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


Uygulayan tür, vektörün türü hakkında bilgi döndürmelidir
görüntü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Uygulayan tür, bu vektör görüntüsünün içeriğini bayt olarak döndürmelidir
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Uygulayan tür, bu vektör görüntüsünün içeriğini metin olarak döndürmelidir
form: görüntü türüyle ilgili XML'in base64 kodlu hali


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Uygulayan tür, bu görüntüyü belirtilen yola disk üzerinde kaydetmelidir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Uygulayan tür, mevcut vektör görüntüsünü raster PNG'ye kaydetmelidir
belirtilen bayt akışına formatla


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Bayt akışı, bu raster görüntünün PNG sürümünün depolanacağı yer. NULL olmamalı ve yazmayı desteklemelidir. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Uygulayan tür, bu örneği serbest bırakmalıdır


