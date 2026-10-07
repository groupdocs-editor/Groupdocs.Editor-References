---
title: "MhtmlSaveOptions"
second_title: "GroupDocs.Editor for Java API 참조"
description: "집계 HTML 문서의 MHTML MIME 캡슐화를 생성하고 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다."
type: docs
weight: 26
url: /ko/java/com.groupdocs.editor.options/mhtmlsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MhtmlSaveOptions implements ISaveOptions
```

MHTML(집합 HTML 문서의 MIME 캡슐화) 문서를 생성 및 저장하기 위한 사용자 지정 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MhtmlSaveOptions()](#MhtmlSaveOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getExportCidUrls()](#getExportCidUrls--) | MHTML 문서에 포함된 리소스(이미지, 글꼴, CSS)를 참조하기 위해 CID(Content-ID) URL을 사용할지 여부를 지정합니다. |
|
|  | [setExportCidUrls(boolean value)](#setExportCidUrls-boolean-) | MHTML 문서에 포함된 리소스(이미지, 글꼴, CSS)를 참조하기 위해 CID(Content-ID) URL을 사용할지 여부를 지정합니다. |
|
|  | [getExportDocumentProperties()](#getExportDocumentProperties--) | 내장 및 사용자 정의 문서 속성을 MHTML로 내보낼지 여부를 지정합니다. |
|
|  | [setExportDocumentProperties(boolean value)](#setExportDocumentProperties-boolean-) | 내장 및 사용자 정의 문서 속성을 MHTML로 내보낼지 여부를 지정합니다. |
|
|  | [getExportLanguageInformation()](#getExportLanguageInformation--) | 언어 정보를 MHTML로 내보낼지 여부를 지정합니다. |
|
|  | [setExportLanguageInformation(boolean value)](#setExportLanguageInformation-boolean-) | 언어 정보를 MHTML로 내보낼지 여부를 지정합니다. |
|
### MhtmlSaveOptions() {#MhtmlSaveOptions--}
```
public MhtmlSaveOptions()
```


### getExportCidUrls() {#getExportCidUrls--}
```
public final boolean getExportCidUrls()
```


MHTML 문서에 포함된 리소스(이미지, 글꼴, CSS)를 참조하기 위해 CID(Content-ID) URL을 사용할지 여부를 지정합니다. 기본값은
false
.

<br />

*** ** * ** ***


기본적으로 MHTML 문서의 리소스는 파일 이름(예: "image.png")으로 참조되며, 이는 MIME 파트의 "Content-Location" 헤더와 일치합니다. 이 옵션을 사용하면 리소스 파일에 대한 참조를 CID(Content-ID) URL(예: "cid:image.png")로 작성하고, 이를 "Content-ID" 헤더와 일치시키는 대체 방법을 사용할 수 있습니다.


이론적으로 두 참조 방법 사이에 차이가 없으며 어느 쪽이든 모든 브라우저나 메일 클라이언트에서 정상적으로 작동해야 합니다. 그러나 실제로는 일부 클라이언트가 파일 이름으로 리소스를 가져오지 못합니다. 브라우저나 메일 클라이언트가 MTHML 문서에 포함된 리소스를 로드하지 못하는 경우(이미지가 표시되지 않거나 CSS 스타일이 로드되지 않음), CID URL을 사용하여 문서를 내보내 보세요.

<br />



**Returns:**
boolean
### setExportCidUrls(boolean value) {#setExportCidUrls-boolean-}
```
public final void setExportCidUrls(boolean value)
```


MHTML 문서에 포함된 리소스(이미지, 글꼴, CSS)를 참조하기 위해 CID(Content-ID) URL을 사용할지 여부를 지정합니다. 기본값은
false
.

<br />

*** ** * ** ***


기본적으로 MHTML 문서의 리소스는 파일 이름(예: "image.png")으로 참조되며, 이는 MIME 파트의 "Content-Location" 헤더와 일치합니다. 이 옵션을 사용하면 리소스 파일에 대한 참조를 CID(Content-ID) URL(예: "cid:image.png")로 작성하고, 이를 "Content-ID" 헤더와 일치시키는 대체 방법을 사용할 수 있습니다.


이론적으로 두 참조 방법 사이에 차이가 없으며 어느 쪽이든 모든 브라우저나 메일 클라이언트에서 정상적으로 작동해야 합니다. 그러나 실제로는 일부 클라이언트가 파일 이름으로 리소스를 가져오지 못합니다. 브라우저나 메일 클라이언트가 MTHML 문서에 포함된 리소스를 로드하지 못하는 경우(이미지가 표시되지 않거나 CSS 스타일이 로드되지 않음), CID URL을 사용하여 문서를 내보내 보세요.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getExportDocumentProperties() {#getExportDocumentProperties--}
```
public final boolean getExportDocumentProperties()
```


내장 및 사용자 정의 문서 속성을 MHTML로 내보낼지 여부를 지정합니다. 기본값은
false
.


**Returns:**
boolean
### setExportDocumentProperties(boolean value) {#setExportDocumentProperties-boolean-}
```
public final void setExportDocumentProperties(boolean value)
```


내장 및 사용자 정의 문서 속성을 MHTML로 내보낼지 여부를 지정합니다. 기본값은
false
.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getExportLanguageInformation() {#getExportLanguageInformation--}
```
public final boolean getExportLanguageInformation()
```


언어 정보를 MHTML로 내보낼지 여부를 지정합니다. 기본값은
false
.

<br />

*** ** * ** ***

이 속성이 true 로 설정되면 GroupDocs.Editor는 언어를 지정하는 문서 요소에 lang HTML 속성을 추가합니다. 이는 언어 관련 의미를 보존하는 데 필요할 수 있습니다.

<br />



**Returns:**
boolean
### setExportLanguageInformation(boolean value) {#setExportLanguageInformation-boolean-}
```
public final void setExportLanguageInformation(boolean value)
```


언어 정보를 MHTML로 내보낼지 여부를 지정합니다. 기본값은
false
.

<br />

*** ** * ** ***

이 속성이 true 로 설정되면 GroupDocs.Editor는 언어를 지정하는 문서 요소에 lang HTML 속성을 추가합니다. 이는 언어 관련 의미를 보존하는 데 필요할 수 있습니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

