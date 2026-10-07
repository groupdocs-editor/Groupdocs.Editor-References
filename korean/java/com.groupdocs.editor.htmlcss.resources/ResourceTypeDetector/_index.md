---
title: "ResourceTypeDetector"
second_title: "GroupDocs.Editor for Java API 참조"
description: "리소스 유형 및 형식 감지를 위한 유틸리티 정적 메서드"
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.resources/resourcetypedetector/
---
**Inheritance:**
java.lang.Object
```
public class ResourceTypeDetector
```

리소스 유형(포맷)을 감지하기 위한 유틸리티 정적 메서드들

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ResourceTypeDetector()](#ResourceTypeDetector--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [detectTypeFromFilename(String filename)](#detectTypeFromFilename-java.lang.String-) | 지정된 파일 이름으로부터 유형을 감지하고 인스턴스를 반환합니다 |
해당 IResourceType
|
|  | [tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)](#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-) | 입력 스트림을 분석하려 시도하고 지원 가능한 HTML 중 하나를 생성합니다 |
그것으로부터 리소스를 생성하고, 지정된 가정 유형을 고려합니다, 만약
null이 아닌 경우
|
### ResourceTypeDetector() {#ResourceTypeDetector--}
```
public ResourceTypeDetector()
```


### detectTypeFromFilename(String filename) {#detectTypeFromFilename-java.lang.String-}
```
public static IResourceType detectTypeFromFilename(String filename)
```


지정된 파일 이름으로부터 유형을 감지하고 인스턴스를 반환합니다
해당 IResourceType


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 파일 이름 | java.lang.String | 입력 파일 이름으로, 이 메서드는 결과 IResourceType 구현을 추출하려 시도합니다 |
|

**Returns:**
[IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) - IResourceType implementation on success or NULL on failure

### tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat) {#tryDetectResource-java.io.InputStream-java.lang.String-com.groupdocs.editor.htmlcss.resources.IResourceType-}
```
public static IHtmlResource tryDetectResource(InputStream inputResourceStream, String name, IResourceType assumptiveFormat)
```


입력 스트림을 분석하려 시도하고 지원 가능한 HTML 중 하나를 생성합니다
그것으로부터 리소스를 생성하고, 지정된 가정 유형을 고려합니다, 만약
null이 아닌 경우


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | inputResourceStream | java.io.InputStream | 입력 스트림으로, 여기에는 HTML 리소스가 포함되어 있을 것으로 예상됩니다. 유효하지 않을 경우 예외가 발생합니다. |
|
|  | name | java.lang.String | 리소스 이름으로, 성공 시 생성 및 반환된 리소스에 사용됩니다. NULL, 빈 문자열 또는 공백일 수 없습니다 |
|
|  | assumptiveFormat | [IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype) | 입력 HTML 리소스의 가정 형식으로, 최상의 성능을 달성하는 데 유용합니다. 완전히 알 수 없을 경우 NULL 값을 사용하십시오. 부정확할 수 있으며, 이는 성능을 악화시킬 뿐입니다. |
|

**Returns:**
[IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) - Instance, which implements 'IHtmlResource' interface and represents one of supportable HTML resources on success, or NULL on failure

