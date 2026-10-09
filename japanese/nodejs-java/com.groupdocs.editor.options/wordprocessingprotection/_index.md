---
title: "WordProcessingProtection"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "HTML から生成された WordProcessing ドキュメントの保護オプションをカプセル化します"
type: docs
weight: 46
url: /ja/nodejs-java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

WordProcessing ドキュメントの保護オプションをカプセル化します、
HTML から生成された

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | パラメータなしコンストラクタ - すべてのパラメータはデフォルト値を持ちます |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | クラスのインスタンス化時にすべてのパラメータを設定できます。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | ドキュメントの保護タイプを設定できます。 |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | ドキュメントの保護タイプを設定できます。 |
|
|  | [getPassword()](#getPassword--) | ドキュメントを保護するためのパスワード。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | ドキュメントを保護するためのパスワード。 |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


パラメータなしコンストラクタ - すべてのパラメータはデフォルト値を持ちます


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


クラスのインスタンス化時にすべてのパラメータを設定できます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | protectionType | int | ドキュメントの保護タイプを設定する |
|
|  | パスワード | java.lang.String | 保護パスワードを設定する |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


ドキュメントの保護タイプを設定できます。デフォルトでは保護しないように設定されています
ドキュメントを全く保護しません。


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


ドキュメントの保護タイプを設定できます。デフォルトでは保護しないように設定されています
ドキュメントを全く保護しません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


ドキュメントを保護するためのパスワードです。null または空文字列の場合 -
保護はドキュメントに適用されません。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


ドキュメントを保護するためのパスワードです。null または空文字列の場合 -
保護はドキュメントに適用されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
