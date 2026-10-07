---
title: "BmpImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "BMP BitMap Picture 형식의 이미지를 메타데이터 및 추가 메서드와 함께 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

BMP (BitMap Picture) 형식의 이미지를 메타데이터와 함께 나타냅니다.
추가 메서드

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | 콘텐츠를 base64 인코딩 형태로 표현하여 새로운 BmpImage 인스턴스를 생성합니다. |
문자열이며, 지정된 이름과 함께
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | 콘텐츠에서 새 BmpImage 인스턴스를 생성하고, 바이트 스트림으로 표시합니다, |
그리고 지정된 이름과 함께
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 BMP 이미지인지 확인합니다 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 BMP 이미지인지 확인합니다 |
|
|  | [getType()](#getType--) | ImageType.Bmp를 반환합니다 |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


콘텐츠를 base64 인코딩 형태로 표현하여 새로운 BmpImage 인스턴스를 생성합니다.
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | BMP 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | 콘텐츠를 base64 인코딩 문자열로 제공합니다. null, 빈 문자열 또는 공백일 수 없습니다. BMP 콘텐츠가 아닌 경우 예외가 발생합니다. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


콘텐츠에서 새 BmpImage 인스턴스를 생성하고, 바이트 스트림으로 표시합니다,
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | BMP 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 BMP 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | BMP 이미지를 포함하고 있을 것으로 추정되는 바이트 스트림 |
|

**Returns:**
boolean - 지정된 스트림에 유효한 BMP 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 BMP 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 추정되는 BMP 이미지의 콘텐츠를 base64 인코딩 문자열 형태로 제공합니다 |
|

**Returns:**
boolean - 지정된 문자열에 유효한 BMP 이미지가 포함되어 있으면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Bmp를 반환합니다


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
