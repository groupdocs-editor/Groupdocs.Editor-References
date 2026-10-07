---
title: "ArgbColor"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un valor de color en formato ARGB con convertidores y serializadores"
type: docs
weight: 10
url: /es/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

Representa un valor de color en formato ARGB con convertidores y serializadores

<br />

*** ** * ** ***

Este tipo está diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | Crea un valor [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a partir de los canales Rojo, Verde, Azul y Alfa especificados |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | Crea un valor [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a partir de los canales Rojo, Verde y Azul especificados, mientras que el canal Alfa es totalmente opaco |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | Crea un color totalmente opaco (A=255) a partir de un único valor, que se aplicará a todos los canales |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | Crea un valor [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a partir del [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) especificado |
|
|  | [getValue()](#getValue--) | Obtiene el valor Int32 del color. |
|
|  | [getA()](#getA--) | Obtiene la parte alfa del color. |
|
|  | [getAlpha()](#getAlpha--) | Obtiene la parte alfa del color en porcentaje (0..1). |
|
|  | [getR()](#getR--) | Obtiene la parte roja del color. |
|
|  | [getG()](#getG--) | Obtiene la parte verde del color. |
|
|  | [getB()](#getB--) | Obtiene la parte azul del color. |
|
|  | [isEmpty()](#isEmpty--) | Color no inicializado - los 4 canales están establecidos en 0. |
|
|  | [isDefault()](#isDefault--) | Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es la predeterminada (Transparente) - los 4 canales están establecidos en 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es totalmente transparente - su canal Alfa tiene el valor mínimo (0), por lo que los demás canales R, G y B no tienen efecto visible. |
|
|  | [isTranslucent()](#isTranslucent--) | Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es translúcida (no totalmente transparente, pero tampoco totalmente opaca) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es totalmente opaca, sin transparencia (su canal Alfa tiene el valor máximo) |
|
|  | [toSystemColor()](#toSystemColor--) | Convierte un valor de esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) al instancia [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) y lo devuelve |
|
|  | [toRGBA()](#toRGBA--) | Serializa esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a la notación de función CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | Serializa esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a la notación de función CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | Serializa esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a la notación de función CSS más apropiada según la translucidez |
|
|  | [toString()](#toString--) | Lo mismo que #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Compara dos colores y devuelve un booleano que indica si los dos coinciden. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Compara dos colores y devuelve un booleano que indica si los dos no coinciden. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | Verifica la igualdad de dos colores [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | Verifica la igualdad de dos colores [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Prueba si otro objeto es igual a esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor). |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash que define el color actual. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


Crea un valor [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a partir de los canales Rojo, Verde, Azul y Alfa especificados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | rojo | int | Valor del canal rojo |
|
|  | verde | int | Valor del canal verde |
|
|  | azul | int | Valor del canal azul |
|
|  | alfa | int | Valor del canal alfa |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


Crea un valor [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a partir de los canales Rojo, Verde y Azul especificados, mientras que el canal Alfa es totalmente opaco


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | rojo | int | Valor del canal rojo |
|
|  | verde | int | Valor del canal verde |
|
|  | azul | int | Valor del canal azul |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


Crea un color totalmente opaco (A=255) a partir de un único valor, que se aplicará a todos los canales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte | Un valor de byte, igual para los canales Rojo, Verde y Azul |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


Crea un valor [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a partir del [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


Obtiene el valor Int32 del color.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


Obtiene la parte alfa del color.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


Obtiene la parte alfa del color en porcentaje (0..1).


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


Obtiene la parte roja del color.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


Obtiene la parte verde del color.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


Obtiene la parte azul del color.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


Color no inicializado - los 4 canales se establecen en 0. Igual que Default y Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es la predeterminada (Transparente) - los 4 canales están establecidos en 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es totalmente transparente - su canal Alfa tiene el valor mínimo (0), por lo que los demás canales R, G y B no tienen efecto visible.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es translúcida (no totalmente transparente, pero tampoco totalmente opaca)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


Indica si esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) es totalmente opaca, sin transparencia (su canal Alfa tiene el valor máximo)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


Convierte un valor de esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) al instancia [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) y lo devuelve


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


Serializa esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a la notación de función CSS 'rgba'


**Returns:**
java.lang.String - Una cadena con formato 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


Serializa esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a la notación de función CSS 'rgb'


**Returns:**
java.lang.String - Una cadena con formato 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serializa esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) a la notación de función CSS más apropiada según la translucidez


**Returns:**
java.lang.String - Una cadena con formato 'rgba(r, g, b, a)' o 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


Lo mismo que #serializeDefault.serializeDefault


**Returns:**
java.lang.String - Mismo valor de retorno que en #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


Compara dos colores y devuelve un booleano que indica si los dos coinciden.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | El primer color a usar. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | El segundo color a usar. |
|

**Returns:**
boolean - Verdadero si ambos colores son iguales, de lo contrario falso.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


Compara dos colores y devuelve un booleano que indica si los dos no coinciden.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | El primer color a usar. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | El segundo color a usar. |
|

**Returns:**
boolean - Verdadero si ambos colores no son iguales, de lo contrario falso.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


Verifica la igualdad de dos colores [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | El otro [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) color |
|

**Returns:**
boolean - Verdadero si ambos colores son iguales, de lo contrario falso.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


Verifica la igualdad de dos colores [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | El otro [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) color, convertido al ICssDataType |
|

**Returns:**
boolean - Verdadero si ambos colores son iguales, de lo contrario falso.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Prueba si otro objeto es igual a esta instancia de [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | otro | java.lang.Object | El objeto con el que probar. |
|

**Returns:**
boolean - Verdadero si los dos objetos son iguales, de lo contrario falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash que define el color actual.


**Returns:**
int - El valor entero del código hash.

