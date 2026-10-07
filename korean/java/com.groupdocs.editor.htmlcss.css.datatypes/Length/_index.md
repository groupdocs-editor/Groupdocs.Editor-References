---
title: "길이"
second_title: "GroupDocs.Editor for Java API 참조"
description: "CSS 길이 값을 백분율 및 단위 없는 유형을 포함한 모든 지원 단위로 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

CSS 길이 값을 백분율을 포함한 모든 지원 단위로 나타냅니다.
그리고 단위 없는 유형. 값은 정수 또는 부동소수점, 음수, 0 및
양수. 불변 구조.

*** ** * ** ***


이 유형은 다음 CSS 데이터 유형을 포함합니다:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Length()](#Length--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | 단위 없는 정수 0 - 기본값, 기본 매개변수 없는 경우와 동일합니다 |
생성자
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | 지정된 부동소수점 숫자로 Length 유형의 인스턴스를 생성하고 반환합니다 |
및 단위
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | 지정된 double 숫자로 Length 유형의 인스턴스를 생성하고 반환합니다 |
및 단위
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | 지정된 정수로 Length 유형의 인스턴스를 생성하고 반환합니다 |
숫자 및 단위
|
|  | [isUnitlessZero()](#isUnitlessZero--) | 이 인스턴스가 단위 없는 0인지 여부를 판단합니다. |
|
|  | [isDefault()](#isDefault--) | 이 Length 인스턴스가 기본값 \u2014 단위 없는지를 나타냅니다 |
0.
|
|  | [getUnitType()](#getUnitType--) | 이 Length 인스턴스의 단위 유형을 반환합니다. |
|
|  | [isInteger()](#isInteger--) | 이 Length 인스턴스의 숫자 값이 |
원래 정수(INT32) 숫자로 지정되어 저장되었습니다
|
|  | [isFloat()](#isFloat--) | 이 Length 인스턴스의 숫자 값이 |
원래 부동소수점(FP32) 숫자로 지정되어 저장되었습니다
|
|  | [getFloatValue()](#getFloatValue--) | Length 인스턴스의 부동소수점 숫자 값을 반환합니다. |
|
|  | [getIntegerValue()](#getIntegerValue--) | 이 Length 인스턴스의 정수 숫자 값을 반환합니다, 만약 |
내부적으로 정수로 저장되어 있거나, 그렇다면 예외를 발생시킵니다
원래 부동소수점 숫자로 저장되었습니다.
|
|  | [isAbsolute()](#isAbsolute--) | 길이가 절대 단위로 주어졌는지 가져옵니다. |
|
|  | [isRelative()](#isRelative--) | 길이가 상대 단위로 주어졌는지 가져옵니다. |
|
|  | [isZero()](#isZero--) | 이 길이의 숫자 값이 0인지 여부를 판단합니다 |
|
|  | [isNegative()](#isNegative--) | 이 길이의 숫자 값이 음수인지 여부를 판단합니다 |
|
|  | [isPositive()](#isPositive--) | 이 길이의 숫자 값이 양수인지 여부를 결정합니다. |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | 값은 단위가 없는 유형이지만, 0이 아니며 양수 또는 음수입니다. |
number
|
|  | [toPixel()](#toPixel--) | 가능한 경우 길이를 픽셀 수로 변환합니다. |
|
|  | [to(int unit)](#to-int-) | 가능한 경우 길이를 지정된 단위로 변환합니다. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | 지정된 단위 유형으로 이 길이의 문자열 표현을 반환합니다. |
|
|  | [serializeDefault()](#serializeDefault--) | 이 길이의 원래 네이티브 형태로 문자열 표현을 반환합니다 |
형식(저장된 그대로), 길이 값을 다른 단위로 변환하지 않고
단위 유형
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 이 값이 다른 지정된 길이와 같은지 여부를 정의합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 길이가 지정된 객체와 같은지 여부를 결정합니다. |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | 주어진 Length를 지정된 계수에 곱합니다. |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 두 주어진 길이의 동등성을 확인합니다. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 두 주어진 길이의 부등호를 확인합니다. |
|
|  | [hashCode()](#hashCode--) | 이 Length 인스턴스의 해시 코드를 결합하여 계산하고 반환합니다. |
값과 단위 유형의 해시 코드
|
|  | [deepClone()](#deepClone--) | 이 Length 인스턴스의 전체 복사본을 반환합니다. |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | 지정된 단위 이름을 구문 분석하고 해당 값을 반환하려고 시도합니다. |
Unit 열거형.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | 지정된 문자열을 Length 값으로 구문 분석하려고 시도합니다(그 안에 포함된 |
숫자 값과 단위 이름
|
|  | [parse(String input)](#parse-java.lang.String-) | 지정된 문자열을 Length 값으로 구문 분석하고 반환합니다(그 안에 포함된 |
숫자 값과 단위 이름을 포함하거나, 실패 시 예외를 발생시킵니다.
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


단위 없는 정수 0 - 기본값, 기본 매개변수 없는 경우와 동일합니다
생성자


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


지정된 부동소수점 숫자로 Length 유형의 인스턴스를 생성하고 반환합니다
및 단위


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | float | \>모든 부동 소수점(FP32) 숫자 |
|
|  | 단위 | int | 유효한 단위 유형 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


지정된 double 숫자로 Length 유형의 인스턴스를 생성하고 반환합니다
및 단위


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | double | float(FP32)으로 변환될 모든 double(FP64) 숫자 |
|
|  | 단위 | int | 유효한 단위 유형 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


지정된 정수로 Length 유형의 인스턴스를 생성하고 반환합니다
숫자 및 단위


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int | 모든 정수 |
|
|  | 단위 | int | 유효한 단위 유형 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


이 인스턴스가 단위 없는 0인지 여부를 결정합니다. 단위 없는 0
이 유형의 기본값입니다. IsDefault 속성과 동일합니다.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


이 Length 인스턴스가 기본값 \u2014 단위 없는지를 나타냅니다
0입니다. IsUnitlessZero 속성과 동일합니다.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


이 Length 인스턴스의 단위 유형을 반환합니다.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


이 Length 인스턴스의 숫자 값이
원래 정수(INT32) 숫자로 지정되어 저장되었습니다


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


이 Length 인스턴스의 숫자 값이
원래 부동소수점(FP32) 숫자로 지정되어 저장되었습니다


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Length 인스턴스의 float 숫자 값을 반환합니다. 절대 예외를 발생시키지 않습니다
예외 - 필요에 따라 Integer 값을 Float로 변환합니다.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


이 Length 인스턴스의 정수 숫자 값을 반환합니다, 만약
내부적으로 정수로 저장되어 있거나, 그렇다면 예외를 발생시킵니다
원래 부동소수점 숫자로 저장되었습니다.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


길이가 절대 단위로 지정되었는지 가져옵니다. 이러한 길이는
픽셀로 변환될 수 있습니다.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


길이가 상대 단위로 지정되었는지 가져옵니다. 이러한 길이는
픽셀로 변환될 수 있습니다.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


이 길이의 숫자 값이 0인지 여부를 판단합니다


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


이 길이의 숫자 값이 음수인지 여부를 판단합니다


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


이 길이의 숫자 값이 양수인지 여부를 결정합니다.


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


값은 단위가 없는 유형이지만, 0이 아니며 양수 또는 음수입니다.
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


가능한 경우 길이를 픽셀 수로 변환합니다. 현재
단위가 상대적이면 예외가 발생합니다.


**Returns:**
float - 현재 길이가 나타내는 픽셀 수.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


가능한 경우 길이를 지정된 단위로 변환합니다. 현재 또는
지정된 단위가 상대적이면 예외가 발생합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 단위 | int | 변환할 단위. |
|

**Returns:**
float - 현재 길이의 지정된 단위 값.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


지정된 단위 유형으로 이 길이의 문자열 표현을 반환합니다.
숫자 값은 단위 유형 변경에 따라 변환됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 단위 | int | 문자열로 직렬화하기 전에 이 인스턴스를 변환해야 할 지정된 단위입니다. 유효해야 하며, 단위 없는 값일 수 없습니다. |
|

**Returns:**
java.lang.String - 문자열 표현

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


이 길이의 원래 네이티브 형태로 문자열 표현을 반환합니다
형식(저장된 그대로), 길이 값을 다른 단위로 변환하지 않고
단위 유형


**Returns:**
java.lang.String - 문자열 인스턴스

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


이 값이 다른 지정된 길이와 같은지 여부를 정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length 유형의 다른 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 길이가 지정된 객체와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | System.Object 또는 기타 추상 타입이나 인터페이스에 박싱된 Length 유형의 다른 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


주어진 Length를 지정된 계수에 곱합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - 곱셈인자 |
|
|  | 인자 | int | 임의 정수 - 인자 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


두 주어진 길이의 동등성을 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 왼쪽 길이 피연산자. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 오른쪽 길이 피연산자. |
|

**Returns:**
boolean - 두 길이가 같으면 true, 그렇지 않으면 false.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


두 주어진 길이의 부등호를 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 왼쪽 길이 피연산자. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 오른쪽 길이 피연산자. |
|

**Returns:**
boolean - 두 길이가 다르면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 Length 인스턴스의 해시 코드를 결합하여 계산하고 반환합니다.
값과 단위 유형의 해시 코드


**Returns:**
int - 정수

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


이 Length 인스턴스의 전체 복사본을 반환합니다.


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


지정된 단위 이름을 구문 분석하고 해당 값을 반환하려고 시도합니다.
Unit 열거형. 적절한 LengthUnit을 찾을 수 없으면 LengthUnit.Unitless를 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | unitName | java.lang.String | String, 단위 이름을 나타내는 문자열 |
|

**Returns:**
int - Unit 열거형의 값, 적절한 단위를 찾을 수 없을 때는 LengthUnit.Unitless

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


지정된 문자열을 Length 값으로 구문 분석하려고 시도합니다(그 안에 포함된
숫자 값과 단위 이름


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 입력 | java.lang.String | 입력 문자열, 구문 분석해야 함 |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 출력 매개변수, 구문 분석 결과를 포함합니다. 구문 분석에 실패하면 기본 Length 값 \\u2014 단위 없는 0을 포함합니다. |
|

**Returns:**
boolean - 구문 분석이 성공하면 true, 실패하면 false

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


지정된 문자열을 Length 값으로 구문 분석하고 반환합니다(그 안에 포함된
숫자 값과 단위 이름을 포함하거나, 실패 시 예외를 발생시킵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 입력 | java.lang.String | 입력 문자열, 구문 분석해야 함 |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

