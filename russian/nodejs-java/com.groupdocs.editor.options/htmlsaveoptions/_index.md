---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Позволяет задавать пользовательские параметры для сохранения экземпляра в формате HTML"
type: docs
weight: 19
url: /ru/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Позволяет задавать пользовательские параметры для сохранения экземпляра [EditableDocument](../../com.groupdocs.editor/editabledocument) в формате HTML

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Определяет, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Определяет, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в HTML‑элементах: одинарная кавычка (значение по умолчанию) или двойная кавычка |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в HTML‑элементах: одинарная кавычка (значение по умолчанию) или двойная кавычка |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Управляет местом хранения CSS‑стилей: как внешние ресурсы ( |
false
) , или внедрить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Управляет местом хранения CSS‑стилей: как внешние ресурсы ( |
false
) , или внедрить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Определяет, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Определяет, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в HTML‑элементах: одинарная кавычка (значение по умолчанию) или двойная кавычка


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в HTML‑элементах: одинарная кавычка (значение по умолчанию) или двойная кавычка


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Управляет местом хранения CSS‑стилей: как внешние ресурсы (
false
) , или внедрить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Управляет местом хранения CSS‑стилей: как внешние ресурсы (
false
) , или внедрить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних HTML‑ресурсов


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

