---
title: "FormatFamilyBase"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente la classe de base pour les familles de format fournissant des fonctionnalités communes aux instances de familles de format."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Représente la classe de base pour les familles de formats, offrant une fonctionnalité commune aux instances de famille de format.

<br />

*** ** * ** ***

Cette classe est abstraite et doit être héritée par une classe dérivée qui spécifie les détails réels de la famille de formats.

<br />


## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getId()](#getId--) | Obtient l'identifiant unique de la famille de formats. |
|
|  | [getName()](#getName--) | Obtient le nom de la famille de formats. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Détermine si cette instance est égale à l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) spécifiée. |
|
|  | [toString()](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Récupère toutes les instances du type spécifié |
T
qui dérivent de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si cette instance est égale à l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) spécifiée. |
|
|  | [hashCode()](#hashCode--) | Renvoie un code de hachage pour l'objet actuel. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Récupère une instance du type spécifié |
T
qui possède l'identifiant spécifié.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Récupère une instance du type spécifié |
T
qui possède le nom spécifié.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Détermine si deux instances de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sont égales. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Détermine si deux instances de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ne sont pas égales. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Détermine si une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) est égale à un nom de chaîne spécifié. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Détermine si une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) n'est pas égale à un nom de chaîne spécifié. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Convertit implicitement une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) en entier. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Convertit implicitement une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) en chaîne. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Convertit une chaîne représentant le nom d'une famille de formats en objet [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
|  | [fromId(int id)](#fromId-int-) | Convertit un entier représentant l'ID d'une famille de formats en objet [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|
### getId() {#getId--}
```
public final int getId()
```


Obtient l'identifiant unique de la famille de formats.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Obtient le nom de la famille de formats.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Détermine si cette instance est égale à l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer avec l'instance actuelle. |
|

**Returns:**
booléen -  true  si le [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) spécifié est égal à l'instance actuelle ; sinon,  false .

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l'objet actuel.


**Returns:**
java.lang.String - Une chaîne qui représente l'objet actuel, qui est la valeur de la propriété  Name .

<br />

*** ** * ** ***

Cette méthode remplace  object.ToString  pour renvoyer la propriété  Name  de l'objet.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Récupère toutes les instances du type spécifié
T
qui dérivent de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Une collection énumérable d'instances du type spécifié  T .


T
: Le type de la famille de formats.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si cette instance est égale à l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | L'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer avec l'instance actuelle. |
|

**Returns:**
booléen -  true  si le [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) spécifié est égal à l'instance actuelle ; sinon,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour l'objet actuel.


**Returns:**
int - Un code de hachage pour l'objet actuel, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.

<br />

*** ** * ** ***

Cette méthode remplace  object.GetHashCode . Le code de hachage est calculé en utilisant les propriétés  Id  et  Name  de l'objet. Le contexte  unchecked  autorise le dépassement, ce qui est acceptable dans le contexte du calcul d'un code de hachage.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Récupère une instance du type spécifié
T
qui possède l'identifiant spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | valeur | int | L'identifiant de la famille de formats. |


T
: Le type de la famille de formats.
|

**Returns:**
T - Une instance du type spécifié  T  avec l'identifiant spécifié.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Récupère une instance du type spécifié
T
qui possède le nom spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | name | java.lang.String | Le nom de la famille de formats. |


T
: Le type de la famille de formats.
|

**Returns:**
T - Une instance du type spécifié  T  avec le nom spécifié.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Détermine si deux instances de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La première instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La deuxième instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer. |
|

**Returns:**
boolean - true si les deux instances [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sont égales ; sinon, false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


Détermine si deux instances de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ne sont pas égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La première instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | La deuxième instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer. |
|

**Returns:**
boolean - true si les deux instances [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) ne sont pas égales ; sinon, false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Détermine si une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) est égale à un nom de chaîne spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer. |
|
|  | name | java.lang.String | Le nom de chaîne à comparer avec l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true si le nom de l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) est égal au nom de chaîne spécifié ; sinon, false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Détermine si une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) n'est pas égale à un nom de chaîne spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à comparer. |
|
|  | name | java.lang.String | Le nom de chaîne à comparer avec l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase). |
|

**Returns:**
boolean - true si le nom de l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) n'est pas égal au nom de chaîne spécifié ; sinon, false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Convertit implicitement une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) en entier.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à convertir. |
|

**Returns:**
int - L'identifiant unique de l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Convertit implicitement une instance de [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) en chaîne.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | L'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) à convertir. |
|

**Returns:**
java.lang.String - Le nom de l'instance [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Convertit une chaîne représentant le nom d'une famille de formats en objet [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | famille | java.lang.String | Le nom de la famille de formats à convertir. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Convertit un entier représentant l'ID d'une famille de formats en objet [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | id | int | L'ID de la famille de formats à convertir. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

