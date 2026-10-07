---
title: "InvalidFormField"
second_title: "GroupDocs.Editor for Java API 참조"
description: "FormFieldManager.FixInvalidFormFieldNames 작업 중에 잘못된 양식 필드 이름의 업데이트를 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

잘못된 양식 필드 이름을 업데이트하는 동안
FormFieldManager.FixInvalidFormFieldNames
작업.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | 지정된 이름을 사용하여 [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 외부에서 수정할 수 없는 양식 필드의 원래 이름을 가져옵니다. |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | 수리 후 양식 필드의 새 이름을 가져오거나 설정합니다. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | 수리 후 양식 필드의 새 이름을 가져오거나 설정합니다. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


지정된 이름을 사용하여 [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 양식 필드의 원래 이름입니다. |
|

### getName() {#getName--}
```
public final String getName()
```


외부에서 수정할 수 없는 양식 필드의 원래 이름을 가져옵니다.
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


수리 후 양식 필드의 새 이름을 가져오거나 설정합니다.
이 이름은 다른 양식 필드와 중복되는 고유 식별자를 제거하고 고유한 북마크 이름을 설정합니다.

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


수리 후 양식 필드의 새 이름을 가져오거나 설정합니다.
이 이름은 다른 양식 필드와 중복되는 고유 식별자를 제거하고 고유한 북마크 이름을 설정합니다.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

