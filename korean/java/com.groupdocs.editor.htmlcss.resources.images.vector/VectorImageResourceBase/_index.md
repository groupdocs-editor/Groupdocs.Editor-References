---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "지원되는 모든 벡터 이미지에 대한 기본 클래스입니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

지원되는 모든 벡터 이미지에 대한 기본 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 이 벡터 이미지의 이름을 반환합니다. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 이 벡터 이미지의 올바른 파일 이름을 반환합니다, 이는 이름과 |
확장자.
|
|  | [getAspectRatio()](#getAspectRatio--) | 이 벡터 이미지의 가로 세로 비율을 반환합니다. |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 이 벡터 이미지의 선형 차원(너비와 높이)을 반환합니다. |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 지정된 인스턴스와 레퍼런스 동등성을 확인합니다. |
|
|  | [isDisposed()](#isDisposed--) | 이 래스터 이미지가 해제되었는지 여부를 결정합니다. |
|
|  | [getType()](#getType--) | 구현 유형에서는 벡터 유형에 대한 정보를 반환해야 합니다. |
이미지
|
|  | [getByteContent()](#getByteContent--) | 구현 유형에서는 이 벡터 이미지의 내용을 바이트 형태로 반환해야 합니다. |
stream
|
|  | [getTextContent()](#getTextContent--) | 구현 유형에서는 이 벡터 이미지의 내용을 텍스트 형태로 반환해야 합니다. |
형식: 이미지 유형에 관한 XML을 base64 인코딩한 것
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 구현 유형에서는 지정된 경로에 이 이미지를 디스크에 저장해야 합니다. |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 구현 유형에서는 현재 벡터 이미지를 래스터 PNG로 저장해야 합니다. |
지정된 바이트 스트림으로 포맷합니다.
|
|  | [dispose()](#dispose--) | 구현 유형에서는 이 인스턴스를 해제해야 합니다. |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


이 벡터 이미지의 이름을 반환합니다. 일반적으로 파일 이름을 포함하지 않습니다.
확장자는 이론적으로 파일 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


이 벡터 이미지의 올바른 파일 이름을 반환합니다, 이는 이름과
확장자. 이론적으로 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


이 벡터 이미지의 가로 세로 비율을 반환합니다.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


이 벡터 이미지의 선형 차원(너비와 높이)을 반환합니다.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


지정된 인스턴스와 레퍼런스 동등성을 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 다른 벡터 이미지 인스턴스 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


이 래스터 이미지가 해제되었는지 여부를 결정합니다.


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


구현 유형에서는 벡터 유형에 대한 정보를 반환해야 합니다.
이미지


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


구현 유형에서는 이 벡터 이미지의 내용을 바이트 형태로 반환해야 합니다.
stream


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


구현 유형에서는 이 벡터 이미지의 내용을 텍스트 형태로 반환해야 합니다.
형식: 이미지 유형에 관한 XML을 base64 인코딩한 것


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


구현 유형에서는 지정된 경로에 이 이미지를 디스크에 저장해야 합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


구현 유형에서는 현재 벡터 이미지를 래스터 PNG로 저장해야 합니다.
지정된 바이트 스트림으로 포맷합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 바이트 스트림으로, 이 래스터 이미지의 PNG 버전이 저장됩니다. NULL이면 안 되며 쓰기를 지원해야 합니다. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


구현 유형에서는 이 인스턴스를 해제해야 합니다.


