---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Contiene opciones que permiten ajustar el formato del documento XML cuando se representa como HTML"
type: docs
weight: 52
url: /es/java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

Contiene opciones que permiten ajustar el formato del documento XML cuando se representa como HTML

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | Cuando está habilitado, cada par atributo-valor en cada elemento XML se colocará en una nueva línea. |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | Cuando está habilitado, cada par atributo-valor en cada elemento XML se colocará en una nueva línea. |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | Cuando está habilitado, los nodos de texto hoja (contenido textual dentro de los elementos XML que no tienen hijos) se renderizarán en una nueva línea con una sangría izquierda mayor. |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | Cuando está habilitado, los nodos de texto hoja (contenido textual dentro de los elementos XML que no tienen hijos) se renderizarán en una nueva línea con una sangría izquierda mayor. |
|
|  | [getLeftIndent()](#getLeftIndent--) | Permite especificar un desplazamiento para la sangría izquierda de cada nueva línea. |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Permite especificar un desplazamiento para la sangría izquierda de cada nueva línea. |
|
|  | [isDefault()](#isDefault--) | Indica si esta instancia de opciones de formato XML tiene un valor predeterminado |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


Cuando está habilitado, cada par atributo-valor en cada elemento XML se colocará en una nueva línea.
Por defecto es false (deshabilitado) \\u2014 todos los pares atributo-valor se colocan en una sola línea.


**Returns:**
boolean
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


Cuando está habilitado, cada par atributo-valor en cada elemento XML se colocará en una nueva línea.
Por defecto es false (deshabilitado) \\u2014 todos los pares atributo-valor se colocan en una sola línea.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


Cuando está habilitado, los nodos de texto hoja (contenido textual dentro de los elementos XML que no tienen hijos) se renderizarán en una nueva línea con una sangría izquierda mayor.
Por defecto es false (deshabilitado) \\u2014 los nodos de texto hoja se colocan en la misma línea que sus padres, sin nueva sangría.


**Returns:**
boolean
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


Cuando está habilitado, los nodos de texto hoja (contenido textual dentro de los elementos XML que no tienen hijos) se renderizarán en una nueva línea con una sangría izquierda mayor.
Por defecto es false (deshabilitado) \\u2014 los nodos de texto hoja se colocan en la misma línea que sus padres, sin nueva sangría.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


Permite especificar un desplazamiento para la sangría izquierda de cada nueva línea. No puede ser un valor sin unidades distinto de cero. Por defecto es 10pt


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


Permite especificar un desplazamiento para la sangría izquierda de cada nueva línea. No puede ser un valor sin unidades distinto de cero. Por defecto es 10pt


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica si esta instancia de opciones de formato XML tiene un valor predeterminado


**Returns:**
boolean
