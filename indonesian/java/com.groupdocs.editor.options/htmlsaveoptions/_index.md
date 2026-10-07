---
title: "HtmlSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk Java"
description: "Mengizinkan untuk menentukan opsi khusus untuk menyimpan instance ke format HTML"
type: docs
weight: 19
url: /id/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Mengizinkan untuk menentukan opsi khusus untuk menyimpan instance [EditableDocument](../../com.groupdocs.editor/editabledocument) ke format HTML

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Mengontrol bagaimana nama tag HTML akan ditampilkan dalam markup HTML: Semua huruf kecil (nilai default), Semua huruf besar, atau Huruf pertama besar |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Mengontrol bagaimana nama tag HTML akan ditampilkan dalam markup HTML: Semua huruf kecil (nilai default), Semua huruf besar, atau Huruf pertama besar |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Mengontrol delimiter mana di sekitar nilai atribut dalam elemen HTML yang akan digunakan: kutip tunggal (nilai default) atau kutip ganda |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Mengontrol delimiter mana di sekitar nilai atribut dalam elemen HTML yang akan digunakan: kutip tunggal (nilai default) atau kutip ganda |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Mengontrol dimana menyimpan stylesheet CSS: sebagai sumber eksternal ( |
false
), atau menyematkannya ke dalam markup HTML, di dalam elemen STYLE pada bagian HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Mengontrol dimana menyimpan stylesheet CSS: sebagai sumber eksternal ( |
false
), atau menyematkannya ke dalam markup HTML, di dalam elemen STYLE pada bagian HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Antarmuka, yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Antarmuka, yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Mengontrol bagaimana nama tag HTML akan ditampilkan dalam markup HTML: Semua huruf kecil (nilai default), Semua huruf besar, atau Huruf pertama besar


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Mengontrol bagaimana nama tag HTML akan ditampilkan dalam markup HTML: Semua huruf kecil (nilai default), Semua huruf besar, atau Huruf pertama besar


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Mengontrol delimiter mana di sekitar nilai atribut dalam elemen HTML yang akan digunakan: kutip tunggal (nilai default) atau kutip ganda


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Mengontrol delimiter mana di sekitar nilai atribut dalam elemen HTML yang akan digunakan: kutip tunggal (nilai default) atau kutip ganda


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Mengontrol dimana menyimpan stylesheet CSS: sebagai sumber eksternal (
false
), atau menyematkannya ke dalam markup HTML, di dalam elemen STYLE pada bagian HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Mengontrol dimana menyimpan stylesheet CSS: sebagai sumber eksternal (
false
), atau menyematkannya ke dalam markup HTML, di dalam elemen STYLE pada bagian HTML-\>HEAD (
true
)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Antarmuka, yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Antarmuka, yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

