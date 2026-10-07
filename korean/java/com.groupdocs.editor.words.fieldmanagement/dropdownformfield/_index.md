---
title: "DropDownFormField"
second_title: "GroupDocs.Editor for Java API 참조"
description: "드롭다운 목록을 표시하는 폼 필드를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.words.fieldmanagement/dropdownformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class DropDownFormField implements IFormField
```

드롭다운 목록을 표시하는 폼 필드를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DropDownFormField(String stylesheet, String name)](#DropDownFormField-java.lang.String-java.lang.String-) | 지정된 스타일시트와 이름을 사용하여 [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) 클래스의 새 인스턴스를 초기화합니다. |
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
|  | [getSelectedIndex()](#getSelectedIndex--) | 드롭다운 목록에서 선택된 항목의 인덱스를 가져오거나 설정합니다. |
|
|  | [setSelectedIndex(int value)](#setSelectedIndex-int-) | 드롭다운 목록에서 선택된 항목의 인덱스를 가져오거나 설정합니다. |
|
|  | [getType()](#getType--) | 이 클래스의 양식 필드 유형을 가져옵니다. 이 유형은 항상 FormFieldType.DropDown입니다. |
|
|  | [getLocaleId()](#getLocaleId--) | 폼 필드와 연결된 문화권 또는 지역 설정을 나타내는 로케일 ID를 가져오거나 설정합니다. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | 폼 필드와 연결된 문화권 또는 지역 설정을 나타내는 로케일 ID를 가져오거나 설정합니다. |
|
|  | [getStatusText()](#getStatusText--) | 양식 필드가 포커스를 가질 때 상태 표시줄에 표시되는 텍스트의 출처인 양식 필드와 연결된 상태 텍스트를 가져오거나 설정합니다. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | 양식 필드가 포커스를 가질 때 상태 표시줄에 표시되는 텍스트의 출처인 양식 필드와 연결된 상태 텍스트를 가져오거나 설정합니다. |
|
|  | [getHelpText()](#getHelpText--) | 폼 필드가 포커스를 가질 때 사용자가 F1을 누르면 메시지 상자에 표시되는 텍스트의 출처인 도움말 텍스트를 가져오거나 설정합니다. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | 폼 필드가 포커스를 가질 때 사용자가 F1을 누르면 메시지 상자에 표시되는 텍스트의 출처인 도움말 텍스트를 가져오거나 설정합니다. |
|
|  | [getValue()](#getValue--) | 양식 필드의 값을 가져오거나 설정합니다. 이 값은 드롭다운 목록의 옵션 목록을 나타냅니다. |
|
|  | [setValue(List<String> value)](#setValue-java.util.List-java.lang.String--) | 양식 필드의 값을 가져오거나 설정합니다. 이 값은 드롭다운 목록의 옵션 목록을 나타냅니다. |
|
### DropDownFormField(String stylesheet, String name) {#DropDownFormField-java.lang.String-java.lang.String-}
```
public DropDownFormField(String stylesheet, String name)
```


지정된 스타일시트와 이름을 사용하여 [DropDownFormField](../../com.groupdocs.editor.words.fieldmanagement/dropdownformfield) 클래스의 새 인스턴스를 초기화합니다.


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
### getSelectedIndex() {#getSelectedIndex--}
```
public final int getSelectedIndex()
```


드롭다운 목록에서 선택된 항목의 인덱스를 가져오거나 설정합니다.


**Returns:**
int
### setSelectedIndex(int value) {#setSelectedIndex-int-}
```
public final void setSelectedIndex(int value)
```


드롭다운 목록에서 선택된 항목의 인덱스를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getType() {#getType--}
```
public final int getType()
```


이 클래스의 양식 필드 유형을 가져옵니다. 이 유형은 항상 FormFieldType.DropDown입니다.


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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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
>  dropDownField.LocaleId = new CultureInfo("en-US").LCID;
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


양식 필드가 포커스를 가질 때 상태 표시줄에 표시되는 텍스트의 출처인 양식 필드와 연결된 상태 텍스트를 가져오거나 설정합니다.

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


양식 필드가 포커스를 가질 때 상태 표시줄에 표시되는 텍스트의 출처인 양식 필드와 연결된 상태 텍스트를 가져오거나 설정합니다.

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


폼 필드가 포커스를 가질 때 사용자가 F1을 누르면 메시지 상자에 표시되는 텍스트의 출처인 도움말 텍스트를 가져오거나 설정합니다.

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


폼 필드가 포커스를 가질 때 사용자가 F1을 누르면 메시지 상자에 표시되는 텍스트의 출처인 도움말 텍스트를 가져오거나 설정합니다.

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
public final List<String> getValue()
```


양식 필드의 값을 가져오거나 설정합니다. 이 값은 드롭다운 목록의 옵션 목록을 나타냅니다.


**Returns:**
java.util.List<java.lang.String>
### setValue(List<String> value) {#setValue-java.util.List-java.lang.String--}
```
public final void setValue(List<String> value)
```


양식 필드의 값을 가져오거나 설정합니다. 이 값은 드롭다운 목록의 옵션 목록을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<java.lang.String> |  |

