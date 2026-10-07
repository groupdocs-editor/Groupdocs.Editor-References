---
title: "FixedLayoutEditOptionsBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "PDF 및 XPS와 같은 고정 레이아웃 형식 문서에 대한 옵션을 위한 기본 추상 클래스"
type: docs
weight: 16
url: /ko/java/com.groupdocs.editor.options/fixedlayouteditoptionsbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public abstract class FixedLayoutEditOptionsBase implements IEditOptions
```

PDF 및 XPS와 같은 고정 레이아웃 형식 문서에 대한 옵션을 위한 기본 추상 클래스

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FixedLayoutEditOptionsBase()](#FixedLayoutEditOptionsBase--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSkipImages()](#getSkipImages--) | 입력 고정 레이아웃 문서를 결과 HTML로 변환하는 동안 이미지가 건너뛰어야 하는지를 나타내는 플래그를 가져오거나 설정합니다. |
|
|  | [setSkipImages(boolean value)](#setSkipImages-boolean-) | 입력 고정 레이아웃 문서를 결과 HTML로 변환하는 동안 이미지가 건너뛰어야 하는지를 나타내는 플래그를 가져오거나 설정합니다. |
|
|  | [getPages()](#getPages--) | 처리할 페이지 범위를 설정할 수 있습니다. |
|
|  | [setPages(PageRange value)](#setPages-com.groupdocs.editor.options.PageRange-) | 처리할 페이지 범위를 설정할 수 있습니다. |
|
|  | [getEnablePagination()](#getEnablePagination--) | 결과 HTML 문서에서 페이지 매김을 활성화(true)하거나 비활성화(false)할 수 있습니다. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 결과 HTML 문서에서 페이지 매김을 활성화(true)하거나 비활성화(false)할 수 있습니다. |
|
### FixedLayoutEditOptionsBase() {#FixedLayoutEditOptionsBase--}
```
public FixedLayoutEditOptionsBase()
```


### getSkipImages() {#getSkipImages--}
```
public final boolean getSkipImages()
```


입력 고정 레이아웃 문서를 결과 HTML로 변환하는 동안 이미지가 건너뛰어야 하는지를 나타내는 플래그를 가져오거나 설정합니다. 기본값은 false이며, 이미지가 보존됩니다.


**Returns:**
boolean
### setSkipImages(boolean value) {#setSkipImages-boolean-}
```
public final void setSkipImages(boolean value)
```


입력 고정 레이아웃 문서를 결과 HTML로 변환하는 동안 이미지가 건너뛰어야 하는지를 나타내는 플래그를 가져오거나 설정합니다. 기본값은 false이며, 이미지가 보존됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPages() {#getPages--}
```
public final PageRange getPages()
```


처리할 페이지 범위를 설정할 수 있습니다. 기본적으로 고정 레이아웃 문서의 모든 페이지가 처리됩니다.


**Returns:**
[PageRange](../../com.groupdocs.editor.options/pagerange)
### setPages(PageRange value) {#setPages-com.groupdocs.editor.options.PageRange-}
```
public final void setPages(PageRange value)
```


처리할 페이지 범위를 설정할 수 있습니다. 기본적으로 고정 레이아웃 문서의 모든 페이지가 처리됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PageRange](../../com.groupdocs.editor.options/pagerange) |  |

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


결과 HTML 문서에서 페이지 매김을 활성화(true)하거나 비활성화(false)할 수 있습니다. 기본값은 비활성화(false)입니다.

<br />

*** ** * ** ***

고정 레이아웃 형식 문서(PDF 및 XPS 등)는 본질적으로 페이지가 엄격히 구분되어 있으며, 내용이 고정된 레이아웃을 가지고 페이지로 나뉩니다. 그러나 결과 편집 가능한 HTML은 페이지가 없는 뷰 또는 페이지가 있는 뷰 중 하나로 표현될 수 있습니다.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


결과 HTML 문서에서 페이지 매김을 활성화(true)하거나 비활성화(false)할 수 있습니다. 기본값은 비활성화(false)입니다.

<br />

*** ** * ** ***

고정 레이아웃 형식 문서(PDF 및 XPS 등)는 본질적으로 페이지가 엄격히 구분되어 있으며, 내용이 고정된 레이아웃을 가지고 페이지로 나뉩니다. 그러나 결과 편집 가능한 HTML은 페이지가 없는 뷰 또는 페이지가 있는 뷰 중 하나로 표현될 수 있습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

