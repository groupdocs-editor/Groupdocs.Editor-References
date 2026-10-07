---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Belgeyi oluşturmak ve kaydetmek için tüm desteklenen e-Kitap formatları ePub, MOBI ve AZW3'te özel seçenekler belirtmeye olanak tanır."
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.options/ebooksaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EbookSaveOptions implements ISaveOptions
```

Belgeyi tüm desteklenen e-Kitap formatlarında (ePub, MOBI ve AZW3) oluşturma ve kaydetme için özel seçenekleri belirtmeye izin verir.

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
|  | [EbookSaveOptions()](#EbookSaveOptions--) | Bu parametresiz yapıcı, ePub çıktı formatı ile EbookSaveOptions'ın yeni bir örneğini oluşturur (daha sonra şu şekilde değiştirilebilir |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) özelliği)
|
|  | [EbookSaveOptions(EBookFormats outputFormat)](#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-) | [EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) yeni bir örnek oluşturur, belirtilen zorunlu e-Kitap çıktı formatı ile, diğer tüm parametreler varsayılandır |
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


Bu parametresiz yapıcı, ePub çıktı formatı ile EbookSaveOptions'ın yeni bir örneğini oluşturur (daha sonra şu şekilde değiştirilebilir
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(EBookFormats).setOutputFormat(EBookFormats)) özelliği)


### EbookSaveOptions(EBookFormats outputFormat) {#EbookSaveOptions-com.groupdocs.editor.formats.EBookFormats-}
```
public EbookSaveOptions(EBookFormats outputFormat)
```


[EbookSaveOptions](../../com.groupdocs.editor.options/ebooksaveoptions) yeni bir örnek oluşturur, belirtilen zorunlu e-Kitap çıktı formatı ile, diğer tüm parametreler varsayılandır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFormat | [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) | zorunlu çıktı formatı, e-Kitap'ın kaydedileceği |
|

### getSplitHeadingLevel() {#getSplitHeadingLevel--}
```
public final int getSplitHeadingLevel()
```


e-Book dosyasını bölmek için kullanılacak başlıkların maksimum seviyesini belirtir. Varsayılan değer
2
.
Bunu şu şekilde ayarlayarak
0
bölmeyi devre dışı bırakır, böylece e-Book'un tüm içeriği sonuç dosyasında tek bir paket içinde birleştirilir.

<br />

*** ** * ** ***

Bu özellik 1 ile 9 arasında bir değere ayarlandığında, belge, kullanılan biçimdeki paragraflarda bölünecektir

**Heading 1**
,
**Heading 2**
,
**Heading 3**
vb. stiller belirtilen başlık seviyesine kadar.

Varsayılan olarak, yalnızca
**Heading 1**
ve
**Heading 2**
paragraflar belgenin bölünmesine neden olur.
Bu özelliği sıfıra (veya sıfırdan daha düşük bir değere) ayarlamak, belgenin başlık paragraflarında hiç bölünmemesine neden olur.

<br />



**Returns:**
int
### setSplitHeadingLevel(int value) {#setSplitHeadingLevel-int-}
```
public final void setSplitHeadingLevel(int value)
```


e-Book dosyasını bölmek için kullanılacak başlıkların maksimum seviyesini belirtir. Varsayılan değer
2
.
Bunu şu şekilde ayarlayarak
0
bölmeyi devre dışı bırakır, böylece e-Book'un tüm içeriği sonuç dosyasında tek bir paket içinde birleştirilir.

<br />

*** ** * ** ***

Bu özellik 1 ile 9 arasında bir değere ayarlandığında, belge, kullanılan biçimdeki paragraflarda bölünecektir

**Heading 1**
,
**Heading 2**
,
**Heading 3**
vb. stiller belirtilen başlık seviyesine kadar.

Varsayılan olarak, yalnızca
**Heading 1**
ve
**Heading 2**
paragraflar belgenin bölünmesine neden olur.
Bu özelliği sıfıra (veya sıfırdan daha düşük bir değere) ayarlamak, belgenin başlık paragraflarında hiç bölünmemesine neden olur.

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

