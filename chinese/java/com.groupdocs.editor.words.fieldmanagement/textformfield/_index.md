---
title: "TextFormField"
second_title: "GroupDocs.Editor for Java API 参考"
description: "表示接受文本输入的表单字段。"
type: docs
weight: 20
url: /zh/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

表示接受文本输入的表单字段。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | 使用指定的样式表和名称初始化 [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | 获取应用于表单字段的样式表。 |
|
|  | [getReadonly()](#getReadonly--) | 获取或设置一个值，指示表单字段是否为只读。 |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | 获取或设置一个值，指示表单字段是否为只读。 |
|
|  | [getName()](#getName--) | 获取表单字段的名称。 |
|
|  | [getType()](#getType--) | 获取表单字段的类型，对于此类始终为 FormFieldType.Text。 |
|
|  | [getLocaleId()](#getLocaleId--) | 获取或设置表单字段的区域设置标识符，表示与表单字段关联的文化或地区设置。 |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | 获取或设置表单字段的区域设置标识符，表示与表单字段关联的文化或地区设置。 |
|
|  | [getStatusText()](#getStatusText--) | 获取或设置与表单字段关联的状态文本， |
当表单字段获得焦点时，在状态栏中显示的文本来源。
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | 获取或设置与表单字段关联的状态文本， |
当表单字段获得焦点时，在状态栏中显示的文本来源。
|
|  | [getHelpText()](#getHelpText--) | 获取或设置与表单字段关联的帮助文本， |
当表单字段获得焦点且用户按下 F1 时，在消息框中显示的文本来源。
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | 获取或设置与表单字段关联的帮助文本， |
当表单字段获得焦点且用户按下 F1 时，在消息框中显示的文本来源。
|
|  | [getValue()](#getValue--) | 获取或设置表单字段的值，该值表示文本输入。 |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | 获取或设置表单字段的值，该值表示文本输入。 |
|
|  | [getMaxLength()](#getMaxLength--) | 获取或设置表单字段输入的最大长度。 |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | 获取或设置表单字段输入的最大长度。 |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


使用指定的样式表和名称初始化 [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 样式表 | java.lang.String | 要应用于表单字段的样式表。 |
|
|  | 名称 | java.lang.String | 表单字段的名称。 |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


获取应用于表单字段的样式表。


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


获取或设置一个值，指示表单字段是否为只读。


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


获取或设置一个值，指示表单字段是否为只读。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


获取表单字段的名称。


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


获取表单字段的类型，对于此类始终为 FormFieldType.Text。


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


获取或设置表单字段的区域设置标识符，表示与表单字段关联的文化或地区设置。

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

LocaleId 属性指定一个区域标识符 (LCID)，该标识符对应特定的文化或地区。

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


获取或设置表单字段的区域设置标识符，表示与表单字段关联的文化或地区设置。

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

LocaleId 属性指定一个区域标识符 (LCID)，该标识符对应特定的文化或地区。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


获取或设置与表单字段关联的状态文本，
当表单字段获得焦点时，在状态栏中显示的文本来源。

<br />

*** ** * ** ***

如果设置为 false，则状态文本将不被应用。

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


获取或设置与表单字段关联的状态文本，
当表单字段获得焦点时，在状态栏中显示的文本来源。

<br />

*** ** * ** ***

如果设置为 false，则状态文本将不被应用。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


获取或设置与表单字段关联的帮助文本，
当表单字段获得焦点且用户按下 F1 时，在消息框中显示的文本来源。

<br />

*** ** * ** ***

如果设置为 false，则帮助文本将不被应用。

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


获取或设置与表单字段关联的帮助文本，
当表单字段获得焦点且用户按下 F1 时，在消息框中显示的文本来源。

<br />

*** ** * ** ***

如果设置为 false，则帮助文本将不被应用。

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


获取或设置表单字段的值，该值表示文本输入。


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


获取或设置表单字段的值，该值表示文本输入。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


获取或设置表单字段输入的最大长度。


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


获取或设置表单字段输入的最大长度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

