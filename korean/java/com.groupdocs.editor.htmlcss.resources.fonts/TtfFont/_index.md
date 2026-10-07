---
title: "TtfFont"
second_title: "GroupDocs.Editor for Java API 참조"
description: "TTF TrueType Font 형식의 글꼴 하나를 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

TTF(TrueType Font) 포맷의 폰트 하나를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | 콘텐츠에서 새 TtfFont 클래스를 생성하고, base64 인코딩 형태로 표현됩니다. |
문자열이며, 지정된 이름과 함께
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | 콘텐츠에서 새 TtfFont 클래스를 생성하고, 바이트 스트림으로 표현되며, 그리고 |
지정된 이름과 함께
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | TTF 헤더 크기(바이트 단위), 검증에 필요합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | 지정된 스트림이 유효한 TTF 글꼴인지 확인합니다. |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | 지정된 base64 인코딩 문자열이 유효한 TTF 글꼴인지 확인합니다. |
|
|  | [getType()](#getType--) | FontType.Ttf를 반환합니다. |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


콘텐츠에서 새 TtfFont 클래스를 생성하고, base64 인코딩 형태로 표현됩니다.
문자열이며, 지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | TTF 글꼴의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | contentInBase64 | java.lang.String | 콘텐츠를 base64 인코딩 문자열로 제공합니다. null, 빈 문자열 또는 공백일 수 없습니다. TTF 콘텐츠가 아닌 경우 예외가 발생합니다. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


콘텐츠에서 새 TtfFont 클래스를 생성하고, 바이트 스트림으로 표현되며, 그리고
지정된 이름과 함께


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | name | java.lang.String | TTF 글꼴의 이름입니다. null, 빈 문자열 또는 공백일 수 없습니다. |
|
|  | binaryContent | java.io.InputStream | 바이트 스트림 형태의 콘텐츠입니다. 읽기는 원래 위치에서 시작합니다. null일 수 없습니다. 읽기 가능하고 탐색 가능해야 합니다. 이 인스턴스가 해제되면 해당 스트림도 해제됩니다. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


TTF 헤더 크기(바이트 단위), 검증에 필요합니다.


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


지정된 스트림이 유효한 TTF 글꼴인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | 바이트 스트림으로, TTF 리소스를 포함하고 있을 것으로 추정됩니다. |
|

**Returns:**
boolean - 지정된 스트림에 유효한 TTF 글꼴이 포함되어 있으면 true, 그렇지 않으면 false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


지정된 base64 인코딩 문자열이 유효한 TTF 글꼴인지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | 추정되는 TTF 글꼴의 콘텐츠를 base64 인코딩 문자열 형태로 제공합니다. |
|

**Returns:**
boolean - 지정된 문자열에 유효한 TTF 글꼴이 포함되어 있으면 True, 그렇지 않으면 false

### getType() {#getType--}
```
public FontType getType()
```


FontType.Ttf를 반환합니다.


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
