---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "DOCX, RTF, ODT 등 Word 호환 문서를 로드하기 위한 옵션을 포함합니다."
type: docs
weight: 45
url: /ko/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

WordProcessing (Word 호환) 문서를 로드하기 위한 옵션을 포함합니다, 예를 들어
DOC(X), RTF, ODT 등을 Editor 클래스에 로드합니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
인코딩된 경우 WordProcessing 문서를 엽니다.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
인코딩된 경우 WordProcessing 문서를 엽니다.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
인코딩된 경우 WordProcessing 문서를 엽니다. NULL 또는 빈 값으로 설정합니다
비밀번호를 사용하지 않기 위한 문자열 (기본값).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
인코딩된 경우 WordProcessing 문서를 엽니다. NULL 또는 빈 값으로 설정합니다
비밀번호를 사용하지 않기 위한 문자열 (기본값).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

