---
title: "EmfImage"
second_title: "GroupDocs.Editor for Java API 참조"
description: "메타데이터와 추가 메서드를 포함한 향상된 메타파일 형식(EMF) 벡터 이미지를 하나 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

향상된 메타파일 형식(EMF) 벡터 이미지를 하나 나타냅니다.
메타데이터 및 추가 메서드

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | base64 인코딩된 콘텐츠에서 새로운 EmfImage 인스턴스를 생성합니다. |
문자열이며, 지정된 이름과 함께
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | 바이트 스트림으로 표현된 콘텐츠에서 새로운 EmfImage 인스턴스를 생성합니다. |
그리고 지정된 이름과 함께
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 EMF 이미지인지 확인합니다. |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 EMF 이미지인지 확인합니다. |
|
|  | [getType()](#getType--) | ImageType.Emf를 반환합니다. |
|
|  | [getByteContent()](#getByteContent--) | 이 EMF 이미지의 내용을 바이너리 스트림으로 반환합니다. |
|
|  | [getTextContent()](#getTextContent--) | 이 EMF 이미지의 내용을 일반 텍스트로 반환합니다. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | 이 EMF 이미지를 파일에 저장합니다. |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | 이 벡터 EMF 이미지를 래스터 PNG 이미지로 저장합니다. |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 이 벡터 EMF 이미지를 벡터 SVG 이미지로 저장합니다. |
|
|  | [dispose()](#dispose--) | 이 EMF 이미지의 콘텐츠를 해제하고 대부분의 |
메서드와 속성을 작동하지 않게 합니다.
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


base64 인코딩된 콘텐츠에서 새로운 EmfImage 인스턴스를 생성합니다.
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | EMF 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | base64 인코딩 문자열 형태의 콘텐츠입니다. null, 빈 문자열 또는 공백일 수 없습니다. EMF 콘텐츠가 아닌 경우 예외가 발생합니다. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


바이트 스트림으로 표현된 콘텐츠에서 새로운 EmfImage 인스턴스를 생성합니다.
그리고 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | EMF 이미지의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 EMF 이미지인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 입력 바이트 스트림입니다. NULL이 아니어야 하며 읽기와 탐색을 지원해야 합니다. |
|

**Returns:**
boolean - 지정된 스트림이 유효한 EMF 이미지를 포함하면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 EMF 이미지인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 입력 문자열로, EMF 이미지의 콘텐츠가 base64 인코딩으로 저장됩니다. NULL이거나 빈 문자열일 수 없습니다. |
|

**Returns:**
boolean - 지정된 문자열이 유효한 EMF 이미지인 경우 true, 그렇지 않으면 false

### getType() {#getType--}
```
public ImageType getType()
```


ImageType.Emf를 반환합니다.


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


이 EMF 이미지의 내용을 바이너리 스트림으로 반환합니다.


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


이 EMF 이미지의 내용을 일반 텍스트로 반환합니다.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


이 EMF 이미지를 파일에 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | 전체 파일 경로로, 이 EMF 이미지의 내용으로 파일이 존재하지 않으면 생성되고(존재하면) 기존 파일이 덮어쓰기됩니다. |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


이 벡터 EMF 이미지를 래스터 PNG 이미지로 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | 출력 스트림으로, PNG 이미지의 내용이 기록됩니다. NULL일 수 없으며 쓰기 가능해야 합니다. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


이 벡터 EMF 이미지를 벡터 SVG 이미지로 저장합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | 출력 스트림으로, SVG 이미지의 내용이 기록됩니다. NULL일 수 없으며 쓰기 가능해야 합니다. |
|

### dispose() {#dispose--}
```
public void dispose()
```


이 EMF 이미지의 콘텐츠를 해제하고 대부분의
메서드와 속성을 작동하지 않게 합니다.


