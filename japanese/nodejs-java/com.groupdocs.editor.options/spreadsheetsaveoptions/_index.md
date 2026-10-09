---
title: "SpreadsheetSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "SpreadsheetのExcel準拠ドキュメントを生成および保存するためのカスタムオプションを指定できます"
type: docs
weight: 37
url: /ja/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Spreadsheetの生成および保存のためのカスタムオプションを指定できます
(Excel準拠) ドキュメント

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | このパラメータなしコンストラクタは、XLSX出力形式でSpreadsheetSaveOptionsの新しいインスタンスを作成します（その後、以下を通じて変更可能です |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) プロパティ)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | 指定された必須項目でSpreadsheetSaveOptionsの新しいインスタンスを作成します |
他のすべてのパラメータはデフォルトのままで、Spreadsheetの出力形式を指定します
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | パスワードを指定、変更、取得、または削除することを許可します |
生成されたSpreadsheetドキュメントをエンコードするために使用されます（このドキュメント形式の場合）
パスワード保護をサポートします。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを指定、変更、取得、または削除することを許可します |
生成されたSpreadsheetドキュメントをエンコードするために使用されます（このドキュメント形式の場合）
パスワード保護をサポートします。
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | 既存のスプレッドシートのコピーに編集済みワークシートを挿入できます |
新しい単一ワークシートのスプレッドシートを作成する代わりに（デフォルト
動作）。
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | 既存のスプレッドシートのコピーに編集済みワークシートを挿入できます |
新しい単一ワークシートのスプレッドシートを作成する代わりに（デフォルト
動作）。
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | 編集済みワークシートが置き換えるかどうかを指定するブールフラグ |
元のスプレッドシート内の既存ワークシートを、指定された位置に
その

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
プロパティ、または既存のワークシートと
前のワークシートの間に挿入され、内容を置き換えません。
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | 編集済みワークシートが置き換えるかどうかを指定するブールフラグ |
元のスプレッドシート内の既存ワークシートを、指定された位置に
その

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
プロパティ、または既存のワークシートと
前のワークシートの間に挿入され、内容を置き換えません。
|
|  | [getOutputFormat()](#getOutputFormat--) | 保存に使用されるSpreadsheet形式を指定できます |
文書
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | 保存に使用されるSpreadsheet形式を指定できます |
文書
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | 出力Spreadsheetに対してワークシート保護を有効にできます |
ドキュメント。
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | 出力Spreadsheetに対してワークシート保護を有効にできます |
ドキュメント。
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | 編集されたワークシートが既存のスプレッドシートに挿入される場合に、保存時にスプレッドシートから削除すべきワークシートの 1 ベース番号の配列を指定できます。 |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | 編集されたワークシートが既存のスプレッドシートに挿入される場合に、保存時にスプレッドシートから削除すべきワークシートの 1 ベース番号の配列を指定できます。 |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


このパラメータなしコンストラクタは、XLSX出力形式でSpreadsheetSaveOptionsの新しいインスタンスを作成します（その後、以下を通じて変更可能です
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) プロパティ)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


指定された必須項目でSpreadsheetSaveOptionsの新しいインスタンスを作成します
他のすべてのパラメータはデフォルトのままで、Spreadsheetの出力形式を指定します


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | スプレッドシートドキュメントを保存すべき必須の出力形式 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードを指定、変更、取得、または削除することを許可します
生成されたSpreadsheetドキュメントをエンコードするために使用されます（このドキュメント形式の場合）
パスワード保護をサポートします。削除する場合は NULL または空文字列を指定してください。
(パスワードの)クリーニング。


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワードを指定、変更、取得、または削除することを許可します
生成されたSpreadsheetドキュメントをエンコードするために使用されます（このドキュメント形式の場合）
パスワード保護をサポートします。削除する場合は NULL または空文字列を指定してください。
(パスワードの)クリーニング。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


既存のスプレッドシートのコピーに編集済みワークシートを挿入できます
新しい単一ワークシートのスプレッドシートを作成する代わりに（デフォルト
動作)。WorksheetNumber は、ワークシートの 1 ベース番号です。
スプレッドシートで、Editor クラスにロードされます。0（デフォルト値）の場合、
新しいスプレッドシートは単一の編集済みワークシートで作成されます。もしそれが
0 より大きいまたは小さい場合で、かつ有効なスプレッドシートが Editor クラスにロードされている場合、
Editor クラス内で、入力によって表される編集済みワークシートは、
EditableDocument インスタンスとして、このスプレッドシートに挿入されます。


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


