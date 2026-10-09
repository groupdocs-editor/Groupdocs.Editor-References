---
title: "TextFormField"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "テキスト入力を受け付けるフォームフィールドを表します。"
type: docs
weight: 20
url: /ja/nodejs-java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

テキスト入力を受け付けるフォームフィールドを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | 指定されたスタイルシートと名前で新しい [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) クラスのインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | フォームフィールドに適用されるスタイルシートを取得します。 |
|
|  | [getReadonly()](#getReadonly--) | フォームフィールドが読み取り専用かどうかを示す値を取得または設定します。 |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | フォームフィールドが読み取り専用かどうかを示す値を取得または設定します。 |
|
|  | [getName()](#getName--) | フォームフィールドの名前を取得します。 |
|
|  | [getType()](#getType--) | このクラスでは常に FormFieldType.Text になるフォームフィールドのタイプを取得します。 |
|
|  | [getLocaleId()](#getLocaleId--) | フォームフィールドに関連付けられたカルチャまたは地域設定を表すロケール ID を取得または設定します。 |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | フォームフィールドに関連付けられたカルチャまたは地域設定を表すロケール ID を取得または設定します。 |
|
|  | [getStatusText()](#getStatusText--) | フォームフィールドに関連付けられたステータステキストを取得または設定します、 |
フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースです。
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | フォームフィールドに関連付けられたステータステキストを取得または設定します、 |
フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースです。
|
|  | [getHelpText()](#getHelpText--) | フォームフィールドに関連付けられたヘルプテキストを取得または設定します、 |
フォームフィールドがフォーカスを持ち、ユーザーが F1 を押したときにメッセージボックスに表示されるテキストのソースです。
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | フォームフィールドに関連付けられたヘルプテキストを取得または設定します、 |
フォームフィールドがフォーカスを持ち、ユーザーが F1 を押したときにメッセージボックスに表示されるテキストのソースです。
|
|  | [getValue()](#getValue--) | テキスト入力を表すフォームフィールドの値を取得または設定します。 |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | テキスト入力を表すフォームフィールドの値を取得または設定します。 |
|
|  | [getMaxLength()](#getMaxLength--) | フォームフィールドの入力の最大長さを取得または設定します。 |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | フォームフィールドの入力の最大長さを取得または設定します。 |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


指定されたスタイルシートと名前で新しい [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) クラスのインスタンスを初期化します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | スタイルシート | java.lang.String | フォームフィールドに適用するスタイルシート。 |
|
|  | 名前 | java.lang.String | フォームフィールドの名前。 |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


フォームフィールドに適用されるスタイルシートを取得します。


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


フォームフィールドが読み取り専用かどうかを示す値を取得または設定します。


**Returns:**
ブール
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


フォームフィールドが読み取り専用かどうかを示す値を取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

### getName() {#getName--}
```
public final String getName()
```


フォームフィールドの名前を取得します。


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


このクラスでは常に FormFieldType.Text になるフォームフィールドのタイプを取得します。


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


フォームフィールドに関連付けられたカルチャまたは地域設定を表すロケール ID を取得または設定します。

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

LocaleId プロパティは、特定の文化または地域に対応するロケール識別子 (LCID) を指定します。

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


フォームフィールドに関連付けられたカルチャまたは地域設定を表すロケール ID を取得または設定します。

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

LocaleId プロパティは、特定の文化または地域に対応するロケール識別子 (LCID) を指定します。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


フォームフィールドに関連付けられたステータステキストを取得または設定します、
フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースです。

<br />

*** ** * ** ***

false に設定すると、ステータステキストは適用されません。

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


フォームフィールドに関連付けられたステータステキストを取得または設定します、
フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースです。

<br />

*** ** * ** ***

false に設定すると、ステータステキストは適用されません。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


フォームフィールドに関連付けられたヘルプテキストを取得または設定します、
フォームフィールドがフォーカスを持ち、ユーザーが F1 を押したときにメッセージボックスに表示されるテキストのソースです。

<br />

*** ** * ** ***

false に設定すると、ヘルプテキストは適用されません。

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


フォームフィールドに関連付けられたヘルプテキストを取得または設定します、
フォームフィールドがフォーカスを持ち、ユーザーが F1 を押したときにメッセージボックスに表示されるテキストのソースです。

<br />

*** ** * ** ***

false に設定すると、ヘルプテキストは適用されません。

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


テキスト入力を表すフォームフィールドの値を取得または設定します。


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


テキスト入力を表すフォームフィールドの値を取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


フォームフィールドの入力の最大長さを取得または設定します。


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


フォームフィールドの入力の最大長さを取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

