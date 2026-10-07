---
title: "외부 HTML 리소스를 모두 저장하기 위해 최종 사용자가 구현해야 하는 인터페이스."
second_title: "GroupDocs.Editor for Java API 참조"
description: "XmlHighlightOptions"
type: docs
weight: 53
url: /ko/java/com.groupdocs.editor.options/xmlhighlightoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class XmlHighlightOptions implements IEditOptions
```

XML을 HTML로 변환하는 동안 XML 하이라이팅을 사용자 지정할 수 있는 옵션을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getXmlTagsFontSettings()](#getXmlTagsFontSettings--) | XML을 HTML로 변환하는 동안 XML 하이라이팅을 사용자 지정할 수 있는 옵션을 포함합니다. |
|
|  | [getAttributeNamesFontSettings()](#getAttributeNamesFontSettings--) | XML 태그(태그 이름이 있는 꺾쇠 괄호)의 글꼴을 표시하는 역할을 합니다. |
|
|  | [getAttributeValuesFontSettings()](#getAttributeValuesFontSettings--) | 속성 이름의 글꼴을 표시하는 역할을 합니다. |
|
|  | [getInnerTextFontSettings()](#getInnerTextFontSettings--) | 속성 값의 글꼴을 표시하는 역할을 합니다. |
|
|  | [getHtmlCommentsFontSettings()](#getHtmlCommentsFontSettings--) | 내부 태그 텍스트의 글꼴을 표시하는 역할을 합니다. |
|
|  | [getCDataFontSettings()](#getCDataFontSettings--) | HTML 주석(시작 및 종료 태그 쌍 포함)의 글꼴을 표시하는 역할을 합니다. |
|
|  | [isDefault()](#isDefault--) | CDATA 섹션(시작 및 종료 태그 쌍 포함)의 글꼴을 표시하는 역할을 합니다. |
|
|  | [resetToDefault()](#resetToDefault--) | 이 XML 하이라이트 옵션 객체에 기본 글꼴 설정이 있는지 여부를 결정합니다. |
|
### getXmlTagsFontSettings() {#getXmlTagsFontSettings--}
```
public final WebFont getXmlTagsFontSettings()
```


XML을 HTML로 변환하는 동안 XML 하이라이팅을 사용자 지정할 수 있는 옵션을 포함합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeNamesFontSettings() {#getAttributeNamesFontSettings--}
```
public final WebFont getAttributeNamesFontSettings()
```


XML 태그(태그 이름이 있는 꺾쇠 괄호)의 글꼴을 표시하는 역할을 합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getAttributeValuesFontSettings() {#getAttributeValuesFontSettings--}
```
public final WebFont getAttributeValuesFontSettings()
```


속성 이름의 글꼴을 표시하는 역할을 합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getInnerTextFontSettings() {#getInnerTextFontSettings--}
```
public final WebFont getInnerTextFontSettings()
```


속성 값의 글꼴을 표시하는 역할을 합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getHtmlCommentsFontSettings() {#getHtmlCommentsFontSettings--}
```
public final WebFont getHtmlCommentsFontSettings()
```


내부 태그 텍스트의 글꼴을 표시하는 역할을 합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### getCDataFontSettings() {#getCDataFontSettings--}
```
public final WebFont getCDataFontSettings()
```


HTML 주석(시작 및 종료 태그 쌍 포함)의 글꼴을 표시하는 역할을 합니다.


**Returns:**
[WebFont](../../com.groupdocs.editor.options/webfont)
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


CDATA 섹션(시작 및 종료 태그 쌍 포함)의 글꼴을 표시하는 역할을 합니다.


**Returns:**
boolean
### resetToDefault() {#resetToDefault--}
```
public final void resetToDefault()
```


이 XML 하이라이트 옵션 객체에 기본 글꼴 설정이 있는지 여부를 결정합니다.


