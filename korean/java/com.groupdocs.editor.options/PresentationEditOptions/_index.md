---
title: "PresentationEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 프레젠테이션 PowerPoint 호환 형식 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 32
url: /ko/java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

DOCX, RTF, ODT 등 지원 가능한 모든 WordProcessing Words 호환 형식의 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다.
프레젠테이션 (PowerPoint 호환) 형식

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSlideNumber()](#getSlideNumber--) | 편집을 위해 열어야 할 슬라이드 번호를 지정할 수 있습니다. |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | 편집을 위해 열어야 할 슬라이드 번호를 지정할 수 있습니다. |
|
|  | [getShowHiddenSlides()](#getShowHiddenSlides--) | 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
|
|  | [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 숨겨진 슬라이드를 포함할지 여부를 지정합니다. |
|
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


편집을 위해 열어야 할 슬라이드 번호를 지정할 수 있습니다.


*** ** * ** ***

슬라이드 번호는 슬라이드의 0부터 시작하는 인덱스로, 프레젠테이션에서 편집할 특정 슬라이드를 지정하고 선택할 수 있게 합니다. 0보다 작으면 첫 번째 슬라이드가 선택됩니다(SlideNumber = 0과 동일). 프레젠테이션의 전체 슬라이드 수보다 크면 마지막 슬라이드가 선택됩니다. 입력 프레젠테이션에 슬라이드가 하나만 있는 경우 이 옵션은 무시되고 해당 단일 슬라이드가 편집됩니다. 숨겨진 슬라이드를 편집하려고 시도하면서 ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) 옵션이 'false'로 설정된 경우 예외가 발생합니다.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


편집을 위해 열어야 할 슬라이드 번호를 지정할 수 있습니다.


*** ** * ** ***

슬라이드 번호는 슬라이드의 0부터 시작하는 인덱스로, 프레젠테이션에서 편집할 특정 슬라이드를 지정하고 선택할 수 있게 합니다. 0보다 작으면 첫 번째 슬라이드가 선택됩니다(SlideNumber = 0과 동일). 프레젠테이션의 전체 슬라이드 수보다 크면 마지막 슬라이드가 선택됩니다. 입력 프레젠테이션에 슬라이드가 하나만 있는 경우 이 옵션은 무시되고 해당 단일 슬라이드가 편집됩니다. 숨겨진 슬라이드를 편집하려고 시도하면서 ShowHiddenSlides (#getShowHiddenSlides.getShowHiddenSlides/#setShowHiddenSlides(boolean).setShowHiddenSlides(boolean)) 옵션이 'false'로 설정된 경우 예외가 발생합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은
false - 숨겨진 슬라이드가 표시되지 않으며,
편집을 시도할 때 예외가 발생합니다.


**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


숨겨진 슬라이드를 포함할지 여부를 지정합니다. 기본값은
false - 숨겨진 슬라이드가 표시되지 않으며,
편집을 시도할 때 예외가 발생합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

