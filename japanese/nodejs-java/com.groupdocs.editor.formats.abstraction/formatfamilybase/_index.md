---
title: "FormatFamilyBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "フォーマットファミリーのインスタンスに共通機能を提供する、フォーマットファミリー用の基底クラスを表します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.formats.abstraction/formatfamilybase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class FormatFamilyBase implements System.IEquatable<FormatFamilyBase>
```

形式ファミリーの基本クラスを表し、形式ファミリーインスタンスに共通の機能を提供します。

<br />

*** ** * ** ***

このクラスは抽象クラスであり、実際のフォーマットファミリーの詳細を指定する派生クラスによって継承される必要があります。

<br />


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getId()](#getId--) | フォーマットファミリーの一意の識別子を取得します。 |
|
|  | [getName()](#getName--) | フォーマットファミリーの名前を取得します。 |
|
|  | [equals(FormatFamilyBase other)](#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | このインスタンスが指定された[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスと等しいかどうかを判断します。 |
|
|  | [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
|
|  | [<T>getAll(Class<T> clazz)](#-T-getAll-java.lang.Class-T--) | 指定された型のすべてのインスタンスを取得します |
T
それらは[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)から派生します。
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスと等しいかどうかを判断します。 |
|
|  | [hashCode()](#hashCode--) | 現在のオブジェクトのハッシュコードを返します。 |
|
|  | [<T>fromValue(Class<T> clazz, int value)](#-T-fromValue-java.lang.Class-T--int-) | 指定された型のインスタンスを取得します |
T
指定された識別子を持つもの。
|
|  | [<T>fromName(Class<T> clazz, String name)](#-T-fromName-java.lang.Class-T--java.lang.String-) | 指定された型のインスタンスを取得します |
T
指定された名前を持つもの。
|
|  | [areEqual(FormatFamilyBase first, FormatFamilyBase second)](#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 2つの[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが等しいかどうかを判断します。 |
|
|  | [areNotEqual(FormatFamilyBase first, FormatFamilyBase second)](#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | 2つの[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが等しくないかどうかを判断します。 |
|
|  | [equalsName(FormatFamilyBase first, String name)](#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | ある[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが指定された文字列名と等しいかどうかを判断します。 |
|
|  | [notEqualsName(FormatFamilyBase first, String name)](#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-) | ある[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが指定された文字列名と等しくないかどうかを判断します。 |
|
|  | [toInt(FormatFamilyBase family)](#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスを暗黙的に整数に変換します。 |
|
|  | [toString(FormatFamilyBase family)](#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-) | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスを暗黙的に文字列に変換します。 |
|
|  | [fromName(String family)](#fromName-java.lang.String-) | フォーマットファミリー名を表す文字列を[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)オブジェクトに変換します。 |
|
|  | [fromId(int id)](#fromId-int-) | フォーマットファミリーIDを表す整数を[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)オブジェクトに変換します。 |
|
### getId() {#getId--}
```
public final int getId()
```


フォーマットファミリーの一意の識別子を取得します。


**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


フォーマットファミリーの名前を取得します。


**Returns:**
java.lang.String
### equals(FormatFamilyBase other) {#equals-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public final boolean equals(FormatFamilyBase other)
```


