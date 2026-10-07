---
title: "Ratio"
second_title: "GroupDocs.Editor for Java API 참조"
description: "ratio CSS 데이터 유형을 나타내며, 미디어 쿼리에서 종횡비를 설명하고 래스터 이미지에서 분자와 분모라고 하는 두 무단위 값 사이의 비율을 나타내는 데 사용됩니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

\"ratio\" CSS 데이터 유형을 나타내며, 종횡비를 설명하는 데 사용됩니다
미디어 쿼리의 비율 및 래스터 이미지에서 비율을 나타냅니다
\"numerator\"와 \"denominator\"라고 하는 두 무단위 값 사이. 불변
구조체.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Single](#Single) | 단일 기본 비율 1/1 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | 이 비율의 분자를 반환합니다 |
|
|  | [getDenominator()](#getDenominator--) | 이 비율의 분모를 반환합니다 |
|
|  | [calculate()](#calculate--) | 이 비율을 단일 부동 소수점 숫자로 계산하여 반환합니다 |
|
|  | [getInverseRatio()](#getInverseRatio--) | 이 비율에 대한 역(역수) 비율을 생성하고 반환합니다 |
|
|  | [serializeDefault()](#serializeDefault--) | 이 비율을 문자열로 직렬화하고 반환합니다 |
|
|  | [toString()](#toString--) | 이 비율의 문자열 표현을 반환합니다; 동일함 |
\"SerializeDefault()\"
|
|  | [isDefault()](#isDefault--) | 이 비율이 기본값을 가지고 있는지 또는 \"1/1\"(단일)인지 확인합니다 |
|
|  | [deepClone()](#deepClone--) | 이 비율의 전체 복사본을 반환합니다 |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 이 인스턴스가 지정된 \"Ratio\" 인스턴스와 동일한지 확인합니다 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다, |
이는 아마도 다른 \"Ratio\" 인스턴스일 것입니다
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 두 비율을 비교하고 두 비율이 일치하는지 여부를 나타내는 부울 값을 반환합니다. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | 두 비율을 비교하고 두 비율이 일치하지 않는지 여부를 나타내는 부울 값을 반환합니다 |
일치.
|
|  | [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시코드를 반환합니다. 이는 해당 인스턴스의 |
수명
|
|  | [create(int numerator, int denominator)](#create-int-int-) | 지정된 분자와 |
분모
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


단일 기본 비율 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


이 비율의 분자를 반환합니다


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


이 비율의 분모를 반환합니다


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


이 비율을 단일 부동 소수점 숫자로 계산하여 반환합니다


**Returns:**
double - 배정밀도 부동소수점 숫자

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


이 비율에 대한 역(역수) 비율을 생성하고 반환합니다


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


이 비율을 문자열로 직렬화하고 반환합니다


**Returns:**
java.lang.String - "분자/분모" 형식의 문자열

### toString() {#toString--}
```
public String toString()
```


이 비율의 문자열 표현을 반환합니다; 동일함
\"SerializeDefault()\"


**Returns:**
java.lang.String - "분자/분모" 형식의 문자열

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


이 비율이 기본값을 가지고 있는지 또는 \"1/1\"(단일)인지 확인합니다


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


이 비율의 전체 복사본을 반환합니다


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


이 인스턴스가 지정된 \"Ratio\" 인스턴스와 동일한지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 이와 동등성을 확인하기 위한 다른 Ratio 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다,
이는 아마도 다른 \"Ratio\" 인스턴스일 것입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 기타 | java.lang.Object | 이와 동등성을 확인하기 위한 다른 System.Object 인스턴스, 이는 아마 Ratio 유형일 것입니다 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


두 비율을 비교하고 두 비율이 일치하는지 여부를 나타내는 부울 값을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 사용할 첫 번째 비율. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 사용할 두 번째 비율. |
|

**Returns:**
boolean - 두 비율이 동일하면 true, 그렇지 않으면 false.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


두 비율을 비교하고 두 비율이 일치하지 않는지 여부를 나타내는 부울 값을 반환합니다
일치.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 사용할 첫 번째 비율. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | 사용할 두 번째 비율. |
|

**Returns:**
boolean - 두 비율이 동일하지 않으면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시코드를 반환합니다. 이는 해당 인스턴스의
수명


**Returns:**
int - 부호가 있는 4바이트 정수이며, 이 인스턴스에 대해 불변입니다.

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


지정된 분자와
분모


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 분자 | int | 비율의 분자. 양의 정수여야 합니다. |
|
|  | 분모 | int | 비율의 분모. 양의 정수여야 합니다. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

