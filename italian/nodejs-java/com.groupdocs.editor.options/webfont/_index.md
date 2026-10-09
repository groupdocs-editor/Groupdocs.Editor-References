---
title: "WebFont"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta le impostazioni dei font per il web"
type: docs
weight: 43
url: /it/nodejs-java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Rappresenta le impostazioni dei font per il web

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getColor()](#getColor--) | Colore del carattere in formato ARGB32 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Colore del carattere in formato ARGB32 |
|
|  | [getWeight()](#getWeight--) | Imposta il peso (o il grassetto) del carattere |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Imposta il peso (o il grassetto) del carattere |
|
|  | [getStyle()](#getStyle--) | Imposta se un carattere deve essere stilizzato con una forma normale, corsiva o obliqua dalla sua famiglia di caratteri. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Imposta se un carattere deve essere stilizzato con una forma normale, corsiva o obliqua dalla sua famiglia di caratteri. |
|
|  | [getLine()](#getLine--) | Imposta una linea o una combinazione di linee, applicata al testo |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Imposta una linea o una combinazione di linee, applicata al testo |
|
|  | [getSize()](#getSize--) | Imposta la dimensione del carattere in unità assolute o relative |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Imposta la dimensione del carattere in unità assolute o relative |
|
|  | [getName()](#getName--) | Imposta il nome del carattere. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Imposta il nome del carattere. |
|
|  | [deepClone()](#deepClone--) | Crea e restituisce una copia profonda completa di questa istanza [WebFont](../../com.groupdocs.editor.options/webfont) |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | Determina se questa istanza di WebFont è uguale a quella specificata |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza di WebFont è uguale all'oggetto non convertito specificato |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


Colore del carattere in formato ARGB32


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


Colore del carattere in formato ARGB32


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


Imposta il peso (o il grassetto) del carattere


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


Imposta il peso (o il grassetto) del carattere


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


Imposta se un carattere deve essere stilizzato con una forma normale, corsiva o obliqua dalla sua famiglia di caratteri.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


Imposta se un carattere deve essere stilizzato con una forma normale, corsiva o obliqua dalla sua famiglia di caratteri.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


Imposta una linea o una combinazione di linee, applicata al testo


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


Imposta una linea o una combinazione di linee, applicata al testo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


Imposta la dimensione del carattere in unità assolute o relative


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


Imposta la dimensione del carattere in unità assolute o relative


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


Imposta il nome del carattere. Se non specificato, verrà utilizzato il carattere predefinito


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Imposta il nome del carattere. Se non specificato, verrà utilizzato il carattere predefinito


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


Crea e restituisce una copia profonda completa di questa istanza [WebFont](../../com.groupdocs.editor.options/webfont)


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


Determina se questa istanza di WebFont è uguale a quella specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | Un altro WebFont per verificare l'uguaglianza, può essere NULL |
|

**Returns:**
boolean - vero se uguale, falso se diverso

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza di WebFont è uguale all'oggetto non convertito specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Oggetto, che ci si aspetta sia un'istanza di [WebFont](../../com.groupdocs.editor.options/webfont) |
|

**Returns:**
boolean - vero se uguale, falso se diverso

