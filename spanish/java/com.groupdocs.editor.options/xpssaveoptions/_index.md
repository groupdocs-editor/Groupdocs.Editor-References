---
title: "XpsSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para generar y guardar documentos XPS XML Paper Specifications"
type: docs
weight: 54
url: /es/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar documentos XPS (XML Paper Specifications)

<br />

*** ** * ** ***

Un archivo XPS representa archivos de diseño de página que se basan en XML Paper Specifications creadas por Microsoft. Fue desarrollado como reemplazo del formato de archivo EMF y es similar al formato de archivo PDF, pero utiliza XML en el diseño, la apariencia y la información de impresión de un documento.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsable de incrustar recursos de fuentes en el documento XPS resultante, que se utilizan en el documento original. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


Responsable de incrustar recursos de fuentes en el documento XPS resultante, que se utilizan en el documento original.
Por defecto no incrusta ninguna fuente (NotEmbed).


**Returns:**
byte
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción en true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción en true puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es false (la optimización de memoria está deshabilitada para lograr un mejor rendimiento).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

