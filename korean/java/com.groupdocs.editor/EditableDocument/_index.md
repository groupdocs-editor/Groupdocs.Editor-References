---
title: "EditableDocument"
second_title: "GroupDocs.Editor for Java API 참조"
description: "편집 전후의 내용을 포함하는 중간 문서"
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor/editabledocument/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IAuxDisposable](../../com.groupdocs.editor.htmlcss.resources/iauxdisposable)
```
public final class EditableDocument implements IAuxDisposable
```

편집 전후의 내용을 포함하는 중간 문서


*** ** * ** ***

EditableDocument 클래스의 인스턴스는 Editor.edit() 메서드로 생성하거나 사용자가 정적 팩터리를 사용해 직접 만들 수 있습니다. EditableDocument는 내부적으로 문서를 자체 폐쇄 형식으로 저장하며, 이는 GroupDocs.Editor가 지원하는 모든 가져오기 및 내보내기 형식과 호환(변환)됩니다. 문서를 CKEditor나 TinyMCE와 같은 WYSIWYG 클라이언트‑사이드 편집기에서 편집 가능하도록 만들기 위해 EditableDocument는 HTML 마크업을 생성하고 사용자가 사용할 수 있는 리소스를 제공하는 메서드를 제공합니다.

<br />


## 필드

