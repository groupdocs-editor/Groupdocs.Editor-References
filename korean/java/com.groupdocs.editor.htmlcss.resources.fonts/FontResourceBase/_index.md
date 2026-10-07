---
title: "FontResourceBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "HTML 문서의 리소스로 사용되는 모든 지원되는 글꼴 유형에 대한 기본 클래스이며 모든 속성을 포함합니다"
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

HTML 문서의 리소스로 사용되는 모든 지원되는 글꼴 유형에 대한 기본 클래스
모든 속성을 포함합니다

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Disposed](#Disposed) | 이 글꼴이 해제될 때 발생하는 이벤트 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 이 글꼴 리소스의 이름을 반환합니다. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 이 글꼴 리소스의 올바른 파일명을 반환합니다. 파일명은 이름으로 구성됩니다 |
및 확장자를 포함합니다.
|
|  | [getByteContent()](#getByteContent--) | 이 폰트의 내용을 바이트 스트림으로 반환합니다 |
|
|  | [getTextContent()](#getTextContent--) | 이 글꼴의 내용을 base64 인코딩 문자열로 반환합니다. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 글꼴을 지정된 파일에 저장합니다 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 지정된 HTML 리소스와 이 인스턴스가 참조 동일성인지 확인합니다 |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | 지정된 폰트 리소스와 이 인스턴스가 참조 동일성인지 확인합니다 |
|
|  | [dispose()](#dispose--) | 이 글꼴 리소스를 해제하고, 그 내용도 해제하며 대부분을 |
메서드와 속성을 작동하지 않게 합니다.
|
|  | [isDisposed()](#isDisposed--) | 이 글꼴이 해제되었는지 여부를 결정합니다 |
|
|  | [getType()](#getType--) | 구현 유형은 특정 유형에 대한 정보를 반환해야 합니다 |
특정 FontType 유형의 인스턴스로서 글꼴 리소스를 반환합니다, 이는
모든 유형별 정보를 캡슐화합니다
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


이 글꼴이 해제될 때 발생하는 이벤트


### getName() {#getName--}
```
public final String getName()
```


이 글꼴 리소스의 이름을 반환합니다. 일반적으로 파일명을 포함하지 않습니다
확장자는 이론적으로 파일 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


이 글꼴 리소스의 올바른 파일명을 반환합니다. 파일명은 이름으로 구성됩니다
및 확장자. 이론적으로 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


이 폰트의 내용을 바이트 스트림으로 반환합니다


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


이 글꼴의 내용을 base64 인코딩 문자열로 반환합니다. 이 값은
첫 호출 후 캐시됩니다.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


이 글꼴을 지정된 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 생성되거나 다시 기록될 파일의 전체 경로 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


지정된 HTML 리소스와 이 인스턴스가 참조 동일성인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | IHtmlResource 인터페이스의 다른 구현체 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


지정된 폰트 리소스와 이 인스턴스가 참조 동일성인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | FontResourceBase 추상 클래스의 다른 파생 클래스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### dispose() {#dispose--}
```
public final void dispose()
```


이 글꼴 리소스를 해제하고, 그 내용도 해제하며 대부분을
메서드와 속성을 작동하지 않게 합니다.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


이 글꼴이 해제되었는지 여부를 결정합니다


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


구현 유형은 특정 유형에 대한 정보를 반환해야 합니다
특정 FontType 유형의 인스턴스로서 글꼴 리소스를 반환합니다, 이는
모든 유형별 정보를 캡슐화합니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
