---
title: "JpegImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "JPEG Joint Photographic Experts Group 형식의 이미지를 하나 나타내며, 메타데이터와 추가 메서드를 포함합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

JPEG (Joint Photographic Experts Group) 형식의 이미지를 하나 나타내며
그 메타데이터와 추가 메서드를 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | 내용으로부터 새로운 JpegImage 인스턴스를 생성합니다, 표현 형식은 |
base64 인코딩 문자열이며, 지정된 이름과 함께
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | 내용으로부터 새로운 JpegImage 인스턴스를 생성합니다, 바이트 스트림으로 표현된, |
그리고 지정된 이름과 함께
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 JPEG 이미지인지 확인합니다 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 JPEG 이미지인지 확인합니다 |
|
|  | [getType()](#getType--) | ImageType.Jpeg 를 반환합니다 |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


내용으로부터 새로운 JpegImage 인스턴스를 생성합니다, 표현 형식은
base64 인코딩 문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | JPEG 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | base64 인코딩된 문자열 형태의 콘텐츠. null이거나 비어 있거나 공백일 수 없습니다. JPEG 콘텐츠가 아닌 경우 예외가 발생합니다. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


내용으로부터 새로운 JpegImage 인스턴스를 생성합니다, 바이트 스트림으로 표현된,
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | JPEG 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 JPEG 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | JPEG 이미지를 포함하고 있을 것으로 추정되는 바이트 스트림 |
|

**Returns:**
boolean - 지정된 스트림에 유효한 JPEG 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 JPEG 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 추정되는 JPEG 이미지의 콘텐츠를 base64 인코딩된 문자열 형태로 |
|

**Returns:**
boolean - 지정된 문자열에 유효한 JPEG 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Jpeg 를 반환합니다


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
