---
title: "比率"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "ratio CSS データ型を表し、メディアクエリにおけるアスペクト比やラスタ画像の記述に使用され、分子と分母と呼ばれる単位なしの 2 つの値間の比例を示します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

\"ratio\" CSS データ型を表し、アスペクト
メディアクエリにおける比率やラスタ画像の比例を示すことにより
\"numerator\" と \"denominator\" と呼ばれる単位なしの 2 つの値間。Immutable
構造体。


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Single](#Single) | 単一のデフォルト比率 1/1 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | この ratio の分子を返します |
|
|  | [getDenominator()](#getDenominator--) | この ratio の分母を返します |
|
|  | [calculate()](#calculate--) | この ratio を単一の浮動小数点数として計算し、返します |
|
|  | [getInverseRatio()](#getInverseRatio--) | この ratio の逆（相互）ratio を生成し、返します |
|
|  | [serializeDefault()](#serializeDefault--) | この ratio を文字列にシリアライズし、返します |
|
|  | [toString()](#toString--) | この ratio の文字列表現を返します；同等は |
\"SerializeDefault()\"
|
|  | [isDefault()](#isDefault--) | この ratio がデフォルト値を持つか、\"1/1\"（単一）であるかを判定します |
|
|  | [deepClone()](#deepClone--) | この ratio の完全なコピーを返します |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | このインスタンスが指定された \"Ratio\" インスタンスと等しいかどうかを判定します |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、 |
それはおそらく別の \"Ratio\" インスタンスです
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 2 つの ratio を比較し、両者が一致するかを示すブール値を返します。 |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 2 つの ratio を比較し、両者が一致しないかを示すブール値を返します |
一致。
|
|  | [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。このハッシュコードはインスタンスの存続期間中に変更できません |
存続期間
|
|  | [create(int numerator, int denominator)](#create-int-int-) | 指定された分子とから Ratio インスタンスを作成し、返します |
分母
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


単一のデフォルト比率 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


この ratio の分子を返します


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


この ratio の分母を返します


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


この ratio を単一の浮動小数点数として計算し、返します


**Returns:**
double - 倍精度浮動小数点数

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


この ratio の逆（相互）ratio を生成し、返します


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


この ratio を文字列にシリアライズし、返します


**Returns:**
java.lang.String - "numerator/denominator" 形式の文字列

### toString() {#toString--}
```
public String toString()
```


この ratio の文字列表現を返します；同等は
\"SerializeDefault()\"


**Returns:**
java.lang.String - "numerator/denominator" 形式の文字列

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


この ratio がデフォルト値を持つか、\"1/1\"（単一）であるかを判定します


**Returns:**
ブール
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


この ratio の完全なコピーを返します


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


このインスタンスが指定された \"Ratio\" インスタンスと等しいかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | このインスタンスと等価かどうかを確認するための他の Ratio インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、
それはおそらく別の \"Ratio\" インスタンスです


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | その他 | java.lang.Object | このインスタンスと等価かどうかを確認するための、Ratio 型であると推測される他の System.Object インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


2 つの ratio を比較し、両者が一致するかを示すブール値を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 使用する最初の Ratio。 |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 使用する2番目の Ratio。 |
|

**Returns:**
boolean - 両方の Ratio が等しい場合は true、そうでなければ false。

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


2 つの ratio を比較し、両者が一致しないかを示すブール値を返します
一致。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 使用する最初の Ratio。 |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 使用する2番目の Ratio。 |
|

**Returns:**
boolean - 両方の Ratio が等しくない場合は true、そうでなければ false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。このハッシュコードはインスタンスの存続期間中に変更できません
存続期間


**Returns:**
int - 符号付き 4 バイト整数で、このインスタンスでは不変です

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


指定された分子とから Ratio インスタンスを作成し、返します
分母


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 分子 | int | Ratio の分子。正の整数である必要があります。 |
|
|  | 分母 | int | Ratio の分母。正の整数である必要があります。 |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