既存のスプレッドシートのコピーに編集済みワークシートを挿入できます
新しい単一ワークシートのスプレッドシートを作成する代わりに（デフォルト
動作)。WorksheetNumber は、ワークシートの 1 ベース番号です。
スプレッドシートで、Editor クラスにロードされます。0（デフォルト値）の場合、
新しいスプレッドシートは単一の編集済みワークシートで作成されます。もしそれが
0 より大きいまたは小さい場合で、かつ有効なスプレッドシートが Editor クラスにロードされている場合、
Editor クラス内で、入力によって表される編集済みワークシートは、
EditableDocument インスタンスとして、このスプレッドシートに挿入されます。


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


編集済みワークシートが置き換えるかどうかを指定するブールフラグ
元のスプレッドシート内の既存ワークシートを、指定された位置に
その

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
プロパティ、または既存のワークシートと
前のものを置き換えずに挿入します。デフォルトは false \\u2014
既存のワークシートが置き換えられます。このプロパティは、値が
の

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
プロパティが '0' に設定されている場合は無視されます。


*** ** * ** ***

デフォルトではワークシートは置き換えられます。つまり、対象のスプレッドシートに 5 枚のワークシートがあり、WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 の場合、4 番目のワークシートは新しい編集済みワークシートで置き換えられ、スプレッドシート全体のワークシート数 (5) は変わりません。しかし、このプロパティの値が *true* に設定されている場合、新しい編集済みワークシートは 4 番目のワークシートとして挿入され、その後のすべてのワークシートが末尾へシフトします。つまり、元の 4 番目のワークシートは 5 番目になり、5 番目は 6 番目になり、スプレッドシートのワークシート総数は 1 増えて 6 になります。

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


編集済みワークシートが置き換えるかどうかを指定するブールフラグ
元のスプレッドシート内の既存ワークシートを、指定された位置に
その

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
プロパティ、または既存のワークシートと
前のものを置き換えずに挿入します。デフォルトは false \\u2014
既存のワークシートが置き換えられます。このプロパティは、値が
の

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
プロパティが '0' に設定されている場合は無視されます。


*** ** * ** ***

デフォルトではワークシートは置き換えられます。つまり、対象のスプレッドシートに 5 枚のワークシートがあり、WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4 の場合、4 番目のワークシートは新しい編集済みワークシートで置き換えられ、スプレッドシート全体のワークシート数 (5) は変わりません。しかし、このプロパティの値が *true* に設定されている場合、新しい編集済みワークシートは 4 番目のワークシートとして挿入され、その後のすべてのワークシートが末尾へシフトします。つまり、元の 4 番目のワークシートは 5 番目になり、5 番目は 6 番目になり、スプレッドシートのワークシート総数は 1 増えて 6 になります。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


保存に使用されるSpreadsheet形式を指定できます
文書


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


保存に使用されるSpreadsheet形式を指定できます
文書


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


出力Spreadsheetに対してワークシート保護を有効にできます
ドキュメント。デフォルトは NULL で、保護は適用されません。すべての形式が対象ではありません
ワークシート保護をサポートしています。


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


出力Spreadsheetに対してワークシート保護を有効にできます
ドキュメント。デフォルトは NULL で、保護は適用されません。すべての形式が対象ではありません
ワークシート保護をサポートしています。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


編集されたワークシートが既存のスプレッドシートに挿入される場合に、保存時にスプレッドシートから削除すべきワークシートの 1 ベース番号の配列を指定できます。編集されたワークシートが新しい単一ワークシートのスプレッドシートとして保存されるのではなく（デフォルトの動作）、既存のスプレッドシートに保存される場合（#getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int) を使用）、この配列で番号を指定することにより、特定のワークシートを削除することも可能です。デフォルトではこの配列は null  \\u2014 ワークシートは削除されません。ただし、配列が null でなく空でもなく、少なくとも 1 つの有効なワークシート番号を含む場合、編集されたワークシートの内容で出力スプレッドシートドキュメントが生成された後、指定された番号のワークシートは出力ストリームまたはファイルに書き込む直前にスプレッドシートから削除されます。この配列のワークシート番号は 1 ベースで、0 ベースではありません。無効な番号（1 未満またはワークシート総数を超えるもの）は無視されます。


**Returns:**
int[] - 削除する 1 ベースのワークシート番号の配列、または何も削除しない場合は null

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


編集されたワークシートが既存のスプレッドシートに挿入される場合に、保存時にスプレッドシートから削除すべきワークシートの 1 ベース番号の配列を指定できます。この配列のワークシート番号は 1 ベースです。無効な番号は無視されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 値 | int[] | 削除する 1 ベースのワークシート番号の配列（null または空でも可） |
|

