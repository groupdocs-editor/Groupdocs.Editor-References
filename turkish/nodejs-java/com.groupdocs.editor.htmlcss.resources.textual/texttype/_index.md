---
title: "TextType"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Desteklenebilir bir metin kaynağı türünü temsil eder"
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Desteklenebilir bir metin kaynağı türünü temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextType()](#TextType--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Tanımsız, bilinmeyen veya desteklenmeyen metinsel değeri işaretleyen özel değer. |
kaynak
|
|  | [getCss()](#getCss--) | Metinsel kaynağın CSS türü |
|
|  | [getXml()](#getXml--) | Metinsel kaynağın XML türü |
|
|  | [getFormalName()](#getFormalName--) | Bu metinsel kaynak türünün resmi adını döndürür |
|
|  | [getFileExtension()](#getFileExtension--) | Belirli bir metnin dosya uzantısı (başındaki nokta karakteri olmadan) |
kaynak
|
|  | [getMimeCode()](#getMimeCode--) | Belirli bir metin kaynağı türünün MIME kodu |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Bu örneğin belirtilen \"TextType\" ile eşit olup olmadığını belirler |
örnek
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler, |
muhtemelen başka bir \"TextType\" örneği
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | İki belirli \"TextType\" örneğinin eşit olup olmadığını tanımlar |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | İki belirli \"TextType\" örneğinin eşit olmadığını tanımlar |
|
|  | [hashCode()](#hashCode--) | Bu belirli değer için sabit bir sayı olan bir hash kodu döndürür |
tip
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Belirtilen dosya adıyla uzantıdan veya yalnızca uzantıdan çıkarılan dosya uzantısına eşdeğer bir TextType değeri döndürür |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Tanımsız, bilinmeyen veya desteklenmeyen metinsel değeri işaretleyen özel değer.
kaynak


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


Metinsel kaynağın CSS türü


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


Metinsel kaynağın XML türü


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Bu metinsel kaynak türünün resmi adını döndürür


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Belirli bir metnin dosya uzantısı (başındaki nokta karakteri olmadan)
kaynak


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


Belirli bir metin kaynağı türünün MIME kodu


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Bu örneğin belirtilen \"TextType\" ile eşit olup olmadığını belirler
örnek


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Eşitlik karşılaştırması için bu örnekle karşılaştırılması gereken diğer TextType örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false döndürür

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen tip dönüşümü yapılmamış nesne ile eşit olup olmadığını belirler,
muhtemelen başka bir \"TextType\" örneği


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Nesneye kutulanmış diğer TextType örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false döndürür

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


İki belirli \"TextType\" örneğinin eşit olup olmadığını tanımlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | İlk TextType örneği |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | İkinci TextType örneği |
|

**Returns:**
boolean - Eşitse true, eşit değilse false döndürür

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


İki belirli \"TextType\" örneğinin eşit olmadığını tanımlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | İlk TextType örneği |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | İkinci TextType örneği |
|

**Returns:**
boolean - Eşit değilse true, eşitse false döndürür

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu belirli değer için sabit bir sayı olan bir hash kodu döndürür
tip


**Returns:**
int - İşaretli 4 baytlık tam sayı. Bu örnek varsayılan değere sahipse 0 döndürür.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Belirtilen dosya adıyla uzantıdan veya yalnızca uzantıdan çıkarılan dosya uzantısına eşdeğer bir TextType değeri döndürür


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | dosya adı | java.lang.String | Uzantılı dosya adı, göreli ya da mutlak yol olabilir veya yalnızca uzantı da olabilir |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