| 필드 | 설명 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getImages()](#getImages--) | 외부 이미지 리소스(래스터 이미지)를 얻을 수 있으며, 이는 사용됩니다 |
이 HTML 문서에 의해
|
|  | [getFonts()](#getFonts--) | 외부 글꼴 리소스를 얻을 수 있으며, 이는 이 HTML에서 사용됩니다 |
문서
|
|  | [getCss()](#getCss--) | CSS 리소스 목록을 반환합니다 |
|
|  | [getAudio()](#getAudio--) | 오디오 리소스 목록을 반환합니다 |
|
|  | [getAllResources()](#getAllResources--) | 존재하는 모든 리소스 목록을 반환합니다: 모든 스타일시트, 이미지 출처 |
HTML 및 모든 스타일시트, 글꼴
|
|  | [getContent(OutputStream storage, Charset encoding)](#getContent-java.io.OutputStream-java.nio.charset.Charset-) | 지정된 텍스트 인코딩으로 지정된 스트림에 이 내용을 기록하여 HTML 문서의 전체 내용을 바이트 스트림으로 반환합니다 |
|
|  | [getBodyContent()](#getBodyContent--) | HTML 문서의 본문을 반환합니다(시작과 종료 사이의 내용 |
BODY 태그를 제외한 내용) 문자열로 반환합니다.
|
|  | [getBodyContent(String externalImagesTemplate)](#getBodyContent-java.lang.String-) | HTML 문서의 본문을 반환합니다(시작과 종료 사이의 내용 |
BODY 태그를 제외한 내용) 문자열로 반환하며, 외부 링크가
리소스에 지정된 접두사가 포함됩니다.
|
|  | [getContent()](#getContent--) | HTML 문서의 전체 내용을 문자열로 반환합니다. |
|
|  | [getContentString(String externalImagesTemplate, String externalCssTemplate)](#getContentString-java.lang.String-java.lang.String-) | HTML 문서의 전체 내용을 문자열로 반환하며, 링크가 |
외부 리소스에 지정된 접두사가 포함됩니다.
|
|  | [getCssContent()](#getCssContent--) | 외부 스타일시트 전체 내용을 문자열 목록으로 반환하며, |
각 문자열은 하나의 스타일시트를 나타냅니다.
|
|  | [getCssContent(String externalImagesPrefix, String externalFontsPrefix)](#getCssContent-java.lang.String-java.lang.String-) | 외부 스타일시트 전체 내용을 문자열 목록으로 반환하며, |
각 문자열은 하나의 스타일시트를 나타냅니다.
|
|  | [getEmbeddedHtml()](#getEmbeddedHtml--) | 이 HTML 문서와 모든 관련 리소스의 전체 내용을 |
단일 문자열 형태로 반환하며, 모든 리소스가 HTML 내부에 포함됩니다
마크업이 base64 인코딩 형태로 포함됩니다.
|
|  | [save(String htmlFilePath)](#save-java.lang.String-) | 지정된 경로에 파일로 이 HTML 문서를 저장하며, HTML 마크업이 |
저장되고, 리소스가 포함된 부속 폴더에도 저장됩니다.
|
|  | [save(String htmlFilePath, String resourcesFolderPath)](#save-java.lang.String-java.lang.String-) | 지정된 경로에 파일로 이 HTML 문서를 저장하며, HTML 마크업이 |
저장되며, 리소스가 포함된 부속 폴더는
지정된 경로에 위치합니다.
|
| [save(Writer htmlMarkup, HtmlSaveOptions saveOptions)](#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-) |  |
|  | [fromMarkup(String newHtmlContent, List<IHtmlResource> resources)](#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--) | EditableDocument 인스턴스를 생성하는 정적 팩토리, |
지정된 HTML 마크업과 해당되는 연결된 리소스 집합으로부터
|
|  | [fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)](#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-) | 전체 경로로 지정된 폴더에 위치한 리소스로부터 지정된 HTML 마크업을 사용하여 EditableDocument 인스턴스를 생성하는 정적 팩토리 |
|
|  | [fromFile(String htmlFilePath, String resourceFolderPath)](#fromFile-java.lang.String-java.lang.String-) | HTML로부터 EditableDocument 인스턴스를 생성하는 정적 팩토리 |
파일, 즉 \*.html 파일 자체와 폴더에 대한 경로로 지정된 파일
연결된 리소스와 함께
|
|  | [dispose()](#dispose--) | 이 Editable 문서 인스턴스를 해제하고, 해당 내용도 해제하며 |
그 메서드와 속성을 사용할 수 없게 만듭니다
|
|  | [isDisposed()](#isDisposed--) | 이 Editable 문서가 이미 해제되었는지 (true) 여부를 판단하거나 |
아니면 (false)
|
### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getImages() {#getImages--}
```
public final List<IImageResource> getImages()
```


외부 이미지 리소스(래스터 이미지)를 얻을 수 있으며, 이는 사용됩니다
이 HTML 문서에 의해


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.images.IImageResource>
### getFonts() {#getFonts--}
```
public final List<FontResourceBase> getFonts()
```


외부 글꼴 리소스를 얻을 수 있으며, 이는 이 HTML에서 사용됩니다
문서


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase>
### getCss() {#getCss--}
```
public final List<CssText> getCss()
```


CSS 리소스 목록을 반환합니다


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.textual.CssText>
### getAudio() {#getAudio--}
```
public final List<Mp3Audio> getAudio()
```


오디오 리소스 목록을 반환합니다


**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio>
### getAllResources() {#getAllResources--}
```
public final List<IHtmlResource> getAllResources()
```


존재하는 모든 리소스 목록을 반환합니다: 모든 스타일시트, 이미지 출처
HTML 및 모든 스타일시트, 글꼴


*** ** * ** ***

이 속성은 'Images', 'Fonts', 및 'Css' 속성들의 연결된 결과를 반환합니다

<br />



**Returns:**
java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource>
### getContent(OutputStream storage, Charset encoding) {#getContent-java.io.OutputStream-java.nio.charset.Charset-}
```
public OutputStream getContent(OutputStream storage, Charset encoding)
```


지정된 텍스트 인코딩으로 지정된 스트림에 이 내용을 기록하여 HTML 문서의 전체 내용을 바이트 스트림으로 반환합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스토리지 | java.io.OutputStream | 쓰기 지원이 가능한 null이 아닌 바이트 스트림 |
|
|  | encoding | java.nio.charset.Charset | 지정된 스토리지에 텍스트 내용을 쓸 때 적용해야 하는 null이 아닌 텍스트 인코딩 |


TStream
: java.io.InputStream의 모든 구현
|

**Returns:**
java.io.OutputStream - 지정된 스토리지의 인스턴스

### getBodyContent() {#getBodyContent--}
```
public final String getBodyContent()
```


HTML 문서의 본문을 반환합니다(시작과 종료 사이의 내용
BODY 태그를 제외한 내용) 문자열로 반환합니다.


**Returns:**
java.lang.String - HTML 문서 본문을 포함하는 문자열


*** ** * ** ***

WYSIWYG 편집기는 문서 본문을 다루며 HEAD 블록의 메타 정보를 올바르게 처리하지 못합니다. 이 메서드는 이러한 경우를 위해 설계되었습니다. 이 오버로드는 외부 리소스 요청에 대한 URI를 조정하는 것을 허용하지 않습니다.

<br />


### getBodyContent(String externalImagesTemplate) {#getBodyContent-java.lang.String-}
```
public final String getBodyContent(String externalImagesTemplate)
```


HTML 문서의 본문을 반환합니다(시작과 종료 사이의 내용
BODY 태그를 제외한 내용) 문자열로 반환하며, 외부 링크가
리소스에 지정된 접두사가 포함됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | 이 매개변수를 사용하면 결과 HTML 문자열에 포함될 IMG 요소의 모든 외부 이미지 링크에 추가될 접두사를 지정할 수 있습니다. NULL이거나 비어 있으면 접두사가 추가되지 않습니다. |


*** ** * ** ***

WYSIWYG 편집기는 문서 본문을 다루며 HEAD 블록의 메타 정보를 올바르게 처리하지 못합니다. 이 메서드는 이러한 경우를 위해 설계되었습니다. 이 오버로드는 외부 리소스 요청에 대한 URI를 조정할 수 있도록 허용합니다.

<br />

|

**Returns:**
java.lang.String - 외부 이미지에 맞게 조정된 링크가 포함된 HTML 문서 본문을 포함하는 문자열

### getContent() {#getContent--}
```
public String getContent()
```


HTML 문서의 전체 내용을 문자열로 반환합니다.


**Returns:**
java.lang.String - HTML 문서의 내용을 포함하는 문자열

### getContentString(String externalImagesTemplate, String externalCssTemplate) {#getContentString-java.lang.String-java.lang.String-}
```
public String getContentString(String externalImagesTemplate, String externalCssTemplate)
```


HTML 문서의 전체 내용을 문자열로 반환하며, 링크가
외부 리소스에 지정된 접두사가 포함됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | externalImagesTemplate | java.lang.String | 이 매개변수를 사용하면 결과 HTML 문자열에 포함될 IMG 요소의 모든 외부 이미지 링크에 추가될 접두사를 지정할 수 있습니다. NULL이거나 비어 있으면 접두사가 추가되지 않습니다. |
|
|  | externalCssTemplate | java.lang.String | 이 매개변수를 사용하면 PREFIX를 지정할 수 있으며, 이는 결과 HTML 문자열에 포함되는 LINK 요소의 모든 외부 스타일시트 링크에 추가됩니다. NULL이거나 비어 있으면 접두사가 추가되지 않습니다. |
|

**Returns:**
java.lang.String - 문자열, 외부 리소스에 맞게 조정된 링크가 포함된 HTML 문서의 내용을 포함합니다.

### getCssContent() {#getCssContent--}
```
public final List<String> getCssContent()
```


외부 스타일시트 전체 내용을 문자열 목록으로 반환하며,
하나의 문자열은 하나의 스타일시트를 나타냅니다. 없을 경우 빈 목록을 반환합니다.
이 문서의 CSS.


**Returns:**
java.util.List<java.lang.String> - 각 문자열이 하나의 CSS 문서 내용을 보유하는 문자열 목록

### getCssContent(String externalImagesPrefix, String externalFontsPrefix) {#getCssContent-java.lang.String-java.lang.String-}
```
public final List<String> getCssContent(String externalImagesPrefix, String externalFontsPrefix)
```


외부 스타일시트 전체 내용을 문자열 목록으로 반환하며,
하나의 문자열은 하나의 스타일시트를 나타냅니다. 지정된 접두사는 다음에 적용됩니다.
각 결과 스타일시트의 모든 외부 리소스 링크에 적용됩니다.
이 문서에 CSS가 없으면 빈 목록을 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | externalImagesPrefix | java.lang.String | 이 매개변수를 사용하면 PREFIX를 지정할 수 있으며, 이는 결과 CSS 문자열의 CSS 선언에 포함되는 모든 외부 이미지 링크에 추가됩니다. NULL이거나 비어 있으면 접두사가 추가되지 않습니다. |
|
|  | externalFontsPrefix | java.lang.String | 이 매개변수를 사용하면 PREFIX를 지정할 수 있으며, 이는 모든 외부 글꼴 링크에 추가됩니다. |
|

**Returns:**
java.util.List<java.lang.String> - 각 문자열이 하나의 CSS 문서 내용을 보유하는 문자열 목록

### getEmbeddedHtml() {#getEmbeddedHtml--}
```
public final String getEmbeddedHtml()
```


이 HTML 문서와 모든 관련 리소스의 전체 내용을
단일 문자열 형태로 반환하며, 모든 리소스가 HTML 내부에 포함됩니다
마크업이 base64 인코딩 형태로 포함됩니다.


**Returns:**
java.lang.String - 문자열, 어떤 경우에도 NULL이 아니며 비어 있지 않습니다.

### save(String htmlFilePath) {#save-java.lang.String-}
```
public final void save(String htmlFilePath)
```


지정된 경로에 파일로 이 HTML 문서를 저장하며, HTML 마크업이
저장되고, 리소스가 포함된 부속 폴더에도 저장됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML 마크업이 저장될 파일의 전체 경로입니다. 파일이 존재하면 생성되거나 덮어쓰기됩니다. HTML 파일이 있는 동일한 폴더에 연관 리소스 폴더가 생성됩니다. |
|

### save(String htmlFilePath, String resourcesFolderPath) {#save-java.lang.String-java.lang.String-}
```
public final void save(String htmlFilePath, String resourcesFolderPath)
```


지정된 경로에 파일로 이 HTML 문서를 저장하며, HTML 마크업이
저장되며, 리소스가 포함된 부속 폴더는
지정된 경로에 위치합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML 마크업이 저장될 파일의 전체 경로입니다. NULL이거나 비어 있을 수 없습니다. 파일이 존재하면 생성되거나 덮어쓰기됩니다. |
|
|  | resourcesFolderPath | java.lang.String | 모든 관련 리소스가 저장될 부속 폴더의 전체 경로입니다. NULL이거나 비어 있으면 \*.html 파일이 있는 동일한 디렉터리에 폴더가 자동으로 생성됩니다. 지정했지만 존재하지 않으면 생성됩니다. |
|

### save(Writer htmlMarkup, HtmlSaveOptions saveOptions) {#save-java.io.Writer-com.groupdocs.editor.options.HtmlSaveOptions-}
```
public void save(Writer htmlMarkup, HtmlSaveOptions saveOptions)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| htmlMarkup | java.io.Writer |  |
| saveOptions | [HtmlSaveOptions](../../com.groupdocs.editor.options/htmlsaveoptions) |  |

### fromMarkup(String newHtmlContent, List<IHtmlResource> resources) {#fromMarkup-java.lang.String-java.util.List-com.groupdocs.editor.htmlcss.resources.IHtmlResource--}
```
public static EditableDocument fromMarkup(String newHtmlContent, List<IHtmlResource> resources)
```


EditableDocument 인스턴스를 생성하는 정적 팩토리,
지정된 HTML 마크업과 해당되는 연결된 리소스 집합으로부터


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, 구문 분석해야 하는 원시 HTML 마크업을 포함합니다. NULL이거나 비어 있거나 유효하지 않을 수 없습니다. |
|
|  | resources | java.util.List<com.groupdocs.editor.htmlcss.resources.IHtmlResource> | newHtmlContent 매개변수에 지정된 HTML 문서에서 사용되는 모든 리소스(이미지, 스타일시트, 글꼴)의 컬렉션입니다. 없을 수도 있습니다 (NULL이거나 빈 컬렉션). |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath) {#fromMarkupAndResourceFolder-java.lang.String-java.lang.String-}
```
public static EditableDocument fromMarkupAndResourceFolder(String newHtmlContent, String resourceFolderPath)
```


전체 경로로 지정된 폴더에 위치한 리소스로부터 지정된 HTML 마크업을 사용하여 EditableDocument 인스턴스를 생성하는 정적 팩토리


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | newHtmlContent | java.lang.String | String, 구문 분석해야 하는 원시 HTML 마크업을 포함합니다. NULL이거나 비어 있거나 유효하지 않을 수 없습니다. |
|
|  | resourceFolderPath | java.lang.String | 리소스가 있는 폴더에 대한 필수 경로입니다. 이 폴더에 위치한 모든 스타일시트가 사용됩니다. NULL이거나 빈 문자열일 수 없으며, 이 폴더가 존재해야 합니다. |

<br />

*** ** * ** ***

HTML 문서의 내용이 문자열로 제공되고 모든 리소스가 특정 폴더에 위치하며, HTML 마크업 내의 이러한 리소스에 대한 링크가 잘못되었거나 없을 때 유용한 정적 팩토리입니다. 이 메서드를 호출하면 지정된 폴더를 스캔하고 발견된 모든 스타일시트를 문서에 자동으로 적용합니다. 이 메서드는 일반적으로 문서 메타데이터 등을 잘라내는 다양한 HTML 편집기에서 콘텐츠를 가져올 때 매우 유용합니다.

<br />

|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### fromFile(String htmlFilePath, String resourceFolderPath) {#fromFile-java.lang.String-java.lang.String-}
```
public static EditableDocument fromFile(String htmlFilePath, String resourceFolderPath)
```


HTML로부터 EditableDocument 인스턴스를 생성하는 정적 팩토리
파일, 즉 \*.html 파일 자체와 폴더에 대한 경로로 지정된 파일
연결된 리소스와 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | htmlFilePath | java.lang.String | HTML 파일에 대한 전체 경로를 포함하는 문자열입니다. null일 수 없으며, 유효한 파일 경로여야 하고 파일 자체가 존재해야 합니다. |
|
|  | resourceFolderPath | java.lang.String | HTML 리소스가 있는 폴더에 대한 선택적 경로입니다. NULL이거나 유효하지 않거나 해당 폴더가 존재하지 않으면, Editor가 HTML 마크업을 분석하여 스스로 이 폴더를 찾으려고 시도합니다. |
|

**Returns:**
[EditableDocument](../../com.groupdocs.editor/editabledocument) - New non-null instance of EditableDocument

### dispose() {#dispose--}
```
public final void dispose()
```


이 Editable 문서 인스턴스를 해제하고, 해당 내용도 해제하며
그 메서드와 속성을 사용할 수 없게 만듭니다


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


이 Editable 문서가 이미 해제되었는지 (true) 여부를 판단하거나
아니면 (false)


**Returns:**
boolean
