---
title: "DocumentFormatBase"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет базовый класс для форматов документов, предоставляющий общую функциональность для экземпляров форматов."
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.formats.abstraction/documentformatbase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.formats.abstraction.FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)

**All Implemented Interfaces:**
[com.groupdocs.editor.formats.abstraction.IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat)
```
public abstract class DocumentFormatBase extends FormatFamilyBase implements IDocumentFormat
```

Представляет базовый класс для форматов документов, предоставляющий общую функциональность для экземпляров форматов.

## Методы

| Метод | Описание |
| --- | --- |
|  | [getMime()](#getMime--) | Возвращает MIME-тип формата документа. |
|
|  | [getExtension()](#getExtension--) | Возвращает расширение файла формата документа. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Возвращает семейство форматов, к которому принадлежит формат документа. |
|
|  | [<T>fromMime(Class<T> clazz, String mime)](#-T-fromMime-java.lang.Class-T--java.lang.String-) | Получает экземпляр указанного типа. |
T
который имеет указанный MIME type.
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код для текущего объекта. |
|
|  | [equals(IDocumentFormat other)](#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-) | Определяет, равен ли данный экземпляр указанному экземпляру [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat). |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр указанному экземпляру [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase). |
|
|  | [toString(DocumentFormatBase extension)](#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-) | Неявно преобразует экземпляр [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) в строку. |
|
### getMime() {#getMime--}
```
public final String getMime()
```


Возвращает MIME-тип формата документа.


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Возвращает расширение файла формата документа.


**Returns:**
java.lang.String
### getFormatFamily() {#getFormatFamily--}
```
public final FormatFamilies getFormatFamily()
```


Возвращает семейство форматов, к которому принадлежит формат документа.


**Returns:**
[FormatFamilies](../../com.groupdocs.editor.formats/formatfamilies)
### <T>fromMime(Class<T> clazz, String mime) {#-T-fromMime-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromMime(Class<T> clazz, String mime)
```


Получает экземпляр указанного типа.
T
который имеет указанный MIME type.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | mime | java.lang.String | MIME‑тип формата документа. |


T
: Тип формата документа.
|

**Returns:**
T - Экземпляр указанного типа T с указанным MIME‑типом.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для текущего объекта.


**Returns:**
int - Хеш‑код текущего объекта, объединяющий хеш‑коды базового объекта, MIME‑типа, расширения файла и семейства форматов.

### equals(IDocumentFormat other) {#equals-com.groupdocs.editor.formats.abstraction.IDocumentFormat-}
```
public final boolean equals(IDocumentFormat other)
```


Определяет, равен ли данный экземпляр указанному экземпляру [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) | Экземпляр [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) для сравнения с текущим экземпляром. |
|

**Returns:**
boolean -  true  если указанный [IDocumentFormat](../../com.groupdocs.editor.formats.abstraction/idocumentformat) равен текущему экземпляру; иначе  false .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр указанному экземпляру [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Экземпляр [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) для сравнения с текущим экземпляром. |
|

**Returns:**
boolean -  true  если указанный [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) равен текущему экземпляру; иначе  false .

### toString(DocumentFormatBase extension) {#toString-com.groupdocs.editor.formats.abstraction.DocumentFormatBase-}
```
public static String toString(DocumentFormatBase extension)
```


Неявно преобразует экземпляр [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) в строку.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | extension | [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) | Экземпляр [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase) для преобразования. |
|

**Returns:**
java.lang.String - Расширение файла экземпляра [DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase).

