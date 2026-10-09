---
title: "FixedLayoutEditOptionsBase"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Clase abstracta base para las opciones de todos los documentos de formatos de diseño fijo como PDF y XPS"
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

Clase abstracta base para las opciones de todos los documentos de formatos de diseño fijo como PDF y XPS

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | Obtiene o establece el indicador que indica si las imágenes deben omitirse al convertir el documento de diseño fijo de entrada al HTML resultante. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | Obtiene o establece el indicador que indica si las imágenes deben omitirse al convertir el documento de diseño fijo de entrada al HTML resultante. |
|
|  | [getPages()](#getPages--) | Permite establecer un rango de páginas a procesar. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | Permite establecer un rango de páginas a procesar. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Permite habilitar (true) o deshabilitar (false) la paginación en el documento HTML resultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permite habilitar (true) o deshabilitar (false) la paginación en el documento HTML resultante. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


Obtiene o establece el indicador que indica si las imágenes deben omitirse al convertir el documento de diseño fijo de entrada al HTML resultante. Por defecto es false - las imágenes se conservan.


**Returns:**
booleano
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


Obtiene o establece el indicador que indica si las imágenes deben omitirse al convertir el documento de diseño fijo de entrada al HTML resultante. Por defecto es false - las imágenes se conservan.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


Permite establecer un rango de páginas a procesar. Por defecto se procesan todas las páginas de un documento de diseño fijo.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


Permite establecer un rango de páginas a procesar. Por defecto se procesan todas las páginas de un documento de diseño fijo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permite habilitar (true) o deshabilitar (false) la paginación en el documento HTML resultante. Por defecto está deshabilitado (false).

<br />

*** ** * ** ***

Los documentos de formato de diseño fijo (PDF y XPS en particular) en su esencia están estrictamente paginados, su contenido tiene un diseño fijo y está dividido en páginas. Pero el HTML editable resultante puede representarse en una vista sin páginas o paginada.

<br />



**Returns:**
booleano
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permite habilitar (true) o deshabilitar (false) la paginación en el documento HTML resultante. Por defecto está deshabilitado (false).

<br />

*** ** * ** ***

Los documentos de formato de diseño fijo (PDF y XPS en particular) en su esencia están estrictamente paginados, su contenido tiene un diseño fijo y está dividido en páginas. Pero el HTML editable resultante puede representarse en una vista sin páginas o paginada.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

