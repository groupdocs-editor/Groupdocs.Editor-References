---
title: "FormFieldCollection"
second_title: "GroupDocs.Editor for Java API 참조"
description: "폼 필드 컬렉션을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.words.fieldmanagement/formfieldcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FormFieldCollection implements Iterable<IFormField>
```

폼 필드 컬렉션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FormFieldCollection()](#FormFieldCollection--) | 새로운 [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) 클래스 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [iterator()](#iterator--) | 컬렉션을 반복하는 열거자를 반환합니다. |
|
|  | [insert(IFormField field)](#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-) | 컬렉션에 폼 필드를 삽입합니다. |
|
|  | [get(String name)](#get-java.lang.String-) | 지정된 이름을 가진 폼 필드를 가져옵니다. |
|
|  | [<T>getFormField(String name, Class<T> type)](#-T-getFormField-java.lang.String-java.lang.Class-T--) | 지정된 이름 및 유형을 가진 폼 필드를 가져옵니다. |
|
### FormFieldCollection() {#FormFieldCollection--}
```
public FormFieldCollection()
```


새로운 [FormFieldCollection](../../com.groupdocs.editor.words.fieldmanagement/formfieldcollection) 클래스 인스턴스를 초기화합니다.


### iterator() {#iterator--}
```
public Iterator<IFormField> iterator()
```


컬렉션을 반복하는 열거자를 반환합니다.


**Returns:**
java.util.Iterator<com.groupdocs.editor.words.fieldmanagement.IFormField> - 컬렉션을 반복하는 데 사용할 수 있는 열거자입니다.

### insert(IFormField field) {#insert-com.groupdocs.editor.words.fieldmanagement.IFormField-}
```
public void insert(IFormField field)
```


컬렉션에 폼 필드를 삽입합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | field | [IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) | 삽입할 폼 필드입니다. |
|

### get(String name) {#get-java.lang.String-}
```
public IFormField get(String name)
```


지정된 이름을 가진 폼 필드를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 폼 필드의 이름. |
|

**Returns:**
[IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield) - The form field with the specified name, if found; otherwise,  null .

### <T>getFormField(String name, Class<T> type) {#-T-getFormField-java.lang.String-java.lang.Class-T--}
```
public T <T>getFormField(String name, Class<T> type)
```


지정된 이름 및 유형을 가진 폼 필드를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 폼 필드의 이름. |


T
: 폼 필드의 유형입니다.
|
| 유형 | java.lang.Class<T> |  |

**Returns:**
T - 지정된 이름 및 유형을 가진 폼 필드(찾은 경우); 그렇지 않으면 해당 유형의 기본값입니다.

