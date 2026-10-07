---
title: "WmfImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "WMF Windows MetaFile 형식의 메타데이터 및 추가 메서드를 포함한 하나의 벡터 이미지를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

WMF (Windows MetaFile) 형식의 하나의 벡터 이미지를 나타냅니다.
메타데이터 및 추가 메서드

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | 내용을 base64 인코딩된 형태로 표현한 새로운 WmfImage 인스턴스를 생성합니다 |
문자열이며, 지정된 이름과 함께
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | 내용을 바이트 스트림으로 표현한 새로운 WmfImage 인스턴스를 생성합니다, |
그리고 지정된 이름과 함께
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 WMF 이미지인지 확인합니다 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 WMF 이미지인지 확인합니다 |
|
|  | [getType()](#getType--) | ImageType.Wmf를 반환합니다 |
|
|  | [getByteContent()](#getByteContent--) | 이 WMF 이미지의 내용을 바이너리 스트림으로 반환합니다 |
|
|  | [getTextContent()](#getTextContent--) | 이 WMF 이미지의 내용을 일반 텍스트로 반환합니다 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 WMF 이미지를 파일에 저장합니다 |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 이 벡터 WMF 이미지를 래스터 PNG 이미지로 저장합니다 |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 이 벡터 WMF 이미지를 벡터 SVG 이미지로 저장합니다 |
|
|  | [dispose()](#dispose--) | 이 WMF 이미지를 내용과 대부분을 해제하여 폐기합니다 |
메서드와 속성을 작동하지 않게 합니다.
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


내용을 base64 인코딩된 형태로 표현한 새로운 WmfImage 인스턴스를 생성합니다
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | WMF 이미지의 이름입니다. null, 비어 있거나 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | base64 인코딩 문자열 형태의 내용입니다. null, 비어 있거나 공백일 수 없습니다. WMF 내용이 아니면 예외가 발생합니다. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


내용을 바이트 스트림으로 표현한 새로운 WmfImage 인스턴스를 생성합니다,
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | WMF 이미지의 이름입니다. null, 비어 있거나 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 WMF 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 입력 바이트 스트림입니다. NULL이 아니어야 하며 읽기와 탐색을 지원해야 합니다. |
|

**Returns:**
boolean - 지정된 스트림이 유효한 WMF 이미지를 포함하면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 WMF 이미지인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 입력 문자열로, WMF 이미지의 내용이 base64 인코딩으로 저장됩니다. NULL이거나 비어 있을 수 없습니다. |
|

**Returns:**
boolean - 지정된 문자열이 유효한 WMF 이미지를 포함하면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Wmf를 반환합니다


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


이 WMF 이미지의 내용을 바이너리 스트림으로 반환합니다


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


이 WMF 이미지의 내용을 일반 텍스트로 반환합니다


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


이 WMF 이미지를 파일에 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 이 WMF 이미지의 내용으로 생성(존재하지 않을 경우)하거나 덮어쓰기(존재할 경우)될 파일의 전체 경로 |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


이 벡터 WMF 이미지를 래스터 PNG 이미지로 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 출력 스트림으로, PNG 이미지의 내용이 기록됩니다. NULL일 수 없으며 쓰기 가능해야 합니다. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


이 벡터 WMF 이미지를 벡터 SVG 이미지로 저장합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | 출력 스트림으로, SVG 이미지의 내용이 기록됩니다. NULL일 수 없으며 쓰기 가능해야 합니다. |
|

### dispose() {#dispose--}
```
public void dispose()
```


이 WMF 이미지를 내용과 대부분을 해제하여 폐기합니다
메서드와 속성을 작동하지 않게 합니다.


