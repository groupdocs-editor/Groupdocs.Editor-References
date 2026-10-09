---
title: "Dimensions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "任意の単位で、1 つのラスタ矩形画像の幅と高さという線形寸法を表します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

1 つのラスタ矩形の（幅と高さ）の線形寸法を表します
任意の単位の画像です。変更不可能な構造体です。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | 指定された幅と高さから新しいインスタンスを作成します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 画像の幅を返します |
|
|  | [getHeight()](#getHeight--) | 画像の高さを返します |
|
|  | [isSquare()](#isSquare--) | 指定された 'Dimensions' が正方形かどうかを判定します。すなわち、 |
|
|  | [getArea()](#getArea--) | 面積（幅 × 高さ）を返します |
|
|  | [isEmpty()](#isEmpty--) | この "Dimensions" インスタンスが空でデフォルトかどうかを判定します。すなわち、 |
|
|  | [getAspectRatio()](#getAspectRatio--) | この寸法のアスペクト比（幅/高さ） |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | 比例的に新しい "Dimensions" インスタンスを作成し、返します |
指定された幅に基づいて現在からサイズ変更します
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | 比例的に新しい "Dimensions" インスタンスを作成し、返します |
指定された高さに基づいて現在からサイズ変更します
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | このインスタンスが指定された "Dimensions" と等しいかどうかを判定します |
インスタンス
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、 |
おそらく別の "Dimensions" インスタンスです
|
|  | [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。このハッシュコードはインスタンスの存続期間中に変更できません |
存続期間
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 2 つの "Dimensions" 値が等しいかどうかをチェックします。すなわち、 |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 2 つの "Dimensions" 値が等しくないかどうかをチェックします。すなわち、 |
|
|  | [toString()](#toString--) | この "Dimensions" の文字列表現を返します |
|
|  | [deepClone()](#deepClone--) | このインスタンスの完全なコピーを返します |
|
|  | [getEmpty()](#getEmpty--) | 空の Dimensions インスタンスを返します |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


指定された幅と高さから新しいインスタンスを作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 幅 | int | 画像の幅 |
|
|  | 高さ | int | 画像の高さ |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


画像の幅を返します


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


画像の高さを返します


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


指定された 'Dimensions' が正方形かどうかを判断します。つまり、
幅が高さと等しいかどうか


**Returns:**
ブール
### getArea() {#getArea--}
```
public final long getArea()
```


面積（幅 × 高さ）を返します


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


この "Dimensions" インスタンスが空でデフォルトかどうかを判定します。すなわち、
正しい幅と高さが保存されません


**Returns:**
ブール
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


この寸法のアスペクト比（幅/高さ）


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


比例的に新しい "Dimensions" インスタンスを作成し、返します
指定された幅に基づいて現在からサイズ変更します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | targetWidth | int | 結果の Dimension に含まれる新しいターゲット幅 |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


比例的に新しい "Dimensions" インスタンスを作成し、返します
指定された高さに基づいて現在からサイズ変更します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | targetHeight | int | 結果の Dimension に含まれる新しいターゲット高さ |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


このインスタンスが指定された "Dimensions" と等しいかどうかを判定します
インスタンス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 等価性をチェックするための別の "Dimensions" インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、
おそらく別の "Dimensions" インスタンスです


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | このオブジェクトと等価性をチェックすべき、恐らく "Dimensions" 型の別のオブジェクト |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。このハッシュコードはインスタンスの存続期間中に変更できません
存続期間


**Returns:**
int - このインスタンスに対して不変な、符号付き 4 バイト整数としてのハッシュコード

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


二つの "Dimensions" 値が等しいかどうかをチェックします。つまり、等しい
幅と高さ、または両方が空であるかどうか


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | チェックする最初のインスタンス |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | チェックする二番目のインスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


二つの "Dimensions" 値が等しくないかどうかをチェックします。つまり、
対応する幅および/または高さが異なるかどうか


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | チェックする最初のインスタンス |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | チェックする二番目のインスタンス |
|

**Returns:**
boolean - 不等の場合は True、等しい場合は false

### toString() {#toString--}
```
public String toString()
```


この "Dimensions" の文字列表現を返します

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - 幅と高さを W:(width)×H:(height) 形式で含む String インスタンス

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


このインスタンスの完全なコピーを返します


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


空の Dimensions インスタンスを返します


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
