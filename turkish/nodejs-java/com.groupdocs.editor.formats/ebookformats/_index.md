---
title: "EBookFormats"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Tüm eBook formatlarını kapsar."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.editor.formats/ebookformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class EBookFormats extends DocumentFormatBase
```

Tüm e-kitap formatlarını kapsar. Aşağıdaki dosya türlerini içerir:
[Mobi](../../com.groupdocs.editor.formats/ebookformats#Mobi),
[Epub](../../com.groupdocs.editor.formats/ebookformats#Epub)
Mobi formatı hakkında daha fazla bilgi için [here](../https://docs.fileformat.com/ebook/mobi/), ve ePub formatı hakkında [here](../https://docs.fileformat.com/ebook/epub/).

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Mobi](#Mobi) | MOBI, MobiPocket Reader için geliştirilen formatın adıdır. |
|
|  | [Epub](#Epub) | Electronic Publication (IDPF ePub) formatı, yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır. |
|
|  | [Azw3](#Azw3) | AZW3, Kindle Format 8 (KF8) olarak da bilinir, Amazon Kindle cihazları için geliştirilen AZW e-kitap dijital dosya formatının değiştirilmiş sürümüdür. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) öğelerinin yinelenebilir bir koleksiyonunu alır. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Belirtilen dosya uzantısına sahip belirtilen türdeki [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) örneğini getirir. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Dosya uzantısını temsil eden bir dizeyi bir [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) nesnesine dönüştürür. |
|
### Mobi {#Mobi}
```
public static final EBookFormats Mobi
```


MOBI, MobiPocket Reader için geliştirilen formatın adıdır. Ayrıca PRC, AZW olarak da bilinir.
Şu anda Amazon tarafından biraz farklı bir DRM şemasıyla kullanılmakta ve AZW olarak adlandırılmaktadır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/ebook/mobi/)
.


### Epub {#Epub}
```
public static final EBookFormats Epub
```


Electronic Publication (IDPF ePub) formatı, yayıncılar ve tüketiciler için standart bir dijital yayın formatı sağlayan bir e-kitap dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/ebook/epub/)
.


### Azw3 {#Azw3}
```
public static final EBookFormats Azw3
```


AZW3, Kindle Format 8 (KF8) olarak da bilinir, Amazon Kindle cihazları için geliştirilen AZW e-kitap dijital dosya formatının değiştirilmiş sürümüdür.
Bu format, eski AZW dosyalarına bir iyileştirme getirir.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/ebook/azw3/)
.


### getAll() {#getAll--}
```
public static List<EBookFormats> getAll()
```


Tüm [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) öğelerinin yinelenebilir bir koleksiyonunu alır.
Değer: Tüm [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) örneklerini içeren bir IEnumerable{EBookFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.EBookFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static EBookFormats fromExtension(String extension)
```


Belirtilen dosya uzantısına sahip belirtilen türdeki [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) örneğini getirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Belge formatının dosya uzantısı. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - An instance of the specified type [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static EBookFormats fromString(String extension)
```


Dosya uzantısını temsil eden bir dizeyi bir [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |
|

**Returns:**
[EBookFormats](../../com.groupdocs.editor.formats/ebookformats) - A [EBookFormats](../../com.groupdocs.editor.formats/ebookformats) object corresponding to the specified file extension.

