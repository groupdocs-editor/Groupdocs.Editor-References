---
title: "FontSize"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa un tamaño de fuente como una unidad especial o un valor de longitud que especifica el tamaño de la fuente, históricamente la anchura de la M mayúscula."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Representa un tamaño de fuente como una unidad especial o un valor de longitud, que especifica el tamaño de la fuente (históricamente el ancho de la letra mayúscula "M").

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Medium](#Medium) | Tamaño medio. |
|
|  | [XxSmall](#XxSmall) | El tamaño absoluto muy pequeño |
|
|  | [XSmall](#XSmall) | El tamaño absoluto pequeño mediocre |
|
|  | [Small](#Small) | El tamaño absoluto normalmente pequeño |
|
|  | [Large](#Large) | El tamaño absoluto normalmente grande |
|
|  | [XLarge](#XLarge) | El tamaño absoluto grande mediocre |
|
|  | [XxLarge](#XxLarge) | El tamaño absoluto muy grande |
|
|  | [Larger](#Larger) | Tamaño relativo mayor - font será mayor relativo al font-size del elemento padre, aproximadamente por la razón usada para separar las palabras clave de tamaño absoluto anteriores. |
|
|  | [Smaller](#Smaller) | Tamaño relativo menor - font será menor relativo al font-size del elemento padre, aproximadamente por la razón usada para separar las palabras clave de tamaño absoluto anteriores. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica si este font-size tiene un valor inicial (Medium) |
|
|  | [getValue()](#getValue--) | Devuelve un valor de este font size como una cadena |
|
|  | [isLengthDefined()](#isLengthDefined--) | Indica si este font-size está definido con un valor [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | Un valor de longitud, si este font-size fue definido con él, o lanza una excepción de lo contrario |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Indica si este font-size está definido con un tamaño absoluto como palabra clave, basado en el tamaño de fuente predeterminado del usuario (que es medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Indica si este font-size está definido con un tamaño relativo como palabra clave. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Determina si esta instancia de font-size es igual a la especificada |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia de font-size es igual a la especificada sin convertir |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Comprueba si dos valores "FontSize" son iguales |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Comprueba si dos valores "FontSize" no son iguales |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Crea un font-size a partir de la longitud especificada |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Intenta reconocer una palabra clave especificada como un valor de palabra clave válido del 'font-size' y lo devuelve en caso de éxito o NULL en caso de falla. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Tamaño medium. Valor inicial.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


El tamaño absoluto muy pequeño


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


El tamaño absoluto pequeño mediocre


### Small {#Small}
```
public static final FontSize Small
```


El tamaño absoluto normalmente pequeño


### Large {#Large}
```
public static final FontSize Large
```


El tamaño absoluto normalmente grande


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


El tamaño absoluto grande mediocre


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


El tamaño absoluto muy grande


### Larger {#Larger}
```
public static final FontSize Larger
```


Tamaño relativo mayor - font será mayor relativo al font-size del elemento padre, aproximadamente por la razón usada para separar las palabras clave de tamaño absoluto anteriores.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Tamaño relativo menor - font será menor relativo al font-size del elemento padre, aproximadamente por la razón usada para separar las palabras clave de tamaño absoluto anteriores.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica si este font-size tiene un valor inicial (Medium)


**Returns:**
booleano
### getValue() {#getValue--}
```
public final String getValue()
```


Devuelve un valor de este font size como una cadena


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Indica si este font-size está definido con un valor [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
booleano
### getLength() {#getLength--}
```
public final Length getLength()
```


Un valor de longitud, si este font-size fue definido con él, o lanza una excepción de lo contrario


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Indica si este font-size está definido con un tamaño absoluto como palabra clave, basado en el tamaño de fuente predeterminado del usuario (que es medium)


**Returns:**
booleano
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Indica si este font-size está definido con un tamaño relativo como palabra clave. La fuente será mayor o menor en relación al tamaño de fuente del elemento padre, aproximadamente según la proporción utilizada para separar las palabras clave de tamaño absoluto.


**Returns:**
booleano
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Determina si esta instancia de font-size es igual a la especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Otra instancia de font-size |
|

**Returns:**
booleano - true si son iguales, false de lo contrario

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia de font-size es igual a la especificada sin convertir


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia de font-size sin convertir, puede ser nula |
|

**Returns:**
booleano - true si son iguales, false si no son iguales, null o de otro tipo

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia


**Returns:**
int - Código hash como un entero con signo

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Comprueba si dos valores "FontSize" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Primer valor a comprobar |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Segundo valor a comprobar |
|

**Returns:**
booleano - true si son iguales, false de lo contrario

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Comprueba si dos valores "FontSize" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Primer valor a comprobar |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Segundo valor a comprobar |
|

**Returns:**
booleano - false si son iguales, true de lo contrario

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Crea un font-size a partir de la longitud especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Un valor de longitud, no puede ser sin unidad o negativo |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Intenta reconocer una palabra clave especificada como un valor de palabra clave válido del 'font-size' y lo devuelve en caso de éxito o NULL en caso de falla.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | palabra clave | java.lang.String | Una palabra clave para analizar |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Resultado, si el análisis fue exitoso, o #Medium.Medium de lo contrario |
|

**Returns:**
booleano - true si el análisis fue exitoso, false de lo contrario

