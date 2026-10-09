---
title: "FixedLayoutEditOptionsBase"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PDF や XPS などの固定レイアウト形式のすべてのドキュメント向けオプションの基底抽象クラスです。"
type: docs
weight: 16
url: /ja/nodejs-java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

PDF や XPS などの固定レイアウト形式のすべてのドキュメント向けオプションの基底抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | 入力の固定レイアウト文書を結果のHTMLに変換する際に画像をスキップするかどうかを示すフラグを取得または設定します。 |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | 入力の固定レイアウト文書を結果のHTMLに変換する際に画像をスキップするかどうかを示すフラグを取得または設定します。 |
|
|  | [getPages()](#getPages--) | 処理するページ範囲を設定できるようにします。 |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | 処理するページ範囲を設定できるようにします。 |
|
|  | [getEnablePagination()](#getEnablePagination--) | 結果のHTMLドキュメントでページネーションを有効（true）または無効（false）にできるようにします。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 結果のHTMLドキュメントでページネーションを有効（true）または無効（false）にできるようにします。 |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


入力の固定レイアウト文書を結果のHTMLに変換する際に画像をスキップするかどうかを示すフラグを取得または設定します。デフォルトは false で、画像は保持されます。


**Returns:**
ブール
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


入力の固定レイアウト文書を結果のHTMLに変換する際に画像をスキップするかどうかを示すフラグを取得または設定します。デフォルトは false で、画像は保持されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


処理するページ範囲を設定できます。デフォルトでは、固定レイアウト文書のすべてのページが処理されます。


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


処理するページ範囲を設定できます。デフォルトでは、固定レイアウト文書のすべてのページが処理されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


結果のHTMLドキュメントでページネーションを有効（true）または無効（false）にできます。デフォルトでは無効（false）です。

<br />

*** ** * ** ***

固定レイアウト形式の文書（特に PDF と XPS）は本質的に厳密にページ分割されており、コンテンツは固定レイアウトでページに分割されています。ただし、結果として得られる編集可能なHTMLは、ページなしビューまたはページ付きビューのいずれかで表現できます。

<br />



**Returns:**
ブール
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


結果のHTMLドキュメントでページネーションを有効（true）または無効（false）にできます。デフォルトでは無効（false）です。

<br />

*** ** * ** ***

固定レイアウト形式の文書（特に PDF と XPS）は本質的に厳密にページ分割されており、コンテンツは固定レイアウトでページに分割されています。ただし、結果として得られる編集可能なHTMLは、ページなしビューまたはページ付きビューのいずれかで表現できます。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

