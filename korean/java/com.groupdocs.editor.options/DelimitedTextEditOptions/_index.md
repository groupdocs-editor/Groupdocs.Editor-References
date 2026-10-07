---
title: "DelimitedTextEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "텍스트 기반 스프레드시트 문서(CSV, 탭 기반 등)를 로드하기 위한 옵션으로, 구분자를 사용합니다"
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

텍스트 기반 스프레드시트 문서(CSV, 탭 기반 등)를 로드하기 위한 옵션,
구분자(구분자)를 사용하는


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | 필수 구분자를 사용하여 구분 텍스트 옵션 클래스의 인스턴스를 생성합니다 |
구분자 (구분자)
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | 텍스트 기반에 대한 문자열 구분자(구분자)를 지정할 수 있습니다 |
스프레드시트 문서
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | 텍스트 기반에 대한 문자열 구분자(구분자)를 지정할 수 있습니다 |
스프레드시트 문서
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | 텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다 |
문서가 날짜 데이터로 변환됩니다.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | 텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다 |
문서가 날짜 데이터로 변환됩니다.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | 텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다 |
문서가 숫자 데이터로 변환됩니다.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | 텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다 |
문서가 숫자 데이터로 변환됩니다.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | 연속된 구분자를 하나로 처리할지 여부를 정의합니다. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | 연속된 구분자를 하나로 처리할지 여부를 정의합니다. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | 입력 문서 처리 중 메모리 최적화 메커니즘을 활성화합니다, |
특정 경우 성능이 저하될 수 있지만, 반면에
메모리 사용량을 감소시킵니다.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | 입력 문서 처리 중 메모리 최적화 메커니즘을 활성화합니다, |
특정 경우 성능이 저하될 수 있지만, 반면에
메모리 사용량을 감소시킵니다.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


필수 구분자를 사용하여 구분 텍스트 옵션 클래스의 인스턴스를 생성합니다
구분자 (구분자)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 구분자 | java.lang.String | NULL이거나 비어 있을 수 없는 필수 구분자(구분자) |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


텍스트 기반에 대한 문자열 구분자(구분자)를 지정할 수 있습니다
스프레드시트 문서


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


텍스트 기반에 대한 문자열 구분자(구분자)를 지정할 수 있습니다
스프레드시트 문서


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다
문서가 날짜 데이터로 변환됩니다. 기본값은 false입니다.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다
문서가 날짜 데이터로 변환됩니다. 기본값은 false입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다
문서가 숫자 데이터로 변환됩니다. 기본값은 false입니다.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


텍스트 기반 문자열이 ...인지 여부를 나타내는 값을 가져오거나 설정합니다
문서가 숫자 데이터로 변환됩니다. 기본값은 false입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


연속된 구분자를 하나로 처리할지 여부를 정의합니다. By
기본값은 false입니다.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


연속된 구분자를 하나로 처리할지 여부를 정의합니다. By
기본값은 false입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

