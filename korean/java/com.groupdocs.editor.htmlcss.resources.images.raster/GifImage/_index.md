---
title: "GifImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "GIF 그래픽스 인터체인지 포맷 형식의 이미지를 메타데이터 및 추가 메서드와 함께 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

GIF (Graphics Interchange Format) 형식의 이미지를 나타냅니다.
메타데이터 및 추가 메서드

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | base64 인코딩된 형태로 표현된 콘텐츠에서 새로운 GifImage 인스턴스를 생성합니다. |
문자열이며, 지정된 이름과 함께
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | 바이트 스트림으로 표현된 콘텐츠에서 새로운 GifImage 인스턴스를 생성합니다. |
그리고 지정된 이름과 함께
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 GIF 이미지인지 확인합니다. |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 GIF 이미지인지 확인합니다. |
|
|  | [getType()](#getType--) | ImageType.Gif를 반환합니다. |
|
|  | [getVersion()](#getVersion--) | 이 GIF 이미지의 내부 버전을 반환합니다 (버전은 다음에서 추출됨 |
헤더)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


base64 인코딩된 형태로 표현된 콘텐츠에서 새로운 GifImage 인스턴스를 생성합니다.
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | GIF 이미지의 이름. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | 콘텐츠를 base64 인코딩 문자열로 제공합니다. null이거나 비어 있거나 공백일 수 없습니다. GIF 콘텐츠가 아닌 경우 예외가 발생합니다. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
```


바이트 스트림으로 표현된 콘텐츠에서 새로운 GifImage 인스턴스를 생성합니다.
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | GIF 이미지의 이름. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 GIF 이미지인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 바이트 스트림으로, GIF 이미지가 포함되어 있을 것으로 예상됩니다. |
|

**Returns:**
boolean - 지정된 스트림에 유효한 GIF 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 GIF 이미지인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 예상되는 GIF 이미지의 내용을 base64 인코딩 문자열 형태로 제공합니다. |
|

**Returns:**
boolean - 지정된 문자열에 유효한 GIF 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Gif를 반환합니다.


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


이 GIF 이미지의 내부 버전을 반환합니다 (버전은 다음에서 추출됨
헤더)


**Returns:**
java.lang.String
