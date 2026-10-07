---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "고정된 이름, 차원, 종횡비, 유형, 크기 및 콘텐츠를 가진 모든 지원되는 래스터 이미지의 기본 클래스입니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

고정된 이름, 차원, 종횡비를 가진 모든 지원되는 래스터 이미지의 기본 클래스
비율, 유형, 크기 및 콘텐츠.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Disposed](#Disposed) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 이 래스터 이미지의 이름을 반환합니다. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | 이 래스터 이미지의 올바른 파일 이름을 반환합니다. 파일 이름은 이름과 |
확장자.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | 이 래스터 이미지의 선형 차원(너비와 높이)을 반환합니다 |
|
|  | [getAspectRatio()](#getAspectRatio--) | 이 이미지의 종횡비를 너비 대비 높이 비율로 반환합니다 |
|
|  | [getLength()](#getLength--) | 이 래스터 이미지 파일의 길이를 바이트 단위로 반환합니다 |
|
|  | [getByteContent()](#getByteContent--) | 이 래스터 이미지의 콘텐츠를 바이트 스트림으로 반환합니다 |
|
|  | [getTextContent()](#getTextContent--) | 이 래스터 이미지의 콘텐츠를 base64 인코딩 문자열로 반환합니다 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 래스터 이미지를 지정된 파일에 저장합니다 |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | 지정된 인스턴스와 레퍼런스 동등성을 확인합니다. |
|
|  | [dispose()](#dispose--) | 이 래스터 이미지를 해제하고, 그 콘텐츠를 해제하며 대부분의 메서드를 사용할 수 없게 합니다 |
및 속성이 작동하지 않음
|
|  | [isDisposed()](#isDisposed--) | 이 래스터 이미지가 해제되었는지 여부를 결정합니다. |
|
|  | [getType()](#getType--) | 구현 시 유형은 래스터 유형에 대한 정보를 반환해야 합니다. |
이미지
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


이 래스터 이미지의 이름을 반환합니다. 일반적으로 파일 이름을 포함하지 않습니다.
확장자는 이론적으로 파일 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


이 래스터 이미지의 올바른 파일 이름을 반환합니다. 파일 이름은 이름과
확장자. 이론적으로 이름과 다를 수 있습니다.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


이 래스터 이미지의 선형 차원(너비와 높이)을 반환합니다


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


이 이미지의 종횡비를 너비 대비 높이 비율로 반환합니다


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


이 래스터 이미지 파일의 길이를 바이트 단위로 반환합니다


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


이 래스터 이미지의 콘텐츠를 바이트 스트림으로 반환합니다


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


이 래스터 이미지의 콘텐츠를 base64 인코딩 문자열로 반환합니다


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


이 래스터 이미지를 지정된 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 생성되거나 다시 기록될 파일의 전체 경로 |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


지정된 인스턴스와 레퍼런스 동등성을 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | 다른 IHtmlResource 상속자 |
|

**Returns:**
boolean - 같으면 true, 다르면 false

### dispose() {#dispose--}
```
public final void dispose()
```


이 래스터 이미지를 해제하고, 그 콘텐츠를 해제하며 대부분의 메서드를 사용할 수 없게 합니다
및 속성이 작동하지 않음


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


구현 시 유형은 래스터 유형에 대한 정보를 반환해야 합니다.
이미지


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
