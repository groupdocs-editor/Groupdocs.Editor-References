---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Metin tabanlı Spreadsheet belgelerini (CSV, Tab tabanlı vb.) yüklemek için seçenekler, ayırıcı kullanan"
type: docs
weight: 10
url: /tr/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Metin tabanlı Spreadsheet belgelerini (CSV, Tab tabanlı vb.) yüklemek için seçenekler,
ayırıcı (delimiter) kullanan


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Ayırıcı metin için zorunlu olan seçenek sınıfının bir örneğini oluşturur |
ayırıcı (delimiter)
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Metin tabanlı için bir dize ayırıcı (delimiter) belirtmeye izin verir |
Spreadsheet belgeleri
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Metin tabanlı için bir dize ayırıcı (delimiter) belirtmeye izin verir |
Spreadsheet belgeleri
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Metin tabanlı içindeki dizeyin |
belge tarih verisine dönüştürülür.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Metin tabanlı içindeki dizeyin |
belge tarih verisine dönüştürülür.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Metin tabanlı içindeki dizeyin |
belge sayısal veriye dönüştürülür.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Metin tabanlı içindeki dizeyin |
belge sayısal veriye dönüştürülür.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Ardışık ayırıcıların tek bir ayırıcı olarak ele alınıp alınmayacağını tanımlar. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Ardışık ayırıcıların tek bir ayırıcı olarak ele alınıp alınmayacağını tanımlar. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir, |
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir, |
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Ayırıcı metin için zorunlu olan seçenek sınıfının bir örneğini oluşturur
ayırıcı (delimiter)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ayırıcı | java.lang.String | NULL veya boş olamayan zorunlu ayırıcı (delimiter) |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Metin tabanlı için bir dize ayırıcı (delimiter) belirtmeye izin verir
Spreadsheet belgeleri


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Metin tabanlı için bir dize ayırıcı (delimiter) belirtmeye izin verir
Spreadsheet belgeleri


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Metin tabanlı içindeki dizeyin
belge tarih verisine dönüştürülür. Varsayılan değer false'tur.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Metin tabanlı içindeki dizeyin
belge tarih verisine dönüştürülür. Varsayılan değer false'tur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Metin tabanlı içindeki dizeyin
belge sayısal veriye dönüştürülür. Varsayılan değer false'tur.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Metin tabanlı içindeki dizeyin
belge sayısal veriye dönüştürülür. Varsayılan değer false'tur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Ardışık ayırıcıların tek bir ayırıcı gibi ele alınması gerektiğini tanımlar. By
varsayılan false'tur.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Ardışık ayırıcıların tek bir ayırıcı gibi ele alınması gerektiğini tanımlar. By
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
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt. Büyük belgeler işlenirken faydalıdır ve
OutOfMemoryException ile karşılaşıldığında. Varsayılan değer false'tur (bellek optimizasyonu
daha iyi performans için devre dışı bırakılmıştır).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Girdi belge işleme sırasında bellek optimizasyon mekanizmalarını etkinleştirir,
bu, bazı özel durumlarda performansı düşürebilir, ancak diğer yandan
elle bellek kullanımını azalt. Büyük belgeler işlenirken faydalıdır ve
OutOfMemoryException ile karşılaşıldığında. Varsayılan değer false'tur (bellek optimizasyonu
daha iyi performans için devre dışı bırakılmıştır).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

