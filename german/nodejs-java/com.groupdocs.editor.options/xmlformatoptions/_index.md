---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Enthält Optionen, die es ermöglichen, die Formatierung von XML-Dokumenten anzupassen, wenn sie als HTML dargestellt werden"
type: docs
weight: 52
url: /de/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Enthält Optionen, die es ermöglichen, die Formatierung des XML-Dokuments anzupassen, wenn es als HTML dargestellt wird

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Wenn aktiviert, wird jedes Attribut‑Wert‑Paar in jedem XML-Element in einer neuen Zeile platziert. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Wenn aktiviert, wird jedes Attribut‑Wert‑Paar in jedem XML-Element in einer neuen Zeile platziert. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Wenn aktiviert, werden Blatt‑Textknoten (textueller Inhalt innerhalb von XML-Elementen, der keine Kinder hat) in einer neuen Zeile mit größerer linker Einrückung dargestellt. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Wenn aktiviert, werden Blatt‑Textknoten (textueller Inhalt innerhalb von XML-Elementen, der keine Kinder hat) in einer neuen Zeile mit größerer linker Einrückung dargestellt. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Ermöglicht die Angabe eines Versatzes für die linke Einrückung jeder neuen Zeile. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Ermöglicht die Angabe eines Versatzes für die linke Einrückung jeder neuen Zeile. |
|
|  | [isDefault()](#isDefault--) | Gibt an, ob diese Instanz der XML-Formatierungsoptionen einen Standardwert hat |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Wenn aktiviert, wird jedes Attribut‑Wert‑Paar in jedem XML-Element in einer neuen Zeile platziert.
Standardmäßig ist false (deaktiviert) \u2014 alle Attribut‑Wert‑Paare werden in einer einzigen Zeile platziert.


**Returns:**
boolesch
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Wenn aktiviert, wird jedes Attribut‑Wert‑Paar in jedem XML-Element in einer neuen Zeile platziert.
Standardmäßig ist false (deaktiviert) \u2014 alle Attribut‑Wert‑Paare werden in einer einzigen Zeile platziert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Wenn aktiviert, werden Blatt‑Textknoten (textueller Inhalt innerhalb von XML-Elementen, der keine Kinder hat) in einer neuen Zeile mit größerer linker Einrückung dargestellt.
Standardmäßig ist false (deaktiviert) \u2014 Blatt‑Textknoten werden in derselben Zeile wie ihre Eltern platziert, ohne neue Einrückung.


**Returns:**
boolesch
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Wenn aktiviert, werden Blatt‑Textknoten (textueller Inhalt innerhalb von XML-Elementen, der keine Kinder hat) in einer neuen Zeile mit größerer linker Einrückung dargestellt.
Standardmäßig ist false (deaktiviert) \u2014 Blatt‑Textknoten werden in derselben Zeile wie ihre Eltern platziert, ohne neue Einrückung.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Ermöglicht das Festlegen eines Versatzes für den linken Einzug jeder neuen Zeile. Darf kein einheitenloser, von null verschiedener Wert sein. Standardmäßig ist 10pt.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Ermöglicht das Festlegen eines Versatzes für den linken Einzug jeder neuen Zeile. Darf kein einheitenloser, von null verschiedener Wert sein. Standardmäßig ist 10pt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Gibt an, ob diese Instanz der XML-Formatierungsoptionen einen Standardwert hat


**Returns:**
boolesch
