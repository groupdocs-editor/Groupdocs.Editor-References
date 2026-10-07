---
title: "TextualFormats"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "İşaretleme XML HTML ve diğerlerini içeren tüm metin tabanlı formatları kapsar."
type: docs
weight: 16
url: /tr/java/com.groupdocs.editor.formats/textualformats/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase), [com.groupdocs.editor.formats.abstraction.DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
```
public class TextualFormats extends DocumentFormatBase
```

İşaretleme (XML, HTML) ve diğerlerini içeren tüm metin (metin tabanlı) formatlarını kapsar.
Aşağıdaki formatları içerir:
[Html](../../com.groupdocs.editor.formats/textualformats#Html),
[Txt](../../com.groupdocs.editor.formats/textualformats#Txt),
[Xml](../../com.groupdocs.editor.formats/textualformats#Xml).
[Md](../../com.groupdocs.editor.formats/textualformats#Md),
[Json](../../com.groupdocs.editor.formats/textualformats#Json).

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Html](#Html) | HyperText Markup Language belgesi (HTML), tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları için uzantıdır. |
|
|  | [Xml](#Xml) | eXtensible Markup Language belgesi (XML), HTML'ye benzer ancak nesneleri tanımlamak için etiket kullanımı bakımından farklıdır. |
|
|  | [Txt](#Txt) | Düz Metin Belgesi (TXT), satır biçiminde düz metin içeren bir metin belgesini temsil eder. |
|
|  | [Md](#Md) | Markdown, düz metin düzenleyicisi kullanarak biçimlendirilmiş metin oluşturmak için hafif bir işaretleme dilidir. |
|
|  | [Json](#Json) | JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insan tarafından okunabilir metin kullanan açık bir standart dosya formatıdır. |
|
|  | [Mhtml](#Mhtml) | Birden fazla HTML belgesinin MIME kapsüllemesi, HTML kodunu ve ilgili kaynaklarını tek bir bilgisayar dosyasında birleştirmek için kullanılan bir web sayfası arşiv formatıdır. |
|
|  | [Chm](#Chm) | Microsoft Compiled HTML Help, HTML sayfalarından, bir indeks ve diğer gezinme araçlarından oluşan Microsoft'a ait özel bir çevrimiçi yardım ikili formatıdır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getAll()](#getAll--) | Tüm [TextualFormats](../../com.groupdocs.editor.formats/textualformats) öğelerinin sayılabilir bir koleksiyonunu alır. |
|
|  | [fromExtension(String extension)](#fromExtension-java.lang.String-) | Belirtilen dosya uzantısına sahip belirtilen türdeki [TextualFormats](../../com.groupdocs.editor.formats/textualformats) örneğini alır. |
|
|  | [fromString(String extension)](#fromString-java.lang.String-) | Dosya uzantısını temsil eden bir dizeyi bir [TextualFormats](../../com.groupdocs.editor.formats/textualformats) nesnesine dönüştürür. |
|
### Html {#Html}
```
public static final TextualFormats Html
```


HyperText Markup Language belgesi (HTML), tarayıcılarda görüntülenmek üzere oluşturulan web sayfaları için uzantıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/web/html)
.


### Xml {#Xml}
```
public static final TextualFormats Xml
```


eXtensible Markup Language belgesi (XML), HTML'ye benzer ancak nesneleri tanımlamak için etiket kullanımı bakımından farklıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/web/xml)
.


### Txt {#Txt}
```
public static final TextualFormats Txt
```


Düz Metin Belgesi (TXT), satır biçiminde düz metin içeren bir metin belgesini temsil eder.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://wiki.fileformat.com/word-processing/txt)
.


### Md {#Md}
```
public static final TextualFormats Md
```


Markdown, düz metin düzenleyicisi kullanarak biçimlendirilmiş metin oluşturmak için hafif bir işaretleme dilidir.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/word-processing/md/)
.


### Json {#Json}
```
public static final TextualFormats Json
```


JSON (JavaScript Object Notation), verileri depolamak ve iletmek için insan tarafından okunabilir metin kullanan açık bir standart dosya formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/web/json/)
.


### Mhtml {#Mhtml}
```
public static final TextualFormats Mhtml
```


Birden fazla HTML belgesinin MIME kapsüllemesi, HTML kodunu ve ilgili kaynaklarını tek bir bilgisayar dosyasında birleştirmek için kullanılan bir web sayfası arşiv formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/web/mhtml/)
.


### Chm {#Chm}
```
public static final TextualFormats Chm
```


Microsoft Compiled HTML Help, HTML sayfalarından, bir indeks ve diğer gezinme araçlarından oluşan Microsoft'a ait özel bir çevrimiçi yardım ikili formatıdır.
Bu dosya formatı hakkında daha fazla bilgi edinin
[here](../https://docs.fileformat.com/web/chm/)
.


### getAll() {#getAll--}
```
public static List<TextualFormats> getAll()
```


Tüm [TextualFormats](../../com.groupdocs.editor.formats/textualformats) öğelerinin sayılabilir bir koleksiyonunu alır.
Değer: Tüm [TextualFormats](../../com.groupdocs.editor.formats/textualformats) örneklerini içeren bir IEnumerable{TextualFormats}.


**Returns:**
java.util.List<com.groupdocs.editor.formats.TextualFormats>
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static TextualFormats fromExtension(String extension)
```


Belirtilen dosya uzantısına sahip belirtilen türdeki [TextualFormats](../../com.groupdocs.editor.formats/textualformats) örneğini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Belge formatının dosya uzantısı. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - An instance of the specified type [TextualFormats](../../com.groupdocs.editor.formats/textualformats) with the specified file extension.

### fromString(String extension) {#fromString-java.lang.String-}
```
public static TextualFormats fromString(String extension)
```


Dosya uzantısını temsil eden bir dizeyi bir [TextualFormats](../../com.groupdocs.editor.formats/textualformats) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | uzantı | java.lang.String | Dönüştürülecek dosya uzantısı. Uzantı birden fazla nokta içeriyorsa, son noktanın sonrasındaki kısım kullanılır. |
|

**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats) - A [TextualFormats](../../com.groupdocs.editor.formats/textualformats) object corresponding to the specified file extension.

