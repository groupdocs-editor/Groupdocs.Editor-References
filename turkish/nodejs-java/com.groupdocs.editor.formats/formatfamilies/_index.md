---
title: "FormatFamilies"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Sistemde mevcut olan farklı format ailelerini temsil eder."
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.editor.formats/formatfamilies/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)
```
public class FormatFamilies extends FormatFamilyBase
```

Sistemde mevcut olan farklı format ailelerini temsil eder.

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
|  | [Textual](#Textual) | Metinsel format ailesini temsil eder. |
|
|  | [WordProcessing](#WordProcessing) | Kelime İşleme format ailesini temsil eder. |
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
Çeşitli belge görüntüleme veya yayınlama uygulamaları, kullanıcıların belirli formatlardaki (Adobe Acrobat, XPS Viewer) belgeleri açmasına ve bazen (Adobe InDesign) düzenlemesine izin verir.
Bu uygulamalar tipik olarak sözde “fixed-page” formatında belgeler üretir.
Böyle bir belge formatı, bir belgenin içeriğinin her sayfada tam olarak nerede konumlandırıldığını tanımlar.
İçeride, PDF veya XPS formatı her sayfanın bir açıklamasını ve sayfadaki içeriğin düzenini belirten çizim talimatlarını içerir.
Bu, içeriğin raster veya vektör biçiminde nerede gösterildiğini tanımlayan görüntü formatlarına benzer.


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
Çalışma kitabının kaydedilebileceği tüm ikili, XML ve metinsel Elektronik Tablo formatları (CSV, TSV, noktalı virgül ayırıcı gibi ayırıcı tabanlı tüm metinsel formatlar hariç).


### Textual {#Textual}
```
public static final FormatFamilies Textual
```


Metinsel format ailesini temsil eder.
İşaretleme (XML, HTML) ve diğerlerini içeren tüm metinsel (metin tabanlı) formatları kapsar.


### WordProcessing {#WordProcessing}
```
public static final FormatFamilies WordProcessing
```


Kelime İşleme format ailesini temsil eder.
Kelime İşleme formatları hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing)
.

<br />

*** ** * ** ***

MIME kodları verilen kaynaklardan alınmıştır: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

<br />



