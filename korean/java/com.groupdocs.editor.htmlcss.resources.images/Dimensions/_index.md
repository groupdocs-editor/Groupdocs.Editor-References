---
title: "차원"
second_title: "GroupDocs.Editor for Java API 참조"
description: "임의 단위로 하나의 래스터 직사각형 이미지의 너비와 높이 선형 차원을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

하나의 래스터 직사각형(너비와 높이)의 선형 차원을 나타냅니다
이미지를 임의 단위로 나타냅니다. 불변 구조체.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | 지정된 너비와 높이로 새 인스턴스를 생성합니다 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 이미지의 너비를 반환합니다 |
|
|  | [getHeight()](#getHeight--) | 이미지의 높이를 반환합니다 |
|
|  | [isSquare()](#isSquare--) | 지정된 'Dimensions'가 정사각형인지 여부를 판단합니다, 즉. |
|
|  | [getArea()](#getArea--) | 면적을 반환합니다 (너비 x 높이) |
|
|  | [isEmpty()](#isEmpty--) | 이 "Dimensions" 인스턴스가 비어 있고 기본값인지 여부를 판단합니다, 즉. |
|
|  | [getAspectRatio()](#getAspectRatio--) | 이 차원의 종횡비를 너비/높이로 표시합니다 |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | 비례적으로 새로운 "Dimensions" 인스턴스를 생성하고 반환합니다 |
지정된 너비를 기준으로 현재에서 크기가 조정됩니다
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | 비례적으로 새로운 "Dimensions" 인스턴스를 생성하고 반환합니다 |
지정된 높이를 기준으로 현재에서 크기가 조정됩니다
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 이 인스턴스가 지정된 "Dimensions"와 같은지 여부를 판단합니다 |
인스턴스
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다, |
이는 아마도 다른 "Dimensions" 인스턴스일 것입니다
|
|  | [hashCode()](#hashCode--) | 이 인스턴스에 대한 해시코드를 반환합니다. 이는 해당 인스턴스의 |
수명
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 두 "Dimensions" 값이 같은지 여부를 확인합니다, 즉. |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | 두 "Dimensions" 값이 다른지 여부를 확인합니다, 즉. |
|
|  | [toString()](#toString--) | 이 "Dimensions"의 문자열 표현을 반환합니다 |
|
|  | [deepClone()](#deepClone--) | 이 인스턴스의 전체 복사본을 반환합니다 |
|
|  | [getEmpty()](#getEmpty--) | 빈 Dimensions 인스턴스를 반환합니다 |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


지정된 너비와 높이로 새 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 너비 | int | 이미지의 너비 |
|
|  | 높이 | int | 이미지의 높이 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


이미지의 너비를 반환합니다


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


이미지의 높이를 반환합니다


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


지정된 'Dimensions'가 정사각형인지 여부를 판단합니다, 즉, 만약
너비가 높이와 같습니다


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


면적을 반환합니다 (너비 x 높이)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


이 "Dimensions" 인스턴스가 비어 있고 기본값인지 여부를 판단합니다, 즉.
올바른 너비와 높이를 저장하지 않습니다


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


이 차원의 종횡비를 너비/높이로 표시합니다


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


비례적으로 새로운 "Dimensions" 인스턴스를 생성하고 반환합니다
지정된 너비를 기준으로 현재에서 크기가 조정됩니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | targetWidth | int | 새 대상 너비, 결과 Dimension에 포함됩니다 |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


비례적으로 새로운 "Dimensions" 인스턴스를 생성하고 반환합니다
지정된 높이를 기준으로 현재에서 크기가 조정됩니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | targetHeight | int | 새 대상 높이, 결과 Dimension에 포함됩니다 |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


이 인스턴스가 지정된 "Dimensions"와 같은지 여부를 판단합니다
인스턴스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 동등성 확인을 위한 다른 "Dimensions" 인스턴스 |
|

**Returns:**
boolean - 같으면 True, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 형 변환되지 않은 객체와 같은지 여부를 결정합니다,
이는 아마도 다른 "Dimensions" 인스턴스일 것입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | 다른 객체, "Dimensions" 타입으로 추정되며, 이것과의 동등성을 확인해야 합니다 |
|

**Returns:**
boolean - 같으면 True, 다르면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스에 대한 해시코드를 반환합니다. 이는 해당 인스턴스의
수명


**Returns:**
int - 이 인스턴스에 대해 불변(Immutable)인 서명된 4바이트 정수 해시 코드

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


두 "Dimensions" 값이 같은지 확인합니다, 즉 동일한
너비와 높이가 같거나, 두 값이 모두 비어 있는 경우


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 첫 번째 인스턴스 |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 두 번째 인스턴스 |
|

**Returns:**
boolean - 같으면 True, 다르면 false

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


두 "Dimensions" 값이 같지 않은지 확인합니다, 즉 그들의
해당 너비 및/또는 높이가 다릅니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 첫 번째 인스턴스 |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | 두 번째 인스턴스 |
|

**Returns:**
boolean - 다르면 True, 같으면 false

### toString() {#toString--}
```
public String toString()
```


이 "Dimensions"의 문자열 표현을 반환합니다

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - 너비와 높이를 W:(width)×H:(height) 형식으로 포함하는 String 인스턴스

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


이 인스턴스의 전체 복사본을 반환합니다


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


빈 Dimensions 인스턴스를 반환합니다


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
