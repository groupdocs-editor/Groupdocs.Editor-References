---
title: "WebFont"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa una configuración de fuentes para la web"
type: docs
weight: 43
url: /es/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Representa una configuración de fuentes para la web

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getColor()](#getColor--) | Color de fuente en formato ARGB32 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Color de fuente en formato ARGB32 |
|
|  | [getWeight()](#getWeight--) | Establece el grosor (o negrita) de la fuente |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Establece el grosor (o negrita) de la fuente |
|
|  | [getStyle()](#getStyle--) | Establece si una fuente debe mostrarse con un estilo normal, cursiva o oblicua a partir de su familia tipográfica. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Establece si una fuente debe mostrarse con un estilo normal, cursiva o oblicua a partir de su familia tipográfica. |
|
|  | [getLine()](#getLine--) | Establece una línea o combinación de líneas, aplicadas al texto |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Establece una línea o combinación de líneas, aplicadas al texto |
|
|  | [getSize()](#getSize--) | Establece el tamaño de la fuente en unidades absolutas o relativas |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Establece el tamaño de la fuente en unidades absolutas o relativas |
|
|  | [getName()](#getName--) | Establece el nombre de la fuente. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Establece el nombre de la fuente. |
|
|  | [deepClone()](#deepClone--) | Crea y devuelve una copia profunda completa de esta instancia de [WebFont](../../com.groupdocs.editor.options/webfont) |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Determina si esta instancia de WebFont es igual a la especificada |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia de WebFont es igual al objeto no convertido especificado |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Color de fuente en formato ARGB32


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Color de fuente en formato ARGB32


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Establece el grosor (o negrita) de la fuente


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Establece el grosor (o negrita) de la fuente


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Establece si una fuente debe mostrarse con un estilo normal, cursiva o oblicua a partir de su familia tipográfica.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Establece si una fuente debe mostrarse con un estilo normal, cursiva o oblicua a partir de su familia tipográfica.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Establece una línea o combinación de líneas, aplicadas al texto


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Establece una línea o combinación de líneas, aplicadas al texto


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Establece el tamaño de la fuente en unidades absolutas o relativas


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Establece el tamaño de la fuente en unidades absolutas o relativas


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Establece el nombre de la fuente. Si no se especifica, se utilizará la fuente predeterminada


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre de la fuente. Si no se especifica, se utilizará la fuente predeterminada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Crea y devuelve una copia profunda completa de esta instancia de [WebFont](../../com.groupdocs.editor.options/webfont)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Determina si esta instancia de WebFont es igual a la especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | Otro WebFont para comprobar la igualdad, puede ser NULL |
|

**Returns:**
boolean - true si es igual, false si es desigual

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia de WebFont es igual al objeto no convertido especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Objeto, que se espera sea una instancia de [WebFont](../../com.groupdocs.editor.options/webfont) |
|

**Returns:**
boolean - true si es igual, false si es desigual

