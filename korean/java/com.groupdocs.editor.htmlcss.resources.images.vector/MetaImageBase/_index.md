---
title: "MetaImageBase"
second_title: "GroupDocs.Editor for Java API 참조"
description: "WMF 및 EMF 이미지 형식에 대한 기본 추상 클래스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

WMF 및 EMF 이미지 형식에 대한 기본 추상 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | 공통 생성자, WMF 또는 EMF 인스턴스를 생성하기 위해 준비합니다 |
base64 인코딩된 문자열
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | 공통 생성자, WMF 또는 EMF 인스턴스를 생성하기 위해 준비합니다 |
바이트 스트림
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | 지정된 바이트 스트림에 유효한 WMF 이미지가 포함되어 있는지 확인합니다 |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | 지정된 문자열에 유효한 WMF 이미지가 포함되어 있는지 확인합니다, 이는 |
base64으로 인코딩된
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | 지정된 바이트 스트림에 유효한 EMF 이미지가 포함되어 있는지 확인합니다 |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | 지정된 문자열에 유효한 EMF 이미지가 포함되어 있는지 확인합니다, 이는 |
base64으로 인코딩된
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | 구현 유형은 현재 벡터 메타 이미지를 다음에 저장해야 합니다 |
지정된 바이트 스트림에 벡터 SVG 형식으로
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


공통 생성자, WMF 또는 EMF 인스턴스를 생성하기 위해 준비합니다
base64 인코딩된 문자열


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 필수 이름 |
|
|  | contentInBase64 | java.lang.String | base64 문자열 형태의 콘텐츠. NULL이 아니고 비어 있지 않아야 합니다. |
|
|  | isWmf | boolean | WMF는 true, EMF는 false |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


공통 생성자, WMF 또는 EMF 인스턴스를 생성하기 위해 준비합니다
바이트 스트림


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | 필수 이름 |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠. 유효해야 합니다. |
|
|  | isWmf | boolean | WMF는 true, EMF는 false |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


지정된 바이트 스트림에 유효한 WMF 이미지가 포함되어 있는지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 입력 바이트 스트림. 유효해야 합니다. |
|

**Returns:**
boolean - 유효하면 'true'를 반환하고, 유효하지 않으면 'false'를 반환합니다

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


지정된 문자열에 유효한 WMF 이미지가 포함되어 있는지 확인합니다, 이는
base64으로 인코딩된


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | base64 인코딩된 WMF 이미지를 포함하고 있다고 가정되는 문자열 |
|

**Returns:**
boolean - 유효하면 'true'를 반환하고, 유효하지 않으면 'false'를 반환합니다

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


지정된 바이트 스트림에 유효한 EMF 이미지가 포함되어 있는지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 입력 바이트 스트림. 유효해야 합니다. |
|

**Returns:**
boolean - 유효하면 'true'를 반환하고, 유효하지 않으면 'false'를 반환합니다

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


지정된 문자열에 유효한 EMF 이미지가 포함되어 있는지 확인합니다, 이는
base64으로 인코딩된


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | String, base64 인코딩된 EMF 이미지를 포함하고 있다고 가정되는 문자열 |
|

**Returns:**
boolean - 유효하면 'true'를 반환하고, 유효하지 않으면 'false'를 반환합니다

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


구현 유형은 현재 벡터 메타 이미지를 다음에 저장해야 합니다
지정된 바이트 스트림에 벡터 SVG 형식으로


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | 바이트 스트림으로, 이 벡터 메타 이미지의 SVG 버전이 저장됩니다. NULL이 아니어야 하며 쓰기를 지원해야 합니다. |
|

