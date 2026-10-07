---
title: "MarkdownEditOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para editar documentos en formato Markdown."
type: docs
weight: 21
url: /es/java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para editar documentos en formato Markdown.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | Crea y devuelve una nueva instancia de la clase MarkdownEditOptions, |
donde todas las opciones están configuradas a sus valores predeterminados
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Permite controlar cómo se guardan las imágenes al convertir un documento Markdown |
a Html.
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Permite controlar cómo se guardan las imágenes al convertir un documento Markdown |
a Html.
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


Crea y devuelve una nueva instancia de la clase MarkdownEditOptions,
donde todas las opciones están configuradas a sus valores predeterminados


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Permite controlar cómo se guardan las imágenes al convertir un documento Markdown
a Html.
Valor: La devolución de llamada de guardado de imagen.


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Permite controlar cómo se guardan las imágenes al convertir un documento Markdown
a Html.
Valor: La devolución de llamada de guardado de imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

