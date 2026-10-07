---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "일반 텍스트 TXT 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 41
url: /ko/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

일반 텍스트 (TXT)를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.
문서

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | 텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다 |
저장
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다 |
저장
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | 각 BiDi 실행 앞에 양방향 표시를 추가할지 여부를 지정합니다. |
일반 텍스트 형식으로 내보낼 때.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | 각 BiDi 실행 앞에 양방향 표시를 추가할지 여부를 지정합니다. |
일반 텍스트 형식으로 내보내기
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | 프로그램이 표 레이아웃을 보존하려고 시도할지 여부를 지정합니다. |
일반 텍스트 형식으로 저장할 때.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | 프로그램이 표 레이아웃을 보존하려고 시도할지 여부를 지정합니다. |
일반 텍스트 형식으로 저장할 때.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다
저장


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


텍스트 문서의 문자 인코딩으로, 이는 해당 문서에 적용됩니다
저장


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


각 BiDi 실행 앞에 양방향 표시를 추가할지 여부를 지정합니다.
일반 텍스트 형식으로 내보내기. 기본값은 'false' \\u2014 BiDi 표시를 추가하지 않습니다.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


각 BiDi 실행 앞에 양방향 표시를 추가할지 여부를 지정합니다.
일반 텍스트 형식으로 내보내기


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


프로그램이 표 레이아웃을 보존하려고 시도할지 여부를 지정합니다.
일반 텍스트 형식으로 저장할 때. 기본값은 false입니다.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


프로그램이 표 레이아웃을 보존하려고 시도할지 여부를 지정합니다.
일반 텍스트 형식으로 저장할 때. 기본값은 false입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

