---
title: "PdfSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "PDF Taşınabilir Belge Formatı belgelerini oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir."
type: docs
weight: 31
url: /tr/java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

Oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir PDF (Taşınabilir
Belge Formatı) belgeler

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Şifre, oluşturulan PDF belgesine kullanıcı şifresi olarak uygulanacak, açmak için gereklidir. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifre, oluşturulan PDF belgesine kullanıcı şifresi olarak uygulanacak, açmak için gereklidir. |
|
|  | [getCompliance()](#getCompliance--) | Çıktı belgeleri için PDF standartları uyumluluk seviyesini belirtir. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | Çıktı belgeleri için PDF standartları uyumluluk seviyesini belirtir. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Orijinal belgede kullanılan font kaynaklarını sonuç PDF belgesine gömmekten sorumludur. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Orijinal belgede kullanılan font kaynaklarını sonuç PDF belgesine gömmekten sorumludur. |
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


Şifre, oluşturulan PDF belgesine kullanıcı şifresi olarak uygulanacak, açmak için gereklidir.
NULL veya boş ise belgeye şifre uygulanmaz. Aksi takdirde belge RC4 (128 bit anahtar uzunluğu) ile şifrelenir.
Varsayılan olarak NULL \u2014 şifre uygulanmaz.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifre, oluşturulan PDF belgesine kullanıcı şifresi olarak uygulanacak, açmak için gereklidir.
NULL veya boş ise belgeye şifre uygulanmaz. Aksi takdirde belge RC4 (128 bit anahtar uzunluğu) ile şifrelenir.
Varsayılan olarak NULL \u2014 şifre uygulanmaz.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Çıktı belgeleri için PDF standartları uyumluluk seviyesini belirtir. Varsayılan değer PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Çıktı belgeleri için PDF standartları uyumluluk seviyesini belirtir. Varsayılan değer PdfCompliance.Pdf17.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Orijinal belgede kullanılan font kaynaklarını sonuç PDF belgesine gömmekten sorumludur. Varsayılan olarak hiçbir font gömülmez (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Orijinal belgede kullanılan font kaynaklarını sonuç PDF belgesine gömmekten sorumludur. Varsayılan olarak hiçbir font gömülmez (NotEmbed).


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

