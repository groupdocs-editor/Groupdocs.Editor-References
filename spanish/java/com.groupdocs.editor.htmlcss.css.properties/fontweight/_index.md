---
title: "FontWeight"
second_title: "GroupDocs.Editor for Java API Reference"
description: "La propiedad font-weight establece el peso o la negritud de la fuente."
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

La propiedad font-weight establece el peso (o la negritud) de la fuente. Los pesos disponibles dependen de la familia de fuentes que está configurada actualmente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Lighter](#Lighter) | Un peso de fuente relativo más ligero que el elemento padre |
|
|  | [Bolder](#Bolder) | Un peso de fuente relativo más pesado que el elemento padre |
|
|  | [Normal](#Normal) | Peso de fuente normal. |
|
|  | [Bold](#Bold) | Peso de fuente negrita. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica si este font-size tiene un valor inicial (Medium) |
|
|  | [getNumber()](#getNumber--) | Devuelve un número - valor entero entre 1 y 1000, inclusive, que describe la negritud de la fuente, o lanza una excepción si la negritud actual no es absoluta, sino relativa. |
|
|  | [isAbsolute()](#isAbsolute--) | Indica si esta instancia de font-weight almacena un valor absoluto del peso (negritud) de la fuente, como un número entero. |
|
|  | [isRelative()](#isRelative--) | Indica si esta instancia de font-weight almacena un valor relativo del peso (grosor) de la fuente, comparado con el grosor del elemento padre |
|
|  | [getValue()](#getValue--) | Devuelve un valor de este font-weight como una cadena |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Determina si las instancias especificadas de FontWeight son iguales |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia de FontWeight es igual a la especificada sin convertir |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Comprueba si dos valores \"FontWeight\" son iguales |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Comprueba si dos valores \"FontWeight\" no son iguales |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Crea un font-weight a partir del número especificado |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Intenta analizar una cadena especificada y devuelve una instancia válida de FontWeight en caso de éxito |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Un peso de fuente relativo más ligero que el elemento padre


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Un peso de fuente relativo más pesado que el elemento padre


### Normal {#Normal}
```
public static final FontWeight Normal
```


Peso de fuente normal. Igual a 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Peso de fuente en negrita. Igual a 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica si este font-size tiene un valor inicial (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Devuelve un número - valor entero entre 1 y 1000, inclusive, que describe la negritud de la fuente, o lanza una excepción si la negritud actual no es absoluta, sino relativa.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Indica si esta instancia de font-weight almacena un valor absoluto del peso (negritud) de la fuente, como un número entero.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Indica si esta instancia de font-weight almacena un valor relativo del peso (grosor) de la fuente, comparado con el grosor del elemento padre


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Devuelve un valor de este font-weight como una cadena


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Determina si las instancias especificadas de FontWeight son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Otra instancia de FontWeight para comprobar la igualdad |
|

**Returns:**
boolean - verdadero si son iguales, falso si son diferentes

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia de FontWeight es igual a la especificada sin convertir


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia de FontWeight sin convertir, puede ser nula |
|

**Returns:**
boolean - false si son iguales, true de lo contrario

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia


**Returns:**
int - Hash-code como un entero con signo

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Comprueba si dos valores \"FontWeight\" son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Primer valor a comprobar |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Segundo valor a comprobar |
|

**Returns:**
boolean - true si son iguales, false de lo contrario

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Comprueba si dos valores \"FontWeight\" no son iguales


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Primer valor a comprobar |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Segundo valor a comprobar |
|

**Returns:**
boolean - false si son iguales, true de lo contrario

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Crea un font-weight a partir del número especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | number | int | Entero sin signo, debe estar dentro del rango [1..1000] |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Intenta analizar una cadena especificada y devuelve una instancia válida de FontWeight en caso de éxito


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | input | java.lang.String | Cadena de entrada para analizar |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Valor válido de FontWeight en caso de éxito o #Normal.Normal en caso de falla |
|

**Returns:**
boolean - Éxito (true) o falla (false) del análisis

