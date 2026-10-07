---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Bevat opties die het mogelijk maken de opmaak van een XML-document aan te passen wanneer het wordt weergegeven als HTML"
type: docs
weight: 52
url: /nl/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Bevat opties die toelaten de opmaak van een XML-document aan te passen wanneer het wordt weergegeven als HTML

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Wanneer ingeschakeld, wordt elk attribuut‑waarde paar in elk XML‑element op een nieuwe regel geplaatst. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Wanneer ingeschakeld, wordt elk attribuut‑waarde paar in elk XML‑element op een nieuwe regel geplaatst. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Wanneer ingeschakeld, worden bladtekstknooppunten (tekstuele inhoud binnen XML‑elementen zonder kinderen) op een nieuwe regel weergegeven met een grotere linkerinspringing. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Wanneer ingeschakeld, worden bladtekstknooppunten (tekstuele inhoud binnen XML‑elementen zonder kinderen) op een nieuwe regel weergegeven met een grotere linkerinspringing. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Staat toe een offset voor de linkerinspringing van elke nieuwe regel op te geven. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Staat toe een offset voor de linkerinspringing van elke nieuwe regel op te geven. |
|
|  | [isDefault()](#isDefault--) | Geeft aan of deze instantie van XML-opmaakopties een standaardwaarde heeft |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Wanneer ingeschakeld, wordt elk attribuut‑waarde paar in elk XML‑element op een nieuwe regel geplaatst.
Standaard is false (uitgeschakeld) \\u2014 alle attribuut‑waarde paren worden op één regel geplaatst.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Wanneer ingeschakeld, wordt elk attribuut‑waarde paar in elk XML‑element op een nieuwe regel geplaatst.
Standaard is false (uitgeschakeld) \\u2014 alle attribuut‑waarde paren worden op één regel geplaatst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Wanneer ingeschakeld, worden bladtekstknooppunten (tekstuele inhoud binnen XML‑elementen zonder kinderen) op een nieuwe regel weergegeven met een grotere linkerinspringing.
Standaard is false (uitgeschakeld) \\u2014 bladtekstknooppunten worden op dezelfde regel als hun ouders geplaatst, zonder nieuwe inspringing.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Wanneer ingeschakeld, worden bladtekstknooppunten (tekstuele inhoud binnen XML‑elementen zonder kinderen) op een nieuwe regel weergegeven met een grotere linkerinspringing.
Standaard is false (uitgeschakeld) \\u2014 bladtekstknooppunten worden op dezelfde regel als hun ouders geplaatst, zonder nieuwe inspringing.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Staat toe een offset voor de linkerinspringing van elke nieuwe regel op te geven. Mag geen eenheidloze niet‑nul waarde zijn. Standaard is 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Staat toe een offset voor de linkerinspringing van elke nieuwe regel op te geven. Mag geen eenheidloze niet‑nul waarde zijn. Standaard is 10pt


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Geeft aan of deze instantie van XML-opmaakopties een standaardwaarde heeft


**Returns:**
boolean
