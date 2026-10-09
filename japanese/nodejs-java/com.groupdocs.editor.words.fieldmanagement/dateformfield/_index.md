---
title: "DateFormField"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "日付を表示するフォームフィールドを表します"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.words.fieldmanagement/dateformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DateFormField implements IFormField
```

日付を表示するフォームフィールドを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DateFormField(String stylesheet, String name)](#DateFormField-java.lang.String-java.lang.String-) | 指定されたスタイルシートと名前で、[DateFormField](../../com.groupdocs.editor.words.fieldmanagement/dateformfield) クラスの新しいインスタンスを初期化します。 |
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
|  | [getType()](#getType--) | このクラスのフォーム フィールドのタイプを取得します。このタイプは常に FormFieldType.Date です。 |
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
|  | [getValue()](#getValue--) | 日付を表すフォーム フィールドの値を取得または設定します。 |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | 日付を表すフォーム フィールドの値を取得または設定します。 |
|
### DateFormField(String stylesheet, String name) {#DateFormField-java.lang.String-java.lang.String-}
```
public DateFormField(String stylesheet, String name)
```


指定されたスタイルシートと名前で、[DateFormField](../../com.groupdocs.editor.words.fieldmanagement/dateformfield) クラスの新しいインスタンスを初期化します。


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


このクラスのフォーム フィールドのタイプを取得します。このタイプは常に FormFieldType.Date です。


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
>  dateField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dateField.LocaleId = new CultureInfo("en-US").LCID;
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
public final Date getValue()
```


日付を表すフォーム フィールドの値を取得または設定します。


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


日付を表すフォーム フィールドの値を取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

