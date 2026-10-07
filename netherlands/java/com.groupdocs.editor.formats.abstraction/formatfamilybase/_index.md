---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt de basisklasse voor formatfamilies voor die gemeenschappelijke functionaliteit biedt voor formatfamilie-instanties."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Stelt de basisklasse voor formatfamilies voor, die gemeenschappelijke functionaliteit voor formatfamilie-instanties biedt.

<br />

*** ** * ** ***

Deze klasse is abstract en moet worden geërfd door een afgeleide klasse die de werkelijke details van de formaatfamilie specificeert.

<br />


## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getId()](#getId--) | Haalt de unieke identifier op voor de formaatfamilie. |
|
|  | [getName()](#getName--) | Haalt de naam van de formaatfamilie op. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bepaalt of deze instantie gelijk is aan de opgegeven [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
|
|  | [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Haalt alle instanties op van het opgegeven type |
T
die afstammen van [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze instantie gelijk is aan de opgegeven [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor het huidige object. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Haalt een instantie op van het opgegeven type |
T
die de opgegeven identifier heeft.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Haalt een instantie op van het opgegeven type |
T
die de opgegeven naam heeft.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bepaalt of twee [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanties gelijk zijn. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bepaalt of twee [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanties niet gelijk zijn. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bepaalt of een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie gelijk is aan een opgegeven stringnaam. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bepaalt of een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie niet gelijk is aan een opgegeven stringnaam. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Converteert een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie impliciet naar een integer. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Converteert een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie impliciet naar een string. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Converteert een string die een formaatfamilienaam vertegenwoordigt naar een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object. |
|
|  | [fromId(int id)](#fromId-int-) | Converteert een integer die een formaatfamilie-ID vertegenwoordigt naar een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object. |
|
### getId() {#getId--}
```
public final int getId()
```


Haalt de unieke identifier op voor de formaatfamilie.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Haalt de naam van de formaatfamilie op.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken met de huidige instantie. |
|

**Returns:**
boolean -  true  als de opgegeven [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) gelijk is aan de huidige instantie; anders,  false .

### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.


**Returns:**
java.lang.String - Een string die het huidige object vertegenwoordigt, wat de waarde is van de  Name  eigenschap.

<br />

*** ** * ** ***

Deze methode overschrijft  object.ToString  om de  Name  eigenschap van het object terug te geven.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Haalt alle instanties op van het opgegeven type
T
die afstammen van [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Een doorzoekbare collectie van instanties van het opgegeven type  T .


T
: Het type van de formaatfamilie.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze instantie gelijk is aan de opgegeven [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | De [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken met de huidige instantie. |
|

**Returns:**
boolean -  true  als de opgegeven [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) gelijk is aan de huidige instantie; anders,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor het huidige object.


**Returns:**
int - Een hashcode voor het huidige object, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.

<br />

*** ** * ** ***

Deze methode overschrijft  object.GetHashCode . De hashcode wordt berekend met behulp van de  Id  en  Name  eigenschappen van het object. De  unchecked  context staat overflow toe, wat acceptabel is in een hashcode-berekeningscontext.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Haalt een instantie op van het opgegeven type
T
die de opgegeven identifier heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | waarde | int | De identifier van de formaatfamilie. |


T
: Het type van de formaatfamilie.
|

**Returns:**
T - Een instantie van het opgegeven type  T  met de opgegeven identifier.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Haalt een instantie op van het opgegeven type
T
die de opgegeven naam heeft.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | naam | java.lang.String | De naam van de formaatfamilie. |


T
: Het type van de formaatfamilie.
|

**Returns:**
T - Een instantie van het opgegeven type  T  met de opgegeven naam.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Bepaalt of twee [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanties gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De eerste [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De tweede [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken. |
|

**Returns:**
boolean - true als de twee [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanties gelijk zijn; anders false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Bepaalt of twee [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanties niet gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De eerste [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De tweede [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken. |
|

**Returns:**
boolean - true als de twee [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanties niet gelijk zijn; anders false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Bepaalt of een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie gelijk is aan een opgegeven stringnaam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken. |
|
|  | name | java.lang.String | De tekenreeksnaam om te vergelijken met de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
|

**Returns:**
boolean - true als de naam van de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie gelijk is aan de opgegeven tekenreeksnaam; anders false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Bepaalt of een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie niet gelijk is aan een opgegeven stringnaam.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te vergelijken. |
|
|  | name | java.lang.String | De tekenreeksnaam om te vergelijken met de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie. |
|

**Returns:**
boolean - true als de naam van de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie niet gelijk is aan de opgegeven tekenreeksnaam; anders false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Converteert een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie impliciet naar een integer.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te converteren. |
|

**Returns:**
int - De unieke identifier van de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie.

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Converteert een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie impliciet naar een string.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | De [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie om te converteren. |
|

**Returns:**
java.lang.String - De naam van de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instantie.

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Converteert een string die een formaatfamilienaam vertegenwoordigt naar een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | familie | java.lang.String | De naam van de formaatfamilie om te converteren. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Converteert een integer die een formaatfamilie-ID vertegenwoordigt naar een [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | id | int | De ID van de formaatfamilie om te converteren. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

