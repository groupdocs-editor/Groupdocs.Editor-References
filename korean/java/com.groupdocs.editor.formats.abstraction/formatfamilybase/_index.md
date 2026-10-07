---
title: "FormatFamilyBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "형식 패밀리 인스턴스에 대한 공통 기능을 제공하는 형식 패밀리의 기본 클래스를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

형식 패밀리의 기본 클래스를 나타내며, 형식 패밀리 인스턴스에 공통 기능을 제공합니다.

<br />

*** ** * ** ***

이 클래스는 추상 클래스이며 실제 형식 패밀리 세부 정보를 지정하는 파생 클래스에서 상속해야 합니다.

<br />


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getId()](#getId--) | 형식 패밀리의 고유 식별자를 가져옵니다. |
|
|  | [getName()](#getName--) | 포맷 패밀리의 이름을 가져옵니다. |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 이 인스턴스가 지정된 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 여부를 결정합니다. |
|
|  | [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | 지정된 유형의 모든 인스턴스를 검색합니다. |
T
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)에서 파생된.
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 여부를 결정합니다. |
|
|  | [hashCode()](#hashCode--) | 현재 객체에 대한 해시 코드를 반환합니다. |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | 지정된 유형의 인스턴스를 검색합니다. |
T
지정된 식별자를 가진.
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | 지정된 유형의 인스턴스를 검색합니다. |
T
지정된 이름을 가진.
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 두 개의 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 같은지 여부를 결정합니다. |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 두 개의 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 다른지 여부를 결정합니다. |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | 지정된 문자열 이름과 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 같은지 여부를 결정합니다. |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | 지정된 문자열 이름과 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 다른지 여부를 결정합니다. |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스를 정수로 암시적으로 변환합니다. |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스를 문자열로 암시적으로 변환합니다. |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | 포맷 패밀리 이름을 나타내는 문자열을 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 객체로 변환합니다. |
|
|  | [fromId(int id)](#fromId-int-) | 포맷 패밀리 ID를 나타내는 정수를 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 객체로 변환합니다. |
|
### getId() {#getId--}
```
public final int getId()
```


형식 패밀리의 고유 식별자를 가져옵니다.


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


포맷 패밀리의 이름을 가져옵니다.


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


이 인스턴스가 지정된 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 현재 인스턴스와 비교할 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|

**Returns:**
boolean - 지정된 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)가 현재 인스턴스와 같으면 true, 그렇지 않으면 false.

### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.


**Returns:**
java.lang.String - 현재 객체를 나타내는 문자열이며, 이는 Name 속성의 값입니다.

<br />

*** ** * ** ***

이 메서드는 object.ToString을 재정의하여 객체의 Name 속성을 반환합니다.

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


지정된 유형의 모든 인스턴스를 검색합니다.
T
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)에서 파생된.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - 지정된 유형 T의 인스턴스들로 구성된 열거 가능한 컬렉션입니다.


T
: 포맷 패밀리 유형.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 현재 인스턴스와 비교할 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|

**Returns:**
boolean - 지정된 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)가 현재 인스턴스와 같으면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


현재 객체에 대한 해시 코드를 반환합니다.


**Returns:**
int - 현재 객체의 해시 코드이며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용하기에 적합합니다.

<br />

*** ** * ** ***

이 메서드는 object.GetHashCode를 재정의합니다. 해시 코드는 객체의 Id 및 Name 속성을 사용하여 계산됩니다. unchecked 컨텍스트는 오버플로를 허용하며, 이는 해시 코드 계산 상황에서 허용됩니다.

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


지정된 유형의 인스턴스를 검색합니다.
T
지정된 식별자를 가진.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | 값 | int | 포맷 패밀리의 식별자입니다. |


T
: 포맷 패밀리 유형.
|

**Returns:**
T - 지정된 식별자를 가진 지정된 유형 T의 인스턴스입니다.

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


지정된 유형의 인스턴스를 검색합니다.
T
지정된 이름을 가진.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | name | java.lang.String | 포맷 패밀리의 이름. |


T
: 포맷 패밀리 유형.
|

**Returns:**
T - 지정된 이름을 가진 지정된 유형 T의 인스턴스.

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


두 개의 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 비교할 첫 번째 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 비교할 두 번째 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|

**Returns:**
boolean - 두 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 동일하면 true; 그렇지 않으면 false.

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


두 개의 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 다른지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 비교할 첫 번째 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 비교할 두 번째 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|

**Returns:**
boolean - 두 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 동일하지 않으면 true; 그렇지 않으면 false.

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


지정된 문자열 이름과 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 비교할 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|
|  | name | java.lang.String | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 비교할 문자열 이름입니다. |
|

**Returns:**
boolean - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스의 이름이 지정된 문자열 이름과 같으면 true; 그렇지 않으면 false.

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


지정된 문자열 이름과 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스가 다른지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 비교할 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|
|  | name | java.lang.String | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스와 비교할 문자열 이름입니다. |
|

**Returns:**
boolean - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스의 이름이 지정된 문자열 이름과 다르면 true; 그렇지 않으면 false.

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스를 정수로 암시적으로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 변환할 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|

**Returns:**
int - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스의 고유 식별자입니다.

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스를 문자열로 암시적으로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 변환할 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스입니다. |
|

**Returns:**
java.lang.String - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 인스턴스의 이름입니다.

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


포맷 패밀리 이름을 나타내는 문자열을 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 패밀리 | java.lang.String | 변환할 포맷 패밀리의 이름입니다. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


포맷 패밀리 ID를 나타내는 정수를 [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) 객체로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | id | int | 변환할 포맷 패밀리의 ID입니다. |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

