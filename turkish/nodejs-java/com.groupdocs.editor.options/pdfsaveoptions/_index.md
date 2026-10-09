---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "PDF Taşınabilir Belge Formatı belgelerini oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 31
url: /tr/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

PDF (Taşınabilir
Belge Formatı) belgeleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Açmak için gerekli olan kullanıcı şifresi olarak oluşturulan PDF belgesine uygulanacak şifre. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Açmak için gerekli olan kullanıcı şifresi olarak oluşturulan PDF belgesine uygulanacak şifre. |
|
|  | [getCompliance()](#getCompliance--) | Çıktı belgeleri için PDF standartları uyumluluk seviyesini belirtir. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Çıktı belgeleri için PDF standartları uyumluluk seviyesini belirtir. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Orijinal belgede kullanılan yazı tipi kaynaklarını sonuç PDF belgesine gömmekten sorumludur. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Orijinal belgede kullanılan yazı tipi kaynaklarını sonuç PDF belgesine gömmekten sorumludur. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Açmak için gerekli olan kullanıcı şifresi olarak oluşturulan PDF belgesine uygulanacak şifre.
If NULL or empty, no password will be applied to the document. Otherwise, document will be encrypted with RC4 (key length of 128 bit).
Varsayılan olarak NULL \\u2014 şifre uygulanmaz.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Açmak için gerekli olan kullanıcı şifresi olarak oluşturulan PDF belgesine uygulanacak şifre.
If NULL or empty, no password will be applied to the document. Otherwise, document will be encrypted with RC4 (key length of 128 bit).
Varsayılan olarak NULL \\u2014 şifre uygulanmaz.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Specifies the PDF standards compliance level for output documents. Default is PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Specifies the PDF standards compliance level for output documents. Default is PdfCompliance.Pdf17.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsible for embedding font resources into resultant PDF document, which are used in the original document. By default doesn't embed any fonts (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsible for embedding font resources into resultant PDF document, which are used in the original document. By default doesn't embed any fonts (NotEmbed).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir.
Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken daha yavaş kaydetme süresi pahasına bellek tüketimini önemli ölçüde azaltabilir.
Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML'den belge oluşturulurken bellek kullanımını azaltma maliyeti olarak performansı düşüren bellek optimizasyon mekanizmalarını etkinleştirir.
Bu seçeneği true olarak ayarlamak, büyük belgeler oluşturulurken daha yavaş kaydetme süresi pahasına bellek tüketimini önemli ölçüde azaltabilir.
Varsayılan değer false'tur (daha iyi performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

