---
title: "EmailSaveOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "電子メールドキュメントの生成および保存時にカスタムオプションを指定できます。"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

電子メール（email）ドキュメントを生成および保存するためのカスタムオプションを指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | すべてのオプションがデフォルト値に設定された、[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) クラスの新しいインスタンスを初期化します |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | 次のパラメータで、[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) クラスの新しいインスタンスを初期化します |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) パラメータ
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | メールメッセージのどの部分を出力メールドキュメントに渡すかを制御できるようにし、[Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) メソッドで生成および保存されます |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | メールメッセージのどの部分を出力メールドキュメントに渡すかを制御できるようにし、[Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) メソッドで生成および保存されます |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


すべてのオプションがデフォルト値に設定された、[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) クラスの新しいインスタンスを初期化します


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


次のパラメータで、[EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) クラスの新しいインスタンスを初期化します
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


メールメッセージのどの部分を出力メールドキュメントに渡すかを制御できるようにし、[Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) メソッドで生成および保存されます
値: 処理すべきメールメッセージの部分を制御するフラグ付き列挙体です。デフォルト値は MailMessageOutput.All です


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


メールメッセージのどの部分を出力メールドキュメントに渡すかを制御できるようにし、[Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) メソッドで生成および保存されます
値: 処理すべきメールメッセージの部分を制御するフラグ付き列挙体です。デフォルト値は MailMessageOutput.All です


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

