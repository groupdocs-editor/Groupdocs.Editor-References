---
title: "TextDecorationLineType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "テキスト装飾ラインのタイプ（underline、underscore、overline、line-through（取り消し線））を表します。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

テキスト装飾線のタイプを表します：下線（アンダースコア）、上線、取り消し線（ストライクスルー）。

<br />

*** ** * ** ***

不変構造体。https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line と似ています。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [None](#None) | テキスト装飾を生成しません。 |
|
|  | [Underline](#Underline) | 各テキスト行に下線が引かれます。 |
|
|  | [Overline](#Overline) | 各テキスト行の上に線があります。 |
|
|  | [LineThrough](#LineThrough) | 各テキスト行の中央に線が引かれます。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isInitial()](#isInitial--) | このインスタンスに初期値があるかどうかを示します — None |
|
|  | [isUnderline()](#isUnderline--) | 下線（アンダースコア）が有効かどうかを示します |
|
|  | [isOverline()](#isOverline--) | 上線が有効かどうかを示します |
|
|  | [isLineThrough()](#isLineThrough--) | 取り消し線（ストライクスルー）が有効かどうかを示します |
|
|  | [getValue()](#getValue--) | このインスタンスのすべてのフラグの値をテキストとして返します |
|
|  | [toString()](#toString--) | このインスタンスのすべてのフラグの値をテキストとして返します |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | この [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスが指定されたものと等しいかどうかを示します |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | この [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスがキャストされていない指定されたものと等しいかどうかを示します |
|
|  | [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 二つの "TextDecorationLineType" 値が等しいかどうかを確認します |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 二つの "TextDecorationLineType" 値が等しくないかどうかを確認します |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | 指定されたパラメーターで定義されたフラグを持つ [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスを作成し、返します |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | 指定された文字列を解析し、有効な [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスを返そうとします |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 指定された二つのラインタイプを結合（マージ）し、フラグが統合（和集合）された新しい結果のラインタイプを生成します |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 二番目に指定されたラインタイプを最初に指定されたラインタイプから減算し、第二オペランドに存在しない最初のオペランドのフラグのみが残る新しい結果のラインタイプを生成します（差集合） |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 最初と二番目のラインタイプの交差を返します。両方のオペランドで同時に有効なフラグのみが有効になります。 |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | 特定のバイト（8ビットオクテット）を対応する [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) にキャストし、キャストが無効な場合は例外をスローします |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


テキスト装飾を生成しません。初期値です。


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


各テキスト行に下線が引かれます。


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


各テキスト行の上に線があります。


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


各テキスト行の中央に線が引かれます。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


このインスタンスに初期値があるかどうかを示します — None


**Returns:**
ブール
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


下線（アンダースコア）が有効かどうかを示します


**Returns:**
ブール
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


上線が有効かどうかを示します


**Returns:**
ブール
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


取り消し線（ストライクスルー）が有効かどうかを示します


**Returns:**
ブール
### getValue() {#getValue--}
```
public final String getValue()
```


このインスタンスのすべてのフラグの値をテキストとして返します


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


このインスタンスのすべてのフラグの値をテキストとして返します


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


この [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスが指定されたものと等しいかどうかを示します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 他の [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンス |
|

**Returns:**
boolean - 等しい場合は true、そうでない場合は false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


この [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスがキャストされていない指定されたものと等しいかどうかを示します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | java.lang.Object | 他の [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンス、object にキャストされたもの |
|

**Returns:**
boolean - 等しい場合は true、そうでない場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します


**Returns:**
int - 符号付き整数のハッシュコード

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


二つの "TextDecorationLineType" 値が等しいかどうかを確認します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | チェックする最初のオペランド |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | チェックする2番目のオペランド |
|

**Returns:**
boolean - 等しい場合は true、そうでない場合は false

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


二つの "TextDecorationLineType" 値が等しくないかどうかを確認します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | チェックする最初のオペランド |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | チェックする2番目のオペランド |
|

**Returns:**
boolean -  不等の場合は true、そうでない場合は false

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


指定されたパラメーターで定義されたフラグを持つ [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスを作成し、返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | isUnderline | ブール | 下線フラグが有効かどうかを決定します |
|
|  | isOverline | ブール | 上線フラグが有効かどうかを決定します |
|
|  | isLineThrough | ブール | 取り消し線フラグが有効かどうかを決定します |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


指定された文字列を解析し、有効な [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) インスタンスを返そうとします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | input | java.lang.String | 入力文字列 |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 結果。解析が無効な場合、#None.None の値になります |
|

**Returns:**
boolean -  解析が成功した場合は true、失敗した場合は false

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


指定された二つのラインタイプを結合（マージ）し、フラグが統合（和集合）された新しい結果のラインタイプを生成します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 最初のラインタイプオペランド |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 2番目のラインタイプオペランド |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


二番目に指定されたラインタイプを最初に指定されたラインタイプから減算し、第二オペランドに存在しない最初のオペランドのフラグのみが残る新しい結果のラインタイプを生成します（差集合）


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 最初のラインタイプオペランド |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 2番目のラインタイプオペランド |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


最初と2番目のラインタイプの交差を返します。両方のオペランドで同時に有効になっているフラグのみが有効になります。すべての演算子の中で最も優先度が高く（結合や差分よりも高い）


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 最初のラインタイプオペランド |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 2番目のラインタイプオペランド |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


特定のバイト（8ビットオクテット）を対応する [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) にキャストし、キャストが無効な場合は例外をスローします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | オクテット | バイト | 5ビットがゼロで、残りの3ビットがフラグを示す8ビットオクテット（ビットフィールド） |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
