---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Содержит параметры, позволяющие настроить форматирование XML‑документа при его представлении в виде HTML"
type: docs
weight: 52
url: /ru/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Содержит параметры, позволяющие настроить форматирование XML‑документа, когда он представлен в виде HTML

## Методы

| Метод | Описание |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Если включено, каждая пара атрибут‑значение в каждом XML‑элементе будет размещена на новой строке. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Если включено, каждая пара атрибут‑значение в каждом XML‑элементе будет размещена на новой строке. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Если включено, листовые текстовые узлы (текстовое содержимое внутри XML‑элементов, не имеющих дочерних элементов) будут выводиться на новой строке с большим отступом слева. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Если включено, листовые текстовые узлы (текстовое содержимое внутри XML‑элементов, не имеющих дочерних элементов) будут выводиться на новой строке с большим отступом слева. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Позволяет задать смещение для левого отступа каждой новой строки. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Позволяет задать смещение для левого отступа каждой новой строки. |
|
|  | [isDefault()](#isDefault--) | Указывает, имеет ли данный экземпляр параметров форматирования XML значение по умолчанию |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Если включено, каждая пара атрибут‑значение в каждом XML‑элементе будет размещена на новой строке.
По умолчанию false (отключено) \u2014 все пары атрибут‑значение размещаются в одной строке.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Если включено, каждая пара атрибут‑значение в каждом XML‑элементе будет размещена на новой строке.
По умолчанию false (отключено) \u2014 все пары атрибут‑значение размещаются в одной строке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Если включено, листовые текстовые узлы (текстовое содержимое внутри XML‑элементов, не имеющих дочерних элементов) будут выводиться на новой строке с большим отступом слева.
По умолчанию false (отключено) \u2014 листовые текстовые узлы размещаются в той же строке, что и их родители, без нового отступа.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Если включено, листовые текстовые узлы (текстовое содержимое внутри XML‑элементов, не имеющих дочерних элементов) будут выводиться на новой строке с большим отступом слева.
По умолчанию false (отключено) \u2014 листовые текстовые узлы размещаются в той же строке, что и их родители, без нового отступа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Позволяет задать смещение для левого отступа каждой новой строки. Не может быть безразмерным ненулевым значением. По умолчанию 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Позволяет задать смещение для левого отступа каждой новой строки. Не может быть безразмерным ненулевым значением. По умолчанию 10pt


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Указывает, имеет ли данный экземпляр параметров форматирования XML значение по умолчанию


**Returns:**
boolean
