---
title: "DelimitedTextEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Opsi untuk memuat dokumen Spreadsheet berbasis teks CSV, berbasis Tab, dll. yang menggunakan pemisah delimiter"
type: docs
weight: 10
url: /id/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Opsi untuk memuat dokumen Spreadsheet berbasis teks (CSV, berbasis Tab, dll.),
yang menggunakan pemisah (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Membuat instance kelas opsi untuk teks berdelimiter dengan keharusan |
pemisah (delimiter)
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis |
dokumen Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis |
dokumen Spreadsheet
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis |
dokumen dikonversi menjadi data tanggal.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis |
dokumen dikonversi menjadi data tanggal.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis |
dokumen dikonversi menjadi data numerik.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis |
dokumen dikonversi menjadi data numerik.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Mendefinisikan apakah delimiter berurutan harus diperlakukan sebagai satu. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Mendefinisikan apakah delimiter berurutan harus diperlakukan sebagai satu. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input, |
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input, |
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Membuat instance kelas opsi untuk teks berdelimiter dengan keharusan
pemisah (delimiter)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pemisah | java.lang.String | Pemisor wajib (delimiter), yang tidak boleh NULL atau kosong |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis
dokumen Spreadsheet


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Mengizinkan menentukan pemisah string (delimiter) untuk teks berbasis
dokumen Spreadsheet


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis
dokumen diubah menjadi data tanggal. Default adalah false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis
dokumen diubah menjadi data tanggal. Default adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis
dokumen diubah menjadi data numerik. Default adalah false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Mendapatkan atau mengatur nilai yang menunjukkan apakah string dalam teks berbasis
dokumen diubah menjadi data numerik. Default adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Mendefinisikan apakah delimiter berurutan harus diperlakukan sebagai satu. By
default adalah false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Mendefinisikan apakah delimiter berurutan harus diperlakukan sebagai satu. By
default adalah false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input,
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual. Berguna saat memproses dokumen besar dan
menghadapi OutOfMemoryException. Default adalah false (optimisasi memori
dinonaktifkan demi kinerja yang lebih baik).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Mengaktifkan mekanisme optimasi memori selama pemrosesan dokumen input,
yang dapat menurunkan kinerja dalam beberapa kasus khusus, tetapi di sisi lain
menurunkan penggunaan memori secara manual. Berguna saat memproses dokumen besar dan
menghadapi OutOfMemoryException. Default adalah false (optimisasi memori
dinonaktifkan demi kinerja yang lebih baik).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

