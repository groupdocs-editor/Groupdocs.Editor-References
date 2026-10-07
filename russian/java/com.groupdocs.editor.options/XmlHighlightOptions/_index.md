---
title: "XmlHighlightOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Содержит параметры, позволяющие настроить подсветку XML во время преобразования XML в HTML"
type: docs
weight: 53
url: /ru/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

Содержит параметры, позволяющие настроить подсветку XML при конвертации XML в HTML

## Методы

| Метод | Описание |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | Отвечает за отображение шрифта XML‑тегов (угловые скобки с именами тегов) |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | Отвечает за отображение шрифта имен атрибутов |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | Отвечает за отображение шрифта значений атрибутов |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | Отвечает за отображение шрифта текста внутри тегов |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | Отвечает за отображение шрифта комментариев HTML (включая пару открывающего и закрывающего тегов) |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | Отвечает за отображение шрифта секций CDATA (включая пару открывающего и закрывающего тегов) |
|
|  | [isDefault()](#isDefault--) | Определяет, имеет ли объект параметров подсветки XML настройки шрифта по умолчанию |
|
|  | [resetToDefault()](#resetToDefault--) | Сбрасывает текущие настройки шрифта к их значениям по умолчанию |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


Отвечает за отображение шрифта XML‑тегов (угловые скобки с именами тегов)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


Отвечает за отображение шрифта имен атрибутов


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


Отвечает за отображение шрифта значений атрибутов


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


Отвечает за отображение шрифта текста внутри тегов


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


Отвечает за отображение шрифта комментариев HTML (включая пару открывающего и закрывающего тегов)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


Отвечает за отображение шрифта секций CDATA (включая пару открывающего и закрывающего тегов)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Определяет, имеет ли объект параметров подсветки XML настройки шрифта по умолчанию


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


Сбрасывает текущие настройки шрифта к их значениям по умолчанию


