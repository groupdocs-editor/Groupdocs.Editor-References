---
title: "MarkdownEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "Markdown 形式のドキュメントを編集するためのカスタムオプションを指定できます。"
type: docs
weight: 21
url: /ja/nodejs-java/com.groupdocs.editor.options/markdowneditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class MarkdownEditOptions implements IEditOptions
```

Markdown 形式のドキュメントを編集するためのカスタムオプションを指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [MarkdownEditOptions()](#MarkdownEditOptions--) | MarkdownEditOptions クラスの新しいインスタンスを作成し、返します。 |
すべてのオプションがデフォルト値に設定されている場所
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getImageLoadCallback()](#getImageLoadCallback--) | Markdown ドキュメントを変換する際の画像の保存方法を制御できます |
HTML に。
|
|  | [setImageLoadCallback(IMarkdownImageLoadCallback value)](#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-) | Markdown ドキュメントを変換する際の画像の保存方法を制御できます |
HTML に。
|
### MarkdownEditOptions() {#MarkdownEditOptions--}
```
public MarkdownEditOptions()
```


MarkdownEditOptions クラスの新しいインスタンスを作成し、返します。
すべてのオプションがデフォルト値に設定されている場所


### getImageLoadCallback() {#getImageLoadCallback--}
```
public final IMarkdownImageLoadCallback getImageLoadCallback()
```


Markdown ドキュメントを変換する際の画像の保存方法を制御できます
HTML に。
値: 画像保存コールバック。


**Returns:**
[IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback)
### setImageLoadCallback(IMarkdownImageLoadCallback value) {#setImageLoadCallback-com.groupdocs.editor.options.IMarkdownImageLoadCallback-}
```
public final void setImageLoadCallback(IMarkdownImageLoadCallback value)
```


Markdown ドキュメントを変換する際の画像の保存方法を制御できます
HTML に。
値: 画像保存コールバック。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMarkdownImageLoadCallback](../../com.groupdocs.editor.options/imarkdownimageloadcallback) |  |

