---
title: "WordProcessingEditOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para editar documentos de todos los formatos compatibles con WordProcessing y compatibles con Words, como DOCX, RTF, ODT, etc."
type: docs
weight: 44
url: /es/nodejs-java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para editar documentos de todos los compatibles
Formatos WordProcessing (compatibles con Words) como DOC(X), RTF, ODT, etc.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | Crea y devuelve una nueva instancia de WordProcessingEditOptions |
clase, donde todas las opciones se establecen a sus valores predeterminados
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | Crea y devuelve una nueva instancia de WordProcessingEditOptions |
clase con paginación especificada y el resto de opciones predeterminadas
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | Especifica si la información de idioma se exporta al marcado HTML en |
una forma de atributos HTML 'lang'.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | Especifica si la información de idioma se exporta al marcado HTML en |
una forma de atributos HTML 'lang'.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | Obtiene o establece un valor que indica si extraer solo los recursos de fuente que |
se utilizan en el contenido textual del documento.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | Obtiene o establece un valor que indica si extraer solo los recursos de fuente que |
se utilizan en el contenido textual del documento.
|
|  | [getFontExtraction()](#getFontExtraction--) | Responsable de extraer los recursos de fuente, que se utilizan en la entrada |
Documento WordProcessing.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | Responsable de extraer los recursos de fuente, que se utilizan en la entrada |
Documento WordProcessing.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | Permite especificar un nombre de clase, que se colocará en el atributo 'class' |
atributos en cada elemento HTML, que representan algún campo en la entrada
Documento WordProcessing.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | Permite especificar un nombre de clase, que se colocará en el atributo 'class' |
atributos en cada elemento HTML, que representan algún campo en la entrada
Documento WordProcessing.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | Controla dónde almacenar los datos de estilo y formato del documento WordProcessing de entrada: en una hoja de estilos externa ( |
false
) o como estilos en línea en el marcado HTML (
true
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | Controla dónde almacenar los datos de estilo y formato del documento WordProcessing de entrada: en una hoja de estilos externa ( |
false
) o como estilos en línea en el marcado HTML (
true
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


Crea y devuelve una nueva instancia de WordProcessingEditOptions
clase, donde todas las opciones se establecen a sus valores predeterminados


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


Crea y devuelve una nueva instancia de WordProcessingEditOptions
clase con paginación especificada y el resto de opciones predeterminadas


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | enablePagination | booleano | Bandera de paginación, que habilita la salida HTML, ajustada para modo paginado |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por
el valor predeterminado está deshabilitado (false).


**Returns:**
booleano
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por
el valor predeterminado está deshabilitado (false).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


Especifica si la información de idioma se exporta al marcado HTML en
una forma de los atributos HTML 'lang'. Esta opción puede ser útil para la ida y vuelta
de la conversión de documentos multilingües. Por defecto está deshabilitada
(false).


**Returns:**
booleano
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


Especifica si la información de idioma se exporta al marcado HTML en
una forma de los atributos HTML 'lang'. Esta opción puede ser útil para la ida y vuelta
de la conversión de documentos multilingües. Por defecto está deshabilitada
(false).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


Obtiene o establece un valor que indica si extraer solo los recursos de fuente que
se utilizan en el contenido textual del documento.
Valor:  true  si se requiere extraer solo los recursos de fuentes que se utilizan en el contenido de texto del documento; de lo contrario,  false . El valor predeterminado es  false .


*** ** * ** ***

No todas las fuentes utilizadas en el documento WordProcessing se usan al 100% directamente (aplicadas a algún texto). Puede haber una situación en la que una fuente esté referenciada en el documento e incluso pueda estar incrustada, pero no se aplique a ningún fragmento de texto. Por ejemplo, una fuente puede estar asociada a algún estilo, pero ese estilo no se aplique a ninguna parte del texto. Esta opción controla cómo procesar dichos casos.

<br />



**Returns:**
booleano
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


Obtiene o establece un valor que indica si extraer solo los recursos de fuente que
se utilizan en el contenido textual del documento.
Valor:  true  si se requiere extraer solo los recursos de fuentes que se utilizan en el contenido de texto del documento; de lo contrario,  false . El valor predeterminado es  false .


*** ** * ** ***

No todas las fuentes utilizadas en el documento WordProcessing se usan al 100% directamente (aplicadas a algún texto). Puede haber una situación en la que una fuente esté referenciada en el documento e incluso pueda estar incrustada, pero no se aplique a ningún fragmento de texto. Por ejemplo, una fuente puede estar asociada a algún estilo, pero ese estilo no se aplique a ninguna parte del texto. Esta opción controla cómo procesar dichos casos.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


Responsable de extraer los recursos de fuente, que se utilizan en la entrada
Documento WordProcessing. Por defecto no extrae ninguna fuente
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


Responsable de extraer los recursos de fuente, que se utilizan en la entrada
Documento WordProcessing. Por defecto no extrae ninguna fuente
(NotExtract).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


Permite especificar un nombre de clase, que se colocará en el atributo 'class'
atributos en cada elemento HTML, que representan algún campo en la entrada
Documento WordProcessing. Por defecto es NULL - los atributos 'class' no son
aplicados.


*** ** * ** ***

Casi todos los formatos de la familia de formatos WordProcessing contienen campos \u2014 entidades específicas del documento, que permiten obtener datos de entrada de los usuarios. Existe una gran variedad de campos: cuadros de texto, casillas de verificación, listas desplegables, botones, selectores de fecha/hora, etc. Todos ellos se traducen a las estructuras y elementos HTML más apropiados, preservando los datos introducidos por el usuario, si están presentes en el documento de entrada. En casos de uso específicos solo se requiere recopilar los datos introducidos del lado del cliente en lugar de editar todo el contenido del documento. Para tal caso es necesario identificar los controles de entrada de alguna manera para obtenerlos con sus datos del lado del cliente. Esta propiedad permite especificar un nombre de clase, que se aplicará a cada control de entrada en el marcado HTML, de modo que el código cliente pueda recorrer la estructura del documento HTML y recopilar los datos.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


Permite especificar un nombre de clase, que se colocará en el atributo 'class'
atributos en cada elemento HTML, que representan algún campo en la entrada
Documento WordProcessing. Por defecto es NULL - los atributos 'class' no son
aplicados.


*** ** * ** ***

Casi todos los formatos de la familia de formatos WordProcessing contienen campos \u2014 entidades específicas del documento, que permiten obtener datos de entrada de los usuarios. Existe una gran variedad de campos: cuadros de texto, casillas de verificación, listas desplegables, botones, selectores de fecha/hora, etc. Todos ellos se traducen a las estructuras y elementos HTML más apropiados, preservando los datos introducidos por el usuario, si están presentes en el documento de entrada. En casos de uso específicos solo se requiere recopilar los datos introducidos del lado del cliente en lugar de editar todo el contenido del documento. Para tal caso es necesario identificar los controles de entrada de alguna manera para obtenerlos con sus datos del lado del cliente. Esta propiedad permite especificar un nombre de clase, que se aplicará a cada control de entrada en el marcado HTML, de modo que el código cliente pueda recorrer la estructura del documento HTML y recopilar los datos.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


Controla dónde almacenar los datos de estilo y formato del documento WordProcessing de entrada: en una hoja de estilos externa (
false
) o como estilos en línea en el marcado HTML (
true
). Por defecto se usan estilos externos (
false
).


**Returns:**
booleano
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


Controla dónde almacenar los datos de estilo y formato del documento WordProcessing de entrada: en una hoja de estilos externa (
false
) o como estilos en línea en el marcado HTML (
true
). Por defecto se usan estilos externos (
false
).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

