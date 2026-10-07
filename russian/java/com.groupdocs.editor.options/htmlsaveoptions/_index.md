---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для сохранения экземпляра в формате HTML"
type: docs
weight: 19
url: /ru/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Позволяет указать пользовательские параметры для сохранения экземпляра [EditableDocument](../../com.groupdocs.editor/editabledocument) в формате HTML

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Управляет тем, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Управляет тем, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в элементах HTML: одинарная кавычка (значение по умолчанию) или двойная кавычка |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в элементах HTML: одинарная кавычка (значение по умолчанию) или двойная кавычка |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Управляет тем, где хранить CSS‑таблицы стилей: как внешние ресурсы ( |
false
) , или встроить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Управляет тем, где хранить CSS‑таблицы стилей: как внешние ресурсы ( |
false
) , или встроить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних ресурсов HTML |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних ресурсов HTML |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Управляет тем, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Управляет тем, как имена HTML‑тегов будут отображаться в разметке HTML: все строчные (значение по умолчанию), все заглавные или первая буква заглавная


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в элементах HTML: одинарная кавычка (значение по умолчанию) или двойная кавычка


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Управляет тем, какой разделитель будет использоваться вокруг значений атрибутов в элементах HTML: одинарная кавычка (значение по умолчанию) или двойная кавычка


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Управляет тем, где хранить CSS‑таблицы стилей: как внешние ресурсы (
false
) , или встроить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Управляет тем, где хранить CSS‑таблицы стилей: как внешние ресурсы (
false
) , или встроить их в разметку HTML, внутри элемента STYLE в секции HTML-\>HEAD (
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


Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних ресурсов HTML


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Интерфейс, который должен быть реализован конечным пользователем для сохранения всех внешних ресурсов HTML


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

