---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa la clase base para familias de formatos que proporciona funcionalidad común para las instancias de familias de formatos."
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Representa la clase base para familias de formatos, proporcionando funcionalidad común para instancias de familia de formato.

<br />

*** ** * ** ***

Esta clase es abstracta y debe ser heredada por una clase derivada que especifique los detalles reales de la familia de formatos.

<br />


## Métodos

| Método | Descripción |
| --- | --- |
|  | [getId()](#getId--) | Obtiene el identificador único de la familia de formatos. |
|
|  | [getName()](#getName--) | Obtiene el nombre de la familia de formatos. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determina si esta instancia es igual a la instancia especificada de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Recupera todas las instancias del tipo especificado |
T
que derivan de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia es igual a la instancia especificada de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [hashCode()](#hashCode--) | Devuelve un código hash para el objeto actual. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Recupera una instancia del tipo especificado |
T
que tiene el identificador especificado.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Recupera una instancia del tipo especificado |
T
que tiene el nombre especificado.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determina si dos instancias de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) son iguales. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determina si dos instancias de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) no son iguales. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Determina si una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) es igual a un nombre de cadena especificado. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Determina si una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) no es igual a un nombre de cadena especificado. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Convierte implícitamente una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) a un entero. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Convierte implícitamente una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) a una cadena. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Convierte una cadena que representa el nombre de una familia de formatos a un objeto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | Convierte un entero que representa el ID de una familia de formatos a un objeto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


Obtiene el identificador único de la familia de formatos.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de la familia de formatos.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Determina si esta instancia es igual a la instancia especificada de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar con la instancia actual. |
|

**Returns:**
boolean -  true  si la [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) especificada es igual a la instancia actual; de lo contrario,  false .

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.


**Returns:**
java.lang.String - Una cadena que representa el objeto actual, que es el valor de la propiedad  Name .

<br />

*** ** * ** ***

Este método sobrescribe  object.ToString  para devolver la propiedad  Name  del objeto.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Recupera todas las instancias del tipo especificado
T
que derivan de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Una colección enumerable de instancias del tipo especificado  T .


T
: El tipo de familia de formatos.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia es igual a la instancia especificada de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | La instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar con la instancia actual. |
|

**Returns:**
boolean -  true  si la [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) especificada es igual a la instancia actual; de lo contrario,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para el objeto actual.


**Returns:**
int - Un código hash para el objeto actual, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.

<br />

*** ** * ** ***

Este método sobrescribe  object.GetHashCode . El código hash se calcula usando las propiedades  Id  y  Name  del objeto. El contexto  unchecked  permite desbordamiento, lo cual es aceptable en un contexto de cálculo de código hash.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Recupera una instancia del tipo especificado
T
que tiene el identificador especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | valor | int | El identificador de la familia de formatos. |


T
: El tipo de familia de formatos.
|

**Returns:**
T - Una instancia del tipo especificado  T  con el identificador especificado.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Recupera una instancia del tipo especificado
T
que tiene el nombre especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | nombre | java.lang.String | El nombre de la familia de formatos. |


T
: El tipo de familia de formatos.
|

**Returns:**
T - Una instancia del tipo especificado  T  con el nombre especificado.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Determina si dos instancias de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) son iguales.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La primera instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La segunda instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar. |
|

**Returns:**
boolean - verdadero si las dos instancias de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) son iguales; de lo contrario, falso.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Determina si dos instancias de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) no son iguales.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La primera instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La segunda instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar. |
|

**Returns:**
boolean - verdadero si las dos instancias de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) no son iguales; de lo contrario, falso.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Determina si una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) es igual a un nombre de cadena especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar. |
|
|  | name | java.lang.String | El nombre de cadena para comparar con la instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - verdadero si el nombre de la instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) es igual al nombre de cadena especificado; de lo contrario, falso.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Determina si una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) no es igual a un nombre de cadena especificado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para comparar. |
|
|  | name | java.lang.String | El nombre de cadena para comparar con la instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - verdadero si el nombre de la instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) no es igual al nombre de cadena especificado; de lo contrario, falso.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Convierte implícitamente una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) a un entero.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para convertir. |
|

**Returns:**
int - El identificador único de la instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Convierte implícitamente una instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) a una cadena.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) para convertir. |
|

**Returns:**
java.lang.String - El nombre de la instancia de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Convierte una cadena que representa el nombre de una familia de formatos a un objeto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | familia | java.lang.String | El nombre de la familia de formatos para convertir. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Convierte un entero que representa el ID de una familia de formatos a un objeto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | id | int | El ID de la familia de formatos para convertir. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

