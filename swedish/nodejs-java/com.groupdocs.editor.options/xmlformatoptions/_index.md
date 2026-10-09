---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Innehåller alternativ som möjliggör att justera formateringen av XML-dokument när det representeras som HTML"
type: docs
weight: 52
url: /sv/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Innehåller alternativ som tillåter att justera formateringen av XML-dokumentet när det representeras som HTML.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | När den är aktiverad kommer varje attribut‑värde‑par i varje XML‑element att placeras på en ny rad. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | När den är aktiverad kommer varje attribut‑värde‑par i varje XML‑element att placeras på en ny rad. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | När den är aktiverad kommer löv‑textnoder (textinnehåll inuti XML‑element som saknar barn) att renderas på en ny rad med större vänsterindrag. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | När den är aktiverad kommer löv‑textnoder (textinnehåll inuti XML‑element som saknar barn) att renderas på en ny rad med större vänsterindrag. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Tillåter att ange ett avstånd för vänsterindraget på varje ny rad. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Tillåter att ange ett avstånd för vänsterindraget på varje ny rad. |
|
|  | [isDefault()](#isDefault--) | Indikerar om detta exempel av XML‑formateringsalternativ har ett standardvärde |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


När den är aktiverad kommer varje attribut‑värde‑par i varje XML‑element att placeras på en ny rad.
Som standard är den falsk (inaktiverad) \\u2014 alla attribut‑värde‑par placeras på en enda rad.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


När den är aktiverad kommer varje attribut‑värde‑par i varje XML‑element att placeras på en ny rad.
Som standard är den falsk (inaktiverad) \\u2014 alla attribut‑värde‑par placeras på en enda rad.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


När den är aktiverad kommer löv‑textnoder (textinnehåll inuti XML‑element som saknar barn) att renderas på en ny rad med större vänsterindrag.
Som standard är den falsk (inaktiverad) \\u2014 löv‑textnoder placeras på samma rad som sina föräldrar, utan nytt indrag.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


När den är aktiverad kommer löv‑textnoder (textinnehåll inuti XML‑element som saknar barn) att renderas på en ny rad med större vänsterindrag.
Som standard är den falsk (inaktiverad) \\u2014 löv‑textnoder placeras på samma rad som sina föräldrar, utan nytt indrag.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Tillåter att ange ett avstånd för vänsterindraget på varje ny rad. Kan inte vara ett enhetslöst icke‑nollvärde. Som standard är 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Tillåter att ange ett avstånd för vänsterindraget på varje ny rad. Kan inte vara ett enhetslöst icke‑nollvärde. Som standard är 10pt


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indikerar om detta exempel av XML‑formateringsalternativ har ett standardvärde


**Returns:**
boolean
