---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示格式族的基类，为格式族实例提供通用功能。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

表示格式族的基类，提供格式族实例的通用功能。

<br />

*** ** * ** ***

此类是抽象的，必须由指定实际格式族细节的派生类继承。

<br />


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getId()](#getId--) | 获取格式族的唯一标识符。 |
|
|  | [getName()](#getName--) | 获取格式族的名称。 |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 确定此实例是否等于指定的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|
|  | [toString()](#toString--) | 返回表示当前对象的字符串。 |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | 检索指定类型的所有实例 |
T
这些实例派生自 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)。
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 确定此实例是否等于指定的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|
|  | [hashCode()](#hashCode--) | 返回当前对象的哈希码。 |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | 检索指定类型的实例 |
T
具有指定标识符的实例。
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | 检索指定类型的实例 |
T
具有指定名称的实例。
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 确定两个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否相等。 |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 确定两个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否不相等。 |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | 确定一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否等于指定的字符串名称。 |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | 确定一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否不等于指定的字符串名称。 |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 将一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例隐式转换为整数。 |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 将一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例隐式转换为字符串。 |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | 将表示格式族名称的字符串转换为 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 对象。 |
|
|  | [fromId(int id)](#fromId-int-) | 将表示格式族 ID 的整数转换为 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 对象。 |
|
### getId() {#getId--}
```
public final int getId()
```


获取格式族的唯一标识符。


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


获取格式族的名称。


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


确定此实例是否等于指定的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 用于与当前实例比较的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|

**Returns:**
boolean - 如果指定的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 等于当前实例则为 true；否则为 false。

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。


**Returns:**
java.lang.String - 表示当前对象的字符串，其值为 Name 属性的值。

<br />

*** ** * ** ***

此方法重写 object.ToString，以返回对象的 Name 属性。

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


检索指定类型的所有实例
T
这些实例派生自 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - 指定类型 T 的实例的可枚举集合。


T
: 格式族的类型。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定此实例是否等于指定的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | obj | java.lang.Object | 用于与当前实例比较的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|

**Returns:**
boolean - 如果指定的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 等于当前实例则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


返回当前对象的哈希码。


**Returns:**
int - 当前对象的哈希码，适用于哈希算法和哈希表等数据结构。

<br />

*** ** * ** ***

此方法重写 object.GetHashCode。哈希码使用对象的 Id 和 Name 属性计算。unchecked 上下文允许溢出，这在哈希码计算中是可接受的。

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


检索指定类型的实例
T
具有指定标识符的实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | 值 | int | 格式族的标识符。 |


T
: 格式族的类型。
|

**Returns:**
T - 指定类型 T 的实例，具有指定的标识符。

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


检索指定类型的实例
T
具有指定名称的实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | 名称 | java.lang.String | 格式族的名称。 |


T
: 格式族的类型。
|

**Returns:**
T - 指定类型 T 的实例，具有指定的名称。

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


确定两个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要比较的第一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要比较的第二个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|

**Returns:**
boolean - 如果两个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例相等则为 true；否则为 false。

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


确定两个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否不相等。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要比较的第一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要比较的第二个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|

**Returns:**
boolean - 如果两个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例不相等则为 true；否则为 false。

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


确定一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否等于指定的字符串名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要比较的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|
|  | name | java.lang.String | 要与 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例比较的字符串名称。 |
|

**Returns:**
boolean - 如果 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例的名称等于指定的字符串名称则为 true；否则为 false。

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


确定一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例是否不等于指定的字符串名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要比较的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|
|  | name | java.lang.String | 要与 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例比较的字符串名称。 |
|

**Returns:**
boolean - 如果 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例的名称不等于指定的字符串名称则为 true；否则为 false。

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


将一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例隐式转换为整数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要转换的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|

**Returns:**
int - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例的唯一标识符。

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


将一个 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例隐式转换为字符串。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 要转换的 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例。 |
|

**Returns:**
java.lang.String - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 实例的名称。

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


将表示格式族名称的字符串转换为 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | family | java.lang.String | 要转换的格式族的名称。 |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


将表示格式族 ID 的整数转换为 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | id | int | 要转换的格式族的 ID。 |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

