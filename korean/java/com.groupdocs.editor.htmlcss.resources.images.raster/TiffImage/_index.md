---
title: "TiffImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "TIFF Tagged Image File Format 형식의 이미지 하나를 메타데이터 및 추가 메서드와 함께 나타냅니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

TIFF (Tagged Image File Format) 형식의 이미지를 하나 나타냅니다.
메타데이터 및 추가 메서드


*** ** * ** ***

자세한 내용은 https://en.wikipedia.org/wiki/TIFF 를 참조하십시오. 매우 드문 경우에 TIFF가 WordProcessing 문서 내부에 존재할 수 있습니다.

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | 내용으로부터 새로운 TiffImage 인스턴스를 생성합니다, 표현 형식은 |
base64 인코딩 문자열이며, 지정된 이름과 함께
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | 바이트 스트림으로 표현된 콘텐츠에서 새로운 GifImage 인스턴스를 생성합니다. |
그리고 지정된 이름과 함께
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 TIFF 이미지인지 확인합니다 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 TIFF 이미지인지 확인합니다 |
|
|  | [getType()](#getType--) | ImageType.Tiff 를 반환합니다 |
|
|  | [getFramesCount()](#getFramesCount--) | 이 TIFF 이미지 안에 포함된 프레임(이미지) 수를 반환합니다. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


내용으로부터 새로운 TiffImage 인스턴스를 생성합니다, 표현 형식은
base64 인코딩 문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | TIFF 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | 내용을 base64 인코딩 문자열로 제공합니다. null, 빈 문자열 또는 공백일 수 없습니다. TIFF 내용이 아닌 경우 예외가 발생합니다. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
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

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 TIFF 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | TIFF 이미지를 포함하고 있을 것으로 추정되는 바이트 스트림 |
|

**Returns:**
boolean - 지정된 스트림에 유효한 TIFF 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 TIFF 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 추정되는 TIFF 이미지의 내용을 base64 인코딩 문자열 형태로 제공합니다 |
|

**Returns:**
boolean - 지정된 문자열에 유효한 TIFF 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Tiff 를 반환합니다


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


이 TIFF 이미지 안에 포함된 프레임(이미지) 수를 반환합니다. 이는
1보다 작을 수 없습니다.


**Returns:**
int -
