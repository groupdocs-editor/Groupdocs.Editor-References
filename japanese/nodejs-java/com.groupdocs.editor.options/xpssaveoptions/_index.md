---
title: "XpsSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "XPS XML Paper Specifications ドキュメントの生成および保存のためのカスタムオプションを指定できます"
type: docs
weight: 54
url: /ja/nodejs-java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

XPS（XML Paper Specifications）ドキュメントの生成および保存にカスタムオプションを指定できます。

<br />

*** ** * ** ***

XPS ファイルは、Microsoft が作成した XML Paper Specifications に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、ドキュメントのレイアウト、外観、印刷情報に XML を使用します。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | 元のドキュメントで使用されているフォントリソースを、生成された XPS ドキュメントに埋め込む役割を担います。 |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。 |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


元のドキュメントで使用されているフォントリソースを、生成された XPS ドキュメントに埋め込む役割を担います。
デフォルトではフォントを埋め込みません (NotEmbed)。


**Returns:**
バイト
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。
このオプションを true に設定すると、保存時間が遅くなる代償として、大きなドキュメント生成時のメモリ消費を大幅に削減できます。
デフォルトは false です (メモリ最適化は、より高いパフォーマンスを得るために無効化されています)。


**Returns:**
ブール
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。
このオプションを true に設定すると、保存時間が遅くなる代償として、大きなドキュメント生成時のメモリ消費を大幅に削減できます。
デフォルトは false です (メモリ最適化は、より高いパフォーマンスを得るために無効化されています)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

