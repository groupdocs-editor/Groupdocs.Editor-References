---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt die Basisklasse für Formatfamilien dar, die gemeinsame Funktionalität für Instanzen von Formatfamilien bereitstellt."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Stellt die Basisklasse für Formatfamilien dar und bietet gemeinsame Funktionalität für Instanzen von Formatfamilien.

<br />

*** ** * ** ***

Diese Klasse ist abstrakt und muss von einer abgeleiteten Klasse geerbt werden, die die tatsächlichen Details der Formatfamilie spezifiziert.

<br />


## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getId()](#getId--) | Liefert die eindeutige Kennung für die Formatfamilie. |
|
|  | [getName()](#getName--) | Liefert den Namen der Formatfamilie. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bestimmt, ob diese Instanz gleich der angegebenen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz ist. |
|
|  | [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Ruft alle Instanzen des angegebenen Typs ab |
T
die von [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) abgeleitet sind.
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob diese Instanz gleich der angegebenen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz ist. |
|
|  | [hashCode()](#hashCode--) | Gibt einen Hashcode für das aktuelle Objekt zurück. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Ruft eine Instanz des angegebenen Typs ab. |
T
die die angegebene Kennung hat.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Ruft eine Instanz des angegebenen Typs ab. |
T
die den angegebenen Namen hat.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bestimmt, ob zwei [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanzen gleich sind. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bestimmt, ob zwei [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanzen nicht gleich sind. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bestimmt, ob eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz gleich einem angegebenen Zeichenkettennamen ist. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bestimmt, ob eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz nicht gleich einem angegebenen Zeichenkettennamen ist. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Konvertiert implizit eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz in einen Integer. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Konvertiert implizit eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz in eine Zeichenkette. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Konvertiert eine Zeichenkette, die einen Formatfamiliennamen darstellt, in ein [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Objekt. |
|
|  | [fromId(int id)](#fromId-int-) | Konvertiert einen Integer, der eine Formatfamilien-ID darstellt, in ein [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Objekt. |
|
### getId() {#getId--}
```
public final int getId()
```


Liefert die eindeutige Kennung für die Formatfamilie.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Liefert den Namen der Formatfamilie.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Bestimmt, ob diese Instanz gleich der angegebenen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz, die mit der aktuellen Instanz verglichen wird. |
|

**Returns:**
boolean -  true  wenn die angegebene [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) gleich der aktuellen Instanz ist; andernfalls,  false .

### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.


**Returns:**
java.lang.String - Eine Zeichenkette, die das aktuelle Objekt darstellt, wobei es sich um den Wert der  Name  Eigenschaft handelt.

<br />

*** ** * ** ***

Diese Methode überschreibt  object.ToString  und gibt die  Name  Eigenschaft des Objekts zurück.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Ruft alle Instanzen des angegebenen Typs ab
T
die von [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) abgeleitet sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Eine aufzählbare Sammlung von Instanzen des angegebenen Typs  T .


T
: Der Typ der Formatfamilie.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob diese Instanz gleich der angegebenen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | Die [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz, die mit der aktuellen Instanz verglichen wird. |
|

**Returns:**
boolean -  true  wenn die angegebene [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) gleich der aktuellen Instanz ist; andernfalls,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für das aktuelle Objekt zurück.


**Returns:**
int - Ein Hashcode für das aktuelle Objekt, geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle.

<br />

*** ** * ** ***

Diese Methode überschreibt  object.GetHashCode . Der Hashcode wird unter Verwendung der  Id  und  Name  Eigenschaften des Objekts berechnet. Der  unchecked  Kontext erlaubt Überlauf, was im Kontext einer Hashcode‑Berechnung akzeptabel ist.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Ruft eine Instanz des angegebenen Typs ab.
T
die die angegebene Kennung hat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | Wert | int | Der Bezeichner der Formatfamilie. |


T
: Der Typ der Formatfamilie.
|

**Returns:**
T - Eine Instanz des angegebenen Typs  T  mit dem angegebenen Bezeichner.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Ruft eine Instanz des angegebenen Typs ab.
T
die den angegebenen Namen hat.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | Name | java.lang.String | Der Name der Formatfamilie. |


T
: Der Typ der Formatfamilie.
|

**Returns:**
T - Eine Instanz des angegebenen Typs  T  mit dem angegebenen Namen.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Bestimmt, ob zwei [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die erste [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Vergleichen. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die zweite [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Vergleichen. |
|

**Returns:**
boolean - true, wenn die beiden [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanzen gleich sind; andernfalls false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Bestimmt, ob zwei [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanzen nicht gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die erste [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Vergleichen. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die zweite [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Vergleichen. |
|

**Returns:**
boolean - true, wenn die beiden [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanzen nicht gleich sind; andernfalls false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Bestimmt, ob eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz gleich einem angegebenen Zeichenkettennamen ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Vergleichen. |
|
|  | name | java.lang.String | Der Zeichenkettenname zum Vergleich mit der [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz. |
|

**Returns:**
boolean - true, wenn der Name der [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz dem angegebenen Zeichenkettennamen entspricht; andernfalls false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Bestimmt, ob eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz nicht gleich einem angegebenen Zeichenkettennamen ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Vergleichen. |
|
|  | name | java.lang.String | Der Zeichenkettenname zum Vergleich mit der [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz. |
|

**Returns:**
boolean - true, wenn der Name der [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz nicht dem angegebenen Zeichenkettennamen entspricht; andernfalls false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Konvertiert implizit eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz in einen Integer.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Konvertieren. |
|

**Returns:**
int - Der eindeutige Bezeichner der [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz.

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Konvertiert implizit eine [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz in eine Zeichenkette.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Die [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz zum Konvertieren. |
|

**Returns:**
java.lang.String - Der Name der [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Instanz.

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Konvertiert eine Zeichenkette, die einen Formatfamiliennamen darstellt, in ein [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | family | java.lang.String | Der Name der Formatfamilie zum Konvertieren. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Konvertiert einen Integer, der eine Formatfamilien-ID darstellt, in ein [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) Objekt.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | id | int | Die ID der Formatfamilie zum Konvertieren. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

