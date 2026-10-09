---
title: "InvalidFormField"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "FormFieldManager.FixInvalidFormFieldNames 操作中に無効なフォームフィールド名の更新を表します。"
type: docs
weight: 18
url: /ja/nodejs-java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

無効なフォームフィールド名の更新を表します。
FormFieldManager.FixInvalidFormFieldNames
操作。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | 指定された名前で [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | 外部から変更できないフォームフィールドの元の名前を取得します。 |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | 修復後のフォームフィールドの新しい名前を取得または設定します。 |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | 修復後のフォームフィールドの新しい名前を取得または設定します。 |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


指定された名前で [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | フォームフィールドの元の名前です。 |
|

### getName() {#getName--}
```
public final String getName()
```


外部から変更できないフォームフィールドの元の名前を取得します。
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


修復後のフォームフィールドの新しい名前を取得または設定します。
この名前は他のフォームフィールドとの重複した一意の識別子を削除し、ユニークなブックマーク名を設定します。

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


修復後のフォームフィールドの新しい名前を取得または設定します。
この名前は他のフォームフィールドとの重複した一意の識別子を削除し、ユニークなブックマーク名を設定します。

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

