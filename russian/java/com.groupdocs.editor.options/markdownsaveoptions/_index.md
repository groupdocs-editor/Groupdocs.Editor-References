---
title: "MarkdownSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет задавать пользовательские параметры для создания и сохранения документов Markdown."
type: docs
weight: 24
url: /ru/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Позволяет задавать пользовательские параметры для создания и сохранения документов Markdown.

<br />

*** ** * ** ***

Класс MarkdownSaveOptions должен быть применён пользователем, когда существует экземпляр класса EditableDocument, содержащий отредактированное содержимое документа, и требуется сохранить это содержимое в новый документ формата Markdown.

<br />


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow указывает, как выравнивать содержимое таблиц при экспорте в формат Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow указывает, как выравнивать содержимое таблиц при экспорте в формат Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Указывает физическую папку, в которой сохраняются изображения при экспорте документа в |
формат Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Указывает физическую папку, в которой сохраняются изображения при экспорте документа в |
формат Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Указывает, сохраняются ли изображения в формате Base64 в выходном файле. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Указывает, сохраняются ли изображения в формате Base64 в выходном файле. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти.
Установка этой опции в
true
может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения.
По умолчанию:
false
(оптимизация памяти отключена в целях повышения производительности).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Включает механизмы оптимизации памяти при генерации документа из HTML, что снижает производительность в качестве цены за уменьшение использования памяти.
Установка этой опции в
true
может значительно снизить потребление памяти при генерации больших документов за счёт более медленного времени сохранения.
По умолчанию:
false
(оптимизация памяти отключена в целях повышения производительности).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow указывает, как выравнивать содержимое таблиц при экспорте в формат Markdown.
Значение по умолчанию: [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Значение: выравнивание содержимого таблицы


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow указывает, как выравнивать содержимое таблиц при экспорте в формат Markdown.
Значение по умолчанию: [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Значение: выравнивание содержимого таблицы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Указывает физическую папку, в которой сохраняются изображения при экспорте документа в
формат Markdown. По умолчанию null.

<br />

*** ** * ** ***

Если пользователь не указывает ни ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)), ни ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)), то GroupDocs.Editor попытается самостоятельно определить ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) и применит его при успешном определении

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Указывает физическую папку, в которой сохраняются изображения при экспорте документа в
формат Markdown. По умолчанию null.

<br />

*** ** * ** ***

Если пользователь не указывает ни ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)), ни ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)), то GroupDocs.Editor попытается самостоятельно определить ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) и применит его при успешном определении

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Указывает, сохраняются ли изображения в формате Base64 в выходном файле. По умолчанию —
false
.

<br />

*** ** * ** ***

Когда это свойство установлено в  true , данные изображений экспортируются напрямую в элементы изображения ![](../) и отдельные файлы не создаются. Это свойство, если установлено в  true , имеет более высокий приоритет, чем свойство MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Указывает, сохраняются ли изображения в формате Base64 в выходном файле. По умолчанию —
false
.

<br />

*** ** * ** ***

Когда это свойство установлено в  true , данные изображений экспортируются напрямую в элементы изображения ![](../) и отдельные файлы не создаются. Это свойство, если установлено в  true , имеет более высокий приоритет, чем свойство MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

