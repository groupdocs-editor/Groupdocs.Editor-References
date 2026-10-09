---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar basklassen för formatfamiljer som tillhandahåller gemensam funktionalitet för formatfamiljeinstanser."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Representerar basklassen för formatfamiljer, och tillhandahåller gemensam funktionalitet för formatfamiljeinstanser.

<br />

*** ** * ** ***

Denna klass är abstrakt och måste ärvas av en avledd klass som specificerar de faktiska formatfamiljedetaljerna.

<br />


## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getId()](#getId--) | Hämtar den unika identifieraren för formatfamiljen. |
|
|  | [getName()](#getName--) | Hämtar namnet på formatfamiljen. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bestämmer om detta objekt är lika med den angivna [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
|
|  | [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Hämtar alla instanser av den angivna typen |
T
som härstammar från [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med den angivna [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod för det aktuella objektet. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Hämtar en instans av den angivna typen |
T
som har den angivna identifieraren.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Hämtar en instans av den angivna typen |
T
som har det angivna namnet.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bestämmer om två [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instanser är lika. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bestämmer om två [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instanser inte är lika. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bestämmer om en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans är lika med ett angivet strängnamn. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bestämmer om en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans inte är lika med ett angivet strängnamn. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Konverterar en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans till ett heltal implicit. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Konverterar en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans till en sträng implicit. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Konverterar en sträng som representerar ett formatfamiljenamn till ett [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-objekt. |
|
|  | [fromId(int id)](#fromId-int-) | Konverterar ett heltal som representerar ett formatfamilje-ID till ett [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-objekt. |
|
### getId() {#getId--}
```
public final int getId()
```


Hämtar den unika identifieraren för formatfamiljen.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på formatfamiljen.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Bestämmer om detta objekt är lika med den angivna [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instansen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instansen att jämföra med den aktuella instansen. |
|

**Returns:**
boolean -  true  om den angivna [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) är lika med den aktuella instansen; annars,  false .

### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar det aktuella objektet.


**Returns:**
java.lang.String - En sträng som representerar det aktuella objektet, vilket är värdet av egenskapen  Name  .

<br />

*** ** * ** ***

Denna metod åsidosätter  object.ToString  för att returnera  Name  -egenskapen för objektet.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Hämtar alla instanser av den angivna typen
T
som härstammar från [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - En uppräkningsbar samling av instanser av den angivna typen  T .


T
: Typen av formatfamilj.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt är lika med den angivna [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instansen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Den [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instansen att jämföra med den aktuella instansen. |
|

**Returns:**
boolean -  true  om den angivna [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) är lika med den aktuella instansen; annars,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för det aktuella objektet.


**Returns:**
int - En hashkod för det aktuella objektet, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.

<br />

*** ** * ** ***

Denna metod åsidosätter  object.GetHashCode . Hashkoden beräknas med hjälp av objektets  Id  och  Name  -egenskaper. Det  unchecked  -kontextet tillåter overflow, vilket är acceptabelt i ett hashkodberäkningssammanhang.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Hämtar en instans av den angivna typen
T
som har den angivna identifieraren.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | värde | int | Identifieraren för formatfamiljen. |


T
: Typen av formatfamilj.
|

**Returns:**
T - En instans av den angivna typen T med den angivna identifieraren.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Hämtar en instans av den angivna typen
T
som har det angivna namnet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | namn | java.lang.String | Namnet på formatfamiljen. |


T
: Typen av formatfamilj.
|

**Returns:**
T - En instans av den angivna typen T med det angivna namnet.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Bestämmer om två [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instanser är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den första [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att jämföra. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den andra [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att jämföra. |
|

**Returns:**
boolean - sant om de två [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanserna är lika; annars falskt.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Bestämmer om två [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instanser inte är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den första [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att jämföra. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den andra [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att jämföra. |
|

**Returns:**
boolean - sant om de två [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instanserna inte är lika; annars falskt.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Bestämmer om en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans är lika med ett angivet strängnamn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att jämföra. |
|
|  | name | java.lang.String | Strängnamnet att jämföra med [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen. |
|

**Returns:**
boolean - sant om [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansens namn är lika med det angivna strängnamnet; annars falskt.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Bestämmer om en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans inte är lika med ett angivet strängnamn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att jämföra. |
|
|  | name | java.lang.String | Strängnamnet att jämföra med [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen. |
|

**Returns:**
boolean - sant om [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansens namn inte är lika med det angivna strängnamnet; annars falskt.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Konverterar en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans till ett heltal implicit.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att konvertera. |
|

**Returns:**
int - Den unika identifieraren för [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen.

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Konverterar en [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-instans till en sträng implicit.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Den [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen att konvertera. |
|

**Returns:**
java.lang.String - Namnet på [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) instansen.

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Konverterar en sträng som representerar ett formatfamiljenamn till ett [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | familj | java.lang.String | Namnet på formatfamiljen att konvertera. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Konverterar ett heltal som representerar ett formatfamilje-ID till ett [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)-objekt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | id | int | ID för formatfamiljen att konvertera. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

