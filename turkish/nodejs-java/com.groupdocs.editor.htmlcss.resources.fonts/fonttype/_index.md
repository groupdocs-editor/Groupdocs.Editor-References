---
title: "FontType"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Desteklenebilir bir yazı tipi türünü temsil eder."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Desteklenebilir bir yazı tipi türünü temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontType()](#FontType--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Tanımsız, bilinmeyen veya desteklenmeyen fontu işaretleyen özel değer |
kaynak
|
|  | [getWoff()](#getWoff--) | WOFF (Web Open Font Format) font tipini temsil eder |
|
|  | [getWoff2()](#getWoff2--) | WOFF2 (Web Open Font Format sürüm 2) font tipini temsil eder |
|
|  | [getTtf()](#getTtf--) | TTF (TrueType Font) font tipini temsil eder |
|
|  | [getOtf()](#getOtf--) | OTF (OpenType Font) font tipini temsil eder |
|
|  | [getTtc()](#getTtc--) | TrueType Collection (TTC) fontunu temsil eder |
|
|  | [getEot()](#getEot--) | EOT (Embedded OpenType) font tipini temsil eder |
|
|  | [getCssName()](#getCssName--) | Bu font tipinin CSS uyumlu adını döndürür, bu ad ... içinde kullanılır |
|
|  | [getFormalName()](#getFormalName--) | Bu font tipinin resmi adını döndürür |
|
|  | [getFileExtension()](#getFileExtension--) | Bu font tipi için dosya adı uzantısı (nokta karakteri olmadan) |
|
|  | [getFontFormat()](#getFontFormat--) | Font biçimi @font-face formatı için |
|
|  | [getMimeCode()](#getMimeCode--) | Belirli bir font tipinin MIME kodu |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Belirtilen CSS‑uyumlu olanın eşdeğeri olan FontType değerini döndürür |
font tipinin adı
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Dosya uzantısının eşdeğeri olan FontType değerini döndürür, ki |
belirtilen dosya adından çıkarılır
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Belirtilen MIME‑kodunun eşdeğeri olan FontType değerini döndürür |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Belirtilen kümeden "Undefined" olmayan ilk font tipini döndürür |
değer, aksi takdirde (tüm öğeler ... olduğunda) "Undefined" font tipi
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Bu örneğin belirtilen "FontType" ile eşit olup olmadığını belirler |
örnek
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler, |
ki muhtemelen başka bir "FontType" örneğidir
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | İki "FontType" değerinin eşit olup olmadığını denetler |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | İki "FontType" değerinin eşit olmamasını denetler |
|
|  | [hashCode()](#hashCode--) | Bu belirli değer için sabit bir sayı olan bir hash kodu döndürür |
tip
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Tanımsız, bilinmeyen veya desteklenmeyen fontu işaretleyen özel değer
kaynak


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


WOFF (Web Open Font Format) font tipini temsil eder


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


WOFF2 (Web Open Font Format sürüm 2) font tipini temsil eder


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


TTF (TrueType Font) font tipini temsil eder


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


OTF (OpenType Font) font tipini temsil eder


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


TrueType Collection (TTC) fontunu temsil eder


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


EOT (Embedded OpenType) font tipini temsil eder


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Bu font tipinin CSS uyumlu adını döndürür, bu ad ... içinde kullanılır


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Bu font tipinin resmi adını döndürür


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Bu font tipi için dosya adı uzantısı (nokta karakteri olmadan)


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Font biçimi @font-face formatı için


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Belirli bir font tipinin MIME kodu


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Belirtilen CSS‑uyumlu olanın eşdeğeri olan FontType değerini döndürür
font tipinin adı


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | ad | java.lang.String | Font tipinin CSS‑uyumlu adı |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Dosya uzantısının eşdeğeri olan FontType değerini döndürür, ki
belirtilen dosya adından çıkarılır


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya adı | java.lang.String | Uzantılı dosya adı, tam ad olabilir |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Belirtilen MIME‑kodunun eşdeğeri olan FontType değerini döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME‑kod |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Belirtilen kümeden "Undefined" olmayan ilk font tipini döndürür
değer, aksi takdirde (tüm öğeler ... olduğunda) "Undefined" font tipi
"Undefined")


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Bir veya daha fazla FontType değeri, NULL veya boş koleksiyon izin verilmez |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Bu örneğin belirtilen "FontType" ile eşit olup olmadığını belirler
örnek


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Bu ile kontrol edilecek diğer FontType örneği |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler,
ki muhtemelen başka bir "FontType" örneğidir


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Muhtemelen FontType yapısının diğer örneği, System.Object'e kutulanmış |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


İki "FontType" değerinin eşit olup olmadığını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Kontrol edilecek ilk FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Kontrol edilecek ikinci FontType |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


İki "FontType" değerinin eşit olmamasını denetler


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Kontrol edilecek ilk FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Kontrol edilecek ikinci FontType |
|

**Returns:**
boolean - Eşitse True, eşit değilse false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu belirli değer için sabit bir sayı olan bir hash kodu döndürür
tip


**Returns:**
int - 4 bayt işaretli tam sayı, Tanımsız değer için 0

