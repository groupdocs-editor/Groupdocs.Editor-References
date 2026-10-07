---
title: "Ratio"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un tipo de datos CSS de razón que se utiliza para describir relaciones de aspecto en consultas de medios y para imágenes raster al indicar la proporción entre dos valores sin unidad llamados numerador y denominador."
type: docs
weight: 14
url: /es/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

Representa un tipo de datos CSS "ratio", que se utiliza para describir el aspecto
relaciones en consultas de medios y para imágenes raster al indicar la proporción
entre dos valores sin unidad llamados "numerador" y "denominador". Inmutable
estructura.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Single](#Single) | Relación predeterminada única 1/1 |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | Devuelve el numerador de esta relación |
|
|  | [getDenominator()](#getDenominator--) | Devuelve el denominador de esta relación |
|
|  | [calculate()](#calculate--) | Calcula y devuelve esta relación como un único número de punto flotante |
|
|  | [getInverseRatio()](#getInverseRatio--) | Genera y devuelve una relación inversa (recíproca) para esta relación |
|
|  | [serializeDefault()](#serializeDefault--) | Serializa esta relación a una cadena y la devuelve |
|
|  | [toString()](#toString--) | Devuelve una representación en cadena de esta relación; lo mismo que |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | Determina si esta relación tiene el valor predeterminado o es un "1/1" (único) |
|
|  | [deepClone()](#deepClone--) | Devuelve una copia completa de esta relación |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Determina si esta instancia es igual a la instancia "Ratio" especificada |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Determina si esta instancia es igual al objeto sin convertir especificado, |
que presumiblemente es otra instancia "Ratio"
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Compara dos proporciones y devuelve un booleano que indica si las dos coinciden. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | Compara dos proporciones y devuelve un booleano que indica si las dos no |
coinciden.
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia, que no puede ser modificado durante su |
vida útil
|
|  | [create(int numerator, int denominator)](#create-int-int-) | Crea y devuelve una instancia de Ratio a partir del numerador y el |
denominador
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


Relación predeterminada única 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


Devuelve el numerador de esta relación


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


Devuelve el denominador de esta relación


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


Calcula y devuelve esta relación como un único número de punto flotante


**Returns:**
double - Número de punto flotante de doble precisión

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


Genera y devuelve una relación inversa (recíproca) para esta relación


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Serializa esta relación a una cadena y la devuelve


**Returns:**
java.lang.String - String en formato "numerador/denominador"

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en cadena de esta relación; lo mismo que
"SerializeDefault()"


**Returns:**
java.lang.String - String en formato "numerador/denominador"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Determina si esta relación tiene el valor predeterminado o es un "1/1" (único)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


Devuelve una copia completa de esta relación


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


Determina si esta instancia es igual a la instancia "Ratio" especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | Otra instancia de Ratio para comprobar la igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determina si esta instancia es igual al objeto sin convertir especificado,
que presumiblemente es otra instancia "Ratio"


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | otro | java.lang.Object | Otra instancia de System.Object, que presumiblemente es del tipo Ratio, para comprobar la igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


Compara dos proporciones y devuelve un booleano que indica si las dos coinciden.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | La primera proporción a usar. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | La segunda proporción a usar. |
|

**Returns:**
boolean - Verdadero si ambas proporciones son iguales, de lo contrario falso.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


Compara dos proporciones y devuelve un booleano que indica si las dos no
coinciden.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | La primera proporción a usar. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | La segunda proporción a usar. |
|

**Returns:**
boolean - Verdadero si ambas proporciones no son iguales, de lo contrario falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia, que no puede ser modificado durante su
vida útil


**Returns:**
int - Entero con signo de 4 bytes, que es inmutable para esta instancia

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


Crea y devuelve una instancia de Ratio a partir del numerador y el
denominador


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | numerador | int | Numerador para la proporción. Debe ser un número entero estrictamente positivo. |
|
|  | denominador | int | Denominador para la proporción. Debe ser un número entero estrictamente positivo. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

