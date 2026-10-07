---
title: "FormatFamilies"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Sistemde mevcut farklı format ailelerini temsil eder."
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Sistemde mevcut farklı format ailelerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [EBook](#EBook) | eKitap format ailesini temsil eder. |
|
|  | [Email](#Email) | E-posta format ailesini temsil eder. |
|
|  | [FixedLayout](#FixedLayout) | Sabit Düzen format ailesini temsil eder. |
|
|  | [Presentation](#Presentation) | Sunum format ailesini temsil eder. |
|
|  | [Spreadsheet](#Spreadsheet) | Elektronik Tablo format ailesini temsil eder. |
|
|  | [Textual](#Textual) | Metin format ailesini temsil eder. |
|
|  | [WordProcessing](#WordProcessing) | Word İşleme format ailesini temsil eder. |
|
### EBook {#EBook}
```
public static final FormatFamilies EBook
```


eKitap format ailesini temsil eder.
Mobi formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/ebook/mobi/)
,
AZW3 formatı hakkında
[here](../https://docs.fileformat.com/ebook/azw3/)
,
ve ePub formatı hakkında
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Email {#Email}
```
public static final FormatFamilies Email
```


E-posta format ailesini temsil eder.
E-posta formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/email/)
.


### FixedLayout {#FixedLayout}
```
public static final FormatFamilies FixedLayout
```


Sabit Düzen format ailesini temsil eder.
Çeşitli belge görüntüleme veya yayınlama uygulamaları, kullanıcıların belirli formatlardaki belgeleri açmasına (Adobe Acrobat, XPS Viewer) ve bazen (Adobe InDesign) düzenlemesine izin verir.
Bu uygulamalar genellikle sözde \u201cfixed-page\u201d format belgeleri üretir.
Böyle bir belge formatı, bir belgenin\u2019s içeriğinin her sayfada tam olarak nerede konumlandırıldığını açıklar.
İçeride, PDF veya XPS formatı her sayfanın bir açıklamasını ve sayfadaki içeriğin düzenini belirten çizim talimatlarını içerir.
Bu, içeriğin raster veya vektör biçiminde gösterildiği yeri tanımlayan görüntü formatlarına benzer.


### Presentation {#Presentation}
```
public static final FormatFamilies Presentation
```


Sunum format ailesini temsil eder.
Sunum formatları hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/presentation)
.


### Spreadsheet {#Spreadsheet}
```
public static final FormatFamilies Spreadsheet
```


Elektronik Tablo format ailesini temsil eder.
Çalışma kitabının kaydedilebileceği tüm ikili, XML ve metinsel Elektronik Tablo formatları (CSV, TSV, noktalı virgül gibi ayırıcılarla metin tabanlı ayırıcı formatları hariç).


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Metin format ailesini temsil eder.
İşaretleme (XML, HTML) ve diğerlerini içeren tüm metin (metin tabanlı) formatlarını kapsar.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Word İşleme format ailesini temsil eder.
Word İşleme formatları hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME kodları verilen kaynaklardan alınır: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



