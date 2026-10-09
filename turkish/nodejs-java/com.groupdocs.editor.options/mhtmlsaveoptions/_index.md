---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Toplu HTML belgelerinin MHTML MIME kapsüllemesini oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir"
type: docs
weight: 26
url: /tr/nodejs-java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

MHTML (HTML belgelerinin toplu MIME kapsüllemesi) belgelerini oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | MHTML belgelerine dahil edilen kaynakları (görüntüler, yazı tipleri, CSS) referanslamak için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | MHTML belgelerine dahil edilen kaynakları (görüntüler, yazı tipleri, CSS) referanslamak için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Yerleşik ve özel belge özelliklerinin MHTML'ye aktarılıp aktarılmayacağını belirtir. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Yerleşik ve özel belge özelliklerinin MHTML'ye aktarılıp aktarılmayacağını belirtir. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Dil bilgisinin MHTML'ye aktarılıp aktarılmayacağını belirtir. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Dil bilgisinin MHTML'ye aktarılıp aktarılmayacağını belirtir. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


MHTML belgelerine dahil edilen kaynakları (görüntüler, yazı tipleri, CSS) referanslamak için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***


Varsayılan olarak, MHTML belgelerindeki kaynaklar dosya adıyla (örneğin, "image.png") referanslanır ve bu adlar MIME parçalarının "Content-Location" başlıklarıyla eşleştirilir. Bu seçenek, kaynak dosya referanslarının CID (Content-ID) URL'leri (örneğin, "cid:image.png") olarak yazıldığı ve "Content-ID" başlıklarıyla eşleştirildiği alternatif bir yöntemi etkinleştirir.


Teorik olarak, iki referans yöntemi arasında fark olmamalı ve her ikisi de herhangi bir tarayıcı veya e-posta istemcisinde sorunsuz çalışmalıdır. Ancak pratikte, bazı istemciler kaynakları dosya adıyla almada başarısız olur. Tarayıcınız veya e-posta istemciniz bir MHTML belgesine dahil edilen kaynakları (görüntüleri göstermez veya CSS stillerini yüklemez) yüklemeyi reddederse, belgeyi CID URL'leriyle dışa aktarmayı deneyin.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


MHTML belgelerine dahil edilen kaynakları (görüntüler, yazı tipleri, CSS) referanslamak için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***


Varsayılan olarak, MHTML belgelerindeki kaynaklar dosya adıyla (örneğin, "image.png") referanslanır ve bu adlar MIME parçalarının "Content-Location" başlıklarıyla eşleştirilir. Bu seçenek, kaynak dosya referanslarının CID (Content-ID) URL'leri (örneğin, "cid:image.png") olarak yazıldığı ve "Content-ID" başlıklarıyla eşleştirildiği alternatif bir yöntemi etkinleştirir.


Teorik olarak, iki referans yöntemi arasında fark olmamalı ve her ikisi de herhangi bir tarayıcı veya e-posta istemcisinde sorunsuz çalışmalıdır. Ancak pratikte, bazı istemciler kaynakları dosya adıyla almada başarısız olur. Tarayıcınız veya e-posta istemciniz bir MHTML belgesine dahil edilen kaynakları (görüntüleri göstermez veya CSS stillerini yüklemez) yüklemeyi reddederse, belgeyi CID URL'leriyle dışa aktarmayı deneyin.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Yerleşik ve özel belge özelliklerinin MHTML'ye aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Yerleşik ve özel belge özelliklerinin MHTML'ye aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


Dil bilgisinin MHTML'ye aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***

Bu özellik true olarak ayarlandığında, GroupDocs.Editor, dili belirten belge öğelerinde lang HTML niteliğini üretir. Bu, dil ile ilgili anlamsallığı korumak için gerekebilir.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Dil bilgisinin MHTML'ye aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***

Bu özellik true olarak ayarlandığında, GroupDocs.Editor, dili belirten belge öğelerinde lang HTML niteliğini üretir. Bu, dil ile ilgili anlamsallığı korumak için gerekebilir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

