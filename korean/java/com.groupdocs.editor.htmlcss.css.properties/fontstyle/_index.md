---
title: "FontStyle"
second_title: "GroupDocs.Editor for Java API 참조"
description: "글꼴이 폰트 패밀리에서 일반, 이탤릭 또는 기울임체 중 어떤 형태로 스타일링되어야 하는지를 정의합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

글꼴 패밀리에서 일반, 이탤릭 또는 기울임체 중 하나로 글꼴 스타일을 정의합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Normal](#Normal) | 폰트 패밀리 내에서 일반으로 분류된 글꼴을 선택합니다. |
|
|  | [Italic](#Italic) | 이탤릭으로 분류된 글꼴을 선택합니다. |
|
|  | [Oblique](#Oblique) | 기울임체로 분류된 글꼴을 선택합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isInitial()](#isInitial--) | 이 font-style에 초기값(보통)이 있는지 여부를 나타냅니다. |
|
|  | [getValue()](#getValue--) | 이 글꼴 스타일의 값을 문자열로 반환합니다. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 이 font-style 인스턴스가 지정된 값과 같은지 여부를 판단합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 font-style 인스턴스가 지정된 형변환되지 않은 값과 같은지 여부를 판단합니다. |
|
|  | [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 두 "FontStyle" 값이 같은지 확인합니다. |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 두 "FontStyle" 값이 다른지 확인합니다. |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | 지정된 키워드를 'font-style'의 적절한 키워드 값으로 인식하려 시도하고, 성공하면 반환하고 실패하면 NULL을 반환합니다. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


폰트 패밀리 내에서 일반으로 분류된 글꼴을 선택합니다. 초기값.


### Italic {#Italic}
```
public static final FontStyle Italic
```


이탤릭으로 분류된 글꼴을 선택합니다. 이탤릭 버전이 없을 경우, 대신 기울임체로 분류된 글꼴을 사용합니다. 두 경우 모두 없으면 스타일을 인위적으로 시뮬레이션합니다.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


기울임체로 분류된 글꼴을 선택합니다. 기울임체 버전이 없을 경우, 대신 이탤릭으로 분류된 글꼴을 사용합니다. 두 경우 모두 없으면 스타일을 인위적으로 시뮬레이션합니다.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


이 font-style에 초기값(보통)이 있는지 여부를 나타냅니다.


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


이 글꼴 스타일의 값을 문자열로 반환합니다.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


이 font-style 인스턴스가 지정된 값과 같은지 여부를 판단합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 다른 font-style 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 font-style 인스턴스가 지정된 형변환되지 않은 값과 같은지 여부를 판단합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 다른 형변환되지 않은 font-style 인스턴스, null일 수 있음 |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


두 "FontStyle" 값이 같은지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 첫 번째 확인값 |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 true, 그렇지 않으면 false

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


두 "FontStyle" 값이 다른지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 첫 번째 확인값 |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 두 번째 확인값 |
|

**Returns:**
boolean - 같으면 false, 그렇지 않으면 true

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


지정된 키워드를 'font-style'의 적절한 키워드 값으로 인식하려 시도하고, 성공하면 반환하고 실패하면 NULL을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 키워드 | java.lang.String | 파싱할 키워드 |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | 결과, 파싱이 성공했을 경우, 그렇지 않으면 #Normal.Normal |
|

**Returns:**
boolean - 파싱이 성공했으면 true, 그렇지 않으면 false

