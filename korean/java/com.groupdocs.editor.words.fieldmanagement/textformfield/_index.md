---
title: "TextFormField"
second_title: "GroupDocs.Editor for Java API 참조"
description: "텍스트 입력을 허용하는 양식 필드를 나타냅니다."
type: docs
weight: 20
url: /ko/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

텍스트 입력을 허용하는 양식 필드를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | 지정된 스타일시트와 이름을 사용하여 새로운 [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) 클래스 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | 폼 필드에 적용된 스타일시트를 가져옵니다. |
|
|  | [getReadonly()](#getReadonly--) | 폼 필드가 읽기 전용인지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | 폼 필드가 읽기 전용인지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [getName()](#getName--) | 폼 필드의 이름을 가져옵니다. |
|
|  | [getType()](#getType--) | 이 클래스에서는 폼 필드 유형을 가져오며, 항상 FormFieldType.Text입니다. |
|
|  | [getLocaleId()](#getLocaleId--) | 폼 필드와 연결된 문화권 또는 지역 설정을 나타내는 로케일 ID를 가져오거나 설정합니다. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | 폼 필드와 연결된 문화권 또는 지역 설정을 나타내는 로케일 ID를 가져오거나 설정합니다. |
|
|  | [getStatusText()](#getStatusText--) | 폼 필드와 연결된 상태 텍스트를 가져오거나 설정합니다, |
폼 필드가 포커스를 받을 때 상태 표시줄에 표시되는 텍스트의 원본입니다.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | 폼 필드와 연결된 상태 텍스트를 가져오거나 설정합니다, |
폼 필드가 포커스를 받을 때 상태 표시줄에 표시되는 텍스트의 원본입니다.
|
|  | [getHelpText()](#getHelpText--) | 폼 필드와 연결된 도움말 텍스트를 가져오거나 설정합니다, |
폼 필드가 포커스를 받고 사용자가 F1을 누를 때 메시지 상자에 표시되는 텍스트의 원본입니다.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | 폼 필드와 연결된 도움말 텍스트를 가져오거나 설정합니다, |
폼 필드가 포커스를 받고 사용자가 F1을 누를 때 메시지 상자에 표시되는 텍스트의 원본입니다.
|
|  | [getValue()](#getValue--) | 폼 필드의 값을 가져오거나 설정합니다. 이 값은 텍스트 입력을 나타냅니다. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | 폼 필드의 값을 가져오거나 설정합니다. 이 값은 텍스트 입력을 나타냅니다. |
|
|  | [getMaxLength()](#getMaxLength--) | 폼 필드 입력의 최대 길이를 가져오거나 설정합니다. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | 폼 필드 입력의 최대 길이를 가져오거나 설정합니다. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


지정된 스타일시트와 이름을 사용하여 새로운 [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) 클래스 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스타일시트 | java.lang.String | 폼 필드에 적용할 스타일시트. |
|
|  | name | java.lang.String | 폼 필드의 이름. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


폼 필드에 적용된 스타일시트를 가져옵니다.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


폼 필드가 읽기 전용인지 여부를 나타내는 값을 가져오거나 설정합니다.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


폼 필드가 읽기 전용인지 여부를 나타내는 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


폼 필드의 이름을 가져옵니다.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


이 클래스에서는 폼 필드 유형을 가져오며, 항상 FormFieldType.Text입니다.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


폼 필드와 연결된 문화권 또는 지역 설정을 나타내는 로케일 ID를 가져오거나 설정합니다.

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

LocaleId 속성은 특정 문화 또는 지역에 해당하는 로케일 식별자(LCID)를 지정합니다.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


폼 필드와 연결된 문화권 또는 지역 설정을 나타내는 로케일 ID를 가져오거나 설정합니다.

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

LocaleId 속성은 특정 문화 또는 지역에 해당하는 로케일 식별자(LCID)를 지정합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


폼 필드와 연결된 상태 텍스트를 가져오거나 설정합니다,
폼 필드가 포커스를 받을 때 상태 표시줄에 표시되는 텍스트의 원본입니다.

<br />

*** ** * ** ***

false 로 설정하면 상태 텍스트가 적용되지 않습니다.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


폼 필드와 연결된 상태 텍스트를 가져오거나 설정합니다,
폼 필드가 포커스를 받을 때 상태 표시줄에 표시되는 텍스트의 원본입니다.

<br />

*** ** * ** ***

false 로 설정하면 상태 텍스트가 적용되지 않습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


폼 필드와 연결된 도움말 텍스트를 가져오거나 설정합니다,
폼 필드가 포커스를 받고 사용자가 F1을 누를 때 메시지 상자에 표시되는 텍스트의 원본입니다.

<br />

*** ** * ** ***

false 로 설정하면 도움말 텍스트가 적용되지 않습니다.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


폼 필드와 연결된 도움말 텍스트를 가져오거나 설정합니다,
폼 필드가 포커스를 받고 사용자가 F1을 누를 때 메시지 상자에 표시되는 텍스트의 원본입니다.

<br />

*** ** * ** ***

false 로 설정하면 도움말 텍스트가 적용되지 않습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


폼 필드의 값을 가져오거나 설정합니다. 이 값은 텍스트 입력을 나타냅니다.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


폼 필드의 값을 가져오거나 설정합니다. 이 값은 텍스트 입력을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


폼 필드 입력의 최대 길이를 가져오거나 설정합니다.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


폼 필드 입력의 최대 길이를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

