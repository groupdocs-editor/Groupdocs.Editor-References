---
title: "QuoteType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "引用文字を表します - シングルクオート と ダブルクオート"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

シングルクオート (') とダブルクオート (\") の引用文字を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | シングルクオート (U+0027 APOSTROPHE 文字) |
|
|  | [DoubleQuote](#DoubleQuote) | ダブルクオート (U+0022 QUOTATION MARK 文字) |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCode()](#getCode--) | 現在の文字のコードポイント (U+0027 または U+0022) |
|
|  | [getCharacter()](#getCharacter--) | 引用する文字 |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | HTML エンコードされた文字 |
|
|  | [toString()](#toString--) | 現在の値に応じて \"SingleQuote\" または \"DoubleQuote\" 文字列を返します |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | このインスタンスの引用タイプが指定されたものと等しいかどうかを示します |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスの引用タイプが指定された非キャスト値と等しいかどうかを示します |
|
|  | [hashCode()](#hashCode--) | この文字のハッシュコードを返します |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | \"QuoteType\" 値が二つ等しいかどうかをチェックします |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | \"QuoteType\" 値が二つ等しくないかどうかをチェックします |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 指定された [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) インスタンスを char にキャストします |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | 特定の char を対応する [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) にキャストします。キャストが無効な場合は例外がスローされます |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


シングルクオート (U+0027 APOSTROPHE 文字)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


ダブルクオート (U+0022 QUOTATION MARK 文字)


### getCode() {#getCode--}
```
public final int getCode()
```


現在の文字のコードポイント (U+0027 または U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


引用する文字


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


HTML エンコードされた文字


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


現在の値に応じて \"SingleQuote\" または \"DoubleQuote\" 文字列を返します


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


このインスタンスの引用タイプが指定されたものと等しいかどうかを示します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | チェックするための他の QuoteType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスの引用タイプが指定された非キャスト値と等しいかどうかを示します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | キャストされていないオブジェクトで、[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) 型であることが期待されます |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


この文字のハッシュコードを返します


**Returns:**
int - 符号付き整数としてのハッシュコード

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


\"QuoteType\" 値が二つ等しいかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | チェックする最初の値 |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は true、そうでない場合は false

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


\"QuoteType\" 値が二つ等しくないかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | チェックする最初の値 |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | チェックする2番目の値 |
|

**Returns:**
ブール - 等しい場合は false、そうでない場合は true

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


指定された [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) インスタンスを char にキャストします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | キャスト対象の Quote type インスタンス |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


特定の char を対応する [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) にキャストします。キャストが無効な場合は例外がスローされます


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 文字 | char | シングルクオート (U+0027 APOSTROPHE) またはダブルクオート (U+0022 QUOTATION MARK) 文字です。他の文字が指定された場合は例外がスローされます。 |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
