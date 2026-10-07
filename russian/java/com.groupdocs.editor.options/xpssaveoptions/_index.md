---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для создания и сохранения документов XPS XML Paper Specifications"
type: docs
weight: 54
url: /ru/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Позволяет указать пользовательские параметры для создания и сохранения документов XPS (XML Paper Specifications)

<br />

*** ** * ** ***

Файл XPS представляет собой файлы разметки страниц, основанные на XML Paper Specifications, созданные Microsoft. Он был разработан как замена формата EMF и похож на формат PDF, но использует XML для описания разметки, внешнего вида и печатной информации документа.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Отвечает за встраивание ресурсов шрифтов в получающийся документ XPS, которые используются в оригинальном документе. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Отвечает за встраивание ресурсов шрифтов в получающийся документ XPS, которые используются в оригинальном документе.
По умолчанию не встраивает шрифты (NotEmbed).


**Returns:**
байт
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти.
Установка этой опции в true может значительно уменьшить потребление памяти при генерации больших документов за счёт более медленного времени сохранения.
По умолчанию false (оптимизация памяти отключена ради лучшей производительности).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти.
Установка этой опции в true может значительно уменьшить потребление памяти при генерации больших документов за счёт более медленного времени сохранения.
По умолчанию false (оптимизация памяти отключена ради лучшей производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

