---
title: "CheckBoxForm"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "チェックボックスを表示するフォームフィールドを表します"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.editor.words.fieldmanagement/checkboxform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CheckBoxForm implements IFormField
```

チェックボックスを表示するフォームフィールドを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [CheckBoxForm(String stylesheet, String name)](#CheckBoxForm-java.lang.String-java.lang.String-) | 指定されたスタイルシートと名前で、[CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) クラスの新しいインスタンスを初期化します。 |
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
|  | [getType()](#getType--) | このクラスのフォーム フィールドのタイプを取得します。このタイプは常に FormFieldType.CheckBox です。 |
|
|  | [getLocaleId()](#getLocaleId--) | フォームフィールドに関連付けられたカルチャまたは地域設定を表すロケール ID を取得または設定します。 |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | フォームフィールドに関連付けられたカルチャまたは地域設定を表すロケール ID を取得または設定します。 |
|
|  | [getStatusText()](#getStatusText--) | フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースである、フォームフィールドに関連付けられたステータステキストを取得または設定します。 |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースである、フォームフィールドに関連付けられたステータステキストを取得または設定します。 |
|
|  | [getHelpText()](#getHelpText--) | フォームフィールドがフォーカスを持ち、ユーザーがF1を押したときにメッセージボックスに表示されるテキストのソースである、フォームフィールドに関連付けられたヘルプテキストを取得または設定します。 |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | フォームフィールドがフォーカスを持ち、ユーザーがF1を押したときにメッセージボックスに表示されるテキストのソースである、フォームフィールドに関連付けられたヘルプテキストを取得または設定します。 |
|
|  | [getValue()](#getValue--) | チェックボックスの状態を表すフォーム フィールドの値を取得または設定します。 |
|
|  | [setValue(boolean value)](#setValue-boolean-) | チェックボックスの状態を表すフォーム フィールドの値を取得または設定します。 |
|
### CheckBoxForm(String stylesheet, String name) {#CheckBoxForm-java.lang.String-java.lang.String-}
```
public CheckBoxForm(String stylesheet, String name)
```


指定されたスタイルシートと名前で、[CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) クラスの新しいインスタンスを初期化します。


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


このクラスのフォーム フィールドのタイプを取得します。このタイプは常に FormFieldType.CheckBox です。


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
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
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
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
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


フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースである、フォームフィールドに関連付けられたステータステキストを取得または設定します。

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


フォームフィールドがフォーカスを持つとステータスバーに表示されるテキストのソースである、フォームフィールドに関連付けられたステータステキストを取得または設定します。

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


フォームフィールドがフォーカスを持ち、ユーザーがF1を押したときにメッセージボックスに表示されるテキストのソースである、フォームフィールドに関連付けられたヘルプテキストを取得または設定します。

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


フォームフィールドがフォーカスを持ち、ユーザーがF1を押したときにメッセージボックスに表示されるテキストのソースである、フォームフィールドに関連付けられたヘルプテキストを取得または設定します。

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
public final boolean getValue()
```


チェックボックスの状態を表すフォーム フィールドの値を取得または設定します。


**Returns:**
ブール
### setValue(boolean value) {#setValue-boolean-}
```
public final void setValue(boolean value)
```


チェックボックスの状態を表すフォーム フィールドの値を取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | ブール |  |

