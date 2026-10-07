---
title: "FontWeight"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Font-weight 속성은 글꼴의 두께 또는 굵기를 설정합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

Font-weight 속성은 글꼴의 두께(또는 굵기)를 설정합니다. 사용 가능한 두께는 현재 설정된 font-family에 따라 달라집니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Lighter](#Lighter) | 부모 요소보다 한 단계 가벼운 상대적인 글꼴 두께 |
|
|  | [Bolder](#Bolder) | 부모 요소보다 한 단계 무거운 상대적인 글꼴 두께 |
|
|  | [Normal](#Normal) | 보통 글꼴 두께. |
|
|  | [Bold](#Bold) | 굵은 글꼴 두께. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 이 font-size에 초기값(Medium)이 있는지 여부를 나타냅니다. |
|
|  | [getNumber()](#getNumber--) | 글꼴의 굵기를 설명하는 1에서 1000 사이(포함)의 정수 값을 반환하거나, 현재 굵기가 절대값이 아니라 상대값인 경우 예외를 발생시킵니다. |
|
|  | [isAbsolute()](#isAbsolute--) | 이 font-weight 인스턴스가 글꼴의 두께(굵기)를 정수 형태의 절대값으로 저장하고 있는지 여부를 나타냅니다. |
|
|  | [isRelative()](#isRelative--) | 이 font-weight 인스턴스가 폰트의 무게(굵기) 상대값을 저장하는지 여부를 나타냅니다 - 부모 요소의 굵기와 비교하여 |
|
|  | [getValue()](#getValue--) | 이 font-weight의 값을 문자열로 반환합니다 |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 지정된 FontWeight 인스턴스들이 같은지 여부를 판단합니다 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 FontWeight 인스턴스가 지정된 캐스팅되지 않은 인스턴스와 같은지 여부를 판단합니다 |
|
|  | [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | \"FontWeight\" 두 값이 같은지 확인합니다 |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | \"FontWeight\" 두 값이 다른지 확인합니다 |
|
|  | [fromNumber(int number)](#fromNumber-int-) | 지정된 숫자에서 font-weight를 생성합니다 |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | 지정된 문자열을 파싱하려 시도하고 성공하면 유효한 FontWeight 인스턴스를 반환합니다 |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


부모 요소보다 한 단계 가벼운 상대적인 글꼴 두께


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


부모 요소보다 한 단계 무거운 상대적인 글꼴 두께


### Normal {#Normal}
```
public static final FontWeight Normal
```


보통 폰트 무게. 400과 동일합니다.


### Bold {#Bold}
```
public static final FontWeight Bold
```


굵은 폰트 무게. 700과 동일합니다.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


이 font-size에 초기값(Medium)이 있는지 여부를 나타냅니다.


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


글꼴의 굵기를 설명하는 1에서 1000 사이(포함)의 정수 값을 반환하거나, 현재 굵기가 절대값이 아니라 상대값인 경우 예외를 발생시킵니다.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


이 font-weight 인스턴스가 글꼴의 두께(굵기)를 정수 형태의 절대값으로 저장하고 있는지 여부를 나타냅니다.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


이 font-weight 인스턴스가 폰트의 무게(굵기) 상대값을 저장하는지 여부를 나타냅니다 - 부모 요소의 굵기와 비교하여


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


이 font-weight의 값을 문자열로 반환합니다


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


지정된 FontWeight 인스턴스들이 같은지 여부를 판단합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 동등성을 확인하기 위한 다른 FontWeight 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 FontWeight 인스턴스가 지정된 캐스팅되지 않은 인스턴스와 같은지 여부를 판단합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 다른 캐스팅되지 않은 FontWeight 인스턴스, null일 수 있습니다 |
|

**Returns:**
boolean - 같으면 true, 같지 않거나 null이거나 다른 유형이면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.


**Returns:**
int - 부호가 있는 정수로서의 해시 코드

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


\"FontWeight\" 두 값이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 첫 번째 확인값 |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


\"FontWeight\" 두 값이 다른지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 첫 번째 확인값 |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 false, 그렇지 않으면 true

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


지정된 숫자에서 font-weight를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | number | int | 부호 없는 정수, [1..1000] 범위 내에 있어야 합니다 |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


지정된 문자열을 파싱하려 시도하고 성공하면 유효한 FontWeight 인스턴스를 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 입력 | java.lang.String | 파싱할 입력 문자열 |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | 성공 시 유효한 FontWeight 값, 실패 시 #Normal.Normal |
|

**Returns:**
boolean - 파싱 성공(true) 또는 실패(false)

