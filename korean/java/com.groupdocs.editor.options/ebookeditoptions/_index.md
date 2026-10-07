---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 형식(ePub, MOBI 및 AZW3)에서 전자책 문서를 편집하기 위한 사용자 지정 옵션을 지정하고 조정할 수 있습니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.options/ebookeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EbookEditOptions implements IEditOptions
```

지원되는 모든 형식(ePub, MOBI, AZW3)의 전자책 문서를 편집하기 위한 사용자 지정 옵션을 지정하고 조정할 수 있습니다.

<br />

*** ** * ** ***

지원되는 전자책 형식:

1. [ePub](../https://docs.fileformat.com/ebook/epub/) (전자 출판)
2. [MOBI](../https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](../https://docs.fileformat.com/ebook/azw3/) (Kindle 포맷 8t)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EbookEditOptions()](#EbookEditOptions--) | 모든 옵션이 기본값으로 설정된 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [EbookEditOptions(boolean enablePagination)](#EbookEditOptions-boolean-) | 지정된 페이지 매김 모드와 함께 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEnablePagination()](#getEnablePagination--) | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [setEnablePagination(boolean value)](#setEnablePagination-boolean-) | 결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. |
|
|  | [getEnableLanguageInformation()](#getEnableLanguageInformation--) | 언어 정보를 'lang' HTML 속성 형태로 HTML 마크업에 내보낼지 여부를 지정합니다. |
|
|  | [setEnableLanguageInformation(boolean value)](#setEnableLanguageInformation-boolean-) | 언어 정보를 'lang' HTML 속성 형태로 HTML 마크업에 내보낼지 여부를 지정합니다. |
|
### EbookEditOptions() {#EbookEditOptions--}
```
public EbookEditOptions()
```


모든 옵션이 기본값으로 설정된 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 클래스의 새 인스턴스를 초기화합니다.


### EbookEditOptions(boolean enablePagination) {#EbookEditOptions-boolean-}
```
public EbookEditOptions(boolean enablePagination)
```


지정된 페이지 매김 모드와 함께 [EbookEditOptions](../../com.groupdocs.editor.options/ebookeditoptions) 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | enablePagination | boolean | 결과 HTML 문서에서 전자책 콘텐츠의 페이지 매김을 활성화( true )하거나 비활성화( false )합니다. 기본값은 비활성화( false )입니다. |
|

### getEnablePagination() {#getEnablePagination--}
```
public final boolean getEnablePagination()
```


결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본값은 비활성화되어 있습니다(
false
).

<br />

*** ** * ** ***

본질적으로 대부분의 전자책 형식은 내부적으로 Office Open XML과 같은 흐름 형식이며, 내용은 하나의 연속체로 장으로 분할되지만 페이지로는 분할되지 않습니다. 그러나 페이지 번호, 각주, 머리글/바닥글 등 페이지별 정보가 포함됩니다. 일부 전자책 리더는 전자책 내용을 페이지별로 분할하지만, 다른 리더(특히 모바일)는 \\u2014 그렇지 않습니다. 이 옵션은 편집 중 전자책 내용을 HTML/CSS에서 어떻게 표시할지 제어할 수 있게 해줍니다 \\u2014 플로트( false ) 또는 페이지 매김( true ) 보기로.

<br />



**Returns:**
boolean
### setEnablePagination(boolean value) {#setEnablePagination-boolean-}
```
public final void setEnablePagination(boolean value)
```


결과 HTML 문서에서 페이지 매김을 활성화하거나 비활성화할 수 있습니다. 기본값은 비활성화되어 있습니다(
false
).

<br />

*** ** * ** ***

본질적으로 대부분의 전자책 형식은 내부적으로 Office Open XML과 같은 흐름 형식이며, 내용은 하나의 연속체로 장으로 분할되지만 페이지로는 분할되지 않습니다. 그러나 페이지 번호, 각주, 머리글/바닥글 등 페이지별 정보가 포함됩니다. 일부 전자책 리더는 전자책 내용을 페이지별로 분할하지만, 다른 리더(특히 모바일)는 \\u2014 그렇지 않습니다. 이 옵션은 편집 중 전자책 내용을 HTML/CSS에서 어떻게 표시할지 제어할 수 있게 해줍니다 \\u2014 플로트( false ) 또는 페이지 매김( true ) 보기로.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getEnableLanguageInformation() {#getEnableLanguageInformation--}
```
public final boolean getEnableLanguageInformation()
```


언어 정보를 'lang' HTML 속성 형태로 HTML 마크업에 내보낼지 여부를 지정합니다.
이 옵션은 다국어 문서의 라운드트립 변환에 유용할 수 있습니다. 기본값은 비활성화되어 있습니다(
false
).


**Returns:**
boolean
### setEnableLanguageInformation(boolean value) {#setEnableLanguageInformation-boolean-}
```
public final void setEnableLanguageInformation(boolean value)
```


언어 정보를 'lang' HTML 속성 형태로 HTML 마크업에 내보낼지 여부를 지정합니다.
이 옵션은 다국어 문서의 라운드트립 변환에 유용할 수 있습니다. 기본값은 비활성화되어 있습니다(
false
).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

