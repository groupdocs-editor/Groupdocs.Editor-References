---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Format aileleri için ortak işlevsellik sağlayan temel sınıfı temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

Format aileleri için temel sınıfı temsil eder, format ailesi örnekleri için ortak işlevsellik sağlar.

<br />

*** ** * ** ***

Bu sınıf soyuttur ve gerçek format ailesi ayrıntılarını belirten türetilmiş bir sınıf tarafından miras alınmalıdır.

<br />


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getId()](#getId--) | Format ailesi için benzersiz tanımlayıcıyı alır. |
|
|  | [getName()](#getName--) | Format ailesinin adını alır. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bu örneğin belirtilen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
|
|  | [toString()](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | Belirtilen tipin tüm örneklerini alır |
T
bu, [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sınıfından türetilen.
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bu örneğin belirtilen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler. |
|
|  | [hashCode()](#hashCode--) | Geçerli nesne için bir karma kodu döndürür. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | Belirtilen tipin bir örneğini alır. |
T
belirtilen tanımlayıcıya sahip olan.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | Belirtilen tipin bir örneğini alır. |
T
belirtilen ada sahip olan.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | İki [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin eşit olup olmadığını belirler. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | İki [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin eşit olmama durumunu belirler. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin belirtilen dize adına eşit olup olmadığını belirler. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin belirtilen dize adına eşit olmama durumunu belirler. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğini örtük olarak bir tam sayıya dönüştürür. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğini örtük olarak bir dizeye dönüştürür. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | Bir format ailesi adını temsil eden dizeyi bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) nesnesine dönüştürür. |
|
|  | [fromId(int id)](#fromId-int-) | Bir format ailesi kimliğini temsil eden tam sayıyı bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) nesnesine dönüştürür. |
|
### getId() {#getId--}
```
public final int getId()
```


Format ailesi için benzersiz tanımlayıcıyı alır.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Format ailesinin adını alır.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


Bu örneğin belirtilen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Geçerli örnek ile karşılaştırılacak [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|

**Returns:**
boolean -  true  eğer belirtilen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) geçerli örnek ile eşitse; aksi takdirde,  false .

### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir dize döndürür.


**Returns:**
java.lang.String - Geçerli nesneyi temsil eden bir dize, bu da  Name  özelliğinin değeridir.

<br />

*** ** * ** ***

Bu yöntem, nesnenin  Name  özelliğini döndürmek için  object.ToString  metodunu geçersiz kılar.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


Belirtilen tipin tüm örneklerini alır
T
bu, [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) sınıfından türetilen.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - Belirtilen  T  tipinin örneklerinden oluşan bir yinelenebilir koleksiyon.


T
: Format ailesinin türü.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bu örneğin belirtilen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Geçerli örnek ile karşılaştırılacak [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|

**Returns:**
boolean -  true  eğer belirtilen [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) geçerli örnek ile eşitse; aksi takdirde,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Geçerli nesne için bir karma kodu döndürür.


**Returns:**
int - Geçerli nesne için bir hash kodu, hash tabloları gibi veri yapılarında ve hashleme algoritmalarında kullanılmaya uygundur.

<br />

*** ** * ** ***

Bu yöntem,  object.GetHashCode  metodunu geçersiz kılar. Hash kodu, nesnenin  Id  ve  Name  özellikleri kullanılarak hesaplanır.  unchecked  bağlamı taşmayı izin verir; bu, bir hash kodu hesaplama bağlamında kabul edilebilir.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


Belirtilen tipin bir örneğini alır.
T
belirtilen tanımlayıcıya sahip olan.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | değer | int | Biçim ailesinin tanımlayıcısı. |


T
: Format ailesinin türü.
|

**Returns:**
T - Belirtilen tanımlayıcıya sahip belirtilen tür T örneği.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


Belirtilen tipin bir örneğini alır.
T
belirtilen ada sahip olan.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | ad | java.lang.String | Biçim ailesinin adı. |


T
: Format ailesinin türü.
|

**Returns:**
T - Belirtilen ada sahip belirtilen tür T örneği.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


İki [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Karşılaştırılacak ilk [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Karşılaştırılacak ikinci [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|

**Returns:**
boolean - iki [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği eşitse true; aksi takdirde false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


İki [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin eşit olmama durumunu belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Karşılaştırılacak ilk [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Karşılaştırılacak ikinci [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|

**Returns:**
boolean - iki [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği eşit değilse true; aksi takdirde false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin belirtilen dize adına eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Karşılaştırılacak [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|
|  | name | java.lang.String | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle karşılaştırılacak dize adı. |
|

**Returns:**
boolean - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin adı belirtilen dize adıyla eşitse true; aksi takdirde false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin belirtilen dize adına eşit olmama durumunu belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Karşılaştırılacak [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|
|  | name | java.lang.String | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğiyle karşılaştırılacak dize adı. |
|

**Returns:**
boolean - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin adı belirtilen dize adıyla eşit değilse true; aksi takdirinde false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğini örtük olarak bir tam sayıya dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Dönüştürülecek [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|

**Returns:**
int - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin benzersiz tanımlayıcısı.

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


Bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğini örtük olarak bir dizeye dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | Dönüştürülecek [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneği. |
|

**Returns:**
java.lang.String - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) örneğinin adı.

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


Bir format ailesi adını temsil eden dizeyi bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | aile | java.lang.String | Dönüştürülecek biçim ailesinin adı. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


Bir format ailesi kimliğini temsil eden tam sayıyı bir [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) nesnesine dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | id | int | Dönüştürülecek biçim ailesinin kimliği. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

