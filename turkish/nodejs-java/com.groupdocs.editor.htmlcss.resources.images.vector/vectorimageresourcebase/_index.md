---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Desteklenen herhangi bir vektör görüntü için temel sınıf."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

Desteklenen herhangi bir vektör görüntü için temel sınıf.

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
|  | [getName()](#getName--) | Bu vektör görüntünün adını döndürür. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | Bu vektör görüntünün doğru dosya adını döndürür, ad ve |
uzantı.
|
|  | [getAspectRatio()](#getAspectRatio--) | Bu vektör görüntünün en‑boy oranını döndürür |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Bu vektör görüntünün lineer boyutlarını (genişlik ve yükseklik) döndürür |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | Bu örneği belirtilen nesneyle referans eşitliği açısından denetler. |
|
|  | [isDisposed()](#isDisposed--) | Bu raster görüntünün serbest bırakılıp bırakılmadığını belirler |
|
|  | [getType()](#getType--) | Uygulama sırasında tür, vektörün tipine ilişkin bilgiyi döndürmelidir |
görüntü
|
|  | [getByteContent()](#getByteContent--) | Uygulama sırasında tür, bu vektör görüntünün içeriğini bayt olarak döndürmelidir |
akış
|
|  | [getTextContent()](#getTextContent--) | Uygulama sırasında tür, bu vektör görüntünün içeriğini metin olarak döndürmelidir |
form: görüntü tipine ilişkin XML'in base64 kodlu hali
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | Uygulama sırasında tür, bu görüntüyü belirtilen yol ile diske kaydetmelidir |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | Uygulama sırasında tür, mevcut vektör görüntüyü raster PNG'ye kaydetmelidir |
belirtilen bayt akışına biçimlendir
|
|  | [dispose()](#dispose--) | Uygulama sırasında tür, bu örneği serbest bırakmalıdır |
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


Bu vektör görüntünün adını döndürür. Genellikle dosya adı içermez
uzantı ve teorik olarak dosya adından farklı olabilir.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


Bu vektör görüntünün doğru dosya adını döndürür, ad ve
uzantı. Teorik olarak isimden farklı olabilir.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


Bu vektör görüntünün en‑boy oranını döndürür


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


Bu vektör görüntünün lineer boyutlarını (genişlik ve yükseklik) döndürür


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


Bu örneği belirtilen nesneyle referans eşitliği açısından denetler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | Vektör görüntünün diğer örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

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


Uygulama sırasında tür, vektörün tipine ilişkin bilgiyi döndürmelidir
görüntü


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


Uygulama sırasında tür, bu vektör görüntünün içeriğini bayt olarak döndürmelidir
akış


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


Uygulama sırasında tür, bu vektör görüntünün içeriğini metin olarak döndürmelidir
form: görüntü tipine ilişkin XML'in base64 kodlu hali


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


Uygulama sırasında tür, bu görüntüyü belirtilen yol ile diske kaydetmelidir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


Uygulama sırasında tür, mevcut vektör görüntüyü raster PNG'ye kaydetmelidir
belirtilen bayt akışına biçimlendir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | Bayt akışı, bu raster görüntünün PNG sürümünün depolanacağı yer. NULL olmamalı ve yazma desteklemelidir. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


Uygulama sırasında tür, bu örneği serbest bırakmalıdır


