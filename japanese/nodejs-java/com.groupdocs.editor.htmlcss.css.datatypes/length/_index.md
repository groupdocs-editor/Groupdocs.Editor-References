---
title: "Length"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "パーセンテージや単位なしの型を含む、サポート可能な任意の単位での CSS 長さ値を表します。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

パーセンテージを含む、サポート可能な任意の単位での CSS 長さ値を表します。
および単位なしの型。値は整数または浮動小数点、負、ゼロ、そして
正です。変更不可能な構造体です。

*** ** * ** ***


この型は次の CSS データ型をカバーします：

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Length()](#Length--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | 単位なし整数ゼロ - デフォルト値で、デフォルトのパラメータなしと同じです |
コンストラクタ
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | 指定された浮動小数点数で Length 型のインスタンスを作成し、返します |
および単位
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | 指定された double 数で Length 型のインスタンスを作成し、返します |
および単位
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | 指定された整数で Length 型のインスタンスを作成し、返します |
数値と単位
|
|  | [isUnitlessZero()](#isUnitlessZero--) | このインスタンスが単位なしゼロかどうかを判定します。 |
|
|  | [isDefault()](#isDefault--) | この Length インスタンスがデフォルト値 \\u2014 単位なし を持つかどうかを示します |
ゼロ。
|
|  | [getUnitType()](#getUnitType--) | この Length インスタンスの単位タイプを返します。 |
|
|  | [isInteger()](#isInteger--) | この Length インスタンスの数値が...であるかどうかを示します |
元々整数 (INT32) として指定され、保存されています
|
|  | [isFloat()](#isFloat--) | この Length インスタンスの数値が...であるかどうかを示します |
元々浮動小数点数 (FP32) として指定され、保存されています
|
|  | [getFloatValue()](#getFloatValue--) | Length インスタンスの浮動小数点数値を返します。 |
|
|  | [getIntegerValue()](#getIntegerValue--) | この Length インスタンスの整数数値を返します（ただし、 |
内部的に整数として保存されている場合、例外をスローします、もし
元々浮動小数点数として保存されています。
|
|  | [isAbsolute()](#isAbsolute--) | 長さが絶対単位で与えられているか取得します。 |
|
|  | [isRelative()](#isRelative--) | 長さが相対単位で与えられているか取得します。 |
|
|  | [isZero()](#isZero--) | この長さの数値がゼロであるかどうかを判断します |
|
|  | [isNegative()](#isNegative--) | この長さの数値が負の数であるかどうかを判断します |
|
|  | [isPositive()](#isPositive--) | この長さの数値が正の数であるかどうかを判断します |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | この値は単位なしタイプですが、ゼロではなく、正または負です |
number
|
|  | [toPixel()](#toPixel--) | 可能であれば、長さをピクセル数に変換します。 |
|
|  | [to(int unit)](#to-int-) | 可能であれば、長さを指定された単位に変換します。 |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | 指定された単位タイプでこの長さの文字列表現を返します。 |
|
|  | [serializeDefault()](#serializeDefault--) | この長さを元のネイティブ形式で文字列として返します |
（保存されている形）で、長さの値を他の単位に変換せずに
単位タイプ
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | この値が他の指定された長さと等しいかどうかを定義します |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | この長さが指定されたオブジェクトと等しいかどうかを判断します |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | 与えられた Length を指定された係数で乗算します |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 2つの与えられた長さの等価性をチェックします。 |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 2つの与えられた長さの不等価性をチェックします。 |
|
|  | [hashCode()](#hashCode--) | この Length インスタンスのハッシュコードを組み合わせて計算し、返します |
値と単位型のハッシュコード
|
|  | [deepClone()](#deepClone--) | この Length インスタンスの完全なコピーを返します |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | 指定された単位名を解析し、対応する値を返そうとします |
Unit 列挙型。
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | 指定された文字列を Length 値として解析しようとします。その |
数値と単位名
|
|  | [parse(String input)](#parse-java.lang.String-) | 指定された文字列を Length 値として解析し、返します。その |
数値と単位名、または失敗時に例外をスローします
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


単位なし整数ゼロ - デフォルト値で、デフォルトのパラメータなしと同じです
コンストラクタ


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


指定された浮動小数点数で Length 型のインスタンスを作成し、返します
および単位


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 値 | float | \>任意の float (FP32) 数値 |
|
|  | 単位 | int | 有効な単位型 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


指定された double 数で Length 型のインスタンスを作成し、返します
および単位


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 値 | double | 任意の double (FP64) 数値は、float (FP32) に変換されます |
|
|  | 単位 | int | 有効な単位型 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


指定された整数で Length 型のインスタンスを作成し、返します
数値と単位


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int | 任意の整数 |
|
|  | 単位 | int | 有効な単位型 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


このインスタンスが単位なしのゼロかどうかを判定します。単位なしゼロ
この型のデフォルト値です。IsDefault プロパティと同じです。


**Returns:**
ブール
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


この Length インスタンスがデフォルト値 \\u2014 単位なし を持つかどうかを示します
ゼロです。IsUnitlessZero プロパティと同じです。


**Returns:**
ブール
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


この Length インスタンスの単位タイプを返します。


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


この Length インスタンスの数値が...であるかどうかを示します
元々整数 (INT32) として指定され、保存されています


**Returns:**
ブール
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


この Length インスタンスの数値が...であるかどうかを示します
元々浮動小数点数 (FP32) として指定され、保存されています


**Returns:**
ブール
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Length インスタンスの float 数値を返します。決して例外をスローしません
例外 - 必要に応じて Integer 値を Float に変換します。


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


この Length インスタンスの整数数値を返します（ただし、
内部的に整数として保存されている場合、例外をスローします、もし
元々浮動小数点数として保存されています。


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


長さが絶対単位で与えられているか取得します。そのような長さは
ピクセルに変換されます。


**Returns:**
ブール
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


長さが相対単位で与えられているか取得します。そのような長さは
ピクセルに変換されます。


**Returns:**
ブール
### isZero() {#isZero--}
```
public final boolean isZero()
```


この長さの数値がゼロであるかどうかを判断します


**Returns:**
ブール
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


この長さの数値が負の数であるかどうかを判断します


**Returns:**
ブール
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


この長さの数値が正の数であるかどうかを判断します


**Returns:**
ブール
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


この値は単位なしタイプですが、ゼロではなく、正または負です
number


**Returns:**
ブール
### toPixel() {#toPixel--}
```
public final float toPixel()
```


可能であれば長さをピクセル数に変換します。現在の
単位が相対的である場合、例外がスローされます。


**Returns:**
float - 現在の長さが表すピクセル数。

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


長さを可能であれば指定された単位に変換します。現在の単位または
指定された単位が相対的な場合、例外がスローされます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 単位 | int | 変換先の単位。 |
|

**Returns:**
float - 現在の長さの指定された単位での値。

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


指定された単位タイプでこの長さの文字列表現を返します。
数値は単位タイプの変更に対応して変換されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 単位 | int | シリアライズして文字列に変換する前に、このインスタンスが変換されるべき指定された単位です。有効である必要があります。単位なしにはできません。 |
|

**Returns:**
java.lang.String - 文字列表現

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


この長さを元のネイティブ形式で文字列として返します
（保存されている形）で、長さの値を他の単位に変換せずに
単位タイプ


**Returns:**
java.lang.String - 文字列インスタンス

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


この値が他の指定された長さと等しいかどうかを定義します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length 型の他のインスタンス |
|

**Returns:**
boolean - 等しい場合は true、そうでなければ false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この長さが指定されたオブジェクトと等しいかどうかを判断します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | Length 型の他のインスタンスで、System.Object または他の抽象型やインターフェイスにボックス化されたもの |
|

**Returns:**
boolean - 等しい場合は true、そうでなければ false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


与えられた Length を指定された係数で乗算します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - 乗数 |
|
|  | 係数 | int | 任意の整数 - 係数 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


2つの与えられた長さの等価性をチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 左側の長さオペランド。 |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 右側の長さオペランド。 |
|

**Returns:**
boolean - 両方の長さが等しい場合は true、そうでなければ false。

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


2つの与えられた長さの不等価性をチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 左側の長さオペランド。 |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 右側の長さオペランド。 |
|

**Returns:**
boolean - 両方の長さが等しくない場合は true、そうでなければ false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


この Length インスタンスのハッシュコードを組み合わせて計算し、返します
値と単位型のハッシュコード


**Returns:**
int - 整数

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


この Length インスタンスの完全なコピーを返します


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


指定された単位名を解析し、対応する値を返そうとします
Unit 列挙型。適切な LengthUnit が見つからない場合は LengthUnit.Unitless を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | unitName | java.lang.String | 単位名を表す文字列 |
|

**Returns:**
int - Unit 列挙型の値（いずれの場合でも）、適切な単位が見つからないときは LengthUnit.Unitless

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


指定された文字列を Length 値として解析しようとします。その
数値と単位名


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | input | java.lang.String | 解析すべき入力文字列 |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 出力パラメータで、解析結果を含みます。解析に失敗した場合は、デフォルトの Length 値（単位なしのゼロ）を含みます。 |
|

**Returns:**
boolean - パースが成功した場合は true、失敗した場合は false

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


指定された文字列を Length 値として解析し、返します。その
数値と単位名、または失敗時に例外をスローします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | input | java.lang.String | 解析すべき入力文字列 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

