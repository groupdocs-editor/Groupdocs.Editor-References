---
title: FormatFamilyBase
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Represents the base class for format families providing common functionality for format family instances.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Represents the base class for format families, providing common functionality for format family instances.

<br />

*** ** * ** ***

This class is abstract and must be inherited by a derived class that specifies the actual format family details.

<br />


## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Gets the unique identifier for the format family.
 |
| [getName()](#getName--) | Gets the name of the format family.
 |
| [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determines whether this instance is equal to the specified [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.
 |
| [toString()](#toString--) | Returns a string that represents the current object.
 |
| [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Retrieves all instances of the specified type 
T
 that derive from [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
 |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether this instance is equal to the specified [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.
 |
| [hashCode()](#hashCode--) | Returns a hash code for the current object.
 |
| [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Retrieves an instance of the specified type 
T
 that has the specified identifier.
 |
| [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Retrieves an instance of the specified type 
T
 that has the specified name.
 |
| [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determines whether two [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instances are equal.
 |
| [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determines whether two [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instances are not equal.
 |
| [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Determines whether a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance is equal to a specified string name.
 |
| [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Determines whether a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance is not equal to a specified string name.
 |
| [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Converts a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to an integer implicitly.
 |
| [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Converts a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to a string implicitly.
 |
| [fromName(String family)](#fromName-java.lang.String-) | Converts a string representing a format family name to a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object.
 |
| [fromId(int id)](#fromId-int-) | Converts an integer representing a format family ID to a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object.
 |
### getId() {#getId--}
```
public final int getId()
```


Gets the unique identifier for the format family.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets the name of the format family.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Determines whether this instance is equal to the specified [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare with the current instance.
 |

**Returns:**
boolean -  true  if the specified [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) is equal to the current instance; otherwise,  false .

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.


**Returns:**
java.lang.String - A string that represents the current object, which is the value of the  Name  property.

<br />

*** ** * ** ***

This method overrides  object.ToString  to return the  Name  property of the object.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Retrieves all instances of the specified type 
T
 that derive from [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - An enumerable collection of instances of the specified type  T .


T
: The type of format family.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether this instance is equal to the specified [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare with the current instance.
 |

**Returns:**
boolean -  true  if the specified [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) is equal to the current instance; otherwise,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for the current object.


**Returns:**
int - A hash code for the current object, suitable for use in hashing algorithms and data structures like a hash table.

<br />

*** ** * ** ***

This method overrides  object.GetHashCode . The hash code is computed using the object's  Id  and  Name  properties. The  unchecked  context allows overflow, which is acceptable in a hash code calculation context.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Retrieves an instance of the specified type 
T
 that has the specified identifier.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
| value | int | The identifier of the format family.


T
: The type of format family.
 |

**Returns:**
T - An instance of the specified type  T  with the specified identifier.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Retrieves an instance of the specified type 
T
 that has the specified name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
| name | java.lang.String | The name of the format family.


T
: The type of format family.
 |

**Returns:**
T - An instance of the specified type  T  with the specified name.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Determines whether two [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instances are equal.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The first [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare.
 |
| second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The second [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare.
 |

**Returns:**
boolean - true if the two [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instances are equal; otherwise, false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Determines whether two [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instances are not equal.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The first [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare.
 |
| second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The second [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare.
 |

**Returns:**
boolean - true if the two [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instances are not equal; otherwise, false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Determines whether a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance is equal to a specified string name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare.
 |
| name | java.lang.String | The string name to compare with the [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.
 |

**Returns:**
boolean - true if the [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance's name is equal to the specified string name; otherwise, false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Determines whether a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance is not equal to a specified string name.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to compare.
 |
| name | java.lang.String | The string name to compare with the [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.
 |

**Returns:**
boolean - true if the [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance's name is not equal to the specified string name; otherwise, false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Converts a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to an integer implicitly.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to convert.
 |

**Returns:**
int - The unique identifier of the [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Converts a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to a string implicitly.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | The [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance to convert.
 |

**Returns:**
java.lang.String - The name of the [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instance.

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Converts a string representing a format family name to a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| family | java.lang.String | The name of the format family to convert.
 |

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Converts an integer representing a format family ID to a [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | The ID of the format family to convert.
 |

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

