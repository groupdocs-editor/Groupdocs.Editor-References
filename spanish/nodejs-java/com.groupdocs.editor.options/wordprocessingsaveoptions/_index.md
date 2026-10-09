---
title: "WordProcessingSaveOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para generar y guardar documentos compatibles con WordProcessing después de haber sido editados"
type: docs
weight: 48
url: /es/nodejs-java/com.groupdocs.editor.options/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class WordProcessingSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar
Documentos compatibles con WordProcessing después de haber sido editados


*** ** * ** ***

WordProcessingSaveOptions se aplica en situaciones en las que hay una instancia de la clase EditableDocument, que contiene el contenido de un documento editado, y se requiere guardar este contenido en un nuevo documento con formato WordProcessing.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | Este constructor sin parámetros crea una nueva instancia de WordProcessingSaveOptions con formato de salida DOCX (puede modificarse luego a través de |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) propiedad)
|
|  | [WordProcessingSaveOptions(WordProcessingFormats outputFormat)](#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-) | Crea una nueva instancia de WordProcessingSaveOptions con el especificado |
formato de salida obligatorio de WordProcessing, mientras que todos los demás parámetros son
por defecto
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Permite habilitar o deshabilitar la paginación que se utilizará para guardar el |
documento.
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permite habilitar o deshabilitar la paginación que se utilizará para guardar el |
documento.
|
|  | [getPassword()](#getPassword--) | Permite especificar, modificar, obtener o eliminar una contraseña, que será |
utilizada para codificar el documento WordProcessing generado.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar, obtener o eliminar una contraseña, que será |
utilizada para codificar el documento WordProcessing generado.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permite especificar un formato WordProcessing, que se utilizará para guardar |
el documento
|
|  | [setOutputFormat(WordProcessingFormats value)](#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-) | Permite especificar un formato WordProcessing, que se utilizará para guardar |
el documento
|
|  | [getLocale()](#getLocale--) | Permite establecer anular la configuración regional predeterminada (idioma) para el WordProcessing |
documento, que se aplicará durante su creación.
|
|  | [setLocale(Locale value)](#setLocale-java.util.Locale-) | Permite establecer anular la configuración regional predeterminada (idioma) para el WordProcessing |
documento, que se aplicará durante su creación.
|
|  | [getLocaleBi()](#getLocaleBi--) | Permite establecer anular la configuración regional (idioma) para el documento WordProcessing |
para el texto RTL (de derecha a izquierda), que se aplicará durante su
creación.
|
|  | [setLocaleBi(Locale value)](#setLocaleBi-java.util.Locale-) | Permite establecer anular la configuración regional (idioma) para el documento WordProcessing |
para el texto RTL (de derecha a izquierda), que se aplicará durante su
creación.
|
|  | [getLocaleFarEast()](#getLocaleFarEast--) | Permite anular la configuración regional (idioma) para el documento WordProcessing |
para el texto de Asia Oriental, que se aplicará durante su creación.
|
|  | [setLocaleFarEast(Locale value)](#setLocaleFarEast-java.util.Locale-) | Permite anular la configuración regional (idioma) para el documento WordProcessing |
para el texto de Asia Oriental, que se aplicará durante su creación.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de |
HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de |
HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
|
|  | [getProtection()](#getProtection--) | Permite controlar y aplicar las opciones de protección del documento para el |
documento WordProcessing de cualquier formato, que soporta la protección del documento
protección.
|
|  | [setProtection(WordProcessingProtection value)](#setProtection-com.groupdocs.editor.options.WordProcessingProtection-) | Permite controlar y aplicar las opciones de protección del documento para el |
documento WordProcessing de cualquier formato, que soporta la protección del documento
protección.
|
|  | [getFontEmbedding()](#getFontEmbedding--) | Responsable de incrustar recursos de fuentes en el WordProcessing de salida |
documento.
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | Responsable de incrustar recursos de fuentes en el WordProcessing de salida |
documento.
|
|  | [deepClone()](#deepClone--) | Crea y devuelve una copia completa de esta instancia de |
Clase WordProcessingSaveOptions
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


Este constructor sin parámetros crea una nueva instancia de WordProcessingSaveOptions con formato de salida DOCX (puede modificarse luego a través de
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(WordProcessingFormats).setOutputFormat(WordProcessingFormats)) propiedad)


### WordProcessingSaveOptions(WordProcessingFormats outputFormat) {#WordProcessingSaveOptions-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public WordProcessingSaveOptions(WordProcessingFormats outputFormat)
```


Crea una nueva instancia de WordProcessingSaveOptions con el especificado
formato de salida obligatorio de WordProcessing, mientras que todos los demás parámetros son
por defecto


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFormat | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) | Formato de salida obligatorio, en el que el documento WordProcessing debe guardarse |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permite habilitar o deshabilitar la paginación que se utilizará para guardar el
documento. Si el documento original se abrió y editó en paginación
modo, esta opción también debe habilitarse. Por defecto está deshabilitada.


**Returns:**
boolean -
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permite habilitar o deshabilitar la paginación que se utilizará para guardar el
documento. Si el documento original se abrió y editó en paginación
modo, esta opción también debe habilitarse. Por defecto está deshabilitada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar, obtener o eliminar una contraseña, que será
se usa para codificar el documento WordProcessing generado. Especifique NULL o
cadena vacía para eliminar (limpiar) la contraseña.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar, obtener o eliminar una contraseña, que será
se usa para codificar el documento WordProcessing generado. Especifique NULL o
cadena vacía para eliminar (limpiar) la contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getOutputFormat() {#getOutputFormat--}
```
public final WordProcessingFormats getOutputFormat()
```


Permite especificar un formato WordProcessing, que se utilizará para guardar
el documento


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) - 
### setOutputFormat(WordProcessingFormats value) {#setOutputFormat-com.groupdocs.editor.formats.WordProcessingFormats-}
```
public final void setOutputFormat(WordProcessingFormats value)
```


Permite especificar un formato WordProcessing, que se utilizará para guardar
el documento


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats) |  |

### getLocale() {#getLocale--}
```
public final Locale getLocale()
```


Permite establecer anular la configuración regional predeterminada (idioma) para el WordProcessing
documento, que se aplicará durante su creación. Cuando no está
especificado (valor predeterminado), MS Word (u otro programa) detectará (o
elegirá) la configuración regional del documento según sus propias configuraciones u otros
factores.


*** ** * ** ***

Esta opción aplica forzadamente la configuración regional especificada a todo el texto del documento. No la use si el documento contiene diferentes partes de texto que están escritas en diferentes idiomas.

<br />



**Returns:**
java.util.Locale -
### setLocale(Locale value) {#setLocale-java.util.Locale-}
```
public final void setLocale(Locale value)
```


Permite establecer anular la configuración regional predeterminada (idioma) para el WordProcessing
documento, que se aplicará durante su creación. Cuando no está
especificado (valor predeterminado), MS Word (u otro programa) detectará (o
elegirá) la configuración regional del documento según sus propias configuraciones u otros
factores.

*** ** * ** ***


Esta opción aplica forzadamente la configuración regional especificada a todo el texto en
el documento. No la use si el documento contiene diferentes partes de
texto, que están escritas en diferentes idiomas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Locale |  |

### getLocaleBi() {#getLocaleBi--}
```
public final Locale getLocaleBi()
```


Permite establecer anular la configuración regional (idioma) para el documento WordProcessing
para el texto RTL (de derecha a izquierda), que se aplicará durante su
creación. Cuando no está especificado (valor predeterminado), MS Word (u otro
programa) detectará (o elegirá) la configuración regional RTL del documento según su
propias configuraciones u otros factores.

*** ** * ** ***


Esta opción aplica forzadamente la configuración regional especificada a todo el texto RTL
en el documento. No la use si el documento contiene diferentes partes de
texto, que están escritas en diferentes idiomas.


**Returns:**
java.util.Locale -
### setLocaleBi(Locale value) {#setLocaleBi-java.util.Locale-}
```
public final void setLocaleBi(Locale value)
```


Permite establecer anular la configuración regional (idioma) para el documento WordProcessing
para el texto RTL (de derecha a izquierda), que se aplicará durante su
creación. Cuando no está especificado (valor predeterminado), MS Word (u otro
programa) detectará (o elegirá) la configuración regional RTL del documento según su
propias configuraciones u otros factores.

*** ** * ** ***


Esta opción aplica forzadamente la configuración regional especificada a todo el texto RTL
en el documento. No la use si el documento contiene diferentes partes de
texto, que están escritas en diferentes idiomas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Locale |  |

### getLocaleFarEast() {#getLocaleFarEast--}
```
public final Locale getLocaleFarEast()
```


Permite anular la configuración regional (idioma) para el documento WordProcessing
para el texto de Asia Oriental, que se aplicará durante su creación. Cuando
no está especificado (valor predeterminado), MS Word (u otro programa) detectará
(o elegirá) la configuración regional de Asia Oriental del documento según sus propias configuraciones
u otros factores.

*** ** * ** ***


Esta opción aplica forzadamente la configuración regional especificada al conjunto
Texto este-asiático en el documento. No lo use si el documento contiene
diferentes partes del texto, que están escritas en diferentes
idiomas.


**Returns:**
java.util.Locale -
### setLocaleFarEast(Locale value) {#setLocaleFarEast-java.util.Locale-}
```
public final void setLocaleFarEast(Locale value)
```


Permite anular la configuración regional (idioma) para el documento WordProcessing
para el texto de Asia Oriental, que se aplicará durante su creación. Cuando
no está especificado (valor predeterminado), MS Word (u otro programa) detectará
(o elegirá) la configuración regional de Asia Oriental del documento según sus propias configuraciones
u otros factores.

*** ** * ** ***


Esta opción aplica forzadamente la configuración regional especificada al conjunto
Texto este-asiático en el documento. No lo use si el documento contiene
diferentes partes del texto, que están escritas en diferentes
idiomas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Locale |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de
HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción en true puede reducir significativamente el consumo de memoria
mientras se generan documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es false (la optimización de memoria está deshabilitada por el bien de un mejor
rendimiento).


**Returns:**
boolean -
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Habilita mecanismos de optimización de memoria durante la generación de documentos a partir de
HTML, lo que degrada el rendimiento como costo de reducir el uso de memoria.
Establecer esta opción en true puede reducir significativamente el consumo de memoria
mientras se generan documentos grandes a costa de un tiempo de guardado más lento.
El valor predeterminado es false (la optimización de memoria está deshabilitada por el bien de un mejor
rendimiento).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getProtection() {#getProtection--}
```
public final WordProcessingProtection getProtection()
```


Permite controlar y aplicar las opciones de protección del documento para el
documento WordProcessing de cualquier formato, que soporta la protección del documento
protección. Por defecto es NULL - la protección del documento no se utilizará.


**Returns:**
[WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) - 
### setProtection(WordProcessingProtection value) {#setProtection-com.groupdocs.editor.options.WordProcessingProtection-}
```
public final void setProtection(WordProcessingProtection value)
```


Permite controlar y aplicar las opciones de protección del documento para el
documento WordProcessing de cualquier formato, que soporta la protección del documento
protección. Por defecto es NULL - la protección del documento no se utilizará.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WordProcessingProtection](../../com.groupdocs.editor.options/wordprocessingprotection) |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


Responsable de incrustar recursos de fuentes en el WordProcessing de salida
documento. Por defecto no incrusta ninguna fuente (NotEmbed).


**Returns:**
int -
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


Responsable de incrustar recursos de fuentes en el WordProcessing de salida
documento. Por defecto no incrusta ninguna fuente (NotEmbed).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### deepClone() {#deepClone--}
```
public final WordProcessingSaveOptions deepClone()
```


Crea y devuelve una copia completa de esta instancia de
Clase WordProcessingSaveOptions


**Returns:**
[WordProcessingSaveOptions](../../com.groupdocs.editor.options/wordprocessingsaveoptions) - New WordProcessingSaveOptions instance

