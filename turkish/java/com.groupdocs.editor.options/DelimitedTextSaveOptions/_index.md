---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Ayırıcı kullanan CSV, Tab tabanlı vb. metin tabanlı Elektronik Tablo belgeleri oluşturmak ve kaydetmek için seçenekler içerir"
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Metin tabanlı Elektronik Tablo belgeleri oluşturma ve kaydetme seçeneklerini içerir
(CSV, Tab tabanlı vb.), ayırıcı (delimiter) kullanan


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Bu parametresiz yapıcı, varsayılan ayırıcı olarak noktalı virgül (;) kullanılan DelimitedTextSaveOptions sınıfının yeni bir örneğini oluşturur (daha sonra değiştirilebilir |
Ayırıcı
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) özelliği)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Ayırıcı metin için zorunlu olan seçenek sınıfının bir örneğini oluşturur |
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
|  | [getEncoding()](#getEncoding--) | Metin tabanlı Elektronik Tablo belgesi için bir kodlama ayarlamaya izin verir. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin tabanlı Elektronik Tablo belgesi için bir kodlama ayarlamaya izin verir. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Başlangıçtaki boş satır ve sütunların, şu şekilde kesilip kesilmeyeceğini gösterir |
MS Excel'in yaptığı gibi
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Başlangıçtaki boş satır ve sütunların, şu şekilde kesilip kesilmeyeceğini gösterir |
MS Excel'in yaptığı gibi
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Boş satır için ayırıcıların çıktılanıp çıktılanmayacağını gösterir. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Boş satır için ayırıcıların çıktılanıp çıktılanmayacağını gösterir. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Bu parametresiz yapıcı, varsayılan ayırıcı olarak noktalı virgül (;) kullanılan DelimitedTextSaveOptions sınıfının yeni bir örneğini oluşturur (daha sonra değiştirilebilir
Ayırıcı
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) özelliği)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Ayırıcı metin için zorunlu olan seçenek sınıfının bir örneğini oluşturur
ayırıcı (delimiter)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ayırıcı | java.lang.String | Metin tabanlı Elektronik Tablo belgeleri için dize ayırıcı (delimiter) |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Metin tabanlı için bir dize ayırıcı (delimiter) belirtmeye izin verir
Spreadsheet belgeleri


**Returns:**
java.lang.String -
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

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin tabanlı Elektronik Tablo belgesi için bir kodlama ayarlamaya izin verir. By
varsayılan (ve belirtilmezse) UTF8'dir.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Metin tabanlı Elektronik Tablo belgesi için bir kodlama ayarlamaya izin verir. By
varsayılan (ve belirtilmezse) UTF8'dir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Başlangıçtaki boş satır ve sütunların, şu şekilde kesilip kesilmeyeceğini gösterir
MS Excel'in yaptığı gibi


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Başlangıçtaki boş satır ve sütunların, şu şekilde kesilip kesilmeyeceğini gösterir
MS Excel'in yaptığı gibi


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Boş satır için ayırıcıların çıktılanıp çıktılanmayacağını gösterir. Varsayılan
değeri false'tur, bu da boş satırın içeriğinin boş olacağı anlamına gelir.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Boş satır için ayırıcıların çıktılanıp çıktılanmayacağını gösterir. Varsayılan
değeri false'tur, bu da boş satırın içeriğinin boş olacağı anlamına gelir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

