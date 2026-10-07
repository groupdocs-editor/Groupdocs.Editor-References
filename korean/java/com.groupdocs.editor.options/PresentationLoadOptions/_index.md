---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "PPTX, PPTM, PPSX 등 지원되는 모든 프레젠테이션 형식의 문서를 로드하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 33
url: /ko/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

지원되는 모든 문서를 로드하기 위한 사용자 지정 옵션을 지정할 수 있습니다
PPT(X), PPTM, PPS(X) 등과 같은 프레젠테이션 형식

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
프레젠테이션 문서를 열 때, 인코딩된 경우
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
프레젠테이션 문서를 열 때, 인코딩된 경우
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
프레젠테이션 문서를 열 때, 인코딩된 경우. NULL 또는 빈 문자열로 설정하십시오
비밀번호를 제거하기 위한 문자열입니다.


*** ** * ** ***

기본적으로 이 속성은 NULL 값을 갖습니다 — 비밀번호가 설정되지 않음. 입력 프레젠테이션 문서가 비밀번호로 보호된 경우 비밀번호가 필수이며, 비밀번호가 지정되지 않았거나 유효하지 않으면 예외가 발생합니다. 입력 프레젠테이션 문서가 비밀번호로 보호되지 않았지만 비밀번호가 설정된 경우 무시됩니다.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
프레젠테이션 문서를 열 때, 인코딩된 경우. NULL 또는 빈 문자열로 설정하십시오
비밀번호를 제거하기 위한 문자열입니다.


*** ** * ** ***

기본적으로 이 속성은 NULL 값을 갖습니다 — 비밀번호가 설정되지 않음. 입력 프레젠테이션 문서가 비밀번호로 보호된 경우 비밀번호가 필수이며, 비밀번호가 지정되지 않았거나 유효하지 않으면 예외가 발생합니다. 입력 프레젠테이션 문서가 비밀번호로 보호되지 않았지만 비밀번호가 설정된 경우 무시됩니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

