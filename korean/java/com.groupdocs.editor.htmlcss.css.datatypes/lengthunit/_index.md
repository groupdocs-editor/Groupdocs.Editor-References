---
title: "LengthUnit"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 길이 단위"
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

지원되는 모든 길이 단위


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - 정의된 길이 단위가 없음. |
|
|  | [Px](#Px) | 픽셀. |
|
|  | [Em](#Em) | Em. |
|
|  | [Ex](#Ex) | Ex (x-길이). |
|
|  | [Cm](#Cm) | Cm. |
|
|  | [Mm](#Mm) | Mm. |
|
|  | [In](#In) | In. |
|
|  | [Pt](#Pt) | Pt. |
|
|  | [Pc](#Pc) | Pc. |
|
|  | [Ch](#Ch) | Ch. |
|
|  | [Rem](#Rem) | Rem. |
|
|  | [Vw](#Vw) | Vw - 뷰포트 너비. |
|
|  | [Vh](#Vh) | Vh - 뷰포트 높이. |
|
|  | [Vmin](#Vmin) | Vmin. |
|
|  | [Vmax](#Vmax) | Vmax. |
|
|  | [Percent](#Percent) | 값은 고정된 (외부) 값에 상대적이며, 이는 컨텍스트 |
종속적.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


단위 없음 - 정의된 길이 단위가 없습니다. 기본값.


### Px {#Px}
```
public static final int Px
```


픽셀. 보기 장치에 상대적입니다. 화면 표시의 경우 일반적으로
디스플레이의 한 장치 픽셀(점)입니다.


### Em {#Em}
```
public static final int Em
```


Em. 이 단위는 요소의 계산된 글꼴 크기를 나타냅니다.


### Ex {#Ex}
```
public static final int Ex
```


Ex (x-길이). 이 단위는 요소의 x-높이를 나타냅니다
글꼴. 'x' 문자가 있는 글꼴에서 일반적으로 높이는
소문자 높이; 많은 글꼴에서 1ex \\u2248 0.5em.


### Cm {#Cm}
```
public static final int Cm
```


Cm. 1센티미터(10밀리미터).


### Mm {#Mm}
```
public static final int Mm
```


Mm. 1밀리미터.


### In {#In}
```
public static final int In
```


In. 1인치(2.54센티미터).


### Pt {#Pt}
```
public static final int Pt
```


Pt. 1포인트는 인치의 1/72 또는 0.353mm입니다.


### Pc {#Pc}
```
public static final int Pc
```


Pc. 1파이카(12포인트).


### Ch {#Ch}
```
public static final int Ch
```


Ch. 이 단위는 너비, 보다 정확히는 전진을 나타냅니다
측정값, 글리프 '0'(제로, 유니코드 문자 U+0030)의
요소의 글꼴.


### Rem {#Rem}
```
public static final int Rem
```


Rem. 이 단위는 루트 요소(예:
\<html\> 요소의 font-size). font-size에 사용될 때
이 루트 요소는 초기 값을 나타냅니다.


### Vw {#Vw}
```
public static final int Vw
```


Vw - 뷰포트 너비. 뷰포트 너비의 1/100.


### Vh {#Vh}
```
public static final int Vh
```


Vh - 뷰포트 높이. 뷰포트 높이의 1/100.


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin. 높이와 너비 중 최소값의 1/100.
뷰포트의.


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax. 높이와 너비 사이의 최대값의 1/100
뷰포트의.


### Percent {#Percent}
```
public static final int Percent
```


값은 고정된 (외부) 값에 상대적이며, 이는 컨텍스트
dependent. 1% = 외부 값의 1/100.


### getUnit() {#getUnit--}
```
public static Integer[] getUnit()
```




**Returns:**
java.lang.Integer[]
### getUnits() {#getUnits--}
```
public static Map<Integer,String> getUnits()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
