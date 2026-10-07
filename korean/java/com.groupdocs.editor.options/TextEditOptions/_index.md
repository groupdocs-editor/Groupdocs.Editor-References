---
title: "TextEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "일반 텍스트 TXT 문서를 로드하기 위한 사용자 지정 옵션을 지정할 수 있습니다"
type: docs
weight: 39
url: /ko/java/com.groupdocs.editor.options/texteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class TextEditOptions implements IEditOptions
```

일반 텍스트(TXT) 문서를 로드하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextEditOptions()](#TextEditOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | 텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다 |
열기
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다 |
열기
|
|  | [getRecognizeLists()](#getRecognizeLists--) | 문서가 번호 매긴 목록 항목을 인식하는 방식을 지정할 수 있습니다 |
일반 텍스트 형식에서 가져올 때.
|
|  | [setRecognizeLists(boolean value)](#setRecognizeLists-boolean-) | 문서가 번호 매긴 목록 항목을 인식하는 방식을 지정할 수 있습니다 |
일반 텍스트 형식에서 가져올 때.
|
|  | [getLeadingSpaces()](#getLeadingSpaces--) | 선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
|
|  | [setLeadingSpaces(int value)](#setLeadingSpaces-int-) | 선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
|
|  | [getTrailingSpaces()](#getTrailingSpaces--) | 후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
|
|  | [setTrailingSpaces(int value)](#setTrailingSpaces-int-) | 후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. |
|
|  | [getEnablePagination()](#getEnablePagination--) | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [getDirection()](#getDirection--) | 입력 일반 텍스트에서 텍스트 흐름 방향을 지정할 수 있습니다 |
문서.
|
|  | [setDirection(int value)](#setDirection-int-) | 입력 일반 텍스트에서 텍스트 흐름 방향을 지정할 수 있습니다 |
문서.
|
### TextEditOptions() {#TextEditOptions--}
```
public TextEditOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다
열기


**Returns:**
java.nio.charset.Charset
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다
열기


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### getRecognizeLists() {#getRecognizeLists--}
```
public final boolean getRecognizeLists()
```


문서가 번호 매긴 목록 항목을 인식하는 방식을 지정할 수 있습니다
일반 텍스트 형식에서 가져옵니다. 기본값은 true입니다.


*** ** * ** ***

이 옵션이 false로 설정된 경우, 목록 인식 알고리즘은 목록 번호가 마침표, 오른쪽 대괄호 또는 글머리 기호(예: "\\u2022", "\*", "-" 또는 "o")로 끝날 때 목록 단락을 감지합니다. 이 옵션이 true로 설정된 경우, 공백도 목록 번호 구분 기호로 사용됩니다: 아라비아식 번호 매기기(1., 1.1.2.)에 대한 목록 인식 알고리즘은 공백과 마침표(".") 기호를 모두 사용합니다.

<br />



**Returns:**
boolean
### setRecognizeLists(boolean value) {#setRecognizeLists-boolean-}
```
public final void setRecognizeLists(boolean value)
```


문서가 번호 매긴 목록 항목을 인식하는 방식을 지정할 수 있습니다
일반 텍스트 형식에서 가져옵니다. 기본값은 true입니다.


*** ** * ** ***

이 옵션이 false로 설정된 경우, 목록 인식 알고리즘은 목록 번호가 마침표, 오른쪽 대괄호 또는 글머리 기호(예: "\\u2022", "\*", "-" 또는 "o")로 끝날 때 목록 단락을 감지합니다. 이 옵션이 true로 설정된 경우, 공백도 목록 번호 구분 기호로 사용됩니다: 아라비아식 번호 매기기(1., 1.1.2.)에 대한 목록 인식 알고리즘은 공백과 마침표(".") 기호를 모두 사용합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getLeadingSpaces() {#getLeadingSpaces--}
```
public final int getLeadingSpaces()
```


선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은
선행 공백을 왼쪽 들여쓰기로 변환합니다.


**Returns:**
int
### setLeadingSpaces(int value) {#setLeadingSpaces-int-}
```
public final void setLeadingSpaces(int value)
```


선행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은
선행 공백을 왼쪽 들여쓰기로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTrailingSpaces() {#getTrailingSpaces--}
```
public final int getTrailingSpaces()
```


후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은
모든 후행 공백을 잘라냅니다.


**Returns:**
int
### setTrailingSpaces(int value) {#setTrailingSpaces-int-}
```
public final void setTrailingSpaces(int value)
```


후행 공백 처리에 대한 기본 옵션을 가져오거나 설정합니다. 기본값은
모든 후행 공백을 잘라냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본적으로
기본값은 비활성화되어 있습니다 (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본적으로
기본값은 비활성화되어 있습니다 (false).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDirection() {#getDirection--}
```
public final int getDirection()
```


입력 일반 텍스트에서 텍스트 흐름 방향을 지정할 수 있습니다
문서. 기본값은 왼쪽에서 오른쪽으로입니다.


**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


입력 일반 텍스트에서 텍스트 흐름 방향을 지정할 수 있습니다
문서. 기본값은 왼쪽에서 오른쪽으로입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

