---
title: "WebFont"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar en teckensnittsinställning för webben."
type: docs
weight: 43
url: /sv/nodejs-java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Representerar en teckensnittsinställning för webben.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getColor()](#getColor--) | Teckensnittsfärg i ARGB32-format |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Teckensnittsfärg i ARGB32-format |
|
|  | [getWeight()](#getWeight--) | Ställer in vikten (eller fetstil) för teckensnittet |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Ställer in vikten (eller fetstil) för teckensnittet |
|
|  | [getStyle()](#getStyle--) | Ställer in om ett teckensnitt ska stiliseras med normal, kursiv eller sned stil från dess teckensnittsfamilj. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Ställer in om ett teckensnitt ska stiliseras med normal, kursiv eller sned stil från dess teckensnittsfamilj. |
|
|  | [getLine()](#getLine--) | Ställer in en linje eller kombination av linjer som tillämpas på texten |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Ställer in en linje eller kombination av linjer som tillämpas på texten |
|
|  | [getSize()](#getSize--) | Ställer in storleken på teckensnittet i absoluta eller relativa enheter |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Ställer in storleken på teckensnittet i absoluta eller relativa enheter |
|
|  | [getName()](#getName--) | Ställer in teckensnittets namn. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ställer in teckensnittets namn. |
|
|  | [deepClone()](#deepClone--) | Skapar och returnerar en fullständig djupkopiering av detta [WebFont](../../com.groupdocs.editor.options/webfont)-instans |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Bestämmer om denna instans av WebFont är lika med den angivna |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om denna instans av WebFont är lika med det angivna okastade objektet |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Teckensnittsfärg i ARGB32-format


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Teckensnittsfärg i ARGB32-format


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Ställer in vikten (eller fetstil) för teckensnittet


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Ställer in vikten (eller fetstil) för teckensnittet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Ställer in om ett teckensnitt ska stiliseras med normal, kursiv eller sned stil från dess teckensnittsfamilj.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Ställer in om ett teckensnitt ska stiliseras med normal, kursiv eller sned stil från dess teckensnittsfamilj.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Ställer in en linje eller kombination av linjer som tillämpas på texten


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Ställer in en linje eller kombination av linjer som tillämpas på texten


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Ställer in storleken på teckensnittet i absoluta eller relativa enheter


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Ställer in storleken på teckensnittet i absoluta eller relativa enheter


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Ställer in teckensnittets namn. Om det inte anges används standardteckensnittet


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ställer in teckensnittets namn. Om det inte anges används standardteckensnittet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Skapar och returnerar en fullständig djupkopiering av detta [WebFont](../../com.groupdocs.editor.options/webfont)-instans


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Bestämmer om denna instans av WebFont är lika med den angivna


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | En annan WebFont för att kontrollera likhet, kan vara NULL |
|

**Returns:**
boolean - true om lika, false om olika

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om denna instans av WebFont är lika med det angivna okastade objektet


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Objekt, som förväntas vara en [WebFont](../../com.groupdocs.editor.options/webfont)-instans |
|

**Returns:**
boolean - true om lika, false om olika

