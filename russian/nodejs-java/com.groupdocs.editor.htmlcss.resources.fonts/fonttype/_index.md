---
title: "FontType"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один поддерживаемый тип шрифта."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

Представляет один поддерживаемый тип шрифта.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontType()](#FontType--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Специальное значение, обозначающее неопределённый, неизвестный или неподдерживаемый шрифт |
resource
|
|  | [getWoff()](#getWoff--) | Представляет тип шрифта WOFF (Web Open Font Format) |
|
|  | [getWoff2()](#getWoff2--) | Представляет тип шрифта WOFF2 (Web Open Font Format version 2) |
|
|  | [getTtf()](#getTtf--) | Представляет тип шрифта TTF (TrueType Font) |
|
|  | [getOtf()](#getOtf--) | Представляет тип шрифта OTF (OpenType Font) |
|
|  | [getTtc()](#getTtc--) | Представляет шрифт TrueType Collection (TTC) |
|
|  | [getEot()](#getEot--) | Представляет тип шрифта EOT (Embedded OpenType) |
|
|  | [getCssName()](#getCssName--) | Возвращает совместимое с CSS имя этого типа шрифта, которое используется в |
|
|  | [getFormalName()](#getFormalName--) | Возвращает официальное имя этого типа шрифта |
|
|  | [getFileExtension()](#getFileExtension--) | Расширение имени файла (без символа точки) для этого типа шрифта |
|
|  | [getFontFormat()](#getFontFormat--) | Формат шрифта для формата @font-face |
|
|  | [getMimeCode()](#getMimeCode--) | MIME‑код конкретного типа шрифта |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | Возвращает значение FontType, которое эквивалентно указанному CSS‑compatible |
имя типа шрифта
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Возвращает значение FontType, которое эквивалентно расширению имени файла, которое |
извлекается из указанного имени файла
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | Возвращает значение FontType, которое эквивалентно указанному MIME‑code |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | Возвращает первый тип шрифта из указанного набора, который не является "Undefined" |
значение, или тип шрифта "Undefined" в противном случае (когда все элементы
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Определяет, равен ли данный экземпляр указанному "FontType" |
экземпляр
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, |
который, предположительно, является другим экземпляром "FontType"
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Проверяет, равны ли два значения "FontType" |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | Проверяет, не равны ли два значения "FontType" |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код, который является постоянным числом для этого конкретного значения |
тип
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


Специальное значение, обозначающее неопределённый, неизвестный или неподдерживаемый шрифт
resource


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


Представляет тип шрифта WOFF (Web Open Font Format)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


Представляет тип шрифта WOFF2 (Web Open Font Format version 2)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


Представляет тип шрифта TTF (TrueType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


Представляет тип шрифта OTF (OpenType Font)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


Представляет шрифт TrueType Collection (TTC)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


Представляет тип шрифта EOT (Embedded OpenType)


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


Возвращает совместимое с CSS имя этого типа шрифта, которое используется в


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Возвращает официальное имя этого типа шрифта


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Расширение имени файла (без символа точки) для этого типа шрифта


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


Формат шрифта для формата @font-face


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME‑код конкретного типа шрифта


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


Возвращает значение FontType, которое эквивалентно указанному CSS‑compatible
имя типа шрифта


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | name | java.lang.String | CSS‑compatible имя типа шрифта |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


Возвращает значение FontType, которое эквивалентно расширению имени файла, которое
извлекается из указанного имени файла


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя файла | java.lang.String | Имя файла с расширением, может быть полным именем |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


Возвращает значение FontType, которое эквивалентно указанному MIME‑code


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME‑code |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


Возвращает первый тип шрифта из указанного набора, который не является "Undefined"
значение, или тип шрифта "Undefined" в противном случае (когда все элементы
"Undefined")


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Один или несколько значений FontType, NULL или пустая коллекция не допускаются |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


Определяет, равен ли данный экземпляр указанному "FontType"
экземпляр


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Другой экземпляр FontType для проверки с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр указанному неконвертированному объекту,
который, предположительно, является другим экземпляром "FontType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой экземпляр, предположительно, структуры FontType, упакованный в System.Object |
|

**Returns:**
boolean - True, если равны, false, если не равны

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


Проверяет, равны ли два значения "FontType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Первый FontType для проверки |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Второй FontType для проверки |
|

**Returns:**
boolean - True, если равны, false, если не равны

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


Проверяет, не равны ли два значения "FontType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Первый FontType для проверки |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | Второй FontType для проверки |
|

**Returns:**
boolean - True, если равны, false, если не равны

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код, который является постоянным числом для этого конкретного значения
тип


**Returns:**
int — 4‑байтовое знаковое целое, 0 для значения Undefined

