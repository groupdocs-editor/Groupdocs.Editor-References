---
title: "EbookEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされているすべての形式（ePub、MOBI、AZW3）で電子書籍ドキュメントを編集するためのカスタムオプションを指定および調整できます。"
type: docs
weight: 12
url: /ja/nodejs-java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

すべてのサポートされている形式（ePub、MOBI、AZW3）で電子書籍ドキュメントを編集するためのカスタムオプションを指定および調整できます。

<br />

*** ** * ** ***

サポートされている電子書籍形式：

1. [ePub](../https://docs.fileformat.com/ebook/epub/)（電子出版）
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/)（MobiPocket）
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/)（Kindle Format 8t）

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) クラスの新しいインスタンスを初期化します。すべてのオプションはデフォルト値に設定されています |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | 指定されたページングモードで [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) クラスの新しいインスタンスを初期化します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 生成された HTML ドキュメントでページングを有効または無効にできます。 |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 生成された HTML ドキュメントでページングを有効または無効にできます。 |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | 言語情報を 'lang' HTML 属性の形で HTML マークアップにエクスポートするかどうかを指定します。 |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | 言語情報を 'lang' HTML 属性の形で HTML マークアップにエクスポートするかどうかを指定します。 |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


[EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) クラスの新しいインスタンスを初期化します。すべてのオプションはデフォルト値に設定されています


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


指定されたページングモードで [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) クラスの新しいインスタンスを初期化します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | enablePagination | ブール | 結果の HTML ドキュメント内の電子書籍コンテンツのページングを有効にする ( true ) または無効にする ( false )。デフォルトでは無効 ( false ) です。 |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


結果の HTML ドキュメントでページングを有効または無効にできます。デフォルトでは無効です (
false
）。

<br />

*** ** * ** ***

本質的に、ほとんどの電子書籍フォーマットは内部的に Office Open XML のようなフローフォーマットで、コンテンツは一続きで章に分割されますがページには分割されません。ただし、ページ番号、脚注、ヘッダー/フッターなどのページ固有情報を含みます。一部の電子書籍リーダーはコンテンツをページ単位に分割しますが、他のリーダー（特にモバイル） \\u2014 そうではありません。このオプションは、編集時に電子書籍コンテンツを HTML/CSS でどのように表現するか（フロート ( false ) またはページング ( true ) ビュー）を制御できます。

<br />



**Returns:**
ブール
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


結果の HTML ドキュメントでページングを有効または無効にできます。デフォルトでは無効です (
false
）。

<br />

*** ** * ** ***

本質的に、ほとんどの電子書籍フォーマットは内部的に Office Open XML のようなフローフォーマットで、コンテンツは一続きで章に分割されますがページには分割されません。ただし、ページ番号、脚注、ヘッダー/フッターなどのページ固有情報を含みます。一部の電子書籍リーダーはコンテンツをページ単位に分割しますが、他のリーダー（特にモバイル） \\u2014 そうではありません。このオプションは、編集時に電子書籍コンテンツを HTML/CSS でどのように表現するか（フロート ( false ) またはページング ( true ) ビュー）を制御できます。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


言語情報を 'lang' HTML 属性の形で HTML マークアップにエクスポートするかどうかを指定します。
このオプションは、多言語ドキュメントの往復変換に役立つ場合があります。デフォルトでは無効です (
false
）。


**Returns:**
ブール
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


言語情報を 'lang' HTML 属性の形で HTML マークアップにエクスポートするかどうかを指定します。
このオプションは、多言語ドキュメントの往復変換に役立つ場合があります。デフォルトでは無効です (
false
）。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

