---
title: "WorksheetProtection"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "出力の Spreadsheet ドキュメントで、指定されたタイプの変更からワークシートを保護するためのオプションをカプセル化し、指定されたパスワードで保護します。"
type: docs
weight: 49
url: /ja/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

ワークシートを保護するためのオプションをカプセル化します
出力の Spreadsheet ドキュメントで、指定されたタイプの変更から
指定されたパスワードで。


*** ** * ** ***

XLSX などの多くの Spreadsheet 形式は、パスワードで編集を保護することができます。このクラスはその保護を有効にし、オプションを指定できるようにします。

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | デフォルトパラメータで新しいインスタンスを作成します。 |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | 指定されたワークシート保護タイプで新しいインスタンスを作成し、 |
パスワード
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | ワークシート保護のタイプを指定できます。 |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | ワークシート保護のタイプを指定できます。 |
|
|  | [getPassword()](#getPassword--) | ワークシートを保護するために使用されるパスワード。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | ワークシートを保護するために使用されるパスワード。 |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


デフォルトパラメーターで新しいインスタンスを作成します。変更されずに渡された場合
SpreadsheetSaveOptions に渡すと、ワークシート保護は適用されません


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


指定されたワークシート保護タイプで新しいインスタンスを作成し、
パスワード


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | protectionType | int | ワークシート保護のタイプ |
|
|  | パスワード | java.lang.String | 保護をロックするパスワード |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


ワークシート保護のタイプを指定できます。デフォルトは 'None' -
保護は適用されません。


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


ワークシート保護のタイプを指定できます。デフォルトは 'None' -
保護は適用されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


ワークシートを保護するために使用されるパスワード。NULL または空の場合
文字列の場合、保護は適用されません。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


ワークシートを保護するために使用されるパスワード。NULL または空の場合
文字列の場合、保護は適用されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

