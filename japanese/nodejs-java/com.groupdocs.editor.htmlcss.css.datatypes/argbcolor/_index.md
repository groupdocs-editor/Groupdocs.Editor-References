---
title: "ArgbColor"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "コンバータとシリアライザを備えた ARGB 形式の単一カラー値を表します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

コンバータとシリアライザを備えた ARGB 形式の単一カラー値を表します。

<br />

*** ** * ** ***

この型は CSS 操作に役立つように設計されています（ただしこれに限定されません）。詳細はこちら: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | 指定された赤、緑、青、アルファ チャネルから 1 つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 値を作成します |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | 指定された赤、緑、青チャネルから 1 つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 値を作成し、アルファチャネルは完全に不透明です |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | 単一の値からすべてのチャネルに適用される、完全に不透明 (A=255) な色を作成します |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | 指定された [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) から 1 つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 値を作成します |
|
|  | [getValue()](#getValue--) | 色の Int32 値を取得します |
|
|  | [getA()](#getA--) | 色のアルファ部分を取得します |
|
|  | [getAlpha()](#getAlpha--) | 色のアルファ部分をパーセンテージ (0..1) で取得します |
|
|  | [getR()](#getR--) | 色の赤色部分を取得します |
|
|  | [getG()](#getG--) | 色の緑色部分を取得します |
|
|  | [getB()](#getB--) | 色の青色部分を取得します |
|
|  | [isEmpty()](#isEmpty--) | 初期化されていない色 - 4 つのチャネルすべてが 0 に設定されています |
|
|  | [isDefault()](#isDefault--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスがデフォルト（透明）かどうかを示します - 4 つのチャネルすべてが 0 に設定されています |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスが完全に透明かどうかを示します - アルファチャネルが最小値 (0) であるため、他の R、G、B チャネルは可視効果がありません |
|
|  | [isTranslucent()](#isTranslucent--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスが半透明かどうかを示します（完全に透明ではなく、完全に不透明でもない） |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスが完全に不透明かどうかを示します（透明性がなく、アルファチャネルが最大値です） |
|
|  | [toSystemColor()](#toSystemColor--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスの値を [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) インスタンスに変換し、返します |
|
|  | [toRGBA()](#toRGBA--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスを 'rgba' CSS 関数表記にシリアライズします |
|
|  | [toRGB()](#toRGB--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスを 'rgb' CSS 関数表記にシリアライズします |
|
|  | [serializeDefault()](#serializeDefault--) | この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスを、透明度に応じて最も適切な CSS 関数表記にシリアライズします |
|
|  | [toString()](#toString--) | #serializeDefault.serializeDefault と同じです |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 2 つの色を比較し、一致するかどうかを示すブール値を返します |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 2 つの色を比較し、一致しないかどうかを示すブール値を返します |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 2つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) カラーが等しいかチェックします |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | 2つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) カラーが等しいかチェックします |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 別のオブジェクトがこの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスと等しいかテストします。 |
|
|  | [hashCode()](#hashCode--) | 現在のカラーを定義するハッシュコードを返します。 |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


指定された赤、緑、青、アルファ チャネルから 1 つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 値を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 赤 | int | 赤チャンネルの値 |
|
|  | 緑 | int | 緑チャンネルの値 |
|
|  | 青 | int | 青チャンネルの値 |
|
|  | アルファ | int | アルファチャンネルの値 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


指定された赤、緑、青チャネルから 1 つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 値を作成し、アルファチャネルは完全に不透明です


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 赤 | int | 赤チャンネルの値 |
|
|  | 緑 | int | 緑チャンネルの値 |
|
|  | 青 | int | 青チャンネルの値 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


単一の値からすべてのチャネルに適用される、完全に不透明 (A=255) な色を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 値 | バイト | バイト値で、赤、緑、青チャンネルすべてに共通です |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


指定された [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) から 1 つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 値を作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 色 | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


色の Int32 値を取得します


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


色のアルファ部分を取得します


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


色のアルファ部分をパーセンテージ (0..1) で取得します


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


色の赤色部分を取得します


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


色の緑色部分を取得します


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


色の青色部分を取得します


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


初期化されていない色 - 4つのチャンネルすべてが0に設定されています。DefaultおよびTransparentと同じです。


**Returns:**
ブール
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスがデフォルト（透明）かどうかを示します - 4 つのチャネルすべてが 0 に設定されています


**Returns:**
ブール
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスが完全に透明かどうかを示します - アルファチャネルが最小値 (0) であるため、他の R、G、B チャネルは可視効果がありません


**Returns:**
ブール
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスが半透明かどうかを示します（完全に透明ではなく、完全に不透明でもない）


**Returns:**
ブール
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスが完全に不透明かどうかを示します（透明性がなく、アルファチャネルが最大値です）


**Returns:**
ブール
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスの値を [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) インスタンスに変換し、返します


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスを 'rgba' CSS 関数表記にシリアライズします


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' 形式の文字列

### toRGB() {#toRGB--}
```
public final String toRGB()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスを 'rgb' CSS 関数表記にシリアライズします


**Returns:**
java.lang.String - 'rgb(r, g, b)' 形式の文字列

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


この [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスを、透明度に応じて最も適切な CSS 関数表記にシリアライズします


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' または 'rgb(r, g, b)' 形式の文字列

### toString() {#toString--}
```
public String toString()
```


#serializeDefault.serializeDefault と同じです


**Returns:**
java.lang.String - #serializeDefault.serializeDefault と同じ戻り値

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


2 つの色を比較し、一致するかどうかを示すブール値を返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 使用する最初の色。 |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 使用する2番目の色。 |
|

**Returns:**
boolean - 両方の色が等しい場合は true、そうでなければ false。

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


2 つの色を比較し、一致しないかどうかを示すブール値を返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 使用する最初の色。 |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 使用する2番目の色。 |
|

**Returns:**
boolean - 両方の色が等しくない場合は True、そうでなければ false。

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


2つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) カラーが等しいかチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 他の [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 色 |
|

**Returns:**
boolean - 両方の色が等しい場合は True、そうでなければ false。

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


2つの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) カラーが等しいかチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | 他の [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 色、ICssDataType にキャストされた |
|

**Returns:**
boolean - 両方の色が等しい場合は True、そうでなければ false。

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


別のオブジェクトがこの [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) インスタンスと等しいかテストします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | その他 | java.lang.Object | テストに使用するオブジェクト。 |
|

**Returns:**
boolean - 2 つのオブジェクトが等しい場合は True、そうでなければ false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


現在のカラーを定義するハッシュコードを返します。


**Returns:**
int - ハッシュコードの整数値。

