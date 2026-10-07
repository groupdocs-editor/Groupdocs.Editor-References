---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Düz metin TXT belgeleri oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir"
type: docs
weight: 41
url: /tr/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Düz metin (TXT) oluşturmak ve kaydetmek için özel seçenekler belirtmeye izin verir
belgeler

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Metin belgesinin karakter kodlaması, uygulanacak |
kaydetme
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Metin belgesinin karakter kodlaması, uygulanacak |
kaydetme
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Her BiDi çalıştırmasından önce çift yönlü işaretlerin eklenip eklenmeyeceğini belirtir |
düz metin formatında dışa aktarırken.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Her BiDi çalıştırmasından önce çift yönlü işaretlerin eklenip eklenmeyeceğini belirtir |
düz metin formatında dışa aktarım
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Programın tabloların düzenini korumaya çalışıp çalışmayacağını belirtir |
düz metin formatında kaydederken.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Programın tabloların düzenini korumaya çalışıp çalışmayacağını belirtir |
düz metin formatında kaydederken.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Metin belgesinin karakter kodlaması, uygulanacak
kaydetme


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Metin belgesinin karakter kodlaması, uygulanacak
kaydetme


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Her BiDi çalıştırmasından önce çift yönlü işaretlerin eklenip eklenmeyeceğini belirtir
Düz metin formatında dışa aktarım. Varsayılan değer 'false' \\u2014 BiDi işaretleri eklenmez.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Her BiDi çalıştırmasından önce çift yönlü işaretlerin eklenip eklenmeyeceğini belirtir
düz metin formatında dışa aktarım


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Programın tabloların düzenini korumaya çalışıp çalışmayacağını belirtir
düz metin formatında kaydederken. Varsayılan değer false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Programın tabloların düzenini korumaya çalışıp çalışmayacağını belirtir
düz metin formatında kaydederken. Varsayılan değer false.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

