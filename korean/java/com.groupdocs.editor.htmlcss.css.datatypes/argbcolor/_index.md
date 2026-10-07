---
title: "ArgbColor"
second_title: "GroupDocs.Editor for Java API 참조"
description: "컨버터와 직렬화 도구를 사용한 ARGB 형식의 색상 값을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

컨버터와 직렬화 도구를 사용한 ARGB 형식의 색상 값을 나타냅니다.

<br />

*** ** * ** ***

이 타입은 CSS 작업에 유용하도록 설계되었습니다(하지만 이에 국한되지 않음). 자세히 보기: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | 지정된 빨강, 초록, 파랑 및 알파 채널에서 하나의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 값을 생성합니다 |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | 지정된 빨강, 초록, 파랑 채널에서 하나의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 값을 생성하며, 알파 채널은 완전히 불투명합니다 |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | 단일 값으로부터 모든 채널에 적용되는 완전 불투명(A=255) 색상을 생성합니다 |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | 지정된 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)에서 하나의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 값을 생성합니다 |
|
|  | [getValue()](#getValue--) | 색상의 Int32 값을 가져옵니다. |
|
|  | [getA()](#getA--) | 색상의 알파 부분을 가져옵니다. |
|
|  | [getAlpha()](#getAlpha--) | 색상의 알파 부분을 백분율(0..1)로 가져옵니다. |
|
|  | [getR()](#getR--) | 색상의 빨강 부분을 가져옵니다. |
|
|  | [getG()](#getG--) | 색상의 초록 부분을 가져옵니다. |
|
|  | [getB()](#getB--) | 색상의 파랑 부분을 가져옵니다. |
|
|  | [isEmpty()](#isEmpty--) | 초기화되지 않은 색상 - 모든 4채널이 0으로 설정됩니다. |
|
|  | [isDefault()](#isDefault--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 기본(투명)인지 여부를 나타냅니다 - 모든 4채널이 0으로 설정됩니다 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 완전 투명인지 여부를 나타냅니다 - 알파 채널이 최소값(0)이며, 따라서 다른 R, G, B 채널은 눈에 보이는 효과가 없습니다. |
|
|  | [isTranslucent()](#isTranslucent--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 반투명인지 여부를 나타냅니다(완전 투명하지도, 완전 불투명하지도 않음). |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 투명성 없이 완전 불투명인지 여부를 나타냅니다(알파 채널이 최대값을 가짐). |
|
|  | [toSystemColor()](#toSystemColor--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스의 값을 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) 인스턴스로 변환하고 반환합니다 |
|
|  | [toRGBA()](#toRGBA--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스를 'rgba' CSS 함수 표기법으로 직렬화합니다 |
|
|  | [toRGB()](#toRGB--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스를 'rgb' CSS 함수 표기법으로 직렬화합니다 |
|
|  | [serializeDefault()](#serializeDefault--) | 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스를 투명도에 따라 가장 적절한 CSS 함수 표기법으로 직렬화합니다 |
|
|  | [toString()](#toString--) | #serializeDefault.serializeDefault와 동일합니다 |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 두 색상을 비교하고 두 색상이 일치하는지 여부를 나타내는 부울 값을 반환합니다. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 두 색상을 비교하고 두 색상이 일치하지 않는지 여부를 나타내는 부울 값을 반환합니다. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | 두 개의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 색상이 같은지 확인합니다 |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | 두 개의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 색상이 같은지 확인합니다 |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | 다른 객체가 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스와 같은지 테스트합니다. |
|
|  | [hashCode()](#hashCode--) | 현재 색상을 정의하는 해시 코드를 반환합니다. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


지정된 빨강, 초록, 파랑 및 알파 채널에서 하나의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 값을 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 빨강 | int | 빨강 채널 값 |
|
|  | 초록 | int | 초록 채널 값 |
|
|  | 파랑 | int | 파랑 채널 값 |
|
|  | 알파 | int | 알파 채널 값 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


지정된 빨강, 초록, 파랑 채널에서 하나의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 값을 생성하며, 알파 채널은 완전히 불투명합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 빨강 | int | 빨강 채널 값 |
|
|  | 초록 | int | 초록 채널 값 |
|
|  | 파랑 | int | 파랑 채널 값 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


단일 값으로부터 모든 채널에 적용되는 완전 불투명(A=255) 색상을 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | 바이트 | 바이트 값이며, 빨강, 초록 및 파랑 채널에 동일합니다 |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


지정된 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color)에서 하나의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 값을 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 색상 | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


색상의 Int32 값을 가져옵니다.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


색상의 알파 부분을 가져옵니다.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


색상의 알파 부분을 백분율(0..1)로 가져옵니다.


**Returns:**
double
### getR() {#getR--}
```
public final int getR()
```


색상의 빨강 부분을 가져옵니다.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


색상의 초록 부분을 가져옵니다.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


색상의 파랑 부분을 가져옵니다.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


초기화되지 않은 색상 - 모든 4채널이 0으로 설정됩니다. 기본값 및 투명과 동일합니다.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 기본(투명)인지 여부를 나타냅니다 - 모든 4채널이 0으로 설정됩니다


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 완전 투명인지 여부를 나타냅니다 - 알파 채널이 최소값(0)이며, 따라서 다른 R, G, B 채널은 눈에 보이는 효과가 없습니다.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 반투명인지 여부를 나타냅니다(완전 투명하지도, 완전 불투명하지도 않음).


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스가 투명성 없이 완전 불투명인지 여부를 나타냅니다(알파 채널이 최대값을 가짐).


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스의 값을 [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) 인스턴스로 변환하고 반환합니다


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스를 'rgba' CSS 함수 표기법으로 직렬화합니다


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' 형식의 문자열

### toRGB() {#toRGB--}
```
public final String toRGB()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스를 'rgb' CSS 함수 표기법으로 직렬화합니다


**Returns:**
java.lang.String - 'rgb(r, g, b)' 형식의 문자열

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스를 투명도에 따라 가장 적절한 CSS 함수 표기법으로 직렬화합니다


**Returns:**
java.lang.String - 'rgba(r, g, b, a)' 또는 'rgb(r, g, b)' 형식의 문자열

### toString() {#toString--}
```
public String toString()
```


#serializeDefault.serializeDefault와 동일합니다


**Returns:**
java.lang.String - #serializeDefault.serializeDefault와 동일한 반환값

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


두 색상을 비교하고 두 색상이 일치하는지 여부를 나타내는 부울 값을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 사용할 첫 번째 색상. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 사용할 두 번째 색상. |
|

**Returns:**
boolean - 두 색상이 동일하면 True, 그렇지 않으면 false.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


두 색상을 비교하고 두 색상이 일치하지 않는지 여부를 나타내는 부울 값을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 사용할 첫 번째 색상. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 사용할 두 번째 색상. |
|

**Returns:**
boolean - 두 색상이 동일하지 않으면 True, 그렇지 않으면 false.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


두 개의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 색상이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | 다른 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 색상 |
|

**Returns:**
boolean - 두 색상이 동일하면 True, 그렇지 않으면 false.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


두 개의 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 색상이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | 다른 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 색상, ICssDataType으로 캐스팅된 |
|

**Returns:**
boolean - 두 색상이 동일하면 True, 그렇지 않으면 false.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


다른 객체가 이 [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) 인스턴스와 같은지 테스트합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 기타 | java.lang.Object | 테스트에 사용할 객체. |
|

**Returns:**
boolean - 두 객체가 동일하면 True, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


현재 색상을 정의하는 해시 코드를 반환합니다.


**Returns:**
int - 해시코드의 정수값.

