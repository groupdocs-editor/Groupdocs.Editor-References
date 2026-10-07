---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar y ajustar opciones personalizadas para editar documentos de libros electrónicos en todos los formatos compatibles ePub, MOBI y AZW3."
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

Permite especificar y ajustar opciones personalizadas para editar documentos de libros electrónicos en todos los formatos compatibles: ePub, MOBI y AZW3.

<br />

*** ** * ** ***

Formatos de E-book compatibles:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (Publicación electrónica)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Formato Kindle 8t)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | Inicializa una nueva instancia de la clase [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), donde todas las opciones se establecen a sus valores predeterminados |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | Inicializa una nueva instancia de la clase [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) con el modo de paginación especificado |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Especifica si la información de idioma se exporta al marcado HTML en forma de atributos HTML 'lang'. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Especifica si la información de idioma se exporta al marcado HTML en forma de atributos HTML 'lang'. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


Inicializa una nueva instancia de la clase [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions), donde todas las opciones se establecen a sus valores predeterminados


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


Inicializa una nueva instancia de la clase [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) con el modo de paginación especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | enablePagination | boolean | Habilita ( true ) o deshabilita ( false ) la paginación del contenido del libro electrónico en el documento HTML resultante. Por defecto está deshabilitada ( false ). |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitada (
false
).

<br />

*** ** * ** ***

En esencia, la mayoría de los formatos de libros electrónicos son internamente un formato de flujo como Office Open XML, donde el contenido es sólido y se divide en capítulos pero no en páginas. Sin embargo, contiene información específica de página como números de página, notas al pie, encabezados/pies de página, etc. Algunos lectores de libros electrónicos dividen el contenido del libro en páginas, mientras que otros (especialmente móviles) \\u2014 no. Esta opción permite controlar cómo debe representarse el contenido del libro electrónico en HTML/CSS durante la edición \\u2014 en vista flotante ( false ) o paginada ( true ).

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitada (
false
).

<br />

*** ** * ** ***

En esencia, la mayoría de los formatos de libros electrónicos son internamente un formato de flujo como Office Open XML, donde el contenido es sólido y se divide en capítulos pero no en páginas. Sin embargo, contiene información específica de página como números de página, notas al pie, encabezados/pies de página, etc. Algunos lectores de libros electrónicos dividen el contenido del libro en páginas, mientras que otros (especialmente móviles) \\u2014 no. Esta opción permite controlar cómo debe representarse el contenido del libro electrónico en HTML/CSS durante la edición \\u2014 en vista flotante ( false ) o paginada ( true ).

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Especifica si la información de idioma se exporta al marcado HTML en forma de atributos HTML 'lang'.
Esta opción puede ser útil para la conversión de ida y vuelta de documentos multilingües. Por defecto está deshabilitada (
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Especifica si la información de idioma se exporta al marcado HTML en forma de atributos HTML 'lang'.
Esta opción puede ser útil para la conversión de ida y vuelta de documentos multilingües. Por defecto está deshabilitada (
false
).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

