---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Tüm Kelime İşleme formatlarını kapsar."
type: docs
weight: 17
url: /tr/java/com.groupdocs.editor.formats/wordprocessingformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class WordProcessingFormats extends DocumentFormatBase
```

Tüm WordProcessing formatlarını kapsar. Aşağıdaki dosya türlerini içerir:
[Doc](../../com.groupdocs.editor.formats/wordprocessingformats#Doc),
[Docm](../../com.groupdocs.editor.formats/wordprocessingformats#Docm),
[Docx](../../com.groupdocs.editor.formats/wordprocessingformats#Docx),
[Dot](../../com.groupdocs.editor.formats/wordprocessingformats#Dot),
[Dotm](../../com.groupdocs.editor.formats/wordprocessingformats#Dotm),
[Dotx](../../com.groupdocs.editor.formats/wordprocessingformats#Dotx),
[FlatOpc](../../com.groupdocs.editor.formats/wordprocessingformats#FlatOpc),
[Odt](../../com.groupdocs.editor.formats/wordprocessingformats#Odt),
[Ott](../../com.groupdocs.editor.formats/wordprocessingformats#Ott),
[Rtf](../../com.groupdocs.editor.formats/wordprocessingformats#Rtf),
[WordML](../../com.groupdocs.editor.formats/wordprocessingformats#WordML).
Word Processing formatları hakkında daha fazla bilgi için [buraya](../https://wiki.fileformat.com/word-processing) tıklayın.

MIME kodları verilen kaynaklardan alınır:
https://filext.com/faq/office_mime_types.html
https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Doc](#Doc) | MS Word 97-2007 Binary File Format (DOC), Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder. |
|
|  | [Docx](#Docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX), Microsoft Word belgeleri için yaygın bilinen bir formattır. |
|
|  | [Dot](#Dot) | MS Word 97-2007 Template (DOT), Microsoft Word tarafından daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır. |
|
|  | [Docm](#Docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM) dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan belgelerdir. |
|
|  | [Dotx](#Dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX), Microsoft Word tarafından daha sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır. |
|
|  | [Dotm](#Dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM), Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan şablon dosyalarını temsil eder. |
|
|  | [FlatOpc](#FlatOpc) | Office Open XML WordprocessingML, ZIP paketi yerine düz bir XML dosyasında depolanır. |
|
|  | [Rtf](#Rtf) | Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder. |
|
|  | [Odt](#Odt) | Open Document Format Text Document (ODT) dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir. |
|
|  | [Ott](#Ott) | Open Document Format Text Document Template (OTT), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder. |
|
|  | [WordML](#WordML) | Microsoft Office Word 2003 XML Format \\u2014 WordProcessingML veya WordML (.XML). |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) öğelerinin yinelenebilir bir koleksiyonunu alır. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Belirtilen dosya uzantısına sahip belirtilen türdeki [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) örneğini getirir. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Dosya uzantısını temsil eden bir dizeyi [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) nesnesine dönüştürür. |
|
### Doc {#Doc}
```
public static final WordProcessingFormats Doc
```


MS Word 97-2007 Binary File Format (DOC), Microsoft Word veya diğer kelime işlem programları tarafından ikili dosya formatında oluşturulan belgeleri temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/doc)
.


### Docx {#Docx}
```
public static final WordProcessingFormats Docx
```


Office Open XML WordProcessingML Macro-Free Document (DOCX), Microsoft Word belgeleri için yaygın bilinen bir formattır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/docx)
.


### Dot {#Dot}
```
public static final WordProcessingFormats Dot
```


MS Word 97-2007 Template (DOT), Microsoft Word tarafından daha sonraki DOC veya DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/dot)
.


### Docm {#Docm}
```
public static final WordProcessingFormats Docm
```


Office Open XML WordProcessingML Macro-Enabled Document (DOCM) dosyaları, makroları çalıştırma yeteneğine sahip Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan belgelerdir.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/docm)
.


### Dotx {#Dotx}
```
public static final WordProcessingFormats Dotx
```


Office Open XML WordprocessingML Macro-Free Template (DOTX), Microsoft Word tarafından daha sonraki DOCX dosyalarının oluşturulması için önceden biçimlendirilmiş ayarlara sahip şablon dosyalarıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/dotx)
.


### Dotm {#Dotm}
```
public static final WordProcessingFormats Dotm
```


Office Open XML WordprocessingML Macro-Enabled Template (DOTM), Microsoft Word 2007 veya daha yeni sürümlerle oluşturulan şablon dosyalarını temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/dotm)
.


### FlatOpc {#FlatOpc}
```
public static final WordProcessingFormats FlatOpc
```


Office Open XML WordprocessingML, ZIP paketi yerine düz bir XML dosyasında depolanır.


### Rtf {#Rtf}
```
public static final WordProcessingFormats Rtf
```


Rich Text Format (RTF), uygulamalar içinde kullanılmak üzere biçimlendirilmiş metin ve grafiklerin kodlanma yöntemini temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/rtf)
.


### Odt {#Odt}
```
public static final WordProcessingFormats Odt
```


Open Document Format Text Document (ODT) dosyaları, OpenDocument Metin Dosyası formatına dayalı kelime işlem uygulamalarıyla oluşturulan belge türleridir.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/odt)
.


### Ott {#Ott}
```
public static final WordProcessingFormats Ott
```


Open Document Format Text Document Template (OTT), OASIS'in OpenDocument standart formatına uygun olarak uygulamalar tarafından oluşturulan şablon belgeleri temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/ott)
.


### WordML {#WordML}
```
public static final WordProcessingFormats WordML
```


Microsoft Office Word 2003 XML Format \\u2014 WordProcessingML veya WordML (.XML).

<br />

*** ** * ** ***

https://en.wikipedia.org/wiki/Microsoft_Office_XML_formats

<br />



### getAll() {#getAll--}
```
public static List<WordProcessingFormats> getAll()
```


Tüm [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) öğelerinin yinelenebilir bir koleksiyonunu alır.
Değer: Tüm [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) örneklerini içeren bir IEnumerable{WordProcessingFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.WordProcessingFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static WordProcessingFormats fromExtension(String extension)
```


Belirtilen dosya uzantısına sahip belirtilen türdeki [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) örneğini getirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Belge formatının dosya uzantısı. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - An instance of the specified type [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static WordProcessingFormats fromString(String extension)
```


Dosya uzantısını temsil eden bir dizeyi [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |
|

**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - A [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) object corresponding to the specified file extension.

