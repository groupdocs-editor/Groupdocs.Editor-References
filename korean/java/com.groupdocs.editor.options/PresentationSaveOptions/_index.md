---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "Presentation PowerPoint 호환 문서를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 34
url: /ko/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Presentation을 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.
(PowerPoint 호환) 문서

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | 이 매개변수 없는 생성자는 PPTX 출력 형식으로 PresentationSaveOptions의 새 인스턴스를 생성합니다(그 후에 다음을 통해 수정할 수 있음 |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | 지정된 옵션으로 PresentationSaveOptions의 새 인스턴스를 생성합니다 |
필수 Presentation 출력 형식이며, 다른 모든 매개변수는
기본값
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다 |
결과 Presentation 문서를 인코딩합니다.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 결과 Presentation 문서를 인코딩하는 데 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다. |
|
|  | [getSlideNumber()](#getSlideNumber--) | 새 단일 슬라이드 프레젠테이션을 만드는 대신 편집된 슬라이드를 기존 프레젠테이션에 삽입할 수 있습니다(기본 동작). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | 새 단일 슬라이드 프레젠테이션을 만드는 대신 편집된 슬라이드를 기존 프레젠테이션에 삽입할 수 있습니다(기본 동작). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | 편집된 슬라이드가 원본 프레젠테이션에서 지정된 위치의 기존 슬라이드를 교체할지 여부를 지정하는 부울 플래그, 해당 위치는 |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 속성, 또는 기존 슬라이드와 이전 슬라이드 사이에 삽입되어 내용이 교체되지 않아야 합니다.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | 편집된 슬라이드가 원본 프레젠테이션에서 지정된 위치의 기존 슬라이드를 교체할지 여부를 지정하는 부울 플래그, 해당 위치는 |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 속성, 또는 기존 슬라이드와 이전 슬라이드 사이에 삽입되어 내용이 교체되지 않아야 합니다.
|
|  | [getOutputFormat()](#getOutputFormat--) | 문서를 저장하는 데 사용될 Presentation 형식을 지정할 수 있습니다. |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | 문서를 저장하는 데 사용될 Presentation 형식을 지정할 수 있습니다. |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | 편집된 슬라이드가 기존 프레젠테이션에 삽입될 경우 저장 중에 프레젠테이션에서 삭제해야 할 1부터 시작하는 슬라이드 번호 배열을 지정할 수 있습니다. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | 편집된 슬라이드가 기존 프레젠테이션에 삽입될 경우 저장 중에 프레젠테이션에서 삭제해야 할 1부터 시작하는 슬라이드 번호 배열을 지정할 수 있습니다. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


이 매개변수 없는 생성자는 PPTX 출력 형식으로 PresentationSaveOptions의 새 인스턴스를 생성합니다(그 후에 다음을 통해 수정할 수 있음
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


지정된 옵션으로 PresentationSaveOptions의 새 인스턴스를 생성합니다
필수 Presentation 출력 형식이며, 다른 모든 매개변수는
기본값


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Presentation 문서를 저장해야 하는 필수 출력 형식 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다
결과 Presentation 문서를 인코딩합니다. 기본값은 NULL -
비밀번호가 설정되지 않습니다. 제거하려면 NULL 또는 빈 문자열로 설정하십시오
이전에 설정된 비밀번호를 제거합니다.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


결과 Presentation 문서를 인코딩하는 데 사용될 비밀번호를 지정, 수정 및 가져올 수 있습니다.
기본값은 NULL - 비밀번호가 설정되지 않습니다. 이전에 설정된 비밀번호를 제거하려면 NULL 또는 빈 문자열로 설정하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


새 단일 슬라이드 프레젠테이션을 만드는 대신 편집된 슬라이드를 기존 프레젠테이션에 삽입할 수 있습니다(기본 동작).
슬라이드 번호는 프레젠테이션에서 1부터 시작하는 슬라이드 번호이며, Editor 클래스에 로드됩니다. 값이 0(기본값)인 경우 새 프레젠테이션이 단일 편집 슬라이드로 생성됩니다. 값이 0보다 크거나 작고, Editor 클래스에 로드된 유효한 프레젠테이션이 있는 경우, 입력 EditableDocument 인스턴스에 저장된 편집 슬라이드가 이 프레젠테이션에 삽입됩니다.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


새 단일 슬라이드 프레젠테이션을 만드는 대신 편집된 슬라이드를 기존 프레젠테이션에 삽입할 수 있습니다(기본 동작).
슬라이드 번호는 프레젠테이션에서 1부터 시작하는 슬라이드 번호이며, Editor 클래스에 로드됩니다. 값이 0(기본값)인 경우 새 프레젠테이션이 단일 편집 슬라이드로 생성됩니다. 값이 0보다 크거나 작고, Editor 클래스에 로드된 유효한 프레젠테이션이 있는 경우, 입력 EditableDocument 인스턴스에 저장된 편집 슬라이드가 이 프레젠테이션에 삽입됩니다.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


편집된 슬라이드가 원본 프레젠테이션에서 지정된 위치의 기존 슬라이드를 교체할지 여부를 지정하는 부울 플래그, 해당 위치는
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 속성, 또는 기존 슬라이드와 이전 슬라이드 사이에 삽입되어 내용이 교체되지 않아야 합니다.
기본값은 false \\u2014 기존 슬라이드가 교체됩니다. 이 속성은 값이
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 속성이 '0'으로 설정된 경우.

<br />

*** ** * ** ***

기본적으로 슬라이드는 교체됩니다. 이는 주어진 프레젠테이션에 슬라이드가 5개 있고, SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4인 경우, 4번째 슬라이드가 새 편집 슬라이드로 교체되며 프레젠테이션의 전체 슬라이드 수(5)는 변하지 않음을 의미합니다. 그러나 이 속성의 값이 *true* 로 설정되면 새 편집 슬라이드가 4번째 슬라이드로 삽입되고, 이후의 모든 슬라이드가 끝으로 이동합니다: "old" 4번째 슬라이드가 5번째가 되고, 5번째가 6번째가 되며, 프레젠테이션의 전체 슬라이드 수가 하나 증가하여 6이 됩니다.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


편집된 슬라이드가 원본 프레젠테이션에서 지정된 위치의 기존 슬라이드를 교체할지 여부를 지정하는 부울 플래그, 해당 위치는
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 속성, 또는 기존 슬라이드와 이전 슬라이드 사이에 삽입되어 내용이 교체되지 않아야 합니다.
기본값은 false \\u2014 기존 슬라이드가 교체됩니다. 이 속성은 값이
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) 속성이 '0'으로 설정된 경우.

<br />

*** ** * ** ***

기본적으로 슬라이드는 교체됩니다. 이는 주어진 프레젠테이션에 슬라이드가 5개 있고, SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4인 경우, 4번째 슬라이드가 새 편집 슬라이드로 교체되며 프레젠테이션의 전체 슬라이드 수(5)는 변하지 않음을 의미합니다. 그러나 이 속성의 값이 *true* 로 설정되면 새 편집 슬라이드가 4번째 슬라이드로 삽입되고, 이후의 모든 슬라이드가 끝으로 이동합니다: "old" 4번째 슬라이드가 5번째가 되고, 5번째가 6번째가 되며, 프레젠테이션의 전체 슬라이드 수가 하나 증가하여 6이 됩니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


문서를 저장하는 데 사용될 Presentation 형식을 지정할 수 있습니다.

<br />

*** ** * ** ***

출력 형식은 일반적으로 이 클래스의 생성자에서 설정되며, 필수입니다. 이 속성을 사용하면 [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) 클래스의 인스턴스가 이미 생성된 후에도 출력 형식을 얻거나 수정할 수 있습니다.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


문서를 저장하는 데 사용될 Presentation 형식을 지정할 수 있습니다.

<br />

*** ** * ** ***

출력 형식은 일반적으로 이 클래스의 생성자에서 설정되며, 필수입니다. 이 속성을 사용하면 [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) 클래스의 인스턴스가 이미 생성된 후에도 출력 형식을 얻거나 수정할 수 있습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


편집된 슬라이드가 기존 프레젠테이션에 삽입되는 경우 저장 중에 프레젠테이션에서 삭제해야 할 슬라이드의 1 기반 번호 배열을 지정할 수 있습니다. 편집된 슬라이드가 새 단일 슬라이드 프레젠테이션(기본 동작)으로 저장되는 대신 기존 프레젠테이션에 저장될 때(#getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int) 사용), 이 배열에 번호를 지정하여 해당 프레젠테이션의 특정 슬라이드를 삭제할 수도 있습니다. 기본값으로 이 배열은  null  \\u2014 슬라이드가 삭제되지 않습니다. 그러나 이 배열이 null이 아니고 비어 있지 않으며 최소 하나의 유효한 슬라이드 번호를 포함하는 경우, 편집된 슬라이드의 내용으로 출력 Presentation 문서가 생성된 후 지정된 번호의 슬라이드가 출력 스트림이나 파일에 쓰기 직전에 프레젠테이션에서 삭제됩니다. 이 배열의 슬라이드 번호는 1 기반이며 0 기반이 아닙니다. 1보다 작거나 전체 슬라이드 수보다 큰 잘못된 번호는 무시됩니다.


**Returns:**
int[] - 삭제할 1 기반 슬라이드 번호 배열, 또는 삭제할 것이 없으면  null 

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


편집된 슬라이드가 기존 프레젠테이션에 삽입되는 경우 저장 중에 프레젠테이션에서 삭제할 슬라이드의 1 기반 번호 배열을 지정할 수 있습니다. 이 배열의 슬라이드 번호는 1 기반이며, 잘못된 번호는 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 삭제할 1 기반 슬라이드 번호 배열( null 이거나 비어 있을 수 있음). |
|

