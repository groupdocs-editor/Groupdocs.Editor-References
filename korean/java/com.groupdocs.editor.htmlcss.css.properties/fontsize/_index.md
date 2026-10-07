---
title: "FontSize"
second_title: "GroupDocs.Editor for Java API 참조"
description: "특수 단위 또는 길이 값으로서의 글꼴 크기를 나타내며, 이는 역사적으로 대문자 M의 너비를 기준으로 글꼴 크기를 지정합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

특수 단위 또는 길이 값으로 글꼴 크기를 나타내며, 글꼴의 크기(전통적으로 대문자 "M"의 너비)를 지정합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Medium](#Medium) | 중간 크기. |
|
|  | [XxSmall](#XxSmall) | 매우 작은 absolute-size |
|
|  | [XSmall](#XSmall) | 보통 작은 absolute-size |
|
|  | [Small](#Small) | 일반적인 작은 absolute-size |
|
|  | [Large](#Large) | 일반적인 큰 absolute-size |
|
|  | [XLarge](#XLarge) | 보통 큰 absolute-size |
|
|  | [XxLarge](#XxLarge) | 매우 큰 absolute-size |
|
|  | [Larger](#Larger) | 더 큰 relative-size - 글꼴은 부모 요소의 font-size에 비해 더 크게 표시되며, 위의 absolute-size 키워드를 구분하는 비율에 따라 대략적으로 결정됩니다. |
|
|  | [Smaller](#Smaller) | 더 작은 relative-size - 글꼴은 부모 요소의 font-size에 비해 더 작게 표시되며, 위의 absolute-size 키워드를 구분하는 비율에 따라 대략적으로 결정됩니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 이 font-size에 초기값(Medium)이 있는지 여부를 나타냅니다. |
|
|  | [getValue()](#getValue--) | 이 글꼴 크기의 값을 문자열로 반환합니다. |
|
|  | [isLengthDefined()](#isLengthDefined--) | 이 font-size가 [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) 값으로 정의되었는지 여부를 나타냅니다 |
|
|  | [getLength()](#getLength--) | 이 font-size가 해당 값으로 정의된 경우 길이 값이며, 그렇지 않으면 예외를 발생시킵니다 |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | 사용자의 기본 글꼴 크기(중간) 를 기준으로 절대 크기를 키워드로 정의했는지 여부를 나타냅니다 |
|
|  | [isRelativeSize()](#isRelativeSize--) | 이 font-size가 상대 크기를 키워드로 정의했는지 여부를 나타냅니다. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 이 font-size 인스턴스가 지정된 값과 같은지 여부를 결정합니다 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 font-size 인스턴스가 지정된 캐스팅되지 않은 값과 같은지 여부를 결정합니다 |
|
|  | [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | \"FontSize\" 두 값이 같은지 확인합니다 |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | \"FontSize\" 두 값이 같지 않은지 확인합니다 |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | 지정된 길이에서 font-size를 생성합니다 |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | 지정된 키워드를 'font-size'의 적절한 키워드 값으로 인식하려 시도하고, 성공하면 반환하고 실패하면 NULL을 반환합니다. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


중간 크기. 초기값.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


매우 작은 absolute-size


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


보통 작은 absolute-size


### Small {#Small}
```
public static final FontSize Small
```


일반적인 작은 absolute-size


### Large {#Large}
```
public static final FontSize Large
```


일반적인 큰 absolute-size


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


보통 큰 absolute-size


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


매우 큰 absolute-size


### Larger {#Larger}
```
public static final FontSize Larger
```


더 큰 relative-size - 글꼴은 부모 요소의 font-size에 비해 더 크게 표시되며, 위의 absolute-size 키워드를 구분하는 비율에 따라 대략적으로 결정됩니다.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


더 작은 relative-size - 글꼴은 부모 요소의 font-size에 비해 더 작게 표시되며, 위의 absolute-size 키워드를 구분하는 비율에 따라 대략적으로 결정됩니다.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


이 font-size에 초기값(Medium)이 있는지 여부를 나타냅니다.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


이 글꼴 크기의 값을 문자열로 반환합니다.


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


이 font-size가 [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) 값으로 정의되었는지 여부를 나타냅니다


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


이 font-size가 해당 값으로 정의된 경우 길이 값이며, 그렇지 않으면 예외를 발생시킵니다


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


사용자의 기본 글꼴 크기(중간) 를 기준으로 절대 크기를 키워드로 정의했는지 여부를 나타냅니다


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


이 font-size가 상대 크기를 키워드로 정의했는지 여부를 나타냅니다. 글꼴은 부모 요소의 글꼴 크기에 비해 대략 절대 크기 키워드를 구분하는 비율에 따라 크거나 작게 표시됩니다.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


이 font-size 인스턴스가 지정된 값과 같은지 여부를 결정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 다른 font-size 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 font-size 인스턴스가 지정된 캐스팅되지 않은 값과 같은지 여부를 결정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 다른 캐스팅되지 않은 font-size 인스턴스이며, null일 수 있습니다 |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


\"FontSize\" 두 값이 같은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 첫 번째 확인값 |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


\"FontSize\" 두 값이 같지 않은지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 첫 번째 확인값 |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 false, 그렇지 않으면 true

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


지정된 길이에서 font-size를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | 길이 값이며, 단위가 없거나 음수일 수 없습니다 |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


지정된 키워드를 'font-size'의 적절한 키워드 값으로 인식하려 시도하고, 성공하면 반환하고 실패하면 NULL을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 키워드 | java.lang.String | 파싱할 키워드 |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | 파싱 결과가 성공했을 경우 결과이며, 그렇지 않으면 #Medium.Medium 입니다 |
|

**Returns:**
boolean - 파싱이 성공했으면 true, 그렇지 않으면 false

