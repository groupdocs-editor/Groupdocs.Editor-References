---
title: "TextType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポート可能なテキストリソースタイプを表します"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

サポート可能なテキストリソースタイプを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextType()](#TextType--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 未定義、未知、またはサポートされていないテキストを示す特別な値 |
resource
|
|  | [getCss()](#getCss--) | テキストリソースの CSS タイプ |
|
|  | [getXml()](#getXml--) | テキストリソースの XML タイプ |
|
|  | [getFormalName()](#getFormalName--) | このテキストリソースタイプの正式名称を返します |
|
|  | [getFileExtension()](#getFileExtension--) | 特定のテキストのファイル拡張子（先頭のドット文字なし） |
resource
|
|  | [getMimeCode()](#getMimeCode--) | 特定のテキストリソースタイプのMIMEコード |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | このインスタンスが指定された \"TextType\" と等しいかどうかを判定します |
インスタンス
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、 |
それはおそらく別の \"TextType\" インスタンスです
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 2つの特定の \"TextType\" インスタンスが等しいかどうかを定義します |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | 2つの特定の \"TextType\" インスタンスが等しくないかどうかを定義します |
|
|  | [hashCode()](#hashCode--) | この特定の値に対する一定の数値であるハッシュコードを返します |
型
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | 指定されたファイル名（拡張子付き）または純粋な拡張子から抽出されたファイル名拡張子に相当する TextType の値を返します |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


未定義、未知、またはサポートされていないテキストを示す特別な値
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


テキストリソースの CSS タイプ


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


テキストリソースの XML タイプ


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


このテキストリソースタイプの正式名称を返します


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


特定のテキストのファイル拡張子（先頭のドット文字なし）
resource


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


特定のテキストリソースタイプのMIMEコード


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


このインスタンスが指定された \"TextType\" と等しいかどうかを判定します
インスタンス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 等価比較の際にこのインスタンスと比較されるべき他の TextType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false を返します

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、
それはおそらく別の \"TextType\" インスタンスです


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | object にボックス化された他の TextType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false を返します

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


2つの特定の \"TextType\" インスタンスが等しいかどうかを定義します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 最初の TextType インスタンス |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 2番目の TextType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false を返します

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


2つの特定の \"TextType\" インスタンスが等しくないかどうかを定義します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 最初の TextType インスタンス |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | 2番目の TextType インスタンス |
|

**Returns:**
boolean - 等しくない場合は true、等しい場合は false を返します

### hashCode() {#hashCode--}
```
public int hashCode()
```


この特定の値に対する一定の数値であるハッシュコードを返します
型


**Returns:**
int - 符号付き4バイト整数。インスタンスがデフォルト値の場合は 0 を返します。

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


指定されたファイル名（拡張子付き）または純粋な拡張子から抽出されたファイル名拡張子に相当する TextType の値を返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ファイル名 | java.lang.String | 拡張子付きのファイル名。相対パスまたは絶対パス、あるいは純粋な拡張子自体でも構いません |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

