---
title: "FontSize"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "フォントサイズを特別な単位または長さの値として表し、歴史的に大文字 M の幅でフォントのサイズを指定します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

フォントサイズを特別な単位または長さの値として表し、フォントのサイズ（歴史的には大文字 \"M\" の幅）を指定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Medium](#Medium) | 中サイズ。 |
|
|  | [XxSmall](#XxSmall) | 非常に小さい絶対サイズ |
|
|  | [XSmall](#XSmall) | やや小さい絶対サイズ |
|
|  | [Small](#Small) | 通常の小さい絶対サイズ |
|
|  | [Large](#Large) | 通常の大きい絶対サイズ |
|
|  | [XLarge](#XLarge) | やや大きい絶対サイズ |
|
|  | [XxLarge](#XxLarge) | 非常に大きい絶対サイズ |
|
|  | [Larger](#Larger) | より大きい相対サイズ - フォントは親要素の font-size に対して相対的に大きくなります。上記の絶対サイズキーワードを分ける比率でおおよそ決まります。 |
|
|  | [Smaller](#Smaller) | より小さい相対サイズ - フォントは親要素の font-size に対して相対的に小さくなります。上記の絶対サイズキーワードを分ける比率でおおよそ決まります。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isInitial()](#isInitial--) | このフォントサイズが初期値（Medium）を持つかどうかを示します |
|
|  | [getValue()](#getValue--) | このフォントサイズの値を文字列として返します |
|
|  | [isLengthDefined()](#isLengthDefined--) | このフォントサイズが [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) 値で定義されているかどうかを示します |
|
|  | [getLength()](#getLength--) | このフォントサイズがそれで定義されている場合は長さの値を返し、そうでない場合は例外をスローします |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | このフォントサイズがユーザーのデフォルトフォントサイズ（medium）に基づく絶対サイズのキーワードで定義されているかどうかを示します |
|
|  | [isRelativeSize()](#isRelativeSize--) | このフォントサイズが相対サイズのキーワードで定義されているかどうかを示します。 |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | このフォントサイズインスタンスが指定されたものと等しいかどうかを判定します |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このフォントサイズインスタンスが指定されたキャストされていないものと等しいかどうかを判定します |
|
|  | [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 二つの "FontSize" 値が等しいかどうかをチェックします |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 二つの "FontSize" 値が等しくないかどうかをチェックします |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 指定された長さからフォントサイズを作成します |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | 指定されたキーワードを 'font-size' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返します。 |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


中サイズ。初期値です。


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


非常に小さい絶対サイズ


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


やや小さい絶対サイズ


### Small {#Small}
```
public static final FontSize Small
```


通常の小さい絶対サイズ


### Large {#Large}
```
public static final FontSize Large
```


通常の大きい絶対サイズ


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


やや大きい絶対サイズ


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


非常に大きい絶対サイズ


### Larger {#Larger}
```
public static final FontSize Larger
```


より大きい相対サイズ - フォントは親要素の font-size に対して相対的に大きくなります。上記の絶対サイズキーワードを分ける比率でおおよそ決まります。


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


より小さい相対サイズ - フォントは親要素の font-size に対して相対的に小さくなります。上記の絶対サイズキーワードを分ける比率でおおよそ決まります。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


このフォントサイズが初期値（Medium）を持つかどうかを示します


**Returns:**
ブール
### getValue() {#getValue--}
```
public final String getValue()
```


このフォントサイズの値を文字列として返します


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


このフォントサイズが [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) 値で定義されているかどうかを示します


**Returns:**
ブール
### getLength() {#getLength--}
```
public final Length getLength()
```


このフォントサイズがそれで定義されている場合は長さの値を返し、そうでない場合は例外をスローします


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


このフォントサイズがユーザーのデフォルトフォントサイズ（medium）に基づく絶対サイズのキーワードで定義されているかどうかを示します


**Returns:**
ブール
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


このフォントサイズが相対サイズのキーワードで定義されているかどうかを示します。フォントは親要素のフォントサイズに対して相対的に大きくまたは小さくなり、絶対サイズのキーワードを区別するために使用される比率で概算されます。


**Returns:**
ブール
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


このフォントサイズインスタンスが指定されたものと等しいかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | その他のフォントサイズインスタンス |
|

**Returns:**
ブール - 等しい場合は true、そうでない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このフォントサイズインスタンスが指定されたキャストされていないものと等しいかどうかを判定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | その他のキャストされていないフォントサイズインスタンス（null の可能性あり） |
|

**Returns:**
ブール - 等しい場合は true、等しくない、null、または他の型の場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。


**Returns:**
int - 符号付き整数としてのハッシュコード

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


二つの "FontSize" 値が等しいかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | チェックする最初の値 |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は true、そうでない場合は false

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


二つの "FontSize" 値が等しくないかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | チェックする最初の値 |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は false、そうでない場合は true

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


指定された長さからフォントサイズを作成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 単位なしまたは負の値にできない長さの値です |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


指定されたキーワードを 'font-size' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | キーワード | java.lang.String | 解析するキーワード |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 解析が成功した場合の結果、またはそれ以外の場合は #Medium.Medium です |
|

**Returns:**
ブール - 解析が成功した場合は true、そうでない場合は false

