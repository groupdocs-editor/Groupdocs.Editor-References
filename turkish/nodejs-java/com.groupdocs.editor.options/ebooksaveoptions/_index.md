---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Belgeyi tüm desteklenen e-Kitap formatları (ePub, MOBI ve AZW3) içinde oluşturmak ve kaydetmek için özel seçenekler belirtmeye olanak tanır."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Tüm desteklenebilir e-Kitap formatlarında (ePub, MOBI ve AZW3) belgeyi oluşturmak ve kaydetmek için özel seçenekleri belirtmeye izin verir.

<br />

*** ** * ** ***

Desteklenen e-Kitap formatları:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Elektronik Yayın)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle Format 8t)

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Bu parametresiz yapıcı, ePub çıktı formatı ile bir EbookSaveOptions örneği oluşturur (daha sonra şu şekilde değiştirilebilir |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | Belirtilen zorunlu e-Kitap çıktı formatı ile, diğer tüm parametreler varsayılan iken, [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) yeni bir örnek oluşturur |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSplitHeadingLevel()](#getSplitHeadingLevel--) | e-Kitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. |
|
|  | [setSplitHeadingLevel(int value)](#setSplitHeadingLevel-int-) | e-Kitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | Sonuç dosyasında yerleşik ve özel belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | Sonuç dosyasında yerleşik ve özel belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir. |
|
|  | [getOutputFormat()](#getOutputFormat--) | Sonuç e-Kitap dosyasının formatını belirtir: IDPF ePub, MOBI veya AZW3. |
|
|  | [setOutputFormat(EBookFormats value)](#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-) | Sonuç e-Kitap dosyasının formatını belirtir: IDPF ePub, MOBI veya AZW3. |
|
### EbookSaveOptions() {#EbookSaveOptions--}
```
public EbookSaveOptions()
```


Bu parametresiz yapıcı, ePub çıktı formatı ile bir EbookSaveOptions örneği oluşturur (daha sonra şu şekilde değiştirilebilir
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) property)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


Belirtilen zorunlu e-Kitap çıktı formatı ile, diğer tüm parametreler varsayılan iken, [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) yeni bir örnek oluşturur


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | e-Kitap'ın kaydedileceği zorunlu çıktı formatı |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


e-Kitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. Varsayılan değer
2
.
Bunu ayarlamak
0
bölmeyi devre dışı bırakır, böylece e-Kitap'ın tüm içeriği sonuç dosyası içinde tek bir paket içinde birleştirilir.

<br />

*** ** * ** ***

Bu özellik 1 ile 9 arasında bir değere ayarlandığında, belge, kullanılan biçimlendirilmiş paragraflarda bölünecektir

**Heading 1**
,
**Heading 2**
,
**Heading 3**
vb. stiller, belirtilen başlık seviyesine kadar.

Varsayılan olarak, yalnızca
**Heading 1**
ve
**Heading 2**
paragraflar belgenin bölünmesine neden olur.
Bu özelliği sıfıra (veya sıfırdan düşük bir değere) ayarlamak, belgenin başlık paragraflarında hiç bölünmemesine neden olur.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


e-Kitap dosyasının bölüneceği en yüksek başlık seviyesini belirtir. Varsayılan değer
2
.
Bunu ayarlamak
0
bölmeyi devre dışı bırakır, böylece e-Kitap'ın tüm içeriği sonuç dosyası içinde tek bir paket içinde birleştirilir.

<br />

*** ** * ** ***

Bu özellik 1 ile 9 arasında bir değere ayarlandığında, belge, kullanılan biçimlendirilmiş paragraflarda bölünecektir

**Heading 1**
,
**Heading 2**
,
**Heading 3**
vb. stiller, belirtilen başlık seviyesine kadar.

Varsayılan olarak, yalnızca
**Heading 1**
ve
**Heading 2**
paragraflar belgenin bölünmesine neden olur.
Bu özelliği sıfıra (veya sıfırdan düşük bir değere) ayarlamak, belgenin başlık paragraflarında hiç bölünmemesine neden olur.

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


Sonuç dosyasında yerleşik ve özel belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir.
Varsayılan değer
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


Sonuç dosyasında yerleşik ve özel belge özelliklerinin dışa aktarılıp aktarılmayacağını belirtir.
Varsayılan değer
false
.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final EBookFormats getOutputFormat()
```


Sonuç e-Kitap dosyasının formatını belirtir: IDPF ePub, MOBI veya AZW3.


**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats)
### setOutputFormat(EBookFormats value) {#setOutputFormat-com.groupdocs.editor.formats.EBookFormats-}
```
public final void setOutputFormat(EBookFormats value)
```


Sonuç e-Kitap dosyasının formatını belirtir: IDPF ePub, MOBI veya AZW3.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) |  |

