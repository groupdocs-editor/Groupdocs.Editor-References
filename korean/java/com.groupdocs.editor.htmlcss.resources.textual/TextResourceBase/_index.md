---
title: "TextResourceBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "텍스트 내용과 인코딩을 가진 모든 지원 텍스트 리소스의 기본 클래스"
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

텍스트 내용과 인코딩을 가진 모든 지원 텍스트 리소스의 기본 클래스

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | 지정된 텍스트 콘텐츠와 인코딩을 사용하여 새로운 텍스트 리소스를 생성합니다. |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | 지정된 바이트 스트림과 인코딩을 사용하여 새로운 텍스트 리소스를 생성합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 파일 확장자 없이 이 텍스트 리소스의 이름을 반환합니다. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 이 텍스트 리소스의 올바른 파일 이름을 반환합니다, 이름으로 구성됨 |
및 확장자
|
|  | [getEncoding()](#getEncoding--) | 이 텍스트 리소스의 인코딩을 반환합니다. |
|
|  | [getByteContent()](#getByteContent--) | 원본과 함께 이 텍스트 리소스의 내용을 바이트 스트림으로 반환합니다. |
encoding
|
|  | [getTextContent()](#getTextContent--) | 이 텍스트 리소스의 내용을 표준 문자열로 반환합니다 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 텍스트 리소스를 지정된 파일에 저장합니다 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 이 인스턴스를 지정된 것과 동등성 여부를 확인합니다. |
|
|  | [dispose()](#dispose--) | 이 텍스트 리소스를 해제하고, 그 내용도 해제하여 대부분의 |
메서드와 속성이 작동하지 않게 됩니다.
|
|  | [isDisposed()](#isDisposed--) | 이 텍스트 리소스가 해제되었는지 여부를 결정합니다 |
|
|  | [getType()](#getType--) | 구현 유형은 텍스트 유형에 대한 정보를 반환해야 합니다 |
resource
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


지정된 텍스트 콘텐츠와 인코딩을 사용하여 새로운 텍스트 리소스를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 리소스의 고유 식별자로 사용되는 필수 이름입니다. 일반적으로 파일 이름입니다. |
|
|  | textualContent | java.lang.String | 리소스의 텍스트 내용이며, NULL이거나 비어 있을 수 없습니다 |
|
|  | originalEncoding | java.nio.charset.Charset | 리소스의 원본 인코딩이며, NULL이거나 비어 있을 수 없습니다 |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


지정된 바이트 스트림과 인코딩을 사용하여 새로운 텍스트 리소스를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 리소스의 고유 식별자로 사용되는 필수 이름입니다. 일반적으로 파일 이름입니다. |
|
|  | binaryContent | java.io.InputStream | 리소스의 이진 내용을 바이트 스트림으로 제공합니다. NULL이 될 수 없으며, 해제되지 않아야 하고, 읽기 및 탐색이 가능해야 합니다. |
|
|  | originalEncoding | java.nio.charset.Charset | 리소스의 원본 인코딩이며, NULL이거나 비어 있을 수 없습니다 |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


파일 확장자 없이 이 텍스트 리소스의 이름을 반환합니다.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


이 텍스트 리소스의 올바른 파일 이름을 반환합니다, 이름으로 구성됨
및 확장자


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


이 텍스트 리소스의 인코딩을 반환합니다. 일반적으로 UTF-8을 반환합니다.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


원본과 함께 이 텍스트 리소스의 내용을 바이트 스트림으로 반환합니다.
encoding


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


이 텍스트 리소스의 내용을 표준 문자열로 반환합니다


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


이 텍스트 리소스를 지정된 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 이미 존재하는 경우에도 생성되거나 다시 쓰여질 파일의 전체 경로 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


이 인스턴스를 지정된 것과 동등성 여부를 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 알 수 없는 유형의 다른 HTML 리소스로, 또한 TextResourceBase를 상속한 것으로 추정됩니다 |
|

**Returns:**
boolean - 같으면 true를 반환하고, 다르면 false를 반환합니다

### dispose() {#dispose--}
```
public final void dispose()
```


이 텍스트 리소스를 해제하고, 그 내용도 해제하여 대부분의
메서드와 속성이 작동하지 않습니다. 여러 번 호출해도 허용됩니다.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


이 텍스트 리소스가 해제되었는지 여부를 결정합니다


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


구현 유형은 텍스트 유형에 대한 정보를 반환해야 합니다
resource


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
