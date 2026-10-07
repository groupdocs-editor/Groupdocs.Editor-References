---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta la classe base per le famiglie di formati che fornisce funzionalità comuni per le istanze delle famiglie di formati."
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Rappresenta la classe base per le famiglie di formato, fornendo funzionalità comuni per le istanze di famiglia di formato.

<br />

*** ** * ** ***

Questa classe è astratta e deve essere ereditata da una classe derivata che specifica i dettagli effettivi della famiglia di formati.

<br />


## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getId()](#getId--) | Ottiene l'identificatore univoco per la famiglia di formati. |
|
|  | [getName()](#getName--) | Ottiene il nome della famiglia di formati. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determina se questa istanza è uguale all'istanza [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) specificata. |
|
|  | [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Recupera tutte le istanze del tipo specificato |
T
che derivano da [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza è uguale all'istanza [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) specificata. |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash per l'oggetto corrente. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Recupera un'istanza del tipo specificato |
T
che ha l'identificatore specificato.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Recupera un'istanza del tipo specificato |
T
che ha il nome specificato.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determina se due istanze di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sono uguali. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Determina se due istanze di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) non sono uguali. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Determina se un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) è uguale a un nome stringa specificato. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Determina se un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) non è uguale a un nome stringa specificato. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Converte implicitamente un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) in un intero. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Converte implicitamente un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) in una stringa. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Converte una stringa che rappresenta il nome di una famiglia di formati in un oggetto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | Converte un intero che rappresenta l'ID di una famiglia di formati in un oggetto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


Ottiene l'identificatore univoco per la famiglia di formati.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome della famiglia di formati.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Determina se questa istanza è uguale all'istanza [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'istanza [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare con l'istanza corrente. |
|

**Returns:**
boolean -  true  se l'[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) specificato è uguale all'istanza corrente; altrimenti,  false .

### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.


**Returns:**
java.lang.String - Una stringa che rappresenta l'oggetto corrente, che è il valore della proprietà  Name .

<br />

*** ** * ** ***

Questo metodo sovrascrive  object.ToString  per restituire la proprietà  Name  dell'oggetto.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Recupera tutte le istanze del tipo specificato
T
che derivano da [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Una collezione enumerabile di istanze del tipo specificato  T .


T
: Il tipo di famiglia di formati.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza è uguale all'istanza [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | L'istanza [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare con l'istanza corrente. |
|

**Returns:**
boolean -  true  se l'[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) specificato è uguale all'istanza corrente; altrimenti,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per l'oggetto corrente.


**Returns:**
int - Un codice hash per l'oggetto corrente, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.

<br />

*** ** * ** ***

Questo metodo sovrascrive  object.GetHashCode . Il codice hash è calcolato utilizzando le proprietà  Id  e  Name  dell'oggetto. Il contesto  unchecked  consente overflow, il che è accettabile in un contesto di calcolo del codice hash.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Recupera un'istanza del tipo specificato
T
che ha l'identificatore specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | valore | int | L'identificatore della famiglia di formati. |


T
: Il tipo di famiglia di formati.
|

**Returns:**
T - Un'istanza del tipo specificato  T  con l'identificatore specificato.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Recupera un'istanza del tipo specificato
T
che ha il nome specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | nome | java.lang.String | Il nome della famiglia di formati. |


T
: Il tipo di famiglia di formati.
|

**Returns:**
T - Un'istanza del tipo specificato  T  con il nome specificato.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Determina se due istanze di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La prima istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La seconda istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare. |
|

**Returns:**
boolean - vero se le due istanze di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sono uguali; altrimenti, falso.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Determina se due istanze di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) non sono uguali.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La prima istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La seconda istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare. |
|

**Returns:**
boolean - vero se le due istanze di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) non sono uguali; altrimenti, falso.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Determina se un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) è uguale a un nome stringa specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare. |
|
|  | name | java.lang.String | Il nome stringa da confrontare con l'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - vero se il nome dell'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) è uguale al nome stringa specificato; altrimenti, falso.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Determina se un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) non è uguale a un nome stringa specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da confrontare. |
|
|  | name | java.lang.String | Il nome stringa da confrontare con l'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - vero se il nome dell'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) non è uguale al nome stringa specificato; altrimenti, falso.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Converte implicitamente un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) in un intero.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da convertire. |
|

**Returns:**
int - L'identificatore unico dell'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Converte implicitamente un'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) in una stringa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) da convertire. |
|

**Returns:**
java.lang.String - Il nome dell'istanza di [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Converte una stringa che rappresenta il nome di una famiglia di formati in un oggetto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | famiglia | java.lang.String | Il nome della famiglia di formati da convertire. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Converte un intero che rappresenta l'ID di una famiglia di formati in un oggetto [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | id | int | L'ID della famiglia di formati da convertire. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

