---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Toplu HTML belgelerinin MHTML MIME kapsüllemesini oluşturmak ve kaydetmek için özel seçenekler belirtmeye olanak tanır"
type: docs
weight: 26
url: /tr/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

MHTML (Toplu HTML belgelerinin MIME kapsüllemesi) belgelerini oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | MHTML belgelerinde bulunan kaynaklara (görseller, yazı tipleri, CSS) referans vermek için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | MHTML belgelerinde bulunan kaynaklara (görseller, yazı tipleri, CSS) referans vermek için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Yerleşik ve özel belge özelliklerinin MHTML'e aktarılıp aktarılmayacağını belirtir. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Yerleşik ve özel belge özelliklerinin MHTML'e aktarılıp aktarılmayacağını belirtir. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | Dil bilgilerinin MHTML'e aktarılıp aktarılmayacağını belirtir. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | Dil bilgilerinin MHTML'e aktarılıp aktarılmayacağını belirtir. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


MHTML belgelerinde bulunan kaynaklara (görseller, yazı tipleri, CSS) referans vermek için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***


Varsayılan olarak, MHTML belgelerindeki kaynaklar dosya adıyla (örneğin, "image.png") referans alınır ve bu adlar MIME bölümlerinin "Content-Location" başlıklarıyla eşleştirilir. Bu seçenek, kaynak dosyalara referansların CID (Content-ID) URL'leri (örneğin, "cid:image.png") olarak yazıldığı ve "Content-ID" başlıklarıyla eşleştirildiği alternatif bir yöntemi etkinleştirir.


Teorik olarak, iki referans yöntemi arasında fark olmamalı ve her ikisi de herhangi bir tarayıcı ya da e-posta istemcisinde sorunsuz çalışmalıdır. Ancak pratikte, bazı istemciler dosya adıyla kaynakları almada başarısız olur. Tarayıcınız veya e-posta istemciniz bir MTHML belgesine dahil edilen kaynakları (görselleri göstermez veya CSS stillerini yüklemez) yüklemeyi reddederse, belgeyi CID URL'leriyle dışa aktarmayı deneyin.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


MHTML belgelerinde bulunan kaynaklara (görseller, yazı tipleri, CSS) referans vermek için CID (Content-ID) URL'lerinin kullanılıp kullanılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***


Varsayılan olarak, MHTML belgelerindeki kaynaklar dosya adıyla (örneğin, "image.png") referans alınır ve bu adlar MIME bölümlerinin "Content-Location" başlıklarıyla eşleştirilir. Bu seçenek, kaynak dosyalara referansların CID (Content-ID) URL'leri (örneğin, "cid:image.png") olarak yazıldığı ve "Content-ID" başlıklarıyla eşleştirildiği alternatif bir yöntemi etkinleştirir.


Teorik olarak, iki referans yöntemi arasında fark olmamalı ve her ikisi de herhangi bir tarayıcı ya da e-posta istemcisinde sorunsuz çalışmalıdır. Ancak pratikte, bazı istemciler dosya adıyla kaynakları almada başarısız olur. Tarayıcınız veya e-posta istemciniz bir MTHML belgesine dahil edilen kaynakları (görselleri göstermez veya CSS stillerini yüklemez) yüklemeyi reddederse, belgeyi CID URL'leriyle dışa aktarmayı deneyin.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Yerleşik ve özel belge özelliklerinin MHTML'e aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Yerleşik ve özel belge özelliklerinin MHTML'e aktarılıp aktarılmayacağını belirtir. Varsayılan değer
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


Dil bilgilerinin MHTML'e aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***

Bu özellik **true** olarak ayarlandığında, GroupDocs.Editor, dili belirten belge öğelerinde **lang** HTML-attribute'yi üretir. Bu, dil ile ilgili anlamsal bilgilerin korunması için gerekebilir.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


Dil bilgilerinin MHTML'e aktarılıp aktarılmayacağını belirtir. Varsayılan değer
false
.

<br />

*** ** * ** ***

Bu özellik **true** olarak ayarlandığında, GroupDocs.Editor, dili belirten belge öğelerinde **lang** HTML-attribute'yi üretir. Bu, dil ile ilgili anlamsal bilgilerin korunması için gerekebilir.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

