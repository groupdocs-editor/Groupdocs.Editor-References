---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Düzenlendikten sonra WordProcessing uyumlu belgeleri oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir"
type: docs
weight: 48
url: /tr/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Oluşturma ve kaydetme için özel seçenekler belirtmeye izin verir
WordProcessing uyumlu belgeler, düzenlendikten sonra


*** ** * ** ***

WordProcessingSaveOptions, düzenlenmiş belge içeriğini içeren bir EditableDocument sınıfı örneği bulunduğunda ve bu içeriğin WordProcessing formatında yeni bir belgeye kaydedilmesi gerektiğinde uygulanır.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Bu parametresiz yapıcı, DOCX çıktı formatı ile bir WordProcessingSaveOptions yeni örneği oluşturur (daha sonra şu şekilde değiştirilebilir |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) özelliği)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Belirtilen ile bir WordProcessingSaveOptions yeni örneği oluşturur |
zorunlu WordProcessing çıktı formatı, diğer tüm parametreler ise
default
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Kaydetme sırasında kullanılacak sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir |
belge.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Kaydetme sırasında kullanılacak sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir |
belge.
|
|  | [getPassword()](#getPassword--) | Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu |
oluşturulan WordProcessing belgesini kodlamak için kullanılacaktır.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu |
oluşturulan WordProcessing belgesini kodlamak için kullanılacaktır.
|
|  | [getOutputFormat()](#getOutputFormat--) | Kaydetme için kullanılacak bir WordProcessing formatı belirtmeye izin verir |
belgeyi
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Kaydetme için kullanılacak bir WordProcessing formatı belirtmeye izin verir |
belgeyi
|
|  | [getLocale()](#getLocale--) | WordProcessing için varsayılan yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir |
belge, oluşturulması sırasında uygulanacaktır.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | WordProcessing için varsayılan yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir |
belge, oluşturulması sırasında uygulanacaktır.
|
|  | [getLocaleBi()](#getLocaleBi--) | WordProcessing belgesi için yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir |
RTL (right-to-left) metin için, bu
oluşturulması.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | WordProcessing belgesi için yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir |
RTL (right-to-left) metin için, bu
oluşturulması.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | WordProcessing belgesi için yerel ayarı (dili) geçersiz kılmaya izin verir |
Doğu Asya metni için, bu belge oluşturulurken uygulanacaktır.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | WordProcessing belgesi için yerel ayarı (dili) geçersiz kılmaya izin verir |
Doğu Asya metni için, bu belge oluşturulurken uygulanacaktır.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Belge oluşturma sırasında bellek optimizasyon mekanizmalarını etkinleştirir |
HTML'den, bellek kullanımını azaltmanın bir maliyeti olarak performansı düşürür.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Belge oluşturma sırasında bellek optimizasyon mekanizmalarını etkinleştirir |
HTML'den, bellek kullanımını azaltmanın bir maliyeti olarak performansı düşürür.
|
|  | [getProtection()](#getProtection--) | Belge koruma seçeneklerini kontrol etmeye ve uygulamaya izin verir |
herhangi bir formatta WordProcessing belgesi, belge
korumasını.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Belge koruma seçeneklerini kontrol etmeye ve uygulamaya izin verir |
herhangi bir formatta WordProcessing belgesi, belge
korumasını.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Çıktı WordProcessing içine yazı tipi kaynaklarını gömmekten sorumludur |
belge.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Çıktı WordProcessing içine yazı tipi kaynaklarını gömmekten sorumludur |
belge.
|
|  | [deepClone()](#deepClone--) | Bu örneğin tam bir kopyasını oluşturur ve döndürür |
WordProcessingSaveOptions sınıfı
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Bu parametresiz yapıcı, DOCX çıktı formatı ile bir WordProcessingSaveOptions yeni örneği oluşturur (daha sonra şu şekilde değiştirilebilir
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) özelliği)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Belirtilen ile bir WordProcessingSaveOptions yeni örneği oluşturur
zorunlu WordProcessing çıktı formatı, diğer tüm parametreler ise
default


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Zorunlu çıktı formatı, WordProcessing belgesinin kaydedileceği format |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Kaydetme sırasında kullanılacak sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir
belge. Orijinal belge sayfalama modunda açıldıysa ve düzenlendiyse
modunda, bu seçenek de etkinleştirilmelidir. Varsayılan olarak devre dışıdır.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Kaydetme sırasında kullanılacak sayfalama özelliğini etkinleştirmeye veya devre dışı bırakmaya izin verir
belge. Orijinal belge sayfalama modunda açıldıysa ve düzenlendiyse
modunda, bu seçenek de etkinleştirilmelidir. Varsayılan olarak devre dışıdır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu
oluşturulan WordProcessing belgesini kodlamak için kullanılır. NULL veya
parolayı kaldırmak (temizlemek) için boş dize.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreyi belirtmeye, değiştirmeye, almaya veya kaldırmaya izin verir, bu
oluşturulan WordProcessing belgesini kodlamak için kullanılır. NULL veya
parolayı kaldırmak (temizlemek) için boş dize.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Kaydetme için kullanılacak bir WordProcessing formatı belirtmeye izin verir
belgeyi


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Kaydetme için kullanılacak bir WordProcessing formatı belirtmeye izin verir
belgeyi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


WordProcessing için varsayılan yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir
belge, oluşturulması sırasında uygulanacak. Belirtilmediğinde
belirtilirse (varsayılan değer), MS Word (veya başka bir program) algılayacaktır (veya
seçer) belge yerel ayarını kendi ayarlarına veya diğer
faktörlere.


*** ** * ** ***

Bu seçenek, belirtilen yerel ayarı belgedeki tüm metne zorla uygular. Belge, farklı dillerde yazılmış farklı metin bölümleri içeriyorsa kullanmayın.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


WordProcessing için varsayılan yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir
belge, oluşturulması sırasında uygulanacak. Belirtilmediğinde
belirtilirse (varsayılan değer), MS Word (veya başka bir program) algılayacaktır (veya
seçer) belge yerel ayarını kendi ayarlarına veya diğer
faktörlere.

*** ** * ** ***


Bu seçenek, belirtilen yerel ayarı tüm metne zorla uygular
belgede. Belge, farklı bölümler içeriyorsa kullanmayın
metin, farklı dillerde yazılmışsa.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


WordProcessing belgesi için yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir
RTL (right-to-left) metin için, bu
oluşturulması. Belirtilmediğinde (varsayılan değer), MS Word (veya başka
program) belge RTL yerel ayarını kendi
ayarlarına veya diğer faktörlere göre

*** ** * ** ***


Bu seçenek, belirtilen yerel ayarı tüm RTL metne zorla uygular
belgede. Belge, farklı bölümler içeriyorsa kullanmayın
metin, farklı dillerde yazılmışsa.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


WordProcessing belgesi için yerel ayarı (dili) geçersiz kılacak şekilde ayarlamaya izin verir
RTL (right-to-left) metin için, bu
oluşturulması. Belirtilmediğinde (varsayılan değer), MS Word (veya başka
program) belge RTL yerel ayarını kendi
ayarlarına veya diğer faktörlere göre

*** ** * ** ***


Bu seçenek, belirtilen yerel ayarı tüm RTL metne zorla uygular
belgede. Belge, farklı bölümler içeriyorsa kullanmayın
metin, farklı dillerde yazılmışsa.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


WordProcessing belgesi için yerel ayarı (dili) geçersiz kılmaya izin verir
Doğu Asya metni için, oluşturulması sırasında uygulanacak. Belirtilmediğinde
belirtilmezse (varsayılan değer), MS Word (veya başka bir program) algılayacaktır
(veya seçer) belge Doğu Asya yerel ayarını kendi ayarlarına göre
veya diğer faktörler.

*** ** * ** ***


Bu seçenek, belirtilen yerel ayarı zorla genel olarak uygular
Belgedeki Doğu Asya metni. Belge içeriyorsa kullanmayın
farklı dillerde yazılmış metnin farklı bölümleri
diller.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


WordProcessing belgesi için yerel ayarı (dili) geçersiz kılmaya izin verir
Doğu Asya metni için, oluşturulması sırasında uygulanacak. Belirtilmediğinde
belirtilmezse (varsayılan değer), MS Word (veya başka bir program) algılayacaktır
(veya seçer) belge Doğu Asya yerel ayarını kendi ayarlarına göre
veya diğer faktörler.

*** ** * ** ***


Bu seçenek, belirtilen yerel ayarı zorla genel olarak uygular
Belgedeki Doğu Asya metni. Belge içeriyorsa kullanmayın
farklı dillerde yazılmış metnin farklı bölümleri
diller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Belge oluşturma sırasında bellek optimizasyon mekanizmalarını etkinleştirir
HTML'den, bellek kullanımını azaltmanın bir maliyeti olarak performansı düşürür.
Bu seçeneği true olarak ayarlamak, bellek tüketimini önemli ölçüde azaltabilir
büyük belgeler oluşturulurken, daha yavaş kaydetme süresi pahasına.
Varsayılan false'tur (daha iyi
performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Belge oluşturma sırasında bellek optimizasyon mekanizmalarını etkinleştirir
HTML'den, bellek kullanımını azaltmanın bir maliyeti olarak performansı düşürür.
Bu seçeneği true olarak ayarlamak, bellek tüketimini önemli ölçüde azaltabilir
büyük belgeler oluşturulurken, daha yavaş kaydetme süresi pahasına.
Varsayılan false'tur (daha iyi
performans için bellek optimizasyonu devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Belge koruma seçeneklerini kontrol etmeye ve uygulamaya izin verir
herhangi bir formatta WordProcessing belgesi, belge
koruma. Varsayılan olarak NULL'dur - belge koruması kullanılmayacaktır.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Belge koruma seçeneklerini kontrol etmeye ve uygulamaya izin verir
herhangi bir formatta WordProcessing belgesi, belge
koruma. Varsayılan olarak NULL'dur - belge koruması kullanılmayacaktır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Çıktı WordProcessing içine yazı tipi kaynaklarını gömmekten sorumludur
belge. Varsayılan olarak hiçbir yazı tipi gömülmez (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Çıktı WordProcessing içine yazı tipi kaynaklarını gömmekten sorumludur
belge. Varsayılan olarak hiçbir yazı tipi gömülmez (NotEmbed).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Bu örneğin tam bir kopyasını oluşturur ve döndürür
WordProcessingSaveOptions sınıfı


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

