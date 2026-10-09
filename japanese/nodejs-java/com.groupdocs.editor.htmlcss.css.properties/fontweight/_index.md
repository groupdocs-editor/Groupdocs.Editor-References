---
title: "FontWeight"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "font-weight プロパティはフォントの太さまたはボールド度を設定します。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

font-weight プロパティはフォントの太さ（またはボールド度）を設定します。利用可能な太さは現在設定されている font-family に依存します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Lighter](#Lighter) | 親要素よりも一段階軽い相対フォントウェイト |
|
|  | [Bolder](#Bolder) | 親要素よりも一段階重い相対フォントウェイト |
|
|  | [Normal](#Normal) | 標準のフォントウェイトです。 |
|
|  | [Bold](#Bold) | 太字のフォントウェイトです。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isInitial()](#isInitial--) | このフォントサイズが初期値（Medium）を持つかどうかを示します |
|
|  | [getNumber()](#getNumber--) | 1から1000までの整数値（範囲を含む）を返します。この値はフォントの太さ（boldness）を表します。ただし、現在の太さが絶対値ではなく相対値の場合は例外をスローします。 |
|
|  | [isAbsolute()](#isAbsolute--) | この font-weight インスタンスがフォントの太さ（boldness）の絶対値を整数として保持しているかどうかを示します。 |
|
|  | [isRelative()](#isRelative--) | この font-weight インスタンスがフォントの太さ（boldness）の相対値を保持しているかどうかを示します（親要素の boldness と比較）。 |
|
|  | [getValue()](#getValue--) | この font-weight の値を文字列として返します。 |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 指定された FontWeight インスタンスが等しいかどうかを判定します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | この FontWeight インスタンスが指定されたキャストされていないインスタンスと等しいかどうかを判定します。 |
|
|  | [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 二つの "FontWeight" 値が等しいかどうかをチェックします。 |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 二つの "FontWeight" 値が等しくないかどうかをチェックします。 |
|
|  | [fromNumber(int number)](#fromNumber-int-) | 指定された数値から font-weight を作成します。 |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | 指定された文字列を解析し、成功した場合は有効な FontWeight インスタンスを返します。 |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


親要素よりも一段階軽い相対フォントウェイト


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


親要素よりも一段階重い相対フォントウェイト


### Normal {#Normal}
```
public static final FontWeight Normal
```


標準のフォントウェイト。400 と同等です。


### Bold {#Bold}
```
public static final FontWeight Bold
```


太字のフォントウェイト。700 と同等です。


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


このフォントサイズが初期値（Medium）を持つかどうかを示します


**Returns:**
ブール
### getNumber() {#getNumber--}
```
public final int getNumber()
```


1から1000までの整数値（範囲を含む）を返します。この値はフォントの太さ（boldness）を表します。ただし、現在の太さが絶対値ではなく相対値の場合は例外をスローします。


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


この font-weight インスタンスがフォントの太さ（boldness）の絶対値を整数として保持しているかどうかを示します。


**Returns:**
ブール
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


この font-weight インスタンスがフォントの太さ（boldness）の相対値を保持しているかどうかを示します（親要素の boldness と比較）。


**Returns:**
ブール
### getValue() {#getValue--}
```
public final String getValue()
```


この font-weight の値を文字列として返します。


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


指定された FontWeight インスタンスが等しいかどうかを判定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 等価性をチェックするための他の FontWeight インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この FontWeight インスタンスが指定されたキャストされていないインスタンスと等しいかどうかを判定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 他のキャストされていない FontWeight インスタンス、null の可能性があります。 |
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

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


二つの "FontWeight" 値が等しいかどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | チェックする最初の値 |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は true、そうでない場合は false

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


二つの "FontWeight" 値が等しくないかどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | チェックする最初の値 |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は false、そうでない場合は true

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


指定された数値から font-weight を作成します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | number | int | 符号なし整数、[1..1000] の範囲内である必要があります。 |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


指定された文字列を解析し、成功した場合は有効な FontWeight インスタンスを返します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | input | java.lang.String | 解析する入力文字列 |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 成功時は有効な FontWeight 値、失敗時は #Normal.Normal を返します。 |
|

**Returns:**
boolean - 解析の成功 (true) または失敗 (false)

