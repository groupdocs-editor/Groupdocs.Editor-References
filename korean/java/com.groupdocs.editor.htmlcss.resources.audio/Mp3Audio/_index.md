---
title: "Mp3Audio"
second_title: "GroupDocs.Editor for Java API 참조"
description: "임의 형식의 오디오 리소스 하나를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public final class Mp3Audio implements IHtmlResource
```

임의 형식의 오디오 리소스 하나를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)](#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-) | 바이트 스트림으로 표현된 MP3 콘텐츠와 지정된 이름을 사용하여 새로운 Mp3Audio 클래스를 생성합니다 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(System.IO.Stream binaryContent)](#isValid-com.aspose.ms.System.IO.Stream-) | 지정된 스트림이 유효한 MP3 콘텐츠인지 확인합니다 |
|
|  | [getName()](#getName--) | 이 MP3 콘텐츠의 이름을 반환합니다. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 이 MP3 콘텐츠의 이름과 확장자로 구성된 올바른 파일 이름을 반환합니다. |
|
|  | [getType()](#getType--) | AudioFormat.Mp3을 반환합니다 (공변 반환을 통해 IHtmlResource.getFormat()도 만족합니다) |
|
|  | [getByteContent()](#getByteContent--) | 이 폰트의 내용을 바이트 스트림으로 반환합니다 |
|
|  | [getByteContentInternal()](#getByteContentInternal--) | 원래 위치를 유지한 채 이 MP3 오디오 리소스의 내용을 바이트 스트림으로 반환합니다 |
|
|  | [getTextContent()](#getTextContent--) | 이 MP3 리소스의 내용을 base64 인코딩 문자열로 반환합니다. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 MP3 리소스를 지정된 파일에 저장합니다 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 지정된 HTML 리소스와 이 인스턴스가 참조 동일성인지 확인합니다 |
|
|  | [equals(Mp3Audio other)](#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-) | 지정된 폰트 리소스와 이 인스턴스가 참조 동일성인지 확인합니다 |
|
|  | [dispose()](#dispose--) | 이 MP3 리소스를 해제하고, 해당 콘텐츠를 해제하여 대부분의 메서드와 속성을 사용할 수 없게 합니다. |
|
|  | [isDisposed()](#isDisposed--) | 이 MP3 콘텐츠가 해제되었는지 여부를 결정합니다. |
|
| [addDisposedListener(EventHandler value)](#addDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
| [removeDisposedListener(EventHandler value)](#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-) |  |
### Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen) {#Mp3Audio-java.lang.String-com.aspose.ms.System.IO.Stream-boolean-}
```
public Mp3Audio(String name, System.IO.Stream binaryContent, boolean leaveOpen)
```


바이트 스트림으로 표현된 MP3 콘텐츠와 지정된 이름을 사용하여 새로운 Mp3Audio 클래스를 생성합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | MP3 콘텐츠의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | com.aspose.ms.System.IO.Stream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|
|  | leaveOpen | boolean | Mp3Audio 인스턴스가 해제될 때 지정된 스트림을 해제할지 여부를 결정합니다. |
|

### isValid(System.IO.Stream binaryContent) {#isValid-com.aspose.ms.System.IO.Stream-}
```
public static boolean isValid(System.IO.Stream binaryContent)
```


지정된 스트림이 유효한 MP3 콘텐츠인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | com.aspose.ms.System.IO.Stream | MP3 콘텐츠를 포함하고 있을 것으로 추정되는 바이트 스트림 |
|

**Returns:**
boolean - 지정된 스트림에 유효한 MP3 콘텐츠가 포함되어 있으면 true, 그렇지 않으면 false

### getName() {#getName--}
```
public String getName()
```


이 MP3 콘텐츠의 이름을 반환합니다. 일반적으로 파일 확장자를 포함하지 않으며 이론적으로 파일 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public String getFilenameWithExtension()
```


이 MP3 콘텐츠의 올바른 파일 이름을 반환합니다. 이름과 확장자로 구성됩니다. 이론적으로 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public AudioType getType()
```


AudioFormat.Mp3을 반환합니다 (공변 반환을 통해 IHtmlResource.getFormat()도 만족합니다)


**Returns:**
[AudioType](../../com.groupdocs.editor.htmlcss.resources.audio/audiotype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


이 폰트의 내용을 바이트 스트림으로 반환합니다


**Returns:**
java.io.InputStream
### getByteContentInternal() {#getByteContentInternal--}
```
public System.IO.Stream getByteContentInternal()
```


원래 위치를 유지한 채 이 MP3 오디오 리소스의 내용을 바이트 스트림으로 반환합니다


**Returns:**
com.aspose.ms.System.IO.Stream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


이 MP3 리소스의 콘텐츠를 base64 인코딩 문자열로 반환합니다. 이 값은 첫 호출 이후 캐시됩니다.


**Returns:**
java.lang.String
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


이 MP3 리소스를 지정된 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 생성되거나 다시 기록될 파일의 전체 경로 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public boolean equals(IHtmlResource other)
```


지정된 HTML 리소스와 이 인스턴스가 참조 동일성인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource 인터페이스의 다른 구현체 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(Mp3Audio other) {#equals-com.groupdocs.editor.htmlcss.resources.audio.Mp3Audio-}
```
public boolean equals(Mp3Audio other)
```


지정된 폰트 리소스와 이 인스턴스가 참조 동일성인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [Mp3Audio](../../com.groupdocs.editor.htmlcss.resources.audio/mp3audio) | Mp3Audio 클래스의 다른 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### dispose() {#dispose--}
```
public void dispose()
```


이 MP3 리소스를 해제하고, 해당 콘텐츠를 해제하여 대부분의 메서드와 속성을 사용할 수 없게 합니다.


### isDisposed() {#isDisposed--}
```
public boolean isDisposed()
```


이 MP3 콘텐츠가 해제되었는지 여부를 결정합니다.


**Returns:**
boolean
### addDisposedListener(EventHandler value) {#addDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void addDisposedListener(EventHandler value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

### removeDisposedListener(EventHandler value) {#removeDisposedListener-com.groupdocs.editor.handler.EventHandler-}
```
public void removeDisposedListener(EventHandler value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [EventHandler](../../com.groupdocs.editor.handler/eventhandler) |  |

