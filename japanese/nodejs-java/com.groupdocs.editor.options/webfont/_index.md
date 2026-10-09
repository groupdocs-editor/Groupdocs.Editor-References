---
title: "WebFont"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "Web用のフォント設定を表します。"
type: docs
weight: 43
url: /ja/nodejs-java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

Web用のフォント設定を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getColor()](#getColor--) | ARGB32 形式のフォントカラー |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | ARGB32 形式のフォントカラー |
|
|  | [getWeight()](#getWeight--) | フォントの太さ（またはボールド）を設定します |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | フォントの太さ（またはボールド）を設定します |
|
|  | [getStyle()](#getStyle--) | フォントファミリーから通常、イタリック、または斜体のスタイルを適用するかどうかを設定します。 |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | フォントファミリーから通常、イタリック、または斜体のスタイルを適用するかどうかを設定します。 |
|
|  | [getLine()](#getLine--) | テキストに適用される行または行の組み合わせを設定します |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | テキストに適用される行または行の組み合わせを設定します |
|
|  | [getSize()](#getSize--) | フォントサイズを絶対単位または相対単位で設定します |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | フォントサイズを絶対単位または相対単位で設定します |
|
|  | [getName()](#getName--) | フォント名を設定します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | フォント名を設定します。 |
|
|  | [deepClone()](#deepClone--) | この [WebFont](../../com.groupdocs.editor.options/webfont) インスタンスの完全なディープコピーを作成して返します |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | この WebFont インスタンスが指定されたものと等しいかどうかを判断します |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | この WebFont インスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判断します |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


ARGB32 形式のフォントカラー


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


ARGB32 形式のフォントカラー


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


フォントの太さ（またはボールド）を設定します


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


フォントの太さ（またはボールド）を設定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


フォントファミリーから通常、イタリック、または斜体のスタイルを適用するかどうかを設定します。


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


フォントファミリーから通常、イタリック、または斜体のスタイルを適用するかどうかを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


テキストに適用される行または行の組み合わせを設定します


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


テキストに適用される行または行の組み合わせを設定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


フォントサイズを絶対単位または相対単位で設定します


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


フォントサイズを絶対単位または相対単位で設定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


フォント名を設定します。指定しない場合、デフォルトのフォントが使用されます


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


フォント名を設定します。指定しない場合、デフォルトのフォントが使用されます


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


この [WebFont](../../com.groupdocs.editor.options/webfont) インスタンスの完全なディープコピーを作成して返します


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


この WebFont インスタンスが指定されたものと等しいかどうかを判断します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | 等価性をチェックする別の WebFont（NULL の可能性あり） |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


この WebFont インスタンスが指定されたキャストされていないオブジェクトと等しいかどうかを判断します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | オブジェクト（[WebFont](../../com.groupdocs.editor.options/webfont) インスタンスであることが期待されます） |
|

**Returns:**
boolean - 等しい場合は true、等しくない場合は false

