---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Ayırıcı (delimiter) kullanan metin tabanlı Elektronik Tablo belgelerini (CSV, Tab tabanlı vb.) yükleme seçenekleri"
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Metin tabanlı Elektronik Tablo belgelerini (CSV, Tab tabanlı vb.) yükleme seçenekleri,
ayırıcı (delimiter) kullanan


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Sınırlı metin için zorunlu olan seçenek sınıfının bir örneğini oluşturur |
ayırıcı (sınırlayıcı)
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Metin tabanlı için bir dize ayırıcı (sınırlayıcı) belirtmeye izin verir |
Elektronik Tablo Belgeleri
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Metin tabanlı için bir dize ayırıcı (sınırlayıcı) belirtmeye izin verir |
Elektronik Tablo Belgeleri
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar |
belge tarih verisine dönüştürülür.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar |
belge tarih verisine dönüştürülür.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar |
belge sayısal veriye dönüştürülür.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar |
belge sayısal veriye dönüştürülür.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Ardışık ayırıcıların tek olarak ele alınıp alınmayacağını tanımlar. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Ardışık ayırıcıların tek olarak ele alınıp alınmayacağını tanımlar. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir, |
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer
yanda bellek kullanımını azaltır.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir, |
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer
yanda bellek kullanımını azaltır.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Sınırlı metin için zorunlu olan seçenek sınıfının bir örneğini oluşturur
ayırıcı (sınırlayıcı)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ayırıcı | java.lang.String | NULL veya boş olamayan zorunlu ayırıcı (delimiter). |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Metin tabanlı için bir dize ayırıcı (sınırlayıcı) belirtmeye izin verir
Elektronik Tablo Belgeleri


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Metin tabanlı için bir dize ayırıcı (sınırlayıcı) belirtmeye izin verir
Elektronik Tablo Belgeleri


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar
belge tarih verisine dönüştürülür. Varsayılan değer false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar
belge tarih verisine dönüştürülür. Varsayılan değer false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar
belge sayısal veriye dönüştürülür. Varsayılan değer false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Metin tabanlı dizede olup olmadığını gösteren bir değeri alır veya ayarlar
belge sayısal veriye dönüştürülür. Varsayılan değer false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Ardışık sınırlayıcıların tek bir sınırlayıcı gibi ele alınması gerekip gerekmediğini tanımlar. Tarafından
varsayılan false'tur.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Ardışık sınırlayıcıların tek bir sınırlayıcı gibi ele alınması gerekip gerekmediğini tanımlar. Tarafından
varsayılan false'tur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir,
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer
yanda bellek kullanımını azaltır. Büyük belgeleri işlerken faydalıdır ve
OutOfMemoryException ile karşılaşıldığında. Varsayılan false'tur (bellek optimizasyonu
daha iyi performans için devre dışı bırakılmıştır).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir,
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer
yanda bellek kullanımını azaltır. Büyük belgeleri işlerken faydalıdır ve
OutOfMemoryException ile karşılaşıldığında. Varsayılan false'tur (bellek optimizasyonu
daha iyi performans için devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

