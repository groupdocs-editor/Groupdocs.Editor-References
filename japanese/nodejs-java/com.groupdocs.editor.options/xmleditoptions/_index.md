---
title: "XmlEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "XML（eXtensible Markup Language）ドキュメントの読み込みと HTML への変換のためのカスタムオプションを指定できます"
type: docs
weight: 51
url: /ja/nodejs-java/com.groupdocs.editor.options/xmleditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class XmlEditOptions implements IEditOptions
```

XML（eXtensible Markup Language）の読み込みのためのカスタムオプションを指定できます
ドキュメントを HTML に変換します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XmlEditOptions()](#XmlEditOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | テキストドキュメントの文字エンコーディングで、これが適用されます |
開く時。
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストドキュメントの文字エンコーディングで、これが適用されます |
開く時。
|
|  | [getFixIncorrectStructure()](#getFixIncorrectStructure--) | 破損した XML 構造を修正するメカニズムの有効化または無効化ができます。 |
|
|  | [setFixIncorrectStructure(boolean value)](#setFixIncorrectStructure-boolean-) | 破損した XML 構造を修正するメカニズムの有効化または無効化ができます。 |
|
|  | [getRecognizeUris()](#getRecognizeUris--) | URI 認識アルゴリズムを有効にできます |
|
|  | [setRecognizeUris(boolean value)](#setRecognizeUris-boolean-) | URI 認識アルゴリズムを有効にできます |
|
|  | [getRecognizeEmails()](#getRecognizeEmails--) | 属性内のメールアドレス認識アルゴリズムを有効にできます |
値
|
|  | [setRecognizeEmails(boolean value)](#setRecognizeEmails-boolean-) | 属性内のメールアドレス認識アルゴリズムを有効にできます |
値
|
|  | [getTrimTrailingWhitespaces()](#getTrimTrailingWhitespaces--) | 内部タグの末尾空白の切り捨てを有効にできます |
テキスト。
|
|  | [setTrimTrailingWhitespaces(boolean value)](#setTrimTrailingWhitespaces-boolean-) | 内部タグの末尾空白の切り捨てを有効にできます |
テキスト。
|
|  | [getAttributeValuesQuoteType()](#getAttributeValuesQuoteType--) | 属性値の引用符タイプ（シングルまたはダブル）を指定できます。 |
|
|  | [setAttributeValuesQuoteType(QuoteType value)](#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | 属性値の引用符タイプ（シングルまたはダブル）を指定できます。 |
|
|  | [getHighlightOptions()](#getHighlightOptions--) | XML 構造が HTML で表現される際に適用される XML ハイライトを調整できます。 |
|
|  | [getFormatOptions()](#getFormatOptions--) | XML 構造が HTML で表現される際に適用される XML フォーマットを調整できます。 |
|
### XmlEditOptions() {#XmlEditOptions--}
```
public XmlEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


テキストドキュメントの文字エンコーディングで、これが適用されます
開く時。デフォルトは null \\u2014 内部ドキュメントエンコーディングが適用されます。


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


テキストドキュメントの文字エンコーディングで、これが適用されます
開く時。デフォルトは null \\u2014 内部ドキュメントエンコーディングが適用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset |  |

### getFixIncorrectStructure() {#getFixIncorrectStructure--}
```
public final boolean getFixIncorrectStructure()
```


破損した XML 構造を修正するメカニズムの有効化または無効化ができます。
デフォルトでは無効です (false)。

*** ** * ** ***


デフォルトでは、適切で有効な整形式 XML ドキュメントのみが
受け入れられます。このオプションが有効な場合、GroupDocs.Editor は修正しようとします
可能であれば破損した XML 構造を修正します。


**Returns:**
ブール
### setFixIncorrectStructure(boolean value) {#setFixIncorrectStructure-boolean-}
```
public final void setFixIncorrectStructure(boolean value)
```


破損した XML 構造を修正するメカニズムの有効化または無効化ができます。
デフォルトでは無効です (false)。

*** ** * ** ***


デフォルトでは、適切で有効な整形式 XML ドキュメントのみが
受け入れられます。このオプションが有効な場合、GroupDocs.Editor は修正しようとします
可能であれば破損した XML 構造を修正します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getRecognizeUris() {#getRecognizeUris--}
```
public final boolean getRecognizeUris()
```


URI 認識アルゴリズムを有効にできます


**Returns:**
ブール
### setRecognizeUris(boolean value) {#setRecognizeUris-boolean-}
```
public final void setRecognizeUris(boolean value)
```


URI 認識アルゴリズムを有効にできます


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getRecognizeEmails() {#getRecognizeEmails--}
```
public final boolean getRecognizeEmails()
```


属性内のメールアドレス認識アルゴリズムを有効にできます
値


**Returns:**
ブール
### setRecognizeEmails(boolean value) {#setRecognizeEmails-boolean-}
```
public final void setRecognizeEmails(boolean value)
```


属性内のメールアドレス認識アルゴリズムを有効にできます
値


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getTrimTrailingWhitespaces() {#getTrimTrailingWhitespaces--}
```
public final boolean getTrimTrailingWhitespaces()
```


内部タグの末尾空白の切り捨てを有効にできます
テキスト。デフォルトでは無効です (false) \\u2014 末尾の空白は
保持されます。


**Returns:**
ブール
### setTrimTrailingWhitespaces(boolean value) {#setTrimTrailingWhitespaces-boolean-}
```
public final void setTrimTrailingWhitespaces(boolean value)
```


内部タグの末尾空白の切り捨てを有効にできます
テキスト。デフォルトでは無効です (false) \\u2014 末尾の空白は
保持されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getAttributeValuesQuoteType() {#getAttributeValuesQuoteType--}
```
public final QuoteType getAttributeValuesQuoteType()
```


属性値の引用符タイプ（シングルまたはダブルクオート）を指定できます。デフォルトはダブルクオートです。


**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
### setAttributeValuesQuoteType(QuoteType value) {#setAttributeValuesQuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final void setAttributeValuesQuoteType(QuoteType value)
```


属性値の引用符タイプ（シングルまたはダブルクオート）を指定できます。デフォルトはダブルクオートです。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |  |

### getHighlightOptions() {#getHighlightOptions--}
```
public final XmlHighlightOptions getHighlightOptions()
```


HTMLで表現される際にXML構造に適用されるXMLハイライトを調整できます。デフォルトのハイライトが使用され、調整可能です。nullにすることはできません。


**Returns:**
[XmlHighlightOptions](../../com.groupdocs.editor.options/xmlhighlightoptions)
### getFormatOptions() {#getFormatOptions--}
```
public final XmlFormatOptions getFormatOptions()
```


HTMLで表現される際にXML構造に適用されるXMLフォーマットを調整できます。デフォルトのフォーマットが使用され、調整可能です。nullにすることはできません。


**Returns:**
[XmlFormatOptions](../../com.groupdocs.editor.options/xmlformatoptions)
