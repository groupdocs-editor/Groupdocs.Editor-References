---
title: "Longitud"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa un valor de longitud CSS en cualquier unidad compatible, incluyendo porcentaje y tipo sin unidad."
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Representa un valor de longitud CSS en cualquier unidad compatible, incluyendo porcentaje
y tipo sin unidad. Los valores pueden ser enteros o flotantes, negativos, cero y
positivos. Estructura inmutable.

*** ** * ** ***


Este tipo cubre los siguientes tipos de datos CSS:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [Length()](#Length--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Cero entero sin unidad - valor predeterminado, el mismo que el predeterminado sin parámetros |
constructor
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Crea y devuelve una instancia del tipo Length a partir del número float especificado |
y unidad
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Crea y devuelve una instancia del tipo Length a partir del número double especificado |
y unidad
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Crea y devuelve una instancia del tipo Length a partir del entero especificado |
número y unidad
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Determina si esta instancia es un cero sin unidad o no. |
|
|  | [isDefault()](#isDefault--) | Indica si esta instancia de Length tiene un valor predeterminado \\u2014 sin unidad |
cero.
|
|  | [getUnitType()](#getUnitType--) | Devuelve un tipo de unidad de esta instancia de Length. |
|
|  | [isInteger()](#isInteger--) | Indica si el valor numérico de esta instancia de Length fue |
originalmente especificado y almacenado como un número entero (INT32)
|
|  | [isFloat()](#isFloat--) | Indica si el valor numérico de esta instancia de Length fue |
originalmente especificado y almacenado como un número float (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | Devuelve un valor numérico float de la instancia de Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Devuelve un valor numérico entero de esta instancia de Length, si es |
almacenado internamente como entero, o lanza una excepción, si fue
originalmente almacenado como número float.
|
|  | [isAbsolute()](#isAbsolute--) | Obtiene si la longitud se da en unidades absolutas. |
|
|  | [isRelative()](#isRelative--) | Obtiene si la longitud se da en unidades relativas. |
|
|  | [isZero()](#isZero--) | Determina si el valor numérico de esta longitud es un número cero |
|
|  | [isNegative()](#isNegative--) | Determina si el valor numérico de esta longitud es un número negativo |
|
|  | [isPositive()](#isPositive--) | Determina si el valor numérico de esta longitud es un número positivo |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | El valor tiene tipo sin unidades, pero no es cero - positivo o negativo |
number
|
|  | [toPixel()](#toPixel--) | Convierte la longitud a un número de píxeles, si es posible. |
|
|  | [to(int unit)](#to-int-) | Convierte la longitud a la unidad dada, si es posible. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Devuelve una representación en cadena de esta longitud en el tipo de unidad especificado. |
|
|  | [serializeDefault()](#serializeDefault--) | Devuelve una representación en cadena de esta longitud en su nativa original |
forma (tal como se almacena), sin convertir el valor de la longitud a otra
tipo de unidad
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Define si este valor es igual a la otra longitud especificada |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta longitud es igual al objeto especificado |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Multiplica la Longitud dada por el factor dado |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Comprueba la igualdad de las dos longitudes dadas. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Comprueba la desigualdad de las dos longitudes dadas. |
|
|  | [hashCode()](#hashCode--) | Calcula y devuelve un código hash de esta instancia de Length combinando |
códigos hash del valor y del tipo de unidad
|
|  | [deepClone()](#deepClone--) | Devuelve una copia completa de esta instancia de Length |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Intenta analizar el nombre de unidad especificado y devolver el valor correspondiente de un |
enumerado Unit.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Intenta analizar una cadena especificada como un valor de Length, incluyendo su |
valor numérico y nombre de unidad
|
|  | [parse(String input)](#parse-java.lang.String-) | Analiza y devuelve la cadena especificada como un valor de Length, incluyendo su |
valor numérico y nombre de unidad, o lanza una excepción en caso de error
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Cero entero sin unidad - valor predeterminado, el mismo que el predeterminado sin parámetros
constructor


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Crea y devuelve una instancia del tipo Length a partir del número float especificado
y unidad


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | float | \>Cualquier número flotante (FP32) |
|
|  | unidad | int | Cualquier tipo de unidad válido |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Crea y devuelve una instancia del tipo Length a partir del número double especificado
y unidad


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | Cualquier número double (FP64), que será convertido a float (FP32) |
|
|  | unidad | int | Cualquier tipo de unidad válido |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Crea y devuelve una instancia del tipo Length a partir del entero especificado
número y unidad


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | Cualquier número entero |
|
|  | unidad | int | Cualquier tipo de unidad válido |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Determina si esta instancia es un cero sin unidad o no. Cero sin unidad
es el valor predeterminado de este tipo. Igual que la propiedad IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica si esta instancia de Length tiene un valor predeterminado \\u2014 sin unidad
cero. Igual que la propiedad IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Devuelve un tipo de unidad de esta instancia de Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Indica si el valor numérico de esta instancia de Length fue
originalmente especificado y almacenado como un número entero (INT32)


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Indica si el valor numérico de esta instancia de Length fue
originalmente especificado y almacenado como un número float (FP32)


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Devuelve un valor numérico float de la instancia Length. Nunca lanza un
excepción - convierte el valor Integer a Float si es necesario.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Devuelve un valor numérico entero de esta instancia de Length, si es
almacenado internamente como entero, o lanza una excepción, si fue
originalmente almacenado como número float.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Obtiene si la longitud se da en unidades absolutas. Tal longitud puede ser
convertida a píxeles.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Obtiene si la longitud se da en unidades relativas. Tal longitud no puede ser
convertida a píxeles.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Determina si el valor numérico de esta longitud es un número cero


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Determina si el valor numérico de esta longitud es un número negativo


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Determina si el valor numérico de esta longitud es un número positivo


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


El valor tiene tipo sin unidades, pero no es cero - positivo o negativo
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Convierte la longitud a un número de píxeles, si es posible. Si la
unidad es relativa, se lanzará una excepción.


**Returns:**
float - El número de píxeles representado por la longitud actual.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Convierte la longitud a la unidad dada, si es posible. Si la actual o
unidad dada es relativa, se lanzará una excepción.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | unidad | int | La unidad a la que convertir. |
|

**Returns:**
float - El valor en la unidad dada de la longitud actual.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Devuelve una representación en cadena de esta longitud en el tipo de unidad especificado.
El valor numérico será convertido de acuerdo al cambio de tipo de unidad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | unidad | int | Unidad especificada, a la que esta instancia debe convertirse antes de serializar a la cadena. Debe ser válida. No puede ser sin unidad. |
|

**Returns:**
java.lang.String - Representación de cadena

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Devuelve una representación en cadena de esta longitud en su nativa original
forma (tal como se almacena), sin convertir el valor de la longitud a otra
tipo de unidad


**Returns:**
java.lang.String - Instancia de cadena

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Define si este valor es igual a la otra longitud especificada


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Otra instancia del tipo Length |
|

**Returns:**
boolean - Verdadero si es igual, de lo contrario falso

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta longitud es igual al objeto especificado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Otra instancia del tipo Length, que está encapsulada en System.Object o cualquier otro tipo abstracto o interfaz |
|

**Returns:**
boolean - Verdadero si es igual, de lo contrario falso

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Multiplica la Longitud dada por el factor dado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - multiplicando |
|
|  | factor | int | Entero arbitrario - factor |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Comprueba la igualdad de las dos longitudes dadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | El operando de longitud izquierdo. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | El operando de longitud derecho. |
|

**Returns:**
boolean - Verdadero si ambas longitudes son iguales, de lo contrario falso.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Comprueba la desigualdad de las dos longitudes dadas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | El operando de longitud izquierdo. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | El operando de longitud derecho. |
|

**Returns:**
boolean - Verdadero si ambas longitudes no son iguales, de lo contrario falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcula y devuelve un código hash de esta instancia de Length combinando
códigos hash del valor y del tipo de unidad


**Returns:**
int - Número entero

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Devuelve una copia completa de esta instancia de Length


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Intenta analizar el nombre de unidad especificado y devolver el valor correspondiente de un
Enum Unit. Devuelve LengthUnit.Unitless si no se puede encontrar un LengthUnit apropiado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | unitName | java.lang.String | String, que representa un nombre de unidad |
|

**Returns:**
int - Valor del enum Unit en cualquier caso, LengthUnit.Unitless cuando no se puede encontrar una unidad apropiada

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Intenta analizar una cadena especificada como un valor de Length, incluyendo su
valor numérico y nombre de unidad


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | input | java.lang.String | Cadena de entrada, que debe analizarse |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Parámetro de salida, que contiene un resultado del análisis. Si el análisis no tiene éxito, contiene un valor predeterminado de Length \\u2014 un cero sin unidad. |
|

**Returns:**
boolean - Verdadero si el análisis tiene éxito, falso si no tiene éxito

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Analiza y devuelve la cadena especificada como un valor de Length, incluyendo su
valor numérico y nombre de unidad, o lanza una excepción en caso de error


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | input | java.lang.String | Cadena de entrada, que debe analizarse |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

