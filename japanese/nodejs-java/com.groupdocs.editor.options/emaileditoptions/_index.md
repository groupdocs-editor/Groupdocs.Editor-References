---
title: "EmailEditOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "さまざまな電子メール形式で文書を編集するためのカスタムオプションを指定できます"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

さまざまな電子メール（email）形式のドキュメントを編集するためのカスタムオプションを指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) クラスの新しいインスタンスを初期化し、すべてのオプションをデフォルト値に設定します |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) クラスの新しいインスタンスを以下で初期化します |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) パラメータ
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | メールメッセージのどの部分を出力の [EditableDocument](../../com.groupdocs.editor/editabledocument) に配信し、さらに生成された HTML に渡すかを制御できます |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | メールメッセージのどの部分を出力の [EditableDocument](../../com.groupdocs.editor/editabledocument) に配信し、さらに生成された HTML に渡すかを制御できます |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


[EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) クラスの新しいインスタンスを初期化し、すべてのオプションをデフォルト値に設定します


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


[EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) クラスの新しいインスタンスを以下で初期化します
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) パラメータ


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | mailMessageOutput | int | プロパティでも指定できるメールメッセージの出力です |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


メールメッセージのどの部分を出力の [EditableDocument](../../com.groupdocs.editor/editabledocument) に配信し、さらに生成された HTML に渡すかを制御できます
値: 処理すべきメールメッセージの部分を制御するフラグ付き列挙体です。デフォルト値は MailMessageOutput.All です


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


メールメッセージのどの部分を出力の [EditableDocument](../../com.groupdocs.editor/editabledocument) に配信し、さらに生成された HTML に渡すかを制御できます
値: 処理すべきメールメッセージの部分を制御するフラグ付き列挙体です。デフォルト値は MailMessageOutput.All です


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

