---
title: "TextType"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет один поддерживаемый тип текстового ресурса"
type: docs
weight: 12
url: /ru/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Представляет один поддерживаемый тип текстового ресурса

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextType()](#TextType--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Специальное значение, которое отмечает неопределённый, неизвестный или неподдерживаемый текст |
ресурс
|
|  | [getCss()](#getCss--) | CSS‑тип текстового ресурса |
|
|  | [getXml()](#getXml--) | XML‑тип текстового ресурса |
|
|  | [getFormalName()](#getFormalName--) | Возвращает официальное название этого типа текстового ресурса |
|
|  | [getFileExtension()](#getFileExtension--) | Расширение файла (без начальной точки) конкретного текстового ресурса |
ресурс
|
|  | [getMimeCode()](#getMimeCode--) | MIME‑код конкретного типа текстового ресурса |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Определяет, равен ли этот экземпляр указанному "TextType" |
экземпляр
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли этот экземпляр указанному неконвертированному объекту, |
который, предположительно, является другим экземпляром "TextType"
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Определяет, равны ли два конкретных экземпляра "TextType" |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Определяет, не равны ли два конкретных экземпляра "TextType" |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код, который является постоянным числом для этого конкретного значения |
тип
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Возвращает значение TextType, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла с расширением или из чистого расширения |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Специальное значение, которое отмечает неопределённый, неизвестный или неподдерживаемый текст
ресурс


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


CSS‑тип текстового ресурса


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


XML‑тип текстового ресурса


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Возвращает официальное название этого типа текстового ресурса


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Расширение файла (без начальной точки) конкретного текстового ресурса
ресурс


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME‑код конкретного типа текстового ресурса


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Определяет, равен ли этот экземпляр указанному "TextType"
экземпляр


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Другой экземпляр TextType, который должен сравниваться с этим на равенство |
|

**Returns:**
boolean - Возвращает true, если равны, или false, если не равны

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли этот экземпляр указанному неконвертированному объекту,
который, предположительно, является другим экземпляром "TextType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой экземпляр TextType, который упакован в объект |
|

**Returns:**
boolean - Возвращает true, если равны, или false, если не равны

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Определяет, равны ли два конкретных экземпляра "TextType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Первый экземпляр TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Второй экземпляр TextType |
|

**Returns:**
boolean - Возвращает true, если равны, или false, если не равны

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Определяет, не равны ли два конкретных экземпляра "TextType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Первый экземпляр TextType |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Второй экземпляр TextType |
|

**Returns:**
boolean - Возвращает true, если не равны, или false, если равны

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код, который является постоянным числом для этого конкретного значения
тип


**Returns:**
int - Знаковое 4‑байтовое целое число. Возвращает 0, если этот экземпляр имеет значение по умолчанию.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Возвращает значение TextType, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла с расширением или из чистого расширения


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя файла | java.lang.String | Имя файла с расширением, может быть относительным или абсолютным путём, либо самим чистым расширением |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

