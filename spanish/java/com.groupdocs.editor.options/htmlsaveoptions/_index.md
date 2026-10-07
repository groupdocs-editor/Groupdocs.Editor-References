---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para guardar la instancia en el formato HTML"
type: docs
weight: 19
url: /es/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

Permite especificar opciones personalizadas para guardar la instancia de [EditableDocument](../../com.groupdocs.editor/editabledocument) en el formato HTML

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | Controla cómo se presentarán los nombres de etiquetas HTML en el marcado HTML: todo en minúsculas (valor predeterminado), todo en mayúsculas o la primera letra en mayúscula |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | Controla cómo se presentarán los nombres de etiquetas HTML en el marcado HTML: todo en minúsculas (valor predeterminado), todo en mayúsculas o la primera letra en mayúscula |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | Controla qué delimitador se usará alrededor de los valores de los atributos en los elementos HTML: comilla simple (valor predeterminado) o comilla doble |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | Controla qué delimitador se usará alrededor de los valores de los atributos en los elementos HTML: comilla simple (valor predeterminado) o comilla doble |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | Controla dónde almacenar la(s) hoja(s) de estilo CSS: como recursos externos ( |
false
), o incrustarlos en el marcado HTML, dentro del elemento STYLE en la sección HTML-\>HEAD (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | Controla dónde almacenar la(s) hoja(s) de estilo CSS: como recursos externos ( |
false
), o incrustarlos en el marcado HTML, dentro del elemento STYLE en la sección HTML-\>HEAD (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


Controla cómo se presentarán los nombres de etiquetas HTML en el marcado HTML: todo en minúsculas (valor predeterminado), todo en mayúsculas o la primera letra en mayúscula


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


Controla cómo se presentarán los nombres de etiquetas HTML en el marcado HTML: todo en minúsculas (valor predeterminado), todo en mayúsculas o la primera letra en mayúscula


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


Controla qué delimitador se usará alrededor de los valores de los atributos en los elementos HTML: comilla simple (valor predeterminado) o comilla doble


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


Controla qué delimitador se usará alrededor de los valores de los atributos en los elementos HTML: comilla simple (valor predeterminado) o comilla doble


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


Controla dónde almacenar la(s) hoja(s) de estilo CSS: como recursos externos (
false
), o incrustarlos en el marcado HTML, dentro del elemento STYLE en la sección HTML-\>HEAD (
true
)


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


Controla dónde almacenar la(s) hoja(s) de estilo CSS: como recursos externos (
false
), o incrustarlos en el marcado HTML, dentro del elemento STYLE en la sección HTML-\>HEAD (
true
)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


Interfaz que debe ser implementada por el usuario final para guardar todos los recursos HTML externos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

