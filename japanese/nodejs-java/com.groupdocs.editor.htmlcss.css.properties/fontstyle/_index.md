---
title: "FontStyle"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "フォントファミリーから通常、イタリック、またはオブリークのフェイスでフォントをどのようにスタイル設定するかを定義します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

フォントファミリーから、通常、イタリック、または斜体のいずれかのスタイルでフォントを設定する方法を定義します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Normal](#Normal) | フォントファミリー内で通常として分類されるフォントを選択します。 |
|
|  | [Italic](#Italic) | イタリックとして分類されるフォントを選択します。 |
|
|  | [Oblique](#Oblique) | オブリークとして分類されるフォントを選択します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isInitial()](#isInitial--) | この font-style に初期値（Normal）があるかどうかを示します。 |
|
|  | [getValue()](#getValue--) | このフォントスタイルの値を文字列として返します。 |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | この font-style インスタンスが指定されたものと等しいかどうかを判定します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | この font-style インスタンスが指定されたキャストされていないものと等しいかどうかを判定します。 |
|
|  | [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 二つの "FontStyle" 値が等しいかどうかをチェックします。 |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 二つの "FontStyle" 値が等しくないかどうかをチェックします。 |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | 指定されたキーワードを 'font-style' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返します。 |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


フォントファミリー内で通常として分類されるフォントを選択します。初期値です。


### Italic {#Italic}
```
public static final FontStyle Italic
```


イタリックとして分類されるフォントを選択します。イタリック版が利用できない場合は、代わりにオブリークとして分類されたものが使用されます。どちらも利用できない場合、スタイルは人工的にシミュレートされます。


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


オブリークとして分類されるフォントを選択します。オブリーク版が利用できない場合は、代わりにイタリックとして分類されたものが使用されます。どちらも利用できない場合、スタイルは人工的にシミュレートされます。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


この font-style に初期値（Normal）があるかどうかを示します。


**Returns:**
ブール
### getValue() {#getValue--}
```
public final String getValue()
```


このフォントスタイルの値を文字列として返します。


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


この font-style インスタンスが指定されたものと等しいかどうかを判定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 他の font-style インスタンス |
|

**Returns:**
ブール - 等しい場合は true、そうでない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この font-style インスタンスが指定されたキャストされていないものと等しいかどうかを判定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 他のキャストされていない font-style インスタンス、null の可能性があります |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


二つの "FontStyle" 値が等しいかどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | チェックする最初の値 |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は true、そうでない場合は false

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


二つの "FontStyle" 値が等しくないかどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | チェックする最初の値 |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は false、そうでない場合は true

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


指定されたキーワードを 'font-style' の適切なキーワード値として認識し、成功した場合はそれを返し、失敗した場合は NULL を返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | キーワード | java.lang.String | 解析するキーワード |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 結果、解析が成功した場合、そうでなければ #Normal.Normal |
|

**Returns:**
ブール - 解析が成功した場合は true、そうでない場合は false

