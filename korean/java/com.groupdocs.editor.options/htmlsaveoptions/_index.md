---
title: "HtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "HTML 형식으로 인스턴스를 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 19
url: /ko/java/com.groupdocs.editor.options/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object
```
public final class HtmlSaveOptions
```

HTML 형식으로 [EditableDocument](../../com.groupdocs.editor/editabledocument) 인스턴스를 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getHtmlTagCase()](#getHtmlTagCase--) | HTML 마크업에서 HTML 태그 이름이 표시되는 방식을 제어합니다: 모두 소문자(기본값), 모두 대문자, 또는 첫 글자만 대문자. |
|
|  | [setHtmlTagCase(int value)](#setHtmlTagCase-int-) | HTML 마크업에서 HTML 태그 이름이 표시되는 방식을 제어합니다: 모두 소문자(기본값), 모두 대문자, 또는 첫 글자만 대문자. |
|
|  | [getAttributeValueDelimiter()](#getAttributeValueDelimiter--) | HTML 요소의 속성 값 주위에 사용할 구분자를 제어합니다: 작은따옴표(기본값) 또는 큰따옴표. |
|
|  | [setAttributeValueDelimiter(int value)](#setAttributeValueDelimiter-int-) | HTML 요소의 속성 값 주위에 사용할 구분자를 제어합니다: 작은따옴표(기본값) 또는 큰따옴표. |
|
|  | [getEmbedStylesheetsIntoMarkup()](#getEmbedStylesheetsIntoMarkup--) | CSS 스타일시트 저장 위치를 제어합니다: 외부 리소스로 ( |
false
)
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
true
|
|  | [setEmbedStylesheetsIntoMarkup(boolean value)](#setEmbedStylesheetsIntoMarkup-boolean-) | CSS 스타일시트 저장 위치를 제어합니다: 외부 리소스로 ( |
false
)
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
true
|
|  | [getSavingCallback()](#getSavingCallback--) | ) |
|
|  | [setSavingCallback(IHtmlSavingCallback value)](#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-) | ) |
|
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


### getHtmlTagCase() {#getHtmlTagCase--}
```
public final int getHtmlTagCase()
```


HTML 마크업에서 HTML 태그 이름이 표시되는 방식을 제어합니다: 모두 소문자(기본값), 모두 대문자, 또는 첫 글자만 대문자.


**Returns:**
int
### setHtmlTagCase(int value) {#setHtmlTagCase-int-}
```
public final void setHtmlTagCase(int value)
```


HTML 마크업에서 HTML 태그 이름이 표시되는 방식을 제어합니다: 모두 소문자(기본값), 모두 대문자, 또는 첫 글자만 대문자.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getAttributeValueDelimiter() {#getAttributeValueDelimiter--}
```
public final int getAttributeValueDelimiter()
```


HTML 요소의 속성 값 주위에 사용할 구분자를 제어합니다: 작은따옴표(기본값) 또는 큰따옴표.


**Returns:**
int
### setAttributeValueDelimiter(int value) {#setAttributeValueDelimiter-int-}
```
public final void setAttributeValueDelimiter(int value)
```


HTML 요소의 속성 값 주위에 사용할 구분자를 제어합니다: 작은따옴표(기본값) 또는 큰따옴표.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getEmbedStylesheetsIntoMarkup() {#getEmbedStylesheetsIntoMarkup--}
```
public final boolean getEmbedStylesheetsIntoMarkup()
```


CSS 스타일시트 저장 위치를 제어합니다: 외부 리소스로 (
false
)
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
true


**Returns:**
boolean
### setEmbedStylesheetsIntoMarkup(boolean value) {#setEmbedStylesheetsIntoMarkup-boolean-}
```
public final void setEmbedStylesheetsIntoMarkup(boolean value)
```


CSS 스타일시트 저장 위치를 제어합니다: 외부 리소스로 (
false
)
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
true


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getSavingCallback() {#getSavingCallback--}
```
public final IHtmlSavingCallback getSavingCallback()
```


)


**Returns:**
[IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback)
### setSavingCallback(IHtmlSavingCallback value) {#setSavingCallback-com.groupdocs.editor.options.IHtmlSavingCallback-}
```
public final void setSavingCallback(IHtmlSavingCallback value)
```


)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IHtmlSavingCallback](../../com.groupdocs.editor.options/ihtmlsavingcallback) |  |

