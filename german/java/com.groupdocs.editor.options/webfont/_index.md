---
title: "WebFont"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt eine Schrifteinstellung für das Web dar."
type: docs
weight: 43
url: /de/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Stellt eine Schrifteinstellung für das Web dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getColor()](#getColor--) | Schriftfarbe im ARGB32-Format |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Schriftfarbe im ARGB32-Format |
|
|  | [getWeight()](#getWeight--) | Legt die Stärke (oder Fettdicke) der Schrift fest |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Legt die Stärke (oder Fettdicke) der Schrift fest |
|
|  | [getStyle()](#getStyle--) | Legt fest, ob eine Schriftart aus ihrer Schriftfamilie normal, kursiv oder schräg dargestellt werden soll. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Legt fest, ob eine Schriftart aus ihrer Schriftfamilie normal, kursiv oder schräg dargestellt werden soll. |
|
|  | [getLine()](#getLine--) | Setzt eine Linie oder eine Kombination von Linien, die auf den Text angewendet werden |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Setzt eine Linie oder eine Kombination von Linien, die auf den Text angewendet werden |
|
|  | [getSize()](#getSize--) | Legt die Größe der Schrift in absoluten oder relativen Einheiten fest |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Legt die Größe der Schrift in absoluten oder relativen Einheiten fest |
|
|  | [getName()](#getName--) | Legt den Schriftartnamen fest. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Legt den Schriftartnamen fest. |
|
|  | [deepClone()](#deepClone--) | Erstellt und gibt eine vollständige tiefe Kopie dieser [WebFont](../../com.groupdocs.editor.options/webfont)-Instanz zurück |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Bestimmt, ob diese Instanz von WebFont gleich dem angegebenen ist |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz von WebFont dem angegebenen nicht gecasteten Objekt gleich ist |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Schriftfarbe im ARGB32-Format


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Schriftfarbe im ARGB32-Format


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Legt die Stärke (oder Fettdicke) der Schrift fest


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Legt die Stärke (oder Fettdicke) der Schrift fest


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Legt fest, ob eine Schriftart aus ihrer Schriftfamilie normal, kursiv oder schräg dargestellt werden soll.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Legt fest, ob eine Schriftart aus ihrer Schriftfamilie normal, kursiv oder schräg dargestellt werden soll.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Setzt eine Linie oder eine Kombination von Linien, die auf den Text angewendet werden


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Setzt eine Linie oder eine Kombination von Linien, die auf den Text angewendet werden


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Legt die Größe der Schrift in absoluten oder relativen Einheiten fest


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Legt die Größe der Schrift in absoluten oder relativen Einheiten fest


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Legt den Schriftartnamen fest. Wenn nicht angegeben, wird die Standardschriftart verwendet


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Legt den Schriftartnamen fest. Wenn nicht angegeben, wird die Standardschriftart verwendet


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Erstellt und gibt eine vollständige tiefe Kopie dieser [WebFont](../../com.groupdocs.editor.options/webfont)-Instanz zurück


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Bestimmt, ob diese Instanz von WebFont gleich dem angegebenen ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | Ein weiteres WebFont zum Prüfen der Gleichheit, kann NULL sein |
|

**Returns:**
boolean - true, wenn gleich, false, wenn ungleich

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz von WebFont dem angegebenen nicht gecasteten Objekt gleich ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Objekt, das voraussichtlich eine [WebFont](../../com.groupdocs.editor.options/webfont)-Instanz ist |
|

**Returns:**
boolean - true, wenn gleich, false, wenn ungleich

