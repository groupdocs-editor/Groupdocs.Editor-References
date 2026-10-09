---
title: "TextDecorationLineType"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa los tipos de línea de decoración de texto subrayado, guion bajo, sobrelínea y tachado"
type: docs
weight: 13
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Representa los tipos de línea de decoración de texto: subrayado (guion bajo), sobrelínea y tachado (line-through).

<br />

*** ** * ** ***

Estructura inmutable. Similar a https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [None](#None) | No produce decoración de texto. |
|
|  | [Underline](#Underline) | Cada línea de texto está subrayada. |
|
|  | [Overline](#Overline) | Cada línea de texto tiene una línea encima. |
|
|  | [LineThrough](#LineThrough) | Cada línea de texto tiene una línea en el medio. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica si esta instancia tiene un valor inicial \\u2014 None |
|
|  | [isUnderline()](#isUnderline--) | Indica si el subrayado (guion bajo) está habilitado |
|
|  | [isOverline()](#isOverline--) | Indica si la sobrelínea está habilitada |
|
|  | [isLineThrough()](#isLineThrough--) | Indica si la línea tachada (strikethrough) está habilitada |
|
|  | [getValue()](#getValue--) | Devuelve un valor de todas las banderas en esta instancia como texto |
|
|  | [toString()](#toString--) | Devuelve un valor de todas las banderas en esta instancia como texto |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Indica si esta instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) es igual a la especificada |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Indica si esta instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) es igual a la especificada sin convertir |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash de esta instancia |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Comprueba si dos valores "TextDecorationLineType" son iguales |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Comprueba si dos valores "TextDecorationLineType" no son iguales |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Crea y devuelve una instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) con banderas, definidas por los parámetros especificados |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Intenta analizar una cadena especificada y devolver una instancia válida de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Combina (fusiona) dos tipos de línea especificados y produce un nuevo tipo de línea resultante, donde las banderas se combinan (unión) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Resta el segundo tipo de línea especificado del primer tipo de línea especificado y produce un nuevo tipo de línea resultante, donde solo están presentes aquellas banderas del primer operando que no se encuentran en el segundo operando (diferencia) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Devuelve una intersección entre el primer y segundo tipo de línea, donde solo están habilitadas aquellas banderas que están habilitadas simultáneamente en ambos operandos. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Convierte un byte específico (octeto de 8 bits) al [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) correspondiente, lanza una excepción si la conversión es inválida |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


No produce decoración de texto. Valor inicial.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Cada línea de texto está subrayada.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Cada línea de texto tiene una línea encima.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Cada línea de texto tiene una línea en el medio.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica si esta instancia tiene un valor inicial \\u2014 None


**Returns:**
booleano
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Indica si el subrayado (guion bajo) está habilitado


**Returns:**
booleano
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Indica si la sobrelínea está habilitada


**Returns:**
booleano
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Indica si la línea tachada (strikethrough) está habilitada


**Returns:**
booleano
### getValue() {#getValue--}
```
public final String getValue()
```


Devuelve un valor de todas las banderas en esta instancia como texto


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Devuelve un valor de todas las banderas en esta instancia como texto


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Indica si esta instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) es igual a la especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Otra instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
boolean -  true  si son iguales,  false  de lo contrario

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Indica si esta instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) es igual a la especificada sin convertir


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | java.lang.Object | Otra instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), convertida a objeto |
|

**Returns:**
boolean -  true  si son iguales,  false  de lo contrario

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash de esta instancia


**Returns:**
int - Código hash de entero con signo

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Comprueba si dos valores "TextDecorationLineType" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primer operando a comprobar |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Segundo operando a comprobar |
|

**Returns:**
boolean -  true  si son iguales,  false  de lo contrario

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Comprueba si dos valores "TextDecorationLineType" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primer operando a comprobar |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Segundo operando a comprobar |
|

**Returns:**
boolean -  true  si son diferentes,  false  de lo contrario

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Crea y devuelve una instancia de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) con banderas, definidas por los parámetros especificados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | isUnderline | booleano | Determina si la bandera de subrayado está habilitada o no |
|
|  | isOverline | booleano | Determina si la bandera de sobrelínea está habilitada o no |
|
|  | isLineThrough | booleano | Determina si la bandera de tachado está habilitada o no |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Intenta analizar una cadena especificada y devolver una instancia válida de [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | entrada | java.lang.String | Cadena de entrada |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Resultado. Si el análisis es inválido, es un valor #None.None |
|

**Returns:**
boolean -  true  si el análisis fue exitoso,  false  en caso de fallo

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Combina (fusiona) dos tipos de línea especificados y produce un nuevo tipo de línea resultante, donde las banderas se combinan (unión)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primer operando de tipo de línea |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Segundo operando de tipo de línea |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Resta el segundo tipo de línea especificado del primer tipo de línea especificado y produce un nuevo tipo de línea resultante, donde solo están presentes aquellas banderas del primer operando que no se encuentran en el segundo operando (diferencia)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primer operando de tipo de línea |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Segundo operando de tipo de línea |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Devuelve una intersección entre los tipos de línea primero y segundo, donde solo están habilitadas aquellas banderas que están habilitadas simultáneamente en ambos operandos. Tiene la mayor prioridad entre todos los operadores (superior a la unión y la diferencia)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primer operando de tipo de línea |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Segundo operando de tipo de línea |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Convierte un byte específico (octeto de 8 bits) al [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) correspondiente, lanza una excepción si la conversión es inválida


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | octeto | byte | Un octeto de 8 bits (campo de bits), donde los 5 bits iniciales son ceros, mientras que los últimos 3 indican banderas |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
