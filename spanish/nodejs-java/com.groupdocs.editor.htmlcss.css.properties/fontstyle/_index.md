---
title: "FontStyle"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Define cómo debe estilizarse la fuente con una cara normal, cursiva o oblicua de su familia de fuentes."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Define cómo debe estilizarse la fuente: una variante normal, cursiva u oblicua de su font-family.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Normal](#Normal) | Selecciona una fuente que está clasificada como normal dentro de una familia de fuentes. |
|
|  | [Italic](#Italic) | Selecciona una fuente que está clasificada como cursiva. |
|
|  | [Oblique](#Oblique) | Selecciona una fuente que está clasificada como oblicua. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica si este estilo de fuente tiene un valor inicial (Normal) |
|
|  | [getValue()](#getValue--) | Devuelve un valor de este estilo de fuente como cadena |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Determina si esta instancia de estilo de fuente es igual a la especificada |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia de estilo de fuente es igual a la especificada sin convertir |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Comprueba si dos valores de "FontStyle" son iguales |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Comprueba si dos valores de "FontStyle" no son iguales |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Intenta reconocer una palabra clave especificada como un valor de palabra clave adecuado del 'font-style' y lo devuelve en caso de éxito o NULL en caso de falla. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Selecciona una fuente que está clasificada como normal dentro de una familia de fuentes. Valor inicial.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Selecciona una fuente que está clasificada como cursiva. Si no hay una versión cursiva de la cara disponible, se usa una clasificada como oblicua. Si ninguna está disponible, el estilo se simula artificialmente.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Selecciona una fuente que está clasificada como oblicua. Si no hay una versión oblicua de la cara disponible, se usa una clasificada como cursiva. Si ninguna está disponible, el estilo se simula artificialmente.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica si este estilo de fuente tiene un valor inicial (Normal)


**Returns:**
booleano
### getValue() {#getValue--}
```
public final String getValue()
```


Devuelve un valor de este estilo de fuente como cadena


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Determina si esta instancia de estilo de fuente es igual a la especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Otra instancia de font-style |
|

**Returns:**
booleano - true si son iguales, false de lo contrario

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia de estilo de fuente es igual a la especificada sin convertir


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia de font-style sin castear, puede ser null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Comprueba si dos valores de "FontStyle" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Primer valor a comprobar |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Segundo valor a comprobar |
|

**Returns:**
booleano - true si son iguales, false de lo contrario

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Comprueba si dos valores de "FontStyle" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Primer valor a comprobar |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Segundo valor a comprobar |
|

**Returns:**
booleano - false si son iguales, true de lo contrario

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Intenta reconocer una palabra clave especificada como un valor de palabra clave adecuado del 'font-style' y lo devuelve en caso de éxito o NULL en caso de falla.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | palabra clave | java.lang.String | Una palabra clave para analizar |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Resultado, si el análisis fue exitoso, o #Normal.Normal de lo contrario |
|

**Returns:**
booleano - true si el análisis fue exitoso, false de lo contrario

