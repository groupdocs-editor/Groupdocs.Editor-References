---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para cargar documentos de texto plano TXT"
type: docs
weight: 39
url: /es/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para cargar documentos de texto plano (TXT)

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Codificación de caracteres del documento de texto, que se aplicará a su |
apertura
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codificación de caracteres del documento de texto, que se aplicará a su |
apertura
|
|  | [getRecognizeLists()](#getRecognizeLists--) | Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento está |
importado desde formato de texto plano.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento está |
importado desde formato de texto plano.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | Obtiene o establece la opción preferida para el manejo de espacios iniciales. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | Obtiene o establece la opción preferida para el manejo de espacios iniciales. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | Obtiene o establece la opción preferida para el manejo de espacios finales. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | Obtiene o establece la opción preferida para el manejo de espacios finales. |
|
|  | [getEnablePagination()](#getEnablePagination--) | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. |
|
|  | [getDirection()](#getDirection--) | Permite especificar la dirección del flujo de texto en el texto plano de entrada |
documento.
|
|  | [setDirection(int value)](#setDirection-int-) | Permite especificar la dirección del flujo de texto en el texto plano de entrada |
documento.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codificación de caracteres del documento de texto, que se aplicará a su
apertura


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Codificación de caracteres del documento de texto, que se aplicará a su
apertura


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento está
importado desde formato de texto plano. El valor predeterminado es true.


*** ** * ** ***

Si esta opción se establece en false, el algoritmo de reconocimiento de listas detecta párrafos de lista, cuando los números de lista terminan con un punto, corchete derecho o símbolos de viñeta (como "\\u2022", "\*", "-" o "o"). Si esta opción se establece en true, los espacios en blanco también se utilizan como delimitadores de números de lista: el algoritmo de reconocimiento de listas para numeración al estilo árabe (1., 1.1.2.) utiliza tanto espacios en blanco como el punto (".") como símbolos.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


Permite especificar cómo se reconocen los elementos de listas numeradas cuando el documento está
importado desde formato de texto plano. El valor predeterminado es true.


*** ** * ** ***

Si esta opción se establece en false, el algoritmo de reconocimiento de listas detecta párrafos de lista, cuando los números de lista terminan con un punto, corchete derecho o símbolos de viñeta (como "\\u2022", "\*", "-" o "o"). Si esta opción se establece en true, los espacios en blanco también se utilizan como delimitadores de números de lista: el algoritmo de reconocimiento de listas para numeración al estilo árabe (1., 1.1.2.) utiliza tanto espacios en blanco como el punto (".") como símbolos.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


Obtiene o establece la opción preferida para el manejo de espacios iniciales. Por defecto
convierte los espacios iniciales en sangría izquierda.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


Obtiene o establece la opción preferida para el manejo de espacios iniciales. Por defecto
convierte los espacios iniciales en sangría izquierda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


Obtiene o establece la opción preferida para el manejo de espacios finales. Por defecto
trunca todos los espacios finales.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


Obtiene o establece la opción preferida para el manejo de espacios finales. Por defecto
trunca todos los espacios finales.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por
el valor predeterminado está deshabilitado (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por
el valor predeterminado está deshabilitado (false).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


Permite especificar la dirección del flujo de texto en el texto plano de entrada
documento. Por defecto es de izquierda a derecha.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


Permite especificar la dirección del flujo de texto en el texto plano de entrada
documento. Por defecto es de izquierda a derecha.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

