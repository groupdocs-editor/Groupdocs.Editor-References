---
title: "MarkdownSaveOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para generar y guardar documentos Markdown"
type: docs
weight: 24
url: /es/nodejs-java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar documentos Markdown

<br />

*** ** * ** ***

La clase MarkdownSaveOptions debe ser aplicada por el usuario cuando hay una instancia de la clase EditableDocument, que contiene el contenido de un documento editado, y se requiere guardar este contenido en el nuevo documento con formato Markdown.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow especifica cómo alinear el contenido en tablas al exportar al formato Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow especifica cómo alinear el contenido en tablas al exportar al formato Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | Especifica la carpeta física donde se guardan las imágenes al exportar un documento a |
el formato Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | Especifica la carpeta física donde se guardan las imágenes al exportar un documento a |
el formato Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | Especifica si las imágenes se guardan en formato Base64 en el archivo de salida. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | Especifica si las imágenes se guardan en formato Base64 en el archivo de salida. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción a
true
puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es
false
(la optimización de memoria está desactivada para lograr un mejor rendimiento).


**Returns:**
booleano
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción a
true
puede disminuir significativamente el consumo de memoria al generar documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es
false
(la optimización de memoria está desactivada para lograr un mejor rendimiento).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow especifica cómo alinear el contenido en tablas al exportar al formato Markdown.
El valor predeterminado es [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Valor: la alineación del contenido de la tabla


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow especifica cómo alinear el contenido en tablas al exportar al formato Markdown.
El valor predeterminado es [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
Valor: la alineación del contenido de la tabla


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


Especifica la carpeta física donde se guardan las imágenes al exportar un documento a
el formato Markdown. El valor predeterminado es null.

<br />

*** ** * ** ***

Si ni el ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ni el ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) son especificados por el usuario, entonces GroupDocs.Editor intentará determinar el ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) por sí mismo y lo aplicará si tiene éxito.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


Especifica la carpeta física donde se guardan las imágenes al exportar un documento a
el formato Markdown. El valor predeterminado es null.

<br />

*** ** * ** ***

Si ni el ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ni el ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) son especificados por el usuario, entonces GroupDocs.Editor intentará determinar el ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) por sí mismo y lo aplicará si tiene éxito.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


Especifica si las imágenes se guardan en formato Base64 en el archivo de salida. El valor predeterminado es
false
.

<br />

*** ** * ** ***

Cuando esta propiedad se establece en true, los datos de las imágenes se exportan directamente a los elementos de imagen ![](../) y no se crean archivos separados. Esta propiedad, si se establece en true, tiene mayor prioridad que la propiedad MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Returns:**
booleano
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


Especifica si las imágenes se guardan en formato Base64 en el archivo de salida. El valor predeterminado es
false
.

<br />

*** ** * ** ***

Cuando esta propiedad se establece en true, los datos de las imágenes se exportan directamente a los elementos de imagen ![](../) y no se crean archivos separados. Esta propiedad, si se establece en true, tiene mayor prioridad que la propiedad MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)).

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

