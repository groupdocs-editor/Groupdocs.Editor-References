---
title: "DropDownFormField"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "ドロップダウンリストを表示するフォームフィールドを表します"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

ドロップダウンリストを表示するフォームフィールドを表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | 指定されたスタイルシートと名前で、[DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) クラスの新しいインスタンスを初期化します。 |
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
|  | [getSelectedIndex()](#getSelectedIndex--) | ドロップダウン リストで選択された項目のインデックスを取得または設定します。 |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | ドロップダウン リストで選択された項目のインデックスを取得または設定します。 |
|
|  | [getType()](#getType--) | このクラスのフォーム フィールドのタイプを取得します。このタイプは常に FormFieldType.DropDown です。 |
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
|  | [getValue()](#getValue--) | ドロップダウン リストのオプション一覧を表すフォーム フィールドの値を取得または設定します。 |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | ドロップダウン リストのオプション一覧を表すフォーム フィールドの値を取得または設定します。 |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


指定されたスタイルシートと名前で、[DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) クラスの新しいインスタンスを初期化します。


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
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


ドロップダウン リストで選択された項目のインデックスを取得または設定します。


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


ドロップダウン リストで選択された項目のインデックスを取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getType() {#getType--}
```
public final int getType()
```


このクラスのフォーム フィールドのタイプを取得します。このタイプは常に FormFieldType.DropDown です。


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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
public final List<String> getValue()
```


ドロップダウン リストのオプション一覧を表すフォーム フィールドの値を取得または設定します。


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


ドロップダウン リストのオプション一覧を表すフォーム フィールドの値を取得または設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<java.lang.String> |  |

