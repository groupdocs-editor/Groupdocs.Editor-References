---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "XLSX, ODS 등과 같은 바이너리 스프레드시트 셀 Excel 호환 문서를 로드하기 위한 옵션을 포함합니다."
type: docs
weight: 36
url: /ko/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

바이너리 스프레드시트(셀, Excel 호환)를 로드하기 위한 옵션을 포함합니다.
XLS(X), ODS 등과 같은 문서를 Editor 클래스에 로드합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | 기본 매개변수 없는 생성자 - 모든 매개변수는 기본값을 가집니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
스프레드시트 문서를 열 때, 인코딩된 경우.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
스프레드시트 문서를 열 때, 인코딩된 경우.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 입력 문서 처리 중 메모리 최적화 메커니즘을 활성화합니다, |
특정 경우 성능이 저하될 수 있지만, 반면에
메모리 사용량을 감소시킵니다.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 입력 문서 처리 중 메모리 최적화 메커니즘을 활성화합니다, |
특정 경우 성능이 저하될 수 있지만, 반면에
메모리 사용량을 감소시킵니다.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


기본 매개변수 없는 생성자 - 모든 매개변수는 기본값을 가집니다.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
스프레드시트 문서를 열 때, 인코딩된 경우. NULL이거나 비어 있으면 설정합니다
비밀번호를 사용하지 않기 위한 문자열 (기본값).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
스프레드시트 문서를 열 때, 인코딩된 경우. NULL이거나 비어 있으면 설정합니다
비밀번호를 사용하지 않기 위한 문자열 (기본값).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


입력 문서 처리 중 메모리 최적화 메커니즘을 활성화합니다,
특정 경우 성능이 저하될 수 있지만, 반면에
메모리 사용량을 감소시킵니다. 대용량 문서를 처리할 때 유용하며
OutOfMemoryException이 발생할 경우. 기본값은 false이며 (메모리 최적화는
성능 향상을 위해 비활성화되었습니다).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


입력 문서 처리 중 메모리 최적화 메커니즘을 활성화합니다,
특정 경우 성능이 저하될 수 있지만, 반면에
메모리 사용량을 감소시킵니다. 대용량 문서를 처리할 때 유용하며
OutOfMemoryException이 발생할 경우. 기본값은 false이며 (메모리 최적화는
성능 향상을 위해 비활성화되었습니다).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

