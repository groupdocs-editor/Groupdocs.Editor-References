---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "구분자를 사용하는 텍스트 기반 스프레드시트 문서(CSV, 탭 기반 등)를 생성하고 저장하기 위한 옵션을 포함합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

텍스트 기반 스프레드시트 문서를 생성하고 저장하기 위한 옵션을 포함합니다.
(CSV, 탭 기반 등), 구분자(구분 기호)를 사용하는


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | 이 매개변수 없는 생성자는 세미콜론 (;)을 기본 구분자로 하여 DelimitedTextSaveOptions의 새 인스턴스를 생성합니다(그 후에 수정 가능). |
구분자
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) 속성)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | 필수 구분자를 사용하여 구분 텍스트 옵션 클래스의 인스턴스를 생성합니다 |
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
|  | [getEncoding()](#getEncoding--) | 텍스트 기반 스프레드시트 문서의 인코딩을 설정할 수 있습니다. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | 텍스트 기반 스프레드시트 문서의 인코딩을 설정할 수 있습니다. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | 선행 빈 행 및 열을 제거할지 여부를 나타냅니다. |
MS Excel이 하는 방식처럼
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | 선행 빈 행 및 열을 제거할지 여부를 나타냅니다. |
MS Excel이 하는 방식처럼
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | 빈 행에 구분자를 출력할지 여부를 나타냅니다. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | 빈 행에 구분자를 출력할지 여부를 나타냅니다. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


이 매개변수 없는 생성자는 세미콜론 (;)을 기본 구분자로 하여 DelimitedTextSaveOptions의 새 인스턴스를 생성합니다(그 후에 수정 가능).
구분자
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) 속성)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


필수 구분자를 사용하여 구분 텍스트 옵션 클래스의 인스턴스를 생성합니다
구분자 (구분자)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 구분자 | java.lang.String | 텍스트 기반 스프레드시트 문서용 문자열 구분자(구분 기호) |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


텍스트 기반에 대한 문자열 구분자(구분자)를 지정할 수 있습니다
스프레드시트 문서


**Returns:**
java.lang.String -
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

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


텍스트 기반 스프레드시트 문서의 인코딩을 설정할 수 있습니다. 기본적으로
기본값(지정되지 않은 경우)은 UTF8입니다.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


텍스트 기반 스프레드시트 문서의 인코딩을 설정할 수 있습니다. 기본적으로
기본값(지정되지 않은 경우)은 UTF8입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


선행 빈 행 및 열을 제거할지 여부를 나타냅니다.
MS Excel이 하는 방식처럼


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


선행 빈 행 및 열을 제거할지 여부를 나타냅니다.
MS Excel이 하는 방식처럼


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


빈 행에 구분자를 출력할지 여부를 나타냅니다. 기본값
값이 false이면 빈 행의 내용이 비게 됩니다.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


빈 행에 구분자를 출력할지 여부를 나타냅니다. 기본값
값이 false이면 빈 행의 내용이 비게 됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