このインスタンスが指定された[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスと等しいかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 現在のインスタンスと比較するための[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンス。 |
|

**Returns:**
boolean - 指定された[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)が現在のインスタンスと等しい場合は true、そうでない場合は false。

### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。


**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列で、Name プロパティの値です。

<br />

*** ** * ** ***

このメソッドは object.ToString をオーバーライドし、オブジェクトの Name プロパティを返します。

<br />


### <T>getAll(Class<T> clazz) {#-T-getAll-java.lang.Class-T--}
```
public static List<T> <T>getAll(Class<T> clazz)
```


指定された型のすべてのインスタンスを取得します
T
それらは[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)から派生します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - 指定された型 T のインスタンスの列挙可能なコレクション。


T
: フォーマットファミリーの型です。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスと等しいかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 現在のインスタンスと比較するための[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンス。 |
|

**Returns:**
boolean - 指定された[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)が現在のインスタンスと等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


現在のオブジェクトのハッシュコードを返します。


**Returns:**
int - ハッシュテーブルなどのハッシュアルゴリズムやデータ構造で使用できる、現在のオブジェクトのハッシュコード。

<br />

*** ** * ** ***

このメソッドは object.GetHashCode をオーバーライドします。ハッシュコードはオブジェクトの Id と Name プロパティを使用して計算されます。unchecked コンテキストはオーバーフローを許容し、ハッシュコード計算のコンテキストでは許容されます。

<br />


### <T>fromValue(Class<T> clazz, int value) {#-T-fromValue-java.lang.Class-T--int-}
```
public static T <T>fromValue(Class<T> clazz, int value)
```


指定された型のインスタンスを取得します
T
指定された識別子を持つもの。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | 値 | int | フォーマットファミリの識別子。 |


T
: フォーマットファミリーの型です。
|

**Returns:**
T - 指定された識別子を持つ、指定された型 T のインスタンス。

### <T>fromName(Class<T> clazz, String name) {#-T-fromName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromName(Class<T> clazz, String name)
```


指定された型のインスタンスを取得します
T
指定された名前を持つもの。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| clazz | java.lang.Class<T> |  |
|  | 名前 | java.lang.String | フォーマットファミリの名前。 |


T
: フォーマットファミリーの型です。
|

**Returns:**
T - 指定された名前を持つ、指定された型 T のインスタンス。

### areEqual(FormatFamilyBase first, FormatFamilyBase second) {#areEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areEqual(FormatFamilyBase first, FormatFamilyBase second)
```


2つの[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが等しいかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 比較対象となる最初の [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 比較対象となる2番目の [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|

**Returns:**
boolean - 2つの [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスが等しい場合は true、そうでない場合は false。

### areNotEqual(FormatFamilyBase first, FormatFamilyBase second) {#areNotEqual-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static boolean areNotEqual(FormatFamilyBase first, FormatFamilyBase second)
```


2つの[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが等しくないかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 比較対象となる最初の [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|
|  | second | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 比較対象となる2番目の [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|

**Returns:**
boolean - 2つの [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスが等しくない場合は true、そうでない場合は false。

### equalsName(FormatFamilyBase first, String name) {#equalsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean equalsName(FormatFamilyBase first, String name)
```


ある[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが指定された文字列名と等しいかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 比較対象となる [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|
|  | name | java.lang.String | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと比較する文字列名。 |
|

**Returns:**
boolean - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスの名前が指定された文字列名と等しい場合は true、そうでない場合は false。

### notEqualsName(FormatFamilyBase first, String name) {#notEqualsName-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-java.lang.String-}
```
public static boolean notEqualsName(FormatFamilyBase first, String name)
```


ある[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスが指定された文字列名と等しくないかどうかを判断します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 比較対象となる [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|
|  | name | java.lang.String | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスと比較する文字列名。 |
|

**Returns:**
boolean - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスの名前が指定された文字列名と等しくない場合は true、そうでない場合は false。

### toInt(FormatFamilyBase family) {#toInt-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static int toInt(FormatFamilyBase family)
```


[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスを暗黙的に整数に変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 変換対象の [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|

**Returns:**
int - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスの一意の識別子。

### toString(FormatFamilyBase family) {#toString-com.groupdocs.editor.formats.abstraction.FormatFamilyBase-}
```
public static String toString(FormatFamilyBase family)
```


[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)インスタンスを暗黙的に文字列に変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | family | [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) | 変換対象の [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンス。 |
|

**Returns:**
java.lang.String - [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) インスタンスの名前。

### fromName(String family) {#fromName-java.lang.String-}
```
public static FormatFamilyBase fromName(String family)
```


フォーマットファミリー名を表す文字列を[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | family | java.lang.String | 変換対象のフォーマットファミリの名前。 |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family name.

### fromId(int id) {#fromId-int-}
```
public static FormatFamilyBase fromId(int id)
```


フォーマットファミリーIDを表す整数を[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase)オブジェクトに変換します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | id | int | 変換対象のフォーマットファミリの ID。 |
|

**Returns:**
[FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) - A [FormatFamilyBase](../../com.groupdocs.editor.formats.abstraction/formatfamilybase) object corresponding to the specified format family ID.

