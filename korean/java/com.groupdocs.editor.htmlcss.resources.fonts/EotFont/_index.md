---
title: "EotFont"
second_title: "GroupDocs.Editor for Java API 참조"
description: "EOT Embedded OpenType 형식에서 하나의 글꼴을 나타냅니다"
type: docs
weight: 10
url: /ko/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

EOT(Embedded OpenType) 포맷의 폰트 하나를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | 내용을 base64-encoded 형태로 사용하여 새로운 EotFont 클래스를 생성합니다 |
문자열이며, 지정된 이름과 함께
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | 내용을 byte stream 형태로 사용하여 새로운 EotFont 클래스를 생성하고 |
지정된 이름과 함께
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | 검증에 필요한 EOT 헤더 크기(바이트) |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 EOT 글꼴인지 확인합니다 |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64-encoded 문자열이 유효한 EOT 글꼴인지 확인합니다 |
|
|  | [getType()](#getType--) | FontType.Eot을 반환합니다 |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


내용을 base64-encoded 형태로 사용하여 새로운 EotFont 클래스를 생성합니다
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | EOT 글꼴의 이름. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | 내용을 base64-encoded 문자열로 제공합니다. null, 빈 문자열 또는 공백일 수 없습니다. EOT 내용이 아닌 경우 예외가 발생합니다. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


내용을 byte stream 형태로 사용하여 새로운 EotFont 클래스를 생성하고
지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | EOT 글꼴의 이름. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


검증에 필요한 EOT 헤더 크기(바이트)


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 EOT 글꼴인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 바이트 스트림으로, 추정컨대 EOT 리소스를 포함하고 있습니다 |
|

**Returns:**
boolean - 지정된 스트림에 유효한 EOT 글꼴이 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64-encoded 문자열이 유효한 EOT 글꼴인지 확인합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 추정되는 EOT 글꼴의 내용을 base64 인코딩 문자열 형태로 |
|

**Returns:**
boolean - 지정된 문자열에 유효한 EOT 글꼴이 포함되어 있으면 true, 그렇지 않으면 false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Eot을 반환합니다


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
