---
title: "XmlFormatOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "XML 文書が HTML として表現される際の書式設定を調整できるオプションを含みます"
type: docs
weight: 52
url: /ja/nodejs-java/com.groupdocs.editor.options/xmlformatoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlFormatOptions implements IEditOptions
```

XMLドキュメントがHTMLとして表現される際の書式設定を調整できるオプションを含みます。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEachAttributeFromNewline()](#getEachAttributeFromNewline--) | 有効にすると、すべての XML 要素内の属性と値のペアがそれぞれ新しい行に配置されます。 |
|
|  | [setEachAttributeFromNewline(boolean value)](#setEachAttributeFromNewline-boolean-) | 有効にすると、すべての XML 要素内の属性と値のペアがそれぞれ新しい行に配置されます。 |
|
|  | [getLeafTextNodesOnNewline()](#getLeafTextNodesOnNewline--) | 有効にすると、子を持たない XML 要素内のテキストノード（テキストコンテンツ）は、左インデントを大きくして新しい行にレンダリングされます。 |
|
|  | [setLeafTextNodesOnNewline(boolean value)](#setLeafTextNodesOnNewline-boolean-) | 有効にすると、子を持たない XML 要素内のテキストノード（テキストコンテンツ）は、左インデントを大きくして新しい行にレンダリングされます。 |
|
|  | [getLeftIndent()](#getLeftIndent--) | 各新しい行の左インデントのオフセットを指定できます。 |
|
|  | [setLeftIndent(Length value)](#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 各新しい行の左インデントのオフセットを指定できます。 |
|
|  | [isDefault()](#isDefault--) | この XML 書式設定オプションのインスタンスがデフォルト値を持つかどうかを示します。 |
|
### getEachAttributeFromNewline() {#getEachAttributeFromNewline--}
```
public final boolean getEachAttributeFromNewline()
```


有効にすると、すべての XML 要素内の属性と値のペアがそれぞれ新しい行に配置されます。
デフォルトでは false（無効）\\u2014 すべての属性と値のペアは単一行に配置されます。


**Returns:**
ブール
### setEachAttributeFromNewline(boolean value) {#setEachAttributeFromNewline-boolean-}
```
public final void setEachAttributeFromNewline(boolean value)
```


有効にすると、すべての XML 要素内の属性と値のペアがそれぞれ新しい行に配置されます。
デフォルトでは false（無効）\\u2014 すべての属性と値のペアは単一行に配置されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getLeafTextNodesOnNewline() {#getLeafTextNodesOnNewline--}
```
public final boolean getLeafTextNodesOnNewline()
```


有効にすると、子を持たない XML 要素内のテキストノード（テキストコンテンツ）は、左インデントを大きくして新しい行にレンダリングされます。
デフォルトでは false（無効）\\u2014 子を持たないテキストノードは親と同じ行に配置され、インデントは追加されません。


**Returns:**
ブール
### setLeafTextNodesOnNewline(boolean value) {#setLeafTextNodesOnNewline-boolean-}
```
public final void setLeafTextNodesOnNewline(boolean value)
```


有効にすると、子を持たない XML 要素内のテキストノード（テキストコンテンツ）は、左インデントを大きくして新しい行にレンダリングされます。
デフォルトでは false（無効）\\u2014 子を持たないテキストノードは親と同じ行に配置され、インデントは追加されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getLeftIndent() {#getLeftIndent--}
```
public final Length getLeftIndent()
```


各新しい行の左インデントのオフセットを指定できます。単位なしの非ゼロ値は使用できません。デフォルトは 10pt です。


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### setLeftIndent(Length value) {#setLeftIndent-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final void setLeftIndent(Length value)
```


各新しい行の左インデントのオフセットを指定できます。単位なしの非ゼロ値は使用できません。デフォルトは 10pt です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |  |

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


この XML 書式設定オプションのインスタンスがデフォルト値を持つかどうかを示します。


**Returns:**
ブール
