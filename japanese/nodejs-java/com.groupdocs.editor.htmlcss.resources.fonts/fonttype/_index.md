---
title: "FontType"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポート可能なフォントタイプを 1 つ表します。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class FontType implements IResourceType
```

サポート可能なフォントタイプを 1 つ表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontType()](#FontType--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | 未定義、未知、またはサポートされていないフォントを示す特別な値 |
resource
|
|  | [getWoff()](#getWoff--) | WOFF (Web Open Font Format) フォントタイプを表します |
|
|  | [getWoff2()](#getWoff2--) | WOFF2 (Web Open Font Format version 2) フォントタイプを表します |
|
|  | [getTtf()](#getTtf--) | TTF (TrueType Font) フォントタイプを表します |
|
|  | [getOtf()](#getOtf--) | OTF (OpenType Font) フォントタイプを表します |
|
|  | [getTtc()](#getTtc--) | TrueType Collection (TTC) フォントを表します |
|
|  | [getEot()](#getEot--) | EOT (Embedded OpenType) フォントタイプを表します |
|
|  | [getCssName()](#getCssName--) | このフォントタイプの CSS 互換名を返します。 |
|
|  | [getFormalName()](#getFormalName--) | このフォントタイプの正式名称を返します |
|
|  | [getFileExtension()](#getFileExtension--) | このフォントタイプのファイル名拡張子（ドット文字なし） |
|
|  | [getFontFormat()](#getFontFormat--) | @font-face 形式のフォントフォーマット |
|
|  | [getMimeCode()](#getMimeCode--) | 特定のフォントタイプの MIME コード |
|
|  | [parseFromCssName(String name)](#parseFromCssName-java.lang.String-) | 指定された CSS 互換のものに相当する FontType 値を返します |
フォントタイプの名前
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | ファイル名拡張子に相当する FontType 値を返します |
は指定されたファイル名から抽出されます
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | 指定された MIME コードに相当する FontType 値を返します |
|
|  | [getFirstDefined(FontType[] fonts)](#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-) | 指定されたセットから最初のフォントタイプを返しますが、"Undefined" ではありません |
値、またはすべての項目が...の場合は "Undefined" フォントタイプが返されます (
"Undefined")
|
|  | [equals(FontType other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | このインスタンスが指定された "FontType" と等しいかどうかを判定します |
インスタンス
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、 |
おそらく別の "FontType" インスタンスです
|
|  | [op_Equality(FontType first, FontType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 2つの "FontType" 値が等しいかどうかをチェックします |
|
|  | [op_Inequality(FontType first, FontType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-) | 2つの "FontType" 値が等しくないかどうかをチェックします |
|
|  | [hashCode()](#hashCode--) | この特定の値に対する一定の数値であるハッシュコードを返します |
型
|
### FontType() {#FontType--}
```
public FontType()
```


### getUndefined() {#getUndefined--}
```
public static FontType getUndefined()
```


未定義、未知、またはサポートされていないフォントを示す特別な値
resource


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff() {#getWoff--}
```
public static FontType getWoff()
```


WOFF (Web Open Font Format) フォントタイプを表します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getWoff2() {#getWoff2--}
```
public static FontType getWoff2()
```


WOFF2 (Web Open Font Format version 2) フォントタイプを表します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtf() {#getTtf--}
```
public static FontType getTtf()
```


TTF (TrueType Font) フォントタイプを表します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getOtf() {#getOtf--}
```
public static FontType getOtf()
```


OTF (OpenType Font) フォントタイプを表します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getTtc() {#getTtc--}
```
public static FontType getTtc()
```


TrueType Collection (TTC) フォントを表します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getEot() {#getEot--}
```
public static FontType getEot()
```


EOT (Embedded OpenType) フォントタイプを表します


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
### getCssName() {#getCssName--}
```
public final String getCssName()
```


このフォントタイプの CSS 互換名を返します。


**Returns:**
java.lang.String -
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


このフォントタイプの正式名称を返します


**Returns:**
java.lang.String -
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


このフォントタイプのファイル名拡張子（ドット文字なし）


**Returns:**
java.lang.String -
### getFontFormat() {#getFontFormat--}
```
public final String getFontFormat()
```


@font-face 形式のフォントフォーマット


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


特定のフォントタイプの MIME コード


**Returns:**
java.lang.String -
### parseFromCssName(String name) {#parseFromCssName-java.lang.String-}
```
public static FontType parseFromCssName(String name)
```


指定された CSS 互換のものに相当する FontType 値を返します
フォントタイプの名前


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォントタイプの CSS 互換名 |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static FontType parseFromFilenameWithExtension(String filename)
```


ファイル名拡張子に相当する FontType 値を返します
は指定されたファイル名から抽出されます


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | ファイル名 | java.lang.String | 拡張子付きのファイル名、フルネームでも構いません |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static FontType parseFromMime(String mimeCode)
```


指定された MIME コードに相当する FontType 値を返します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | mimeCode | java.lang.String | MIME コード |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - Valid FontType value on success or FontType.Undefined on failure

### getFirstDefined(FontType[] fonts) {#getFirstDefined-com.groupdocs.editor.htmlcss.resources.fonts.FontType...-}
```
public static FontType getFirstDefined(FontType[] fonts)
```


指定されたセットから最初のフォントタイプを返しますが、"Undefined" ではありません
値、またはすべての項目が...の場合は "Undefined" フォントタイプが返されます (
"Undefined")


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | fonts | [FontType\[\]](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | 1つ以上の FontType 値、NULL または空のコレクションは許可されません |
|

**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - First FontType value from specified collection, that is not Undefined, or Undefined, if all items are Undefined

### equals(FontType other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public final boolean equals(FontType other)
```


このインスタンスが指定された "FontType" と等しいかどうかを判定します
インスタンス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | このインスタンスと比較する他の FontType インスタンス |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判定します、
おそらく別の "FontType" インスタンスです


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | おそらく FontType 構造体の他のインスタンスで、System.Object にボックス化されたもの |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Equality(FontType first, FontType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Equality(FontType first, FontType second)
```


2つの "FontType" 値が等しいかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | チェックする最初の FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | チェックする2番目の FontType |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### op_Inequality(FontType first, FontType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.fonts.FontType-com.groupdocs.editor.htmlcss.resources.fonts.FontType-}
```
public static boolean op_Inequality(FontType first, FontType second)
```


2つの "FontType" 値が等しくないかどうかをチェックします


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | first | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | チェックする最初の FontType |
|
|  | second | [FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) | チェックする2番目の FontType |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### hashCode() {#hashCode--}
```
public int hashCode()
```


この特定の値に対する一定の数値であるハッシュコードを返します
型


**Returns:**
int - 4 バイト符号付き整数、未定義値の場合は 0

