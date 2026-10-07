---
title: "현재 글꼴 설정을 기본값으로 재설정합니다."
second_title: "GroupDocs.Editor for Java API 참조"
description: "WordProcessingEditOptions"
type: docs
weight: 44
url: /ko/java/com.groupdocs.editor.options/wordprocessingeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class WordProcessingEditOptions implements IEditOptions
```

DOCX, RTF, ODT 등 지원 가능한 모든 WordProcessing Words 호환 형식의 문서를 편집하기 위한 사용자 지정 옵션을 지정할 수 있습니다.
WordProcessing(Word 호환) 형식인 DOC(X), RTF, ODT 등.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingEditOptions()](#WordProcessingEditOptions--) | WordProcessingEditOptions의 새 인스턴스를 생성하고 반환합니다. |
클래스, 모든 옵션이 기본값으로 설정된 경우
|
|  | [WordProcessingEditOptions(boolean enablePagination)](#WordProcessingEditOptions-boolean-) | WordProcessingEditOptions의 새 인스턴스를 생성하고 반환합니다. |
지정된 페이지 매김이 적용되고 다른 모든 옵션이 기본값인 클래스
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | 언어 정보가 HTML 마크업에 내보내지는지 여부를 지정합니다 |
'lang' HTML 속성 형태.
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | 언어 정보가 HTML 마크업에 내보내지는지 여부를 지정합니다 |
'lang' HTML 속성 형태.
|
|  | [getExtractOnlyUsedFont()](#getExtractOnlyUsedFont--) | 문서에서 사용되는 글꼴 리소스만 추출할지 여부를 나타내는 값을 가져오거나 설정합니다 |
문서의 텍스트 내용에 사용됩니다.
|
|  | [setExtractOnlyUsedFont(boolean value)](#setExtractOnlyUsedFont-boolean-) | 문서에서 사용되는 글꼴 리소스만 추출할지 여부를 나타내는 값을 가져오거나 설정합니다 |
문서의 텍스트 내용에 사용됩니다.
|
|  | [getFontExtraction()](#getFontExtraction--) | 입력에서 사용되는 글꼴 리소스를 추출하는 역할을 합니다 |
WordProcessing 문서.
|
|  | [setFontExtraction(int value)](#setFontExtraction-int-) | 입력에서 사용되는 글꼴 리소스를 추출하는 역할을 합니다 |
WordProcessing 문서.
|
|  | [getInputControlsClassName()](#getInputControlsClassName--) | 'class'에 배치될 클래스 이름을 지정할 수 있습니다 |
입력의 일부 필드를 나타내는 모든 HTML 요소에 속성을 지정합니다.
WordProcessing 문서.
|
|  | [setInputControlsClassName(String value)](#setInputControlsClassName-java.lang.String-) | 'class'에 배치될 클래스 이름을 지정할 수 있습니다 |
입력의 일부 필드를 나타내는 모든 HTML 요소에 속성을 지정합니다.
WordProcessing 문서.
|
|  | [getUseInlineStyles()](#getUseInlineStyles--) | 입력 WordProcessing 문서의 스타일 및 서식 데이터를 저장할 위치를 제어합니다: 외부 스타일시트( |
false
) 또는 HTML 마크업에 인라인 스타일로(
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
).
|
|  | [setUseInlineStyles(boolean value)](#setUseInlineStyles-boolean-) | 입력 WordProcessing 문서의 스타일 및 서식 데이터를 저장할 위치를 제어합니다: 외부 스타일시트( |
false
) 또는 HTML 마크업에 인라인 스타일로(
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
).
|
### WordProcessingEditOptions() {#WordProcessingEditOptions--}
```
public WordProcessingEditOptions()
```


WordProcessingEditOptions의 새 인스턴스를 생성하고 반환합니다.
클래스, 모든 옵션이 기본값으로 설정된 경우


### WordProcessingEditOptions(boolean enablePagination) {#WordProcessingEditOptions-boolean-}
```
public WordProcessingEditOptions(boolean enablePagination)
```


WordProcessingEditOptions의 새 인스턴스를 생성하고 반환합니다.
지정된 페이지 매김이 적용되고 다른 모든 옵션이 기본값인 클래스


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | enablePagination | boolean | 페이지 매김 플래그로, 페이지 모드에 맞게 조정된 HTML 출력을 활성화합니다. |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본적으로
기본값은 비활성화되어 있습니다 (false).


**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본적으로
기본값은 비활성화되어 있습니다 (false).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


언어 정보가 HTML 마크업에 내보내지는지 여부를 지정합니다
'lang' HTML 속성 형태. 이 옵션은 라운드트립에 유용할 수 있습니다
다중 언어 문서 변환에 사용됩니다. 기본적으로 비활성화됩니다
(false).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


언어 정보가 HTML 마크업에 내보내지는지 여부를 지정합니다
'lang' HTML 속성 형태. 이 옵션은 라운드트립에 유용할 수 있습니다
다중 언어 문서 변환에 사용됩니다. 기본적으로 비활성화됩니다
(false).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getExtractOnlyUsedFont() {#getExtractOnlyUsedFont--}
```
public final boolean getExtractOnlyUsedFont()
```


문서에서 사용되는 글꼴 리소스만 추출할지 여부를 나타내는 값을 가져오거나 설정합니다
문서의 텍스트 내용에 사용됩니다.
값: 문서 텍스트 내용에 사용되는 글꼴 리소스만 추출해야 하는 경우 true, 그렇지 않으면 false. 기본값은 false입니다.


*** ** * ** ***

WordProcessing 문서에 사용된 모든 글꼴이 100% 직접 사용되는 것은 아닙니다(일부 텍스트에 적용됨). 글꼴이 문서에 참조되고 포함될 수도 있지만 실제 텍스트에 적용되지 않는 상황이 있을 수 있습니다. 예를 들어, 특정 글꼴이 스타일에 연결되어 있지만 해당 스타일이 텍스트 어느 부분에도 적용되지 않을 수 있습니다. 이 옵션은 이러한 경우를 어떻게 처리할지 제어합니다.

<br />



**Returns:**
boolean
### setExtractOnlyUsedFont(boolean value) {#setExtractOnlyUsedFont-boolean-}
```
public final void setExtractOnlyUsedFont(boolean value)
```


문서에서 사용되는 글꼴 리소스만 추출할지 여부를 나타내는 값을 가져오거나 설정합니다
문서의 텍스트 내용에 사용됩니다.
값: 문서 텍스트 내용에 사용되는 글꼴 리소스만 추출해야 하는 경우 true, 그렇지 않으면 false. 기본값은 false입니다.


*** ** * ** ***

WordProcessing 문서에 사용된 모든 글꼴이 100% 직접 사용되는 것은 아닙니다(일부 텍스트에 적용됨). 글꼴이 문서에 참조되고 포함될 수도 있지만 실제 텍스트에 적용되지 않는 상황이 있을 수 있습니다. 예를 들어, 특정 글꼴이 스타일에 연결되어 있지만 해당 스타일이 텍스트 어느 부분에도 적용되지 않을 수 있습니다. 이 옵션은 이러한 경우를 어떻게 처리할지 제어합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getFontExtraction() {#getFontExtraction--}
```
public final int getFontExtraction()
```


입력에서 사용되는 글꼴 리소스를 추출하는 역할을 합니다
WordProcessing 문서. 기본적으로 글꼴을 추출하지 않습니다.
(NotExtract).


**Returns:**
int
### setFontExtraction(int value) {#setFontExtraction-int-}
```
public final void setFontExtraction(int value)
```


입력에서 사용되는 글꼴 리소스를 추출하는 역할을 합니다
WordProcessing 문서. 기본적으로 글꼴을 추출하지 않습니다.
(NotExtract).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getInputControlsClassName() {#getInputControlsClassName--}
```
public final String getInputControlsClassName()
```


'class'에 배치될 클래스 이름을 지정할 수 있습니다
입력의 일부 필드를 나타내는 모든 HTML 요소에 속성을 지정합니다.
WordProcessing 문서. 기본값은 NULL이며, 'class' 속성은 적용되지 않습니다
적용됩니다.


*** ** * ** ***

WordProcessing 형식군의 거의 모든 포맷에는 필드(특정 문서 엔터티) 가 포함되어 있어 사용자의 입력 데이터를 얻을 수 있습니다. 텍스트 박스, 체크박스, 콤보 박스, 드롭다운 리스트, 버튼, 날짜/시간 선택기 등 다양한 필드가 있습니다. 이러한 필드들은 입력 문서에 존재한다면 입력된 사용자 데이터를 보존하면서 가장 적합한 HTML 구조와 요소로 변환됩니다. 특정 사용 사례에서는 전체 문서 내용을 편집하는 대신 클라이언트 측에서 입력된 데이터만 수집해야 할 수 있습니다. 이러한 경우 클라이언트 측에서 데이터를 가져오기 위해 입력 컨트롤을 식별할 방법이 필요합니다. 이 속성은 HTML 마크업의 모든 입력 컨트롤에 적용될 클래스 이름을 지정할 수 있게 하여, 클라이언트 코드가 HTML 문서 구조를 순회하면서 데이터를 수집할 수 있도록 합니다.

<br />



**Returns:**
java.lang.String
### setInputControlsClassName(String value) {#setInputControlsClassName-java.lang.String-}
```
public final void setInputControlsClassName(String value)
```


'class'에 배치될 클래스 이름을 지정할 수 있습니다
입력의 일부 필드를 나타내는 모든 HTML 요소에 속성을 지정합니다.
WordProcessing 문서. 기본값은 NULL이며, 'class' 속성은 적용되지 않습니다
적용됩니다.


*** ** * ** ***

WordProcessing 형식군의 거의 모든 포맷에는 필드(특정 문서 엔터티) 가 포함되어 있어 사용자의 입력 데이터를 얻을 수 있습니다. 텍스트 박스, 체크박스, 콤보 박스, 드롭다운 리스트, 버튼, 날짜/시간 선택기 등 다양한 필드가 있습니다. 이러한 필드들은 입력 문서에 존재한다면 입력된 사용자 데이터를 보존하면서 가장 적합한 HTML 구조와 요소로 변환됩니다. 특정 사용 사례에서는 전체 문서 내용을 편집하는 대신 클라이언트 측에서 입력된 데이터만 수집해야 할 수 있습니다. 이러한 경우 클라이언트 측에서 데이터를 가져오기 위해 입력 컨트롤을 식별할 방법이 필요합니다. 이 속성은 HTML 마크업의 모든 입력 컨트롤에 적용될 클래스 이름을 지정할 수 있게 하여, 클라이언트 코드가 HTML 문서 구조를 순회하면서 데이터를 수집할 수 있도록 합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getUseInlineStyles() {#getUseInlineStyles--}
```
public final boolean getUseInlineStyles()
```


입력 WordProcessing 문서의 스타일 및 서식 데이터를 저장할 위치를 제어합니다: 외부 스타일시트(
false
) 또는 HTML 마크업에 인라인 스타일로(
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
.) 기본적으로 외부 스타일이 사용됩니다 (
false
).


**Returns:**
boolean
### setUseInlineStyles(boolean value) {#setUseInlineStyles-boolean-}
```
public final void setUseInlineStyles(boolean value)
```


입력 WordProcessing 문서의 스타일 및 서식 데이터를 저장할 위치를 제어합니다: 외부 스타일시트(
false
) 또는 HTML 마크업에 인라인 스타일로(
또는 HTML 마크업에 삽입하여 HTML-\>HEAD 섹션의 STYLE 요소 내부에 포함합니다 (
.) 기본적으로 외부 스타일이 사용됩니다 (
false
).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

