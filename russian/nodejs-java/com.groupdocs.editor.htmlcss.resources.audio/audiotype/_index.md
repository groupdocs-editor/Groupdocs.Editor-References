---
title: "AudioType"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет один поддерживаемый формат аудио‑типа"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.audio/audiotype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class AudioType implements IResourceType
```

Представляет один поддерживаемый тип аудио (формат)

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AudioType()](#AudioType--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFormalName()](#getFormalName--) | Официальное название этого аудио‑формата |
|
|  | [getFileExtension()](#getFileExtension--) | Расширение имени файла (без символа точки) для этого аудио‑формата |
|
|  | [getMimeCode()](#getMimeCode--) | MIME‑код для этого аудио‑формата |
|
|  | [equals(AudioType other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Определяет, равен ли данный экземпляр указанному экземпляру "AudioType" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "AudioType" |
|
|  | [op_Equality(AudioType first, AudioType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Проверяет, равны ли два значения "AudioType" |
|
|  | [op_Inequality(AudioType first, AudioType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-) | Проверяет, не равны ли два значения "AudioType" |
|
|  | [hashCode()](#hashCode--) | Возвращает хеш‑код, который является постоянным числом для данного конкретного типа значения |
|
|  | [getUndefined()](#getUndefined--) | Специальное значение, обозначающее неопределённый, неизвестный или неподдерживаемый аудио‑формат |
|
|  | [getMp3()](#getMp3--) | Представляет аудио‑формат MPEG‑1 Audio Layer III |
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Возвращает значение AudioType, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла |
|
### AudioType() {#AudioType--}
```
public AudioType()
```


### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Официальное название этого аудио‑формата


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Расширение имени файла (без символа точки) для этого аудио‑формата


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME‑код для этого аудио‑формата


**Returns:**
java.lang.String
### equals(AudioType other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public final boolean equals(AudioType other)
```


Определяет, равен ли данный экземпляр указанному экземпляру "AudioType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Другой экземпляр AudioType для проверки с этим |
|

**Returns:**
boolean - True, если равны, false, если не равны

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "AudioType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | obj | java.lang.Object | Другой экземпляр, предположительно структуры AudioType, который был упакован в System.Object |
|

**Returns:**
boolean - True, если равны, false, если не равны

### op_Equality(AudioType first, AudioType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Equality(AudioType first, AudioType second)
```


Проверяет, равны ли два значения "AudioType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Первый AudioType для проверки |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Второй AudioType для проверки |
|

**Returns:**
boolean - True, если равны, false, если не равны

### op_Inequality(AudioType first, AudioType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.audio.AudioType-com.groupdocs.editor.htmlcss.resources.audio.AudioType-}
```
public static boolean op_Inequality(AudioType first, AudioType second)
```


Проверяет, не равны ли два значения "AudioType"


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | first | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Первый AudioType для проверки |
|
|  | second | [AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) | Второй AudioType для проверки |
|

**Returns:**
boolean - True, если равны, false, если не равны

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код, который является постоянным числом для данного конкретного типа значения


**Returns:**
int — 4‑байтовое знаковое целое, 0 для значения Undefined

### getUndefined() {#getUndefined--}
```
public static AudioType getUndefined()
```


Специальное значение, обозначающее неопределённый, неизвестный или неподдерживаемый аудио‑формат


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getMp3() {#getMp3--}
```
public static AudioType getMp3()
```


Представляет аудио‑формат MPEG‑1 Audio Layer III


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static AudioType parseFromFilenameWithExtension(String filename)
```


Возвращает значение AudioType, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | имя файла | java.lang.String | Произвольное имя файла, может быть относительным или полным путём |
|

**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype) - AudioType value. Returns AudioType.Undefined, if extension cannot be recognized.

