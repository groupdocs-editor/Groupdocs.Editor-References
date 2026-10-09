---
title: "SpreadsheetEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされているすべてのスプレッドシート（Excel 互換）形式のドキュメントを編集するためのカスタムオプションを指定できます"
type: docs
weight: 35
url: /ja/nodejs-java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

サポート可能なすべてのドキュメント編集用にカスタムオプションを指定できます
スプレッドシート（Excel 互換）形式

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 入力のワークシート（タブ）の 0 ベースインデックスを指定できます |
HTML に変換すべきスプレッドシート ドキュメント (参照
備考)。
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 入力のワークシート（タブ）の 0 ベースインデックスを指定できます |
HTML に変換すべきスプレッドシート ドキュメント (参照
備考)。
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | 入力スプレッドシート ドキュメント内の非表示ワークシートを除外できるようにし、 |
それらは完全に無視されます。
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | 入力スプレッドシート ドキュメント内の非表示ワークシートを除外できるようにし、 |
それらは完全に無視されます。
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | 有効にすると、入力スプレッドシート ドキュメントの隣接する空の水平セルは |
対応する
colspan 属性。
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | 有効にすると、生成された HTML ドキュメントの HTML テーブルには、空の下部非表示行が含まれ、 |
高さが 0 で、幅のみが指定された空のセルが含まれます。
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


入力のワークシート（タブ）の 0 ベースインデックスを指定できます
HTML に変換すべきスプレッドシート ドキュメント (参照
備考)。


*** ** * ** ***

ほとんどのスプレッドシート ドキュメントはタブの概念をサポートしており、つまり複数タブを持つことができます。一方、HTML 形式はそのような構造をサポートしていません。そのため GroupDocs.Editor は入力ドキュメントの特定のタブ 1 つだけを HTML に変換でき、このオプションでそのタブを指定できます。タブインデックスは 0 ベースで、負の値は許可されません。指定したインデックスがタブの総数を超えると例外がスローされます。入力スプレッドシート ドキュメントが 1 つのタブしか持たない場合、このオプションは無視されます。デフォルト値は 0（最初のタブ）です。

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


入力のワークシート（タブ）の 0 ベースインデックスを指定できます
HTML に変換すべきスプレッドシート ドキュメント (参照
備考)。


*** ** * ** ***

ほとんどのスプレッドシート ドキュメントはタブの概念をサポートしており、つまり複数タブを持つことができます。一方、HTML 形式はそのような構造をサポートしていません。そのため GroupDocs.Editor は入力ドキュメントの特定のタブ 1 つだけを HTML に変換でき、このオプションでそのタブを指定できます。タブインデックスは 0 ベースで、負の値は許可されません。指定したインデックスがタブの総数を超えると例外がスローされます。入力スプレッドシート ドキュメントが 1 つのタブしか持たない場合、このオプションは無視されます。デフォルト値は 0（最初のタブ）です。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


入力スプレッドシート ドキュメント内の非表示ワークシートを除外できるようにし、
それらは完全に無視されます。デフォルトは false で、非表示ワークシートは
利用可能で通常どおり処理されます。


*** ** * ** ***

XLSX のような一部のバイナリ スプレッドシート形式は、非表示ワークシート（タブ）の概念をサポートしています。そのような形式のドキュメントは、複数のワークシートがある場合、追加の非表示ワークシートを含むことがあります。デフォルトではこれらの非表示ワークシートは処理対象として利用可能ですが、このオプションを使用すると、これらが存在しないかのように無視できます。このオプションが有効な場合、' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' プロパティで非表示ワークシートを選択することはできません。

<br />



**Returns:**
ブール
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


入力スプレッドシート ドキュメント内の非表示ワークシートを除外できるようにし、
それらは完全に無視されます。デフォルトは false で、非表示ワークシートは
利用可能で通常どおり処理されます。


*** ** * ** ***

XLSX のような一部のバイナリ スプレッドシート形式は、非表示ワークシート（タブ）の概念をサポートしています。そのような形式のドキュメントは、複数のワークシートがある場合、追加の非表示ワークシートを含むことがあります。デフォルトではこれらの非表示ワークシートは処理対象として利用可能ですが、このオプションを使用すると、これらが存在しないかのように無視できます。このオプションが有効な場合、' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))' プロパティで非表示ワークシートを選択することはできません。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


有効にすると、入力スプレッドシート ドキュメントの隣接する空の水平セルは
対応する
colspan 属性。デフォルトでは無効（false）です。


デフォルトでは、GroupDocs.Editor は入力スプレッドシート ドキュメントからテーブルを出力へ変換します
HTML ドキュメントに各セルを保持して変換します。ただし、スプレッドシート ドキュメントは稀疎になることがあります \\u2014 それらは
大量の \"empty areas\" を含むことがあり、多くのセルが空です。このオプションは、
有効にすると、これらの空セルを TD 要素の colspan 属性を持つ 1 つのセルに結合し、
そして、生成された HTML マークアップのサイズを大幅に削減できます。


**Returns:**
ブール
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


有効にすると、生成された HTML ドキュメントの HTML テーブルには、空の下部非表示行が含まれ、
高さが 0 で幅のみが指定された空のセルがあります。この空セルの行は
各列の正確な幅の値を含み、HTML からスプレッドシートへの逆変換を改善します。
デフォルトでは有効（true）です。


**Returns:**
ブール
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

