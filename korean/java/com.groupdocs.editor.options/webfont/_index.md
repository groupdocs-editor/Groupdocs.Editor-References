---
title: "WebFont"
second_title: "GroupDocs.Editor for Java API 참조"
description: "웹용 글꼴 설정을 나타냅니다."
type: docs
weight: 43
url: /ko/java/com.groupdocs.editor.options/webfont/
---
**Inheritance:**
java.lang.Object
```
public final class WebFont
```

웹용 글꼴 설정을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getColor()](#getColor--) | ARGB32 형식의 글꼴 색상 |
|
|  | [setColor(ArgbColor value)](#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | ARGB32 형식의 글꼴 색상 |
|
|  | [getWeight()](#getWeight--) | 글꼴의 두께(굵기)를 설정합니다. |
|
|  | [setWeight(FontWeight value)](#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | 글꼴의 두께(굵기)를 설정합니다. |
|
|  | [getStyle()](#getStyle--) | 글꼴 패밀리에서 일반, 이탤릭 또는 기울임체로 스타일링할지 여부를 설정합니다. |
|
|  | [setStyle(FontStyle value)](#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | 글꼴 패밀리에서 일반, 이탤릭 또는 기울임체로 스타일링할지 여부를 설정합니다. |
|
|  | [getLine()](#getLine--) | 텍스트에 적용되는 한 줄 또는 여러 줄을 설정합니다. |
|
|  | [setLine(TextDecorationLineType value)](#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | 텍스트에 적용되는 한 줄 또는 여러 줄을 설정합니다. |
|
|  | [getSize()](#getSize--) | 절대 또는 상대 단위로 글꼴 크기를 설정합니다. |
|
|  | [setSize(FontSize value)](#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | 절대 또는 상대 단위로 글꼴 크기를 설정합니다. |
|
|  | [getName()](#getName--) | 폰트 이름을 설정합니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 폰트 이름을 설정합니다. |
|
|  | [deepClone()](#deepClone--) | 이 [WebFont](../../com.groupdocs.editor.options/webfont) 인스턴스의 전체 깊은 복사본을 생성하고 반환합니다. |
|
|  | [equals(WebFont other)](#equals-com.groupdocs.editor.options.WebFont-) | 이 WebFont 인스턴스가 지정된 것과 같은지 여부를 결정합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 이 WebFont 인스턴스가 지정된 캐스팅되지 않은 객체와 같은지 여부를 결정합니다. |
|
### getColor() {#getColor--}
```
public final ArgbColor getColor()
```


ARGB32 형식의 글꼴 색상


**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)
### setColor(ArgbColor value) {#setColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final void setColor(ArgbColor value)
```


ARGB32 형식의 글꼴 색상


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |  |

### getWeight() {#getWeight--}
```
public final FontWeight getWeight()
```


글꼴의 두께(굵기)를 설정합니다.


**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight)
### setWeight(FontWeight value) {#setWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final void setWeight(FontWeight value)
```


글꼴의 두께(굵기)를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) |  |

### getStyle() {#getStyle--}
```
public final FontStyle getStyle()
```


글꼴 패밀리에서 일반, 이탤릭 또는 기울임체로 스타일링할지 여부를 설정합니다.


**Returns:**
[FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle)
### setStyle(FontStyle value) {#setStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final void setStyle(FontStyle value)
```


글꼴 패밀리에서 일반, 이탤릭 또는 기울임체로 스타일링할지 여부를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) |  |

### getLine() {#getLine--}
```
public final TextDecorationLineType getLine()
```


텍스트에 적용되는 한 줄 또는 여러 줄을 설정합니다.


**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
### setLine(TextDecorationLineType value) {#setLine-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final void setLine(TextDecorationLineType value)
```


텍스트에 적용되는 한 줄 또는 여러 줄을 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |  |

### getSize() {#getSize--}
```
public final FontSize getSize()
```


절대 또는 상대 단위로 글꼴 크기를 설정합니다.


**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize)
### setSize(FontSize value) {#setSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final void setSize(FontSize value)
```


절대 또는 상대 단위로 글꼴 크기를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) |  |

### getName() {#getName--}
```
public final String getName()
```


폰트 이름을 설정합니다. 지정하지 않으면 기본 폰트가 사용됩니다.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


폰트 이름을 설정합니다. 지정하지 않으면 기본 폰트가 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### deepClone() {#deepClone--}
```
public final WebFont deepClone()
```


이 [WebFont](../../com.groupdocs.editor.options/webfont) 인스턴스의 전체 깊은 복사본을 생성하고 반환합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont) - New [WebFont](../../com.groupdocs.editor.options/webfont) instance, that is a full and deep copy of this one

### equals(WebFont other) {#equals-com.groupdocs.editor.options.WebFont-}
```
public final boolean equals(WebFont other)
```


이 WebFont 인스턴스가 지정된 것과 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [WebFont](../../com.groupdocs.editor.options/webfont) | 동등성을 확인할 다른 WebFont이며, NULL일 수 있습니다. |
|

**Returns:**
boolean - 동일하면 true, 다르면 false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 WebFont 인스턴스가 지정된 캐스팅되지 않은 객체와 같은지 여부를 결정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | obj | java.lang.Object | Object, 이는 [WebFont](../../com.groupdocs.editor.options/webfont) 인스턴스일 것으로 예상됩니다. |
|

**Returns:**
boolean - 동일하면 true, 다르면 false

