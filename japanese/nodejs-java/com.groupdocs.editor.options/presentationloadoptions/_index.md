---
title: "PresentationLoadOptions"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "PPTX、PPTM、PPSX など、サポートされるすべての Presentation 形式のドキュメントを読み込むためのカスタムオプションを指定できます"
type: docs
weight: 33
url: /ja/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

サポートされるすべてのドキュメントを読み込むためのカスタムオプションを指定できます
PPT(X)、PPTM、PPS(X) などの Presentation 形式

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
Presentation ドキュメントを開く際に、エンコードされている場合です。
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワードを指定、変更、取得でき、以下の目的で使用されます。 |
Presentation ドキュメントを開く際に、エンコードされている場合です。
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
Presentation ドキュメントを開く際に、エンコードされている場合です。NULL または空に設定します
パスワードを削除するための文字列です。


*** ** * ** ***

デフォルトではこのプロパティは NULL 値 \\u2014 パスワードが設定されていません。入力の Presentation ドキュメントがパスワードで保護されている場合、パスワードは必須で、指定されていないか無効な場合は例外がスローされます。入力の Presentation ドキュメントがパスワードで保護されていない場合でも、パスワードが設定されていると無視されます。

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワードを指定、変更、取得でき、以下の目的で使用されます。
Presentation ドキュメントを開く際に、エンコードされている場合です。NULL または空に設定します
パスワードを削除するための文字列です。


*** ** * ** ***

デフォルトではこのプロパティは NULL 値 \\u2014 パスワードが設定されていません。入力の Presentation ドキュメントがパスワードで保護されている場合、パスワードは必須で、指定されていないか無効な場合は例外がスローされます。入力の Presentation ドキュメントがパスワードで保護されていない場合でも、パスワードが設定されていると無視されます。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

