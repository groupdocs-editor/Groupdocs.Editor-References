---
title: "SvgImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "SVG Scalable Vector Graphics 형식의 메타데이터와 추가 메서드를 포함한 하나의 벡터 이미지를 나타냅니다"
type: docs
weight: 12
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

SVG (Scalable Vector Graphics) 형식의 하나의 벡터 이미지를 나타냅니다
메타데이터 및 추가 메서드

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | 내용을 일반 문자열로 표현한 새로운 SvgImage 인스턴스를 생성합니다, |
그리고 지정된 이름과 함께
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | 내용을 바이트 스트림으로 표현한 새로운 SvgImage 인스턴스를 생성합니다, |
그리고 지정된 이름과 함께
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | 지정된 텍스트 XML 호환 내용에 대한 표면 검사를 수행합니다 |
SVG 이미지를 나타냅니다
|
|  | [getType()](#getType--) | ImageType.Svg를 반환합니다 |
|
|  | [getByteContent()](#getByteContent--) | 이 SVG 이미지의 내용을 바이너리 스트림으로 반환합니다 |
|
|  | [getTextContent()](#getTextContent--) | 이 SVG 이미지의 내용을 일반 텍스트(XML 형식)로 반환합니다 |
|
|  | [getXmlContent()](#getXmlContent--) | 이 SVG 이미지의 내용을 원래 XML 호환 형식으로 반환합니다 |
텍스트 형식
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 SVG 이미지를 파일에 저장합니다 |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 이 벡터 SVG 이미지를 래스터 PNG 이미지로 저장합니다 |
|
|  | [dispose()](#dispose--) | 이 래스터 이미지를 해제하고, 그 콘텐츠를 해제하며 대부분의 메서드를 사용할 수 없게 합니다 |
및 속성이 작동하지 않음
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


내용을 일반 문자열로 표현한 새로운 SvgImage 인스턴스를 생성합니다,
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | SVG 이미지의 이름. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | 내용 | java.lang.String | SVG 이미지의 유효한 XML 호환 내용을 포함하는 일반 문자열 형태의 내용. null, 빈 문자열 또는 공백일 수 없습니다. SVG 내용이 아닌 경우 예외가 발생합니다. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


내용을 바이트 스트림으로 표현한 새로운 SvgImage 인스턴스를 생성합니다,
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | SVG 이미지의 이름. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


지정된 텍스트 XML 호환 내용에 대한 표면 검사를 수행합니다
SVG 이미지를 나타냅니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 내용 | java.lang.String | SVG 이미지의 XML 내용을 단순 텍스트 형태로 제공하며, base64 인코딩된 내용이 아닙니다. |
|

**Returns:**
boolean - 지정된 문자열을 처음에 유효한 SVG로 간주할 수 있으면 True, 확실히 SVG가 아니면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Svg를 반환합니다


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


이 SVG 이미지의 내용을 바이너리 스트림으로 반환합니다


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


이 SVG 이미지의 내용을 일반 텍스트(XML 형식)로 반환합니다


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


이 SVG 이미지의 내용을 원래 XML 호환 형식으로 반환합니다
텍스트 형식


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


이 SVG 이미지를 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 이 SVG 이미지의 내용으로 생성(존재하지 않을 경우)하거나 덮어쓰기(존재할 경우)될 파일의 전체 경로 |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


이 벡터 SVG 이미지를 래스터 PNG 이미지로 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 출력 스트림으로, PNG 이미지의 내용이 기록됩니다. NULL일 수 없으며 쓰기 가능해야 합니다. |
|

### dispose() {#dispose--}
```
public void dispose()
```


이 래스터 이미지를 해제하고, 그 콘텐츠를 해제하며 대부분의 메서드를 사용할 수 없게 합니다
및 속성이 작동하지 않음


