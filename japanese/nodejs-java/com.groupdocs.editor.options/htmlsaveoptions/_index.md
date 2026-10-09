---
title: "HtmlSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "HTML 形式でインスタンスを保存するためのカスタムオプションを指定できます"
type: docs
weight: 19
url: /ja/nodejs-java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

HTML 形式で [EditableDocument](../../com.groupdocs.editor/editabledocument) インスタンスを保存するためのカスタムオプションを指定できます

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | HTML マークアップ内で HTML タグ名がどのように表記されるかを制御します：すべて小文字（デフォルト値）、すべて大文字、または先頭文字だけ大文字 |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | HTML マークアップ内で HTML タグ名がどのように表記されるかを制御します：すべて小文字（デフォルト値）、すべて大文字、または先頭文字だけ大文字 |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | HTML 要素の属性値を囲むデリミタとして、シングルクオート（デフォルト値）またはダブルクオートのどちらを使用するかを制御します |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | HTML 要素の属性値を囲むデリミタとして、シングルクオート（デフォルト値）またはダブルクオートのどちらを使用するかを制御します |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | CSS スタイルシートの保存場所を制御します：外部リソースとして ( |
false
), または HTML マークアップ内に埋め込み、HTML-\>HEAD セクションの STYLE 要素内に配置します (
true
)
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | CSS スタイルシートの保存場所を制御します：外部リソースとして ( |
false
), または HTML マークアップ内に埋め込み、HTML-\>HEAD セクションの STYLE 要素内に配置します (
true
)
|
|  | [getSavingCallback()](#getSavingCallback--) | エンドユーザーがすべての外部 HTML リソースを保存するために実装しなければならないインターフェイス |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | エンドユーザーがすべての外部 HTML リソースを保存するために実装しなければならないインターフェイス |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


HTML マークアップ内で HTML タグ名がどのように表記されるかを制御します：すべて小文字（デフォルト値）、すべて大文字、または先頭文字だけ大文字


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


HTML マークアップ内で HTML タグ名がどのように表記されるかを制御します：すべて小文字（デフォルト値）、すべて大文字、または先頭文字だけ大文字


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


HTML 要素の属性値を囲むデリミタとして、シングルクオート（デフォルト値）またはダブルクオートのどちらを使用するかを制御します


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


HTML 要素の属性値を囲むデリミタとして、シングルクオート（デフォルト値）またはダブルクオートのどちらを使用するかを制御します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


CSS スタイルシートの保存場所を制御します：外部リソースとして (
false
), または HTML マークアップ内に埋め込み、HTML-\>HEAD セクションの STYLE 要素内に配置します (
true
)


**Returns:**
ブール
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


CSS スタイルシートの保存場所を制御します：外部リソースとして (
false
), または HTML マークアップ内に埋め込み、HTML-\>HEAD セクションの STYLE 要素内に配置します (
true
)


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


エンドユーザーがすべての外部 HTML リソースを保存するために実装しなければならないインターフェイス


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


エンドユーザーがすべての外部 HTML リソースを保存するために実装しなければならないインターフェイス


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

