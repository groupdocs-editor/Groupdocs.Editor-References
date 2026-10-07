---
title: "XmlEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Memungkinkan untuk menentukan opsi khusus untuk memuat dokumen XML eXtensible Markup Language dan mengonversinya ke HTML"
type: docs
weight: 51
url: /id/java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

Memungkinkan untuk menentukan opsi khusus untuk memuat XML (eXtensible Markup Language)
dokumen dan mengonversinya ke HTML

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Pengkodean karakter dokumen teks, yang akan diterapkan untuk |
pembukaan.
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Pengkodean karakter dokumen teks, yang akan diterapkan untuk |
pembukaan.
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | Memungkinkan mengaktifkan atau menonaktifkan mekanisme untuk memperbaiki struktur XML yang rusak. |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | Memungkinkan mengaktifkan atau menonaktifkan mekanisme untuk memperbaiki struktur XML yang rusak. |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | Memungkinkan mengaktifkan algoritma pengenalan URI |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | Memungkinkan mengaktifkan algoritma pengenalan URI |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | Memungkinkan mengaktifkan algoritma pengenalan untuk alamat email dalam atribut |
nilai
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | Memungkinkan mengaktifkan algoritma pengenalan untuk alamat email dalam atribut |
nilai
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | Memungkinkan mengaktifkan pemotongan spasi putih di akhir dalam inner-tag |
teks.
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | Memungkinkan mengaktifkan pemotongan spasi putih di akhir dalam inner-tag |
teks.
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | Memungkinkan menentukan jenis kutipan (tunggal atau ganda) untuk nilai atribut. |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | Memungkinkan menentukan jenis kutipan (tunggal atau ganda) untuk nilai atribut. |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | Memungkinkan menyesuaikan penyorotan XML, yang akan diterapkan pada struktur XML ketika ditampilkan dalam HTML. |
|
|  | [getFormatOptions()](#getFormatOptions--) | Memungkinkan menyesuaikan pemformatan XML, yang akan diterapkan pada struktur XML ketika ditampilkan dalam HTML. |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Pengkodean karakter dokumen teks, yang akan diterapkan untuk
pembukaan. Secara default bernilai null \\u2014 enkoding dokumen internal akan diterapkan.


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Pengkodean karakter dokumen teks, yang akan diterapkan untuk
pembukaan. Secara default bernilai null \\u2014 enkoding dokumen internal akan diterapkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


Memungkinkan mengaktifkan atau menonaktifkan mekanisme untuk memperbaiki struktur XML yang rusak.
Secara default dinonaktifkan (false).

*** ** * ** ***


Secara default hanya dokumen XML yang sah dan terbentuk dengan baik yang
dapat diterima. Ketika opsi ini diaktifkan, GroupDocs.Editor akan mencoba memperbaiki
struktur XML yang rusak jika memungkinkan.


**Returns:**
boolean
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


Memungkinkan mengaktifkan atau menonaktifkan mekanisme untuk memperbaiki struktur XML yang rusak.
Secara default dinonaktifkan (false).

*** ** * ** ***


Secara default hanya dokumen XML yang sah dan terbentuk dengan baik yang
dapat diterima. Ketika opsi ini diaktifkan, GroupDocs.Editor akan mencoba memperbaiki
struktur XML yang rusak jika memungkinkan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


Memungkinkan mengaktifkan algoritma pengenalan URI


**Returns:**
boolean
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


Memungkinkan mengaktifkan algoritma pengenalan URI


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


Memungkinkan mengaktifkan algoritma pengenalan untuk alamat email dalam atribut
nilai


**Returns:**
boolean
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


Memungkinkan mengaktifkan algoritma pengenalan untuk alamat email dalam atribut
nilai


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


Memungkinkan mengaktifkan pemotongan spasi putih di akhir dalam inner-tag
teks. Secara default dinonaktifkan (false) \\u2014 spasi putih di akhir akan
dipertahankan.


**Returns:**
boolean
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


Memungkinkan mengaktifkan pemotongan spasi putih di akhir dalam inner-tag
teks. Secara default dinonaktifkan (false) \\u2014 spasi putih di akhir akan
dipertahankan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


Memungkinkan menentukan jenis kutipan (tunggal atau ganda) untuk nilai atribut. Kutipan ganda adalah default.


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


Memungkinkan menentukan jenis kutipan (tunggal atau ganda) untuk nilai atribut. Kutipan ganda adalah default.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


Memungkinkan menyesuaikan penyorotan XML, yang akan diterapkan pada struktur XML ketika ditampilkan dalam HTML. Penyorotan default digunakan dan dapat disesuaikan. Tidak boleh null.


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


Memungkinkan menyesuaikan pemformatan XML, yang akan diterapkan pada struktur XML ketika ditampilkan dalam HTML. Pemformatan default digunakan dan dapat disesuaikan. Tidak boleh null.


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
