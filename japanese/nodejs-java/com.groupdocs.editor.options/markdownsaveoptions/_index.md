---
title: "MarkdownSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "Markdown ドキュメントを生成および保存するためのカスタムオプションを指定できます。"
type: docs
weight: 24
url: /ja/nodejs-java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

Markdown ドキュメントを生成および保存するためのカスタムオプションを指定できます。

<br />

*** ** * ** ***

ユーザーは、編集されたドキュメント内容を含む EditableDocument クラスのインスタンスがある場合に、MarkdownSaveOptions クラスを適用し、この内容を Markdown 形式の新しいドキュメントに保存する必要があります。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。 |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。 |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | Allow は、Markdown 形式にエクスポートする際のテーブル内コンテンツの配置方法を指定します。 |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | Allow は、Markdown 形式にエクスポートする際のテーブル内コンテンツの配置方法を指定します。 |
|
|  | [getImagesFolder()](#getImagesFolder--) | ドキュメントをエクスポートする際に画像が保存される物理フォルダーを指定します。 |
Markdown 形式です。
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | ドキュメントをエクスポートする際に画像が保存される物理フォルダーを指定します。 |
Markdown 形式です。
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | 画像が出力ファイルに Base64 形式で保存されるかどうかを指定します。 |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | 画像が出力ファイルに Base64 形式で保存されるかどうかを指定します。 |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。
このオプションを設定すると
true
大きなドキュメントを生成する際のメモリ消費を大幅に減らす代わりに、保存時間が遅くなります。
デフォルトは
false
(パフォーマンス向上のためにメモリ最適化は無効化されています)。


**Returns:**
ブール
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


HTML からドキュメントを生成する際にメモリ最適化機構を有効にします。これによりメモリ使用量は減少しますが、パフォーマンスが低下します。
このオプションを設定すると
true
大きなドキュメントを生成する際のメモリ消費を大幅に減らす代わりに、保存時間が遅くなります。
デフォルトは
false
(パフォーマンス向上のためにメモリ最適化は無効化されています)。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


Allow は、Markdown 形式にエクスポートする際のテーブル内コンテンツの配置方法を指定します。
デフォルト値は [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto) です。
値: テーブルコンテンツの配置


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


Allow は、Markdown 形式にエクスポートする際のテーブル内コンテンツの配置方法を指定します。
デフォルト値は [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto) です。
値: テーブルコンテンツの配置


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


ドキュメントをエクスポートする際に画像が保存される物理フォルダーを指定します。
Markdown 形式です。デフォルトは null です。

<br />

*** ** * ** ***

ユーザーが ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) も ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) も指定しない場合、GroupDocs.Editor は自動的に ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) を判別し、成功した場合に適用します。

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


ドキュメントをエクスポートする際に画像が保存される物理フォルダーを指定します。
Markdown 形式です。デフォルトは null です。

<br />

*** ** * ** ***

ユーザーが ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) も ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) も指定しない場合、GroupDocs.Editor は自動的に ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) を判別し、成功した場合に適用します。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


画像が出力ファイルに Base64 形式で保存されるかどうかを指定します。デフォルトは
false
.

<br />

*** ** * ** ***

このプロパティが `true` に設定されている場合、画像データは画像要素 ![](../) に直接エクスポートされ、別個のファイルは作成されません。このプロパティが `true` に設定されている場合、MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) プロパティよりも高い優先順位を持ちます。

<br />



**Returns:**
ブール
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


画像が出力ファイルに Base64 形式で保存されるかどうかを指定します。デフォルトは
false
.

<br />

*** ** * ** ***

このプロパティが `true` に設定されている場合、画像データは画像要素 ![](../) に直接エクスポートされ、別個のファイルは作成されません。このプロパティが `true` に設定されている場合、MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) プロパティよりも高い優先順位を持ちます。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

