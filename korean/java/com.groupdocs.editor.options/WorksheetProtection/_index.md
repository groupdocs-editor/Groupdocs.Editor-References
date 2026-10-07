---
title: "WorksheetProtection"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지정된 비밀번호와 유형으로 출력 스프레드시트 문서의 워크시트를 수정으로부터 보호할 수 있는 워크시트 보호 옵션을 캡슐화합니다."
type: docs
weight: 49
url: /ko/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

워크시트를 보호할 수 있는 워크시트 보호 옵션을 캡슐화합니다.
출력 스프레드시트 문서에서 지정된 유형의 수정으로부터
지정된 비밀번호로.


*** ** * ** ***

XLSX와 같은 대부분의 스프레드시트 형식은 비밀번호로 워크시트를 편집으로부터 보호할 수 있습니다. 이 클래스는 이러한 보호를 활성화하고 옵션을 지정할 수 있게 합니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | 기본 매개변수로 새 인스턴스를 생성합니다. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | 지정된 워크시트 보호 유형으로 새 인스턴스를 생성하고 |
비밀번호
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | 워크시트 보호 유형을 지정할 수 있습니다. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | 워크시트 보호 유형을 지정할 수 있습니다. |
|
|  | [getPassword()](#getPassword--) | 워크시트를 보호하는 데 사용되는 비밀번호. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 워크시트를 보호하는 데 사용되는 비밀번호. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


기본 매개변수로 새 인스턴스를 생성합니다. 수정되지 않고 전달된 경우
SpreadsheetSaveOptions에 전달되면 워크시트 보호가 적용되지 않습니다.


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


지정된 워크시트 보호 유형으로 새 인스턴스를 생성하고
비밀번호


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | protectionType | int | 워크시트 보호 유형 |
|
|  | 비밀번호 | java.lang.String | 보호를 잠그는 비밀번호 |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


워크시트 보호 유형을 지정할 수 있습니다. 기본값은 'None' -
보호가 적용되지 않습니다.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


워크시트 보호 유형을 지정할 수 있습니다. 기본값은 'None' -
보호가 적용되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


워크시트를 보호하는 데 사용되는 비밀번호. NULL이거나 비어 있는 경우
문자열이면 보호가 적용되지 않습니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


워크시트를 보호하는 데 사용되는 비밀번호. NULL이거나 비어 있는 경우
문자열이면 보호가 적용되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

