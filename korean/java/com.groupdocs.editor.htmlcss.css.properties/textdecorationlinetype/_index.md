---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor for Java API 참조"
description: "텍스트 장식선 종류인 underline, underscore, overline, line-through(취소선)을 나타냅니다"
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

텍스트 장식선 유형을 나타냅니다: underline(밑줄), overline(윗줄), line-through(취소선).

<br />

*** ** * ** ***

불변 구조체. https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line와 유사합니다

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [None](#None) | 텍스트 장식이 없습니다. |
|
|  | [Underline](#Underline) | 각 텍스트 라인에 밑줄이 그어집니다. |
|
|  | [Overline](#Overline) | 각 텍스트 라인 위에 선이 있습니다. |
|
|  | [LineThrough](#LineThrough) | 각 텍스트 라인 중간에 선이 있습니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 이 인스턴스에 초기값이 있는지 여부를 나타냅니다 \\u2014 없음 |
|
|  | [isUnderline()](#isUnderline--) | 밑줄(언더스코어)이 활성화되어 있는지 여부를 나타냅니다 |
|
|  | [isOverline()](#isOverline--) | 오버라인이 활성화되어 있는지 여부를 나타냅니다 |
|
|  | [isLineThrough()](#isLineThrough--) | 취소선(스트라이크스루)이 활성화되어 있는지 여부를 나타냅니다 |
|
|  | [getValue()](#getValue--) | 이 인스턴스의 모든 플래그 값을 텍스트로 반환합니다 |
|
|  | [toString()](#toString--) | 이 인스턴스의 모든 플래그 값을 텍스트로 반환합니다 |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 이 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스가 지정된 것과 같은지 여부를 나타냅니다 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 이 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스가 지정된 형변환되지 않은 것과 같은지 여부를 나타냅니다 |
|
|  | [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다 |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 두 "TextDecorationLineType" 값이 같은지 확인합니다 |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 두 "TextDecorationLineType" 값이 다른지 확인합니다 |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | 지정된 매개변수에 의해 정의된 플래그를 사용하여 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스를 생성하고 반환합니다 |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | 지정된 문자열을 구문 분석하고 유효한 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스를 반환하려고 시도합니다 |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 두 지정된 라인 유형을 결합(병합)하여 플래그가 병합(합집합)된 새로운 결과 라인 유형을 생성합니다 |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 두 번째 지정된 라인 유형을 첫 번째 지정된 라인 유형에서 빼고, 두 번째 피연산자에 없는 첫 번째 피연산자의 플래그만 포함된 새로운 결과 라인 유형을 생성합니다 (차집합) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 첫 번째와 두 번째 라인 유형 사이의 교집합을 반환하며, 두 피연산자 모두에서 동시에 활성화된 플래그만 활성화됩니다. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | 특정 바이트(8비트 옥텟)를 해당 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)으로 변환하고, 변환이 유효하지 않으면 예외를 발생시킵니다 |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


텍스트 장식이 없습니다. 초기값.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


각 텍스트 라인에 밑줄이 그어집니다.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


각 텍스트 라인 위에 선이 있습니다.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


각 텍스트 라인 중간에 선이 있습니다.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


이 인스턴스에 초기값이 있는지 여부를 나타냅니다 \\u2014 없음


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


밑줄(언더스코어)이 활성화되어 있는지 여부를 나타냅니다


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


오버라인이 활성화되어 있는지 여부를 나타냅니다


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


취소선(스트라이크스루)이 활성화되어 있는지 여부를 나타냅니다


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


이 인스턴스의 모든 플래그 값을 텍스트로 반환합니다


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


이 인스턴스의 모든 플래그 값을 텍스트로 반환합니다


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


이 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스가 지정된 것과 같은지 여부를 나타냅니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 다른 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스 |
|

**Returns:**
boolean -  같으면 true, 그렇지 않으면 false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


이 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스가 지정된 형변환되지 않은 것과 같은지 여부를 나타냅니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | java.lang.Object | 다른 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스, 객체로 형변환된 |
|

**Returns:**
boolean -  같으면 true, 그렇지 않으면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다


**Returns:**
int - 부호 있는 정수 해시 코드

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


두 "TextDecorationLineType" 값이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 확인할 첫 번째 피연산자 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 검사할 두 번째 피연산자 |
|

**Returns:**
boolean -  같으면 true, 그렇지 않으면 false

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


두 "TextDecorationLineType" 값이 다른지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 확인할 첫 번째 피연산자 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 검사할 두 번째 피연산자 |
|

**Returns:**
boolean -  서로 다르면 true, 그렇지 않으면 false

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


지정된 매개변수에 의해 정의된 플래그를 사용하여 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스를 생성하고 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | isUnderline | boolean | 밑줄 플래그가 활성화되어 있는지 여부를 결정합니다 |
|
|  | isOverline | boolean | 오버라인 플래그가 활성화되어 있는지 여부를 결정합니다 |
|
|  | isLineThrough | boolean | 취소선 플래그가 활성화되어 있는지 여부를 결정합니다 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


지정된 문자열을 구문 분석하고 유효한 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) 인스턴스를 반환하려고 시도합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 입력 | java.lang.String | 입력 문자열 |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 결과. 구문 분석이 유효하지 않으면 #None.None 값입니다 |
|

**Returns:**
boolean -  구문 분석에 성공하면 true, 실패하면 false

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


두 지정된 라인 유형을 결합(병합)하여 플래그가 병합(합집합)된 새로운 결과 라인 유형을 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 첫 번째 라인 유형 피연산자 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 두 번째 라인 유형 피연산자 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


두 번째 지정된 라인 유형을 첫 번째 지정된 라인 유형에서 빼고, 두 번째 피연산자에 없는 첫 번째 피연산자의 플래그만 포함된 새로운 결과 라인 유형을 생성합니다 (차집합)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 첫 번째 라인 유형 피연산자 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 두 번째 라인 유형 피연산자 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


첫 번째와 두 번째 라인 유형 사이의 교차점을 반환합니다. 두 피연산자 모두에서 동시에 활성화된 플래그만 활성화됩니다. 모든 연산자 중에서 가장 높은 우선순위를 가집니다(합집합 및 차집합보다 높음)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 첫 번째 라인 유형 피연산자 |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | 두 번째 라인 유형 피연산자 |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


특정 바이트(8비트 옥텟)를 해당 [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)으로 변환하고, 변환이 유효하지 않으면 예외를 발생시킵니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 옥텟 | 바이트 | 5개의 선행 비트가 0이고 마지막 3비트가 플래그를 나타내는 8비트 옥텟(비트필드) |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
