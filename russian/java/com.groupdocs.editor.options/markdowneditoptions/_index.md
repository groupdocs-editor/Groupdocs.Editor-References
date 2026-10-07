---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет задавать пользовательские параметры для редактирования документов в формате Markdown."
type: docs
weight: 21
url: /ru/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Позволяет задавать пользовательские параметры для редактирования документов в формате Markdown.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Создаёт и возвращает новый экземпляр класса MarkdownEditOptions, |
где все параметры установлены в значения по умолчанию
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Позволяет контролировать, как сохраняются изображения при конвертации Markdown‑документа |
в Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Позволяет контролировать, как сохраняются изображения при конвертации Markdown‑документа |
в Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Создаёт и возвращает новый экземпляр класса MarkdownEditOptions,
где все параметры установлены в значения по умолчанию


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Позволяет контролировать, как сохраняются изображения при конвертации Markdown‑документа
в Html.
Значение: обратный вызов сохранения изображения.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Позволяет контролировать, как сохраняются изображения при конвертации Markdown‑документа
в Html.
Значение: обратный вызов сохранения изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

